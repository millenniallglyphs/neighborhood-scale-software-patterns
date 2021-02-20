---
layout: post
title:  "Federated Decentralization"
date:   2021-02-20 11:33:27 +01:00
categories: pattern
tags: [
    {tag: 'web' },
    {tag: 'distributed'}
]
images:
    - https://i.redd.it/qpwnc17hlfa41.jpg
    - https://joinpeertube.org/img/peertube-federation-multiplicity.jpg
---

## Context

Online life centralization enables corporate ownership and control of people's data and means of expression. Complete decentralization and disintermediation, where every user owns and administrates their server nodes, is currently unfeasible.

## Problem

Online centralization is a well documented problem. It enables censorship and often prevents pro-active handling of trolling and moderation issues. Business owners' interests rarely match the interests of users. 

Completely decentralized networks, where each user is expected to run their own node for hosting or mining purposes, present a huge technical burden, and often require users to have spare machines, and uninterrupted internet access. More often than not, those systems encourage reintermediation, in the form of businesses that provide a better UI for transactions, enable discovery, store wallets or host servers. This defeats the purpose of decentralization and adds a chain of new intermediaries that need to be trusted, and whose interests might not match the user's.

## Solution

A federated network, where users connect to a specific node they choose. Each node is hosted and administered independently, and enforces its own rules. It is functionally the same as "intermediated decentralization" described above, but with the benefit of transparency. It does not pretend to be what it is not.

## Examples

- The [Mastodon](https://joinmastodon.org) fediverse.
- [PeerTube](https://joinpeertube.org/).
- SMTP and email.
