# Lean, Eliminating Waste, and Seeing the Whole
So far in this book, you’ve learned about Scrum and XP. Each of those methodologies has practices that you and your team can put in place, and values and principles that help everyone on the team reach an effective mindset. You can tell that you’re on a team doing Scrum because you’re attending a Daily Scrum, using sprints, and working with a Product Owner and Scrum Master. The same goes for XP: if you’re refactoring mercilessly, doing test-driven development, continuously integrating, and doing incremental design, your team is using XP.

Lean is different. Unlike Scrum and XP, Lean doesn’t include a set of practices. Lean is a mindset, and just like with the mindset for Scrum or XP, Lean comes with values and principles (which, in Lean terminology, are called 'thinking tools'). The mindset of lean is sometimes called lean thinking.

## Lean Thinking
Scrum values of commitment, focus, openness, respect, and courage help the team get into that mindset. We also saw that XP requires a mindset of its own, and that an XP team uses the values of simplicity, com‐ munication, feedback, respect, and courage in the same way.

So it shouldn’t be surprising that Lean comes with its own set of values:

* **Eliminate waste** - Find the work that you’re doing that doesn’t directly help to create valuable soft‐ ware and remove it from the project.
* **Amplify learning** - Use feedback from your project to improve how you build software.
* **Decide as late as possible** - Make every important decision for your project when you have the most infor‐ mation about it—at the last responsible moment.
* **Deliver as fast as possible** - Understand the cost of delay, and minimize it using pull systems and queues.
* **Empower the team** - Establish a focused and effective work environment, and build a whole team of energized people.
* **Build integrity in** - Build software that intuitively makes sense to the users, and which forms a coherent whole.
* **See the whole** - Understand the work that happens on your project—and take the right kind of measurements to make sure you’re actually seeing everything clearly, warts and all.

Each value comes with thinking tools to help you apply the values to real-world situa‐ tions for your team. Each of these thinking tools is roughly analogous to an XP principle.

## You Already Understand Many of These Values
*An organization will get what it values, and the Agile Manifesto does us a great service in shifting our perception of value from process to people, from documentation to code, from contracts to collaboration, from plans to action.*

One of Lean value should jump out at you: decide as late as possible. Both Scrum and XP heavily rely on the idea of making decisions at the last responsible moment. This Lean value is exactly the same idea. Scrum teams apply this idea to planning. So do XP teams, and they also apply it to design and coding. Lean practitioners do this too—in fact, this value even has a thinking tool called the last responsible moment, which is identical to the concept that you’ve already learned about.

There’s another value that you’ve learned about already: **amplify learning**—and you know that you’ve already learned it because its first two thinking tools are **feedback** and **iterations**. This value also has two other thinking tools: synchronization and set- based development. Synchronization is very similar to continuous integration and collective ownership in XP.

Finally, you’ve also learned about the value **empower the team**, and its thinking tools **self-determination**, **motivation**, **leadership**, and **expertise**. These ideas are almost identical to the ideas behind the XP practices of whole team and energized work— especially avoiding long days and long nights because they have a severe and negative impact on the software. You learned that Scrum teams also value this, as part of the Scrum value of **focus**. A team whose members have control over their lives will build better software.

### Commitment, Options Thinking, and Set-Based Development
Lean goes further and adds nuances to the ideas of commitment: **options thinking**, means understanding the difference between options and commitments, and making decisions about your project that give you as many options in the future as possible.; and **set-based development**, or running a project in a way that gives you more options by having the team follow several paths simultaneously to build alternatives that they can compare.

In Scrum, when the sprint starts, the items in the sprint backlog may feel like commitments to the team, because they were discussed during the sprint planning session and put on the task board. But they’re not commitments. They’re **options**. You know that they’re not commitments because the Product Owner can remove them from the sprint. And if the team discovers near the end of the sprint that it won’t be “done done” by the end of the timebox, they’ll push it to the next sprint. This is one reason that Scrum works so well: it separates true commitments (delivering valuable working software at the end of a timeboxed sprint) from options (delivering a specific feature at a specific date).

#### Incremental design, set-based development, and other ways to give your team options
XP and Scrum teams practice options thinking in how they plan their work and design their software. But is there something that teams can do to explicitly build options into their project? (XP uses incremental design: decoupled, independent components create options.)

Yes, there is. When teams practice set-based development, they spend time talking about their options, and change the way that they work in order to give themselves additional options in the future. The team will do extra work to pursue more than one option, trusting that the extra work will pay for itself by giving the team more information so that they can make a better decision later.

A very common in software projects; You often don’t know which solution is best until you build them both—or, at least, until you start building them. When developers are tackling difficult problems, they don’t really understand what’s involved in solving them until they get their hands dirty.

Set-based development will help our Scrum team cope with the fact that they don’t know which of the two solutions will work out best. Instead of choosing one path or the other, the team adds tasks to the task board to pursue both options. This may seem like it might be wasteful at first, but it can actually save the team a lot of effort in the long run. If one of those approaches truly leads to a much better solution, while the other one leads to a hacky solution with lots of technical debt, then it’s worth it for the team to pursue both options—at least long enough for developers on both paths to think through their solutions. This gives them much more information to make a better decision, and the responsible moment for making that decision is after they’ve spent time working on the problem.

Another example of set-based development that teams use regularly is **A/B testing**. In A/B testing, the team builds two or more solutions—for example, two different layouts or decision paths for a web-based user interface (an “A” layout and a “B” layout). The team will then randomly assign either the A or B option to beta testers—or, for some projects, to live users—and monitor their usage and suc‐ cess rates. Companies have found repeatedly that while it takes more time and effort to build two different complete solutions, it’s well worth it in the long run because they can take measurements and prove that one of those solutions was more success‐ ful. Not only that, but often the less successful solution still has useful lessons, like features that they can later incorporate into the final product.

## Eliminate Waste
The Lean value **eliminate waste** is about finding project activities that don’t add value and eliminating them.

Most teams don’t really think about how they build software. There’s usually a 'way we do things here' that’s shared between team members, and which new people pick up when they join the team. if you get into the habit of continu‐ ously 'refactoring' the way you run your project, you’ll end up with a more flexible and capable team.

The first step in refactoring code is looking for antipatterns. In lean thinking, antipatterns for running projects are called waste. That makes sense: waste is anything that your team does that doesn’t actively help them build better software.

Examples: If you spend a few hours a week sitting through code reviews that focus entirely on superficial errors or personal preferences but don’t affect design or catch real bugs, then that’s waste. spending hours debugging deployment problems that could be taken care of with scripts? That’s waste too. Other waste is so familiar that it’s essentially invisible—like your team is spread out across three different, disconnected parts of the floor, so it takes an extra five minutes to walk over to your teammate and have a discussion.

If something is waste from a software development perspective, that doesn’t mean that it’s not useful. It’s just not useful for building software. Maybe a senior manager needs that project plan so that she can convince shareholders to keep funding the project. Or maybe the meeting minutes are required for regulators. A statement of work may not be useful for the team, but it could be a required part of a contracting process. Those things may all still be required, but they’re not useful for the project itself. That makes them waste.

The Lean value of eliminating waste starts with **seeing waste**, the first thinking tool for this value.

### Seven Wastes of Software Development
* Partially done work - When you’re doing iteration, you only deliver work that’s “done done” because if it’s not 100% complete and working, then you haven’t delivered value to your users. Any activity that doesn’t deliver value is waste.
* Extra processes - An example: the team spends 20% of their time giving status and creating estimates that aren’t used for anything other than updating a status sheet. All that extra effort going through the process of tracking and reporting time doesn’t cre‐ ate any value.
* Extra features - When the team builds a feature that nobody has asked for instead of one that the users actually need, that’s waste.
* Task switching - The Scrum value of Focus helped us see that switching between projects, or even between unrelated tasks on the same project, adds unexpected delays and effort, because context switch‐ ing requires a lot of cognitive overhead. Now we have another word for this: waste.
* Waiting - so many things to wait for: someone needs to finish reviewing a specification, or approve access to some system that the project uses, or fix a computer problem, or obtain a software license... these are all waste.
* Motion - When the team doesn’t sit together, people literally have to stand up and walk to their team members in order to have a discussion.
* Defects - when the team needs to stay late scrambling to fix bugs that could have been prevented, that’s waste.

Even when something is waste, it’s usually useful (or, at least, it seems useful) to someone. What seeing waste does is help you understand those motives, and lets you objectively eval‐ uate whether they’re more important than getting your project done efficiently.

### Use a Value Stream Map to Help See Waste Clearly
How to build a **value stream map**: Try to find the smallest unit possible (often takes the form of a user story, requirement, or feature request)— this is an example of a **minimal marketable feature** (MMF), or the smallest “chunk” of the product that the customers are willing to prioritize. Think back through all of the steps that the unit went through from inception to delivery. Draw a box for every one of these steps, using arrows to connect the boxes. Because you’re drawing the actual path that a real feature took through your project, this will be a straight line— there are no decision points or forks in the path, because it represents the actual history of a real feature. Next, estimate how much time it took to do the work for the first step, and how much time elapsed before the next step to start. Repeat this for each of the steps, and draw lines underneath the boxes to represent the work and wait times.

The value stream map clearly shows how much wait time was involved during the process. If the team can find a way to cut down on waste and reduce the waiting time, they can sig‐ nificantly improve the delivery time for future features. That will make the customer happier

## Gain a Deeper Understanding of the Product
When your team has a lean thinking mindset, it means more than just thinking clearly about how they do their work, and seeing waste. It also means clear thinking about the software product that they’re building, and how that product delivers value to the users. When the team thinks about how that product delivers value, they’re thinking about integrity. This leads us to the next Lean value: **build integrity in**. A software team that has a lean thinking mindset always thinks about how they build integrity into their software.

There are actually two aspects to this: internal and external integrity. The software needs to have integrity from the users’ perspective (external), but it also needs to have integrity from the perspective of the developers (internal). Lean includes two think‐ ing tools to help us understand internal integrity: **refactoring** and **testing**.

A very effective way to build a system with a high degree of internal integrity is to use XP, especially test-driven development, refactoring, and incremental design.

Lean has two thinking tools to help you get your brain around integrity. The first tool is **perceived integrity**, or how well the product meets the needs of the person using it—and how well the person immediately sees that his or her needs are met.

If software is buggy and crashes a lot, it clearly has a perceived integrity problem. But once you get past the software simply working, perceived integrity can be more subtle. Example: A website’s clicking, selecting, copying, and pasting behavior is inconsistent and frustrating. It may have had a real purpose: news organizations often want to prevent people from copying their intellectual property and pasting it into emails, and would prefer that users use the “Email this article” feature to share the articles. However, this didn’t change the fact that the website did not work the way that the users expected it to. This is an example of poor perceived integrity.

The second thinking tool to help you understand integrity is conceptual integrity, or how well the features of the software work together to form a single, unified product. Example: Teams building video games ran into a lot of trouble with conceptual integrity as the video game industry grew over the first few years of the twenty-first century. There were many games that got poor reviews because they were seen as too easy by hard‐ core gamers, or too difficult by casual gamers. Those teams learned to include fea‐ tures in their games that improved conceptual integrity for both of these audiences. For example, most games aimed at both markets now have a difficulty setting. If your character keeps dying, a game will prompt you to lower the difficulty. A hardcore gamer would never choose this option—and a game with good conceptual integrity won’t continue to ask him if he wants an easier game, because simply asking that question is incongruous with a difficult game. It is now very common for software teams to decide at the beginning of the project whether they’re building for casual gamers, hardcore gamers, or both. They’ll include testing tasks that target the intended audience, and work with their marketing departments to make sure that the games are marketed to the right audience. These are examples of how a team can change the way work is done in order to increase conceptual integrity.

## See the Whole
How your team and your company are structured can have a big impact on how you do your work.

Examples:
* you may need to get half a dozen specifica‐ tion approvals from managers before you can start working on a new feature of your software.
* your boss could fall in love with an overly complex workflow in a ticketing system, and now you need to push every ticket through eight phases before you can start working on it.

We saw earlier how these things are waste, but we also saw that sometimes they serve a purpose that may not benefit your project, but are needed by the project or the company. How do we know which activities are genuinely useful?

Simple, **see the whole**. To really understand whether your team is working efficiently and effectively, you need to take a step back and understand the whole system, because you need to see the whole objectively.

Everyone on the project has a different perspective, and taking objective measurements helps get everyone to see the project on the same terms. This is why Lean teams take **measurements**—another Lean thinking tool.

Example of a measurement: Many teams will measure **lead time** for each feature. This is a measurement of the average time elapsed between when a feature is requested and when it’s delivered. If the team releases software every month, they’ll probably guess the lead time is between one and two months. But the actual lead time is time the user requested the feature to the time the feature makes it to production. The lead time is hence an objective measurement, and not subjective to individual's perspectives.

### Find the Root Cause of Problems That You Discover
Taking measurements and seeing the objective truth about your project and your team is only the first part of seeing the whole. The second part is understanding the **root cause**.

XP teams and Lean teams both utilize a technique called **Five Whys** to figure out the root cause of a problem.

By taking measurements and looking for the root cause, they were able to *see the whole*.

## Deliver As Fast As Possible
**Deliver as fast as possible** means getting rid of any wasteful activities that delay your work and cause bottlenecks.

Scrum and XP gave us insight into how to realistically achieve the optimal pace for delivery with iterations and flow. Lean takes this idea further by giving us three think‐ ing tools to help teams deliver as fast as possible: pull systems, queuing theory, and the cost of delay.

The purpose of **queuing theory** is to make sure that people are not overloaded with work, so that they have time to do things the right way. A queue is a list of tasks, fea‐ tures, or to-do items for a team or for an individual developer. Lean tells us that making a team’s queue of work public, and making it central to the decision- making process, helps teams to deliver more quickly.

### Use an Area Chart to Visualize Work in Progress
An effective way to measure how your team delivers valuable products is to use a **work-in-progress (WIP) area chart**. This is a simple diagram that shows how the minimal marketable features are flowing through your value stream. The WIP area chart helps you see how the work flows through the value stream, and makes it easier to spot delays and other potential waste—like stories that took a very long time to deploy to production.

### Control Bottlenecks by Limiting Work in Progress
An important idea that uses queuing theory is called the *theory of constraints*. One of the ideas behind the theory of constraints is that a particular constraint (like work piling up behind an overburdened team) limits the total amount of work that can get through the system. When the constraint is resolved, another constraint becomes the critical one. The theory of constraints tells us: *every overloaded workflow has at least one constraint*.

When a constraint causes work to pile up at a specific point in a workflow, people will often call it a bottleneck. Removing one bottleneck from the system—maybe by changing the process or adding people—will cause work to flow more smoothly. The theory of constraints tells us that there will still be another critical constraint or bot‐ tleneck somewhere else in the system. However, we can reduce the total amount of waste by systematically tracking down the critical constraint and eliminating it.

### Pull Systems Help Teams Eliminate Constraints
A **pull system** is a way of running a project or a process that uses queues or buffers to eliminate constraints. Pull systems are very useful for building software.

Example: The first step in creating a pull system is to break the work down into small, pullable chunks. So instead of building a large spec, the team can break it into minimal marketable features—say, individual stories, and maybe a small amount of documen‐ tation to go with each story. Those stories would then be approved individually. Typically, when a spec review process is held up for a long time, it’s because people have problems with some of the features. (Can you see how breaking the work down into smaller MMFs gives the team more options? That’s options thinking.) Approving individual MMFs should allow at least a few features to get approved quickly. As soon as the first MMF has been approved, the team can start working on it.

Kanban is an example of a pull system. Developers 'pull' in stories to be worked on based on actual demand, which still consists of the needs/desires of the business, but is now based on the actual capacity of team (i.e. when a developer finishes a story, he/she will pull in the next story accordingly).

This is how all the parts of lean thinking—seeing the whole, identifying the waste, and setting up a pull system of eliminate the unevenness and overburdening—can come together to help a team improve the way they do work.
