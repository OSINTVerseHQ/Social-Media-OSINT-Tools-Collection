# Social Media OSINT Tools Collection

A curated collection of the most useful tools for social media OSINT, grouped by platform.

Maintained by the [OSINTverse](https://osintverse.com) team. Pull requests are welcome.

> **Tip for command-line tools:** entries marked with an `ot install …` line are open-source tools you can install and run by name with [otinstaller](https://github.com/OSINTVerseHQ/OTinstaller), a free MIT-licensed tool manager that puts each tool in its own virtualenv. See [Installing the command-line tools](#installing-the-command-line-tools).

## Contents

1. [What is OSINT](#what-is-osint)
2. [What is Social Media OSINT](#what-is-social-media-osint)
3. [Installing the command-line tools](#installing-the-command-line-tools)
4. [Username and cross-platform search](#username-and-cross-platform-search)
5. [Facebook](#facebook)
6. [Instagram](#instagram)
7. [LinkedIn](#linkedin)
8. [X (Twitter)](#x-twitter)
9. [Pinterest](#pinterest)
10. [Reddit](#reddit)
11. [GitHub](#github)
12. [Snapchat](#snapchat)
13. [WhatsApp](#whatsapp)
14. [Skype](#skype)
15. [Telegram](#telegram)
16. [Discord](#discord)
17. [YouTube](#youtube)
18. [OnlyFans](#onlyfans)
19. [TikTok](#tiktok)
20. [Other](#other)
21. [Further reading and resources](#further-reading-and-resources)
22. [FAQ](#faq)
23. [Contributions](#contributions)

## What is OSINT

Open source intelligence (OSINT) is the practice of collecting information from published or otherwise publicly available sources. OSINT operations, whether practiced by IT security pros, malicious hackers, or state-sanctioned intelligence operatives, use advanced techniques to search through the vast haystack of visible data to find the needles they're looking for to achieve their goals—and learn information that many don't realize is public.

## What is Social Media OSINT

Social media OSINT, also known as social media intelligence (SOCMINT), is intelligence gathered from social media sites like Facebook, X (Twitter), Instagram and others. It is one element of open-source intelligence.

## Installing the command-line tools

Many of the GitHub tools in this list are Python projects, and each one installs a little differently. Rather than cloning and setting up each repo by hand, you can use [otinstaller](https://github.com/OSINTVerseHQ/OTinstaller) (Linux, Python 3.10–3.12) to install, run, update and remove them by name:

```bash
pipx install otinstaller
ot init
ot install sherlock maigret instaloader
ot run --all u:johndoe
```

`u:`, `e:`, `p:` and `d:` mark a username, email, phone number or domain, and otinstaller passes them to each tool in its own syntax. Results are saved under `./results/<tool>/<target>/`. The full list of supported tools is in the [otinstaller docs](https://osintverse.gitbook.io/otinstaller).

You can of course still install any of these tools straight from their own repositories.

## Username and cross-platform search

Most social media investigations start from a username, email or phone number. These tools check many platforms at once.

1. **Sherlock**
   - Link: [Sherlock](https://github.com/sherlock-project/sherlock)
   - Description: Hunt down social media accounts by username across hundreds of social networks.
   - Install: `ot install sherlock`

2. **Maigret**
   - Link: [Maigret](https://github.com/soxoj/maigret)
   - Description: Collect a dossier on a person by username from thousands of sites, and parse profile pages for extra details.
   - Install: `ot install maigret`

3. **Blackbird**
   - Link: [Blackbird](https://github.com/p1ngul1n0/blackbird)
   - Description: Search for accounts by username and email across social networks.
   - Install: `ot install blackbird`

4. **socialscan**
   - Link: [socialscan](https://github.com/iojw/socialscan)
   - Description: Accurately check whether a username or email is in use on major online platforms.
   - Install: `ot install socialscan`

5. **Holehe**
   - Link: [Holehe](https://github.com/megadose/holehe)
   - Description: Check whether an email is registered on sites like X, Instagram and many more, using their password-reset flows.
   - Install: `ot install holehe`

6. **Linkook**
   - Link: [Linkook](https://github.com/JackJuly/linkook)
   - Description: Discover linked social accounts and associated emails across platforms from a single username.
   - Install: `ot install linkook`

7. **NExfil**
   - Link: [NExfil](https://github.com/thewhiteh4t/nexfil)
   - Description: Find profiles by username across a large list of sites.
   - Install: `ot install nexfil`

8. **user-scanner**
   - Link: [user-scanner](https://github.com/kaifcodec/user-scanner)
   - Description: Email and username OSINT suite that pulls data from a single email or username.
   - Install: `ot install user-scanner`

9. **SearchIn**
   - Link: [SearchIn](https://osintverse.com/searchin)
   - Description: Web-based search across breach, people, social and domain data providers from one email, username or phone number, with results kept in a case. Paid per lookup; useful when you need provider data that free tools don't reach.

## Facebook

1. **Facebook Recover Lookup**
   - Link: [Facebook Recover Lookup](https://www.facebook.com/login/identify?ctx=recover)
   - Description: Check whether a given email or phone number is associated with a Facebook account.

2. **CrowdTangle Link Checker** *(discontinued by Meta in August 2024; kept for reference)*
   - Link: [CrowdTangle Link Checker](https://apps.crowdtangle.com/chrome-extension)
   - Description: Showed the Facebook posts, Instagram posts, tweets and subreddits that mention a link.

3. **Social Searcher**
   - Link: [Social Searcher](https://www.social-searcher.com/)
   - Description: Monitor public social mentions across social networks and the web.

4. **Lookup-id.com**
   - Link: [Lookup-id.com](https://lookup-id.com/)
   - Description: Find the Facebook ID of a profile or group.

5. **Who Posted What**
   - Link: [Who Posted What](https://whopostedwhat.com/)
   - Description: Facebook keyword search for people who work in the public interest. Lets you search keywords on specific dates.

6. **SOWsearch**
   - Link: [SOWsearch](https://www.sowsearch.info/)
   - Description: A simple interface for searching Facebook posts, people and photos with filters.

7. **Facebook Graph Searcher**
   - Link: [Facebook Graph Searcher](https://intelx.io/tools?tab=facebook)
   - Description: Search for people on Facebook.

8. **Facebook People Search**
   - Link: [Facebook People Search](https://www.facebook.com/directory/people/)
   - Description: Search Facebook's people directory by name.

9. **DumpItBlue+**
   - Link: [DumpItBlue+](https://chrome.google.com/webstore/detail/dumpitblue%2B/igmgknoioooacbcpcfgjigbaajpelbfe/)
   - Description: Dump Facebook content for analysis or reporting.

10. **Export Comments**
    - Link: [Export Comments](https://exportcomments.com/)
    - Description: Export comments from social media posts to an Excel file.

11. **Facebook Applications**
    - Link: [Facebook Applications](https://khalil-shreateh.com/khalil.shtml/social_applications/facebook-applications/)
    - Description: A collection of online tools that automate Facebook lookups.

12. **Social Analyzer**
    - Link: [SocialAnalyzer - Social Sentiment & Analysis](https://chromewebstore.google.com/detail/socialanalyzer-social-sen/efeikkcpimdfpdlmlbjdecnmkknjcfcp)
    - Description: A free social media monitoring and analysis extension.

13. **AnalyzeID**
    - Link: [AnalyzeID](https://analyzeid.com/)
    - Description: Find sites that may share an owner, including by Facebook App ID match.

14. **Facebook Matrix**
    - Link: [Facebook Matrix](https://plessas.net/facebookmatrix)
    - Description: Formulas for searching Facebook.

15. **StalkFace**
    - Link: [StalkFace](https://stalkface.com/en/)
    - Description: Toolkit for looking up public Facebook profile content.

16. **Search is Back**
    - Link: [Search is Back](https://searchisback.com/)
    - Description: Find people and events on Facebook by location, relationships and more.

## Instagram

1. **SnapInsta**
   - Link: [SnapInsta](https://snapinsta.app)
   - Description: Download photos, videos, IGTV and more from a public Instagram account.

2. **IFTTT Integrations**
   - Link: [IFTTT Instagram integrations](https://ifttt.com/instagram)
   - Description: Popular Instagram workflows and automations.

3. **Picuki**
   - Link: [Picuki](https://www.picuki.com/)
   - Description: Browse publicly available Instagram content without logging in.

4. **Imginn**
   - Link: [Imginn](https://imginn.io/)
   - Description: View and download Instagram content in one place.

5. **Instaloader**
   - Link: [Instaloader](https://github.com/instaloader/instaloader)
   - Description: Download pictures or videos along with their captions and other metadata from Instagram.
   - Install: `ot install instaloader`

6. **SoIG**
   - Link: [SoIG](https://github.com/yezz123/SoIG)
   - Description: Collects a range of information from an Instagram account that you can't see from the profile alone.

7. **Osintgram**
   - Link: [Osintgram](https://github.com/Datalux/Osintgram)
   - Description: Interactive shell to collect, analyze and run reconnaissance on Instagram accounts.

8. **Toutatis**
   - Link: [Toutatis](https://github.com/megadose/toutatis)
   - Description: Extract information such as emails, phone numbers and IDs from Instagram accounts.
   - Install: `ot install toutatis`

9. **instalooter**
   - Link: [instalooter](https://pypi.org/project/instalooter/)
   - Description: Download any picture or video from an Instagram profile without API access.

10. **instagram_monitor**
    - Link: [instagram_monitor](https://github.com/misiektoja/instagram_monitor)
    - Description: Track an Instagram account's activity and profile changes over time, with notifications.
    - Install: `ot install instagram-monitor`

11. **Instagram Location Search**
    - Link: [Instagram Location Search](https://github.com/bellingcat/instagram-location-search)
    - Description: Bellingcat tool that finds Instagram location IDs near given coordinates.
    - Install: `ot install instagram-location-search`

12. **Exportgram**
    - Link: [Exportgram](https://exportgram.net/)
    - Description: Export Instagram comments to Excel, CSV and JSON.

13. **Profile Analyzer**
    - Link: [Profile Analyzer](https://inflact.com/tools/profile-analyzer/)
    - Description: Free statistics for any public Instagram profile.

14. **Find Instagram User ID**
    - Link: [Find Instagram User ID](https://www.codeofaninja.com/tools/find-instagram-user-id/)
    - Description: Get an Instagram account's numeric ID from its username.

15. **Instahunt**
    - Link: [Instahunt](https://instahunt.huntintel.io/)
    - Description: Find Instagram posts around a location.

16. **InstaFreeView**
    - Link: [InstaFreeView](https://instafreeview.com/)
    - Description: View Instagram profile posts without logging in.

17. **InstaNavigation**
    - Link: [InstaNavigation](https://instanavigation.com/)
    - Description: Anonymous Instagram story viewing.

## LinkedIn

1. **RecruitEm**
   - Link: [RecruitEm](https://recruitin.net/)
   - Description: Builds Google boolean strings that search public LinkedIn and other social profiles.

2. **RocketReach**
   - Link: [RocketReach](https://rocketreach.co/person)
   - Description: Look up contact information for professionals and companies.

3. **PhantomBuster**
   - Link: [PhantomBuster](https://phantombuster.com/phantombuster)
   - Description: Automation suite that includes data extraction from LinkedIn and other platforms.

4. **LinkedProspect Boolean Search**
   - Link: [LinkedIn Boolean Search](https://linkedprospect.com/linkedin-boolean-search-tool/#tool)
   - Description: Build a targeted list of LinkedIn people using boolean search.

5. **ReverseContact**
   - Link: [ReverseContact](https://www.reversecontact.com/)
   - Description: Find LinkedIn profiles associated with an email.

6. **LinkedIn Search Engine**
   - Link: [Programmable Search Engine](https://cse.google.com/cse?cx=daaf18e804f81bed0)
   - Description: Google Programmable Search Engine restricted to LinkedIn profiles.

7. **Free People Search Tool**
   - Link: [Free People Search Tool](https://freepeoplesearchtool.com/#gsc.tab=0)
   - Description: Find people on LinkedIn and other sites through search engines.

8. **IntelligenceX LinkedIn**
   - Link: [IntelligenceX LinkedIn](https://intelx.io/tools?tab=linkedin)
   - Description: Web-based tool for searching LinkedIn.

9. **IntelTechniques LinkedIn Tool**
   - Link: [IntelTechniques LinkedIn Tool](https://inteltechniques.com/tools/Linkedin.html)
   - Description: An interface that groups several LinkedIn search techniques.

10. **LinkedInt**
    - Link: [LinkedInt](https://github.com/vysecurity/LinkedInt)
    - Description: LinkedIn intelligence and employee enumeration.

11. **InSpy**
    - Link: [InSpy](https://github.com/jobroche/InSpy)
    - Description: Python-based LinkedIn enumeration tool.

12. **CrossLinked**
    - Link: [CrossLinked](https://github.com/m8sec/CrossLinked)
    - Description: Collects valid employee names from an organization through search engine scraping.
    - Install: `ot install crosslinked`

## X (Twitter)

1. **X Pro (formerly TweetDeck)**
   - Link: [X Pro](https://pro.x.com/)
   - Description: View multiple timelines and searches side by side. Now requires an X Premium subscription.

2. **Followerwonk**
   - Link: [Followerwonk](https://followerwonk.com/bio)
   - Description: Search X accounts by bio, and compare followers.

3. **X Advanced Search**
   - Link: [X Advanced Search](https://x.com/search-advanced)
   - Description: Search X with filters for accounts, dates, engagement and more.

4. **Wayback Tweets**
   - Link: [Wayback Tweets](https://waybacktweets.streamlit.app/)
   - Description: Display many archived tweets from the Wayback Machine without opening each link.

5. **memory.lol**
   - Link: [memory.lol](https://memory.lol/app/)
   - Description: Historical usernames for X accounts.

6. **SocialData API**
   - Link: [SocialData API](https://socialdata.tools/)
   - Description: Unofficial X API alternative for historical tweets, profiles, lists and Spaces.

7. **Social Bearing**
   - Link: [Social Bearing](https://socialbearing.com/)
   - Description: Insights and analytics for tweets and timelines.

8. **Tinfoleak**
   - Link: [Tinfoleak](https://tinfoleak.com/)
   - Description: Search for information leaks from X users.

9. **OSoMe Network Tool**
   - Link: [Network Tool](https://osome.iu.edu/tools/networks/)
   - Description: Explore how information spreads across X with an interactive network.

10. **Foller**
    - Link: [Foller](https://foller.me/)
    - Description: Analytics and topics for any public X profile.

11. **SimpleScraper OSINT**
    - Link: [SimpleScraper OSINT](https://airtable.com/appyDhNeSetZU0rIw/shrceHfvukijgln9q/tblxgilU0SzfXNEwS/viwde4ACDDOpeJ8aO?blocks=bipxY3tKD5Lx0wmEU)
    - Description: An Airtable that scrapes OSINT-related X accounts and saves tweets that contain coordinates.

12. **Deleted Tweet Finder**
    - Link: [Deleted Tweet Finder](https://cache.digitaldigging.org/)
    - Description: Search for deleted tweets across multiple archival services.

13. **Aware Online Twitter Search Tool**
    - Link: [Twitter search tool](https://www.aware-online.com/en/osint-tools/twitter-search-tool/)
    - Description: Build advanced search queries for X.

14. **Twitter Video Downloader**
    - Link: [Twitter Video Downloader](https://twittervideodownloader.com/)
    - Description: Download videos and GIFs from tweets.

15. **Download Twitter Data**
    - Link: [Download Twitter Data](https://www.twtdata.com/)
    - Description: Download X data as CSV by handle, keyword, hashtag, list ID or Space ID.

16. **Twitonomy**
    - Link: [Twitonomy](https://www.twitonomy.com/)
    - Description: Detailed analytics for X accounts.

17. **TweeterID**
    - Link: [TweeterID](https://tweeterid.com/)
    - Description: Convert an X handle to its numeric ID and back.

18. **BirdHunt**
    - Link: [BirdHunt](https://birdhunt.huntintel.io/)
    - Description: Find posts around a location.
      
19. **Twitee**
    - Link: [Twitee](https://twitee.co/)
    - Description: A free, browser-based Twitter/X viewer for researching public profiles, posts, available replies, search results, and media without an X account.

## Pinterest

1. **DownAlbum**
   - Link: [DownAlbum](https://chrome.google.com/webstore/detail/downalbum/cgjnhhjpfcdhbhlcmmjppicjmgfkppok)
   - Description: Chrome extension for downloading photo albums from sites including Pinterest.

2. **Experts PHP: Pinterest Photo Downloader**
   - Link: [Pinterest Photo Downloader](https://www.expertsphp.com/pinterest-photo-downloader.html)
   - Description: Download photos from Pinterest.

3. **Pingroupie**
   - Link: [Pingroupie](http://pingroupie.com)
   - Description: Meta search engine for Pinterest group boards, influencers, pins and keywords.

4. **Tailwind**
   - Link: [Tailwind](https://www.tailwindapp.com)
   - Description: Social media scheduling and management tool that supports Pinterest.

5. **Pinterest Guest**
   - Link: [Pinterest Guest](https://addons.mozilla.org/en-US/firefox/addon/pinterest-guest)
   - Description: Firefox add-on for browsing Pinterest without logging in.

6. **SourcingLab: Pinterest**
   - Link: [SourcingLab: Pinterest](https://sourcinglab.io/search/pinterest)
   - Description: Search for pins, boards and users.

## Reddit

> Many Reddit search tools relied on the Pushshift archive, which has been restricted since 2023. Some of the tools below may return partial results.

1. **F5Bot**
   - Link: [F5Bot](https://f5bot.com)
   - Description: Email notifications for new Reddit posts matching your keywords.

2. **Karma Decay**
   - Link: [Karma Decay](http://karmadecay.com)
   - Description: Reverse image search for reposted images on Reddit.

3. **Mostly Harmless**
   - Link: [Mostly Harmless](http://kerrick.github.io/Mostly-Harmless/#features)
   - Description: Browser extension that shows Reddit discussions about the page you're on.

4. **OSINT Combine: Reddit Post Analyser**
   - Link: [Reddit Post Analyser](https://www.osintcombine.com/reddit-post-analyser)
   - Description: Analyze and gather information from Reddit posts.

5. **PhantomBuster**
   - Link: [PhantomBuster](https://phantombuster.com/phantombuster?category=reddit)
   - Description: Automation suite with Reddit data extraction.

6. **rdddeck**
   - Link: [rdddeck](https://rdddeck.com)
   - Description: Real-time dashboard for monitoring multiple subreddits.

7. **Readr for Reddit**
   - Link: [Readr for Reddit](https://chrome.google.com/webstore/detail/readr-forreddit/molhdaofohigaepljchpmfablknhabmo)
   - Description: Chrome extension for an improved Reddit reading experience.

8. **Reddit Archive**
   - Link: [Reddit Archive](http://www.redditarchive.com)
   - Description: Archive of Reddit front pages for historical reference.

9. **Reddit Comment Search**
   - Link: [Reddit Comment Search](https://redditcommentsearch.com)
   - Description: Search a user's Reddit comments.

10. **Redditery**
    - Link: [Redditery](http://www.redditery.com)
    - Description: Explore Reddit posts and comments by various criteria.

11. **Hacks (EdOverflow)**
    - Link: [Hacks](https://github.com/EdOverflow/hacks)
    - Description: Collection of web tricks and tools, including Reddit techniques.

12. **Reddit List**
    - Link: [Reddit List](http://redditlist.com)
    - Description: Directory of popular subreddits by category.

13. **RedditP**
    - Link: [RedditP](https://www.redditp.com)
    - Description: View a subreddit's images as a full-screen slideshow.

14. **Reddit Search**
    - Link: [Reddit Search (realsrikar)](https://realsrikar.github.io/reddit-search)
    - Link: [Reddit Search (cemulate)](http://cemulate.github.io/reddit-search)
    - Link: [Reddit Search (redditsearch.io)](https://www.redditsearch.io)
    - Link: [Reddit Search (reddit-search)](http://reddit-search.surge.sh)
    - Link: [Reddit Search (react-reddit-search-app)](https://react-reddit-search-app.web.app)
    - Link: [Finddit](https://viralharia.github.io/finddit)
    - Description: Various tools for searching posts and comments on Reddit.

15. **Reddit Shell**
    - Link: [Reddit Shell](https://redditshell.com)
    - Description: Command-line style interface for browsing Reddit.

16. **Reddit Stream**
    - Link: [Reddit Stream](http://reddit-stream.com)
    - Description: Live stream of comments in a Reddit thread.

17. **Reddit Enhancement Suite**
    - Link: [Reddit Enhancement Suite (Chrome)](https://chrome.google.com/webstore/detail/redditenhancementsuite/kbmfpngjjgdllneeigpgjifpgocmfgmb)
    - Link: [Reddit Enhancement Suite (Firefox)](https://addons.mozilla.org/en-GB/firefox/addon/reddit-enhancement-suite)
    - Description: Browser extension that adds features to Reddit browsing.

18. **Reddit User Analyser**
    - Link: [Reddit User Analyser](https://atomiks.github.io/reddit-user-analyser)
    - Description: Analyze and visualize the activity of a Reddit user.

19. **redditvids**
    - Link: [redditvids](https://redditvids.com)
    - Description: Watch Reddit videos and browse video subreddits.

20. **Redective**
    - Link: [Redective](http://redective.com)
    - Description: Investigate Reddit users based on their post history.

21. **Reditr**
    - Link: [Reditr](http://reditr.com)
    - Description: Desktop Reddit client.

22. **Reeddit**
    - Link: [Reeddit](https://reedditapp.com)
    - Description: Minimal Reddit web client.

23. **ReSavr**
    - Link: [ReSavr](https://www.resavr.com)
    - Description: Find deleted Reddit comments.

24. **SMAT**
    - Link: [SMAT](https://www.smat-app.com/timeline)
    - Description: Social media analysis toolkit for tracking terms over time, including on Reddit.

25. **socid_extractor**
    - Link: [socid_extractor](https://github.com/soxoj/socid_extractor)
    - Description: Turn a profile URL from Reddit and 150+ other sites into a structured record.
    - Install: `ot install socid-extractor`

26. **Suggest me a subreddit**
    - Link: [Suggest me a subreddit](https://nikas.praninskas.com/suggest-subreddit)
    - Description: Subreddit recommendations based on your interests.

27. **Subreddits**
    - Link: [Subreddits](http://subreddits.org)
    - Description: Directory of active subreddits by category.

28. **uforio**
    - Link: [uforio](http://uforio.com)
    - Description: Word clouds from Reddit comment threads.

29. **Universal Reddit Scraper (URS)**
    - Link: [Universal Reddit Scraper (URS)](https://github.com/JosephLai241/URS)
    - Description: Scrape Reddit posts, comments and users for analysis.

30. **Vizit**
    - Link: [Vizit](https://redditstuff.github.io/sna/vizit)
    - Description: Visualize relationships between subreddits.

31. **Wisdom of Reddit**
    - Link: [Wisdom of Reddit](https://wisdomofreddit.com)
    - Description: Search insightful Reddit comments.

## GitHub

1. **Awesome Lists**
   - Link: [Awesome Lists](http://awesomelists.top)
   - Description: Searchable index of "awesome" lists on GitHub.

2. **CoderStats**
   - Link: [CoderStats](https://coderstats.net)
   - Description: Coding activity statistics for a GitHub user.

3. **commit-stream**
   - Link: [commit-stream](https://github.com/x1sec/commit-stream)
   - Description: Monitor GitHub commits in real time, filtered by email domain or keyword.

4. **Digital Privacy**
   - Link: [Digital Privacy](https://github.com/ffffffff0x/Digital-Privacy)
   - Description: Collection of resources on digital privacy and security.

5. **Find GitHub User ID**
   - Link: [Find GitHub User ID](http://caius.github.io/github_id)
   - Description: Find the numeric ID of a GitHub user.

6. **GH Archive**
   - Link: [GH Archive](http://www.gharchive.org)
   - Description: Public dataset of GitHub activity events.

7. **Git-Awards**
   - Link: [Git-Awards](http://git-awards.com)
   - Description: Ranks GitHub users by stars per language and location.

8. **GitGot**
   - Link: [GitGot](https://github.com/BishopFox/GitGot)
   - Description: Semi-automated, feedback-driven tool for searching public GitHub data for secrets.

9. **gitGraber**
   - Link: [gitGraber](https://github.com/hisxo/gitGraber)
   - Description: Monitor GitHub for sensitive data in real time.

10. **git-hound**
    - Link: [git-hound](https://github.com/tillson/git-hound)
    - Description: Find sensitive information exposed in GitHub repositories.

11. **GitHub Dorks**
    - Link: [GitHub Dorks](https://github.com/techgaun/github-dorks)
    - Description: GitHub search queries for finding sensitive information.

12. **GitHub Stars**
    - Link: [GitHub Stars](http://githubstars.com)
    - Description: Showcases popular GitHub repositories.

13. **GitHub Trending RSS**
    - Link: [GitHub Trending RSS](https://mshibanami.github.io/GitHubTrendingRSS)
    - Description: RSS feeds for trending repositories.

14. **GitHub Username Search Engine**
    - Link: [GitHub Username Search Engine (jonnygovish)](https://jonnygovish.github.io/Github-username-search-engine)
    - Link: [GitHub Username Search Engine (githubnotes)](https://githubnotes-47071.firebaseapp.com/#/?_k=n0bgxn)
    - Description: Search for GitHub users with filters.

15. **GitHut**
    - Link: [GitHut](https://githut.info)
    - Description: Statistics and visualizations of programming languages on GitHub.

## Snapchat

1. **addmeContacts**
   - Link: [addmeContacts](http://add-me-contacts.com)
   - Description: Directory of usernames for Snapchat and other platforms.

2. **AddMeSnaps**
   - Link: [AddMeSnaps](https://www.addmesnaps.com)
   - Description: Directory for discovering Snapchat users.

3. **ChatToday**
   - Link: [ChatToday](https://chattoday.com)
   - Description: Directory of usernames for chat apps.

4. **Gebruikersnamen: Snapchat**
   - Link: [Gebruikersnamen: Snapchat](https://gebruikersnamen.nl/snapchat)
   - Description: Find Snapchat usernames.

5. **GhostCodes**
   - Link: [GhostCodes](https://www.ghostcodes.com)
   - Description: Discover Snapchat users and their stories.

6. **OSINT Combine: Snapchat Multi-Viewer**
   - Link: [Snapchat Multi-Viewer](https://www.osintcombine.com/snapchat-multi-viewer)
   - Description: View public Snap Map content from several locations at once.

7. **Snap Map**
   - Link: [Snap Map](https://map.snapchat.com)
   - Description: Public Snaps from around the world on a map.

8. **snapchat-map-scraper**
   - Link: [snapchat-map-scraper](https://github.com/nemec/snapchat-map-scraper)
   - Description: Scrape public Snapchat stories from the Snap Map.

9. **Snap Political Ads Library**
   - Link: [Snap Political Ads Library](https://www.snap.com/en-GB/political-ads)
   - Description: Snapchat's library of political ads.

10. **Social Finder**
    - Link: [Social Finder](https://socialfinder.app)
    - Description: Search for social media profiles across platforms.

11. **SnapIntel**
    - Link: [SnapIntel](https://github.com/Kr0wZ/SnapIntel)
    - Description: Python tool that gathers information about Snapchat users.

12. **AddMeS**
    - Link: [AddMeS](https://addmes.io/)
    - Description: "Add me" directory of Snapchat users.

## WhatsApp

1. **checkwa**
   - Link: [checkwa](https://checkwa.online)
   - Description: Check whether phone numbers are registered on WhatsApp.

2. **WhatsApp Fake Chat**
   - Link: [WhatsApp Fake Chat](http://www.fakewhats.com/generator)
   - Description: Generate fake WhatsApp conversations. Useful for training and for recognizing fabricated screenshots.

3. **WhatsappMonitor**
   - Link: [WhatsappMonitor](https://github.com/ErikTschierschke/WhatsappMonitor)
   - Description: Monitor and analyze WhatsApp activity.

4. **whatsfoto**
   - Link: [whatsfoto](https://github.com/zoutepopcorn/whatsfoto)
   - Description: Download WhatsApp profile pictures.

5. **whatsapp-osint**
   - Link: [whatsapp-osint](https://github.com/jasperan/whatsapp-osint)
   - Description: Log a WhatsApp account's online and offline events.
   - Install: `ot install whatsapp-osint`

## Skype

> Microsoft retired Skype in May 2025. These tools are kept for historical lookups.

1. **addmeContacts**
   - Link: [addmeContacts](http://add-me-contacts.com)
   - Description: Directory of usernames for Skype and other platforms.

2. **ChatToday**
   - Link: [ChatToday](https://chattoday.com)
   - Description: Directory of usernames for chat apps.

3. **Skypli**
   - Link: [Skypli](https://www.skypli.com)
   - Description: Search for Skype users.

## Telegram

1. **ChatBottle: Telegram**
   - Link: [ChatBottle: Telegram](https://chatbottle.co/bots/telegram)
   - Description: Directory of Telegram bots.

2. **ChatToday**
   - Link: [ChatToday](https://chattoday.com)
   - Description: Directory of usernames for chat apps.

3. **informer**
   - Link: [informer](https://github.com/paulpierre/informer)
   - Description: Telegram mass surveillance and monitoring bot framework.

4. **IntelligenceX: Telegram**
   - Link: [IntelligenceX: Telegram](https://intelx.io/tools?tab=telegram)
   - Description: Search and analyze Telegram data.

5. **Lyzem**
   - Link: [Lyzem](https://lyzem.com)
   - Description: Search Telegram groups and channels.

6. **Telegram Channels**
   - Link: [telegramchannels.me](https://telegramchannels.me)
   - Link: [tlgrm.eu](https://tlgrm.eu/channels)
   - Description: Directories of Telegram channels by topic.

7. **Telegram Channels Search**
   - Link: [Telegram Channels Search](https://xtea.io/ts_en.html)
   - Description: Search engine for Telegram channels by keyword.

8. **Telegram Directory**
   - Link: [Telegram Directory](https://tdirectory.me)
   - Description: Directory of Telegram channels, groups and bots.

9. **Telegram Group**
   - Link: [Telegram Group](https://www.telegram-group.com)
   - Description: Search and join Telegram groups.

10. **telegram-history-dump**
    - Link: [telegram-history-dump](https://github.com/tvdstaaij/telegram-history-dump)
    - Description: Dump the history of Telegram chats.

11. **telegram-osint-lib**
    - Link: [telegram-osint-lib](https://github.com/Postuf/telegram-osint-lib)
    - Description: Library for performing OSINT on Telegram.

12. **TeleGram-Scraper**
    - Link: [TeleGram-Scraper](https://github.com/th3unkn0n/TeleGram-Scraper)
    - Description: Scrape members and media from Telegram groups.

13. **Telepathy**
    - Link: [Telepathy](https://github.com/jordanwildon/Telepathy)
    - Description: Toolkit for investigating Telegram chats and accounts.
    - Install: `ot install telepathy`

14. **Telegram Phone Number Checker**
    - Link: [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker)
    - Description: Bellingcat tool that checks whether phone numbers are connected to Telegram accounts.
    - Install: `ot install telegram-phone-number-checker`

15. **Tgram.io**
    - Link: [Tgram.io](https://tgram.io)
    - Description: Search Telegram channels, groups and bots.

16. **TGStat**
    - Link: [TGStat](https://tgstat.com)
    - Link: [TGStat RU](https://tgstat.ru)
    - Description: Analytics and search for Telegram channels and groups.

## Discord

1. **DiscordOSINT**
   - Link: [DiscordOSINT](https://github.com/husseinmuhaisen/DiscordOSINT)
   - Description: Resources for conducting research on Discord, including search syntax.

2. **Discord.name**
   - Link: [Discord.name](https://discord.name/)
   - Description: Discord profile lookup by user ID.

3. **Lookup Guru**
   - Link: [Lookup Guru](https://lookup.guru/)
   - Description: Discord profile lookup by user ID.

4. **Discord History Tracker**
   - Link: [Discord History Tracker](https://dht.chylex.com/)
   - Description: Save chat history from servers, groups and DMs and view it offline.

5. **Top.gg**
   - Link: [Top.gg](https://top.gg/)
   - Description: Directory of Discord bots and servers.

6. **Discord.id**
   - Link: [Discord.id](https://discord.id/)
   - Description: Unofficial Discord profile lookup by ID.

7. **Disboard**
   - Link: [Disboard](https://disboard.org/)
   - Description: List and find public Discord servers.

## YouTube

1. **Yark**
   - Link: [Yark](https://github.com/Owez/yark)
   - Description: Archive YouTube channels, including metadata changes and deleted videos, and browse them offline.
   - Install: `ot install yark`

2. **Auto Archiver**
   - Link: [Auto Archiver](https://github.com/bellingcat/auto-archiver)
   - Description: Bellingcat tool that archives posts and media from YouTube, X, Telegram, TikTok and more.
   - Install: `ot install auto-archiver`

## OnlyFans

1. **OnlyFans Finder**
   - Link: [OnlyFans Finder](https://onlyfansfinder.co/)
   - Description: Search with advanced filtering and sorting.

2. **OnlyFam**
   - Link: [OnlyFam](https://onlyfam.com)
   - Description: OnlyFans search and creator finder.

3. **OnlyFinder**
   - Link: [OnlyFinder](https://onlyfinder.com/)
   - Description: OnlyFans account search engine.

4. **OnlySearch**
   - Link: [OnlySearch](https://onlysearch.co/)
   - Description: Find OnlyFans profiles by keyword.

5. **SóTugas**
   - Link: [SóTugas](https://sotugas.com/)
   - Description: Find OnlyFans accounts in Portugal.

6. **Fansmetrics**
   - Link: [Fansmetrics](https://fansmetrics.com/)
   - Description: Search across millions of OnlyFans accounts.

7. **Findr.fans**
   - Link: [Findr.fans](https://findr.fans/)
   - Description: OnlyFans search tool.

8. **Hubite**
   - Link: [Hubite](https://hubite.com/en/onlyfans-search/)
   - Description: Advanced OnlyFans search engine.

9. **SimilarFans**
   - Link: [SimilarFans](https://similarfans.com/)
   - Description: Find similar OnlyFans creators.

10. **Fansearch**
    - Link: [Fansearch](https://www.fansearch.com/)
    - Description: Search across millions of OnlyFans accounts.

11. **FullDP**
    - Link: [FullDP](https://fulldp.co/onlyfans-full-size-profile-picture/)
    - Description: Download full-size OnlyFans profile pictures.

12. **SecretFans**
    - Link: [SecretFans](https://secretfans.net/)
    - Description: Search engine for OnlyFans creators and profiles.

13. **GirlFindr**
    - Link: [GirlFindr](https://girlfindr.com/)
    - Description: Finder tool for OnlyFans creators.

14. **FreeFans.nl**
    - Link: [FreeFans.nl](https://freefans.nl/)
    - Description: Directory of OnlyFans creators, focused on the Netherlands.

15. **FreeFans.de**
    - Link: [FreeFans.de](https://freefans.de/)
    - Description: Directory of OnlyFans creators, focused on Germany.

16. **OnlyBritish**
    - Link: [OnlyBritish](https://onlybritish.uk/)
    - Description: Directory of OnlyFans creators from the United Kingdom.

17. **OnlySuomi**
    - Link: [OnlySuomi](https://onlysuomi.fi/)
    - Description: Directory of OnlyFans creators from Finland.

## TikTok

1. **Mavekite**
   - Link: [Mavekite](https://mavekite.com/)
   - Description: Look up a TikTok profile by username.

2. **TikTok Hashtag Analysis**
   - Link: [TikTok Hashtag Analysis](https://github.com/bellingcat/tiktok-hashtag-analysis)
   - Description: Download posts and videos for a set of hashtags over a period of time.

3. **SSSTik**
   - Link: [SSSTik](https://ssstik.io/en-1)
   - Description: Download TikTok videos without the watermark.

4. **Exolyt**
   - Link: [Exolyt](https://exolyt.com/)
   - Description: TikTok analytics and insights.

## Other

1. **Alfred OSINT**
   - Link: [Alfred OSINT](https://github.com/Alfredredbird/alfred)
   - Description: Open-source tool for discovering social media accounts.

2. **OFToolbox**
   - Link: [OFToolbox](https://oftoolbox.net)
   - Description: List of tools for creating, sharing and monetizing content on platforms such as OnlyFans.

3. **GraphIn**
   - Link: [GraphIn](https://osintverse.com/graphin)
   - Description: Browser-based link analysis. Map how accounts, emails, phone numbers and domains connect, and share the case map read-only.

## Further reading and resources

- [Awesome OSINT](https://github.com/jivoi/awesome-osint) – a broader curated list covering every OSINT discipline.
- [Bellingcat Online Investigation Toolkit](https://bellingcat.gitbook.io/toolkit) – tool write-ups with usage notes and limits.
- [otinstaller](https://github.com/OSINTVerseHQ/OTinstaller) – install and run the open-source tools in this list by name ([docs](https://osintverse.gitbook.io/otinstaller), [1.5-minute demo](https://youtu.be/_AfUGMFRaKA)).
- [OSINT learning path](https://osintverse.com/resources/course) – a step-by-step course from first search to a full case.
- [The Hub](https://hub.osintverse.com) – field notes and webinars on OSINT techniques.
- [OSINT Collective](https://osintverse.com/collective) – a monthly virtual meetup for investigators.
- [OSINTCon archive](https://osintverse.com/osintcon) – recorded talks from a past virtual OSINT conference.
- [OSINTOne API](https://osintverse.com/developers) – one key and one schema for many OSINT data providers, if you want to script lookups.

## FAQ

#### Is using OSINT illegal?

No. Collecting publicly available information is legal in most places, but using it for illegal purposes or with harmful intent is not. Check the laws in your jurisdiction and each platform's terms before you start.

#### Are these the only tools for social media OSINT?

No. There are many more; this list covers the ones we have found most useful. See [Further reading and resources](#further-reading-and-resources) for broader lists.

#### How do I install the command-line tools here?

Each GitHub project has its own install instructions. If you're on Linux, the tools marked with `ot install …` can be installed in one step with [otinstaller](#installing-the-command-line-tools).

#### Where can I find more tools for social media OSINT?

We keep adding tools to this repo. You can also suggest one by opening an issue or a pull request.

## Contributions

Contributions are always welcome! Open an issue or a pull request, or reach us on any of the channels below with suggestions.

- Email: [hi@osintverse.com](mailto:hi@osintverse.com)
- Website: [osintverse.com](https://osintverse.com)
- GitHub: [@OSINTVerseHQ](https://github.com/OSINTVerseHQ)
- X (Twitter): [@osintversehq](https://x.com/osintversehq)
- LinkedIn: [OSINTverse](https://www.linkedin.com/company/osintverse)
- YouTube: [@osintversehq](https://www.youtube.com/@osintversehq)
- Reddit: [r/OSINTVerse](https://www.reddit.com/r/OSINTVerse/)

## Authors

- [@OSINTVerseHQ](https://github.com/OSINTVerseHQ)
- [@dheerajydv19](https://github.com/dheerajydv19)
- [@swayamsopnic](https://twitter.com/Swayamsopnic16)

Developed with ❤️ in India 🇮🇳
