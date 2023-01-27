# Xliffmerge

Xliffmerge serves as a library containing some tools for i18n workflows in Angular.

The two main use cases are 
- Transforming .xlf files to .json
- Translating keys to target languages using Google Translate API

## About this package
The [original package](https://github.com/martinroob/ngx-i18nsupport) had a bigger scope, but is no longer actively maintained. For the extraction of i18n phrases to `.xlf` format, [ng-extract-i18n-merge](https://github.com/daniel-sc/ng-extract-i18n-merge) can be used. 
This package uses the simplified project and build structure by [PeerTube](https://github.com/Chocobozzz/ngx-i18nsupport).

## Usage

In your root directory you will need a `xliffmerge.json` file with your settings. Possible settings can be found at [the original package](https://github.com/martinroob/ngx-i18nsupport/tree/master/projects/xliffmerge#usage)

You can integrate `xliffmerge` in your i18n script. Keep in mind that xliffmerge expects `.xlf` files to be in your `srcDir` specified in your `xliffmerge.json`:

```xliffmerge --profile xliffmerge.json```
