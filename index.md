---
title: 'Prodverbs: Production Proverbs'
layout: 'default'
---

# Prodverbs: Production Proverbs

## Hope is not a strategy {#hope-not-a-strategy}

Always have a backup plan.

_Luck is not a factor. Hope is not a strategy. Fear is not an option._ -- James Cameron


## Hyrum's Law {#hyrums-law}

With a sufficient number of users of an API, it does not matter what you promise in the contract: all observable behaviors of your system will be depended on by somebody.

Not only will users depend on all features, they will assume that they have an [SLO equivalent to observed behavior](#slo-status-quo).

[hyrumslaw.com](https://www.hyrumslaw.com/)



## When in doubt, the SLO is the status quo. {#slo-status-quo}

There's always a baseline expectation of performance. Without an explicit SLO, past performance becomes implicit SLO.

Referred to as _Hettich's Epigram_ ([twitter](https://twitter.com/jjjtttrrr/status/1446144136730447872))

See also [Hyrum's Law](#hyrums-law)



## Your backups are only as good as your last restore. {#test-your-backups}

Unless you restore your data and verify you can read it with your production systems, you don't know if your backup will work.


## Global systems fail globally. {#global-systems}

A global system is a single system or instance that everything else depends on.
If it fails, everything that depends on it might as well.
Isolate your systems from hard dependecies on global systems, so they can fail independently.

