---
title: "CompletePiSSTV"
date: 2018-09-24T22:39:03+01:00
lastmod: 2018-09-24T22:39:03+01:00
description: "SSTV on a Raspberry Pi"
tags : [ "SSTV", "Raspbery Pi"]
categories : [ "Amateur Radio" ]
layout: post
type:  "post"
highlight: true
draft: false
---

The Complete PiSSTV is a compilation of programs designed which enables anyone to convert their Raspberry Pi Computer into an amateur SSTV (Slow Scan TV) transmitter with no additional RF equipment*.

Originally a fork of the [SUWS/pisstv] project, which had the same purpose, however, has undergone significant changes that the only remanents are the parts of the install script.

This project offers a number of improvements over the original including a faster generation of the SSTV audio waveform, and "superior signal purity" by modulating the PLL rather than the clock divider.

Included Programs:

* Pi-FM-RDS - This program generates an FM modulation, with RDS (Radio Data System) data generated in real time. It can include monophonic or stereophonic audio.
* PiSSTV - is a simple implementation of various SSTV protocols, to be used by low-frills computers running a CLI, such as with Raspberry Pis and so on. Its intended for use by ham radio amateurs.

## Repository
The files and instructions can be found at [Stealthbird97/CompletePiSSTV]


[Stealthbird97/CompletePiSSTV]: https://github.com/Stealthbird97/CompletePiSSTV
[SUWS/pisstv]: https://github.com/SUWS/pisstv
