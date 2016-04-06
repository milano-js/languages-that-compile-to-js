# Languages that compile to JS

There are now [hundreds](https://github.com/jashkenas/coffeescript/wiki/list-of-languages-that-compile-to-js) of languages compiling to JavaScript. Some people hate them all, and insist there is only one true JS. Others believe the one they use is vastly superior to any alternative because it has more stars on GitHub, followers on Twitter, or posts about it on Medium.

This is frankly stupid. We don't pretend complete objectivity is possible, but we want to try to analyse these languages with a more rigorous and scientific approach. We have prepared a set of standard questions you should probably ask when you see yet another compile-to-js project being touted as the Next Big Thing. The original list was suggested by [@gcanti](https://github.com/gcanti) on the [MilanoJS Slack](http://milanojs.herokuapp.com/), but the list itself is open to discussion.

## The questions

1. What does the type system look like?
2. Is there a stable version?
3. Is it under active development?
4. What is its [bus factor](https://en.wikipedia.org/wiki/Bus_factor)?
5. Does it support Dead Code Elimination?
6. How many libraries have been written or ported to it?
7. What is the size of the runtime?
8. Is it easy to integrate with the front-end toolchain (webpack, browserify, etc...)?
9. Is it easy to integrate with JS libraries (ffi, definition file, etc...)?
10. Is the language consistent?
11. Is the output readable?
12. How difficult is to hire a developer?

## The methodology

If you've seen a compile-to-JS language that sparked your attention and think you know the answer to all of the questions, create a new Markdown file named [language-name].md and open a pull request. Try to provide references and links for all of your claims. If you are unsure about one of the questions, say it openly in the pull request and ask for help.

## The summary table

Once we have at least 3 or 4 languages in the repo, we'll create a summarised view as part of this README file. Try to provide a 10-character summary for your longer answers, and it will be used in the summary table.

## Bikeshedding

Wikipedia has a [nice story](https://en.wikipedia.org/wiki/Law_of_triviality) about people tasked with designing a nuclear power plant who ended up debating for hours the colour of the bike shed. This is kind of a perfect metaphor for many discussions about JavaScript. Before opening a pull request, or adding a comment to an existing one, stop for a second and think if you're talking about the bike shed.
