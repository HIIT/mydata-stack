# MyData Architecture - *The Stack*

[![Join the chat at https://gitter.im/mydata-stack/Lobby](https://badges.gitter.im/mydata-stack/Lobby.svg)](https://gitter.im/mydata-stack/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This page documents the workflow for contributing to the future revisions of the specifications. For reading and downloading the latest release see. http://hiit.github.io/mydata-stack

## Contributing to the specification

- Join the chat at: https://gitter.im/mydata-stack/Lobby
- Suggest changes with Github issues: https://github.com/HIIT/mydata-stack/issues
- With Google account you can comment directly: http://bit.ly/sourcemarkdown
- Contact: Harri Honko (harri.honko@tut.fi) or Antti Poikola (antti.poikola@hiit.fi)

## Updating the original source

Edit [index.bs](http://bit.ly/sourcemarkdown) source file using the [W3C bikeshed Markdown syntax](https://github.com/tabatkins/bikeshed)

Test that the source converts to html witout errors either:

A) Copy the link: http://bit.ly/mydata2html to “Load from URL” in here: https://api.csswg.org/bikeshed

OR

B) Run on your command-line the following curl command:
```curl https://api.csswg.org/bikeshed/ -F url=http://bit.ly/mydata2html > index.html```
