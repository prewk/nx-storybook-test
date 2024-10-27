This repo is a reproduction of a bug: Whenever you add a `workspace-configuration` with `nx`, It installs React.

Clone this, then run `npx nx g @nx/angular:storybook-configuration foo`.

`nx` will now have installed `react` and `react-dom`.