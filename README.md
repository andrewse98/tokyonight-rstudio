# Tokyonight Theme [RStudio](https://www.rstudio.com/)

A custom RStudio theme inspired by [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) by folke.

## Motivation

I am a researcher who primarily uses RStudio for coding and analysis.
While I enjoy the aesthetics of the tokyonight theme in neovim, I could not find a version for RStudio.
So, I created one as a personal project.

> [!NOTE]
> I have only finished the colorscheme for 'Tokyonight Storm'. In the next iteration, I will work on other flavor as well.
>
> I am still a beginner at programming, css, and in the architecture of Rstudio, so this process may take a while.
> Pretty sure there is a faster way to do this with `lua` or `r` (e.g., [rsthemes](https://github.com/gadenbuie/rsthemes/tree/main))
> If anyone is familiar with any of the above, I'd be happy to learn from you.

## Installation

### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/andrewse98/tokyonight-rstudio.git

### Activating theme

From RStudio click Preferences, Appearance, Add, and then navigate to the rstheme for the theme that you'd like to install. Click apply.

If you're comfortable installing from the console and have [Devtools](https://github.com/r-lib/devtools) installed then you can copy and run the following in your console:

```r
rstudioapi::addTheme("https://raw.githubusercontent.com/andrewse98/tokyonight-rstudio/master/storm.rstheme", apply = TRUE)
```

## Acknowledgements

- This repo is a fork of the [Dracula RStudio Theme](https://github.com/dracula/rstudio).
- Theme inspired by [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) by folke.
- Code structure inspired by [rsthemes](https://github.com/gadenbuie/rsthemes/tree/main).
- RStudio custom theme [documentation](https://rstudio.github.io/rstudio-extensions/rstudio-theme-creation.html) .
- Thanks to the RStudio community for making custom themes possible.

## License

[MIT License](./LICENSE)
