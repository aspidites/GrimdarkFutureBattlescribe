[![Build Status](https://travis-ci.com/sprutton1/GrimdarkFutureBattlescribe.svg?branch=master)](https://travis-ci.com/sprutton1/GrimdarkFutureBattlescribe)

<!-- TOC -->autoauto- [Introduction](#introduction)auto- [How do I use these files?](#how-do-i-use-these-files)auto    - [Instructions](#instructions)auto- [How can I help?](#how-can-i-help)auto    - [Adding an army](#adding-an-army)auto        - [Guidelines](#guidelines)auto        - [What's Done](#whats-done)auto    - [Reporting an issue](#reporting-an-issue)auto- [Credits](#credits)autoauto<!-- /TOC -->

# Introduction

Welcome to the Battlescribe repo for [OnePageRules'](https://onepagerules.com/)
[Grimdark Future](https://onepagerules.com/portfolio/grimdark-future/). This is
a set of files to use with the [Battlescribe](https://battlescribe.net/) app to
build army lists.

You can always reach out to me on
[Discord](https://discordapp.com/channels/610199287346888743/610199287346888746)
or the [OPR Forum](http://forum.onepagerules.com/) if you need something.

# How do I use these files?

In order to use these files, you must manually add the index to Battlescribe and
then refresh the data.

The index is hosted at:

https://grimdark-future.s3.amazonaws.com/index.bsi

## Instructions

[Instructions for Desktop](./desktop.md)

[Instructions for Mobile](./mobile.md)

# How can I help?

## Adding an army

Open a Github issue on this page with which army you would like to see added and
assign yourself to it. We can track progress on those issues.

Then, pick an army and create a datafile for it! I suggest using the Human
Defense Force as an example. Once you are done, open a Pull Request and I will
review the changes before shipping them up to be indexed.

Also, if you make progress on a list, make sure you update the "What's Done"
table!

### Guidelines

1. The "Publication" entry should contain the name of the list you're
   implementing **including** the version (so we know what versions are
   current).

2. You should never add anything to the game system file (.gst) that's not in
   the main ruleset (except weapons).

3. Weapons found in multiple lists should be added to the game system file.
   Lists should use the entries from the game system file instead of entries in
   the army file itself in this case.

4. When in doubt on how to format something, feel free to ask!

### What's Done

| Army | Version | Progress |
|---|---|---|
|Game System|v2.10|Done|
|Alien Hives|v2.9|Done|
|Battle Brothers|Main v2.12 - Prime v2.12 - Detachments v2.12|Done|
|Battle Sisters|v2.9|Done|
|Dark Elf Raiders|v2.7|Done|
|Dwarf Guilds|v2.5|Done|
|Elven Jesters|v2.5|Done|
|Feudal Guard|v2.7|Done|
|Havoc Brothers|Main v2.10 - Disciples v2.12|Done|
|High Elf Fleets|v2.8|Done|
|Human Defense Force|v2.12|Done|
|Human Inquisition|2.6|Done|
|Infected Colonies|v2.3|Done|
|Machine Cult|v2.9|Done|
|Machine Cult Defilers|v2.2|Done|
|Orc Marauders|v2.10|Done|
|Ratmen Clans|v2.5|Done|
|Rebel Guerrillas|v2.3|Done|
|Robot Legions|v2.8|Done|
|Soul-Snatcher Cults|v2.7|Done|
|TAO Coalition|v2.10|Done|
|Titan Lords|v2.3|Done|
|Wormhole Daemons|v2.8|Done|



## Reporting an issue

If you find something wrong with any of the existing army lists, please open a
Github issue so that myself or the owner of that file can address it.

# Credits

Matthew Caron for his work on the original set of Battlescribe files for GF

Scott Prutton for doing this thing.

Darguth for ongoing maintenance and updates.