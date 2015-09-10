## PayTabs Opencart 1.5x module

Slightly modified version of Paytab's Opencart 1.5x module.

The original was confusing to set up, language variables were missing and/or incorrect. For example: It asked for 'Merchant ID' and 'Secret' when it actually meant your Paytabs account email and account password. Took me a few tries to figure that out.

Variables in the view file were also missing. It was using text for merchant id and password fields where it should have been using language variables. 

The link to the Paytabs logo was also broken so the image didn't show when initially installed. Fixed that so now the image shows in the payment modules list.

### Modifications / Improvements

- Fixed broken link for logo image
- Added language variables
- Modified admin/view file to use variables merchant instead of plain text
- Modified admin/controller file to load 'entry_password' instead of 'entry_secret'
- Added help text for configuartion fields

### Screenshots
Before:
![listing](#)
![config](#)

After:
![listing](#)
![config](#)