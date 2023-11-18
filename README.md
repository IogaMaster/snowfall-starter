<h1 align="center"> <img src="./.github/assets/flake.webp" width="250px"/></h1>
<h2 align="center">My NixOS flake template made with <a href="https://github.com/snowfallorg/lib">snowfall</a>.</h2>

<h1 align="center">
<a href='#'><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/palette/macchiato.png" width="600px"/></a>
  <br>
  <br>
  <div>
    <a href="https://github.com/Iogamaster/snowfall-starter/issues">
        <img src="https://img.shields.io/github/issues/Iogamaster/snowfall-starter?color=fab387&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/Iogamaster/snowfall-starter/stargazers">
        <img src="https://img.shields.io/github/stars/Iogamaster/snowfall-starter?color=ca9ee6&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/Iogamaster/snowfall-starter">
        <img src="https://img.shields.io/github/repo-size/Iogamaster/snowfall-starter?color=ea999c&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/Iogamaster/snowfall-starter/blob/main/.github/LICENCE">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=ca9ee6&colorA=313244&colorB=cba6f7"/>
    </a>
    <br>
    </div>
        <img href="https://builtwithnix.org" src="https://builtwithnix.org/badge.svg"/>
   </h1>
   <br>

## My system management tool `sys`

`sys` is a bash script I made that makes working with NixOS easier.

Rebuild (in flake directory)

```sh
sudo sys rebuild # or `r` as a shorthand
```

Testing an ephemeral config:

```sh
sudo sys test # or `t` as a shorthand
```

Deploying to a server (in flake directory):

```sh
sudo sys deploy HOSTNAME # or `d` as a shorthand
```
