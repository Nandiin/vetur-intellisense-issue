0. Open this directory in Visual Studio Code with Vetur installed.
1. Hover over the `a` variable in `index.ts` file. There would be a popover widget indicating `a` is of type `Foo`
2. Hover over the `a` variable in `index.vue` file. There would be a popover widget indication `a` is of type `any`, which is WRONG.
3. In `index.ts` file, type in `a.`, then a popover shows and says there is a `prop` property of type `number` under variable `a`
4. Repeat step 3 inside `index.vue` and there would be no popover.
