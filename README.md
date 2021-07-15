# srt
SRT Website

We are using Jekyll with GitHub pages, along with a custom HTML/CSS template, with Bootstrap 5 (and not using Jekyll themes).

## Getting started

Jekyll uses Ruby, and so it requires you have Ruby and rubygems installed.

1. Clone the repo.
2. Run `bundle install`.
3. To see the site in your local browser, run `bundle exec jekyll serve` and go to http://localhost:4000
4. To make changes, create .MD files with "front matter" (see index.md as an example).  Even though it has an MD extension, it can be pure HTML (does not have to be markdown).
5. There are two page layout templates, one for the home page (home) and one for all other pages (default).  They are stored in the _layouts folder.  Include files (such as a footer) are stored in the _includes folder.  If you want a template that is not the default, specify it at the top of the page in the "front matter" (see  index.md page as an example)
6. You can include custom CSS, images and javascript in the appropriate subfolders and reference them as normal in your layouts or MD files.
7. Commit changes to a branch, and then make PR to the gh-pages branch.  This is the default branch for the repo and is what Github uses to build the website from.


Website URL: https://sul-dlss-labs.github.io/srt/
