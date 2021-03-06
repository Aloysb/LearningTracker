# Web Developper logbook
## Past - What happened until now

What I haven't recorded in the past:
 - multiple attemtps to learn to code
 - source used so far:
 	- Project Odin
 	- CodeAcademy
 	- Code wars
 	- Udemy : Web Development Zero to Mastery from Andrei Neagoie at https://www.udemy.com/the-complete-web-developer-zero-to-mastery/
 	Course done from May 2018 to September 2018. Need a refresher but learned a lot.

## Why I start this log
I start this log after reading an article from Medium.
My past attempts have all 'failed', but I have learned a lot.
I still feel like I am trying to learn to swim in the middle of the ocean, and I feel the more I know, the less I know.
This log is an attempt to 'fix' what I learn, develop a clearer roadmap for learning, documenting my journey, celebrating little achievements and helping to keep my motivation up.
Also, as a 'side-effect', to help me improve my english and writing skills.

## Goal: why code?
As a plan B for body wearing work.
Always enjoyed coding, thought I might enjoy it as a work.

Location free job.
Little set up costs.
Future proof job.
Opportunity for remote work and part time, with appealing salaries.


## Why did I failed in the past?
Hard, very complex, lost.
Questionned why I was learning.
No programming buddies?
Lack of time?

# Skills tracker

Skills | Notions | Basics | Good | Very Good | Confident | Gun |
-------|---------|--------|------|-----------|-----------|-----|
Markdown |:v:|:v:|||||
HTML5 |:v:|:v:|||||
CSS |:v:|:v:|||||
Javascript |:v:|:v:|||||
Sass |:v:||||||
Node.js |:v:||||||
Project Architecture |:v:||||||
Design: colors |:v:||||||
Template |||||||

# RESSOURCES

### Design

##### Color

[Color system according to Material UI](https://material.io/design/color/#color-theme-creation)

# Logbook

## 25 February 2018
##### HTML, SASS, TERMINAL, MARKUP, API, JAVASCRIPT, NODE, GIT

* Tried to develop a mini program to feed expenses from a CSV in Splitwise. Project abandoned. Practiced JS, reading API documentation, terminal (how to print out a function).
	* Run script in the terminal using Node
	* Arrow function
	* Printing out function body using Function.toString()

* Review a couple of videos about node.JS from Udemy (Andre's course) (and express, briefly)

* Starting this documentation about my journey to become a Web dev, inspired from https://medium.freecodecamp.org/the-tools-and-resources-that-landed-me-a-front-end-developer-job-1314c6f1fa7f

* Used GIT on the current work today (init, status, add, commit).

* Started responsive project #3 (Landing page) on FCC. Attempted to use SASS (failed :))

* Topped up my motivation to become a web developper.

* Learnt a lot more about marked up language here: https://guides.github.com/features/mastering-markdown/

* Read a chapter about asynchronous programming in Eloquent Javascript. Haven't grasped all the concepts!

## 26 February 2018
##### SASS,GIT

* Set up Sass --watch for Sass on the FCC Responsive Project #3


* Build up a simple architecture for the project

* Learnt about colors trough material-UI and smashing magazine:
	* One primary color
	* One accent color
	* One background color (components)
	* One surface background (behind scrollable content)
	* Error color
	* 'ONs' color (on Primary, on Accent, etc)
	* Then you can use different shade of the primary/secondary color (hue) as required to separate section (example: App bar vs PhoneSystem bar)

	![Example Palette color](./img/Colorpaletteexample.png)

* Read Eloquent Javascript on DOM
* Switched to Atom.io => love it!
  * Installed packages, struggle with keybindings conflicts.
  * This is a test line to try Git-plus :smile:

* Did my (second?) first contribution to Github [here](https://github.com/Syknapse/Contribute-To-This-Project/pull/189), following an article I've read on Medium. :bowtie::clap::+1:

## 26 February 2018
##### GIT, Javascript

* Contributed to another repo, MoCkInGcAsE.
Great as I knew exactly what to do.
Unfortunaly my PR had some issues and as I tried to update it, the test tool (Travis CI), would not take into account my new commits. Waiting for the admin to help me out.
__*Update:*__ Woohoo! found it!

* ~~Wrote~~ Copy-Paster my first test :smiley: in that same contribution

* Asked to update the Typescript declaration file ... Read about Typescript for a little.

* Posted my first question on Stack [here](https://stackoverflow.com/questions/54902328/typescript-function-declaration-with-multiple-type)!

## 27 February 2018
##### GIT, Javascript, Typescript, stackoverflow, HTML

* Question answered on Stackoverflow, great.

* Updated my PR as per review.

* Studied the new tag in HTML 5 and how to use them:
  * `<Aside>`
  * `<Main>`
  * ``<Article>``
  * ``<Footer>``
  * ``<Header>``
  * ``<Section>``
  * ``<Nav>``

* Studied the difference between the two main programming paradigms, functional and OOP.
  ###### Functional:
    The program is run through a series of pure function.
    The state (data) of the program is held outside of the function
    A function is pure if:

    1. Does not change the state (immutability?)
    1. Does not trigger side effect
    1. The same input return the same output, everytime.

  ###### OOP:
    State and methods are contained into object (great for hiding to the outside world (encapsulation)).
    State can change (with SETs methods).
    An object is made of methods and attributes, and they are grouped together into the object.


**Example:**

  We have 5 green cars and we decide to repaint them in red.

    ```
    let carsColours = [green, green, green, green, ** green]

    repaintCar(car, newColour) => {
        car = colour;
      }

      repaintCarInRed = (car => repaintCar(car, 'red'));

      repaintFleetOfCar = (cars, colour) => {
        for (car) in cars => repaintCar(car, colour)
      };
      ```

  Okay, this is going out of control will have to work a bit more on that example => I am unsure how to represent the state in functional (two dimensional array?)
