<img width="1468" alt="CleanShot 2022-11-22 at 01 00 56@2x" src="https://user-images.githubusercontent.com/318295/203246731-67de825c-df6d-44cc-a296-f76b04aa5b12.png">

![Haxor DX Bounty Logo](https://user-images.githubusercontent.com/318295/203244248-56430fc0-a709-4f58-93b4-5f8062a623af.png)

# Haxor DX Bounty

Haxor is a community effort to help devtools maintainers remove friction from their developer experience (DX). Haxor is like a bug bounty but differs in a couple of ways:

1. Participants submit feedback in addition to bugs. Feedback can be anything that causes you friction when completing the goal, like confusing documentation or time-wasting errors.
2. Participants attach screen recording clips to issues.

## Welcome <a id="welcome"></a>

Hello and welcome to the Haxor DX Bounty! Here you get to try new dev tools, help make them better, and **earn prizes**! Every bug we find helps the next developer save time! The feedback you provide helps maintainers improve their DX.

## Sponsors <a id="sponsors"></a>

<p float="left">
<a href="https://replayable.io"><img height="30" src="https://user-images.githubusercontent.com/318295/203247573-b4f2e617-bb6c-49fd-b6e1-68141d3828ba.png"></a>
&nbsp;&nbsp;
<a href="https://pubnub.com"><img height="30" src="https://user-images.githubusercontent.com/318295/203247474-984f7cf2-ca49-48fe-a074-e7dc786bb24c.png"></a>
&nbsp;&nbsp;
<a href="https://mlh.io"><img height="30" alt="CleanShot 2022-11-22 at 01 10 01@2x" src="https://user-images.githubusercontent.com/318295/203248304-34a30601-b811-4f8c-9744-6690d9073794.png"></a>
</p>

## How It Works

Try to complete the [challenges](#challenges) below. As you complete a challenge, you can file any feedback or bugs you find as issues in the challenge repo. Once you complete the challenge, you can make a pull request adding yourself to the leaderboard! Check out this [example of quality feedback](https://github.com/haxordx/haxor-challenge-pubnub-js-getting-started/issues/1).

In order to earn points for an issue or pull, you'll need to attach a desktop replay clip using [Replayable](https://replayable.io?betacode=1337HAXOR). Replays help maintainers understand the context of your feedback and they help our moderators validate you submissions.

## Table of Contents <a id="toc"></a>

- [Quickstart](#guide)
- [Community](#community)
- [Challenges](#challenges)
- [Earning Points](#rules)
  - [Reporting Friction (10 points)](#rules-feedback)
  - [Completing a Challenge (5 points)](#rules-solution)
- [Prizes](#prizes)
- [Discord](#community)

# Quickstart <a id="guide"></a>

This guide will use the [example challenge](https://github.com/haxordx/haxor-challenge-example), but you should [choose one from the list of challenges below.](#challenges).

#### 1. Fork the Repository

[Fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) and [clone it](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

```sh
git clone https://github.com/your-name/haxor-challenge-example
cd haxor-challenge-example
mkdir solutions/your-name
cd solutions/your-name
```

#### 2. Complete the Challenge

Follow the challenge instructions. Every challenge will be unique. See some example instructions [here](https://github.com/haxordx/haxor-challenge-example/blob/main/README.md#instructions).

#### 3. Report Bugs and Friction

This is the whole point of Haxor! When you encounter friction, confusion, or bugs, **open GitHub issues on the base repository**. Every issue is worth 10 points and you can get rewarded up to 3x per challenge!

```sh
gh issue create -l "feedback" -w -b "`replayable --md`"
```

#### 4. Add Your Solution

When you've completed the challenge, make a pull request to add your solution to the base repository. Successful solutions are worth 5 points.

```sh
gh pr create -w -t "I Completed the Haxor Challenge" -b "`replayable --md`"
```

## Community <a id="community"></a>

[Join our Discord community](https://discord.com/invite/cWDFW8DzPm) to meet other Haxors and get help solving challenges!

<a href="https://discord.com/invite/cWDFW8DzPm"><img src="https://user-images.githubusercontent.com/318295/203452258-7df58408-3247-4df8-9307-d71e4e95ad1f.png" height="40"></a>

Type `!signup [your github username]` in the `#bot` channel to get the `Haxor` role and personalized notificiations in our Discord.

## Challenges <a id="challenges"></a>

### Javascript

- [Create a realtime chat application with PubNub](https://github.com/haxordx/haxor-challenge-pubnub-js-getting-started)

# Prizes <a id="prizes"></a>

**You can earn up to 35 points per challenge.** You'll get 10 points for submitting feedback and 5 bonus points for completing the challenge. Redeem points for items the Haxor shop and other special prizes!

## Haxor Swag

Represent your 1337 skills with Haxor branded merch.

<table>
  <tr>
    <td> 
      <a href="https://shop.haxor.sh/collections/haxor/products/laptop-sticker">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/kiss-cut-stickers-4x4-default-638fac818ba26_720x.png?v=1670360196" width="200" />
      </a>
      <h3>Cult Laptop Sticker</h3>
      <h6>35 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/haxor/products/caffeine_input_device-v0-00">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-49361b41_720x.png?v=1554331544" width="200"/>
      </a>
      <h3>caffeine_input_device</h3>
      <h6>70 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/haxor/products/blackhat">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-00948d62_720x.png?v=1553234911" width="200"/>
      </a>
      <h3>BlackHat</h3>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/haxor/products/mandatory-hoodie">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/unisex-fleece-zip-up-hoodie-black-front-638fae43cd95f_720x.png?v=1670360653" width="200"/>
      </a>
      <h3>Mandatory Hoodie</h3>
      <h6>350 Points</h6>
    </td>
  </tr>
</table>

## Haxor Shirts

Hundreds of shirts that were programatically generated! Every design has multiple varients. Each shirt features the Haxor logo on the sleeve.

<table>
  <tr>
    <td> 
      <a href="https://shop.haxor.sh/collections/freeke">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-1f99865a_720x.png?v=1554328508" width="100" />
      </a>
      <h4>Freeke Shirt</h4>
      <h5>15 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/refactory">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-5d81cbb7_720x.png?v=1554333175" width="100" />
      </a>
      <h4>Refactory Shirt</h4>
      <h5>13 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/hyperblock">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-a9ba38d1_720x.png?v=1554330417" width="100" />
      </a>
      <h4>HyperBlock Shirt</h4>
      <h5>20 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/noisestorm">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-a47a56d8_720x.png?v=1554335946" width="100" />
      </a>
      <h4>NoiseStorm Shirt</h4>
      <h5>20 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/dancingflame">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-15458b88_720x.png?v=1554283190" width="100" />
      </a>
      <h4>Dancing Flame</h4>
      <h5>25 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/entanglement">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-bbdb1e3c_720x.png?v=1554327826" width="100" />
      </a>
      <h4>Entanglement Shirt</h4>
      <h5>30 Variations</h5>
      <h6>150 Points</h6>
    </td>
    <td> 
      <a href="https://shop.haxor.sh/collections/skrill">
      <img src="https://cdn.shopify.com/s/files/1/0073/8708/6899/products/mockup-75b493df_720x.png?v=1554312743" width="100" />
      </a>
      <h4>Skrill Shirt</h4>
      <h5>60 Variations</h5>
      <h6>150 Points</h6>
    </td>
  </tr>
</table>

## Grand Prizes

There aren't enough challenges to earn this many points yet, but these are the kinds of prizes we dream of offering! Help us grow! <a href="#add-challenge">Add your own challenge</a>.

<table>
  <tr>
    <td> 
      <a href="https://www.tangocard.com/reward-catalog/">
      <img src="https://i.imgur.com/eib6hcc.png" width="200" />
      </a>
      <h3>$100 Gift Card</h3>
      <h6>800 Points</h6>
    </td>
    <td> 
      <a href="https://store.steampowered.com/steamdeck">
      <img src="https://i.imgur.com/2GLobsD.png" width="200"/>
      </a>
      <h3>Steam Deck 64 GB</h3>
      <h6>3,000 Points</h6>
    </td>
    <td> 
      <a href="https://www.bestbuy.com/site/cyberpowerpc-gamer-xtreme-gaming-desktop-intel-core-5-12600kf-16gb-memory-nvidia-geforce-rtx-3050-500gb-ssd-black/6500510.p?skuId=6500510">
      <img src="https://i.imgur.com/5EyfKjS.png" width="200"/>
      </a>
      <h3>CyberPowerPC Gaming Desktop</h3>
      <h6>7,000 Points</h6>
    </td>
    <td> 
      <a href="https://store.steampowered.com/steamdeck">
      <img src="https://i.imgur.com/XPOzWbM.png" width="200"/>
      </a>
      <h3>M2 MacBook Pro</h3>
      <h6>15,000 Points</h6>
    </td>
  </tr>
</table>

## Rules <a id="rules"></a>

Our feedback sessions are called challenges. Every challenge asks you to build a small app or add a single feature using a developer tool. Each challenge takes between 15 minutes to 2 hours and you complete them on your own machine.

<img src="https://user-images.githubusercontent.com/318295/206043366-f14c5931-fa37-4321-b0d1-6f724b20fbc5.png"/>

Mostly everything happens on GitHub (but you should also [join our Discord](https://discord.com/invite/cWDFW8DzPm)!). You can see a list of challenges below. Each challenge will include it's own time estimate and goal.

> Replayable makes it simple to add context to bugs and pull requests without ruining your flow. Instead of spending time trying to reproduce a bug in a new screencast, Replayable lets you add footage from when you encountered it the first time. It works full pull requests and demos too! Check out our CLI and Chrome Extension for GitHub and Jira.

### Scoring Points

In order to earn points for your submission, it must contain a 30-second or longer screencast demoing the bug, feedback, or feature.

#### Feedback (10 Points)<a id="rules-feedback"></a>

> 10 points per GitHub Issue, 30 points max per challenge

Giving feedback to maintainers is the whole point of Haxor. It's as easy as opening a GitHub issue against the Haxor challenge repo. You can file feedback for anything that you feel is "friction" to completing your task

- Things you expected to work that didn't
- Confusing or outdated instructions
- Spelling and syntax errors in documentation and code samples
- Website UI that doesn't work

Your experience will help maintainers improve their tools and remove friction for the next developer. And remember, developer experience uses many tools and is different for everyone.

Check out this [example of quality feedback](https://github.com/haxordx/haxor-challenge-pubnub-js-getting-started/issues/1).

##### Using the Replayable CLI

The following shell script will open a GitHub issue with a clip of the last 30 seconds of your screen.

```sh
gh issue create -w -t "My Feedback" -b "`replayable --md`"
```

#### Adding Your Solution (5 Points) <a id="rules-solution"></a>

> 5 Points and Hall of Fame!

While Haxor is all about giving feedback, we still want to award those to complete the challenge successfully!

Every challenge will include some exit criteria that marks it as "complete." Once you successfully complete the challenge, you'll get added to the "Hall of Fame" via https://contrib.rocks/.

In order to get your github profile on the scoreboard and earn points for completing the challenge, you must:

1. Open a pull request that adds your name to the leaderboard
2. Attach a replay of you **demonstrating the exit criteria** to the PR

##### Using the Replayable CLI

```sh
gh pr create -w -t "I Completed the Haxor Challenge" -b "`replayable --md`"
```

### Prizes <a id="cash-out"></a>

Haxor moderators get pinged on new submissions to the repositories and will comment on the issue or pull request to confirm your points.

Once you've earned enough points for a prize, you can cash out by simply emailing the Haxor staff with the prize you want, size (if appropriate), and your address.

Points will be deducted from your total (you can see this on in our leaderboard) and you'll get shipping notifications in your inbox.

# FAQ

## What makes quality feedback?

Note that all feedback should include a Replayable replay as well as a short description of your problem and experience.

- Identify specific areas where you struggled, such as with understanding documentation or debugging an error
- Provide concrete suggestions for improving the developer experience, such as adding more examples to the documentation or clarifying ambiguous language
- Offer suggestions for alternative approaches or tools that may be more effective
- Be respectful and constructive, rather than critical or dismissive

## What are some examples of quality feedback?

Check out this [example of quality feedback](https://github.com/haxordx/haxor-challenge-pubnub-js-getting-started/issues/1). You can find some more examples below, but remember your bugs, issues, and feedback need to include Replayable replays!

> At first, I tried installing through the gradle plugin, but it kept throwing errors, despite installing it how the documentation said to. Then I switched to a maven project which, admittedly, I am not familiar with. Even then following documentation and examples online, it was not allowing me to download and execute the example getting started code.

> Using my existing account/number/service plan didn't work through Java SDK, but does work through the button click online interface. When I released that account/number/service plan and created a fresh one, sending an SMS through the Java SDK worked.

> Setting up the virtual number is confusing. Not sure if my phone number will suffix or do I really need a virtual number. Also, its not exactly clear how to create the virtual number on the site.

> Message is always "This is a test message from your account", regardless of what message I put in when using the Java SDK. Is this a limitation of the trial account/free account? Or is it a bug? If the former, I didn't see it documented clearly anywhere.

## How does this work if solutions are public?

Haxor isn't really about completing challenges, it's about the feedback we give maintainers. Sure, you could copy feedback and solutions, but that's why we use Replayable to validate submissions.

## How do you prevent cheating?

At the end of the day this is a community effort. Points and prizes are a cool thing we can do to reward community members. We reserve the right to refuse submissions, ban participants, revoke your points, etc.

## Code of Conduct

See our code of conduct [here](https://github.com/haxordx/challenges/blob/main/code-of-conduct.md).

## What programming languages?

Currently the only languages we support are Javascript and Java.

## What's the story behind Haxor?

Haxor started when I wondered "how can we reward developers for participating in open source?" Then I realized that developer experience in itself was valuable to the maintainers of dev tools, but there wasn't a great way for developers to share their experience. So I started Haxor, an developer experience agency while building Replayable, a tool that makes sharing context instant.

For 3 years Haxors has privately been helping open-source projects and companies like AWS, Snap, and Mailchimp get feedback from developers who try their tools. Now we're excited to bring Haxor to the larger open-source community with the help of our scren recording tool, Replayable.

## How can I add my own challenge? <a id="add-challenge"></a>

Looking for feedback on yoru own API, SDK, or developer tool?

1. Fork the [haxor-challenge-example](https://github.com/haxordx/haxor-challenge-example) repo.
2. Make a new repo called `haxor-challenge-${your-tool}`
3. Replace the readme in your template with your own challenge details.
4. Make a pull request to the list above linking to your tool
5. We will approve or request changes to your challenge
6. We will supply you with a webhook to add to your repo. This tells Haxor moderators to review submissions and award points.
7. Developers will be notified of your new challenge!
8. You'll get GitHub notifications of new issues!

You will be responsible for maintaining your challenge.

### Requirements

Your challenge:

- Must be entirely self-service and publicly available
- Must not require payment details to complete
- Must target Javascript or Java developers (for now)
