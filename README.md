<div align="center"> <img src="./gay.svg"/> </div>

# Themes

Note: these themes go best with the Comic Sans MS font.

[Discord (gaycord)](./gaycord.css)  
[Firefox (gayfox)](./gayfox.css)

![demo (light)](./gaycord_and_gayfox-light.gif)

![demo (dark)](./gaycord_and_gayfox-dark.gif)



# HALP!? How install?!?
## gaycord:

Multiple options here.

**Web client:**

1. Install Stylus - [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) / [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us)
2. Open the "Manage" page of that extension (left click -> manage)
3. "Write new style"
4. Paste the contents of gaycord.css
5. At the bottom of the page, click the `+` next to "Applies to Everything"
6. Change the "Applies to" dropdown to "URLs matching the regexp"
7. In the textbox to the right, paste `https://discord.com/(?!developers).*` (This is so it doesn't break pages like API docs & Bot management)
8. Give it a name such as "gaycord"
9. Save, and enjoy.  This is an order.

**Electron client (Desktop App)**

[DiscoCSS (Linux-only)](https://github.com/mlvzk/discocss)  
powercord / betterdiscord / something else, PR if you wanna fix this section.


## gayfox:

1. Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config`
2. Go to your profile directory by going to `about:support` and looking for "Profile Directory"
3. Once you're in that dir, make a subdir called `chrome`
4. In the `chrome` subdir, put the contents of the `gayfox.css` file in a file called `userChrome.css` (With those capitals)
5. Restart firefox
