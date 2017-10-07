# **instapy-cli** :zap: [![MIT license](https://img.shields.io/github/license/b3nab/instapy-cli.svg)](https://github.com/b3nab/instapy-cli/blob/master/LICENSE)


[![PyPI version](https://badge.fury.io/py/instapy-cli@.png)](https://badge.fury.io/py/instapy-cli)

Python library and cli used to upload photo on Instagram. W/o a phone!

<p align="center">
  <img src="docs/instagram-private-banner.png" alt="instagram-private-api" width="650px">
</p>
---
## Introduction
There are a plenty of libraries written in Python dedicated to Instagram APIs (public or ***private***, no matter).. but most of them have unsolved issues and PR not maintained for a time as long as 5-6 months.

At the same time lots of developers want a simple and effective way to post/**upload** an photo/**image** **programmatically**.

So I dedice to start this repo and OpenSource it w/ :heart:


***`[FUTURE] spoiler:`*** And if I want to upload a video?


### Usage
Be careful, this repo is in a status of "work in progress" :rotating_light:

**Install**

`pip install instapy-cli`

**Use**

`instapy -f <PATH/TO/IMAGE.jpg> -t "Instagram caption here!" -u <username> -p <password>`

**Help**

`instapy --help`

### Why instapy-cli?
First, long story short: instapy-cli is a fork of pynstagram, with the aim of extend its functionality and fix all unresolved bug.

##### Move this project to a better place :arrow_right_hook:
Anyone that want to collaborate, I'll promise to be a good Repo Manager and merge all yours Pull Request as soon as possible.
I have some ideas to improve this but I need collaboration. Enter and support! :bulb:

##### But, wait! Instagram don't let to upload a photo except from app ( of course :trollface: )
Short answer:
> Yes, you are right.

Long answer:
> Every connection from a mobile phone could be intercepted. Someone has done the hard work to sniff the packets sended from phone to Instagram and "spread the news". You could do a quick research.

### License
MIT


### Contribute
To help `instapy-cli` developers to build and maintain this project, go to **[docs/CONTRIBUTING.md](/docs/CONTRIBUTING.md)**
> instruction soon

(Write it if you want to collaborate! :smirk:)
