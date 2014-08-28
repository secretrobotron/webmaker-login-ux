# Webmaker Login Angular

## Install

```
bower install cadecairos/makeapi-angular
```

## Setup

1. Add makerstap in your head `<link rel="stylsheet" href="bower_components/makerstrap/dist/makerstrap.complete.min.css"`. There are other ways to do this -- see the makerstrap docs.
2. Ensure that an `angularConfig` object is defined on `window`, and specifies a csrfToken attribute.
3. Make sure `angular.js`, `ui-bootstrap`, `webmaker-auth-client.js`, `wmLogin-angular.js` and `wmLogin-angular.templates.js` are all added to your document.
4. Add the `wmLoginAngular` module to your angular app.

## Directives

### wm-create-user

To add a create user modal use the `wm-create-user` attribute:

```html
<button wm-create-user>
</button>
```

### wm-login

To add a login modal use the `wm-login` attribute
```html
<button wm-login>
</button>
```