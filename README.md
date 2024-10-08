## Pagefind XKCD Demo

This is a demonstration of Pagefind searching a large dataset of XKCD comics.

View it live at https://xkcd.pagefind.app

All content from [xkcd](https://xkcd.com) is licensed under [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/) as per the [xkcd license](https://xkcd.com/license.html)</a>

### Run this site locally

To run this site locally, you need [Hugo](https://gohugo.io/) and [node.js](https://nodejs.org/en):

```console
hugo
```

This command will generate the site in the `public/` subdirectory. Then, run Pagefind:

```console
npx pagefind --site public
```

This will generate the search index. Now you can serve the site! If you have Python, you can run:

```console
python3 -m http.server -b localhost -d public 8888
```

This will open a server at port 8888, and you should be able to direct your web browser to http://localhost:8888/ and browse the site!
