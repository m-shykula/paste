# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.0.1](https://github.com/twilio-labs/paste/compare/@twilio-paste/input@1.0.0...@twilio-paste/input@1.0.1) (2020-02-14)


### Bug Fixes

* **input:** add missing peer deps ([502e03d](https://github.com/twilio-labs/paste/commit/502e03dca237f5f2250c3167425a8f87de2a3fde))





# [1.0.0](https://github.com/twilio-labs/paste/compare/@twilio-paste/input@0.2.0...@twilio-paste/input@1.0.0) (2019-11-11)


### Features

* **icons:** delete old icons, add new streamline icons ([#129](https://github.com/twilio-labs/paste/issues/129)) ([571791d](https://github.com/twilio-labs/paste/commit/571791ded8ee4c55bb5a3dbcebee4b17b2c7c826))


### BREAKING CHANGES

* **icons:** removed all the inherited icons since we're moving to a new system

* chore(icons): update icon list for storybook

* fix(spinner): use new icon

* fix(storybook): use new icon for story

* fix(story): button icons should be 24px

* fix: adjust icon size tokens

* feat: add iconSizes as separate key in theme-tokens

* feat(icons): icons package to use tokens and update icons

* fix(spinner): update to use tokens and new icons

* fix(button): use correct spinner size

* fix(icons): major icons package fixes

- huge overhaul to build process
- now uses rollup
- builds into cjs and esm directories
- made the package publishable to npm
- moved svg folder out of src, now src only holds react stuff
- updated scripts to use new paths and cleaned up the code
- programmatically generates rollup config from the icon-list command

* chore: add new icons dist folders to gitignore

* fix: spinner and button icon usage

* feat(icons): add rollup icon list cache file

* fix(core-bundle): sort packages for consistent builds

* chore: use `esm` instead of `es` in rollup for correctness

* chore: yarn.lock

* fix(spinner): lint error

* chore(icons): move rollup icon list

* chore(spinner): use types package in story

* fix(spinner): swap out destructured props for explicit props





# [0.2.0](https://github.com/twilio-labs/paste/compare/@twilio-paste/input@0.1.4...@twilio-paste/input@0.2.0) (2019-10-29)


### Features

* upgrading to styled-system v5 ([#18](https://github.com/twilio-labs/paste/issues/18)) ([2b3ebd8](https://github.com/twilio-labs/paste/commit/2b3ebd8b2f701a0c6e8b75ab6978ba936814f455))





## [0.1.4](https://github.com/twilio-labs/paste/compare/@twilio-paste/input@0.1.3...@twilio-paste/input@0.1.4) (2019-09-16)

**Note:** Version bump only for package @twilio-paste/input





## 0.1.3 (2019-08-15)


### Bug Fixes

* change [@paste](https://github.com/paste) scope to [@twilio-paste](https://github.com/twilio-paste) ([#2](https://github.com/twilio-labs/paste/issues/2)) ([1d8d2ff](https://github.com/twilio-labs/paste/commit/1d8d2ff))
