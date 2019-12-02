# Intro To React

## Download

- if you do know how to use git: `git clone git@github.com:miku86-workshops/react-beginners.git`
- if you do _not_ know how to use git: [click here to download](https://github.com/miku86-workshops/react-beginners/archive/master.zip)

---

## Contribute

I invite you to contribute to this workshop.

Download or fork the repo and make a pull request.

Thanks!

---

## Slides

## The Past / Before React and other SPAs

### Request-Response Cycle (simplified)

1. Client sends a request
1. Server returns a response

In the end, the Browser needs some HTML. How to get the HTML?

### Pre-Rendered / Pre-Built HTML => Static

1. Developer creates HTML.
1. Developer sends HTML to Server.
1. Client requests the page from Server.
1. Server responds with HTML to Client.

### Built by the server => Dynamic

1. Developer creates application on the Server (PHP/JS/Python/etc.)
1. Client requests the page from Server.
1. Server creates HTML depending on Client's request.
1. Server responds with HTML to Client.

## Which problems do exist?

- static pages: bad, if data changes often (site has to get pre-rendered / pre-built all the tim)
- dynamic: user has to wait for every new page (even if only one small detail changes), high load on the server, internet always needed

## How can we solve these problem?

### Built by the client => Dynamic (Client Side Rendering):

1. Developer creates application (JS).
1. Client requests the page from Server.
1. Server responds with the JS application (from Step #1).
1. Client creates HTML depending on received JS application.

=> Solutions: React, Vue, Angular

## React

- JavaScript library for building user interfaces
- big community
- big eco-system
- backed by a dogfooding company (Facebook)
- compose complex UIs from small and isolated pieces of code called "components"
- JSX as syntactic sugar to create HTML/XML like elements
- Virtual DOM, that updates the browser's displayed DOM efficiently => fast

---

## Links

- http://bit.ly/intro-to-react-boilerplate
- http://bit.ly/intro-to-react-links

---

# Where to go?

- [React Docs](https://reactjs.org/docs/getting-started.html)
- [React Intro (deutsch)](https://www.youtube.com/playlist?list=PLVyp9714_1yLU8EUh4FbOoGPnvsNcAqyB)
