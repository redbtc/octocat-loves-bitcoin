# Octocat ❤ BTC

This repo is a demo/playground for an experimental mechanic which enables project backers to be a noticeable part of the development process/community and be immortalized in the project history together with the developers. This might potentially be a great booster for open-source development.

## How it works

- When someone creates a new issue in the repo, it automatically gets a new comment with "support the issue" info and "Pay with BTCPay" button
- When the pay button is pushed and a payment is made (as a GitHub user or anonymously), it triggers a series of actions as per the following rules:
  - update the "support issue" comment with the backer username (if not anonymous)
    - the position depends on the total amount donated by the backer on the issue
    - if the total backer-issue amount is >=0.001 BTC, then the backer's avatar is also added (the avatar sizes differ depending on the amount)
  - post a "@username (or anonymous) donated ฿" comment on the issue if the donation amount is >=0.0005 BTC (the templates and image sets differ depending on the amount)
  - add "priority" label to the issue, if the total amount donated by all backers on the issue is >=0.001 BTC
  - trigger the actions of the common Red BTC - wide donation logic of the "Become a backer" button on <a href="https://redbtc.org/">Red BTC website</a> and <a href="https://github.com/redbtc/">Red BTC repos</a> (including this one)

## Is it open source?

It's built with the open source <a href="https://redbtc.org/">Red BTC stack</a> & <a href="https://github.com/redbtc/node-red-contrib-github-plus">node-red-contrib-github-plus nodeset</a>. The flow implementing the mechanic will be open-sourced after trying it on a few projects. If you want to participate in the experiment and add this mechanic to your repo(s), <a href="https://github.com/redbtc/octocat-loves-btc/issues">create an issue</a>.

## Backers 💝

[[Become a backer](https://mynode.redbtc.org/gh-donate)]

[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/0/avatar/60)](https://mynode.redbtc.org/gh-backer/top/0/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/1/avatar/60)](https://mynode.redbtc.org/gh-backer/top/1/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/2/avatar/60)](https://mynode.redbtc.org/gh-backer/top/2/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/3/avatar/60)](https://mynode.redbtc.org/gh-backer/top/3/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/4/avatar/60)](https://mynode.redbtc.org/gh-backer/top/4/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/5/avatar/60)](https://mynode.redbtc.org/gh-backer/top/5/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/6/avatar/60)](https://mynode.redbtc.org/gh-backer/top/6/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/7/avatar/60)](https://mynode.redbtc.org/gh-backer/top/7/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/8/avatar/60)](https://mynode.redbtc.org/gh-backer/top/8/profile)
[![Red BTC Backer](https://mynode.redbtc.org/gh-backer/top/9/avatar/60)](https://mynode.redbtc.org/gh-backer/top/9/profile)
