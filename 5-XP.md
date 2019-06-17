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

**Quarterly cycle**: For long-term planning. Once a quarter, XP teams will talk about *themes*, or larger ideas in the real world that they can use to tie their project’s stories together. The team also steps back and talks about internal and external problems that they’re experiencing, nagging bugs, and repairs that haven’t been addressed yet. They take the time to reflect on the progress they’ve made so far, how well they’re meeting their users’ needs, and how the project is going overall. Some XP teams will use the same retrospective practice that Scrum teams use.

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

## Understanding the XP Principles Helps You Embrace Change
* Humanity - Software is built by people, and there’s a balance between the needs of each team member and the project’s needs.
* Economics - Somebody is always paying for software project and everybody has to keep the budget in mind.
* Mutual benefit - Search for practices that benefit the individual, the team, and the customer together.
* Self similarity - The pattern of a monthly cycle is the same as a weekly cycle and the same as a daily cycle.
* Improvement - Do your best today, and stay aware of what you need to do to get better tomorrow.
* Diversity - Lots of different opinions and perspectives work together to come up with better solutions.
* Reflection - Good teams stay aware of what’s working and what isn’t in their software process.
* Flow - Constant delivery means a continuous flow of development work, not distinct phases.
* Opportunity - Each problem the team encounters is a chance to learn something new about software development
* Redundancy - Even though it can seem wasteful at first blush, redundancy avoids big quality problems.
* Failure - You can learn a lot from failing. It’s OK to try things that don’t work.
* Quality - You can’t deliver faster by accepting a lower quality product.
* Accepted responsibility - If someone is responsible for something, they need to have the authority to get it done.
* Baby steps - Take small steps in the right direction rather than making wholesale changes when adopting new practices.

When you take the time to understand the values and principles, you start to learn where your team has problems. This is uncomfortable, and it’s often a negative experience. For example, you might look at the principle of failure and real‐ ize that your team has a culture where failure is not an option. Even admitting that you ran into a problem will cause your boss to yell at you. Your team members may start to disrespect you as the person who always makes mistakes. There are many companies where simply admitting that you made a mistake will have serious profes‐ sional consequences.

### XP Principles Help You Understand Planning
Many of the values and principles of XP are shared with Scrum. But there are a lot of differences, too. Like roles—Scrum has the roles of Product Manager and Scrum Master, while a mature XP team doesn’t have fixed roles. A useful way to learn about XP is to concentrate on the principles that it doesn’t share with Scrum. That can be especially valuable when learning about how XP teams plan projects.

A lot of Scrum is about planning: planning the big picture using the product backlog, planning an iteration using the sprint backlog, and getting everyone on the team to collaborate on the plan using the Daily Scrum and other Scrum practices. XP uses similar iterative practices: the quarterly cycle is used to plan the big picture, the weekly cycle is used to manage iterations, and the team uses an informative work‐ space that contains tracking tools like a task board.

But planning and tracking an XP project is not the same as planning and tracking a Scrum project, and the principles help us understand why. Why doesn’t an XP project have specific roles? This is where XP teams take **opportunity** and **diversity** very seriously. It’s rare (although not unheard of) on a Scrum team for a Product Owner or Scrum Master to jump in and work on the software architecture and design, just like it’s rare for a team member to take the lead in working with users or grooming the backlog. XP teams explicitly reject a separation of roles for two reasons. The first rea‐ son is that shutting someone out of a role means passing up an opportunity for him or her to contribute if he or she happens to have something to contribute. And the second is that anyone on the team might bring a fresh perspective, and that perspec‐ tive could be the key to unraveling a tricky problem. Sometimes a highly technical developer has a very good idea for a user, or a project manager might have some val‐ uable input on architecture—specifically because she’s been thinking about the project from a completely different perspective than the people working on those aspects of it.

XP teams rotate pair programming partners, rather than staying with the same pairs all the time. It brings **diversity** to the pairs and means bringing fresh eyes and fresh perspectives, which helps catch more problems and can spark innovation. And the principle of **humanity** comes into play as well: bringing different people in, and having them work together constantly, helps create an environment where everyone is giving feedback to each other all the time, and it helps each person learn to accept feedback and even criticism from their teams while still respecting them as people.

Principles can also help us understand why XP doesn’t have a specific after-action review practice, the way Scrum has retrospectives. XP places value on **improvement** and **reflection**, and XP teams constantly talk about how they’re doing and how they can improve. But XP teams tend to be very conscious of “navel-gazing”—taking reflection too far and getting distracted from continuously delivering work. So XP teams tend to mix their reflection in with the work. This is something that pair pro‐ gramming is very good at: getting developers to talk about what they’re doing while they’re doing it. The principle of **baby steps** helps this a lot: instead of setting a large, overarching goal ('let’s adopt all of the XP practices'), the team can take a small step toward it (“let’s start pair programming, and we’ll make sure we talk every day about how we’re improving”).

### Feedback loops
One way that XP and Scrum are similar is that both methodologies place a lot of value on **feedback**. We already saw how Scrum uses feedback loops to get continuous communication between the team and the customer. Scrum teams and XP teams share very similar values in **openness** (Scrum) and **communication** (XP). They have very similar ways of thinking about how people on software teams communicate.

But XP has more to say about feedback. XP teams aim for a very short iteration—the weekly cycle—to increase feedback and shorten the feedback loop. We learned with Scrum that to iterate effectively, the team has to take an active role in understanding what the users need and what’s valuable to them. To keep feedback loops short, they continuously reflect on how the project is going. If there’s a problem then the team will talk about it. Osmotic communication from sitting together helps spread that feedback around the team. When all of these things combine, the team can achieve **flow**, the XP principle that’s about having a direct and efficient path through the project that delivers a constant stream of high-functioning, high-quality software.

An XP team doesn’t do all of this up-front planning. They’ll discuss themes and sto‐ ries as part of their quarterly cycle, but they have very short, one-week iterations. Individual tasks are only planned on a week-by-week basis. This is the 'extreme' part of Extreme Programming—that’s an extreme way of making decisions at the last responsible moment, and to a developer who’s used to having all of the decisions made very early, it feels like these decisions are cut extremely close.

Another way that an XP team may feel 'disorganized' to someone used to a lot more structure: pairs are constantly switching, and people aren’t planning ahead about who should do what task. The decisions about who does the work aren’t even made until it’s time to actually do the task. This is different from how Scrum teams function, with a daily meeting to review a sprint plan and assign tasks through self- organization. Because the XP team has such a short iteration and short feedback loops, they can leave the tasks in a pile and have each pair simply pull the next task off of the pile when they’re ready for it.
