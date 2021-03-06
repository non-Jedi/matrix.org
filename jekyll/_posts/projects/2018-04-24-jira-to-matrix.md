---
layout: project
title: jira-to-matrix
categories: projects bot
description: A bot which listens to JIRA Webhooks and sends stuff between Matrix and Jira.
author: Mobitel Ltd
maturity: Beta
language: JavaScript
license: 
repo: https://github.com/mobitel-ltd/jira-to-matrix
---

# {{ page.title }}
A bot (web-service) which:

* listens to JIRA Webhooks and sends some stuff to Matrix;
* use command from Matrix Riot to integrate with Jira and make different actions.

Features
+ Creates a room for every new issue;
+ Invites new participants to the room;
+ Posts any issue updates to the room;
+ Appropriately renames the room if the issue was moved to another project;
+ Post new links to related rooms. Notifies when a related issue's status changes;
+ Talks in English or Russian only (easily extendible, see `src/locales`).

Repository: <{{page.repo}}>
