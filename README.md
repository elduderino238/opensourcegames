# Open Source Games

**[Dynamic HTML table](https://trilarion.github.io/opensourcegames/)** of the entries / Development **[Blog](https://trilarion.blogspot.com/search/label/osgames)** / **[Statistics](statistics.md#statistics)**

[comment]: # (start of autogenerated content, do not edit)
**[Games](entries/tocs/_games.md#Games)** (1367) - **[Tools](entries/tocs/_tools.md#Tools)** (43) - **[Frameworks](entries/tocs/_frameworks.md#Frameworks)** (91) - **[Libraries](entries/tocs/_libraries.md#Libraries)** (44)

By category: **[Action](entries/tocs/_action.md#action)** (255), **[Adventure](entries/tocs/_adventure.md#adventure)** (56), **[Arcade](entries/tocs/_arcade.md#arcade)** (146), **[Board](entries/tocs/_board.md#board)** (26), **[Cards](entries/tocs/_cards.md#cards)** (18), **[Educational](entries/tocs/_educational.md#educational)** (13), **[Framework](entries/tocs/_framework.md#framework)** (91), **[Game engine](entries/tocs/_game-engine.md#game-engine)** (126), **[Library](entries/tocs/_library.md#library)** (44), **[Music](entries/tocs/_music.md#music)** (14), **[Platform](entries/tocs/_platform.md#platform)** (64), **[Puzzle](entries/tocs/_puzzle.md#puzzle)** (147), **[Remake](entries/tocs/_remake.md#remake)** (530), **[Role playing](entries/tocs/_role-playing.md#role-playing)** (209), **[Simulation](entries/tocs/_simulation.md#simulation)** (118), **[Sports](entries/tocs/_sports.md#sports)** (25), **[Strategy](entries/tocs/_strategy.md#strategy)** (290), **[Tool](entries/tocs/_tool.md#tool)** (43), **[Visual novel](entries/tocs/_visual-novel.md#visual-novel)** (6)

By platform: **[Windows](entries/tocs/_windows.md#windows)** (485), **[Linux](entries/tocs/_linux.md#linux)** (472), **[macOS](entries/tocs/_macos.md#macos)** (273), **[Android](entries/tocs/_android.md#android)** (138), **[iOS](entries/tocs/_ios.md#ios)** (17), **[Web](entries/tocs/_web.md#web)** (142)

[comment]: # (end of autogenerated content)

A list of open source games sorted by genre. The projects are at least in beta stage with a code basis that builds
into an executable demo. The code must be under a [FOSS](https://en.wikipedia.org/wiki/FOSS) license that allows
modification and sharing by others. For each entry, relevant information is collected regarding code repositories,
download possibilities and build instructions.

Similar collections include [Open Source Clones](https://github.com/opengaming/osgameclones) of popular games;
Popular games, add-ons, maps, etc. [hosted on GitHub](https://github.com/leereilly/games); [List of open-source video games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) on Wikipedia or the [LibreGameWiki](https://libregamewiki.org/Main_Page).

## Contribute

To add or modify entries, please use the [Issue tracker](https://github.com/Trilarion/opensourcegames/issues),
or fork this repository and submit a pull request.

### Adding a new entry

Checklist for a new entry

- Must be a game, a game maker, a game's tool, a framework or a library, used in games
- Must be under a FOSS license (GPL, MIT, ...) and code must be available
- Must be mature or at least in beta (with an executable demo)
- Active or inactive is irrelevant.

All entries are stored as [markdown](https://en.wikipedia.org/wiki/Markdown) text with some specific conventions.
Adding a new entry is as easy as modifying the [template](games/template.md) and adding the modified markdown file in a subdirectory of [games](games).

Description of the fields in the template. Comments start with "//".

<pre>
# {NAME} // name of the game

_{Description}_ // single description line (typically taken from about page of game)

- Home: {URL} // project main site(s) (most significant first)
- Media: {URL} // (optional) links to wikipedia and other significant mentions
- State: {XX} // one of {beta, mature} and optional "inactive since YEAR"
- Play: {URL} // (optional) link(s) to online play possibility
- Download: {URL} // (optional) link(s) to download binary (or source) releases
- Platform: {XX} // (optional) list of supported platforms {Linux, Windows, macOS, Android, ..}
- Keywords: {XX} // list of tags describing the game, first tage is the main category tag
- Code repository: {URL} // code repositories (most significant first)
- Code language: {XX} // programming language(s) used 
- Code license: {XX} // license of the code, use "Custom" with comment in () if the license is project-specific
- Code dependencies: {XX} // (optional) important third party libraries / frameworks used by the project
- Assets license: {XX} // (optional) license(s) of the assets (artwork, ..)

// whatever you want to put here

## Building

- Build system: {XX} // (optional) typically one of {CMake, Autoconf, Gradle, ..}
- Build instructions: {URL} // (optional) link(s) to build instructions offered by the project

// whatever you want to put here
</pre>

- If there are multiple links, licenses, ... separate them by comma.
- The same link can be assigned to different fields (home could also be the code repository, etc.).
- Put comments in "()" parentheses (do not put commas in comments).
- Remove lines with fields that do not apply to the project or where information is not available otherwise.
- Status active is implied/default unless the optional "inactive since" is present
- All lines starting with '- ' are considered fields.

Help: [MarkDown Help](https://help.github.com/articles/github-flavored-markdown), [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Background

I love open source projects and games and I am interested in learning more about building systems.
I see the following benefits of having this database.

- General information about open source games
- Possibility of improving build instructions on the projects side (not all projects actually have build instructions)
- Revival of abandoned games that do not build anymore
- Conversion of old repository formats like CVS to Git

## Disclaimer
 
No warranty whatsoever of the information presented herein for any purpose. There could (will) be errors in here.

## License

See [LICENSE](LICENSE). This work is dedicated to the public domain by waiving all rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

Additionally, the content is also licensed (multi-licensed) under the following other licenses: [WTFPL](http://www.wtfpl.net/txt/copying/), [CC-BY-3.0](https://creativecommons.org/licenses/by/3.0/),
[GFDL 1.3](https://www.gnu.org/licenses/fdl-1.3.txt) and given to the Public Domain (wherever it exists and to the maximum possible extent).

I hope that this does the trick. But really, just use the content however you like.
