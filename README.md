# Portfolio : Ed Fallin

Hi there, thanks for checking out my portfolio!&nbsp;  Please take a look here and click through to whatever looks interesting.

I'm always happy to talk about these projects and how they demonstrate my skills, drive, and interests.&nbsp;  I hope you like them!

> All repositories here are portfolio-facing copies.&nbsp;  Their age varies greatly, up to about eight years.



## Choose a technology

I've worked in a variety of technology mixes, but the two categories here cover the ones I've included in this portfolio.

- NodeJs / Web

  - NodeJs
    - [Risei](#risei)
  - HTML, CSS, JS
    - [JobWave](#jobwave)
  - React [(coming soon)](#react)
  - Angular [(coming soon)](#angular)

- .NET / Windows

  - [QuickBoard](#quickboard)
  - [Rewriter](#rewriter)



## Risei

**Risei** is a declarative testing framework for JavaScript that is rich in features, robust, and is itself well-tested.&nbsp;  It's a published **npm** package with an extensive read-me and its own, even more descriptive website.&nbsp;  It's one of many **NodeJs** apps and tools I have written.

Risei makes it easy to write unit tests, because for most tests, all you have to do is provide the inputs, outputs, and a description in an object.&nbsp;  It runs in the terminal.&nbsp;  I use it all the time (see [JobWave](#jobwave)).&nbsp;  Check it out!

- **Repo:**&nbsp;  [https://github.com/EdFallinOnGitHub/risei](https://github.com/EdFallinOnGitHub/risei)

- **Npm package site:**&nbsp;  [https://npmjs.com/package/risei](https://npmjs.com/package/risei)

- **Full descriptive website:**&nbsp;  [https://deusware.com/risei/](https://deusware.com/risei/)

_[Back to top](#choose-a-technology)_


> ### Screenshots
> These are examples of the easy test syntax you use with Risei...
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Syntax-example.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Syntax-example.png)
>
> ... And the clear output it gives you about test results.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Output-example.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Output-example.png)



## QuickBoard

**QuickBoard** is a Windows tool that saves reusable texts in small files, with each blurb of text copied to the clipboard with a single click, along with many powerful related features.&nbsp;  I use it every day when I'm working in Windows.

- **Repo:**&nbsp;  [https://github.com/EdFallinOnGitHub/QuickBoard](https://github.com/EdFallinOnGitHub/QuickBoard)

_[Back to top](#choose-a-technology)_


> ### Screenshots
> These are two .board files open in QuickBoard...
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/QuickBoard-files.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/QuickBoard-files.png)
>
> ... And here is one of the right-click context menus, showing the some of the wealth of options available.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/QuickBoard-context-menu.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/QuickBoard-context-menu.png)



## Rewriter

**Rewriter** is a Windows tool for rewriting the contents of a file using a series of regular expressions.&nbsp;  It's very useful for widespread changes to code or other text-based material.&nbsp;  Both the file to change and the list of regular expressions can be dragged and dropped onto the UI.

- **Repo:**&nbsp; [https://github.com/EdFallinOnGitHub/Rewriter](https://github.com/EdFallinOnGitHub/Rewriter)

_[Back to top](#choose-a-technology)_


> ### Screenshot
> Here is the UI of Rewriter with a file to change and the regular expressions list already dropped on and ready to use.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Rewriter-user-interface.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/Rewriter-user-interface.png)



## JobWave

**JobWave** is a tool website that I use to track jobs I have looked at online.&nbsp;  It is one of many personal apps and tools I have written with native web technologies (HTML, CSS, and JavaScript).

With JobWave, I can transform job listings from other sites, search, sort, and cache them, and copy them to the clipboard with one click.&nbsp;  JobWave only keeps things in the browser's local storage.

> To make use of this tool on short notice, I first wrote JobWave in a procedural style in one JS file, as seen here.&nbsp;  Now I'm refactoring it and putting it under test using my own test framework, [Risei](#risei).&nbsp;  Only the beginnings of that overhaul are seen here.

> I serve this page for myself from a Linux VM that I maintain in the cloud, using an **nginx** reverse proxy and a custom domain I set up with a DNS registrar.&nbsp;  It is one of several sites I host for myself this way, including the extended read-me site for Risei.

_[Back to top](#choose-a-technology)_

- **Repo:**&nbsp;  [https://github.com/EdFallinOnGitHub/JobWave](https://github.com/EdFallinOnGitHub/JobWave)

- **Hosted site:**&nbsp;  [https://deusware.com/jobwave/](https://deusware.com/jobwave/)

> ### Screenshots
> Here is the UI of Rewriter with a job listing transformed at the top (using the middle right-arrow button).&nbsp;  I can't claim the styling is gorgeous, but it's clear and distinguishes things clearly.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-ui-with-example.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-ui-with-example.png)
>
> And here an example of the flashes seen when any right-side button is clicked.&nbsp;  The flash fades in about a quarter-second.&nbsp;  Colors vary.&nbsp;  In this case, I clicked the down arrow in _Rearranger_.&nbsp;  I can claim this _is_ gorgeous.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-flash.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-flash.png)
>
> And here is the result when the job listing at the top has been found among the cached listings (seen after a flash).&nbsp;  I want all listings to be unique, so the result and flash are gold / yellow to indicate it's undesirable.&nbsp;  Again, this _is_ gorgeous.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-found.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-found.png)
>
> And if I decide to make the browser window narrower, JobWave continues to be usable and look as good, because I made it using responsive design.
>
> ![https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-responsive-design.png](https://github.com/EdFallinOnGitHub/Portfolio/blob/main/images/JobWave-responsive-design.png)



## React

### ___Coming soon!___

I worked for a while with React, and created some pretty nice components and features that used them, but they were proprietary code.&nbsp;  As a result, I don't have a repo of them, or even screenshots.&nbsp;  Personal projects demonstrating my React skills will appear here later.

_[Back to top](#choose-a-technology)_



## Angular

### ___Coming soon!___

I worked for a little while with Angular, as well as making some personal projects with it.&nbsp;  All of it looked and worked great.&nbsp;  However, those projects were not finished enough to link.&nbsp;  Personal projects demonstrating my Angular skills will appear here later.

_[Back to top](#choose-a-technology)_




&nbsp;

_&lt; end &gt;_

&nbsp;
