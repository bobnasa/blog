---
layout: post
title: "Password Managers? Working on my own CLI!"
author: "Bob"
categories: journal
tags: []
image: photo-1457364887197-9150188c107b.avif
---

I hope you know that you shouldn't re-use your passwords across services. You do, right?
Well, but how can you remember dozens of strong passwords?
You can't and that's ok, just store them on your computer!

I created a file locally where I put all my passwords.
Using a few bash commands, it's really convenient to use it and you don't have to remember the command to exit vim :D

```bash
bob@nasa:~$ echo "github bob******@protonmail.com pa55w0rd" >> passwords.txt
bob@nasa:~$ echo "nasa bob s3cret" >> passwords.txt
bob@nasa:~$ grep "github" passwords.txt
github bob******@protonmail.com v3ry5ecure
bob@nasa:~$ 
```

Of course, these are not my real passwords :D
Look into this [Wikipedia article](https://en.wikipedia.org/wiki/Password_strength) to create secure passwords.

Currently I am writing a Python script that makes it even easier to use this.
So you should definitely come back and have a look!

> Photo by [SpaceX](https://unsplash.com/photos/-p-KCm6xB9I) on Unsplash
