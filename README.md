# Accounts UI Zurb for Meteor

Re-styles the Meteor Accounts UI package to use the Zurb Foundation 5 framework.

Note: Currently, this doesn't do anything to style the dropdown. To disable the dropdown, use the code:

```
Accounts._loginButtonsSession.set('dropdownVisible', true);

```


## Requirements

* Meteor
* NPM
* Meteorite


## How do I install this?

1. Install Meteorite `npm install -g meteorite`
2. Create Your project `mrt create mynewapp`
3. Add accounts-ui-zurb `mrt add accounts-ui-zurb`


## References

[Meteor](http://docs.meteor.com/)

[Meteorite](http://oortcloud.github.com/meteorite/)

[Atmosphere (Smart Packages)](https://atmosphere.meteor.com/wtf/package)
