<h1 align="center">Chicago 7</h1>
<p align="center">Embracing the power of less</p>
<p align="center"><a href="https://akop.dev/hugo-theme-chicago7">Live Demo</a></p>

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
git clone https://github.com/akopdev/hugo-theme-chicago7.git  themes/chicago7
```

### Install as a Hugo Module

You can also install the theme as a Hugo module. Keep in mind that, by default, the theme will not appear in the themes directory. 
This means you’ll be using the version of the theme exactly as it exists in the repository at the time you fetch it.

```sh
hugo mod get github.com/akopdev/hugo-theme-chicago7
```

and in your config file add:

```toml
[module]
[[module.imports]]
  path = 'github.com/akopdev/hugo-theme-chicago7'
```

## How to configure

The theme doesn't require any advanced configuration. Just copy to your `config.yaml`:

```yaml
markup:
  highlight:
    style: "bw"

menu:
  header:
  - name: "About"
    url: "about"
    weight: 40

  - name: "Posts"
    url: "posts"
    weight: 30

  - name: "Projects"
    url: "projects"
    weight: 20

  - name: "Home"
    url: "/"
    weight: 10

params:
  author: "Your Name"
  social:
    twitter: https://x.com/example
    behance: "https://behance.net/yourprofile"
    facebook: "https://facebook.com/yourprofile"
```

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
