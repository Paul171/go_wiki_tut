# Writing Web Applications
## This is example by following the tutorials of writing webpage by using Go
** The link is under [gowiki][https://golang.org/doc/articles/wiki/] **
### Other Tasks ###
1. Store templates in tmpl/ and page data in data/.
2. Add a handler to make the web root redirect to /view/FrontPage.
3. Spruce up the page templates by making them valid HTML and adding some CSS rules.
4. Implement inter-page linking by converting instances of [PageName] to 
<a href="/view/PageName">PageName</a>. (hint: you could use regexp.ReplaceAllFunc to do this)