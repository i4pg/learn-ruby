<!-- omit in toc -->
# Learning Ruby: a resource list

Hi! As a second-career developer who didn't go through a bootcamp, I've found it helpful to keep a roadmap of learning resources—building my own curriculum, in a way. I hope this list helps you too!

If you notice any broken links here, please let me know by [opening an issue](https://github.com/fpsvogel/learn-ruby-and-cs/issues/new/choose).

<!-- omit in toc -->
## Table of contents

The "not done" sections (currently "Fundamental tools" and below) are somewhat chaotic because I haven't yet seen what's worth keeping there.

- [Preliminaries](#preliminaries)
- [Basics](#basics)
  - [Front-end basics](#front-end-basics)
  - [Ruby basics](#ruby-basics)
  - [Rails basics](#rails-basics)
  - [Ruby/Rails communities](#rubyrails-communities)
- [Fundamental tools](#fundamental-tools)
  - [SQL](#sql)
  - [Git](#git)
  - [How the Internet works](#how-the-internet-works)
  - [Linux / command line](#linux--command-line)
- [Ruby blogs, podcasts, screencasts](#ruby-blogs-podcasts-screencasts)
- [Front end](#front-end)
  - [Reviewing the basics](#reviewing-the-basics)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [Web components](#web-components)
  - [UI and Usability](#ui-and-usability)
  - [Hotwire](#hotwire)
- [Rails codebases to study](#rails-codebases-to-study)
- [Advanced Ruby and Rails](#advanced-ruby-and-rails)
  - [Misc. Ruby/Rails](#misc-rubyrails)
  - [Rails architecture](#rails-architecture)
- [Expanding my horizons](#expanding-my-horizons)
- [Other resource lists](#other-resource-lists)

## Preliminaries

- **If you want to keep it simple** and use just *one* resource that can take you from zero to hireable, I suggest the free [Odin Project](https://www.theodinproject.com/paths). If you want more variety, keep reading!
- **If you're wondering why I chose Ruby** and not full-stack JavaScript, [I explain why on my blog](https://fpsvogel.com/posts/2021/why-learn-ruby). Or if you want a second opinion, [read this](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) or [watch this](https://youtu.be/IlVfHG-pAag?t=1534).
- **Make sure your day job is conducive to part-time studying** if you're a working adult looking to switch careers. I used to be a teacher and spent hours grading in the evenings and on weekends, which would have made studying very difficult. So I switched to a remote customer support job to free up my schedule.
- **Find a system for keeping *organized* notes**, code snippets, and bookmarked links. I use [a simple text file](https://fpsvogel.com/posts/2021/plain-text-knowledge-base).
- **You should spend more time *coding* than *reading about* coding**. I mention this because below I list lots of books and courses but not many hands-on projects. Why? Because starting a project and getting into a coding routine is easy (if you can't think of any project ideas, try these lists: [1](https://github.com/codecrafters-io/build-your-own-x), [2](https://github.com/practical-tutorials/project-based-learning#ruby), [3](https://projectbook.code.brettchalupa.com)), whereas knowing what to read is not at all obvious at the beginning. Hence the focus on books and courses here.
- **Last but not least, take care of yourself!** Exercise and get plenty of sleep, and you'll better retain what you learn. If you develop wrist pain from heavy computer use, act swiftly: get an ergonomic keyboard ([the one I use](https://fpsvogel.com/posts/2021/keyboardio-atreus) has a learning curve, but I love it *and* it was affordable), [do daily wrist stretches](https://youtu.be/fdD7CgN5FGg), and try using a break app such as [Workrave](https://workrave.org/).

Without further ado, here is my learning roadmap. Resources marked with a dollar sign (💲) cost money. You may be able to find books for free (from your local library, interlibrary loan, or more dubious sources) but buy them if/when you can, to support the authors.

## Basics

### Front-end basics

- [x] **Learn some HTML, CSS, and JavaScript:** [The Odin Project - Foundations path](https://www.theodinproject.com/paths/foundations/courses/foundations). Or if that doesn't click with you, try resources under ["Front end"](#front-end) below.
- [x] **Build a blog from scratch:** I've rebuilt it by now, but [here is the first iteration](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). Building a blog is not only a good exercise in itself, but it might also give you extra motivation to write about what you learn.

### Ruby basics

- [x] **Basics:** [The Odin Project - Ruby](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby) or (for more interactivity) [Try Ruby](https://try.ruby-lang.org/) and [BigBinary Academy](https://academy.bigbinary.com/learn-ruby)
- [x] **Guided practice:** [Exercism](https://exercism.org/tracks/ruby). Be sure to take notes each time you learn something new in an exercise, and at the end you could write up your reflections ([here are mine](https://fpsvogel.com/posts/2020/exercism-ruby)).
- [x] **OOP:** Sandi Metz's books 💲[Practical Object-Oriented Design: An Agile Primer Using Ruby](https://www.poodr.com) (a.k.a. POODR) and 💲[99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby)
- [x] **Build a Ruby app:** Apply those OOP lessons. I made a CLI (command-line interface) [app that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned).
  - Or you could make a game with [DragonRuby](https://dragonruby.itch.io/), using these resources: [Building Games with DragonRuby](https://book.dragonriders.community/), [DragonRuby Zines](https://shop.brettchalupa.com/category/zines), [DragonRuby Recipes](https://www.dragonriders.community/recipes), and the [Scale](https://github.com/DragonRidersUnite/scale) template.
- [x] **Build a site with Bridgetown:** With [Bridgetown](https://github.com/bridgetownrb/bridgetown) you can build a site without yet getting into the complexity of Rails. Maybe [rebuild your blog](https://fpsvogel.com/posts/2021/build-a-blog-with-bridgetown)? Be sure to [join the Bridgetown Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies.

### Rails basics

Only books and courses are listed below, but be sure to *build stuff* as you learn. I myself [started building a large-ish Rails app](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) at first, but then I found it more helpful to build a series of small throwaway apps ([1](https://fpsvogel.com/posts/2021/gpt3-ai-story-writer), [2](https://fpsvogel.com/posts/2021/wikipedia-explorer-discover-articles-like-stumbleupon), [3](https://fpsvogel.com/posts/2021/pass-the-story-collaborative-writing-game), [4](https://fpsvogel.com/posts/2022/doctor-lookup-health-provider-search-tool)).

- **Rails basics:**
  - [x] [GoRails - Rails for Beginners](https://gorails.com/start)
  - [x] [The Odin Project - Rails](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) or (if you prefer videos) 💲[Michael Hartl's Ruby on Rails Tutorial](https://www.railstutorial.org)
- **Rails testing and RSpec:**.
  - [x] Upcase - [Fundamentals of TDD](https://thoughtbot.com/upcase/fundamentals-of-tdd) and [Test Doubles](https://thoughtbot.com/upcase/test-doubles)
  - [x] 💲[Jason Swett - The Complete Guide to Rails Testing](https://www.codewithjason.com/complete-guide-to-rails-testing/)
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/)
- **Polishing up:**
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec

### Ruby/Rails communities

Here are some places where you can learn with others or ask questions when you get stuck.

- **Communities:**
  - [The Ruby Learning Center](https://www.rubylearning.dev/)
  - [StimulusReflex community on Discord](https://discord.com/invite/stimulus-reflex)
  - [Ruby on Rails Link community on Slack](https://www.rubyonrails.link/)
  - [GoRails community on Discord](https://discord.gg/gorails)
- **Mentorship:** I got mentorship about a year after starting with Rails, but you may benefit from it earlier.
  - [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor.
  - [The Rails subreddit](https://www.reddit.com/r/rails) is another good place to find a mentor.
- **Subscribe to Ruby newsletters:** You can learn a lot by listening in on what the Ruby community is talking about.
  - [Ruby Weekly](https://rubyweekly.com/)
  - [Ruby Radar](https://rubyradar.dev/)
  - [Short Ruby](https://newsletter.shortruby.com/)

## Fundamental tools

### SQL

- [x] [SQL Teaching](https://www.sqlteaching.com)
- [x] [SQLBolt](https://sqlbolt.com)
- [x] [Select Star SQL](https://selectstarsql.com)
- [ ] [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial) for practice and some new concepts
- [ ] [Next-Level Database Techniques for Developers](https://sqlfordevs.com/ebook)
- [ ] 💲[SQL Antipatterns, Volume 1](https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/)
- [ ] [Markus Winand - Use the Index, Luke!](https://use-the-index-luke.com/sql/preface)
- [ ] [Markus Winand - SQL Performance Explained](https://sql-performance-explained.com)
- [ ] [Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql) course from Stanford
- [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
- [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at Thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
- [ ] [The Art of PostgreSQL](https://theartofpostgresql.com/)
- [ ] [PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)

### Git

- [x] [Oh My Git!](https://ohmygit.org/)
- [x] [Oh Shit, Git!?!](https://ohshitgit.com/)
- [ ] [Git Katas](https://github.com/eficode-academy/git-katas)
- [ ] [Pro Git](https://git-scm.com/book)
- [ ] [Thoughtbot - Rebuilding Git in Ruby](https://thoughtbot.com/blog/rebuilding-git-in-ruby)
- [ ] 💲[Building Git](https://shop.jcoglan.com/building-git)

### How the Internet works

- [ ] (WIP) [Computer Networks from Scratch](https://www.networksfromscratch.com)
- [ ] 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V)
- [ ] [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [ ] [Jesse Storimer - Working with TCP Sockets](https://workingwithruby.com/wwtcps/intro)
- [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)

### Linux / command line

- [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [ ] [Bashcrawl](https://gitlab.com/slackermedia/bashcrawl)
- [ ] [Practice Linux Commands](https://labex.io/courses/linux-basic-commands-practice-online)
- [ ] [Command Challenge](https://cmdchallenge.com/)
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
- [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
- [ ] 💲[Julia Evans - How Containers Work](https://wizardzines.com/zines/containers/)
- [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
- [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2)
- [ ] [Jesse Storimer - Working with Unix Processes](https://workingwithruby.com/wwup/intro)

## Ruby blogs, podcasts, screencasts

- **Blogs:**
  - [x] [Fullstack Ruby](https://www.fullstackruby.dev/articles)
  - [x] [Code with Jason](https://www.codewithjason.com/articles/)
- **"Let's build" screencasts:** My criteria for inclusion are (1) not *too* out of date, and (2) insightful for someone who has done a basic Rails course such as The Odin Project.
  - [ ] [Rails Code Along](https://www.railscodealong.com/) – Rails 6, Heroku, Devise, Bootstrap
  - [ ] [Web-Crunch - Let's Build collection](https://web-crunch.com/collections/lets-build-with-ruby-on-rails)
  - [ ] [Web-Crunch - Job marketplace app](https://web-crunch.com/collections/lets-build-for-ruby-and-rails-developers)
  - [ ] [Dr. Nic - Notion clone](https://www.youtube.com/playlist?list=PLcKahasNsPxS-Y9yvmOHMOn9Uei6nzYiz)
  - [ ] [CJ Avilla - Automate YouTube Video Production](https://www.youtube.com/playlist?list=PLS6F722u-R6ILDUeteD-A_q6Ja4SH8v95)
  - [ ] [CJ Avilla - Stock App](https://www.youtube.com/playlist?list=PLS6F722u-R6JOyF7jKb4aZsX0l6eDARp1)
  - [ ] [CJ Avilla - clearbnb](https://www.youtube.com/playlist?list=PLS6F722u-R6LoD3UN0EE_cKtHVG2EWn0t)
  - [ ] [CJ Avilla - CreatorPlatform.xyz](https://www.youtube.com/playlist?list=PLS6F722u-R6IJfBrIRx3a2SBkAL4vUp2p)
  - [ ] [Mix & Go - Instagram clone](https://www.youtube.com/playlist?list=PLBhH0uX92r6rjVGaXipwGzzJ_d1Z-J7LX)
  - [ ] [SupeRails - user feedback app](https://www.youtube.com/playlist?list=PLdTytUiloS14rxJRGoEKOcEWFouuZblCL)
  - [ ] [TypeFast - Trello clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJLgAlweneIHqQTUMiVquXaD)
  - [ ] [TypeFast - AirBnB clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJK1_-KVgXyREULRVy_W_1pe)
  - [ ] [TypeFast - Twitter clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJLb9HwPWiizGBNupJszY6bR)
  - [ ] [Pet adoption app](https://www.youtube.com/playlist?list=PLDqVN4u4m3K_6ahSLq9nLVVO6Y8xEVvqV)
- **Topical screencasts:**
  - [ ] [Joel Drapper & Kasper Timm Hansen - Naming Things](https://www.namingthings.org/)
  - [ ] [Web-Crunch - Ruby on Rails collection](https://web-crunch.com/collections/ruby-on-rails)
  - [ ] [Yaroslav Shmarov - SupeRails](https://www.youtube.com/c/SupeRails/playlists)
  - [ ] [Phil Smy - Ruby on Rails](https://youtube.com/playlist?list=PLiJC12qFqVo3DrqGZn80DvdT8qGsQT9wh)
  - [x] [DHH - On Writing Software Well](https://youtube.com/playlist?list=PL9wALaIpe0Py6E_oHCgTrD6FvFETwJLlx)
  - [x] 💲[GoRails](https://gorails.com)
  - [x] 💲[Drifting Ruby](https://www.driftingruby.com)
  - [ ] 💲[Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog)
- **Podcasts:**
  - [x] [Ruby for All](https://www.rubyforall.com/)
  - [ ] [Sierra Rails](https://anchor.fm/sierra-rails)
  - [x] [Fullstack Ruby](https://www.fullstackruby.dev/topics/podcast)
  - [ ] [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [ ] [Rooftop Ruby](https://www.rooftopruby.com)
  - [ ] [Code and the Coding Coders who Code it](https://podcast.drbragg.dev/)
  - [ ] [The Rubber Duck Dev Show](https://www.rubberduckdevshow.com/)
  - [ ] [Framework Friends](https://www.frameworkfriends.com/) about Rails and Laravel
  - [x] [Ruby Rogues](https://topenddevs.com/podcasts/ruby-rogues)
  - [ ] [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/), especially starting at [episode 372](https://www.therubyonrailspodcast.com/372) went they went independent, brought on co-hosts, and hired an editor.
  - [ ] [Code with Jason](https://www.codewithjason.com/podcast)
  - [ ] [Maintainable](https://www.maintainable.fm/) (not Ruby-specific)
  - [ ] [DevDiscuss](https://devpods.dev/podcasts/devdiscuss) (not Ruby-specific)
  - [ ] [The Bike Shed](https://www.bikeshed.fm/)
  - [ ] [Running in Production – Rails](https://runninginproduction.com/tags/rails)

## Front end

### Reviewing the basics

- [ ] [MDN - Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web), plus their [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML), [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS), and [JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) tutorials
- [ ] [web.dev courses](https://web.dev/learn/), especially [HTML](https://web.dev/learn/html/) and [CSS](https://web.dev/learn/css/)
- [ ] The Odin Project - [Intermediate](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/intermediate-html-and-css) and [Advanced](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/advanced-html-and-css) HTML and CSS, [JavaScript](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript)
- [ ] Try [CSS Naked Day](https://css-naked-day.github.io/) on my personal site

### CSS

- [ ] 💲[Julia Evans - Hell Yes! CSS!](https://wizardzines.com/zines/css/)

### JavaScript

- [ ] [JavaScript for impatient programmers](https://exploringjs.com/impatient-js/)
- [ ] [What the heck is the event loop anyway?](https://youtu.be/8aGhZQkoFbQ)
- [ ] [The Modern JavaScript Tutorial](https://javascript.info/)
- [ ] [JavaScript30](https://javascript30.com/) for practice

### Web components

- [ ] [Web components section](https://javascript.info/web-components) in the Modern JavaScript Tutorial
- [ ] [Dave Rupert - HTML with Superpowers: The Guidebook](https://daverupert.com/2023/01/html-with-superpowers-the-guidebook/) or 💲[the course version](https://frontendmasters.com/courses/web-components/)
- [ ] [Lit docs](https://lit.dev/)
- [ ] Build some UIs with [Shoelace](https://shoelace.style/), a web component UI library.
- [ ] Read [the Shoelace source code](https://github.com/shoelace-style/shoelace)
- [ ] 💲[Fullstack Web Components: Complete Guide to Building UI Libraries with Web Components](https://www.newline.co/courses/fullstack-web-components)
- [ ] Build a UI following [Jared White - How Ruby and Web Components Can Work Together](https://www.fullstackruby.dev/fullstack-development/2022/01/04/how-ruby-web-components-work-together/)
- [ ] Experiment using [Turbo](https://turbo.hotwired.dev/) to drive front-end behavior: *"Turbo 7.2.0 (currently in beta) allows you to define your own Stream actions which can be any JS code you want. By combining a custom Stream action or two with web components, you can essentially drive reactive frontend behavior from the backend stupidly easily. Loooove it! 😍 […] For a turnkey example, you could check out https://github.com/hopsoft/turbo_ready "* —Jared White on [The Spicy Web](https://discord.com/channels/811491992285741077/811493083068760104/1019024338042761297) Discord

### UI and Usability

- [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/)
- [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)
- [x] [Victor Ponamariov - 50 UI Tips](https://fifty.user-interface.io/50_ui_tips.pdf)
- [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips) (or on [the landing page](https://hundred.user-interface.io/))
- [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)
- **Better Rails views:**
- [ ] [Phlex](https://www.phlex.fun/)

### Hotwire

- **Community and news:**
  - [StimulusReflex community on Discord](https://discord.com/invite/stimulus-reflex)
  - [Hotwire dev newsletter](https://masilotti.com/hotwire/)
- **Basics:**
  - [ ] [Read the docs](https://hotwired.dev/)
  - [ ] Evil Martians [talk](https://www.youtube.com/watch?v=sIxvxp7E0xg) and [blog post](https://evilmartians.com/chronicles/hotwire-reactive-rails-with-no-javascript)
  - [ ] [Alexandre Ruban - Turbo Rails Tutorial](https://www.hotrails.dev/)
  - [ ] [David Colby - Turbo Rails 101](https://www.colby.so/posts/turbo-rails-101-todo-list)
  - [ ] [Hotwire Handbook, Part 1](https://philreynolds.dev/posts/2022/hotwire-handbook-part-1) (seems abandoned, though)
  - [ ] [Andrea Fomera - Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire)
  - [ ] [David Colby - Hotwired ATS: Modern, full-stack Rails development](https://book.hotwiringrails.com/)
- **Screencasts and blogs:**
  - [ ] [Mix & Go screencasts on Hotwire](https://www.youtube.com/playlist?list=PLBhH0uX92r6oiwiLBjdE-3NNsyRqyLAV9)
  - [ ] [SupeRails screencasts on Hotwire](https://www.youtube.com/playlist?list=PLdTytUiloS16epXsqHswpCUMND_rksjr4)
  - [ ] [SupeRails blog](https://blog.corsego.com) which includes even more Hotwire tips.
  - [ ] [David Colby's blog](https://www.colby.so)
- **Examples and snippets:**
  - [ ] [Hotwire examples](https://github.com/thoughtbot/hotwire-example-template/branches/active) from Thoughtbot
  - [ ] [Better Stimulus](https://www.betterstimulus.com/)
  - [ ] [Stimulus-Use](https://stimulus-use.github.io/stimulus-use)
  - [ ] [Stimulus Components](https://www.stimulus-components.com/) for inspiration
- **Hotwire extensions:**
  - [ ] [TurboPower](https://github.com/marcoroth/turbo_power-rails)
  - [ ] [TurboBoost Commands](https://github.com/hopsoft/turbo_boost-commands)
  - [ ] [TurboBoost Streams](https://github.com/hopsoft/turbo_boost-streams)
  - [ ] [TurboBoost Elements](https://github.com/hopsoft/turbo_boost-elements)
- **Multi-platform:**
  - [ ] 💲[Ayush Newatia - The Rails and Hotwire Codex](https://railsandhotwirecodex.com/)
- **Other similar libraries:**
  - [ ] [HTMX](https://htmx.org/): read the book [Hypermedia Systems](https://hypermedia.systems) and/or watch [Carson Gross — Return To Hypermedia: Solving Javascript Fatigue Using Fundamental Web Architecture](https://youtu.be/LRrrxQXWdhI)

## Rails codebases to study

I've chosen the codebases below based on a these criteria:

- Is active, with recent commits.
- Does not use a JS framework on the front end, though I made exceptions.
- Is well-known *or* it solves a problem that's interesting to me.

If you want to explore more widely, here are other places to find open-source Ruby projects:

- [OpenSourceRails](https://opensourcerails.org/)
- [Ruby projects on CodeTriage](https://www.codetriage.com/?language=Ruby), though not all of them are Rails apps
- [Real World Rails](https://github.com/eliotsykes/real-world-rails) (and [how to search through it](https://www.hexdevs.com/posts/massive-list-of-open-source-ruby-on-rails-applications-you-can-use-as-a-reference/))
- [Awesome Ruby and Rails Open Source Apps](https://github.com/asyraffff/Open-Source-Ruby-and-Rails-Apps)

**Small codebases:** Less than 50k lines of Ruby code.

- [ ] [github.com/SpinaCMS/Spina](https://github.com/SpinaCMS/Spina) (5k lines): *CMS (Content Management System).*
- [ ] [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage) (6k lines): *Issue tracker for open-source projects.*
- [ ] [github.com/joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com) (12k lines): *The reverse job board for Ruby on Rails developers.*
- [ ] [github.com/RailsEventStore/ecommerce](https://github.com/RailsEventStore/ecommerce) (12k lines): *Example app showing DDD (Domain-Driven Design), CQRS, and Event Sourcing.*
- [ ] [github.com/lobsters/lobsters](https://github.com/lobsters/lobsters) (13k lines): *Hacker News clone.*
- [ ] [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase) (14k lines): *Learning platform for developers.*
- [ ] [github.com/houndci/hound](https://github.com/houndci/hound) (14k lines): *Automated code review for GitHub PRs.*
- [ ] [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org) (26k lines): *Where Ruby gems are hosted.*
- [ ] [github.com/AlchemyCMS/alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms) (36k lines): *CMS (Content Management System).*
- [ ] [github.com/SumOfUs/Champaign](https://github.com/SumOfUs/Champaign) (39k lines): *Digital campaigning platform. A Rails app generator.*

**Larger codebases:** More than 50k lines of Ruby code.

- [ ] [github.com/solidusio/solidus](https://github.com/solidusio/solidus) (72k lines): *E-commerce platform.*
- [ ] [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon) (75k lines): *Like Twitter but self-hosted and federated.*
- [ ] [github.com/openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork) (102k lines): *An online marketplace for local food.*
- [ ] [github.com/forem/forem](https://github.com/forem/forem) (103k lines): *Powers the blogging site [dev.to](https://dev.to/). Uses Preact on the front end.*
- [ ] [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall) (117k lines): *Publishes government content on [gov.uk](https://www.gov.uk/).*
- [ ] [github.com/decidim/decidim](https://github.com/decidim/decidim) (288k lines): *The participatory democracy framework.*
- [ ] [github.com/discourse/discourse](https://github.com/discourse/discourse) (322k lines): *Discussion forum platform. Has an Ember.js front end.*
- [ ] [github.com/instructure/canvas-lms](https://github.com/instructure/canvas-lms) (745k lines): *A popular LMS (learning management system).*
- [ ] [gitlab.com/gitlab-org/gitlab](https://gitlab.com/gitlab-org/gitlab) (1.8 million lines): *Like GitHub but with CI/CD and DevOps features built in. Has great [docs on architecture](https://docs.gitlab.com/ee/development/architecture.html).*

## Advanced Ruby and Rails

### Misc. Ruby/Rails

- **Advanced Rails:**
  - [x] 💲[Noah Gibbs - Rebuilding Rails](http://rebuilding-rails.com/)
  - [ ] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] [Ruby Science](https://github.com/thoughtbot/ruby-science) on design patterns in Rails
  - [ ] [Rails API docs](https://api.rubyonrails.org/)
- **Active Record:**
  - [x] [Upcase - Advanced ActiveRecord Querying](https://thoughtbot.com/upcase/advanced-activerecord-querying)
  - [ ] (upcoming) 💲[Jason Charnes - Active Record Cookbook](https://courses.jasoncharnes.com/active-record-cookbook)
  - [ ] 💲[Nate Berkopec - The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[Nate Berkopec - The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/) (not Rails-specific)
- **Advanced Ruby:**
  - [ ] Victor Shepelev (zverok) - [The Ruby Reference](https://rubyreferences.github.io/rubyref/) (Ruby 2.7) and [Ruby Changes](https://rubyreferences.github.io/rubychanges/3.0.html) (for Ruby 3+)
  - [ ] [Ruby Regexp](https://learnbyexample.github.io/Ruby_Regexp/preface.html)
  - [ ] 💲[Metaprogramming Ruby](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2/)
  - [ ] 💲[Joel Drapper - upcoming book on metaprogramming](https://ruby.social/@joeldrapper/109709614411147404)
  - [ ] [Jesse Storimer - Working with Ruby Threads](https://workingwithruby.com/wwrt/intro)
  - [ ] 💲[Ruby Under a Microscope](https://patshaughnessy.net/ruby-under-a-microscope)
- **Background jobs:**
  - [ ] [Nate Berkopec - Sidekiq in Practice](https://nateberk.gumroad.com/l/sidekiqinpractice)
- **Authentication:**
  - [ ] Steve Polito - [Rails Authentication from Scratch](https://github.com/stevepolitodesign/rails-authentication-from-scratch) and the derived [Rails MVP Authentication](https://github.com/stevepolitodesign/rails_mvp_authentication)
  - [ ] [Lázaro Nixon - Authentication Zero](https://github.com/lazaronixon/authentication-zero)
- **Rails deployment/DevOps:**
  - [ ] 💲[Josef Strzibny - Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Deploying Rails Applications](https://leanpub.com/deploying_rails_applications)
  - [ ] 💲[Efficient Rails DevOps](https://efficientrailsdevops.com/)
  - [ ] [Cameron Dutro - RailsConf talk "Kuby: Active Deployment for Rails Apps"](https://youtu.be/zbAslvHa7MI)
  - [ ] Guides to deploying Rails on AWS: [1](https://www.theelastic.guru/lee/how-to-build-a-ruby-on-rails-host-on-aws-for-beginners-232l), [2](https://www.honeybadger.io/blog/rails-6-aws-elastic-beanstalk/), [3](https://www.codewithjason.com/how-to-deploy-a-ruby-on-rails-application-to-aws/)

### Rails architecture

A.K.A. *where the heck do I put my business logic / how can I keep my models from getting huge?*

- **DDD (Domain-Driven Design):**
  - [x] [Getting modules right with Domain-driven Design](https://www.youtube.com/watch?v=Q_0XW46IlHY)
  - [ ] 💲[Learning Domain-Driven Design](https://www.oreilly.com/library/view/learning-domain-driven-design/9781098100124/)
- **Other approaches:**
  - [ ] (upcoming) 💲[Peter Solnica - Data Oriented Web Development with Ruby](https://solnic.podia.com/data-oriented-web-development-with-ruby)
  - [ ] 💲[Ryan Bigg - Maintainable Rails](https://leanpub.com/maintain-rails)
  - [ ] Try [contexts](https://nts.strzibny.name/business-logic-in-rails-with-contexts/), inspired by Phoenix
  - [ ] Learn about the repository pattern: [article](https://engineering.solarisbank.com/the-repository-pattern-in-ruby-with-the-active-record-library-f0445fa282c), [talk](https://www.youtube.com/watch?v=36LB8bfEeVc)
- **Browse the relevant gems:**
  - [ ] [dry-transaction](https://dry-rb.org/gems/dry-transaction)
  - [ ] [Interactor](https://github.com/collectiveidea/interactor)
  - [ ] [Sequent](https://www.sequent.io/) - CQRS and event sourcing
  - [ ] [Rails Event Store](https://github.com/RailsEventStore/rails_event_store) - for an event-driven architecture
  - [ ] [Ventable](https://github.com/kigster/ventable) - a variation of the Observer design pattern
  - [ ] [Wisper](https://github.com/krisleech/wisper) - the Publish-Subscribe design pattern
  - [ ] [Packwerk](https://github.com/Shopify/packwerk) - to enforce boundaries and modularize Rails applications
- **Review criticisms of the Active Record pattern:**
  - [ ] [Bob Martin - Active Record vs. Objects](https://sites.google.com/site/unclebobconsultingllc/active-record-vs-objects)
- **Review criticisms of service objects:**
  - [ ] [Jorge Manrubia - "Vanilla Rails is plenty"](https://dev.37signals.com/vanilla-rails-is-plenty)
  - [ ] [Jorge Manrubia - "Active Record, nice and blended"](https://dev.37signals.com/active-record-nice-and-blended/)
  - [ ] [Jared White - "Why Service Objects are an Anti-Pattern"](https://www.fullstackruby.dev/object-orientation/rails/2018/03/06/why-service-objects-are-an-anti-pattern/)
  - [ ] [Code with Jason #115](https://audio.buzzsprout.com/s73f2h4bgdux90r67nqq1e58h4hk?response-content-disposition=inline#t=882)
  - [ ] [Alex Barret - ActiveModel: An alternative to service objects](https://alexbarret.com/blog/2020/service-object-alternative/)
  - [ ] [Avdi Grimm - "Enough with the Service Objects Already"](https://avdi.codes/service-objects/)

## Expanding my horizons

- **How computers work:**
  - [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.informit.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100)
  - [ ] [NandGame](https://nandgame.com)
  - [x] *From Nand to Tetris* course ([Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2)), optionally with the textbook 💲[The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition)
  - [ ] 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
  - [x] 💲[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- **Compilers:**
  - [ ] [Crafting Interpreters](https://craftinginterpreters.com/)
- **Coding challenges:**
  - [ ] [CodeWars](https://www.codewars.com)
  - [ ] [Advent of Code](https://adventofcode.com/2022/events)
  - [ ] [Project Euler](https://projecteuler.net/)
  - [ ] Code katas: [awesome-katas](https://github.com/gamontal/awesome-katas) and [another list](https://hackmd.io/@pierodibello/A-curated-list-of-programming-kata)
- **Design patterns:**
  - [x] 💲[Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/)
  - [x] [Refactoring.Guru](https://refactoring.guru/)
- **Software architecture:**
  - [ ] 💲[Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
  - [ ] 💲[The Architecture of Open Source Applications](https://aosabook.org/en/index.html)
- **Monitoring:**
  - [ ] 💲[Practical Monitoring](https://www.oreilly.com/library/view/practical-monitoring/9781491957349/)
  - [ ] 💲[Observability Engineering](https://www.oreilly.com/library/view/observability-engineering/9781492076438/)
- **Misc.**
  - [ ] [Divio Documentation System](https://documentation.divio.com/)
- **Learn other app frameworks:** Jobs in Ruby are mostly in Rails, but it's still valuable to broaden my horizons and learn different approaches.
  - [ ] [Roda](https://roda.jeremyevans.net/) in its batteries-included form [via Bridgetown](https://www.bridgetownconf.rocks#talk-bridgetown-database-apps)
  - [ ] [Hanami](https://hanamirb.org/) which will also be easier than ever to get started with once it hits 2.1. Here's an example app: [github.com/decafsucks/decafsucks](https://github.com/decafsucks/decafsucks). And another: [github.com/bkuhlmann/hemo](https://github.com/bkuhlmann/hemo)
  - [ ] [Lucky](https://luckyframework.org/), a web framework for [Crystal](https://crystal-lang.org/)… which is not Ruby but it's close 😉 Here's a handy starting point: [Crystal for Rubyists](https://www.crystalforrubyists.com/). You can even use Crystal alongside a Ruby app, for background jobs: [github.com/crimson-knight/fruit_juice](https://github.com/crimson-knight/fruit_juice).

## Other resource lists

- [Back-End (Ruby) track at Turing School](https://backend.turing.edu/module1/)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [p1xt Computer Science and Programming](https://github.com/P1xt/p1xt-guides)
- [Open Source Society University](https://github.com/ossu/computer-science)
- [roadmap.sh](https://roadmap.sh/)
