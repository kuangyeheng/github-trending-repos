<div align="center"><img src="https://user-images.githubusercontent.com/1473072/33020417-45869a00-ce0f-11e7-9faa-368445d463f7.gif" alt="Stars counter"/></div>
<h1 align="center">GitHub Trending Repos</h1>
<a href="https://circleci.com/gh/vitalets/github-trending-repos"><img src="https://circleci.com/gh/vitalets/github-trending-repos.svg?style=svg" alt="CircleCI"/></a>

A way to subscribe on new [GitHub trending repositories](https://github.com/trending) in your favorite programming language.
Updates come as [GitHub notifications] once a day or a week.

## How it works
1. Every issue in this repo is related to a particular programming language
2. You can subscribe to comments in the issue by pressing <img alt="subscribe button" valign="middle" src="https://user-images.githubusercontent.com/1473072/32487280-46f4489c-c3ba-11e7-82d7-cfe073cac8d1.png"> button
3. Scheduled script grabs trending repos per language on daily and weekly basis
4. If there are new repos - the script drops a comment to the corresponding issue
5. All issue subscribers receive GitHub notification in the web interface <img alt="notification icon" valign="bottom" src="https://user-images.githubusercontent.com/1473072/32723023-01555c78-c87d-11e7-8190-6bf3bb0ec405.png"> or by email

## Schedule
You can choose the following subscription types:
* Daily: runs **every day at 00:00 UTC**, see issues labeled with [trending-daily](https://github.com/vitalets/github-trending-repos/labels/trending-daily)
* Weekly: runs **every friday at 02:00 UTC**, see issues labeled with [trending-weekly](https://github.com/vitalets/github-trending-repos/labels/trending-weekly)

## Examples
Once a day (or a week) you get a notification in GitHub web interface:  
![Example of web notification](https://user-images.githubusercontent.com/1473072/32488601-4295b138-c3be-11e7-8eb2-18a624c54ca2.png)

After click you are navigated to the first unread comment with new trends in selected language:  
![Example of comment](https://user-images.githubusercontent.com/1473072/33029917-f054b67c-ce2a-11e7-9b42-a7ee16d98228.png)

## Available languages
Many languages are available for subscription:

* 1C Enterprise ([daily](https://github.com/vitalets/github-trending-repos/issues/43))
* C ([daily](https://github.com/vitalets/github-trending-repos/issues/33) | [weekly](https://github.com/vitalets/github-trending-repos/issues/21))
* C# ([daily](https://github.com/vitalets/github-trending-repos/issues/31) | [weekly](https://github.com/vitalets/github-trending-repos/issues/19))
* C++ ([daily](https://github.com/vitalets/github-trending-repos/issues/29) | [weekly](https://github.com/vitalets/github-trending-repos/issues/17))
* CSS ([daily](https://github.com/vitalets/github-trending-repos/issues/30) | [weekly](https://github.com/vitalets/github-trending-repos/issues/18))
* Clojure ([daily](https://github.com/vitalets/github-trending-repos/issues/104) | [weekly](https://github.com/vitalets/github-trending-repos/issues/105))
* Common Lisp ([weekly](https://github.com/vitalets/github-trending-repos/issues/91))
* Crystal ([daily](https://github.com/vitalets/github-trending-repos/issues/80) | [weekly](https://github.com/vitalets/github-trending-repos/issues/81))
* Dart ([daily](https://github.com/vitalets/github-trending-repos/issues/102) | [weekly](https://github.com/vitalets/github-trending-repos/issues/103))
* Elixir ([daily](https://github.com/vitalets/github-trending-repos/issues/82) | [weekly](https://github.com/vitalets/github-trending-repos/issues/83))
* Elm ([daily](https://github.com/vitalets/github-trending-repos/issues/87) | [weekly](https://github.com/vitalets/github-trending-repos/issues/88))
* Emacs Lisp ([daily](https://github.com/vitalets/github-trending-repos/issues/89) | [weekly](https://github.com/vitalets/github-trending-repos/issues/90))
* Erlang ([daily](https://github.com/vitalets/github-trending-repos/issues/98) | [weekly](https://github.com/vitalets/github-trending-repos/issues/99))
* F# ([weekly](https://github.com/vitalets/github-trending-repos/issues/84))
* Go ([daily](https://github.com/vitalets/github-trending-repos/issues/32) | [weekly](https://github.com/vitalets/github-trending-repos/issues/20))
* Haskell ([daily](https://github.com/vitalets/github-trending-repos/issues/46) | [weekly](https://github.com/vitalets/github-trending-repos/issues/47))
* Haxe ([daily](https://github.com/vitalets/github-trending-repos/issues/111) | [weekly](https://github.com/vitalets/github-trending-repos/issues/112))
* Java ([daily](https://github.com/vitalets/github-trending-repos/issues/8) | [weekly](https://github.com/vitalets/github-trending-repos/issues/12))
* JavaScript ([daily](https://github.com/vitalets/github-trending-repos/issues/5) | [weekly](https://github.com/vitalets/github-trending-repos/issues/16))
* Jupyter Notebook ([daily](https://github.com/vitalets/github-trending-repos/issues/109) | [weekly](https://github.com/vitalets/github-trending-repos/issues/110))
* Kotlin ([daily](https://github.com/vitalets/github-trending-repos/issues/92) | [weekly](https://github.com/vitalets/github-trending-repos/issues/93))
* Lua ([daily](https://github.com/vitalets/github-trending-repos/issues/76) | [weekly](https://github.com/vitalets/github-trending-repos/issues/77))
* Nim ([daily](https://github.com/vitalets/github-trending-repos/issues/78) | [weekly](https://github.com/vitalets/github-trending-repos/issues/79))
* Nix ([daily](https://github.com/vitalets/github-trending-repos/issues/96) | [weekly](https://github.com/vitalets/github-trending-repos/issues/97))
* OCaml ([daily](https://github.com/vitalets/github-trending-repos/issues/85) | [weekly](https://github.com/vitalets/github-trending-repos/issues/86))
* Objective-C ([daily](https://github.com/vitalets/github-trending-repos/issues/38) | [weekly](https://github.com/vitalets/github-trending-repos/issues/26))
* PHP ([daily](https://github.com/vitalets/github-trending-repos/issues/10) | [weekly](https://github.com/vitalets/github-trending-repos/issues/14))
* Pascal ([weekly](https://github.com/vitalets/github-trending-repos/issues/41))
* Perl ([daily](https://github.com/vitalets/github-trending-repos/issues/94) | [weekly](https://github.com/vitalets/github-trending-repos/issues/95))
* PowerShell ([daily](https://github.com/vitalets/github-trending-repos/issues/106) | [weekly](https://github.com/vitalets/github-trending-repos/issues/107))
* Prolog ([weekly](https://github.com/vitalets/github-trending-repos/issues/108))
* PureScript ([daily](https://github.com/vitalets/github-trending-repos/issues/100) | [weekly](https://github.com/vitalets/github-trending-repos/issues/101))
* Python ([daily](https://github.com/vitalets/github-trending-repos/issues/7) | [weekly](https://github.com/vitalets/github-trending-repos/issues/11))
* R ([weekly](https://github.com/vitalets/github-trending-repos/issues/39))
* Racket ([weekly](https://github.com/vitalets/github-trending-repos/issues/115))
* Ruby ([daily](https://github.com/vitalets/github-trending-repos/issues/9) | [weekly](https://github.com/vitalets/github-trending-repos/issues/13))
* Rust ([daily](https://github.com/vitalets/github-trending-repos/issues/44) | [weekly](https://github.com/vitalets/github-trending-repos/issues/45))
* Scala ([daily](https://github.com/vitalets/github-trending-repos/issues/37) | [weekly](https://github.com/vitalets/github-trending-repos/issues/25))
* Shell ([daily](https://github.com/vitalets/github-trending-repos/issues/35) | [weekly](https://github.com/vitalets/github-trending-repos/issues/23))
* Swift ([daily](https://github.com/vitalets/github-trending-repos/issues/36) | [weekly](https://github.com/vitalets/github-trending-repos/issues/24))
* TypeScript ([daily](https://github.com/vitalets/github-trending-repos/issues/34) | [weekly](https://github.com/vitalets/github-trending-repos/issues/22))
* Verilog ([daily](https://github.com/vitalets/github-trending-repos/issues/50))

If you'd like to add new language - feel free to [open an issue](https://github.com/vitalets/github-trending-repos/issues/new).

## Specials

* Trending repos across all languages ([daily](https://github.com/vitalets/github-trending-repos/issues/6) | [weekly](https://github.com/vitalets/github-trending-repos/issues/15))
* Trending repos in unknown languages ([daily](https://github.com/vitalets/github-trending-repos/issues/28) | [weekly](https://github.com/vitalets/github-trending-repos/issues/27))

## Watching the repo
If you start watching this repo - you will receive **many** notifications about trends in all languages.
It's more convenient to selectively subscribe on issues you are interested in.

## Alternatives
* Newsletter:
  * [Official GitHub Explore Newsletter](https://github.com/explore#newsletter)
  * [Changelog Nightly](https://changelog.com/nightly)
  * [GitLogs](http://www.gitlogs.com/)
* Twitter bot: [@TrendingGithub](https://twitter.com/TrendingGithub)
* Browser extension: [Githunt](https://github.com/kamranahmedse/githunt)
* RSS feed: [github-trends.ryotarai.info](http://github-trends.ryotarai.info/)
* Webpage with extra filters: [gitmostwanted.com/trending](http://gitmostwanted.com/trending/)
* Daily updated repo: [josephyzhou/github-trending](https://github.com/josephyzhou/github-trending)

None of alternatives can *send notifications per programming language*. That's why I've created this project.

&copy; 2017-2018 [Vitaliy Potapov](https://github.com/vitalets)

[trending-daily]: https://github.com/vitalets/github-trending-repos/labels/trending-daily
[trending-weekly]: https://github.com/vitalets/github-trending-repos/labels/trending-weekly
[GitHub notifications]: https://help.github.com/articles/accessing-your-notifications/
