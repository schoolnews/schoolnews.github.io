---
layout: default
---

# Documentation

## Usage/Editing

Editing a site like this is a little different than most people would expect.
Instead of manually going through the code and finding the various items that 
need to be changed, you simply have to look at the files in the `_data` 
directory. The rest of this page provides examples representing every possible 
field that can be used in the file. In the examples below, many of these fields 
are optional. If you do not require that field, just skip adding that line.

**Some important notes:** 

* `.yml` files can be a little annoying at times. Indentation can _only_ be done 
using spaces. 

* While not required, when a line is longer than 80 characters, 
usually used in descriptions, consider using the `>` character as shown below.
This helps everybody so they do not have to scroll left and right to read the 
data file.

```yml
description: >
  Really long text goes here...
  It can even span multiple lines!

  If you need a separate paragraph, separate them with a blank line.
```

* Anything that starts with a dash (`-`) can be repeated over and over and over...
It is a list, where each item start with that dash.

* In some cases, you might see text like `[...]`.
This represents an array. Think of this like a list where each item is separated with 
a comma. Example: `["Something", "Something Else", "Unknown something"]`

* All description like fields accept 
[markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/).
In markdown, the asterisk starts a list item. Feel free to use any markdown you wish.

## Data Files

### wordofthemonth.yml

```yml
wordofthemonth: 

pastwinners:
  - word: 
    names: [...]
```

### birthdays.yml

```yml
belated: [...]
today: [...]
future: [...]
```

### Sports

#### sports/sportname-date-time.yml

```yml
sport:
date: 
time: 
location: 
score:
  - team: 
    points: 
result: 
awards: 
changes: 
tickets: 
```

### Clubs

#### clubs/clubname.yml

```yml
name: 
meetingdates: 
nextdate: 
location: 
time: 
description: 
changes: 
website:
twitter:
facebook:
remind:
```

## Announcements
### announcements/year-month-day-title.yml

```yml
title: 
enabled: 
date: 
time: 
location: 
description: 
extendeddescription: 
picture: 
video: 
tweet: 
```
