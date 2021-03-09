# viewhtmlmail

Take an mbox HTML message (e.g. from mutt), rewrite it and send it to firefox so it can be viewed as html.

## About

This is an old public script that I have ported to python 3. See original authors and contributors in script header.

## Usage

Just pipe the message to the script.

```
cat message.mbox | viewhtmlmail
```

From mutt you can create macros like:
```
macro  index  <F10>  "<pipe-message>~/bin/viewhtmlmail\n" "View HTML in browser"
macro  pager  <F10>  "<pipe-message>~/bin/viewhtmlmail\n" "View HTML in browser"
```

## Disclaimer

Use it at your own risk.

## License

GPL v2 or later.
