![](imgs/logo/consentua-logo-colour.png)
# [consentua.com](http://consentua.com/)
Development for Consentua.com website

See live version at [consentua.com](http://consentua.com/)

## Pages

* `/index.html`
* `/contact.html`
* `/pricing.html`
* `/privacy-policy.html`
* `/privacy-policy-cont.html`
* `/404.html`

> Dashboard is located at [app.consentua.com](https://app.consentua.com/)

## Dependencies / Libraries

All libraries (with exceptions of fonts and icons) are stores locally in either `js/lib` or `styles/lib`


### Scripts
* [Fingerprint2JS](http://scrollmagic.io/) - for ga tracking without cookies

### Styles
* [normalize.css](https://necolas.github.io/normalize.css/) - for rendering all elements more consistently across browsers

## Look and Feel

### Fonts

* [Open Sans](https://fonts.google.com/selection?selection.family=Open+Sans|Raleway) (Medium)- Main font used for text
* [Raleway](https://fonts.google.com/selection?selection.family=Open+Sans|Raleway) (Medium) - Font used for Headings and nav
* [fontawesome 5](http://fontawesome.com/) ver 5 - for icons

### Colours


![](https://coolors.co/export/png/212121-7f0e38-9a1144-e1e1e1-FFC021)

* Main: #9A1144 (154,17,68)
* Secondary: #A42856 (164,40,86)
* Highlight: #FFC021
* Red (error/danger): #F44336
* Green (ok/success): #4CAF50
* Text: #212121 / #FFF
* Whites: #FFF, #F6F6F6
* Greys: #c7c7c7, #d4d4d4, #e1e1e1, #eeeeee
* Darks: #212121, #373737, #000

## Development

To develop on consentua.com:

Clone or fork this repo,
make sure you have ruby and jekyll installed on your machine, and run:

install dependencies:
` gem install -g `

and serve: 
```
$ bundle exec jekyll serve
# => A development server will run at http://localhost:4000/
# Auto-regeneration: enabled. Use `--no-watch` to disable.
```

## How do I deploy?

To deploy, just commit and push your changes to github pages (master branch of this repo).