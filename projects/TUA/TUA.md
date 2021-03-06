---
author: Benoît "badetitou" Verhaeghe
layout: project
title:  "Tests Usage Analyser"
date:   2017-08-08 09:29:00 +200
categories: research smalltalk spy tests _ignore
---

## What is Tests Usage Analyser?

Tests Usage Analyser (TUA) is a plugin developed in [Pharo](http://pharo.org/). It is a spy that allow anybody to record everything on every image of a developer (in Pharo).

TUA was developed with a TUA toolkits composed by [TUA-Decoder](http://smalltalkhub.com/#!/~badetitou/TUA-Decoder) and [TUA-ImageReconstruction](https://github.com/badetitou/TestUsageAnalyser-ImageReconstruction)

To install TUA. The easiest way is to execute the following code in a Playground.

```st
Metacello new
    smalltalkhubUser: 'Pharo' project: 'MetaRepoForPharo60';
    configuration: 'TestsUsageAnalyser';
    version: #stable;
    get;
    load.
```

## Installation

I supposed you already install Pharo. If not, please [install it](http://pharo.org/download).

Using TUA is really simple you only have to install it. And it works. You will notice nothing but all the data are logged and send to a distant server.



## Utilisation

Because TUA is just a recorder.
The software doesn't provide at the moment option to change where the data are sent, the version number or which data are sent.
But you can fork the project and help us by adding this option.

You should take a look at TUA-Decoder and TUA-ImageReconstruction to see what you can do with Tests Usage Analyser.

## Uninstall

To uninstall CORA, it's a bit hard currently. You have to follow this instruction:

- Disable TUA in the settings (System menu)
- Unload TUA

## Links

The projects are present on [smalltalkhub](http://smalltalkhub.com/#!/~badetitou/TestsUsageAnalyser).
We are working on the migration to GitHub.
