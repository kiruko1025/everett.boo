# everett.boo

The source for [everett.boo](https://everett.boo), Everett Xu's writing notebook.

The site is deliberately small: Markdown articles, a shared Jekyll layout, one stylesheet, and a tiny navigation script. It is published from the repository root with GitHub Pages.

## Write an article

Create a folder under `writing/` and add an `index.md`. Copy the front matter from an existing article, then change its title, description, date, reading time, table of contents, and navigation.

## Preview locally

Install the project gems once:

```sh
gem install bundler
bundle install
```

Then start Jekyll:

```sh
bundle exec jekyll serve
```

Open `http://localhost:4000`. Jekyll rebuilds the site whenever a Markdown file is saved.
