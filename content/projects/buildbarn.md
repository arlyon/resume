---
title: "buildbarn"
date: 2019-08-18T10:43:38+01:00
draft: false
pin: false
tags: ["go", "distributed consensus", "etcd", "remote execution"]
demo: ""
source: "https://github.com/buildbarn"
# last two are used in schema.org/SoftwareSourceCode
language: "go"
---

Abstracted out the scheduler into a generic pluggable interface
and implemented a backend for etcd, removing a single point of
failure. 
