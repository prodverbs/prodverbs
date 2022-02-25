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



## Your backups are only as good as your last restore. {#test-your-backups}

Unless you restore your data and verify you can read it with your production systems, you don't know if your backup will work.


## Global systems fail globally. {#global-systems}

A global system is a single system or instance that everything else depends on.
If it fails, everything that depends on it might as well.
Isolate your systems from hard dependecies on global systems, so they can fail independently.


## No Licking Cookies.

## Don't abide haunted graveyards.

## Don't feed the machine with blood.

## Always have a bigger hammer.

## Complex systems produce complex failures

## Tail latency dominates distributed systems.

## At scale, rare failures happen all the time.

## Page for symptoms, alert on causes, graph anomalies

## Extra 9's may require exponential effort.

## Good SLAs describe the system, great SLAs tell you how to use it.

## All systems have an SLA defined by their past performance.

## If you hear hoofbeats, think horses, not zebras.

## If you redesign system X, then you have to build all the supporting infrastructure yourself.

## Production is never homogenous.

## Your production environment and codebase are full of Chesterton's Gates.

## Replicated systems end up with replicated state.

## With a sufficient number of users of an API, it does not matter what you promise in the contract: all observable behaviors of your system will be depended on by somebody. - Hyrum's Law

## If two systems must agree for them to work, someday they will inevitably disagree.

## All software development is maintenance software development.

## “Any sufficiently complicated system has at its root an unmaintainable flat text file.” – huber’s Law of Systems

## Decrease variance, Increase mean.

## Find problems before you start serving.

## Design systems for continuous failure.

## Don't detect failure—detect the absence of success.

## Global systems fail globally.

## Backups are only as good as the last restore.

## SRE scales with the number of differences, not the total size of a system.

## Jitter and truncated binary exponential backoff are the best ways to squash a client-inflicted DDoS.

## Anything that can become synchronized will become synchronized. If you don't have randomness inserted in your intervals, it will stay synchronized.

