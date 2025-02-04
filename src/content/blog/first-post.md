---
title: 'Diverse (like) Features of Front-End Frameworks'
description: 'Is there a difference with these frameworks? Are they just the same?'
pubDate: 'January 23, 2025'
heroImage: '/blog-placeholder-3.jpg'
---

#### **Introduction**<br>
It all started as I wondered what the **_best front-end framework_** to use in a project.

So I decided to check out different front-end frameworks myself. 

After 2 days, I learned that there are a lot of frameworks like Next.js, Laravel, Nuxt, Solid.js, SvelteKit, Angular, Astro, Vite, Ember.js, etc.

As I progressed in researching these front-end frameworks and also checking some Youtube videos about these Frameworks, they didn't mention directly some differences between these front-end frameworks.

I got frustrated because those YouTube videos had a lot to say, yet they didn’t even mention the things I wanted to hear.

With that in mind, I used **_four different_** front-end frameworks to explore their diverse features.

#### **NPM React**<br>
First, I tried npm React, a simple React implementation in a project. 

You can check it here to know what I mean by npm React [(React)](https://react.dev/).

Once installed with npm, I noticed that it has a prebuilt folder and file structure templates. 

It provides an organized and simple approach when it comes to building websites.

<ScreenShot of that folder structure>

This is my first time using the React framework with npm, so I didn’t use it to its full extent.

I just wanted to know how it feels to utilize React.

This npm package is great for beginner React developers. It provides everything needed to integrate React.js with HTML.

#### **Vite React**<br>
Next, I tried Vite + React. It is similar to npm react framework, but it renders JSX to HTML faster. (Based on the reviews and written in its website and documentation.)

Vite also has pre built templates from npm, and it has its own particular folder structure, which is different from npm React, but it also contains the same files and folders.

<ScreenShot of that folder structure>

Well, its usage is the same as npm React, with no differences. 

But it is just the folder structure and also how fast the rendering part is.

It is written on its website you can check it here. [(Vite)](https://vite.dev/) it has a fast front-end build.

#### **NextJS React**<br>
I am currently using Next.js with React. I explored this framework because my team, Team Flux, required it for the version 2 revision of our software, Inspectrum, which won 2nd place in HackFest FlutterFlow 2024.

Among all the frameworks I’ve worked with, I find Next.js to be modern and equipped with built-in import functions. Unlike standard React, this framework uses TSX instead of JSX.

Additionally, I attended a React framework seminar where they mentioned that TSX is more effective at preventing errors compared to JSX.

Moving on, Next.js includes built-in templates for folders and files, streamlining development. While the folder structure remains similar to React, the HTML is rendered in different files.

**layout.tsx:** Handles component rendering.

**page.tsx:** Utilized for folder-based routing.

One of the best features of Next.js, in my opinion, is that you don't the need to install react-router-dom because it has a built-in routing system.

#### **Astro Framework**<br>
Well, this blog is written in astro.. (Writing this part soon!)

#### **TailwindCSS Framework Guides**<br>
Every time I create a project using React, I always utilize the framework with TailwindCSS, since it has a very simple and customizable CSS. 

https://tailwindcss.com/

With TailwindCSS, I have fewer files to handle since all CSS is utilized inside the JSX/TSX.

Though at first, I bashed it to the heck..

I was like _"How can I even style with this? There will be tons of code in my UI file?? Bruh, too many css and tags.."_

But we live and learn.. that's why in creating projects, I like tailwindCSS. hehehe

#### **Folder Structure; Front-End Frameworks**<br>
These front-end frameworks have pre-built templates when installed with npm.

NPM React, Vite, and Next.js have the same files but with different folder structures.

#### **Component Rendering; Front-End Frameworks**<br>
NPM React and Vite have the same way of rendering a component and both utilize JSX.\

It has a main.jsx file that is responsible for rendering the App.jsx component into the DOM, knowing that App.jsx acts as the core structure of the application, containing the UI and logic.

Next.js is somewhat different. You can utilize JSX with Next.js, but it also has TSX. In my POV, it is better to use TSX than JSX with Next.js.

TSX is much more preventive in errors than JSX.

With rendering, Next.js has the layout.tsx file, which is where metadata and rendering components are placed into HTML.

#### **Page Routing; Front-End Frameworks**<br>
React-router-dom is used in both npm React and Vite, and you need to install it to enable routing between pages. 

However, Next.js has built-in routing and linking, so you don't need to install react-router-dom, which I think is a great feature.

#### **Conclusion**<br>
To summarize everything, these frameworks are the same in terms of functionality and usage.

The difference lies in their folder structure and routing… for now..

And I guess it is all about a developer's preferences.

