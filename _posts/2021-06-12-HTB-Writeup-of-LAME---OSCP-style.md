---
published: true
---
## Intro

Following writeup describes the methodology that was necessary to get user and root access to the retired lab system “lame” hosted and provided by hackthebox.eu.
I have done this machine as a preparation for the [OSCP course](https://www.offensive-security.com/pwk-oscp/) exam by Offensive Security and will outline the steps that were important to get high level access rights for Windows (Administrator, user with admin rights or SYSTEM) and for Linux based systems (root).

### Restrictions during the OSCP

In the following I will respect most of the restrictions put on students by Offensive Security to give you as a reader an inside on how they want that a student works and for me to prepare myself for the exam. _- wish me luck ;-)_

To list some of them:

* metasploit framework usage restriction _(I try to avoid the usage completely in my preparation)_
* reproducable documentation style 
* trophy proof restrictions
* several documentation style restrictions _(these I will not apply within this writeup)_ 

_It is worthwile to mention that there are plenty restrictions on the exam that I am not listing here and they might change in the future, that is why you should have a look at the current reporting requirements at the time you do your OSCP exam, currently available [here](https://help.offensive-security.com/hc/en-us/articles/360040165632)._

## Getting our hands dirty

### Reconnaissance and Scanning
### Gaining Access
### Vulnerabilities and Recommendations
### Maintaining Access and Cleanup

## Food for Thoughts



##################################################

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2 (H1 is reserved for post titles)##

### Header 3

#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

An image, located within /images

![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

Syntax highlighting can be used with triple backticks, like so:
---
layout: post
title: Markdown Style Guide
---

This is a demo of all styled elements in Jekyll Now.

[View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2 (H1 is reserved for post titles)##

### Header 3

#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

An image, located within /images

![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

Syntax highlighting can be used with triple backticks, like so:

```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
```

Use two trailing spaces  
on the right  
to create linebreak tags  

Finally, horizontal lines

----
****
```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
```

Use two trailing spaces  
on the right  
to create linebreak tags  

Finally, horizontal lines

----
****