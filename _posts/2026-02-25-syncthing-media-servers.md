---
title: Using Syncthing to manage my 6TB media library
date: 2026-2-25
categories: [Plex, Media Server, Self-hosting]
tags: [data storage]
image:
  path: /assets/img/posts/syncthing.png
  alt: Syncthing
---

## The Issue
So I have two media servers running Plex. They are geographically separate, and both can serve the same media. They function as backups of each other. 

I would prefer to have an offline backup, but my library is 6TB and growing, and I don't really need to have that much storage sitting in a closet doing nothing. 

These two servers constantly get out of sync as I update the libraries separately and use Onedrive to sync between them. My Onedrive has 250GB of storage, and has worked until now, but I'm being demoted to the free plan (5GB) and I'd prefer to build a lasting solution to this problem.

Thus, lets use Syncthing

## What is Syncthing?
From their homepage:
  Syncthing is a continuous file synchronization program. It synchronizes files between two or more computers in real time, safely protected from prying eyes. Your data is your data alone and you deserve to choose where it is stored, whether it is shared with some third party, and how it’s transmitted over the internet.

you can check it out [here](https://syncthing.net/)

## The setup

- The first server is on a synology NAS. This network also has a windows machine that is always one, and I will be using this machine as the Syncthing client to reduce pressure on synology.

- The second server is on a windows 10 machine with external drives attached. This machine constantly crashes since the Windows 10 EOL, so it must first be upgraded to Ubuntu 24.

## The Solution

<a href="https://github.com/colinklich/blog/edit/main/{{ page.path }}">✏️ Edit this page</a>
