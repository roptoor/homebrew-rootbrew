# Custom Brew Formulae
## Why?
Maintain custom versions of brew formulae to fix various issues.

The only formula maintained currently is saml2aws, due to [this upstream issue](https://github.com/Versent/saml2aws/issues/1077)

## How do I install these formulae?

`brew install roptoor/rootbrew/<formula>`

Or `brew tap roptoor/rootbrew` and then `brew install <formula>`.

Notes:
1. you may need to unlink/uninstall later versions, via: `brew unlink <formula>` or `brew uninstall `<formula>`
2. you should pin these versions (using `brew pin <formula>`), otherwise `brew upgrade`s will leave you with the versions from core

## Issues
Submit bugs, issues, etc. through [shortcut](https://app.shortcut.com/joinroot/)
