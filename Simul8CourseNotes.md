# The Simul8 Dev Course

## Season 00 - Introduction

### Lecture 1: Course Introduction

- Live-coded course from start to finish (but not really a finish, just ongoing with additions)
- Season Based
  - 00 - Introduction: Here you will learn about the course and get setup
  - 01 - Minimum Viable Product: We sprint towards our minimum viable product
    - Minimum feature set it has to have before you can take it to market
      - Todo app example &rarr; MVP would be a website where people could add todos and delete todos
    - Way to get something out there into the market as soon as possible so that you can start iterating on it
    - Does not need to be the prettiest, have the biggest feature set, etc. &rarr; need something that does the basic functionality out in the wild
  - 02 - Refactor, Bugfix, Repeat: Post-Launch Development Cycle
    - Switch to this part of the development lifecycle vice adding new features, enhancements, etc.
    - Create a stable product before moving on to make it a better product
      - Listening to customer feedback, developer feedback &rarr; refactor for performance, UI/UX, accessibility, fixing any bugs, etc.
  - 03 - Enhance and Improve: Maitenance cycle: make it Better, Faster, Stronger
    - Iterating and adding features, fleshing out the app, mobile app, (companion) secondary app, etc.
  - Course does not really have an end
- Why does this course exist?
  - Based on author's experiences with numerous other tutorials
    - Tutorials that you see online are not realistic (they know everything beforehand because they have effectively reverse engineered their final product) &rarr; might discourage new developers
    - We will see some of the struggles
  - Part of a (remote) developer team w/ meetings, standups, etc.
- Design on paper &rarr; digital design &rarr; decide what features to implement (put in Trello) &rarr; etc. (coding, deployment, security, ...)
  - Can jump around to portions you are interested in if you want to
- Live coding w/ exercises
  - Will need feedback

### Lecture 2: Who is this course for?

- Who is this course for?
  - This is NOT a course for pure beginners
    - Should be ready to assume a Junior JavaScript Developer position
      - Some HTML, CSS, and JavaScript experience
      - If you have never coded before, then this course is probably not right for you
  - Bridge the gap between the "tutorial hell" and the first (software) developer job
  - Aims to give you a taste of what it will be like once you are a working developer by:
    - Going a bit outside the development process w/ meetings, stand-up, etc.
      - Software developers do not just sit at a desk for eight hours and write code
      - Do planning, go to meetings, etc.
      - Originally suppose to be a Slack channel, but instead we are using Microsoft Teams for this part
      - Planned meetings w/ others
        - Will try to group people by time zones
    - Getting you use to the iterative development cycle
      - Will not have a distinct start and end point like most tutorials you see online
      - This course evolves over time and will not have an end in sight
        - Look at Facebook as an example of how an app has changed over time (features added, features removed, etc.)
    - Showing you how a project evolves over time
  - When you get a job as a developer you do not always get to start on a project from the beginning
    - Thrown into an in development or existing app, which requires you to adapt
- Experimental course
  - Live-coded from start to finish
    - Long videos due to format w/ timestamps to find your way around and back
    - Like looking over Tim's shoulder watching him code and coding along w/ him
      - Being part of Tim's team
    - Will need to condense things (eight hours of work) down
      - Will only show a portion of figuring something out when he gets stuck (e.g. 20 minutes of trying to solve the problem out of something that takes much longer), but will let us know how long it took him
    - Every feature, every line of code, etc. will be recorded
      - Cut out some of the Googling, searching, etc., but not all of it
- Course is not for people:
  - Who cannot stand longer videos
  - With no JavaScript, HTML, etc. experience
  - Who are not interested in the mundane (emails, meetings, etc.) parts of being a developer
- Course is for people:
  - Actively seeking their first gig as a developer
  - People who got hired as a junior developer, found it overwhelming, and ended up leaving

### Lecture 3: How is this course different?

- How is this course different?
  - This will be a LIVE (or living) development course.
    - No filming live or streaming, but rather a recording of live coding
    - We will be:
      - Using a "Season" based approach to keep the project going
        - Like a TV show
        - Keep going until there is no longer interest in the course
        - No set time period
        - Tackle a different strategy in each season
      - We will develop our project exactly like it would be done at a small startup
        - Technical Founder or someone with an idea that hires a technical person
        - Starts with a small number of people and, as they need more skills or skillsets, they bring people in
        - Starts w/ Tim, who will be making the decisions and choosing the direction at the beginning
          - Will choose a tech stack that he is comfortable with, but will go through the process (i.e. defend) of choosing said tech stack
          - What will be a better fit
          - Probably going to be using React for the front-end
      - Since this is a live course I will be able to use feedback (from peers, students, etc.) to improve the course immediately
        - As much feedback and as quickly as possible
        - Being developed as people progress through the course, which is why feedback is so important
  - Just like a "REAL" web app, this project will never be "finished"
    - Project will continue to be worked on with seasons being added as long as their is interest
  - Will be recording screen, working through problems, etc.
    - If the problem takes a little too long to solve, then the screen-time will get condensed
    - Depends on the situation (e.g. basic versus using a new library, package, etc.)

### Lecture 4: What are we building?

- Build something that would be relatively simple in the beginning, but can be expanded upon in the future
  - No Todo app or anything that has been done a million times
  - New project (that has not been planned out) and an entirely new idea for a website (that also has not been planned out)

- What are we building?
  - We'll be working on a project called "Dev Data Jokes". It's going to be a simple project at first but we'll steadily add features and complexity.
  - Gist of the project:
    - User can create an account, login, and post Dev Dad Jokes
      - Be able to manage your Dev Dad Jokes under your user account
      - People can search for your Dev Dad Jokes, click the button to see more by you (the author), etc.
    - People can search for Dev Dad Jokes
      - Search bar that allows people to type in part of a Dev Dad Joke and perform the usual search (by people, category, etc.)
    - Admins can approve or delete submitted Dev Dad Jokes
      - Approve, delete, etc. a Dev Dad Joke
      - Prevent unrelated content (i.e. ads, etc.)
    - Probably going to be the MVP (minimum viable product)
      - Other minor features (e.g. having trusted users who do not need to have their Dev Dad Jokes approved by an admin, etc. &rarr; reputation like StackOverflow)
  - I have no idea what this website will look like. The point is that we're developing it live and it could turn out totally different than I imagine it now.
    - Cards (Material UI) and really bad responsiveness
      - Category, "Dad Dev Joke", Author and Source, as well as a button to see more by the Author
    - Throw around some ideas to start off, maybe have a Twitter poll, etc.
  - Future features (Season 03?)
    - Voting feature to allow people to vote on submitted Dev Dad Jokes (Reddit, StackOverflow, etc. type system) or a Like button
    - Video Dev Dad Jokes
    - Message board for talking, commenting, etc.
    - Following people and receiving notifications

### Lecture 5: Setup Your Development Environment

- Tim will show us what we need to download and install for the course, but will not be going through the motions himself
- A few things will be installed in the command line
  - Optional
- What you need
  - [Node.js](https://nodejs.org/en/)
    - Version should not matter (for now)
  - [Node Version Manager](https://github.com/nvm-sh/nvm)
    - Easily switch back-and-forth between different versions of node
  - [Homebrew](https://brew.sh/)
    - Package manager for macOS
    - Can use to install NVM, Git, etc.
  - [Code Editor: Visual Studio Code](https://code.visualstudio.com/)
    - If you really like using another code editor, then use that code editor
    - Extensions:
      - Bracket Pair Colorizer
        - Color codes your brackets so help you line them up
      - Cobalt2 Theme Official
      - Color Highlight
        - E.g. if you have a hex color, then it will display the color
      - ESLint
        - Static code analyzer that lets you know if you have code errors, standards you are not following, etc.
      - Material Icon Theme
        - Styles the icon (i.e. the .js, .css, etc. files)
      - All are optional except ESLint
  - [A GitHub Account](https://github.com/)
  - [iTerm2 Terminal](https://www.iterm2.com/)
    - Can be personalized (Tim may do a blog post at a later date)
    - Can always use the default terminal
      - Uses zsh vice bash now
  - [Microsoft Teams](https://teams.microsoft.com/start)
    - Used for collaboration, meetings, etc.
    - Install the desktop version (do not use the web version)
    - Sign up, sign in, etc.
  - [Trello](https://trello.com/)
    - Sign up, sign in, etc.
    - Will configure when we go to use
  - [Wes Bos ESLint Config.](https://github.com/wesbos/eslint-config-wesbos)
    - Optional
    - Sometimes works, sometimes does not (and you have to follow the instructions EXACTLY)
    - Local / Per Project Install seems to work best
    - Need to understand how to modify the settings.json file
  - Additional things to be set up down the road
    - Heroku
    - NPM packages

### Lecture 6: What is daily stand-up?

- Daily stand-up
  - What is daily stand-up?
    - Daily stand-up is a part of almost every dev team. It's a quick meeting (15 minutes or less), where you go around the room and people say three things and three things only:
      - What you worked on yesterday
      - What you're working on today
      - If you're blocked by something or someone or if you need help with something
        - E.g. blocked because waiting on a DBA (Database Administrator) who needs to approve all SQL scripts before they are run on the database
        - Maybe said person is in the room and they just missed the email, notification, etc. and that they need to take action
    - Make it quick and do not hold people up (go into more detail later)
      - 30 seconds to 1 minute per person
    - We'll be using the Microsoft Teams (Slack?) Stand-Up (#daily-standup?) for this. I expect everyone to go there daily and post the three things above. Why? Because you'll most likely have to do it when you get a job. Also, if you're stuck it is a way for you to seek help on a daily basis so you don't spin your wheels too much.
- Have a specific channel in Microsoft Teams
  - Maybe broken up by time zone
- Place where you can go (on a regular [daily] basis) and provide an update
  - Do it after you have worked on something
- Allows us to communicate and hold each other accountable

### Lecture 7: Importance of meetings!

- Two aspects of meetings:
  - Nobody likes to do them
  - They are very important
- Part of being a developer is attending meetings and there is no way around that
  - Cannot just blow them off
  - Times when you can skip a meeting because you are working on something important, there is a release, etc.
- Let's face it. Developers HATE meetings. I want to try and change that mindset with this course. You shouldn't be afraid of meetings you should only be afraid of "too many" meetings.
- Meetings are a great time to:
  - Bond with your co-workers
  - Share stuff you're proud of
    - New framework or something similar
  - Call out things you are (your) not happy with
    - Everybody gets the message
    - Less confrontational than directing an issue at one person
- We will have regular scheduled meetings that we'll try and group by time zone so people in each group can find a time that works for most people. Will the time always work for you? No, probably not but guess what? You have to attend meetings at a job so try and make it work.
  - +2 or -2 from your time zone, i.e. the meeting will occur within a couple hours of your time zone
  - No consequences sans public shaming, but they are important
    - If you do not go, then you will have little to no influence on the direction of the course
  - Half hour to an hour, which is way less than what you will see in the dev world
  - Go to as many meetings as you want, other peoples' time zone meetings, etc.
- Format
  - Talk about (i.e. discuss) stuff
    - E.g. authorization protocol to use
    - Pros and cons about what to use
  - Poll in Microsoft Teams for voting on what we discussed and what to use
    - Results will be what we use, so important to attend meetings and argue in favor of what you want to use
- Rigid but not stressful
- Might be recorded in case you are not able to attend
  - You will probably still not be able to influence as much due to a delay