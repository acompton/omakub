This is the hacky customization of Omakub I use. It is **not tested**, 
**not supported**, and **highly unlikely to succeed** in provisioning 
a clean Ubuntu install. Use it at your own risk!

Summary of differences, probably not exhaustive:

| Standard Omakub | My preference |
| --------------- | ------------- |
| alacritty       | ghostty       |
| bash            | zsh           |
| chrome          | chromium      |
| zellij          | tmux          |
| tactile         | ubuntu tiling |
| Hey             | (omit)        |
| Basecamp        | (omit)        |
| Typora          | (omit)        |
| Docker          | (omit)        | 

### TODO
Some gaps in case I ever decide to come back to this.
* Install tmux, ghostty, podman. This currently assumes they are already present.
* Add ghostty theme support
* Add tmux theme support
* Actually test

# Omakub

Turn a fresh Ubuntu installation into a fully-configured, beautiful, and modern web development system by running a single command. That's the one-line pitch for Omakub. No need to write bespoke configs for every essential tool just to get started or to be up on all the latest command-line tools. Omakub is an opinionated take on what Linux can be at its best.

Watch the introduction video and read more at [omakub.org](https://omakub.org).

## Contributing to the documentation

Please help us improve Omakub's documentation on the [basecamp/omakub-site repository](https://github.com/basecamp/omakub-site).

## License

Omakub is released under the [MIT License](https://opensource.org/licenses/MIT).

## Extras

While omakub is purposed to be an opinionated take, the open source community offers alternative customization, add-ons, extras, that you can use to adjust, replace or enrich your experience.

[⇒ Browse the omakub extensions.](EXTENSIONS.md)
