<div align="center">
  <img src="assets/invidious-colored-vector.svg" width="192" height="192" alt="Invidious logo">
  <h1>Invidious</h1>

  <a href="https://www.gnu.org/licenses/agpl-3.0.en.html">
    <img alt="License: AGPLv3" src="https://shields.io/badge/License-AGPL%20v3-blue.svg">
  </a>
  <a href="https://github.com/iv-org/invidious/actions">
    <img alt="Build Status" src="https://github.com/iv-org/invidious/workflows/Invidious%20CI/badge.svg">
  </a>
  <a href="https://github.com/iv-org/invidious/commits/master">
    <img alt="GitHub commits" src="https://img.shields.io/github/commit-activity/y/iv-org/invidious?color=red&label=commits">
  </a>
  <a href="https://github.com/iv-org/invidious/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/iv-org/invidious?color=important">
  </a>
  <a href="https://github.com/iv-org/invidious/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/iv-org/invidious?color=blueviolet">
  </a>
  <a href="https://hosted.weblate.org/engage/invidious/">
    <img alt="Translation Status" src="https://hosted.weblate.org/widgets/invidious/-/translations/svg-badge.svg">
  </a>

  <a href="https://github.com/humanetech-community/awesome-humane-tech">
    <img alt="Awesome Humane Tech" src="https://raw.githubusercontent.com/humanetech-community/awesome-humane-tech/main/humane-tech-badge.svg?sanitize=true">
  </a>

  <h3>An open source alternative front-end to YouTube</h3>

  <a href="https://invidious.io/">Website</a>
  &nbsp;•&nbsp;
  <a href="https://instances.invidious.io/">Instances list</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/faq/">FAQ</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/">Documentation</a>
  &nbsp;•&nbsp;
  <a href="#contribute">Contribute</a>
  &nbsp;•&nbsp;
  <a href="https://invidious.io/donate/">Donate</a>

  <h5>Chat with us:</h5>
  <a href="https://matrix.to/#/#invidious:matrix.org">
    <img alt="Matrix" src="https://img.shields.io/matrix/invidious:matrix.org?label=Matrix&color=darkgreen">
  </a>
  <a href="https://web.libera.chat/?channel=#invidious">
    <img alt="Libera.chat (IRC)" src="https://img.shields.io/badge/IRC%20%28Libera.chat%29-%23invidious-darkgreen">
  </a>
  <br>
  <a rel="me" href="https://social.tchncs.de/@invidious">
  <img alt="Fediverse: @invidious@social.tchncs.de" src="https://img.shields.io/badge/Fediverse-%40invidious%40social.tchncs.de-darkgreen">
  </a>
  <br>
  <a href="https://invidious.io/contact/">
  <img alt="E-mail" src="https://img.shields.io/badge/E%2d%2dmail-darkgreen">
  </a>
</div>


## Screenshots

| Player                              | Preferences                         | Subscriptions                         |
|-------------------------------------|-------------------------------------|---------------------------------------|
| ![](screenshots/01_player.png)      | ![](screenshots/02_preferences.png) | ![](screenshots/03_subscriptions.png) |
| ![](screenshots/04_description.png) | ![](screenshots/05_preferences.png) | ![](screenshots/06_subscriptions.png) |


## Features

**User features**
- Lightweight
- No ads
- No tracking
- No JavaScript required
- Light/Dark themes
- Customizable homepage
- Subscriptions independent from Google
- Notifications for all subscribed channels
- Audio-only mode (with background play on mobile)
- Support for Reddit comments
- [Available in many languages](locales/), thanks to [our translators](#contribute)

**Data import/export**
- Import subscriptions from YouTube, NewPipe and Freetube
- Import watch history from NewPipe
- Export subscriptions to NewPipe and Freetube
- Import/Export Invidious user data

**Technical features**
- Embedded video support
- [Developer API](https://docs.invidious.io/api/)
- Does not use official YouTube APIs
- No Contributor License Agreement (CLA)


## Quick start

**Using invidious:**

- [Select a public instance from the list](https://instances.invidious.io) and start watching videos right now!

**Hosting invidious:**

- [Follow the installation instructions](https://docs.invidious.io/installation/)


## Documentation

The full documentation can be accessed online at https://docs.invidious.io/

The documentation's source code is available in this repository:
https://github.com/iv-org/documentation

### Extensions

We highly recommend the use of [Privacy Redirect](https://github.com/SimonBrazell/privacy-redirect#get),
a browser extension that automatically redirects Youtube URLs to any Invidious instance and replaces
embedded youtube videos on other websites with invidious.

The documentation contains a list of browser extensions that we recommended to use along with Invidious.

You can read more here: https://docs.invidious.io/applications/


## Contribute

### Code

1.  Fork it ( https://github.com/iv-org/invidious/fork ).
1.  Create your feature branch (`git checkout -b my-new-feature`).
1.  Stage your files (`git add .`).
1.  Commit your changes (`git commit -am 'Add some feature'`).
1.  Push to the branch (`git push origin my-new-feature`).
1.  Create a new pull request ( https://github.com/iv-org/invidious/compare ).

### Translations

We use [Weblate](https://weblate.org) to manage Invidious translations.

You can suggest new translations and/or correction here: https://hosted.weblate.org/engage/invidious/.

Creating an account is not required, but recommended, especially if you want to contribute regularly.
Weblate also allows you to log-in with major SSO providers like Github, Gitlab, BitBucket, Google, ...


## Projects using Invidious

- [FreeTube](https://github.com/FreeTubeApp/FreeTube): A libre software YouTube app for privacy.
- [CloudTube](https://sr.ht/~cadence/tube/): A JavaScript-rich alternate YouTube player.
- [PeerTubeify](https://gitlab.com/Cha_de_L/peertubeify): On YouTube, displays a link to the same video on PeerTube, if it exists.
- [MusicPiped](https://github.com/deep-gaurav/MusicPiped): A material design music player that streams music from YouTube.
- [HoloPlay](https://github.com/stephane-r/HoloPlay): Funny Android application connecting on Invidious API's with search, playlists and favorites.
- [WatchTube](https://github.com/WatchTubeTeam/WatchTube): Powerful YouTube client for Apple Watch.
- [Yattee](https://github.com/yattee/yattee): Alternative YouTube frontend for iPhone, iPad, Mac and Apple TV.
- [TubiTui](https://codeberg.org/777/TubiTui): A lightweight, libre, TUI-based YouTube client.
- [Ytfzf](https://github.com/pystardust/ytfzf): A posix script to find and watch youtube videos from the terminal. (Without API)


## Liability

We take no responsibility for the use of our tool, or external instances
provided by third parties. We strongly recommend you abide by the valid
official regulations in your country. Furthermore, we refuse liability
for any inappropriate use of Invidious, such as illegal downloading.
This tool is provided to you in the spirit of free, open software.

You may view the LICENSE in which this software is provided to you [here](./LICENSE).

>   16. Limitation of Liability.
>
> IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
SUCH DAMAGES.
<img align="left" width="70px" src="https://raw.githubusercontent.com/titaniumnetwork-dev/Holy-Unblocker/master/views/assets/img/icon.png"></img>
# Holy Unblocker

Holy Unblocker, an official flagship Titanium Network site, can bypass web filters regardless of whether it is an extension or network-based. Being a secure web proxy service, it supports numerous sites while being updated frequently and concentrating on detail with design, mechanics, and features.

Works with a large number of sites, including YouTube, Discord, and more!
Also has a good amount of locally hosted games featured on the site.

### You can support Holy Unblocker by starring the repository!

Read below for information if the official site is blocked or for obtaining more links.

Can't deploy using any of the free options below? Check out Railway or look into cheap, paid VPS hosting solutions.

#### Why are updates no longer happening here for this repository?
Please read over <a href="#important-message-original">here</a>.

New Repository: https://github.com/holy-unblocker/website-aio

#### Where can I find the games for this repo? (404 errors, etc.)
Due to piracy concerns, size, etc. this has been moved over <a href="https://github.com/QuiteAFancyEmerald/HU-Archive">here</a>.

#### Supports
- Youtube.com
- Discord.com
- Google.com
- Reddit.com
- Bing.com
- And more sites!

#### Features:
- Tab customization using the Options menu for improved stealth 
- Considerable variety with the open selection of proxy types 
- Game library with moderately decent titles
- Has frequent support articles for issues relating to the various proxy instances

Note: EmuLibrary is not featured in the public version.

Official Site: <a href="https://holyubofficial.net">https://holyubofficial.net</a>

**Be sure to join Titanium Network's Discord for more official site links:** <a href="https://discord.gg/unblock">https://discord.gg/unblock</a>

Simply do `%proxy hu` in `#proxy-commands` for more Holy Unblocker links on the TN Discord server.

<img src="https://raw.githubusercontent.com/titaniumnetwork-dev/Holy-Unblocker/master/views/assets/img/preview/hu-v5.0.0-preview.png"></img>

### Deploy Holy Unblocker

[![Deploy to Heroku](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/heroku.svg)](https://heroku.com/deploy/?template=https://github.com/titaniumnetwork-dev/Holy-Unblocker)
[![Run on Replit](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/replit.svg)](https://replit.com/github/titaniumnetwork-dev/Holy-Unblocker)
[![Remix on Glitch](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/glitch.svg)](https://glitch.com/edit/#!/import/github/titaniumnetwork-dev/Holy-Unblocker)
[![Deploy to Azure](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/azure.svg)](https://deploy.azure.com/?repository=https://github.com/titaniumnetwork-dev/Holy-Unblocker)
[![Deploy to IBM Cloud](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/ibmcloud.svg)](https://cloud.ibm.com/devops/setup/deploy?repository=https://github.com/titaniumnetwork-dev/Holy-Unblocker)
[![Deploy to Amplify Console](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/amplifyconsole.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/titaniumnetwork-dev/Holy-Unblocker)
[![Run on Google Cloud](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/googlecloud.svg)](https://deploy.cloud.run/?git_repo=https://github.com/titaniumnetwork-dev/Holy-Unblocker)

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Ftitaniumnetwork-dev%2FHoly-Unblocker)

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/QuiteAFancyEmerald/Holy-Unblocker-Old&branch=master&name=HolyUnblocker&run_command=npm%start)

#### Is Holy Unblocker still being worked on?
Yes! A lot of users may have noticed the initial message about Holy Unblocker being down however Holy Unblocker is now being maintained by a seperate team and no longer by me. You may check it out <a href="https://git.holy.how/">here</a> once setup or join the TN Discord linked below for more information. 

#### Where can I find the new source material for Holy Unblocker?
Check it out <a href="https://github.com/holy-unblocker/website-aio">here</a> if you wish to have an easier to deploy instance with the new changes :D

#### Important Message (Original)
This isn’t the greatest announcement sorry. After lots of thought and severe hesitation I’m shutting down Holy Unblocker and leaving TN. It's just been something that I’ve been super conflicted with for months hence the lack of updates and the massive gaps that happened last year. I just didn’t want to throw away a project that I passionately enjoyed and spent time on while making amazing friends and meeting epic devs here. I could go on forever for who these people are but ima like leave it here. They know who they are :D

The main change of thought is that I’m finally just putting an end right now due to 1) the lack of motivation 2) the community is NOT the greatest at time and not the nicest at times (have to put that out here) 3) the future doesn’t look so good for HU/TN as a project.

Some things I’ll be keeping secret since there are more reasons to this choice unless otherwise for those who don’t find this enough information. Good friends here will know that I’ve been super stressed about this choice for months now. Also regardless a good motivator for this choice is the fact that I’ll be graduating soon.

It’s possible that I may continue/come back for this in the future or keep it on GitHub only. I leave this here because even now I am still doubting myself about this change. But for now I’d check out other proxy sites like Incognito (Duce DOES a ton of updates frequently and he is the creator/developer of Ultraviolet so give him some love) :yayy_hopi: 

Check out his Patreon also! For current HU patrons you will not be billed next month and the HU Patreon will be archived so head over to Duce’s patron so he can purchase more domains for Incognito.

With love <3
Emerald :HuTaoHype:

## Table of contents:

- [Setup](#how-to-setup)
    - [Structure](#structure)
        - [Structure Information](#structure-information)
        - [Static Files](#details-of-views)
        - [Scripts](#scripts-located-in-viewsassetsjs)
    - [Future Additions](#future-additions)
    - [Beginner's Explanation](#vauge-explanation-for-beginners-with-external-proxies-and-hosting)
      - [Hosting Providers](#list-of-some-good-hosting-options)
      - [Heroku Setup](#heroku-steps)
      - [Domain Setup](#freenomdomain-steps)
      - [Cloudflare Setup](#cloudflare-steps)
      - [Workspace Configurations](#workspace-configurations)
    - [Detailed FAQ](#detailed-faq)
    - [More Information](#more-information)

## How to Setup

Either use the button above to deploy to Heroku or do the below:

```
git clone https://github.com/titaniumnetwork-dev/Holy-Unblocker.git

cd Holy-Unblocker

npm install

npm start
```

The default place for the proxy when its started is `http://localhost:8080` but you can change it if needed in config.json

This website is hosted locally with Corrosion built-in. More more information go to the Corrosion repository below.


## Structure
- `index.html`: The homepage of the site.
- `404.html`: The 404 page.
- `error.html`: Other errors that are not 404.
- `info.html`: Documentation (This page!)
- `faq.html`: Frequently asked questions page.
- `hidden.html`: Fake "Site not Found" page (unused)
- `frame.html`: Handles any pages under stealth.
- `surf.html`: Web Proxies page, page offers to be redirected to any proxies you would like to add. In this case, Corrosion, Womginx, and Palladium.
- `credits.html`: List of all contributors to the site.
- `bookmarklets.html`: Bookmarklets page, to be worked on more in the future.
- `icons.html`: Information regarding Settings Menu page. Added this in for standard users.
- `terms.html`: Terms of Services, AUP and Privacy Policy page.
- `gtools.html`: Games page, help from @BinBashBanana and @kinglalu.
- `games5.html`: HTML5 game navigation page.
- `emulators.html`: Emulator navigation page, using <a href="https://github.com/BinBashBanana/webretro">webretro</a>.
- `emulibrary.html`: Games page for emulated games (not included in public release)
- `flash.html`: Games page for flash games, credits given to @BinBashBanana and Titanium Network for its assets.
- `corrosion.html`: Corrosion Proxy page which features Corrosion hosted locally but can be configured to redirect to an external instance.
- `womginx.html`: Womginx Proxy page. Script links to a subdomain for Womginx, a highly fast proxy with reCaptcha and discord support.
- `palladium.html`: Palladium Proxy page.
- `youtube.html`: An proxied version of Youtube running off of the locally hosted Corrosion.
- `discord.html`: Hub for the Discord proxy.
- `reddit.html`: Hub for the Reddit proxy.

### Structure Information
- `/views/`: The physical site base of Holy Unblocker goes here where static assets are served.
- `/src/`: For future implementation of obfuscation and keyword removing features.

#### Details of `/views/`
- `/archive/` is used for game pages and vibeOS.
- `/pages/` is used for the HTML for the site.
- `/assets/` is used for various assets for CSS, JS, and images.

#### Scripts located in `/views/assets/js/`
- `common.js` is used on all of the pages for common useful functions.
- `prset.js` is used on the proxy pages for proxy form functionality.
- `header.js` inserts the header into every page using javascript.
- `csel.js` manages the settings menu on the header.
- `footer.js` inserts the footer into every page using javascript.
- `gnav/*.js` are used for navigation on the games pages.

## Future Additions
- Expansive game library
- Various parity changes.

## Vauge Explanation for Beginners With External Proxies and Hosting
You will first want to host your proxies locally or externally. 

#### List of some good hosting options:
- <a href="https://dedipath.com">Dedipath</a> (Paid and Dedicated)
- <a href="#">Oracle Cloud</a> (Free, Paid, Dedicated)
- <a href="https://heroku.com">Heroku</a> (Paid)
- <a href="https://glitch.com">Glitch</a> (Free)
- <a href="https://repl.it">Repl.it</a> (Free)
- <a href="https://azure.microsoft.com">Azure</a> (Free and Paid)

Out of the list of hosting providers Dedipath and Azure rank first as a preference. You may also self-host.

After you have selected a decent VPS, use Cloudflare for the DNS records for both the site and the subdomains for the proxies.

This is an example of DNS records involving Heroku. Self-hosting will require `A records` preferably.
<img src="https://raw.githubusercontent.com/titaniumnetwork-dev/Holy-Unblocker/master/views/assets/img/dnssetup.png" width="500"></img>

- `@` and `www.example.ml` are being used for the local Ultraviolet proxy.
- `client.example.ml` is being used for Rammerhead.
- `a.example.ml` is being used for womginx.
- `cdn.example.ml` is being used for a private Ultraviolet host on the official sites.

As stated previously, Holy Unblocker is hosted locally with Ultraviolet.

#### Freenom/Domain Steps
For beginners, Freenom is a good provider for obtaining domains for free. However the catch is that you can only use properly "Freenom" domains for free being .cf, .ml, .gq, ga and .tk. However these can be blocked rather easily.

- Get some Freenom domains then add them to your Heroku instance (Personal > [App Name] > Settings > Domains)
Add a domain for both `www.example.cf` and `example.cf` with .cf being interchangeable with other Freenom domain names.
- If you prefer to obtain premium domains (TLDs) then use <a href="https://porkbun.com">Porkbun</a>, which offers domains for amazing prices. Literally a `.net` domain normally costs around $10. On Porkbun for the first year it costs $3 so its definitely a deal.

#### Cloudflare Steps
- Use Cloudflare (make an account), add your site (Freenom Domain or other) and then add your various DNS targets to Cloudflare. Make sure you add Cloudflare's Nameservers which will be given later when you are adding your site. 

Make sure they are CNAME although A records also work and try to follow this structure:

**Type | Name | Target**

`CNAME | @ | your-main-heroku-target-here.herokudns.com`  
`CNAME | www | your-main-heroku-target-here.herokudns.com`

**Below are if you want external proxies also with your site:**

`CNAME | p | your-palladium-instance-here.herokudns.com`  
`CNAME | a | your-womginx-instance-here.herokudns.com`  
`CNAME | pd | your-pydodgeb-instance-here.herokudns.com`

Make sure HTTPS is forced and have SSL set to Flexible for Heroku. Otherwise you can have SSL set to Full.

#### Workspace Configurations 
Preferably if you have your own device use Visual Studio Code. Pretty much the best option you can get but obviously this is an opinion. Also make sure you have <a href="https://nodejs.org/">Node.JS</a> installed on your machine.

Not going to go too in depth with this part but first fork this repository. The clone it locally through a Terminal of some sort depending on what OS you are on. Make sure you navigate to the folder you want to set this up in.

```
git clone https://github.com/titaniumnetwork-dev/Holy-Unblocker.git

cd Holy-Unblocker

npm install
```

Now simply add the folder you cloned this repo in in VSC. Then run `npm install`. I recommend that if you are releasing this publically on GitHub that you add a `.gitignore` in your root directory with the following exclusions:

```
node_modules
```

Now you have your following workspace environment setup. To deploy the following workspace you just created you will need to look up depending on your hosting provider.

For an online IDE that you can use on your school computer and/or chromebook use GitPod. Basically the equivalent of Visual Studio Code but with in-browser support.
- Make an account: `https://gitpod.io/`
- Fork this repo and enter in this URL to setup your workspace: `https://gitpod.io#https://github.com/YourNameHere/Holy-Unblocker/`

Use the same steps above by running `npm install` in your repository and adding a `.gitignore` in your root directory specifying to exclude `node_modules`.

## Detailed FAQ
A detailed FAQ with common issues and solutions can be found <a href="https://holyubofficial.net/?faq">here</a> or on any official HU site on the FAQ page.

<details>
<summary>Quick FAQ</summary>

**Why is the site I am on not working correctly or having CAPTCHA errors?**

Captcha support is currently not available on all of the current proxies sadly. Therefore some sites may not work with any of the sites. Read below for issues with links on sites.

**I am getting 502 errors. What do I do?**

When this happens you may either switch sites to fix the error or wait a bit. Sometimes clearing your cache can help.

If you still have any questions feel free to ask them in the discord linked here.

</details>

## More Information
This project is maintained by Quite A Fancy Emerald with massive help from BinBashBanana (OlyB) and is an official flagship Titanium Network proxy site.

- <a href="https://github.com/titaniumnetwork-dev/">https://github.com/titaniumnetwork-dev/</a>
- <a href="https://titaniumnetwork.org/">https://titaniumnetwork.org/</a>

View the official website for more detail and credits.

### Proxy Sources:
This project currently uses Ultraviolet, Womginx, and Rammerhead, linked below.

- <a href="https://github.com/titaniumnetwork-dev/Ultraviolet">Ultraviolet</a>
- <a href="https://github.com/binary-person/womginx">Womginx</a>
- <a href="https://github.com/binary-person/rammerhead">Rammerhead</a>

### Other:

- <a href="https://github.com/vibedivide/vibeOS">vibeOS</a>
- <a href="https://github.com/BinBashBanana/webretro">webretro</a>
- <a href="https://ruffle.rs/">Ruffle</a>
- <a href="https://github.com/BlaNKtext/webosu">webosu</a>

### Notable Mentions:

- <a href="https://soyoustart.com/">SoYouStart / OVH</a> (Hosting Provider)

Thanks :D
