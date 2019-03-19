---
title: Getting Started
layout: topic
categories: guide
---

## Forward

This documentation website was created as a guiding hand to get you started hacking together the best possible project.
We'd like to reassure you that while we may present advanced concepts in our documents, we do not in any way expect
you to use them. We're all here to have fun after all.

We'll start simple and cover increasingly complex technologies. Work at your own pace and don't be afraid to experiment.
Think long, think hard, imagine solutions to unsolved problems, or problems that haven't been thought of yet.
What you create today could be spark of the next Facebook or Google. You're only limited by your own imagination.
On that note, let's get started.

## An Introduction to WebDev

Someone has to make your favorite websites and web applications you use on the internet. 
It can be easy to take them for granted. To be able to understand how a website works, 
you need to understand how the internet works.
For the sake of time, we'll keep it as abstract as possible.

The internet is a global network of linked computers. The computers that are exposed to the wider network are referred to
as `servers`. The word `server` can refer to both the computer, or the computer software itself running a website.

Servers "serve" information to viewers, allowing them to download webpages to view and navigate. A server can be run from almost any computer with the right software. You can also run a server `locally` on your own computer for development purposes. It doesn't necessarily have to be connected to the internet.

At a fundamental level, websites are a collection of files and code that work together to make delightful interactive applications that communicate with the internet.

## Protocols and Ports

There's this thing called the internet layer, which allows `hosts`, (all `servers` are considered to be hosts, but not the other way around) to communicate with each other using `ports`. In computer networking, a port is a communication endpoint. It is where data is sent and recieved in the form of `packets`.

With basic websites you'll be dealing with ports `80` and `443`. Port `80` serves packets over `http`. HTTP stands for
HyperText Transfer Protocol - the standard protocol for internet layer communication.

Port 443 serves `https`, HTTPS stands for HyperText Transfer Protocol Secure. It almost the same as `http` except that it uses Transport Layer Security (`TLS`), or its predecessor, Secure Sockets Layer (`SSL`) to encrypt packets.