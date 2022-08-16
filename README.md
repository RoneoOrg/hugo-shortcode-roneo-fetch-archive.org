

A Hugo shortcode to retrieve data from archive.org

## Usage

    {{< fetch src="https://archive.org/metadata/e-kreiz-an-noz" >}}

## Screenshot

A file list is created [from the JSON provided by archive.org](https://archive.org/metadata/e-kreiz-an-noz):


<div align="center">

![Screenshot of the Shortcode in action](https://raw.githubusercontent.com/RoneoOrg/hugo-shortcode-roneo-fetch-archive.org/main/img/screenshot.jpg)

</div>

It's possible to filter displayed files, and append a media player to audio files.


## Installation

Requires **Hugo > 0.42**


Install as a Git submodule:

    git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-fetch-archive.org.git themes/hugo-shortcode-roneo-fetch-archive.org

Edit `config.toml`:

    theme = ["hugo-shortcode-roneo-fetch-archive.org", "YourCurrentTheme"]
    enableInlineShortcodes = true

To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo-modules/theme-components/)

## Contribute

Code contributions are welcome. The main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-fetch-archive.org) and you can use [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-fetch-archive.org) too.

## References

- [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)
