# ui-select-min-bootstrap-css
For using Angular ui-select Bootstrap theme without including all of Bootstrap

While working on a project, I was tasked with replacing select with ui-select. Of the themes available for ui-select, one did not look like our site, one did but had issues preventing it from being useful to us, and the last looked somewhat similar but used Bootstrap, which we were not.

I took the Bootstrap CSS and cut it down to the minimum required to appropriately display ui-select while not overriding our Foundation setup. The file in this repo is in three sections:

- The cut-down Bootstrap;
- Lines from the Basic example found here: https://angular-ui.github.io/ui-select/;
- Lines specific to our implementation that may be applicable or not.

I am choosing to share this in case it is useful to anyone who needs to use the ui-select Bootstrap theme but isn't using Bootstrap. Save yourself some time, and start here.
