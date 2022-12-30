An online lab notebook is required of all lab members. Entries need to be organized by date and in reverse chronological order.

## Notebooks

Person | Notebook  | Commitment
--- | --- | ----
Shefali Setia-Verma | [sr320.github.io](https://sr320.github.io/) |  ![GitHub last commit](https://img.shields.io/github/last-commit/sr320/sr320.github.io)
Tess Cherlin | [alldayscientess.github.io](https://alldayscientess.github.io/) |  ![GitHub last commit](https://img.shields.io/github/last-commit/RobertsLab/sams-notebook)
Lindsday Guare | [mattgeorgephd.github.io](https://mattgeorgephd.github.io/notebook/) | ![GitHub last commit](https://img.shields.io/github/last-commit/mattgeorgephd/mattgeorgephd.github.io)
Chelsea Okeh | [afcoyle.github.io](https://afcoyle.github.io) |   ![GitHub last commit](https://img.shields.io/github/last-commit/afcoyle/afcoyle.github.io)
Susanna Liu | [ocattau.github.io](https://ocattau.github.io/notebook-2/)  | ![GitHub last commit](https://img.shields.io/github/last-commit/ocattau/notebook-2)
You're Next | [drlawson.github.io](https://drlawson.github.io)  | ![GitHub last commit](https://img.shields.io/github/last-commit/drlawson/drlawson.github.io)

## Platforms

*Guide to creating a notebook on GitHub:*

One way to approach is simply to to follow the instructions at https://github.com/barryclark/jekyll-now. This is what our Notebooks are forks of.

To leverage the modifications Steven has made...

1) Fork his repository associated with his notebook: https://github.com/sr320/sr320.github.io.   
[Screencast](http://owl.fish.washington.edu/scaphapoda/grace/Github-noteboook.mov)

2) Change the user name associated the repository name in the Settings.

3) Revise the `_config.yml` file to include your own personal information

4) Alter lines 30 - 34 of `your_username.github.io/_layouts/default.html` to edit the items listed in the Navigation bar at the top right of your rendered webpage. It's useufl to add the following so clicking on "admin" link takes you to your `_posts` directory (you'll need to replace `<GITHUB-USERNAME> with your own info):

`<a href="https://github.com/<GITHUB-USERNAME>/<GITHUB-USERNAME>.github.io/tree/master/_posts">admin</a>`

5) Go to Disqus to set up comments for your website. Pick a page name, ignore instructions on adding code to your site. Complete registration.

6) Go back to `_config.yml` file and add your Disqus shortname. This will magically alter code so comments will show up for each posts.

7) All notebook posts have to exist in the `_posts` directory and must be formatted in the following fashion (including the `.md` extension):

`YYYY-MM-DD-<ANYTHING_YOU_want>.md`

Note: Sometimes revisions take a few minutes to render on GitHub.


—--

## Make sure it is reproducible
Document in a fashion where someone could replicate your work.

## Document daily
A record of your work should be published the day of activity. Yep, daily! Even if you feel like you did nothing, post <em>something</em> to describe what you did that day. Did you read some papers? Great! Make a post that lists the papers you read. Did you spend all day searching the web? Also great! Make a post about what you were searching for and how successful you were in finding what you wanted.

## Maintain backup
Have a copy of your notebook in another location. This could be done in several ways.
- composing in text editor and hosting on GitHub
- using IFTTT to post/save entries elsewhere
- run script (i.e. wget) to archive contents

Periodically, you will be asked to show where your backup is and demonstrate that it is functional.
