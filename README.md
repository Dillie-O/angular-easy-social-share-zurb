# AngularJS Easy Social Share using Zurb

An easy way way to share the current page on an AngularJS app with Twitter, Facebook, Google Plus, and LinkedIn.

This directive uses URL links to share your page's content on each of the social media networks and therefore doesn't require the use of an app ID.

## Usage

This repository can be installed using Bower:

```bash
bower install angular-easy-social-share-zurb --save
grunt bower-install
```

### Dependencies

This directive requires [Zurb Foundation Icons 3](http://zurb.com/playground/foundation-icon-fonts-3), which is included in the package. You may need to manually change the directive a little bit if you use a different version.

#### Installation

1. Make sure `easy-social-share.js` is included in your index.html or other file.
 
2. Add `td.easySocialShare` as an app dependency:

	`angular.module('myApp', [ 'td.easySocialShare' ])`

3. Use the `share-links` directive in your view's HTML as follows:

	`<div share-links="Facebook, Twitter, LinkedIn, Google-Plus" share-title="Article Title"></div>`

### Styling

Since this is using Zurb Foundation Icons, you can follow the documentation [here](http://zurb.com/playground/foundation-icon-fonts-3#customize) on how to customize the look.
