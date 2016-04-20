# Remote Full Web Development Portfolio Project

## Introduction and Objectives

The last stage of the Flatiron School is called 'project mode.' You'll be building real applications. The goal of this period is to expose you to actual problems that arise when building and teach you how to manage a big project. The goal of the projects is not to launch a massively popular social network or startup, but rather, just to learn.

>Education is an admirable thing, but it is well to remember from time to time that nothing that is worth knowing can be taught.
>
> — Oscar Wilde

While we love teaching you all the things about programming, in the end, we're trying to build things, and that isn't something we believe can be taught, but rather, must be learned by trying and failing and exploring.

So make sure you are keeping your eye on learning, a constant balance between building and shipping and learning.

**TL;DR**

* Expose you to actual problems
* Learn to manage software projects
* Goal is to learn, not build a company
* Learn through building things

## Your Team

Your team will be chosen for you. Once you complete the Skills Assessment, expect an email from us with your fellow teammates. Depending on the number of students in the same stage of the course as you, this may be one other person, or up to 4 others!

Once you get your team assignment, say Hi! You'll be spending a lot of virtual time with these folks. Become friends.

## Picking a Project

The first step is to pick your project. This is going to be much harder than you think. Remember this is a *portfolio project*. That means you'll want to create something that your group is excited about! Meet with your team and discuss **three** ideas that seem interesting to you all. The projects should be complicated enough to require at least 40 to 80 hours of work from everyone. Try and make sure there are elements of everything you've learned in the project. Roughly that means there should be some element of:

 * Complex Active Record. Think searching, sorting, and many `has_many` relationships.
 * Complex Views and Routes. There should be an opportunity to show off nested routes and resources. Also you'll want to make sure there are non CRUD routes
 * Hitting External APIs. This usually makes things more fun, but it's also an important skill to have!
 * Dynamic Front End. Make sure your front end has AJAX elements. Either simple jQuery or Angular.

The key here, is you are no longer just building something to meet some minimum requirements. This project needs to be **a lot** better than anything you've done. Companies will be using it when making hiring decisions.

Building something usable is tremendously hard. There are a few things we've learned over the years about building.

1. Everything is harder than it sounds. You'd be surprised how quickly complexity grows. Be humble about your estimates and somewhat realistic about what you can accomplish. Remember, you can always make your app do *more* down the road. Think small.

2. Keep it simple! Seriously, embrace constraints. Make your project as small as possible while still capable of delivering the majority of the value. Maybe you don't need a User registration system that supports 10 external OAuth providers, maybe you don't need to allow them to reset their passwords (do you even have users complaining about this?), maybe exporting to PDF is enough and you don't need to support epub and kindle. Just keep it simple. 1 version of something is more than enough. Think Minimum Loveable Project.

Beginners have a tendency to choose very hard projects. Pick a project that you can imagine having a somewhat working version of *after a day*. Keep it simple and small.

![](http://curriculum-content.s3.amazonaws.com/web-development/project-mode-guidelines/how-to-buil-an-mvp.png)

### Narrowing It Down To One

From the three projects that you choose, your instructor will choose the final project your team will work on. We do this because there are so many considerations that go into choosing something to work on that as a beginner developer you may not have the tools to choose. We are trying to optimize for a few variables:

 * Doability in a reasonable amount of time
 * Interestingness
 * Difficulty level, not too large and not too small

Once we communicate the final project, you'll be off to the races!

**Check out this list of project ideas**

- [GameTable](http://gametable.co/)
- [Gitshoes](http://www.gitshoes.com/)
- [Kickammender](http://162.243.246.245/)
- [LocalList](http://localist.herokuapp.com/)
- [NBAStalk](http://162.243.240.32/)
- [OctoMaps](http://octomaps.com)
- [Pale Blue Dot](http://palebluedot.herokuapp.com/)
- [WhoWhatWhen](http://192.241.176.112/)
- [Wishgram](http://162.243.119.229/)

**TL;DR**

* Come up with three ideas
* Instructor will choose the one you do
* Plan to make it **a lot better**
* Be humble about your estimates
* Keep it simple ( Minimum Lovable Product)
* Should have a working version after a day
* External APIs make projects more interesting
* Think about answering or automating a question

## Planning and Working on Your Project

You will be operating as a small remote team. Because of that, communication and organization are absolutely key!

### GitHub Setup

All students will be using GitHub to manage their team, and the project. Get familiar with Github Issues, you'll be spending a lot of time in it.

There are few steps that are blocking any work at all. Let's get those out of the way as a team.

  1. Create the Github Repo on someone's account, add everyone else as collaborators
  2. Create a Slack channel for your group.
  3. Run `rails new` to create your new project, push that to GitHub.
  4. Everyone should install [ZenHub](https://www.zenhub.io/). This will allow a much better and easier view for your github issues.

### Initial Card Dump

Initially, let's get the easy features out of your head, and into GitHub Issues. Then we'll be able to divide and conquer them.

  1. Meet with your team. Start dumping all of the things you need to do into issues on GitHub Issues. Remember we are focusing on the minimum loveable product. Always keep asking yourself if the feature you are putting in as a card is *required* for the user.
  2. Switch over to the "board" view provided by ZenHub by clicking on the boards tab. You should be presented with a handful of boards, or pipelines. Go ahead and delete the "Backlog" board. All of your issues you just made are in the "New Issues" board. Let's move them to the "To Do".
  2. Go through all of those items and prioritize them. There may be ones that block others, bring those to the front. Focus initially on anything that involves models. You may want to do some of the initial model work right now with your entire group.

### Working and Reporting

The goal is to be communicating with your team every single day. In addition that, you'll be posting **daily** video 


  1. Let's get working!! Each person should grab a card, move it to the "In Progress" board and assign it to themselves. Now get working.
  2. **Every day** upload a screencast video of your most recent work on all of the issues that in the "In Progress" pipeline that are assigned to you. Even if all you did was fix some simple bugs or make some great research progress, upload a video!
  3. Make a slack channel for your team and invite @aviflombaum and @joe into it and you can post progress updates there and ask us questions and chat with your team.

##### Some Tips

1. Iterate! Stay fast and small. Build things in small parts. You should be able to launch a new feature every day because you build in the smallest possible unit and are constantly driving toward deploying a new piece of code. Don't pile up requirements, look for shortcuts, look for ways of having a 'good enough' version of the feature and not all the bells and whistles.
2. Don't get bogged down by complexity. Focus on the smallest unit of work, and build up from there. Don't spend time planning every detail of your project. Get an idea of what you want to build and start. You shouldn't find yourself designing a schema with a dozen tables. You also shouldn't find yourself mocking up all the pages of the app before you've written a line of code.

##### Huge gems

Don't use big gems like:
* ActiveAdmin
* RefineryCMS

**TL;DR**
* Iterate!
* Launch a new feature every day
* Make it good enough, not perfect
* Make < 5 minute video every day to demonstrate a feature you built that day

## Working with Your TAs and Classmates

  * You'll have a weekly check in with your instructor to help with prioritization and track progress.

**TL;DR**
* Work with one TA
* Don't get stuck
* Use your TA

## Demo Days and Code Review

  * We will be hosting a demo day every week. A few groups will be randomly selected to present what they are working on to all of the online Flatiron students!
  * As you near the end of your project, your project will be submitted to another group for code review. This means they will go through your code, point out possible problems and areas for improvement and submit it back to you in the form of a pull request similar to [this](https://github.com/flatiron-school/scheduler/pull/14/files). 

## Resources
* [ThoughtBot Playbook](http://thoughtbot.com/) - [ThoughtBot Playbook](http://playbook.thoughtbot.com/)
* [The Twelve Factor App](http://12factor.net/) - [The Twelve Factor App](http://12factor.net/)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/remote-project-mode-guidelines' title='Remote Web Development Project Mode Guideline'>Remote Web Development Project Mode Guideline</a> on Learn.co and start learning to code for free.</p>
