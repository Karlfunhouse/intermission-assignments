# Mod 3 Pre-Work

## Instructional Pre-Work for Mod 3

### Libraries and Frameworks

* What is a JavaScript framework? [Watch this video.](https://www.youtube.com/watch?v=sXA1zpv4DhA)
  Library: Fewer rules.  Can do what you want.  Call the code whenever you like. (jQuery)
  Framework: More rules.  Have to follow more structure.  Framework calls code - which calls library. (react)

* Why would we want to use a framework? [Read this article.](https://medium.com/dailyjs/the-deepest-reason-why-modern-javascript-frameworks-exist-933b86ebc445)
  Batman says the essential fundamental deepest reason to use a framework is: Keeping the UI in sync with the state is hard!
  Vanilla or even jQuery fragments updating the state and the UI.
  
  I really like this explanation: Re-render the whole component: React. When the state of a component changes it renders a DOM in memory and compares it with the existing DOM. Actually since that would be very expensive it renders a Virtual DOM and compares it with the previous Virtual DOM snapshot. Then it calculates the changes and performs the same changes to the real DOM. This process is called reconciliation.
  
There are a bunch of JavaScript frameworks out there to use. At Turing, we choose to teach **React** - it's one of the most popular frameworks out there. Actually, a lot of developers will call React a library, which it is...but it can also be described as a framework. It's a little confusing, but the lines are blurred for React. Let's just say that React is a library with some rules and conventions to follow.

Go through these resources to get started learning some React!

* Read over Tyler McGinnis' [React Tutorial: A Comprehensive Guide to learning React.js in 2018](f)
* Go through the [React tutorial from the docs](https://reactjs.org/tutorial/tutorial.html)
* Optional: practice building an IdeaBox in React. Think of a mod 1 project, and build that in React!

### Asynchronous JavaScript

We will continue to work with asynchronous JavaScript, mainly when we use network requests to get data from servers (like using the `fetch`). We will go in depth with asynchronous JavaScript, including how to test it in mod 3.

* Watch [this video](https://www.youtube.com/watch?v=eesqK59rhGA) on details of the request/response cycle.
* Read [ajax in react](https://reactjs.org/docs/faq-ajax.html) to learn about incorporating network requests in React apps.
* Watch [this video](https://www.youtube.com/watch?v=8aGhZQkoFbQ) on the event loop.

### WorkFlow

Workflow is something you will deal with every day on the job. Let's continue strengthening our knowledge of workflow skills with these articles.

* Review [The Difference Between Forking and Cloning a Repository](https://github.community/t5/Support-Series/The-difference-between-forking-and-cloning-a-repository/ba-p/1372)
* Review [Updating a Remote's URL](https://help.github.com/en/articles/changing-a-remotes-url)

## Instructional Deliverables (Due Friday 5pm of Intermission Week)

Create a GitHub gist to answer these questions in as much detail as possible. Imagine someone is asking these questions in an interview (these are popular interview questions).

* What is a "framework?" And how does it differ from a "library?"
A framework provides a structure in which to write code.  It has a set of rules that requires format to be followed.  In a framework, the framework calls the code, and the code calls a library.  In a library there are fewer rules.  You can do what you want, when you want.  You can call the code whenever you like. (jQuery)

* Why should we consider using a framework over vanilla JS like you have been doing in mods 1 and 2?
Using a framework like React allows us to update the DOM and the Data(state) simultaneously. Instead of having to keep the two separate models updated individually, the built in logic makes our lives much easier.

* What is a "component" in React? Why is it useful to have components?
A component is a reusable piece of code that is responsible for handling one aspect of the program.  For example, we would have an App component that would be the main place where we plugged other components in, like header, main section or footer.

* What are React "props?"
Props are the properties we pass into components in order to allow them to be dynamic.  It can be individual key value pairs or an entire object.  We have to explicitly pass in props when using a functional component, but I think it is unneccessary to pass it in when using a class that extends a React Component.  

* What is React "state?"
State is current value of the data in a component.  It can be modified using setState and we have to pass in prevState in order for it to know the previous value and the newly changed value.  

* What does "data down, actions up" mean in React?
This concept still seems a little hazy for me, but as I understand it we pass down data from parent components (like props) into child components which will actually handle and modify the data, and then pass the changed state back up into the parent component.

_Note:_ As you do your research, stay away from React articles that talk exclusively about "hooks". We will not use hooks in mod 3.

**Before the due date, send a link to your gist to both of your instructors.**

### Extra
[*optional*]

Here are some podcasts and videos to listen to and watch respectively:

- [Testing with Fun Fun Function](https://www.youtube.com/playlist?list=PL0zVEGEvSaeF_zoW9o66wa_UCNE3a7BEr) (This is a playlist of 7 YouTube videos on testing)
- [Shop Talk with Tom Dale](http://shoptalkshow.com/episodes/147-tom-dale/) (This one is a bit older but still a good introduction for thinking about why client-side applications are important and what frameworks bring to the table.)
- [Wes Bos JavaScript30](https://javascript30.com) (Maybe pick 5 or 10 exercises - try to challenge yourself)
- [100 Days of CSS challenge](https://100dayscss.com/) (Do a few days of challenges to keep your CSS skills sharp)


## Professional Development Pre-Work for Mod 3

[You can find all of the instructions here!](https://github.com/turingschool/career-development-curriculum/blob/master/module_three/pre_work.md)
