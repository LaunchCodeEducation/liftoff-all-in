---
title: 'Class 2'
currentMenu: classes
---

## Sections

- [Project Module: Project Process and Tools](#project-module-project-process)
- [Career Module: Live Coding One](#career-module-live-coding-one)

## Career Module: Live Coding One

Today's career module in class activity has two parts.

1. Your group will walk through a live coding problem together under the supervision of your mentor. You will need to go through all the steps, and find a solution to the problem. This is a chance for you to ask questions, and learn from your fellow classmates.

2. You will be paried with someone in a different group that worked on a different problem. In your pair you will take turns practicing a live coding session. One of you will act as the interviewer, and one of you will attempt to solve the problem as the interviewee. After working through the problem you will switch roles.

## Project Module: Project Process and Tools

We will continue with planning work for the [attendance app](../1/) introduced in class 1.

The instructor will present some user stories, and you will use these to generate some wireframes within your groups.

### Writing User Stories

Your first batch of user stories can be challenging. This is not uncommon and all it takes is practice and perseverance.

Follow these simple steps to writing a user stories and you'll be writing them like a pro in no time:

**As a [role], I can [feature] so that [reason]**<br>
  Following this simple pattern makes writing user stories easy and manageable.

  For Example:<br>

        As a account owner, I can check my balance online so that I can keep a daily balance 24 hours a day.

  You have some options on how you'd like to format. If the above framework doesn't work for you, you can cut some of the extra words. Feel free to use one of these variations:

        As a [role], I want [feature] because [reason]
        As a [role], I can [feature]
        As a [role], I can [feature] so that [reason]

**Use index cards and a Sharpie**<br>
  When creating new user stories, always hand write your new stories on a single side of a index card using a Sharpie marker. I realize that a majority of shops use issue trackers like Jira; however, doing this physical activity will aid you in creating the correct size of user story.<br><br>
  _Index Cards_<br>
  The theory is simple – if you use any larger than a 3″ x 5″ index card you will write too much. Likewise, if you use anything smaller than a marker (aka ball point pen) – you will write too much.

  User stories are suppose to be short and sweet. They are suppose to aid in further communication and not to tell the entire long-winded version of the story. Sticking to these physical constraints will help.

**Make it testable with acceptance stories**<br>
Write out any of your acceptance tests using this template:

      Scenario 1: Title<br>
      Given [context]<br>
      And [some more context]…<br>
      When [event]<br>
      Then [outcome]<br>
      And [another outcome]…<br>

For example:

      Scenario 1: Account balance is negative
      Given the account’s balance is below 0
      And their is not a scheduled direct deposit that day
      When the account owner attempts to withdraw money
      Then the bank will deny it
      And send the account owner a nasty letter.

Again, keep user stories small to only allow enough scope so that all of my acceptance stories can be written using a ball point pen on the backside of the user story index card.

If your user story has more than 3-4 acceptance stories, really analyze the story and see if it makes sense to break it down even further so you can fit all its acceptance tests on the back of the card. Doing so might help you break down those larger stories into more digestible pieces.

**Connect the dots**<br>
Write out all the possible user stories you can currently think of. I guarantee that you will be missing some of the project scope; however with a little luck, you will be able to connect the dots and see the entire project picture.

[Group Project Outline](../assignments/project-outline/)

[Project Planning](../assignments/planning/)

[Project Setup](../assignments/project-setup/)
