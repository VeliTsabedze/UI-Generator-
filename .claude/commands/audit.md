Your goal is to update vulnerable dependencies.

This audit command does three things:
1. Run `npm audit` to find vulnerable installed packages
2. Run `npm audit fix` to apply updates
3. Run tests to verify the updates didn't break anything