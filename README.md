# imdb

A very simple shell script for downloading imdb in json.

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - [jq](https://github.com/stedolan/jq)
 - parallel (optional)

## Installation
    
    install -m 755 imdb /usr/bin

## Json format

Here's [json](example.json).

## Usage

Script downloads all articles using /sitemap/title-[0-9]*.xml.gz and writes it into stdout.

If you want to download it in parallel just uncomment the 3 comments and comment the for loop.
