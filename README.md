# Quick Pixels Theme

Simple theme with opinionated styles.  Requires the [Base theme](https://github.com/toughpixels/base).

# Project Start

Make a GitHub repo with the name of the client's site, we're using the example `website`.
- `hugo new site website`  
- `cd website`
- `git init`
If you have access and want to edit quick pixels as you devlop, try this
- `git submodule add git@github.com:toughpixels/quick-pixels.git themes/quick-pixels`
If you're using public access to quick pixels, use this
- `git submodule add https://github.com/toughpixels/quick-pixels.git themes/quick-pixels`
- Copy the example site to your project directory: `cp -r themes/quick-pixels/exampleSite/* .`

You'll also need the base theme:
`git submodule add https://github.com/toughpixels/base.git themes/base`

## Editing Quick Pixels

To run a preview site for the theme, run
* `cd exampleSite/`
* `hugo serve --themesDir ../..`

## Cloning an Existing Project

To clone the submodule code for an exisitng project, run:
`git clone --recurse-submodules git://github.com/toughpixels/SITE.git`

Or, if you've already cloned the repo, run commands to pull and start submodule.
`git submodule update --init`


## Updating a Submodule
Simply run `git submodule update` to get the latest version.

You can also: 
```
cd themes/quick-pixels
git pull
```

Thanks to [Victoria Drake](https://github.com/victoriadrake/hugo-theme-introduction) for the amazing model.
