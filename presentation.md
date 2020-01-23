build-lists: true

# Intro to Web Development

![](https://www.coevote.com/coevote_content/uploads/2018/03/worldwide.jpg)

---

# Jason L Perry

### CEO @ Suncoast Developers Guild

---

# Today's Learning Outcomes:

- Define the Web as it relates to the Internet.
- Explain the separation of responsibilities in each of the three foundational technologies that make up the web.
- Implement a simple static website with HTML and CSS.

---

# A Brief History of the Internet

---

# What is the Internet?

^ A global 'network of networks'
^ Wikipedia says: The Internet is the global system of interconnected computer networks that uses the Internet protocol suite to link devices worldwide.

---

![fit](https://cs.nyu.edu/courses/fall15/CSCI-UA.0004-002/images/internet.gif)

[.footer:]

---

# Did Al Gore invent the Internet?

![](https://static.adweek.com/adweek.com-prod/wp-content/uploads/files/uploads/al-gore-hed-2015.jpg)

^ No, but he did popularize the use of the term: "Information Super Highway"

---

![autoplay loop](https://media.giphy.com/media/RbPbHNLXgyR5C/giphy.gif)

---

# U.S. Department of Defense

## Advanced Research Projects Agency (ARPA)[^1]

![inline](http://mercury.lcs.mit.edu/~jnc/tech/jpg/ARPANet/G69Dec.jpg)

[^1]: Image: http://mercury.lcs.mit.edu/~jnc/tech/arpageo.html.

^ The closest thing to the birth of our modern Internet was ARPANET
^ There were a number of other networks, each speaking a different language, _or_ protocol.
^ What was needed was _internetwork communication_.

---

# TCP/IP[^2]

![inline](https://upload.wikimedia.org/wikipedia/commons/1/13/First_Internet_Demonstration%2C_1977.jpg)

^ Internet protocol suite
^ Transmission Control Protocol (TCP) and the Internet Protocol (IP)

[^2]: Image: https://en.wikipedia.org/wiki/History_of_the_Internet

---

# The Web

![autoplay loop fit](https://media.giphy.com/media/3If8u5wFsfII0/giphy.mp4)

---

# The "World Wide Web" is not the whole internet.

^ Besides the World Wide Web, what are some other Internet protocols you've used?

- FTP
- Usenet (NNTP)

---

# Email

[.column]

- SMTP
- POP3
- IMAP

[.column]

![inline](https://1.bp.blogspot.com/-yH5GeOh0rZI/UDVEbs5N1QI/AAAAAAAAHfc/IoAUPVXhANE/s1600/Youve-Got-Mail-Poster-4.jpg)

---

[.footer:]

# Bittorrent

![autoplay loop](https://media.giphy.com/media/1poV5tPhshE97gw9Df/giphy.mp4)

---

# Cryptocurrencies

![autoplay loop](https://media.giphy.com/media/Nc50m8gBSZUlO/giphy.mp4)

---

# Online Games

![autoplay loop fit](https://media.giphy.com/media/9ok7NGU37j5Pq/giphy.mp4)

---

# HTTP

![](https://cs.nyu.edu/courses/fall15/CSCI-UA.0004-002/images/tim_berners_lee.jpg)

^ Sir Tim Berners-Lee invented the World Wide Web in 1989.

---

[.background-color: #ffffff]
![inline](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13673/6d339b54f6873b97728986a2d9d930dd/HTTP%20%26%20layers.png)

---

[.build-lists: false]

- https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
- https://dev.opera.com/articles/http-basic-introduction/

---

# What is a website?

- HTML
- CSS
- JavaScript

^ HTML, CSS, JS and media assets transfered over HTTP to your Browser.

---

[.background-color: #ffffff]
![inline](http://www.gbengasesan.com/fyp/20/f2-1.gif)

---

![](https://www.aog.jobs/wp-content/uploads/2016/12/maxresdefault-1024x576.jpg)

^ What's the difference between front-end and back-end web development?

---

[.background-color: #eeeeee]
![inline](https://cs.nyu.edu/courses/fall15/CSCI-UA.0004-002/images/html_css_js.png)

---

^ What is HTML?

^ HTML provides structure and content of a webpage, allowing you to add HTML, CSS, other media assets.

^ Very limited control over presentation before CSS was introduced later.

^ Screenshot on Amazon in 1994

![fit](https://cs.nyu.edu/courses/fall15/CSCI-UA.0004-002/images/amazon_1994.gif)

---

^ What is CSS?

^ Allows you to style the elements on a page. Adding presentational aspects; controlling position, color, typography, additional images, etc.

^ Proposed in 1995, first standardized in 1996. Did not see wider implementation and adoption until 1998.

![fit](https://media.giphy.com/media/13FrpeVH09Zrb2/giphy.gif)

---

^ Work on CSS3 begain in 1999, which divided the standard into a number of modules. In varied stages of between draft and recommendation to this day.

![45%](https://upload.wikimedia.org/wikipedia/commons/f/fd/CSS3_taxonomy_and_status-v2.png)

---

^ What is JavaScript?

![fit](https://miro.medium.com/max/1600/0*sN7Gh-sRDm_o678f.gif)

^ Allows you to turn a web page from a static document into a living, breathing interactive experience. Where content can be updated or animated, and respond dynamically to user input.

---

![fit](https://the1995blog.files.wordpress.com/2014/07/netscape-navigator.jpg)

^ Invented by Brendan Eich in 1995, over just 10 days.

---

## [fit] HTML

^ HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content.

^ Text, marked with tags, that give semantic meaning to that text.

---

```
About Me
Hello, my name is Jason. In no particular order, these are some of my very favorite things:
Pandas
Board Games
Code
```

---

```html
<h1>About Me</h1>
<p>
  Hello, my name is <strong>Jason</strong>. In no particular order, these are
  some of my <em>very</em> favorite things:
</p>
<ul>
  <li>Pandas</li>
  <li>Board Games</li>
  <li>Code</li>
</ul>
```

---

[.background-color: #ffffff]
![fit](./assets/html-about-me.png)

---

[.background-color: #1E1C1C]
![inline](https://media.prod.mdn.mozit.cloud/attachments/2014/11/14/9347/c07aa313dbdd667585430f4eca354dbd/grumpy-cat-small.png)

---

^ Structure of an HTML Document.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>
```

---

[.background-color: #1E1C1C]
![inline](https://media.prod.mdn.mozit.cloud/attachments/2014/11/14/9345/99516bbeb470af58b608d17bb30e53e6/grumpy-cat-attribute-small.png)

---

```html
<a href="https://suncoast.io">Suncoast Developers Guild</a>
```

---

# Semantic Markup

- Maintainabiltiy
- Accessibility
- Search Engine Optimization (SEO)

^ Easier to author/update, and rationalize about in our heads
^ Provides context to people who might be using the page through non-tradition means, e.g. the blind, screen readers
^ SEO, gives context for search engine, to understand the importance and meaning of content on your pages

---

## [fit] CSS

---

^ Structure of a CSS document.

```css
body {
  font-family: sans-serif;
  background-color: rebeccapurple;
  color: white;
}

strong {
  color: coral;
}

li {
  list-style-type: "❇️";
  padding: 5px;
}
```

---

[.background-color: #ffffff]
![fit](./assets/html-about-me.png)

---

[.background-color: #663399]
![fit](./assets/css-about-me.png)

---

[.background-color: #ffffff]
![inline](https://media.prod.mdn.mozit.cloud/attachments/2019/12/12/17010/c2f0477d822dcc316fa63daf6f75852c/ruleset.png)

---

```html
<style>
  strong {
    color: coral;
  }
</style>
```

^ The `style` attribute, and the `<style>` & `<link>` tags.

---

```html
<head>
  <!-- ... -->
  <link rel="stylesheet" href="./screen.css" />
</head>
```

---

```html
<!-- This is a comment, you won't see it rendered on the screen. -->
```

---

```html
<p>
  But I must explain to you how all this mistaken idea of denouncing joy and
  praising pain was born and I will give you a complete account of the system,
  and expound the actual teachings of the great explorer of the truth, the
  master-builder of human happiness.
</p>
<p class="note">Don't forget the milk!</p>
<p>
  No one rejects, dislikes, or avoids joy itself, because it is joy, but because
  those who do not know how to pursue joy rationally encounter consequences that
  are extremely painful.
</p>
```

---

```css
p {
  font-family: "Big Caslon", serif;
}

.note {
  float: right;
  font-family: "Marker Felt", script;
  background-color: #f9f3bd;
  color: #22241e;
  padding: 20px;
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 20%);
  transform: rotate(10deg);
}
```

^ How selectors match your page to apply rules.

---

[.background-color: #ffffff]
![inline](./assets/note.png)

---

## JavaScript

---

^ Structure of a JS document.

```html
<script>
  // Your JavaScript goes here
</script>
```

---

```html
<p>Hello, <span class="subject">World</span>!</p>

<script>
  let name = "Jason";
  document.querySelector(".subject").textContent = name;
</script>
```

---

# Hello, World!

---

# Hello, Jason!

---

## [fit] DEMO

## [fit] TIME

---

- Build a project.
