---
title: "Error Checking"
date: 2022-09-08T14:54:36-04:00
---
# Overview
Description of how error checking is handled in DNA storage

# Description
In DNA storage, there are three types of errors that need to be accounted for: "substitutions of one base by another" and insterted bases and deleted bases, called indels (Press). To account for substituted bases, you could read the set of data multiple times, but this doesen't account for spontaneous data insertion or deletion. Various methods should be explorered, with the goal of minimizing redundant data and error rate. When testing translation-compression algorithms, error rate will be considered part of the metric and redundant data will affect the compression ratio.

[Bibliography](/about/bibliography)