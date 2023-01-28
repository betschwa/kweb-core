# Introduction

## Why another web framework?

Kweb is designed to make it easy for developers to create modern websites without having to worry about the complexities of communication between the server and browser. With a unified codebase, you can focus on creating an intuitive and user-friendly interface, rather than spending time on technical details. 
By streamlining the development process, Kweb makes it easier to build and maintain functional and beautiful websites.

## How does it work?

Kweb is a remote interface for a web browser's DOM (Document Object Model). With Kweb, you can create 
and manipulate DOM elements, and listen for and handle events, all using an intuitive Kotlin DSL that mirrors 
the structure of the HTML being created. Kweb is built on the Ktor framework, which handles HTTP, HTTPS, and 
WebSocket transport, and is optimized to minimize latency and resource usage on both the server and browser.

## Features

* End-to-end Kotlin - Write your entire web site or user interface in Kotlin, Kweb takes care of browser-server communication
* Real-time synchronization of your back-end data with your web page - Kweb takes care of all the plumbing for you
* Server-side HTML rendering with hydration - Kweb renders your HTML on the server before sending it to the browser
* Efficient instruction preloading - Kweb avoids unnecessary server communication by preloading instructions
* Very lightweight - Kweb is just 5k lines of code

## Relevant Links

* [GitHub repository](https://github.com/kwebio/kweb-core)
* [API documentation](https://docs.kweb.io/api/)
* [Example Google Cloud Project](https://github.com/freenet/freenetorg-website/)
* [Questions/Feedback/Bugs](https://github.com/kwebio/kweb-core/issues)
* Chat with us on [Matrix](https://matrix.to/#/#kweb:matrix.org)
