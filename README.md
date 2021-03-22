## Simple theme (Based off [Jekyll Now](http://www.jekyllnow.com/)) for creating paper summary websites hosted through GitHub pages

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll))

## Quick Start (website added to existing repo)

### Step 1) Create /docs folder in existing repository
This new folder is where the code for the website will live.

### Step 2) Copy website template to your /docs folder
Copy the following contents of this (Jekyll-PaperTemplate) repository and transfer them into your /docs folder. More specifically, you will need to copy over the following folders and files:
- \_includes folder
- \_layouts folder
- \_sass folder
- images folder
- \_config.yml file
- 404.md file
- about.md file
- index.html file
- style.scss file
- .gitignore file

### Step 3) Update information in config.yml
You will need to update the website information for your repository. To do this, in your new repository code (that you should have just transfered to your repository), you will need to edit the "config.yml" file. More specifically update the following lines:

``name: Paper name`` 

``description: Paper authors`` 

`` paper-link: Paper link`` 

Also, if you'd like to add links to any other platforms (such as your repository), update the content under "footer-links" in config.yml. For example, to add a link on the bottom of the page back to your repository, update:

``github: repousername/reponame``

### Step 4) Push changes to repository
Push this change to your existing repository. You may want to create a new "docs" branch.

### Step 5) Enable GitHub Pages
You will need to enable Github Pages on your existing repository. To do this, go to settings, and under the "GitHub Pages" section, change Source from "None" to "main" (or whatever the name of your repository branch with the changes to /docs is). Then, you will select the folder that GitHub will look for the website information in -- select /docs. Click Save.

## Quick Start (Repo entirely for website)

### Step 1) Fork to your User Repository

Fork this repo, then rename the repository to a simple paper descriptor (for example ICRA2021-LearningHZD)

Your Jekyll blog will often be viewable immediately at <https://yourgithubusername.github.io/REPONAME/> (where REPONAME is the name of the forked repository)

### Step 2) Customize and view your site

Enter your paper name, and paper authors, by editing the _config.yml file. You can turn on Google Analytics tracking here too.

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon

> There are 3 different ways that you can make changes to your blog's files:

> 1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down your repository and make updates locally, then push them to your GitHub repository.

### Step 3) Edit your website content

Edit `about.md` to edit the website content. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/$REPONAME$/ where $REPONAME$ is either Jekyll-PaperTemplate or whatever name you rename your repository to be.
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.


## Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [Barry Clark](https://github.com/barryclark/jekyll-now/) - Jekyll theme used to base this theme off.

## Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.
