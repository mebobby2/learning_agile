# XP and Embracing Change
It’s a long-accepted part of programmer culture: users never ask for what they actually want, and they make your life hard when they change their minds all the time. Developers know from experience that when you have to make changes to code that was already written, it causes bugs. The more changes developers need to make, the more brittle the codebase gets.

XP (or Extreme Programming) is an agile methodology. And just like Scrum, it’s made up of practices, values, and principles. You’ll learn how XP can help get each team member into the right mindset to build better code: instead of hating change, every person on the team learns to embrace change.

## The Primary Practices of XP
There are 13 **primary practices of XP** and many of these practices are specific to programming, and are aimed at addressing the most common problems that cause teams to build lousy code.

### Programming Practices
**Test-first programming**: also known as test-driven development (or TDD), it means that before he writes code, he builds an automated test. This creates a tight feedback loop that helps to prevent defects.

**Pair programming**: Two developers sit together at a single workstation when writing code. In most cases, one programmer types, while the other watches—and they constantly discuss what’s going on. Teams working in pairs inject far fewer bugs, because there are two sets of eyes looking to catch the bugs all the time. Pairing can also help reduce fatigue, because one programmer can take over typing when the other gets a little mentally tired. An effective pair programming team will discuss ideas and approaches, constantly brainstorm, and, as a result, be more innovative. They will also hold each other accountable for good practices.

### Integration Practices
**10-minute build**: the team creates an automated build for the entire code‐ base that runs in under 10 minutes. This build includes automatically running all of the unit tests and generating a report of which tests passed and which failed.

**continuous integration**: a practice built around tools that teams use to let many people work on a single set of source code files simultaneously using a version control system that has a central (or decentralized) master set of files, which individual developers will check out. The problem is that very often when a developer checks in her changes, she’ll find that another of her team members made conflicting changes since she checked out her code.

And that’s where continuous integration comes in: the team will constantly run the build and monitor for compiler errors or unit test failures. Many teams will set up a build server that periodically checks out the latest code from the repository, runs the automated build, and notifies the team if there are any errors. But setting up a contin‐ uous build server is only one part of continuous integration. Integrating continuously means that each team member constantly keeps his or her own copy of the codebase up to date.

### Planning Practices
**Weekly cycle**: XP teams use iterative development to manage their projects. In the weekly cycle practice, the XP team uses one-week iterations. Each cycle starts with a planning meeting, where the team members review the progress they’ve made on the project, work with the customers to pick the *stories* for the iteration, and then break the stories into tasks that are estimated and assigned to developers. It’s very similar to the Scrum planning meeting. Once the planning is done, the team spends the first part of the iteration writing automated tests for the stories and tasks, and the rest of the iteration writing code to make the tests pass. However, instead of self-organizing, some XP teams will stack up all of the tasks for the itera‐ tion and have each developer take the next task in the stack when his current task is done. This helps ensure that developers don’t cherry-pick their favorite tasks, and dis‐ tributes the tasks evenly among all developers.

*Quarterly cycle*: For long-term planning. Once a quarter, XP teams will talk about *themes*, or larger ideas in the real world that they can use to tie their project’s stories together. The team also steps back and talks about internal and external problems that they’re experiencing, nagging bugs, and repairs that haven’t been addressed yet. They take the time to reflect on the progress they’ve made so far, how well they’re meeting their users’ needs, and how the project is going overall. Some XP teams will use the same retrospective practice that Scrum teams use.

**Slack**: This practice has the team add minor, lower-priority stories to each weekly cycle. These stories are broken down into tasks during the planning meeting, but those tasks are left for the end of the iteration. That way, if the team runs into unexpected problems, it’s very easy for them to cut out those “slack” stories and still deliver complete, working software at the end of the cycle—and like all iterative development, XP teams only deliver soft‐ ware that’s “done done” at the end of the cycle, which means that it works, all tests pass, and it can be demonstrated to the users.

### Team Practices
**Sit together**: Teams work best when they sit near each other, and have easy access to everyone else on the team. Team members constantly consult each other about problems, ask each other for advice, and alert each other to problems. If the team sits together in an open workspace, this socialization is naturally encouraged.

**Informative workspace**: where the team’s working environment is set up to automatically communicate important project information to anyone who happens to be working in it. One popular way of making a workspace informative is to have a large task board and burndown chart posted prominently on a wall that everyone can see. By putting all of the information about the project in plain sight all the time, every single person on the team knows where the project stands, and that helps everyone make better decisions. Visible, always-in- your-face charts and other things that teams use to display data and make the work‐ space more informative are called *information radiators* because they automatically 'radiate' current information about the project to anyone who happens to be nearby.

Large, visible charts aren’t the only way to make a workspace informative. When team members have questions, run into problems, or raise issues, they have discussions. When those discussions take place in a shared workspace instead of closed confer‐ ence rooms, the people around them overhear, and will absorb information about what’s going on. When team members automatically absorb project information, whether it’s from charts or from overheard conversations, it’s called *osmotic communication*. While teams need to balance the value of that communication against the potential distraction of overheard discussions that can interrupt a developer’s train of thought and slow down development, effective XP teams will find a good balance that helps keep everyone up to date.

Why are informative workspaces important? The idea is to help the team make better decisions, and to give everyone on the team (regardless of seniority) more control over how the project is run—just like task boards help Scrum teams.

## Why Teams Resist Changes, and How the Practices Help
The thing that agile methodologies—and XP in particular—do really well is admit up front that we don’t know exactly what we’re going to build, and that the most efficient way we have of figuring this out is to build it. They’ll use working software instead of comprehensive documentation, because the most effective way they have of getting feedback from a user is to build part of the software first and get it into that user’s hands.

An XP team doesn’t just treat changes as a necessary evil; they recognize that the only way they can build the best software for their users is to get feedback often and respond to that feedback quickly. This is called **embracing change**.

Embracing change has two aspects: on the scope of the project, and on the codebase itself.

So how do the primary practices of XP help teams embrace change?

* Planning: When teams plan iteratively, and deliver working software at the end of every iteration, they constantly get feedback. Everyone on the team knows that they’re actively asking for that feedback—changes—and it’s a lot easier to deal with changes emotionally when you’re the one who asked for it in the first place.
* Team: Problems are a lot easier to deal with when you’ve got people around you to help. When teams sit together, they pick up on problems a lot earlier. And an informa‐ tive workspace helps make sure that everyone is thinking about the same prob‐ lems. This gives everyone on the team the ability to take control of those changes when they happen, and not be caught off guard by an unexpected change.
* Integration: One of the most frustrating problems caused by unexpected changes is how those changes ripple out through the entire codebase. If you’re working on a change, it helps me, as your team member, to find about it early. But I’ll still be caught off guard if a change you make to one part of the codebase causes an unexpected bug in the part that I’m working on. By continuously integrating, we’ll find out about that problem very quickly, and fix it early—before it has a chance to surprise us and cause headaches later.
* Programming: How does continuous integration help us find those changes? We’ve built a suite of unit tests that we run every time we integrate the code. So when you’re inte‐ grating your change, you run all of the tests, including the ones for the part of the code I’m working on. If one of those tests fails, then we can work together—and even pair up—to fix the problem in both parts of the code.

## The XP Values Help the Team Change Their Mindset
If you and your team resist change, push back against users who need the software to work differently than the team built it, and don’t believe that it’s realistic to build software that’s easy (or even possible) to change, then you don’t get XP.

And if you and your team don’t get simplicity—how simple design and code differ from complex design and code, where simplicity comes from, how your team’s culture and climate affect its ability to produce simple code and architecture, and how simplicity prevents bugs—then you don’t get XP.

The practices of XP help you concentrate on the quality of the code that you’re building before you’ve put a lot of code in place. Where Scrum is all about making sure that your customers know what you can produce and what you can’t, XP is about making it possible for you to make changes as quickly and as defect-free as possible. And that helps everyone on the team to develop an attitude toward quality that permeates all of the development work in your project.

Teams that have the right mindset always use great practices, and never need to be nagged to use them, because they just know that those practices lead to better software.

### The XP Values
* Communication: Each team member is aware of the work everyone else is doing.
* Simplicity: Developers focus on writing the most simple and direct solutions possible.
* Feedback: Constant tests and feedback loops keep the quality of the product in check.
* Courage: Each team member is focused on making the best choices for the project, even if it means having to discard failing solutions or approach things differently.
* Respect: Every team member is important and valuable to the project.
