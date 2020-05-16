##
- [gowiki tutorial](https://golang.org/doc/articles/wiki/)
- [md render in template](https://stackoverflow.com/questions/23124008/how-can-i-render-markdown-to-a-golang-templatehtml-or-tmpl-with-blackfriday)

## TODO
- [x] Store templates in tmpl/ and page data in data/.
- [ ] Add a handler to make the web root redirect to /view/FrontPage.
- [ ] Spruce up the page templates by making them valid HTML and adding some CSS rules.
- [ ] Implement inter-page linking by converting instances of [PageName] to
- [ ] <a href="/view/PageName">PageName</a>. (hint: you could use regexp.ReplaceAllFunc to do this)
- [ ] Add markdown render

