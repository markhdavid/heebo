# Heebo Build Instructions

## Prerequisits

Need `fontmake`:
- see https://github.com/googlefonts/fontmake
- usually do: pip install fontmake

Need `gftools`:
- https://github.com/googlefonts/gftools
- usually do: pip install gftools

## To build:
- From repo top level, do
    1. `cd sources`
    1. ./build.sh
    
## Expected changes

Upon successful build, the following files should show as files to commit, with each paths relative to repo top level:

- fonts/otf/Heebo-Black.otf
- fonts/otf/Heebo-Bold.otf
- fonts/otf/Heebo-ExtraBold.otf
- fonts/otf/Heebo-Light.otf
- fonts/otf/Heebo-Medium.otf
- fonts/otf/Heebo-Regular.otf
- fonts/otf/Heebo-Thin.otf
- fonts/ttf/Heebo-Black.ttf
- fonts/ttf/Heebo-Bold.ttf
- fonts/ttf/Heebo-ExtraBold.ttf
- fonts/ttf/Heebo-Light.ttf
- fonts/ttf/Heebo-Medium.ttf
- fonts/ttf/Heebo-Regular.ttf
- fonts/ttf/Heebo-Thin.ttf
- fonts/variable/Heebo[wght].ttf
