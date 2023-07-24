# One post per year

The one-post-per-year theme is an extremely lightweight theme for [Hugo](https://gohugo.io). It's built with simplicity and speed in mind.

🌏 [Demo site](https://jpanther.github.io/congo/)  
🐛 [Bug reports & issues](https://github.com/jarv/one-post-per-year/issues)

## Features
| Feature | One post a year | A good typical good theme for productive bloggers |
| --- | --- | --- |
| Support for links, text, tables, [GOAT diagrams](https://gohugo.io/content-management/diagrams/) and everything Hugo supports out-of-the-box | ✔️ | ✔️ | 
| Automatic image resizing using Hugo Pipes | ✔️ | ✔️ | 
| HTML and Emoji support in articles 🎉 | ✔️ | ✔️ | 
| Optimised for performance and accessibility with perfect Lighthouse scores | ✔️ | ✔️ | 
| RSS feeds that show the full article | ✔️ | ✔️ | 
| Fully responsive layout | ✖️ | ✔️ |
| Multiple colour schemes | ✖️ | ✔️ |
| Dark mode | ✖️ | ✔️ |
| Highly customisable configuration | ✖️ | ✔️ |
| Multiple homepage layouts | ✖️ | ✔️ |
| Flexible with any content types, taxonomies and menus | ✖️ | ✔️ |
| Multilingual support | ✖️ | ✔️ |
| Client-side site search | ✖️ | ✔️ |
| Diagrams using Mermaid |  ✖️ | ✔️ |
| Charts and math notation |  ✖️ | ✔️ |
| Anything having to do with FontAwesome | ✖️ | ✔️ |
| Any type of links for sharing to social media |  ✖️ | ✔️ |
| Anything having to do with Analytics or Google Analytics |  ✖️ | ✔️ |
| Comments support |  ✖️ | ✔️ |


---

## Documentation

Congo has [extensive documentation](https://jpanther.github.io/congo/docs/) that covers all aspects of the theme. Be sure to [read the docs](https://jpanther.github.io/congo/docs/) to learn more about how to use the theme and its features.

---

## Installation

Congo supports several installation methods - as a Hugo Module (easiest), a git submodule, or as a completely manual install.

Detailed instructions for each method can be found in the [Installation](https://jpanther.github.io/congo/docs/installation) docs. You should consult the documentation for the simplest setup experience. Below is a quick start guide using Hugo modules if you're already confident installing Hugo themes.

### Quick start using Hugo

> **Note:** Ensure you have **Go** and **Hugo** installed, and that you have created a new Hugo project before proceeding.

1. From your project directory, initialise Hugo Modules:

   ```shell
   hugo mod init github.com/<username>/<repo-name>
   ```

2. Create `config/_default/module.toml` and add the following:

   ```toml
   [[imports]]
   path = "github.com/jpanther/congo/v2"
   ```

3. Start your server using `hugo server` and the theme will be downloaded automatically.

4. In the root folder of your website, delete the `config.toml` file that was generated by Hugo. Copy the `*.toml` config files from the theme into your `config/_default/` folder.

   > **Note:** Do not overwrite the `module.toml` file you created above!

   You will find these theme config files in the Hugo cache directory, or [download a copy](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/jpanther/congo/tree/stable/config/_default) from GitHub.

5. Follow the [Getting Started](https://jpanther.github.io/congo/docs/getting-started/) instructions to configure your website.

### Installing theme updates

As new releases are posted, you can update the theme using Hugo. Simply run `hugo mod get -u` from your project directory and the theme will automatically update to the latest release.

Detailed [update instructions](https://jpanther.github.io/congo/docs/installation/#installing-updates) are available in the docs.

---

## Contributing

Congo is expected to evolve over time. I intend to keep adding features and making changes as required.

Feel free to get in touch with any issues or suggestions for new features you'd like to see.

- 🐛 **Bug reports & issues:** Use [GitHub Issues](https://github.com/jpanther/congo/issues)
- 💡 **Ideas for new features:** Open a discussion on [GitHub Discussions](https://github.com/jpanther/congo/discussions)
- 🙋‍♀️ **General questions:** Head to [GitHub Discussions](https://github.com/jpanther/congo/discussions)

If you're able to fix a bug or implement a new feature, I welcome PRs for this purpose. Learn more in the [contributing guidelines](https://github.com/jpanther/congo/blob/dev/CONTRIBUTING.md).
