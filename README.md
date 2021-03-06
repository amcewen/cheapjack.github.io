# Cheapjack Website

This website is built on `Jekyll-Bootstrap` and hosted for free on github pages; and like most things we use on the `internet`, and just like `books`, all built on other people's hard work. The content was previously on `Tumblr`, someone else's hard work. I love `Tumblr` but wanted to take a bit more ownership of the content and be able to put it in a more standard and simpler form. Ideally this should be nice simple `html` but, well I found a way of exporting all my tumblr content safely into github pages while maintaining all the structure and meta data ie tags. As a recent convert to `git` and `github` and even `gitprint` and things like [gitlab](https://about.gitlab.com/) to maintain and project manage information it made sense while also sensibly serve simple static webpages. 

## Some thoughts on tools

I like to celebrate the tools and knowledge we use to be creative. I'm consistently interested in who's knowledge we use and why. The use of tools is a connection to a **wider commons of knowledge** beyond our individual experience, knowledge and expression.

Much of my intent curatorially is to refer back and engage with the wider community knowledge I aquire and profit from. Github pages is one way to do that. There are other ways [like Linked Research](https://github.com/csarven/linked-research) to do that. And many of them are on `github` ;)

## Jekyll-Bootstrap How-To

The quickest way to start and publish your Jekyll powered blog. 100% compatible with GitHub pages

## Quickstart

### Serve the website locally

`cd` into your Jekyll-Bootstrap directory you'll run jekyll with server support:

remember to change USERNAME to your GitHub username.

`$ cd USERNAME.github.com 
$ jekyll serve`

Your blog is now available at:`http://localhost:4000/`.

### Create a Post

Create a post easily via rake task:
`$ rake post title="Hello World"`

The rake task automatically creates a file with properly formatted filename and YAML Front Matter. Make sure to specify your own title. By default, the date is the current date.

The rake task will never overwrite existing posts unless you tell it to.

### Create a Page

Create pages easily via rake task:

`$ rake page name="about.md"`
Create a nested page:

`$ rake page name="pages/about.md"`
Create a page with a "pretty" path:

`$ rake page name="pages/about"`
# this will create the file: ./pages/about/index.html
The rake task automatically creates a page file with properly formatted filename and YAML Front Matter as well as includes the Jekyll Bootstrap "setup" file.

## Usage

For all usage and documentation please see: <http://jekyllbootstrap.com>

## Version

0.3.0 - stable and versioned using [semantic versioning](http://semver.org/).

**NOTE:** 0.3.0 introduces a new theme which is not backwards compatible in the sense it won't _look_ like the old version.
However, the actual API has not changed at all.
You might want to run 0.3.0 in a branch to make sure you are ok with the theme design changes.

## Milestones

[0.4.0](https://github.com/plusjade/jekyll-bootstrap/milestones/v%200.4.0) - next release [ETA 03/29/2015]

### GOALS

* No open PRs against master branch.
* Squash some bugs.
* Add some new features (low-hanging fruit).
* Establish social media presence.


### Bugs

|Bug |Description
|------|---------------
|[#86](https://github.com/plusjade/jekyll-bootstrap/issues/86)  |&#x2611; Facebook Comments
|[#113](https://github.com/plusjade/jekyll-bootstrap/issues/113)|&#x2611; ASSET_PATH w/ page & post
|[#144](https://github.com/plusjade/jekyll-bootstrap/issues/144)|&#x2610; BASE_PATH w/ FQDN
|[#227](https://github.com/plusjade/jekyll-bootstrap/issues/227)|&#x2611; Redundant JB/setup

### Features

|Bug |Description
|------|---------------
|[#98](https://github.com/plusjade/jekyll-bootstrap/issues/98)  |&#x2611; GIST Integration
|[#244](https://github.com/plusjade/jekyll-bootstrap/issues/244)|&#x2611; JB/file_exists Helper
|[#42](https://github.com/plusjade/jekyll-bootstrap/issues/42)  |&#x2611; Sort collections of Pages / Posts
|[#84](https://github.com/plusjade/jekyll-bootstrap/issues/84)  |&#x2610; Detecting production mode

### TODOS

Review existing pull requests against plusjake/jekyll-bootstrap:master. Merge or close each.

* Create twitter account. Add link / icon on jekyllbootstrap.com.
* Create blog posts under plusjade/gh-pages, expose on jekyllbootstrap.com, feed to twitter account.
* Announce state of project, announce roadmap(s), announce new versions as they’re released.

## Contributing


To contribute to the framework please make sure to checkout your branch based on `jb-development`!!
This is very important as it allows me to accept your pull request without having to publish a public version release.

Small, atomic Features, bugs, etc.
Use the `jb-development` branch but note it will likely change fast as pull requests are accepted.
Please rebase as often as possible when working.
Work on small, atomic features/bugs to avoid upstream commits affecting/breaking your development work.

For Big Features or major API extensions/edits:
This is the one case where I'll accept pull-requests based off the master branch.
This allows you to work in isolation but it means I'll have to manually merge your work into the next public release.
Translation : it might take a bit longer so please be patient! (but sincerely thank you).

**Jekyll-Bootstrap Documentation Website.**

The documentation website at <http://jekyllbootstrap.com> is maintained at https://github.com/plusjade/jekyllbootstrap.com


## License

[MIT](http://opensource.org/licenses/MIT)
