Code for Ricardo I Alcala's website [ricardoi.github.io](https://ricardoi.github.io/ricardoi.github.io).

Clone from [matocci27.github.io](https://github.com/mattocci27/mattocci27.github.io) -> modified from [t413.com/SinglePaged](https://github.com/t413/SinglePaged).


## Requirements
- Ruby --> brew install ruby [preferred]
- Bundler --> gem install bundler [preferred]
- gem packages in Gemfile

```shell
% gem install bundler
% bundle install
```

## Usage

```rake publish``` will generate and publish website to gh-pages. I need this step because the [default Github pages workflow](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) does not allow most of the plugins to run for security reasons.

```git push -f``` push the code to gh-pages. I need this step because I am having a liquid tag problem that does not push locally the code.

## to do
- markdown for software page
# website
