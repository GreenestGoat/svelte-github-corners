# svelte-github-corners

[![NPM Downloads](https://img.shields.io/npm/dm/svelte-github-corners.svg?style=flat)](https://www.npmjs.com/package/svelte-github-corners)
[![npm version](https://img.shields.io/npm/v/svelte-github-corners.svg)](https://www.npmjs.com/package/svelte-github-corners)
[![MIT License](https://img.shields.io/github/license/GreenestGoat/svelte-github-corners.svg?color=red)](https://github.com/GreenestGoat/svelte-github-corners/blob/main/LICENSE)

Add a Github corner to your project page

Preview Example: [Svelte Playground](https://svelte.dev/playground/9ef4eab2103c4c829c359be1f8f7c274?version=5.28.2s)

## Installation

Add `svelte-github-corners` to your project:

```bash
npm i -D svelte-github-corners
```

## Usage

```svelte
<script>
  import { GitHubCorners } from 'svelte-github-corners';
</script>

<GitHubCorners position="top-right" href="https://github.com/GreenestGoat/svelte-github-corners" />
```

## Svelte Props

| Property Name | Type   | Default Value                                       | Description                          |
| ------------- | ------ | --------------------------------------------------- | ------------------------------------ |
| href          | String | -                                                   | The link to your project page.       |
| size          | String | `80`                                                | The width and height of the corner.  |
| bgColor       | String | `#151513`                                           | The background color of the corner.  |
| color         | String | `#fff`                                              | The Github logo color of the corner. |
| position      | String | `top-left`/`top-right`/`bottom-left`/`bottom-right` | The position of corner.              |

## Development

```bash
git clone https://github.com/GreenestGoat/svelte-github-corners.git
cd svelte-github-corners
npm install
npm run dev -- --open
```

## Contributors

Contributions are welcome! Please feel free to Fork the project and submit a Pull Request.

<a href="https://github.com/GreenestGoat/svelte-github-corners/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GreenestGoat/svelte-github-corners" />
</a>

## License

Licensed under the MIT License.
