# Tablet Remote

A home-screen web app for controlling the garage tablet from an iPhone: https://frogemon.github.io/tablet-remote/

It sends commands by opening issues in the private `Frogemon/tablet-control` repo, which the tablet's agent runs
and answers within ~15 seconds. This repo only holds the app's code; your GitHub key is stored on your phone only.

Setup: open the link in Safari, paste a fine-grained token (only `tablet-control`, Issues: read and write),
then Share → Add to Home Screen.
