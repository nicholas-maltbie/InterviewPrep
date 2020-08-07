# InterviewPrep
Satya's Squad[rilateral] interview prep notes

# Viewing the Website

This is a blog website and can be viewed at [https://nicholas-maltbie.github.io/InterviewPrep](https://nicholas-maltbie.github.io/InterviewPrep)

# Setup

In order to develop and work on repository, install Jekyll
using Ruby following [these instructions](https://jekyllrb.com/docs/installation/)

## Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.5.0 or above
* [Ruby Gems](https://rubygems.org/pages/download)

## Installation
Ensure jekyll is installed
```bash
gem install jekyll bundler
```

Download and view the website
```bash
# Clone the repository
cd ~/projects
git clone git@github.com:nicholas-maltbie/InterviewPrep.git

# See current website with command
cd ~/projects/InterviewPrep
bundle install
bundler exec jekyll serve

# View website at localhost:4000

```

## Build

To build the website as a static website use the command
```bash
bundler exec jekyll build
# Will output website to ./_build
```
