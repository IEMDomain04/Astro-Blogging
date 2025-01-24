---
title: 'Diverse (like) Features of Front-End Frameworks'
description: 'Is there a difference with these frameworks? Are they just the same?'
pubDate: 'January 23, 2025'
heroImage: '/blog-placeholder-3.jpg'
---

Well, this is my first time writing a blog, so please bear with me as my interest in writing blogs started to kick in.

I want to be good at writing stories and blogs, not just in tech.

**Introduction**<br>
It all started as I wondered what the best front-end framework to use in a project.

So I decided to check out different front-end frameworks. 

I learned that there are a lot of frameworks like Next.js, Laravel, Nuxt, Solid.js, SvelteKit, Angular, Astro, Vite, Ember.js, etc.

As I progressed in researching these front-end frameworks and also checking some Youtube videos, they didn't mention directly some differences between front-end frameworks.

I guess it is all about a developer's preferences.

With all that said, I utilized 4 different front-end frameworks myself to see what diverse features they have.

**NPM React**<br>
First, I tried npm React, a simple React implementation in a project. 

You can check it here to know what I mean by npm React [(React)](https://react.dev/).

Once installed with npm, I noticed that it has a prebuilt folder and file structure templates. 

It provides an organized approach when it comes to building software.

<ScreenShot of that folder structure>

Well, this npm React is my very first usage of the React framework, so I didn’t utilize it to its full extent.

I just wanted to know how it feels to utilize React.

This npm is good for starters for React developers. It has what you need to implement React.js with HTML.

**Vite React**<br>
Next, I tried Vite + React. It is similar to npm react framework, but it renders JSX to HTML faster. (Based on the reviews and written in its website and documentation.)

Vite also has pre built templates from npm, and it has its own particular folder structure, which is different from npm React, but it also contains the same files and folders.

<ScreenShot of that folder structure>

Well, it has the same usage as npm React, nothing different. 

But I guess it is just the folder structure and also how fast the rendering part is.

It is written on its website you can check it here. (Vite), it has a fast front-end build.

**NextJS React**<br>
Currently, I utilize Next.js React. I managed to explore this framework because it was required by my team (Team Flux) for the version 2 revised version of our software (Inspectrum) that won 2nd place in HackFest FlutterFlow 2024.

I figured that out of all frameworks, this is modern and has built-in import functions.

This framework utilizes TSX instead of JSX.

Also I would like to share that there’s this react framework seminar, where they said that TSX is much more preventive to errors than JSX.

Moving on, as usual, this also has built-in templates of folders and files for your development.

Same folder structure, but different files where the HTML is rendered.

Next.js React has a layout.tsx file that is responsible for rendering the components.

Next.js has the page.tsx component, which will be utilized by folder-based routing.

The best thing about Next.js, in my perspective, is that it doesn’t need to install react-router-dom since Next.js has a pre-built function for routing.

**Astro Framework**<br>
Well, this blog is written in astro.. (Writing this part soon!)

**TailwindCSS Framework Guides**<br>
Every time I create a project using React, I always utilize the framework with TailwindCSS, since it has a very simple and customizable CSS. 

https://tailwindcss.com/

With TailwindCSS, I have fewer files to handle since all CSS is utilized inside the JSX/TSX.

**Folder Structure; Front-End Frameworks**<br>
These front-end frameworks have pre-built templates when installed with npm.

NPM React, Vite, and Next.js have the same files but with different folder structures.

**Component Rendering; Front-End Frameworks**<br>
NPM React and Vite have the same way of rendering a component and both utilize JSX.\

It has a main.jsx file that is responsible for rendering the App.jsx component into the DOM, knowing that App.jsx acts as the core structure of the application, containing the UI and logic.

Next.js is somewhat different. You can utilize JSX with Next.js, but it also has TSX. In my POV, it is better to use TSX than JSX with Next.js.

TSX is much more preventive in errors than JSX.

With rendering, Next.js has the layout.tsx file, which is where metadata and rendering components are placed into HTML.

**Page Routing; Front-End Frameworks**<br>
React-router-dom is used in both npm React and Vite, and you need to install it to enable routing between pages. 

However, Next.js has built-in routing and linking, so you don't need to install react-router-dom, which I think is a great feature.

**Conclusion**<br>
To summarize everything, these frameworks are the same in terms of functionality and usage.

The difference lies in their folder structure and routing… for now..

