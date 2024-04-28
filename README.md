# Vitest Repro

1. `pnpm install`
1. `code test/the.test.js`
1. Set breakpoint at line 3 of the test file
1. Start debugging session using 'Debug - vitest' configuration
1. Wait for debugger to attach
1. Press 'Step into' until you're in `add` function implementation
1. Press 'Step over' and see that debugger highlights invalid line

# How it should work

1. `pnpm install`
1. `code test/the.test.js`
1. Set breakpoint at line 3 of the test file
1. Start debugging session using 'Debug - node' configuration
1. Wait for debugger to attach
1. Press 'Step into' until you're in `add` function implementation
1. Press 'Step over' and see that debugger highlights invalid line
