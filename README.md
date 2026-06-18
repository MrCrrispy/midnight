# Midnight Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/midnight.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/midnight)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)

> The Midnight Theme by Marcel Hoffs

## Screenshots

### Home

![Theme - Overview](.docs/demo_midnight.png)

### Profile

![Theme - Profile](.docs/profile_midnight.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Midnight`.
3. Navigate to `Midnight` theme.
4. Press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/home-assistant-community-themes/midnight.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/home-assistant-community-themes/midnight.git
```
