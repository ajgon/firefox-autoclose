# firefox autoclose

This is a simple workaround repository to [prevent firefox from opening new tab when pinned tabs are already present](https://support.mozilla.org/en-US/questions/1115374).

## Firefox configuration

In `about:config` set:

```ini
browser.startup.page = 1
browser.startup.homepage = https://ajgon.github.io/firefox-autoclose
dom.allow_scripts_to_close_windows = true
```
