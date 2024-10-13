# Official Website of Birendra Open Source Club

Made possible with the contributions of the BOSC community. 🚀

## Project Structure

The project is built using Astro.js and Tailwind CSS. Here's a quick look at the project structure:

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

Also, make sure that Prettier is installed in your text editor. Add this to your settings.json in VS Code, as Prettier alone will not format Astro files correctly. You need this additional formatter for Astro. The npm plugins are taken care with devDependencies you don't have to worry about that.

`{
  "prettier.documentSelectors": ["**/*.astro"],
  "[astro]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}`

You can also run this command for installing the extension. Open up the terminal in vscode and paste this line .

`ext install astro-build.astro-vscode`

## 👀 Want to contribute?

Feel free to check [Contribution Methods](CONTRIBUTING.md).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 🙏 Acknowledgements

## 🌟 Resources

- [Astro documentation](https://docs.astro.build).
  - `npm run astro ...` Run CLI commands like `astro add`, `astro check`
  - `npm run astro -- --help` Get help using the Astro CLI
