# Hi there.

## Status

- I'm currently working on my blog and my thesis;
- I'm currently learning front-end development and machine learning;

## My Blog

is separately implemented in serveral distributed packages (a.k.a. subsystems, services), and most of those are hosted on Vercel. 

What mostly noticeable among them (the subsystems) are:

- [blog-ng-nextjs](https://github.com/hsiaofongw/blog-ng-nextjs), the front-end, the index page and the directory pages;
- [blog-data-nextjs](https://github.com/hsiaofongw/blog-data-nextjs), the Content Management System (CMS) built by myself, it mainly serves JSON and some of my uploaded PDF files.
- [markdown-blog](https://github.com/hsiaofongw/markdown-blog), hosting my Markdown files, rendering them into ReactElements before there is a request.

These packages, and other packages that my blog is consisted of, are basicly based on Next.js, React, and TypeScript.

I also built my Email service, which togethered with another telemetry service I build, implemented services monitoring.

There is also a comment service in my blog, which is based on Next.js (front-end), Nest.js and MongoDB (back-end), due to that it is still lack of maturity, I choose not to make it open.

Write every part of this blog in TypeScript, enables the behaviours of the entire system can be clearly model and defined. With the help of TypeScript's powerful features on typing, We now can easily make them work together cohesively and harmoniously.

Rather to say my blog is a big and intact whole, I prefer to say that my blog is in forms of many small independent subsystems. It is several small units integrated to perform as a blog to the outside, rather than one intact one serves several functions.

## What I am learning

- TypeScript, MongoDB, React, Nest.js, Next.js. I belived that someday I will be capable of bulding amazing things from those technologies.

- Recommendation system, Recurrent Neural Network. For my thesis.

## What I will doing

Just implement rest parts that is said to be necessary or important for a properly functional and intact blog system.

What I choose to do it myself but not by just pick the matured solutions like hugo, hexo, wordpress? Because by do it myself, the things I build are at least clear to me, the internal mechanism of every subsystem is visible and understandable to all. A programmable, scalable, flexible, resilient and clearly structural blog system is appealing to me. I will keep working on building every part and every sub-system that it should consist.
