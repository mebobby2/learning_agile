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
