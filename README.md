# soloproject-evaluation

## Table of Contents

* [Overview](#overview)
* [Evaluation Conditions & Feedback](#evaluation-conditions--feedback)
* [Example Feedback](#example-feedback)

## Overview

This repo contains a standard list of conditions and feedback for feedback
provided to Chingu's on the [Solo Project](https://chingucohorts.notion.site/Solo-Project-Conditions-Feedback-a2597fbd2f554500ad231aeea189ffb1) they are 
required to submit prior to their first Voyage.

We want our feedback to achieve these goals:

1. Provide feedback to help our Members become better Developers.
2. Provide feedback to help our Members correct issues, but also to encourage
practices we find that they are doing well.
3. Provide feedback that is consistent & fair, regardless of who performs the
Solo Project evaluation.

Keep in mind that we don't do strict, university-style evaluations. We don't 
expect Solo Projects to be perfect apps. We actually want members to pass if 
their project has a readme and works properly, even though it may contain minor
flaws.

## Evaluation Conditions & Feedback

* [Project Evaluation Results](#project-evaluation-results)
* [Tier](#tier)
* [Readme](#readme)
* [Commits](#commits)
* [HTML/CSS](#htmlcss)
* [Repo](#repo)
* [Code](#code)
* [Automated Tests](#automated-tests)
* [UI/UX](#uiux)
* [Career](#career)
* [Product Owners](#product-owners)
* [Data Scientists](#data-scientists)

In these tables, the `Feedback` column is formatted as code since they may
contain Markdown syntax.

In addition, you should use the `Importance` column to determine the relative
importance of the various evaluation conditions.

### Project Evaluation Results

| Condition | Feedback |
|-----------|----------|
| Passed | Hi @  Congratulations on your hard work and dedication. Your Voyage 46 Solo Project has been accepted and you are advancing to the Voyage Phase starting on October 2nd. Watch the <#1026584387569078373> channel for more information. <br/><br/> ```**_If you haven't yet signed up for Voyage 46 complete this form so you don't miss out _** ``` —> https://forms.gle/DajSfXQCX4qbMAu8A <br/><br/>I’m looking forward to seeing what you and your team will be creating in your Voyage! <br/><br/>https://c.tenor.com/bDxOr4tSm7kAAAAC/spongebob-high-five.gif <br/><br/>Here is some more specific feedback which I hope will be helpful: </br> |
| Requested changes | Hi @  Your app shows that you’ve invested a considerable amount of thought and effort in its design & implementation. <br/><br/>Please make the following change and then open a ticket in <#1105911757177888908> when you are ready for me to look at it again. ``` **_This is the only change you are required to make._** ``` <br/><br/> ```__**Requested changes**__``` <br/> 1. ... <br/><br/>```**_Here’s additional feedback that I hope will be helpful_**```. |
| Requested changes - no GH repo URL or deployed URL | Hi @ I started to review your Solo Project, but you haven’t provided a valid URL for a specific GitHub repo and the URL where it’s deployed on the Internet.<br/><br/>We ask for this so we can not only look at your code, but also the running application and its UI/UX. In addition, knowing how to deploy to a web host like GitHub Pages, Netlify, Vercel, Render, etc. is a skill you’ll need in your Voyage.<br/><br/>Please open a ticket in #📧open-support-ticket when you have this URL and we'll start the evaluation. Thanks! |
| Requested changes - no deployed URL | I started to review your Solo Project, but you haven’t provided a valid URL for where it’s deployed on the Internet. <br/><br/>We ask for this so we can not only look at your code, but also the running application and its UI/UX. In addition, knowing how to deploy to a web host like GitHub Pages, Netlify, Vercel, Render, etc. is a skill you’ll need in your Voyage. <br/><br/>Please open a ticket in <#1105911757177888908> when you have this URL and we'll start the evaluation. Thanks! |
| Repo URL not found |	I started to review your Solo Project, but the URL you’ve provided for your repo is not found (HTTP/404). <br/><br/>This often happens if the repo is marked as private in GitHub instead of public. <br/><br/>Please open a ticket in <#1105911757177888908> when you have this URL and we'll start the evaluation. Thanks! |
| Requested changes - old project ( last change over 12 months ago) |	I started to review your Solo Project, but the project you provided does not have any changes in the past 12 months. We would like to see that you've been coding recently. <br/><br/>Please open a ticket in <#1105911757177888908> when you have a newer project and we'll start the evaluation. Thanks! |
---

[Back to TOC](#evaluation-conditions--feedback)


### Tier
Tier 1 - scripting language; 
Tier 2 - frontend framework; 
Tier 3 - backend or database
| Condition | Importance | Feedback |
|-----------|------------|----------|
| App doesn’t match selected tier | High | ```* This Solo Project is a Tier 2, rather than a Tier 3 app, so you are eligible to join the next Voyage as a Tier 2 participant. You can learn more about our tiers and the requirements of each here —> https://chingucohorts.notion.site/Solo-Projects-2a41ff900cc24a72a919f0eb5e79c42b``` |
| AI generated app | High | ```* This Solo Project was created using and AI tool. We don't accept apps generated using AI since we want to understand your Web Dev skills - not the AI's skill. You can learn more about our tiers and the requirements of each here —> https://chingucohorts.notion.site/Solo-Projects-2a41ff900cc24a72a919f0eb5e79c42b``` |
| Project doesn’t contain any scripting language files (e.g. Javascript, Ruby, PHP, Python, etc.) (Request Change)| High | ```* App shows you understand CSS & HTML, but doesn't contain any scripting such as Javascript, PHP, Python, Ruby, etc. Scripting is important in a Voyage. **_Please add something like a floating scroll to the top button implemented in JS to one of the pages._** ``` |
---

[Back to TOC](#evaluation-conditions--feedback)


### Readme

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Good readme | High | ```* Your repo includes a good readme. Here’s additional info to show how to structure a well-written readme. You can use this to improve your readme in future projects https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d.``` |
| No readme (request changes)| High | ```* You haven’t included a readme in your repo. This is a critical part of any project and here’s additional info to show how to structure a well-written readme.  https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d.``` |
| Unusable readme (request changes)| High | ```* You haven’t included a usable readme in your repo. This is a critical part of any project and here’s additional info to show how to structure a well-written readme. https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d.``` |
| Readme needs improvement | High | ```* Your repo contains a readme that could be even better with a few changes.  This is an important part of any project and here’s additional info to show how to structure a well-written readme.  https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d.``` |
| Good readme, but no screenshot/gif | High | ```* Your readme is good, but could be even better with the addition of a screenshot/gif.  Here’s additional info to show how to structure a well-written readme. You can use this to improve your readme in future projects https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d. ```|
| Readme is generated by a utility | High | ```* Your readme is the template generated by CRA and could be improved. Here’s additional info to show how to structure a well-written readme. You can use this to improve your readme in future projects https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d. ```|

---

[Back to TOC](#evaluation-conditions--feedback)


### Commits

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Commits are atomic & commit messages are descriptive | High | ```* Your commits are atomic and your commit messages are descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.``` |
| Commits are atomic, but commit messages aren’t descriptive | High | ```* Your commits are atomic, but some commit messages could be more descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.``` |
| Commits aren’t atomic, but commit messages are descriptive | High | ```* Your commits aren’t atomic, but your commit messages are descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.``` |
| Commits aren’t atomic and commit messages aren’t descriptive | High | ```* Your commits aren’t atomic and your commit messages could be more descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.``` |
| Files have been uploaded to GitHub rather than by using git | Medium | ```* Changes appear to be made directly to GitHub using file uploads. Suggest using git so individual commits/changes can be tracked. Here’s more information on how to use Git & GitHub to provide better tracking and change management. https://docs.github.com/en/get-started/using-git/about-git``` |

---

[Back to TOC](#evaluation-conditions--feedback)


### Repo

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Repo is well organized | High | ```* Your repo is well organized. This is very important since you'll spend more time maintaining an app than writing it. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2. ``` |
| Source code not in `src` directory | High | ```* I suggest you look at adding source code files to a `src` directory in the root of your repo in future projects. This has little benefit on a project of this size, but for other projects with many source files, the organization it adds will make understanding the app easier. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2``` |
| Repo is well organized, but no separate BE & FE subdirectories | High | ```* Your repo is well organized. But, you can make it even better by adding a `backend` subdirectory for your BE code and a `frontend` subdirectory for your FE code. This is very important since you'll spend more time maintaining an app than writing it. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2. ``` |
| Repo is well organized, but source code is included in a directory that should be merged into the root of the repo | Medium | ```* I suggest you move the source code files in the `` directory into the root of your repo in future projects. This directory currently adds an extra, unnecessary directory level to the project, and moving it will make understanding the app easier. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2``` |
| Image files not in their own subdirectory	| High | ```* You can make your repo even more organized by moving your image files into their own subdirectory. For example, `images`.``` |
| Configuration files not in their own subdirectory	| Medium | ```* You can make your repo even more organized by moving your configuration files, such as site.webmanifest, into their own subdirectory. For example, assets.``` |
| Additional src file organization required	| High | ```* You should consider improving the organization of your repo by creating additional subdirectories under the src directory for specific types of functionality. For example, a components subdirectory for page components. This will help you and any contributors to the project quickly and easily locate specific types of files based on their usage.``` |
| `node_modules` directory included in GitHub repo | High | ```* I suggest adding `node_modules` to `.gitignore` to reduce GitHub repo size. Since this subdirectory is built and managed by NPM from your `package.json` file there’s no advantage to including it in GitHub. However, this is merely a best practice and doesn’t impact how the application runs.``` |
| Python env directory included in GitHub repo | High | ```* I suggest adding `env` to `.gitignore` to reduce GitHub repo size. Since this subdirectory is built and managed by NPM from your `requirements.txt` file there’s no advantage to including it in GitHub. However, this is merely a best practice and doesn’t impact how the application runs.``` |
| Update package.json to move `devDependencies` to be adjacent to `dependencies` | Low | ```* In your `package.json` file consider moving `devDependencies` to be adjacent to `dependencies`. This is a minor change, but since the two need to be examined together during troubleshooting it’s something that could be a timesaver.``` |
| `devDependencies` in `dependencies` | Medium | ```* `@/types` dependencies should be in devDependencies, so they are not installed in production. It is also easier to manage if dependencies are categorized. You can learn more about differen types of dependencies here https://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencie.``` |
| Unused dependencies | Medium | ```* There are unused dependencies in your package.json, such as ``. Removing unused dependencies can reduce the size of your package, which is beneficial when deploying your application. Other reasons to remove unused dependencies include - improves security, easier maintenance, faster installation and builds. You can use `depcheck` to analyze dependencies. https://www.npmjs.com/package/depcheck``` |
| Packages are embedded in repo | Medium | ```* There are several libraries, like `popper.js` embedded in the repo which will greatly increase bundle size. Consider using a bundler like NPM or versions hosted on CDNs to improve initial page load time. This will also let you take advantage of any fixes and changes made by the vendor without having to redeploy your app. However, it does increase the risk of a breaking change impacting your code.``` |
| Code embedded as script in HTML file | High | ```* Javascript code is embedded in your HTML file as a <script>. It’s actually a best practice to include code as a separate file that’s referenced by a <script> tag, rather than embedding the code itself. Here’s information describing the situation in detail and how to deal with it https://www.thoughtco.com/moving-javascript-out-of-the-web-page-2037542``` |
| `.env` file included in GitHub repo | High | ```* App secrets are exposed in plaintext in the `.env` file. A best practice to follow is to add this file to your `.gitignore` so it’s not uploaded to GitHub. https://medium.com/chingu/an-introduction-to-environment-variables-and-how-to-use-them-f602f66d15fa ``` |
| Build files included in Github repo | High | ```* Build files like `/dist` should not be committed. They are generated files that can be easily reproduced from the source code and build configuration. It unnecessarily increases the repository size. Including them in version control can also create extra conflicts to resolve when multiple developers are working on the same codebase.```|
---

[Back to TOC](#evaluation-conditions--feedback)


### HTML/CSS

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Script tag in wrong location | High | ```* In `index.html`  you might want to move the `<script>` tag to the end of the `<body>` section or to use the `defer` attribute on the `<script>` tag to prevent blocking during initial page load. You can learn more about this option here https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script#attr-async``` |
| Add defer attribute to script | High | ```* In `index.html`  you might want to move the `<script>` tag to the end of the `<body>` section or to use the `defer` attribute on the `<script>` tag to prevent blocking during initial page load. You can learn more about this option here https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script#attr-async``` |
| Good use of semantic HTML | Low | ```* You have made good use of semantic HTML. This is a good best practice to follow since it provides meaning to the elements on the page, which is better than any code comments. https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html``` |
| Needs semantic HTML | Low | ```* Your HTML is good, but could be even better by using semantic tags. This is a good best practice to follow since it provides meaning to the elements on the page, which is better than any code comments. https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html``` |
| JS embedded in HTML files	| High | ```* Instead of embedding your Javascript in the HTML files it's an industry best practice to place them in .js files in a src directory in your repo. This doesn't impact the operation of the app, but it makes the code easier to find and troubleshoot. Something you'll appreciate as the app grows in size.``` |
| Large CSS file | Medium | ```* Your main CSS file, ``, is quite large. Breaking this up into multiple files, for example, one for a master layout and the other for individual pages and components, will help make troubleshooting somewhat easier. In addition, separate file names help to add contextual meaning to their contents.``` |
---

[Back to TOC](#evaluation-conditions--feedback)


### Code

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Code is readable & maintainable | High | ```* Your code is readable & maintainable. This is very important since you'll spend more time maintaining an app than writing it. I guarantee that in just a few weeks you'll forget the details you know today. Anything you can do to improve readability & maintainability is a gift to your "future self". ``` |
| Follows SRP principle | High | ```* You have done a good job splitting logic into multiple files & functions so that each has a single responsibility. If you are looking for more info on SOLID principles here’s info that may be of interest https://tinyurl.com/yg26bsot``` |
| Doesn’t follow SOLID principles | High | ```* Consider splitting logic into multiple files & functions so that each has a single responsibility. This won’t have much of an impact on a small app, but it’s a good best practice to get into the habit of following. If you are looking for more info on SOLID principles here’s info that may be of interest https://tinyurl.com/yg26bsot.``` |
| Good use of code comments | Low | ```* Your code comments are very good. They provide additional explanations of the code without making it hard to read. https://www.stepsize.com/blog/the-engineers-guide-to-writing-code-comments``` |
| Some irrelevant comments | High | ```* Some files contain code comments that are irrelevant (e.g. `server.js`). Although this doesn’t affect how the app runs, it could make reading and debugging the code more difficult.``` |
| Too many comments | High | ```* There are a bit too many comments explaining obvious code, this can be counterproductive in some cases. Comments should be used to provide clarity and context to your code, making it easier for other developers (including your future self) to understand your code's functionality, logic, and intentions.  Here's an article you might find interesting - https://www.freecodecamp.org/news/5-comments-you-should-stop-writing-and-1-you-should-start-4d66a367cd2c/``` |
| Some commented-out code | Low | ```* There is some commented-out code in your source files (such as in ``).  Even though this doesn’t affect the operation of the app it can make troubleshooting and debugging more difficult.``` |
| Some folders/files unused | High | ```* There are some empty or unused folders/files in your source files (such as in ``).  These placeholder folders/files should be removed if there are no plans to use them. They clutter the project directory and make it harder to navigate. They can also sometimes provide misleading information about the project status. ``` |
| Good use of environment variables to protect app secrets | High | ```* Great job using environment variables to protect app secrets, like API keys. As you know, protecting application secrets isn’t an option and is critical to protecting apps from unscrupulous hackers.``` |
| Sensitive information exposed in `` | High | ```* Sensitive information, like an API key, is exposed in plaintext in ``. Consider moving these to environment variables.  https://medium.com/chingu/an-introduction-to-environment-variables-and-how-to-use-them-f602f66d15fa``` |
| Repeated code	| Medium | ```* The itemPrice function is repeated in in both pages/Cart.js  and pages/Pdp.js . In future apps consider extracting this logic into a utility function that can be shared. This is known as the DRY principle ('Don't Repeat Yourself', and it will help make the app easier to maintain and enhance. https://en.wikipedia.org/wiki/Don't_repeat_yourself``` |
| Database calls issued from FE	| High | ```* One security concern is you are directly accessing the database from the FE, rather than through a BE app server. This is a security concern since it is impossible to secure browser applications. A more secure approach is to only access your database through an API to a custom backend application server since backend servers can be secured.``` |
| Good error checking | Low | ```* You have done a very good job intercepting and handling errors in a way that provides useful information to maintainers and which allows the app to fail gracefully.``` |
| Insufficient error checking | High | ```* There is no error checking following your API call in `Dictionary.js`. It is important to intercept and handle errors in a way that provides useful information to maintainers and which allows the app to fail gracefully.``` |
| Needs more descriptive variable names	| High | ```* Consider using variable & constant names that are more descriptive. This makes the code more readable by adding context, which can be more effective than any code comment. https://www.brainstobytes.com/writing-good-variable-names/``` |
| Good choice of descriptive variable names	| High | ```* You have done a good job selecting variable & constant names that are descriptive. This makes the code more readable by adding context, which can be more effective than any code comment. https://www.brainstobytes.com/writing-good-variable-names/``` |
| Good use of vanilla JS to manipulate the DOM | High | ```* Good use of vanilla JS to manipulate the DOM. This is an important skill to master and one that will help when you start to learn FE frameworks like React, VueJS, SvelteJS, etc.``` |
| Hardcoded server URL in FE | Low | ```* In `` you have hardcoded the URL to a BE server/service. This can increase maintenance time since a change to a URL will require updates to one or more source files + additional test time. Instead, consider placing URLs in environment variables so they can be modified with no code changes.``` |
| Good attributions for copied code | High | ```* Good work including attributions to code copied from other sources. This shows professional courtesy to other Developers and is much appreciated. ``` |
| Used `var` instead of `const/let` | Medium | ```* In `script.js` you have used `var` instead of `const/let`. This doesn’t impact how the app runs, but is a good defensive practice to adopt. This article explains the difference between the and why `const/let` is favored over `var` in modern JS. https://tinyurl.com/y5zj33d7``` |
| Nested if’s	| High | ```* Some `if` statements nested too deeply (some at 3+ levels such as in ``). This can make troubleshooting problems and adding enhancements extremely difficult. One option is to split these into smaller discrete functions.``` |
| Routes, controllers & middleware logic embedded in a single server-side file. | Medium | ```* In the BE consider isolating routes, controllers, & middleware logic into separate files in your BE. This doesn’t impact how the app will run, but it will make it easier to enhance and debug as it grows.``` |
| Routes, controllers & middleware logic separated into different files	| Medium | ```* In the BE you have done a good job of isolating routes, controllers, & middleware logic into separate files in your BE. This doesn’t impact how the app will run, but it will make it easier to enhance and debug as it grows.``` |
| Hardcoded data embedded in a Javascript file | Low | ```* In `` consider placing the `` array into a separate file and import it to reduce the number of lines in this file. Separating procedural code from declarative data reduces the number of lines in the file, which can make it easier to read, debug, and enhance.``` |
| Hardcoded data included in separate file | Low | ```* You have done a good job isolating constant data into `` so it can be imported into other files to reduce the number of lines in this file. Separating procedural code from declarative data reduces the number of lines in the file, which can make it easier to read, debug, and enhance.``` |
| Magic numbers used | Low | ```* You should consider using constants in place of "magic" numbers to provide contextual meaning (e.g. `request: 10000` in `location.js`). This is often better than any code comment. Here's additional info on magic numbers https://jeffreyeverhart.com/2020/09/28/javascript-tips-using-named-constants-for-magic-numbers/#:~:text=What Are Magic Numbers%3F, replaced by a named constant.&text=Date.,-.``` |
| Implemented common code	| Low | ```* Good work implementing your own functions for dealing with date formatting instead of relying on a library. Although there’s nothing wrong with using a library they often contain far more functions than what you need for something like this, which increases your bundle size.``` |
| Switch/case statements | Low | ```* In `` you have made effective use of switch/case statements. But, for future projects consider encoding the information in an array of JS objects and searching to find the desired result. This doesn't improve performance, but it does make for less code and is straightforward to implement.``` |
| Too many global variables | High | ```* Global variables should be avoided when possible. It should only be used for static values in most cases. Functions should return values instead of updating global values. https://www.baeldung.com/cs/global-variables``` |
| Next.js - Mixing App and Pages router | High | ```* I noticed you are using both app and pages router. In the nextjs docs it is recommended that only use one of them. `Good to know: Although you can use both routers in the same project, routes in app will be prioritized over pages. We recommend using only one router in your new project to avoid confusion.` https://nextjs.org/docs/getting-started/installation#the-pages-directory-optional``` |
---

[Back to TOC](#evaluation-conditions--feedback)


### Automated Tests

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Good use of automated testing | Medium | ```* You have done a good job creating automated tests to validate basic app functionality. Here’s advice from one of my favorite authors for testing JS applications https://testingjavascript.com/```

---

[Back to TOC](#evaluation-conditions--feedback)


### UI/UX

| Condition | Importance | Feedback |
|-----------|------------|----------|
| UI/UX is clear, concise, & engaging | High | ```* UI/UX is clear, concise, & engaging. Here’s a set of principles I hope you will find helpful for future projects. https://www.justinmind.com/ui-design/principles``` |
| UI/UX needs improvement	| High | ```* UI/UX could be better if it contained more color and/or images to capture the users interest and keep them on your page. Here’s a set of principles I hope you will find helpful for future projects. https://www.justinmind.com/ui-design/principles``` |
| App is responsive | High | ```* Your app is responsive. This is important given the fact that many users rely on mobile devices. Here’s some information that may help you understand this for your future apps  https://developers.google.com/web/fundamentals/design-and-ux/responsive/.``` |
| App isn’t responsive | High | ```* Your app isn’t responsive. This is important given the fact that many users rely on mobile devices. Here’s some information that may help you understand this for your future apps  https://developers.google.com/web/fundamentals/design-and-ux/responsive/.``` |
| App is partially responsive | High | ```* Your app is partially responsive, but has alignment & layout issues on smaller screen devices, like phones. This is important given the fact that many users rely on mobile devices. Here’s some information that may help you understand this for your future apps  https://developers.google.com/web/fundamentals/design-and-ux/responsive/.``` |
| No browser tab title | Low | ```* There’s no unique title on the browser tab. Instead of using the default of `React App` generated by CRA consider adding a unique page title. This will make it easier for users to find your app when they have multiple tabs open in the browser.``` |
| No Page title	| Medium | ```* There is no title on your web page. Consider adding one to provide context to your users about this app.``` |
| Some debugging info in browser console | Low | ```* There are some debugging messages in the browser console. This doesn’t impact running the application, but if overdone in a production app these can hide more critical error messages.``` |
| Some application features & functions aren’t working | High | ```* There are some application features & functions that are not working (eg. Buttons & clicking on a product card). Make sure you address this before sharing this in an interview since you want applications you share with potential employers to be fully functional and free of defects.``` |
| Missing favicon | High | ```* In the browsers console log an error message indicates you have a missing favicon. To correct this you can either add a favicon ( http://www.faviconcodegenerator.com/ ) or suppress the error message ( http://www.faviconcodegenerator.com/prevent-favicon-404-error.php ).``` |
| Default favicon | Low | ```*The favicon is the default react favicon. It doesn't affect the operation of the app, but a customized favicon contributes to your website's branding efforts, improves user experience, and helps establish a professional and distinctive online presence. You can learn more about Favicons here https://blog.hubspot.com/website/what-is-a-favicon#why-matter.``` |
| Some error messages in browser console | Medium | ```* There are some error messages in the browser console. This doesn’t seem to impact running the application, but if overdone in a production app these can hide more critical error messages.``` |
| UI/UX Design detail	| Medium | ```* Your design is also quite detailed and complete. This is important since it acts as a blueprint Developers will use to implement your design in code. The more complete and clear the design is, the fewer questions and issues will be raised between the Design & Development teams. The result will be greater development efficiency & a more solid implementation for the users.``` |
| Undisplayable images | Medium | ```* Some of the images on your site aren't being properly displayed. This can be the result of incorrect paths or simply missing files. Make sure you address this before sharing this in an interview since you want applications you share with potential employers to be fully functional and free of defects.``` |
| Large image sizes | Medium | ```* Some of the images on your site are quite large, which impacts page load time. One quick option to address this is to use alternative dimensions and file formats (like WebP or AVIF). Here's more info on the details of these formats https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types``` |
| Large image sizes/Many images | Medium | ```* One option that can make the loading of images on your site faster is to host them on a Content Delivery Network (CDN) to reduce network access time, regardless of where users may be accessing your site from. https://developer.mozilla.org/en-US/docs/Glossary/CDN``` |
| Large GIFs | Medium | ```* Your site includes some large GIF’s. While these have a big impact on the visual presentation they are not the most efficient way to deliver animated content. Instead, consider using MPEG4 or WebM videos and PNG/WebP for static images. This will reduce the network load to deliver pages to the browser (the largest contentful paint metric). For more information —> https://web.dev/efficient-animated-content/?utm_source=lighthouse&utm_medium=devtools``` |
| Images have incorrect aspect ratio | High | ```* At least one image has an incorrect aspect ratio (`https://uploads-ssl.webflow.com/619b5fa1265aac7aba0eedee/6210aca65fdbb33630d8afb4_Frame 3-p-500.png`). When the ratio specified in your CSS/HTML is significantly different from that of the source image it could appear distorted. Here’s additional information you may find useful https://web.dev/image-aspect-ratio/?utm_source=lighthouse&utm_medium=devtools``` |
| UI is accessible | Medium | ```* Your UI is accessible. This is important since it makes it usable for users with different types of impairments, such as those with color blindness. Here’s a good resource if you want to learn more about the concept & practice of designing accessible websites: https://www.a11yproject.com/``` |
| UI isn’t accessible - no [alt] | Medium | ```* Your UI has some accessibility issues. Specifically, image elements don’t have an [alt] attribute. This is important since it makes it usable for users with different types of impairments, such as those with color blindness. Here’s a good resource if you want to learn more about the concept & practice of designing accessible websites: https://www.a11yproject.com/``` |
| Improve Internationalization | Low | ```* Your page HTML doesn’t contain a lang attribute, which allows screen readers to read the page in the users default language. This is important for users with vision impairments who rely on screen readers. You can learn more about this attribute here https://dequeuniversity.com/rules/axe/4.4/html-has-lang?utm_source=lighthouse&utm_medium=devtools``` |
| Contrast | High | ```* Another item to consider is color contrast. You can learn more about this and validate the combination of colors, such as button background & text color choices using this tool. https://color.a11y.com/``` |
| Images w/o width & height | Medium |```*You have some image elements that don't have explicit width and height specified. Adding these to your HTML will help to reduce layout shifts and improve CLS. https://web.dev/optimize-cls/?utm_source=lighthouse&utm_medium=devtools#images-without-dimensions``` |
| Cache policy | Medium | ```* You should consider adding a cache policy for static assets to speed up page loads for return visitors to your site. https://developer.chrome.com/docs/lighthouse/performance/uses-long-cache-ttl/?utm_source=lighthouse&utm_medium=devtools#how-to-cache-static-resources-using-http-caching``` |
---

[Back to TOC](#evaluation-conditions--feedback)


### Career

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Consider adding professional & social links | Low | ```* Consider adding your social & professional links, like GitHub, Twitter, & LinkedIn, to your webpage. This is especially important if you’ll be sharing this app with potential employers. You want to make it easy for them to learn more about you.``` |

---

[Back to TOC](#evaluation-conditions--feedback)

### Product Owners

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Good Kanban board | High | ```* You have done a good job creating a Kanban backlog a team could use to visually see what tasks are needed to complete a project and their status. Having a shared, single source of "truth" is very important for any project.``` |
| Kanban board needs improvement | High | ```* You have done a good job outlining the tasks, but organizing them visually in a Kanban-style board would help make it easier for a team to see the tasks and their relationship to one another and status. Tools that can make this easy to do include Trello, GitHub Projects, and Jira. Here's an article that describes the process in more detail. https://www.atlassian.com/agile/kanban/boards``` |
| Good epics/stories/tasks | High | ```* You've also done a good job creating User Stories for each of the requirements. These are also important because the provide Developers with the definition of what users need rather than how to do it. All too often Developers concentrate more on technology that the fact that an app must solve a user problem.``` |
| Epic/stories/tasks need improvement | High | ```* You'll want to organize the work that needs to be complete in Epics,  User Stories, or tasks for each of the requirements. These are also important because the provide Developers with the definition of what users need rather than how to do it. All too often Developers concentrate more on technology that the fact that an app must solve a user problem.``` |
| Good task checklist | Low | ```* The checklist you've included in each work item is especially useful. It's a great way to ensure that members of the team are following the standard processes to ensure that what they produce meets the teams quality standards.``` |
| Good Task titles | Medium | ```* I liked the fact that you created a short title for each story/task to summarize it, while including the details itself in the body of the task. This helps to make the board easier to read when you have a lot of tasks in a project.``` |
| Task titles need improvement | Medium | ```* The title for each story/task summarize the work item, not include all of the details. You should include details, like the user story itself in the body of the task rather than in its title. This helps to make the board easier to read when you have a lot of tasks in a project.``` |
| Good acceptance/test criteria | High | ```* You have done a good job defining what the Acceptance Criteria and Test Criteria are for the work to be performed. You wouldn't believe how often teams waste time trying to decide whether or not they are done. This also helps Developers create accurate tests to validate the functionality they've created.``` |
| No acceptance/test criteria | High | ```* Consider adding Acceptance Criteria and or Test Criteria with your tasks. You wouldn't believe how often teams waste time trying to decide whether or not they are done. This also helps Developers create accurate tests to validate the functionality they've created.``` |
| Good dependency mapping | High | ```* You have done a good job adding parent/child dependencies between your epics/stories/tasks. In many ways project ownership is about managing the dependencies between tasks more than the tasks themselves. This is because for development to be efficient it's important to not just complete a task, but to complete it in the right order so Developers aren't waiting on one another.``` |
| No dependencies | High | ```* Something else to consider adding to your tasks are the parent/child dependencies between them. In many ways project ownership is about managing the dependencies between tasks more than the tasks themselves. This is because for development to be efficient it's important to not just complete a task, but to complete it in the right order so Developers aren't waiting on one another.``` |
| No prioritization | Low | ```* Something that's helpful in scheduling work is to understand the priority of each task. This can be as simple as flagging individual work items with a priority of 'Must Have', 'Should Have', or 'Nice to Have'. During Sprint Planning understanding the priority of a work item, along with its dependencies, will help you and the team identify the order in which work items need to be completed.``` |
| Good prioritization | Low | ```* You have done a good job of assigning a priority to each work item. During Sprint Planning understanding the priority of a work item, along with its dependencies, will help you and the team identify the order in which work items need to be completed.```

---

[Back to TOC](#evaluation-conditions--feedback)

### Data Scientists

| Condition | Importance | Feedback |
|-----------|------------|----------|
| Jupyter notebook needs methodoloy & analysis | High | ```* Your Jupyter notebook could be greatly improved by adding an explanation of your methodology and an analysis of the results. The raw results of data science projects aren't always obvious and the interpretation by the author is an important part of the results.``` |

---

[Back to TOC](#evaluation-conditions--feedback)

## Example Feedback 

Evaluators use the evaluation conditions & feedback above to build messages with
their feedback, which is DM'ed to the Solo Project creator in Discord. The
following examples show messages that were sent to a creator whose projects 
passed the evaluation and to a creator whose Solo Project required a 
modification.

### Passed

Hi @<Discord-name>. Congratulations on your hard work and dedication. Your Voyage 45 Solo Project has been accepted and you are advancing to the Voyage Phase starting on August 7th. Watch the <#1026584387569078373> channel for more information. 

**_If you haven't yet signed up for Voyage 45 complete this form so you don't miss out_** —> https://forms.gle/DajSfXQCX4qbMAu8A

I’m looking forward to seeing what you and your team will be creating in your Voyage! 

https://c.tenor.com/bDxOr4tSm7kAAAAC/spongebob-high-five.gif

Here is some more specific feedback that I hope will be helpful:

* This Solo Project is a Tier 1, rather than a Tier 2 app, so you are eligible to join the next Voyage as a Tier 1 participant. You can learn more about our tiers and the requirements of each here —> https://chingucohorts.notion.site/Solo-Projects-2a41ff900cc24a72a919f0eb5e79c42b

* Your repo contains a readme that could be even better with a few changes.  This is an important part of any project and here’s additional info to show how to structure a well-written readme.  https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d. 

* Your commits aren’t atomic, but your commit messages are descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.

* I suggest you move the source code files in the `docs` directory into the root of your repo in future projects. This directory currently adds an extra, unnecessary directory level to the project and moving it will make understanding the app easier. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2

* Your code is readable & maintainable. This is very important since you'll spend more time maintaining an app than writing it. I guarantee that in just a few weeks you'll forget the details you know today. Anything you can do to improve readability & maintainability is a gift to your ""future self"". 

* There is some commented-out code in your source files (such as in `docs/app.js`).  Even though this doesn’t affect the operation of the app it can make troubleshooting and debugging more difficult.

* Good use of vanilla JS to manipulate the DOM. This is an important skill to master and one that will help when you start to learn FE frameworks like React, VueJS, SvelteJS, etc.

* Your HTML is good, but could be even better by using semantic tags. This is a good best practice to follow since it provides meaning to the elements on the page, which is better than any code comments. https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html

* UI/UX is clear, concise, & engaging. Here’s a set of principles I hope you will find helpful for future projects. https://www.justinmind.com/ui-design/principles

* Your app is responsive. This is important given the fact that many users rely on mobile devices. Here’s some information that may help you understand this for your future apps  https://developers.google.com/web/fundamentals/design-and-ux/responsive/.

* In the browsers console log an error message indicates you have a missing favicon. To correct this you can either add a favicon ( http://www.faviconcodegenerator.com/ ) or suppress the error message ( http://www.faviconcodegenerator.com/prevent-favicon-404-error.php ).

* Consider adding your social & professional links, like GitHub, Twitter, & LinkedIn, to your webpage. This is especially important if you’ll be sharing this app with potential employers. You want to make it easy for them to learn more about you.										

---

[Back to TOC](#table-of-contents)

### Changes Required

Hi @<Discord-name>. Your app shows that you’ve invested a considerable amount of thought and effort in its design & implementation. 

Please make the following change and then DM me here when you are ready for me to look at it again. **_This is the only change you are required to make._**

**Requested changes**
1. You haven’t included a usable readme in your repo. This is a critical part of any project and here’s additional info to show how to structure a well-written readme.  https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d. 


**Here’s additional feedback that I hope will be helpful.**

* Your commits are atomic and your commit messages are descriptive. Here’s a guide I think you’ll find interesting & useful for future projects. https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/.

* I suggest you look at adding source code files to a `src` directory in the root of your repo in future projects. This has little benefit on a project of this size, but for more projects with many source files, the organization it adds will make understanding the app easier. Here’s some additional info that may be interesting https://dev.to/alexsergey/project-structure-repository-and-folders-review-of-approaches-4kh2

* Your code is readable & maintainable. This is very important since you'll spend more time maintaining an app than writing it. I guarantee that in just a few weeks you'll forget the details you know today. Anything you can do to improve readability & maintainability is a gift to your ""future self"". 

* In `index.html`  you might want to move the `<script>` tag to the end of the `<body>` section or to use the `defer` attribute on the `<script>` tag to prevent blocking during initial page load. You can learn more about this option here https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script#attr-async

* Your HTML is good, but could be even better by using semantic tags. This is a good best practice to follow since it provides meaning to the elements on the page, which is better than any code comments. https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html

* Good use of vanilla JS to manipulate the DOM. This is an important skill to master and one that will help when you start to learn FE frameworks like React, VueJS, SvelteJS, etc.

* UI/UX is clear, concise, & engaging. Here’s a set of principles I hope you will find helpful for future projects. https://www.justinmind.com/ui-design/principles

* Your app isn’t responsive. This is important given the fact that many users rely on mobile devices. Here’s some information that may help you understand this for your future apps  https://developers.google.com/web/fundamentals/design-and-ux/responsive/.

* In the browsers console log an error message indicates you have a missing favicon. To correct this you can either add a favicon ( http://www.faviconcodegenerator.com/ ) or suppress the error message ( http://www.faviconcodegenerator.com/prevent-favicon-404-error.php ).

* There are some application features & functions that are not working (eg. project links). Make sure you address this before sharing this in an interview since you want applications you share with potential employers to be fully functional and free of defects.

* Consider adding your social & professional links, like GitHub, Twitter, & LinkedIn, to your webpage. This is especially important if you’ll be sharing this app with potential employers. You want to make it easy for them to learn more about you.										

---

[Back to TOC](#table-of-contents)
