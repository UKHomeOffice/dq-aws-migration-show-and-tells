# DQ AWS Migration Show and Tells
This repo contains the slides for DQ AWS Migration Show and Tells, produced with prez/revealjs.

## Viewing the slides
### Viewing published slide deck
[Published slide deck available here](http://dq-aws-show-tell.notprod.homeoffice.gov.uk)
[Published PDF slide deck available here](http://dq-aws-show-tell.notprod.homeoffice.gov.uk/slides.pdf)

### Running as a server with docker
```
docker build -t dq-show-tell . 
docker run -ti -p 9000:80 dq-show-tell
```

## Editing the slides
### Pre-requisites
You must have node version 6+ installed. You can install the dependencies with:
```
npm install
```

### Editing the slides
```
npm start
```
This will serve the slides from [http://localhost:9000](http://localhost:9000) and open it in your browser.
These will be reloaded automatically when changes are made to the slides.
It will also update pdf versions of the slides as you make edits.

Edit the slides in the **slides** folder.


## Presentation mode
If you're presenting you can syncronise everyone else's screen, in your browser console do:
```js
Cookies.set("secret", "[insert secret")
```
> Get the secret from @chrisns