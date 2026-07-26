# Personal Website

This GitHub website use [Chirpy theme](https://chirpy.cotes.page/) with some minor modifications.

## Features
- Auto reload after changes
- Experiences list in `_tabs/about.md`
- Image grid
- Allow emoji

# Development

Using `devpod` to create the devcontainer environment

```sh
devpod up . --devcontainer-path .devcontainer/devcontainer.json --ide=none --id=khangtpham25 
```

`ssh` into the devcontainer

```sh
ssh khangtpham25.devpod
```

Inside the container, test run the website

```sh
bundle exec jekyll serve
```

## TODO
- [ ] Add logos of skills (might be too much ?)
