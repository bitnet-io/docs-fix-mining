---
title: Satoshi's Ridge (Deep Dive)
description: A comprehensive overview of building useful Stacks dapps
sidebar_position: 2
---
# Nakamotors (Deep Dive)
Alright so you've taken the quickstart tutorial and know how to get started building on Stacks. Maybe you've read a bit of [Stacks Academy](../stacks-academy/) and understand why Stacks is unique ad what benefits it provides.

Now you want to know how to actually build real-world dapps that are actually useful using Stacks.

You're in the right place.

This comprehensive tutorial is designed to teach you everything you need to know about building on Stacks. We'll be introducing all the important tools and concepts with links out to additional resources for you to dive deeper into what you need.

We'll be covering:

* Setup with Hiro's starter packages
* TDD with Clarity and Clarinet
* Writing robust, secure Clarity contracts
* Utilizing Bitcoin in our Stacks dapp
* Creating a smooth, enjoyable frontend with Remix and Micro-Stacks
* Utilizing oracle data with Redstone
* Self-hosting our own Stacks node
* Deploying our app to Fly
* Deploying our contracts to Stacks testnet with Clarinet

We'll be doing all of this by creating an app that will take full advantage of Stacks' Bitcoin connection by allowing us to create a decentralized organization based on Bitcoin.

Let's do this.

## What We're Building
We're going to be building Satoshi's Ridge, a  platform for creating a Bitcoin-based mini-society a la Balaji's [Network State](https://thenetworkstate.com/). If you aren't familiar with The Network State, don't worry. We're basically building a platform that enables us to create a decentralized organization and mini-economy based around Bitcoin.

In The Network State, one of the key ideas is that a network state should have a singular unifying focus. In the case of Satoshi's Ridge, that unifying focus is that of voluntary regulation.

So the primary goal of Satoshi's Ridge is to create a small network state whose focus is on conceiving of and building voluntary regulation systems.

What do we mean by voluntary regulation? Let's look at the FDA as an example. The FDA is an example of centralized, involuntary regulation. Medical products cannot be sold without FDA approval (theoretically, but that's another matter) and there is no alternative to getting FDA approval.

Centralized, involuntary regulation schemes like this are ripe for corruption, because they provide a prime opportunity for corporate interests to influence this centralized entity.

As an alternative, a decentralized system of various voluntary regulatory agencies would allow consumers to purchase products based on the regulatory organizations they trust to evaluate things effectively.

Furthermore, by structuring this system as a DAO where members are the ones funding the organization, we significantly reduce the risk of corruption.

Obviously this is just a tutorial for learning purposes, and there are complex layers of philosophy, politics, economics, and incentive mechanisms at the heart of this, and people will debate about the merits of such systems.

That is not the point of this tutorial, but only to highlight one of the potential use cases for blockchain technology, and more specifically, Stacks and Bitcoin.

These types of systemic changes are where blockchains potential really shines. And by using the world's best money, Bitcoin, as the bedrock of this system, we are building it on a solid foundation.

Bitcoin is an incredible invention, and it generally fixes many of the issues caused by traditional monetary and banking systems, but it doesn't fix human nature.

If our institutions are still centralized and prone to corruption, Bitcoin only changes the funding source. We need to take the same concepts of decentralization that make Bitcoin so powerful and apply them to our institutions as well, with Bitcoin serving as the economic base layer.

That's the power of Stacks, and is what we'll be exploring in this deep dive.

Let's get started building.