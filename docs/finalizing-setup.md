# Finalizing Setup

While the script will get you most of the way there, some setup remains. To
get things _just right_, follow these steps. You can even copy this file
to create an easy checklist.

## Neovim

- [ ] Open `neovim` and let lazy.nvim install plugins.
- [ ] Configure the AI plugin (see `nvim/lua/config/ai.lua.sample` in the
      dotfiles).

## Alfred

- [ ] Disable command + space triggering spotlight search.
- [ ] Configure command + space to trigger Alfred.
- [ ] (Ensure Alfred will start on launch.)

## Karabiner

- [ ] Open Karabiner and allow input monitoring. (If Karabiner doesn’t
      show up in the Privacy tab, check out the GitHub issues below for
      a workaround.)

- https://github.com/pqrs-org/Karabiner-Elements/issues/3011
- https://github.com/pqrs-org/Karabiner-Elements/issues/1867

## Zen

- [ ] Make default browser.
- [ ] Use duckduckgo.
- [ ] Remove everything but search bar from new tab page.

### Configure Zen Extensions

- [ ] Bitwarden (allow in private tabs)
- [ ] AdBlocker Ultimate (allow in private tabs)
- [ ] Blocksite (block youtube.com, do not allow in private tabs)

## Configure iTerm

- [ ] Profiles > Text > Use Fira Code Nerd Font as Font
- [ ] Profiles > Text > unselect bold
- [ ] Profiles > Window > put transparency to ~ 16
- [ ] Profiles > Window > put blur to ~ 51
- [ ] Appearance > General > Theme > use dark theme
- [ ] Send text at start: tmux
- [ ] open the `.itermcolors` file to get desired theme

## Rectangle

- [ ] Configure to start at login.
- [ ] Set up to use vimlike keybindings (control + option +) hjkl for left, down, up, right, and i top right u top left m bottom left , bottom
      right

## Organizer

- [ ] Clone organizer directory.

## Bitwarden

- [ ] Log in to Bitwarden.

## Todo.txt CLI

- [ ] Point CLI to proper location.

## Hidden Bar

- [ ] Set to start on login.
- [ ] Set to use full menu bar.
