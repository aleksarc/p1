![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for Codeanywhere. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Codeanywhere and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **May 11th, 2023**

## Codeanywhere Reminders

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere, in the terminal, type:

`python3 -m http.server`

A button should appear to click: _Open Preview_ or _Open Browser_.

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere with no-cache, you can use this alias for `python3 -m http.server`.

`http_server`

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A button should appear to click: _Open Preview_ or _Open Browser_.

In Codeanywhere you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In Codeanywhere, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

---

Happy coding!

## Sources

Footer icons provided by https://fontawesome.com/

Website template provided by Code Institute: https://github.com/Code-Institute-Org/ci-full-template

## References

This website was built with asistance of Code Institute professors, tutors and mentors as a result of deliverables for Project 1 or the course "Diploma in Full Stack Software Development (E-commerce Applications)".

How to reverse order of elements while using float:right for the menu items: https://stackoverflow.com/questions/4224476/floatright-reverses-order-of-spans

Reference for aligning elemets on the top of a container: https://www.w3docs.com/snippets/css/how-to-align-inline-block-elements-to-top-of-the-container.html

How to create a fixed header or footer using CSS: https://www.tutorialrepublic.com/faq/how-to-create-fixed-header-or-footer-using-css.php

## Problems Resolution

When pushing commits to Git from Visual Studio Code, the following error may be perceived:

    Enumerating objects: 75, done.
    Counting objects: 100% (75/75), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (51/51), done.
    error: RPC failed; HTTP 500 curl 22 The requested URL returned error: 500
    send-pack: unexpected disconnect while reading sideband packet
    Writing objects: 100% (69/69), 160.13 MiB | 5.99 MiB/s, done.
    Total 69 (delta 22), reused 0 (delta 0), pack-reused 0
    fatal: the remote end hung up unexpectedly
    Everything up-to-date

The resolution was to set "git config http.postBuffer 524288000" as per post in Stack Overflow: https://stackoverflow.com/questions/2702731/git-fails-when-pushing-commit-to-github