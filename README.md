[![Build Status](https://travis-ci.com/countervandalism/CVNBot.svg?branch=master)](https://travis-ci.com/countervandalism/CVNBot)

CVNBot
==================================================


Quick start
----------

Clone the repo, `git clone git://github.com/countervandalism/CVNBot.git`, or
[download the latest
release](https://github.com/countervandalism/CVNBot/zipball/master).


Versioning
----------

We use the Semantic Versioning guidelines as much as possible.

Releases will be numbered in the following format:

`<major>.<minor>.<patch>`

The `-alpha` suffix is used to indicate unreleased versions in development.

For more information on SemVer, please visit https://semver.org/.


Build
----------
The software is written in C#.

Supported runtimes:
* Mono **6.8**
* .NET Core **3.1**

Recommended installation methods:

* For Linux, install [`mono-complete`](https://packages.debian.org/search?keywords=mono-complete) from Debian, or [latest from mono-project.com](https://www.mono-project.com/download/stable/#download-lin),
* For Mac, install [Visual Studio for Mac](https://www.visualstudio.com/vs/visual-studio-mac/) (enable Mono and .NET during installation), or for command-line see [monodevelop.com](https://www.monodevelop.com/download/).
* For Windows, install [Visual Studio](https://visualstudio.microsoft.com/vs/) (enable Mono and .NET during installation) or for command-line see [monodevelop.com](https://www.monodevelop.com/download/).

Then use your IDE to open, build and run the project. Or, if using the command line:

Build:

```bash
countervandalism/CVNBot:$ msbuild src/CVNBot.sln /p:Configuration=Debug
```

Run:

```bash
countervandalism/CVNBot:$ mono src/CVNBot/bin/Debug/CVNBot.exe
```

The above is for targetting local development, see [Installation](./docs/install.md) for the recommended way to run CVNBot in production.

Bug tracker
-----------

Found a bug? Please report it using our [issue
tracker](https://github.com/countervandalism/CVNBot/issues)!


Documentation, support and contact
-----------
* [Documentation (wiki)](https://github.com/countervandalism/CVNBot/wiki/Documentation)
* <irc://irc.freenode.net/#countervandalism>
* [cvn@lists.wikimedia.org](https://lists.wikimedia.org/mailman/listinfo/cvn) (Requires subscription before posting. [Subscribe here](https://lists.wikimedia.org/mailman/listinfo/cvn))


Copyright and license
---------------------

See [LICENSE](https://raw.github.com/countervandalism/CVNBot/master/LICENSE.txt).
