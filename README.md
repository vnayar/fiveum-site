# Abstract

The purpose of this project is to build a website for the Fiveum project, an alternative to Slack
that focuses on the needs of knowledge workers, namely, avoiding interruptions and keeping track of
multiple tasks.

The project is built using [Hugo](https://gohugo.io/getting-started/quick-start/), a static website
building tool whose input is a Markdown-like syntax. The hosting is done on [GitHub
Pages](https://pages.github.com/).

# Local Development

## Generating Static Pages

To generate static HTML, simply invoke the following command:
```
$ hugo
```

The output will be placed into the directory `/public`.

## Starting the Server

```
$ hugo server
```

Browse at http://localhost:1313/fiveum-site/

By default, drafts and features like Disqus are not included, to include these features, run the
following command:

```
$ hugo --buildDrafts
```
