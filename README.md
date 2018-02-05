This is the collaborative Jekyll site for CMS.633, a digital humanities course at MIT. If you are the site administrator and wish to prepare for an upcoming run of the course by archiving the existing site and setting up a new copy, see the following instructions.

### Archiving the existing site
1. If you don’t yet have a local copy of the cms633.github.io repository, run `git clone https://github.com/cms633/cms633.github.io.git` in the command line
1. In the command line, run `cd cms633.github.io` (swap in the name of the directory containing your local copy of the repo, if different). Run `git pull` to bring it up to date.
1. Make a copy of your local cms633.github.io directory. Name it cms633-new.
1. In your web browser, log in to GitHub using the cms633 login (passord in HS wiki). Go to [https://github.com/cms633/cms633.github.io/settings](https://github.com/cms633/cms633.github.io/settings)
1. Under settings > Repository name, change cms633.github.io to 2017. Click rename.
1. In the command line, in your cms633.github.io directory, run `git remote set-url origin https://github.com/cms633/2017.git`
1. In your cms633.github.io directory, open _config.yml in a text editor. In the line reading `url: "http://cms633.github.io”`, add `/2017` to the end of the url string.
1. In the cms633-2017 directory, navigate to the _includes directory and open header.html in a text editor. Add this line of HTML before line 5 (`<a class=“site-tile” …`):<br /> `<p class="archive-notice">This is the archived site for the Spring 2017 session of CMS.633 — for the current site, click <a href="http://cms633.github.io/">here</a>.</p>`
1. In the command line, run the following commands:<br />
`git add .`<br />
`git commit -m "changes for archived site"`<br />
`git push origin master`
1. At [https://github.com/cms633/2017](https://github.com/cms633/2017), click the dropdown button that says “Branch: master”. In the text field, type gh-pages. Then click “Create branch: gh-pages.”
1. In the command line, run `cd ../` to back out of the directory.
1. Rename your local cms633.github.io directory to cms633-2017.
1. Notify last year's students that URLs for their material on the site have changed (they will need to insert `/2017` in any links to the site). The students are still collaborators on the archived site. If they wish to edit or remove their content, they should push changes to the gh-pages branch of the repo.

### Preparing the new site
1. Rename the cms633-temp directory you made to cms633.github.io
1. In the command line, run `cd cms633.github.io`
1. Clean out any content from the previous year you don’t wish to keep:
    - Images and other from the assets folder, except for any used by posts or pages that will remain
    - Posts from the _posts folder (selectively, as some resource or bio posts will still be useful; keep in mind that almost all of the site content is in this folder)
    - Anything in the _drafts folder
1. Copy the new syllabus PDF to the assets folder and name it cms-633-syllabus.pdf (replacing the old one if it’s still there)
1. Open index.html in a text editor. In line 20, change the URL for the Stellar site to the correct URL for this year’s course.
1. Open _includes/header.html in a text editor. Find the line (30) that reads `<li><a href="http://cms633.github.io/2016/">2016</a></li>`. Copy and paste it onto the next line and change both instances of `2016` to `2017`.
1. Save all changes. In the command line, run `git add .`, then `git commit -m “updated site for current year”`.
1. In your web browser, go to [https://github.com/new](https://github.com/new) and in the “Repository name” field, type "cms633.github.io". Enter a description in the “Description" field, e.g. "Course site for CMS 633/833 — Digital Humanities: Topics, Techniques, and Technologies”. Click “Create repository”.
1. If using GitHub credentials in the command line other than those for cms633, add yourself as a collaborator (see below). For attaching GitHub credentials to git, see [https://help.github.com/articles/set-up-git/](https://help.github.com/articles/set-up-git/)
1. In the command line, run `git push origin master`.
1. The new site should appear at [https://cms633.github.io](https://cms633.github.io)

### Adding students as collaborators
1. Each student must first create their own GitHub account (if they don’t already have one) and email their username to you.
1. At https://github.com/cms633/cms633.github.io/settings/collaboration, enter the student’s username and click “Add collaborator"
1. Direct students to the [Contributing to This Site](https://cms633.github.io/about/) for instructions on using prose.io to add content
