<h1 align="center">Chicago 7</h1>
<p align="center">Embracing the power of less</p>
<p align="center"><a href="https://akop.dev/hugo-theme-chicago7">Live Demo</a></p>


[![Chicago7](https://img.shields.io/badge/Hugo--Themes-@Chicago7-blue)](https://themes.gohugo.io/themes/hugo-theme-chicago7/)
[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=>=v0.90.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.146.0)
[![GitHub](https://img.shields.io/github/license/adityatelange/hugo-PaperMod)](https://github.com/akopdev/hugo-theme-chicago7/blob/main/LICENSE)

![Chicago7 Hugo Theme](https://github.com/akopdev/hugo-theme-chicago7/blob/main/images/tn.png)

![Chicago7 Hugo Theme](https://github.com/akopdev/hugo-theme-chicago7/blob/main/images/screenshot.png)

## Features
- Minimalistic and lightweight color scheme built with [PicoCSS](https://picocss.com/). No JavaScript or complicated tooling.
- Fully responsive design, prioritizing semantic HTML.
- Monospaced font with a nostalgic System 7 vibe, inspired by the classic Chicago typeface.
- Light and Dark mode support.
- Easy to customize and extend.

## How to start

The easiest way is to download the theme from GitHub and copy it into `themes/chicago7`, or clone it directly using Git.

```sh
git submodule add https://github.com/akopdev/hugo-theme-chicago7.git themes/chicago7
```

### Install as a Hugo Module

You can also install the theme as a Hugo module. Keep in mind that, by default, the theme will not appear in the themes directory. 
This means you’ll be using the version of the theme exactly as it exists in the repository at the time you fetch it.

Add theme link to `hugo.toml` file:

```toml
theme = ['github.com/akopdev/hugo-theme-chicago7']
```

Although specifying modules in the theme array works fine, you have more control if you explicitly import the theme as a module:

```toml
[module]
[[module.imports]]
path = 'github.com/akopdev/hugo-theme-chicago7'
```
Then, to load/update the theme module and run hugo:

```sh
hugo mod get -u
hugo server --minify
```

### Example of creating site from scratch

Below is an example on how to create a new site from scratch:

```sh
hugo new site my-blog
cd my-blog
hugo mod init github.com/<username>/my-blog
echo "theme = ['github.com/akopdev/hugo-theme-chicago7']" >> hugo.toml
hugo server
```


## How to configure

There are a few configuration options that you can add to your `hugo.toml` file.
Check [example site](exampleSite/hugo.toml) for more info.

*Supported social media links*:

- Behance  
- Dribbble 
- Facebook 
- Feed     
- Gplus    
- Instagram
- Linkedin 
- Pinterest
- Soundcloud
- Vimeo    
- Twitter        
- Youtube  
