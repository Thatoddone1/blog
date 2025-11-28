---
title: Weird HTTP codes
date: 2025-11-28
description: What does code 418 do? How about 451?
---
# what is an HTTP code?
The internet is built upon humanities best tool, standard. And a lot of then for that matter. And one of those very important standards are HTTP response codes. If you have ever tried to navigate to a webpage that didn't exist, you have seen the HTTP code *404 - Not Found*. There are plenty more liked this, used in the background to allow your computer and the website to communicate the status. Examples being *500 - Sever error*, *200 - OK*, and more. 
# april fools
So where does this get interesting? Programmers are a humorous bunch, usually laughing at their own jokes. On April 1, 1998, then Hyper Text Coffee Pot Control Protocol (HTCPCP) was released, a full standard for how a server that is a coffee pot should conduct it self. As part of this (extended in 2014), a response code, `418`, was officially added in an RFC. Code `418` waas the response to be given if a server was a teapot, and therefore could not brew coffee. Obviously, this was all a joke, but since it is a fully legitimate reserved code, some website return this occasionally as a joke.
## other interesting codes
There are some other interesting codes. I find code `451` quite interesting, the code for "restricted for legal reasons". This code was chosen in name of Ray Bradbury's Book *Fahrenheit 451* — a book all about government censorship. It is used often today when a website can't or doesn't want to serve a particular client because of legal reasons, such as GDPR. Code `402` is also interesting, "payment required", a code that is largely unused right now (but that might change [soon](https://www.x402.org/)!). There are plenty of more numbers to make codes out of, so who knows, we could get some new codes soon!