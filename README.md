<img width="1468" alt="CleanShot 2022-11-22 at 01 00 56@2x" src="https://user-images.githubusercontent.com/318295/203246731-67de825c-df6d-44cc-a296-f76b04aa5b12.png">

![Haxor DX Bounty Logo](https://user-images.githubusercontent.com/318295/203244248-56430fc0-a709-4f58-93b4-5f8062a623af.png)

# Haxor DX Bounty

> Haxor is a community effort to help devtools maintainers improve their developer experience (DX).

## Welcome

Hello and welcome to the Haxor DX Bounty! 

As a member of Haxor, you get to try new developer tools, give the maintainers feedback, and **earn prizes**! Every bug we find helps the next developer save time! 

Level up and earn prizes by learning new APIs, SDKs, and developer tools. The feedback you provide helps maintainers improve their products, documentation, and resources.

Our feedback sessions are called challenges. Every challenge asks you to build a small app or add a single feature using a developer tool. Each challenge takes between 15 minutes to 2 hours and you complete them on your own machine. 

So come learn new skills, help other developers, and earn some prizes along the way!

<a href="https://discord.com/invite/cWDFW8DzPm"><img src="https://user-images.githubusercontent.com/318295/203452258-7df58408-3247-4df8-9307-d71e4e95ad1f.png" height="40"></a>

## Sponsors

<p float="left">
<a href="https://replayable.io">
<img height="30" src="https://user-images.githubusercontent.com/318295/203247573-b4f2e617-bb6c-49fd-b6e1-68141d3828ba.png">
</a>
&nbsp;&nbsp;
<a href="https://pubnub.com">
  <img height="30" src="https://user-images.githubusercontent.com/318295/203247474-984f7cf2-ca49-48fe-a074-e7dc786bb24c.png">
  </a>
&nbsp;&nbsp;
<a href="https://mlh.io">
<img height="30" alt="CleanShot 2022-11-22 at 01 10 01@2x" src="https://user-images.githubusercontent.com/318295/203248304-34a30601-b811-4f8c-9744-6690d9073794.png">
  </a>
</p>

# Prizes

<img width="1433" alt="CleanShot 2022-11-22 at 00 52 02@2x" src="https://user-images.githubusercontent.com/318295/203244995-2b96c4db-5895-496b-875a-16a252b2d806.png">

- Haxor Mug - 30 Points
- Haxor Tee-Shirt - 90 Points
- Gift Card - 300 Points
- Steam Deck - 1,000 Points

You can earn up to 50 points per challenge!

# How it works

Everything takes place right here in GitHub. You can see a list of challenges below. Each challenge will include it's own time estimate and goal. 

Try to complete the challenge objective. As you complete the challenge, you can file any feedback or bugs you find as issues in the challenge repo. Once you complete the challenge, you can make a pull request adding yourself to the leaderboard!

## Earning Points

In order to earn points for an issue or pull, you'll need to attach a screen recording. Screen recordings serve two purposes, they help maintainers understand the context of your feedback and they help our moderators validate you submissions.

You can use any tool to record and share clips. We recommend Replayable, our own screen recorder we built to be the fastest and most seamless way to share what happened on your screen. 

> Replayable makes it simple to add context to bugs and pull requests without ruining your flow. Instead of spending time trying to reproduce a bug in a new screencast, Replayable lets you add footage from when you encountered it the first time. It works full pull requests and demos too! Check out our CLI and Chrome Extension for GitHub and Jira.

In order to earn points for your submission, it must contain a 30-second or longer screencast demoing the bug, feedback, or feature.

### Feedback (10 points, 30 points max per challenge)

Giving feedback to maintainers is the whole point of Haxor. It's as easy as opening a GitHub issue against the Haxor challenge repo. You can file feedback for anything that you feel is "friction" to completing your task 
- Things you expected to work that didn't
- Confusing or outdated instructions
- Spelling and syntax errors in documentation and code samples
- Website UI that doesn't work

Your experience will help maintainers improve their tools and remove friction for the next developer. And remember, developer experience uses many tools and is different for everyone.

#### Using the Replayable CLI

The following shell script will open a GitHub issue with a clip of the last 30 seconds of your screen.

```sh
gh issue create -w -t "My Feedback" -b "`replayable --md`"
```

- 10 Points for feedback
- Max 30 points awarded for feedback per challenge

### Completing the Challenge (5 points + Hall of Fame)

While Haxor is all about giving feedback, we still want to award those to complete the challenge successfully!

Every challenge will include some exit criteria that marks it as "complete." Once you successfully complete the challenge, you'll get added to the "Hall of Fame" via https://contrib.rocks/. 

In order to get your github profile on the scoreboard and earn points for completing the challenge, you must:

1. Open a pull request that adds your name to the leaderboard
2. Attach a replay of you **demonstrating the exit criteria** to the PR

#### Using the Replayable CLI

```sh
echo 'Your Username' &>>README.md
git commit -am "Add my name to the leaderboard"
gh pr create -w -t "I Completed the Haxor Challenge" -b "`replayable --md`"
```

- 20 points for completion
- Max 20 points awarded per challenge

## Review

Haxor moderators get pinged on new submissions to the repositories and will comment on the issue or pull request to confirm your points. 

# Leaderboard

The leaderboard contains a centralized record of GitHub users who have contributed to Haxor. You'll appear on the leaderboard after your first contribution and you can see who's contributed the most over time!

New challenges will continue to be added, so keep an eye on your rank!

## Turning Points into Prizes

Once you've earned enough points for a prize, you can cash out by simply emailing the Haxor staff with the prize you want, size (if appropriate), and your address. 

Points will be deducted from your total (you can see this on in our leaderboard) and you'll get shipping notifications in your inbox.

# Getting Started

- Install Replayable, you'll need it to report feedback
- Navigate to the test repository and follow the instructions there
- Start a timer for how long the site says
- Do the stuff in "completing a challenge"

# Rules

# Challenges

## Javascript

## Java

# What does quality feedback look like?

(get examples from coda.io)

# FAQ

## What programming languages?

Currently the only languages we support are Javascript and Java.

# About

Haxor started when I wondered "how can we reward developers for participating in open source?" Then I realized that developer experience in itself was valuable to the maintainers of dev tools, but there wasn't a great way for developers to share their experience. So I started Haxor, an developer experience agency while building Replayable, a tool that makes sharing context instant.

For 3 years Haxors has privately been helping open-source projects and companies like AWS, Snap, and Mailchimp get feedback from developers who try their tools. Now we're excited to bring Haxor to the larger open-source community with the help of our scren recording tool, Replayable.

# Adding your own challenge

Want to participate in Haxor? 

- Make a new repo called haxor-challenge-[your tool]
  - ETA (15 min - 2 hours)
  - Guided Steps
- Make a pull request to the list above linking to your tool
- Developers will be notified of your new challenge!
- Survey
