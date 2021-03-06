# Convert Standard CSS/HTML into Email

Sass / Grunt.js / Zurb Foundation Email Templates (Basic)

### How To Use
Create html/css as normal. When complete, run grunt build:html to apply the styling inline to the elements. This will create a new file in build. Once thats complete run grunt build:css and manually add the compressed css to the build files.

##### More Reading
- http://foundation.zurb.com/emails/email-templates.html
- http://www.leemunroe.com/building-html-email/
- http://www.leemunroe.com/sending-email-designers-developers/

##### Support Guide
- https://www.campaignmonitor.com/css/

##### Bulletproof Backgrounds
- https://backgrounds.cm/

##### Bulletproof Buttons
- https://buttons.cm/

##### Webfonts
- https://www.campaignmonitor.com/dev-resources/will-it-work/webfonts/

##### Alt Text
- https://litmus.com/community/learning/12-alt-text-in-html-email

##### grunt-inline-css
This uses the grunt-inline-css node module.
- https://github.com/jgallen23/grunt-inline-css

### Commands
Resolve Node dependencies
```
$ npm install

```

Move style.css to inline styles, will create a new file in /build
```
$ grunt build:html

```

Compress CSS for Build
```
$ grunt build:css

```

Watch CSS Changes
```
$ grunt watch

```

Lint CSS
```
$ grunt lint:css

```

Lint HTML
```
$ grunt lint:html

```
