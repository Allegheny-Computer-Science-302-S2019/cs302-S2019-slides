# cs103-S2018-slides

This repository contains all of presentation slides for Computer Science 103
Spring 2018. Each HTML file in this repository contains one "deck" of slides for
a module of this course. To learn more about the course in which these
assignments were completed, please visit the [Computer Science 103 Spring 2018
GitHub Organization](https://github.com/Allegheny-Computer-Science-103-S2018).
The source code of the slides uses
[reveal.js](https://github.com/hakimel/reveal.js/) framework to control the
display of each slide. I have developed a custom theme for the slides that
manages the fonts, formatting, color scheme, and the use of full-screen
photographs on the backgrounds.

You are welcome to use these slides as inspiration for your own presentation. If
you find these slides useful, could I trouble you to star this repository and
then acknowledge it in your own presentation slides?

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/Allegheny-Computer-Science-103-S2018/cs103-S2018-slides.git
```

Please note that the presentation uses remote fonts and thus will not correctly
display on a laptop that either may not have access to the Internet or may only
have unreliable Internet access. Also, it should be possible for you to view the
presentation correctly when using Chrome or Chromium on the Ubuntu operating
system &mdash; this is my primary development environment and the one that I
used to present these slides. However, I anticipate that the presentation slides
will display correctly on a wide variety of operating systems and browsers.

I have found that some versions of Chrome and Chromium do not quickly load the
full-screen images that I use as backgrounds. If you notice this problem as
well, then I would encourage you to "serve" the presentation with a local Web
server, such as the Ruby-based one available at
[jlong/serve](https://github.com/jlong/serve). If you adopt this approach, then
you should type the following command:

```shell
serve 4100
```

Now, for instance, you can navigate to the Web site
`http://localhost:4100/cs103_chapter1.html` and view the presentation.
Ultimately, if you are unable to get the presentation to display correctly in
your own web browser, then please open a new issue and I will attempt to resolve
your concerns.
