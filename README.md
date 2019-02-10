# hugo-theme-basic

Basic personal site theme styled with minimal tachyons.

## Features

- ✨ Basic — HTML with a dash of style + emojis stand out more
- 🌯 Extensible — Easily leverage [tachyons](https://tachyons.io/components/) to spice it up

## Getting started

### Installation

Run this command from the root of your Hugo directory (Git needs to be installed):

```
$ git clone https://github.com/siegerts/hugo-theme-basic.git
```

Or, if your Hugo site is already in git, you can include this repository as a git submodule. This makes it easier to update this theme. For this you need to run:

```
$ git submodule add https://github.com/siegerts/hugo-theme-basic.git themes/hugo-theme-basic
```

Alternatively, if you are not familiar with git, you can download the theme as a .zip file, unzip the theme contents, and then move the unzipped source into your themes directory.

For more information, read the official [documentation](https://gohugo.io/themes/installing-and-using-themes) of Hugo.

### Configuration

Take a look at the sample `config.toml`file located in the `exampleSite` folder. You can just copy the `config.toml` to the root directory of your Hugo site. There are instructions in the example configuration file, feel free to change strings as you like to customize your website.

#### Content Types

**Post**
<br />
Used for blog posts. Posts are listed on the `/blog` page. Run `hugo new post/<post-name>.md` to create a post.
<br />

**Page** _Optional_
<br />
Used for site pages. Run `hugo new page/<page-name>.md` to create a page.
<br />

**Project** _Optional_
<br />
Used for project pages. Extend project list with `/layouts/section/project.html`. Run `hugo new project/<project-name>.md` to create a page.
<br />

#### Menu

Menu links are specified, in order, in the theme configuration.

For example:

```toml
[[params.menu]]
  name = "blog"
  url = "blog/"


[[params.menu]]
  name = "about"
  url = "page/about"

```

## Acknowledgments

- [tachyons](http://tachyons.io/)

## License

The code is available under the [MIT license](https://github.com/siegerts/hugo-theme-basic/blob/master/LICENSE).
