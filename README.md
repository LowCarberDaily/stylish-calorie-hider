# Calorie Hider Styles For Stylish
Hides calories on the MFP dashboard.

Unfortunately, some of the recent changes have made hiding the dashboard info with Tampermonkey/Greasemonkey scripts impossible. So, we need a different tool to do that.

Enter: Stylish!

Stylish is a user stylesheet manager, and because it uses CSS, instead of JavaScript to target and alter the page, we don't have to worry as much about MFP's JavaScript interfering with our stuff.

# Installing

## Install Stylish

Firefox: https://addons.mozilla.org/en-US/firefox/addon/stylish/
Chrome: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en
Safari: http://sobolev.us/stylish/

## Install Script

If you're running Firefox, open the `firefox.css` file, otherwise, open the `chrome.css` file.

In the Stylish manager, select "write new style" and copy and paste *all* of the contents of the file you opened. Name it, and save it. Your MFP dashboard should update accordingly.
