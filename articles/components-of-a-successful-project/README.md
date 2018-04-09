---
title: 'Components of a Successful Project'
currentMenu: 'articles'
---

### The Many Faces of Development

#### User Stories

Your first batch of user stories can be challenging. This is not uncommon and all it takes is practice and perseverance.

Follow these simple steps to writing a user stories and you'll be writing them like a pro in no time:

##### As a [role], I can [feature] so that [reason]

Following this simple pattern makes writing user stories easy and manageable.

For Example:

As a account owner, I can check my balance online so that I can keep a daily balance 24 hours a day. |

You have some options on how you'd like to format. If the above framework doesn't work for you, you can cut some of the extra words. Feel free to use one of these variations:

*As a [role], I want [feature] because [reason]
As a [role], I can [feature]
As a [role], I can [feature] so that [reason]*

##### Use index cards and a Sharpie

When creating new user stories, always hand write your new stories on a single side of a index card using a Sharpie marker. I realize that a majority of shops use issue trackers like Jira; however, doing this physical activity will aid you in creating the correct size of user story.<br><br>
_Index Cards_<br>
The theory is simple – if you use any larger than a 3″ x 5″ index card you will write too much. Likewise, if you use anything smaller than a marker (aka ball point pen) – you will write too much.

User stories are suppose to be short and sweet. They are suppose to aid in further communication and not to tell the entire long-winded version of the story. Sticking to these physical constraints will help.

##### Make it testable with acceptance stories

Write out any of your acceptance tests using this template:

*Scenario 1: Title<br>
Given [context]<br>
And [some more context]…<br>
When [event]<br>
Then [outcome]<br>
And [another outcome]…<br>*

For example:

*Scenario 1: Account balance is negative
Given the account’s balance is below 0
And their is not a scheduled direct deposit that day
When the account owner attempts to withdraw money
Then the bank will deny it
And send the account owner a nasty letter.*

Again, keep user stories small to only allow enough scope so that all of my acceptance stories can be written using a ball point pen on the backside of the user story index card.

If your user story has more than 3-4 acceptance stories, really analyze the story and see if it makes sense to break it down even further so you can fit all its acceptance tests on the back of the card. Doing so might help you break down those larger stories into more digestible pieces.

##### Connect the dots

Write out all the possible user stories you can currently think of. I guarantee that you will be missing some of the project scope; however with a little luck, you will be able to connect the dots and see the entire project picture.

#### Wireframes
The visual representation of your user interface.

It communicates four things:
1. **Structure**<br>
Navigation and information architecture
2. **Layout**<br>
Including page heirarchy and placement of elements
3. **Content**<br>
How the content will be placed within the design
4. **Functionality**<br>
How it works, and how it interacts

#### Agile Manifesto
We are uncovering better ways of developing
software by doing it and helping others do it.
Through this work we have come to value:
* **Individuals and interactions** over processes and tools
* **Working software** over comprehensive documentation
* **Customer collaboration** over contract negotiation
* **Responding to change** over following a plan

That is, while there is value in the items on
the right, we value the items on the left more.

#### Source Control
Using source control provides the following main benefits:
* Backs up your work in case you lose your local copy.
* Provides code history, making reversion and tracking root causes of problems significantly easier.
* Branching & Merging, which allows you to work on problems or features without fear of publishing incomplete code.

In addition, employers will expect you to be familiar with working with version control. From now on, if you aren't already, use version control, such as Git, for all of your personal and group projects and commit often!

### Planning

#### Why we plan our projects
- Know what we need to get done
- Know when we need to get it done by
- Know how it can all go wrong
- Know how to get it done despite

#### Making a timeline
- When to stop adding features, and preventing feature creep
- When to finish those features, and making a complete product
- When it needs to be stable, and leaving enough time
- Giving yourself room to breath when the unexpected happens

#### Tracking progress and information
- Keeping track of bugs
- Keeping track of tasks and deadlines
- Documenting features and notes (use the README files in Github)


[Back to Resources](resources/)
