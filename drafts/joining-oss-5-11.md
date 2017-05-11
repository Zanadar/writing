++
draft = true
++

# How to Join an existing open source project

Lets assume you’re convinced that contributing to open soruce is something oyu want to do.  When I started, I had this assumption pretty drilled into me, but it’s hard to get started! And scary!  Let me just assure you: If you find it hard to know where to start, its not you; its hard for everyone!

This point aims to demystify the process by way of a story.  At Stride, we have an Open Source Club. At the club, we don’t just work on open source (although that’s part of it); we also work on the process of open source (how do you run a project, how can you be an effective member of a project).  A number of the members of the club are relatively new to OSS an were curious how they’d join a project, so we, as a group contributed to ESlint. This is the story of that contribution, framed as examples of general guidelines that could be applied to any project.

### Evaulutation 🤔
Assuming that you have a few projects in mind that you might want to contribute to, how do you evaluate whether its worth your time to break into the project. What are the signs of a good, healthy, worth-your-time project?
Here’s a general list of things to look for
- **Attention to the contributors time:** this shows up in Labelled issues (ESlint has issue labelled as `beginner` and `documentation`) a contribution. A working build step (this could be a makefile, steps documented in a readme or contributing.md
- **Tests:** This is not only just a good thing in terms of engineering practice, but tests act as documentation and guiderails when you’re adding things or changing the code
- **Active Community:** How fast do issues and questions get addressed?  ESlint has lots of issues, but questions get answered super fast.  They have a gitter (a slack-like chatroom) where I got questions answered really quickly; they even picked out some `beginner` issues for us to work on.
- **Welcoming Community:** This matters.  ESLint has a gitter chat room, and people on their were super friendly when we asked about beginner issues, even labelling a few for us to work on. Labelled issues like `beginner` or `first-time` or by familiarity level make it easy to pick something to start on.  A **Code of Conduct** is also a part of welcoming community, as it makes the standards of behavior clear and open.
- **Governance Model:** Is it OSS in name only (ie a product created in the open, but with only commercial concerns). This isn't inherently bad, but it'll likely effect how the project runs.

Some anti-patterns to consider:
  - Popularity:  Super popular projects can be frustrating to get started in as issues get snapped up really fastx
  - Rude people in issues
  - Tumbleweeds (super old issues, commits, etc) Not always bad, because you might be able to take ownership over an important project, but maybe not when you're starting out
  - Only core members in commits
  - Open in name only (basically its controlled by one company or its their product)
  - Super complicated build, or you can't build it all
  - No documentation or test
  
  ### What to work on? 🔍
Landing that first PR is an awesome experience, and if you can pick something that ultimately kinda simple, you'll also get to overcome the hurdles of learning the actual contribution process and not get too bogged down in the details of fixing code in an unfamiliar codebase; next time, you can focuse on something in the code, and the process itself won't be a blocker. Docs are often a good first step, because they force you to learn a little bit about the code, but working on them is mostly about writing and then getting through the contribution process.  On ESlint, we found an bug report, that turned out to be a result of some unclarity in the documentation. The actual change was rather minor, adding a few words and a sentence. But we had to do a few things that are unfamiliar to new OSS folks:
1. Fork.  I've done this a lot, and I had to [look on Github](https://help.github.com/articles/fork-a-repo/) almost every time for about the first year.
2. Make changes that follow the style and conventions of the project.
3. Commit in the style of the project.  Some projects have commit templates that you need to follow
3. Make a PR in the style of the project. ESlint provides nice markdown templates and very clear instructions for PRs of various sorts (Docs, bug fixes, etc.) which all follow differant formats.
4. Sign a Contributors License Agreement. This basically certifies your right to contribute code.
3. Make the bots happy! 🤖 ESlint and other projects use bots to automatically enforce conventions in code, commits, and PRS. Usually these are a first gate to get through to getting a merge.
4. Discussion with the project maintainers and changes. This is often a decent back and forth, with tweaks and comments. Overwhelmingly on healthy projects this is a fun and productive exchange that drastically improves the quality of your contributions.

Thats a pretty long list!
 - Docs are always a low hanging fruit
 - (Floor sweeping)
 - You learn about the contribution process, so that can be the focus, rather than writing the code
 - Sometimes there are issues, sometimes you can just add or do copy editing
 - Gardening (checking out old or stale PRs and issues)
 - A bug you encountered -> write a test to verify, then fix it. File an issue and a PR.
 - Adding test coverage
 - Refactotum -> Refactoring in order to add tests
 - Sometimes issues are labelled beginner or first time contributor
IV. Doing it
  - Read the docs on contributing. Projects have their own process, formats for commits, etc.
  - Forking is the usual process. Go into what this means. (find a good post about this). I look at github almost every time i have to do this. Theirs lots of github magic. Its intimidating.
  - Write code or whatever.
  - Also the PR formats, signing a CLA, making the bots happy, etc. (most larger projects have lint, etc. bots)
V. Closing it out (seeing this through to acceptance and merge)
You have to be willing to work through small issues and take critical feedback (core values)
This is good, helps 
Changes to wording, etc.  bigger projects may be more fiddly
VI. Summary


- Example: ESlint
- Gitter Channel
- Help wanted, Beginner
- Beginner
- Maybe not `core`
- Looking at closed issues:
- Do they have lots of communication?  ++ Easy get help
- Simple issue: https://github.com/eslint/eslint/issues/7984
- Add something to the FAQ noting the difference b/w parserOptions and env: {es6: true}
- What the hell is forking? (https://help.github.com/articles/fork-a-repo/)
- https://github.com/eslint/eslint/pull/8350

- Docs can be a soft entry into the project through documentation fixes
- ESlint is a good project, as they are quite responsive on their gitter and on issues.

