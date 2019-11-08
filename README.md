# Treeshaking components' CSS

Experiment with `rollup-plugin-svelte` ([fork](https://github.com/rollup/rollup-plugin-svelte/compare/master...rixo:treeshake-css?expand=1)): remove CSS of treeshaken components.

## Usage

~~~bash
npx degit rixo/template#treeshake-hmr demo
cd demo
npm install
npm run build

# see
cat public/bundle.css
~~~
