# How to Stream Publicly Available TV Over the Internet

- [Simple](#vlc-media-player-to-view-m3u-urls) use VLC Media player configured with the step by step instructions below (everything before advanced).
    - Note that the provided links may break over time. 
    - I personally haven't developed / contributed to this project, and this readme may at any point in time contain links to repositories that are no longer maintained.
    - For trouble-shooting, FAQ stuff, and even legal questions, please see the linked [IPTV repo](https://github.com/iptv-org/iptv/). 
- [Advanced](#advanced) use the linked github repository to search for and even build your own m3u links using community created / maintained tools.
    - Some development skills may or may not be required. 
    - Additional IPTV tools and goodies are provided.
    - Lists of other applications that can be used / documentation / etc. are available in thier resources lists.

# VLC Media player to view m3u URLs

*Before proceeding, please note that no video files is stored by me, or the iptv-org repository. To my understanding, the links are displaying publicly available streaming content that is not saved / stored. At the time of writing, this is a paraphrasing of what is posted within the readme file on their repo. If you feel the need to learn more, see their [Legal](#legal) section, and [FAQ](#faq)  that I pasted for convenience. However, I do not maintain this document. To access their most up to date details, please see thier repository on [GitHub](https://github.com/iptv-org/iptv/).*

### Process:
1. Download and Install VLC Media Player
2. Open VLC Media Player
3. Access the ‘Media’ Menu
4. Select ‘Open Network Stream’
5. Enter the M3U8 URL
    - Note - You can also download link as a file by clicking on it or pasting it into a web browser, and and then uploading the file.

6. Click ‘Play’

# Resources

### Example Links that (should work) without any fuss:

- https://iptv-org.github.io/iptv/countries/us.m3u
- https://iptv-org.github.io/iptv/languages/eng.m3u
- https://iptv-org.github.io/iptv/countries/uk.m3u


### For a massive list of all available channels: 

- https://iptv-org.github.io/iptv/index.m3u


 *The base url below can also be used to look for new link through the github repository's public github pages site. (Github's free hosting service).*

- https://iptv-org.github.io/ 


# Advanced
### For dev/research/etc. 

* Navigating the [GitHub repo](https://github.com/iptv-org/iptv/) will lead you to more links you may use. I included the "read me" file from the repo below -- which contains "how to" / "FAQ" / and other nice to know things.


* Cloning the repository

    - If you are familiar with using a terminal / command line interface, have a Github account with the proper credentials stored, you may want to "clone" the repo to your local computer. This will give you access to what files are online on your own computer instead of having to go to the GitHub again.

    - They also provide access to tools that can be explored for creating your own m3u links and other things. 
    
        - [More from the IPTV Github](https://github.com/iptv-org/)

    - Otherwise, you can also download the repository and others posted on their GitHub as a zip file.  Either way, this will only provide the files that can be run with the proper development environment set up. 


Example of command to clone a repo using git:

```bash
git clone https://github.com/Free-TV/IPTV.git
```
#### Link to the [IPTV repo](https://github.com/iptv-org/iptv/) - which will be updated and maintained by developers and other users of the service. 

*read me as of 10/xx/2024*:
# IPTV [![update](https://github.com/iptv-org/iptv/actions/workflows/update.yml/badge.svg)](https://github.com/iptv-org/iptv/actions/workflows/update.yml)

Collection of publicly available IPTV (Internet Protocol television) channels from all over the world.

## Table of contents

- 🚀 [How to use?](#how-to-use)
- 📺 [Playlists](#playlists)
- 🗓 [EPG](#epg)
- 🗄 [Database](#database)
- 👨‍💻 [API](#api)
- 📚 [Resources](#resources)
- 💬 [Discussions](#discussions)
- ❓ [FAQ](#faq)
- 🛠 [Contribution](#contribution)
- ⚖ [Legal](#legal)
- © [License](#license)

## How to use?

Simply insert one of the links below into [any video player](https://github.com/iptv-org/awesome-iptv#apps) that supports live streaming and press _Open_.

![VLC Network Panel](https://github.com/iptv-org/iptv/raw/master/.readme/preview.png)

## Playlists

There are several versions of playlists that differ in the way they are grouped. As of January 30th, 2024, we have stopped distributing NSFW channels. For more information, please look at [this issue](https://github.com/iptv-org/iptv/issues/15723).

### Main playlist

This playlist includes all known channels available in this repository.

```
https://iptv-org.github.io/iptv/index.m3u
```

### Grouped by category

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _category_ as a group title:

```
https://iptv-org.github.io/iptv/index.category.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
#include "./.readme/_categories.md"

</details>

### Grouped by language

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _language_ as a group title:

```
https://iptv-org.github.io/iptv/index.language.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
#include "./.readme/_languages.md"

</details>

### Grouped by country

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _country_ as a group title:

```
https://iptv-org.github.io/iptv/index.country.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
#include "./.readme/_countries.md"

</details>

### Grouped by region

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _region_ as a group title:

```
https://iptv-org.github.io/iptv/index.region.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
#include "./.readme/_regions.md"

</details>

## EPG

[Electronic Program Guide](https://en.wikipedia.org/wiki/Electronic_program_guide) for most of the channels can be downloaded using utilities published in the [iptv-org/epg](https://github.com/iptv-org/epg) repository.

## Database

All channel data is taken from the [iptv-org/database](https://github.com/iptv-org/database) repository. If you find any errors please open a new [issue](https://github.com/iptv-org/database/issues) there.

## API

The API documentation can be found in the [iptv-org/api](https://github.com/iptv-org/api) repository.

## Resources

Links to other useful IPTV-related resources can be found in the [iptv-org/awesome-iptv](https://github.com/iptv-org/awesome-iptv) repository.

## Discussions

If you need help finding a channel, have a question or idea, welcome to the [Discussions](https://github.com/orgs/iptv-org/discussions).

## FAQ

The answers to the most popular questions can be found in the [FAQ.md](FAQ.md) file.

## Contribution

Please make sure to read the [Contributing Guide](CONTRIBUTING.md) before sending an issue or making a pull request.

And thank you to everyone who has already contributed!

### Backers

<a href="https://opencollective.com/iptv-org"><img src="https://opencollective.com/iptv-org/backers.svg?width=890" /></a>

### Contributors

<a href="https://github.com/iptv-org/iptv/graphs/contributors"><img src="https://opencollective.com/iptv-org/contributors.svg?width=890" /></a>

## Legal

No video files are stored in this repository. The repository simply contains user-submitted links to publicly available video stream URLs, which to the best of our knowledge have been intentionally made publicly by the copyright holders. If any links in these playlists infringe on your rights as a copyright holder, they may be removed by sending a [pull request](https://github.com/iptv-org/iptv/pulls) or opening an [issue](https://github.com/iptv-org/iptv/issues/new?assignees=freearhey&labels=removal+request&template=--removal-request.yml&title=Remove%3A+). However, note that we have **no control** over the destination of the link, and just removing the link from the playlist will not remove its contents from the web. Note that linking does not directly infringe copyright because no copy is made on the site providing the link, and thus this is **not** a valid reason to send a DMCA notice to GitHub. To remove this content from the web, you should contact the web host that's actually hosting the content (**not** GitHub, nor the maintainers of this repository).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](LICENSE)
