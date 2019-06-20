# Kanban, Flow, and Constantly Improving
Kanban is a method for process improvement used by agile teams. Teams that use Kanban start by understanding the way that they currently build software, and make improvements to it over time. Like Scrum and XP, Kanban requires a mindset. Specifically, it requires the lean thinking mindset. We’ve already learned that Lean is the name for a mindset, with values and principles. Teams that use Kanban start by applying the Lean mindset to the way they work. This provides a solid foundation which, combined with the Kanban method, gives them the means to improve their process.

Kanban has a different focus from agile methodologies like Scrum and XP. Scrum primarily focuses on project management: the scope of the work that will be done, when that work will be delivered, and whether the outcome of that work meets the needs of the users and stakeholders. The focus of XP is software development. The XP values and practices are built around creating an environment conducive to development, and developing programmer habits that help them design and build code that’s sim‐ ple and easy to change.

Kanban is about *helping a team improve the way that they build software*. A team that uses Kanban has a clear picture of what actions they use to build software, how they interact with the rest of the company, where they run into waste caused by inefficiency and unevenness, and how to improve over time by removing the root cause of that waste. When a team improves the way that they build software, it’s traditionally called process improvement. Kanban is a good example of applying agile ideas (like the last responsible moment) to create a process improvement method that is straightforward and easy for teams to adopt.

Kanban's emphasis on flow and queuing theory can help a team put lean thinking in practice and help the team to create a culture of continuous improvement.

First follow the foundational principles:
* Start with what you do now
* Agree to pursue incremental, evolutionary change
* Initially, respect current roles, responsibilities & job titles

Then adopt the core practices:
* Visualize
* Limit WIP
* Manage Flow
* Make Process Policies Explicit
* Implement Feedback Loops
* Improve Collaboratively, Evolve Experimentally (using models/scientific method)

## The Principles of Kanban
The goal of process improvement is to find recurring problems, figure out what those problems have in common, and come up with tools to fix them.

### Find a Starting Point and Evolve Experimentally from There
Identifying what all the problems have in common starts by taking a look at how you work today, and treating it as a set of changeable, repeatable steps. Kanban teams call steps or rules that they always follow **policies**.

*Every team has a system for building software*. This system may be chaotic. It may change frequently. It may exist mainly inside the heads of the team members, who never actually discussed a larger system that they follow. Teams that follow a methodology like Scrum, the system is codified and understood by everyone. But many teams follow a system that exists mainly as 'tribal' knowledge.

This is the system that Kanban starts with. The team already has a way to run their project. Kanban just asks them to understand that system. The goal of Kanban is to make small improvements to that system. That’s what it means to pursue incremental, evolutionary change—and why Kanban has the practice **improve collaboratively, evolve experimentally**. In lean thinking, part of seeing the whole is taking measurements, and measurements are at the core of experimentation and the scientific method. A Kanban team will start with their system for building software, and take measurements to get an objec‐ tive understanding of it. Then they’ll make specific changes *as a team* and check their measurements to see if those changes have the desired effect.

### Stories Go into the System; Code Comes Out
The first step in improving a system is recognizing that it exists. This is the idea behind the Lean principle see the whole. When you see the whole, you stop thinking of the team as making a series of individual, disconnected decisions, and start to think of them as following a system. In Lean, this is called **systems thinking**.

Every system takes inputs and turns them into outputs. What does a Scrum team look like from a systems thinking perspective? You can think of Scrum as a system that takes project backlog items as its input and produces code as its output.

And Lean even gives us a tool to take unwritten rules and turn them into a system: a value stream map. When you take an MMF and draw out the value stream map that it followed on its path to becoming code, you’ve written down a description of a path through your system.

#### Kanban is not a software methodology or a project management system
One of the most common pitfalls that people run into when learning about Kanban is to attempt to treat it as a methodology for building software. It isn’t. Kanban is a method for process improvement. It helps you understand the methodology that you use and find ways to make it better.

While Kanban is not a system for project management, it has a very important relationship with the project management used by the team. Kanban is intended to improve and change the process in use on the project and that this can and will affect how the project is managed.

## Improving Your Process with Kanban
 In Kanban, the improvement is *left in the hands of the team*. The team members themselves find the problems with their workflow, suggest their own improvements, measure the results, and hold themselves accounta‐ ble to their own standards.

### Visualize the Workflow
The first step in improving a process is understanding how the team currently works, and that’s what the Kanban practice **visualize** is about. The better you accurately, objectively visualize the workflow, the better you embed the values of see the whole and decide as late as possible into your own thinking.

When a team wants to adopt Kanban, the first thing that they do is visualize the workflow by creating a kanban board. The team would then use the kanban board in a way that’s similar to how a Scrum team uses a task board. The Kanban team holds a meeting (usually daily) called 'walking the board', in which they discuss the state of each item on the board.

#### Kanban boards
A **kanban board** is a tool that teams use to visualize their workflow. A kanban board looks a lot like a Scrum task board: it typically consists of columns drawn on a whiteboard, with sticky notes stuck in each column.

There are three very important differences between a task board and a kanban board.
1. kanban boards only have stories, and do not show tasks
2. columns in kanban boards usually vary from team to team
3. kanban boards can set limits on the amount of work in a column

##### kanban boards only have stories
A typical kanban board only shows those larger **work items**, *not the individual tasks* like scrum task boards. A work item is a single, self-contained unit of work that can be tracked through the entire system. It’s typically larger than an MMF, requirement, user story, or other individual scope item. And while the task board only 'sees' the work items when they’re To Do, In Progress, or Done, the kanban board will have a bigger picture. Where do the work items come from? How does the Product Owner know what work items to put in the project backlog, and how to prioritize them? After the team completes the work item, is it tracked by a production team to make sure that it’s been deployed properly? The work item has a larger lifecycle that extends beyond the team that’s building it. The kanban board will have columns for the steps that a work item goes through before and after the Scrum team gets their hands on it.

##### columns in kanban boards differ
The columns on the kanban board may seem similar to steps in a value stream; however, many Kanban practitioners distinguish value stream maps from kanban boards. They will map the state of work items in the workflow separately from the value stream, something that they call **workflow mapping**. The difference is that value stream mapping is a Lean thinking tool to help you understand the system that you work in; workflow mapping is how the Kanban method determines the actual steps that each work item goes through.

##### Limit Work in Progress
When a team agrees to do more work than they can actually accomplish by the time they’d agreed to deliver it, bad things happen. They either leave some of the work out of the delivery, do a poor job of building the product, or work at an unsustainable pace that will cost dearly in future releases. Unevenness and overburdening become clear on the kanban board when stickies always pile up in one column. Luckily, queuing theory doesn’t just alert us to the problem; it also gives us a way to fix it. Once unevenness in the workflow has been identified, we can use it to control the amount of work that flows through the whole system by placing a strict limit on the amount of work that is allowed to pile up behind it. This is what’s behind the Kanban practice **limit work in progress**.

If you’re a developer it's easy to become fixated on getting that feature built and sent on to the tester as quickly as possible. But what if the test team is already working on more features than they can test right now? It doesn’t make sense to jump into development for this feature if it will just end up waiting around because nobody’s ready to test it. That would cause overburdening for the test team.

For this, Kanban goes back to lean thinking—specifically, the principle of options thinking. One reason that a Kanban team uses a kanban board is because it shows all of your options. If you’re that developer who just finished the design for a feature, it’s easy to think that you now have a commitment to work on the code next. But working on the code for that particular feature is an option, not a commitment. When you look at the whole kanban board, you’ll see many stickies that you can work on next. Maybe there are other stickies in earlier col‐ umns for other features that need to be designed, or ones in later columns for features with bugs that the testers found that need to be fixed. In fact, most of the time you have many options that you can choose from.

Setting a WIP limit for a step in your workflow means limiting the number of fea‐ tures that are allowed to move into that step. This helps limit the team’s options to make that decision easier in a way that will prevent overburdening and keep the fea‐ tures flowing through the workflow as efficiently as possible.

There is no hard-and-fast rule that says how large the WIP limit should be; instead, teams will take an evolutionary approach to setting WIP limits. Kanban teams typically choose a WIP limit that makes sense and that everyone can agree on, and then use measurements to adjust it experimentally

Like any tool, WIP limits and feedback loops can be abused. When a system has a feedback loop that’s too short, it ends up in a state that’s called **thrashing**. This is what happens when too much information is fed back into the system, and there isn’t enough time to respond before the next batch of information is fed back.

Visualizing the workflow with a kanban board helps the team see the feedback loops, and experiment with WIP limits to find an optimal feedback loop length that pro‐ vides frequent feedback that the team can respond to, but which allows them enough time to respond to that feedback before the next batch comes in.

## Measure and Manage Flow
As teams continue to deliver work, they identify workflow problems and adjust their WIP limits so that the feedback loops provide enough information without causing thrashing. The flow of the system is the rate at which work items move through it. When the team finds an optimal pace for delivery combined with a comfortable amount of feedback, they’ve *maximized the flow*. A Kanban team uses the **manage flow** practice by measuring the flow and taking active steps to improve it for the team.

### Use CFDs and WIP Area Charts to Measure and Manage Flow
When you look for the work that piles up and add a WIP limit to smooth it out, you’re taking steps to increase the flow. Limiting WIP changes which work items the team is currently working on, and causes them to work on the ones that will even out the flow and clear up unevenness and workflow problems before they start to form.

But how do you know that you’re actually increasing flow when you add WIP limits? Once again, we can go back to lean thinking, which tells us that we should take measurements—and an effective tool for measuring flow is a **cumulative flow diagram**.

The kanban board can show you where the unevenness, loops, and other workflow problems are today, and helps you manage your flow on a day-to-day basis by adding WIP limits. The CFD lets you look *at the way your entire process is performing over time*, so you can take steps to find and fix the root cause of any long-term problems.

Most teams that use CFDs don’t draw them incrementally on a wall; they use Excel or another spreadsheet program that supports charting. One reason—aside from ease of managing data—is that the spreadsheet can automatically add a linear trendline to the arrival rate and inventory line charts. These trendlines are very useful, because they can tell you whether or not your system is stable. If they’re flat and horizontal, the system is stable. If one of them is tilted, then that value is changing over time. You’ll need to add WIP limits to stabilize your system, and you’ll be able to tell that the system is stable once those lines flatten out.
