# github-console

**Pure javascript cross-platform GitHub console application**

[![version](https://img.shields.io/npm/v/github-console.svg)](https://www.npmjs.org/package/github-console)
[![downloads](https://img.shields.io/npm/dt/github-console.svg)](https://www.npmjs.org/package/github-console)
[![node](https://img.shields.io/node/v/github-console.svg)](https://nodejs.org/)

## Similar Packages

## Installation
`npm install -g github-console`
`npm uninstall -g github-console`

## Basic Usage
```console

ght login
gth add UNAME -t TOKEN 
gth set UNAME
gth del UNAME
gth user
gth dbfile //info
gth check
gth optimize
ght limit
//
gth list --follower --following --fback --uback --limit 100 //unfollowed
gth follow UNAME --limit -fback
gth unfollow UNAME --limit --uback --oldest --notactive
gth sync
gth star UNAME
gth metric --all --limit
gth blacklist --add UNAME --auto --reset
gth best UNAME <follower,following,project> --limit 
gth rank UNAME //Rank a user's followers.
//
gth auto --star
//

```
## Options


## Test
* `mocha` or `npm test`
* Check [test folder](https://gitlab.com/autokent/pdf-parse/tree/master/test) and [quickstart.js](https://gitlab.com/autokent/pdf-parse/blob/master/quickstart.js) for extra usages.

## Support
I use this package actively myself, so it has my top priority. You can chat on WhatsApp about any infos, ideas and suggestions.

[![WhatsApp](https://img.shields.io/badge/style-chat-green.svg?style=flat&label=whatsapp)](https://api.whatsapp.com/send?phone=905063042480&text=Hi%2C%0ALet%27s%20talk%20about%20pdf-parse)

[![Telegram](https://img.shields.io/badge/style-chat-green.svg?style=flat&label=telegram)](https://t.me/MKozan)


### Submitting an Issue
If you find a bug or a mistake, you can help by submitting an issue to [GitHub Repository](https://github.com/mehmet-kozan/github-console/issues)

### Creating a Merge Request
GitLab calls it merge request instead of pull request.  

* [A Guide for First-Timers](https://lab.github.com/lmachens/git-and-github-first-timers)
* [How to create a pull request](https://docs.github.com/articles/creating-a-pull-request)
* Check [Contributing Guide](https://github.com/mehmet-kozan/github-console/blob/main/CONTRIBUTING.md) 

## License
[MIT licensed](https://github.com/mehmet-kozan/github-console/blob/main/LICENSE) and all it's dependencies are MIT or BSD licensed.
