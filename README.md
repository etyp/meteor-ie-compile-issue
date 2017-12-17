# meteor-ie-compile-issue
Meteor 1.6 IE breaking issue reproduction

`meteor npm install`

`meteor run`

Try opening the running app in IE11 on any version of windows and you'll see errors in the console. See [main.js](client/main.js) where we include `sanitize-html` node module.
