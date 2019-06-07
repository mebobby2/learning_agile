# Scrum Planning and Collective Commitment
Now that you understand what Scrum is all about—self-organization and collective commitment—how do you actually get your team to do it in real life?

Collective commitment means *genuinely trying to make your software more useful*. To make your software useful, you need to understand what it is that your users are doing. And the most effective way is customer collaboration.

Common way to build not so useful software
* Gold-plating. Teams gold-plate their software, or add extra features that were never requested and aren’t needed by the users, with the best of intentions.
* The throw-it-over-the- wall mentality. Teams would build software, throw it over the wall to their users, and hope‐ fully some of what they built would stick.

## User Stories Help Build Features Your Users Will Use
A **user story** is a quick and simple description of a specific way that a user will use the software. Most user stories are between one and four sentences long.

Typical format: As a 'type of user', I want to 'specific action I’m taking' so that 'what I want to happen as a result'.

User stories also give teams an easy way to manage their backlog. Many effective agile teams maintain a backlog that consists almost entirely of user stories.

Most teams will then break the stories down into tasks and start to estimate how long those tasks will take. The tasks for each story would go in the 'To Do' column of the task board to wait until someone can work on them.

## Conditions of Satisfaction
**Conditions of satisfaction** are an effective tool for helping developers to know what the software will look like when it’s complete, and to gauge how close they are to done. Also known as acceptance criterias.

Conditions of satisfaction help this by giving the team a concrete definition of “Done.” This gives the team and the Product Owner a concrete, unambiguous way to figure out exactly when that story is 'Done'. The user story is “Done” when a user can open up the working software, and execute each of the conditions in exactly the same way that it would be demonstrated in the sprint review.

## Story Points and Velocity
**Story points** are a way to under‐ stand how much effort you’ll need to build a specific user story by assigning a num‐ ber of points to it. The team comes up with those points by comparing the current user story to other stories your team has built in the past.

As your team assigns points to all of the stories they work on, they start to see how many points’ worth of stories they can complete (or “burn”) in a sprint. If your team com‐ pletes on average, say, 25 points’ worth of stories in a sprint, then their **project velocity** is 25 points per sprint.

A sprint planning session using story points might go like this:
1. Start with the most valuable user stories from the product backlog.
2. Take a story in that list—ideally the smallest one, because that makes a good baseline for comparison—find a similarly sized story from a previous sprint, and assign it the same number of points.
3. Discuss with the team whether that estimate is accurate—discovering additional problems, work, or technical challenges increases the estimate; simplifying fac‐ tors, reusing existing code, or scaling back what needs to be built decreases the estimate.
4. Keep going through the stories until you’ve accumulated enough points to fill the sprint.

It’s OK to leave room in the backlog, but it’s not OK to go beyond what your team has done in the past.

What about the first time you do this? It takes time to build up a history of stories, and to build up the common knowledge among your team about how big a 3-point story is. So for the first time through, just take a guess. By the time you’ve gone through two sprints, you’ll have plenty of stories to compare to, and a good idea of your team’s average velocity.

## Burndown Charts
A **burndown chart** is a way for anyone to see, at a glance, how the sprint is actually progressing when compared with the team’s past velocity.

1. tart with an empty line chart. The x-axis has dates, starting with the first day of the sprint and ending with the last day. The y-axis has story points, ranging from 0 to 20% more than the total number of points in the sprint backlog. Draw the first dot on the chart: the number of points in the sprint, at day 0. Draw a straight line (called the 'guideline') from the first point to the end of the project—zero points left when the sprint is complete.
2. As soon as the first user story is finished and moved to the 'Done' column of the task board, draw the next dot on the chart: the number of points left in the sprint, at the current day. As you finish more stories and burn more points off of the backlog, fill in more days in the burndown chart.
3. You might discover during a Daily Scrum that more work needs to be added. Sometimes you’ll do this because the team is burning more points than they expected, and they’ll finish early as a result. Or an important support task comes in, and the team and product owner agree that it needs to be added to the sprint, but they don’t yet know how much work the team will need to remove to balance out the sprint. When you add the cards for that work to the task board, schedule a follow-up meeting to gather up the team, estimate the story points for each card, and add them to the chart. It’s helpful to draw an extra line that shows where the points were added—and don’t be afraid to write notes on the chart!
4. As you get close to the end of the sprint, more and more points burn off the chart. Keep an eye out for a gap between the guideline and your actual burn‐ down, because that could mean you’ve got too many points left in the sprint and need to remove a user story.

## Planning and Running a Sprint Using Stories, Points, Tasks, and a Task Board
We just showed you how a team can use story points and velocity to figure out what will go into the sprint. But how do they actually plan out the work.

Here’s how many teams do this:
1. The team holds the second sprint planning meeting. The Scrum Master starts with the first story, and leads a discussion with the team about exactly what they need to do to build it. Everyone works together to come up with a list of individ‐ ual tasks that they think will each take no more than a day to complete. Each task is written on a separate card—some teams use different colored cards for stories and their tasks to make it easier to tell them apart—and the story card is grouped together with its task cards. This continues until all stories are planned. If the sprint planning timebox expires before all of the stories are broken down, each unplanned story gets a single task card for a task to plan out the story.
2. The stories and their tasks are grouped together and added to the “To Do” column of the task board.
3. When a team member finishes one task and is ready to move on to the next, he moves the task card for the completed work to the “Done” column. Then he pulls the task card for the next piece of work out of the “To Do” column, writes his name on it, and then puts it back on the board in the “In Progress” column. If the story is still in the “To Do” column, he moves it to “In Progress” as well (but doesn’t write his name on it because one of his teammates might work on tasks for the same story).
4. As the sprint rolls along, the team moves tasks from “To Do” to “In Progress” to the “Done” column. It’s pretty common for team members to discover that they need to do additional tasks to finish a story. When this happens, the new task is added to the board, and the team member points that out in the Daily Scrum so everyone is aware of what’s going on, and can help spot potential problems.
5. Once a team member finishes the final task for a story, he pulls the story card off of the task board, verifies that all of the conditions of satisfaction are completed, and moves it to the “Done” column so that it’s grouped with all of its tasks. (But remember—the story’s not done done until the Product Owner accepts it as potentially shippable on behalf of the company!) If he discovers that one of the conditions of satisfaction hasn’t been met, then there’s still work to be done—so he moves the story back to the “In Progress” column and adds tasks to complete that work to the “To Do” column.
6. The sprint is done when the timebox expires. This means that there might still be story and task cards left in the “To Do” and “In Progress” columns. The stories go back to the product backlog so they can be prioritized in the next sprint planning session,5 but the team can reduce the number of points based on the tasks that remain. The team does not get credit for completing a story until its card and all of its task cards are moved to the “Done” column.

## Is Your Company’s Culture Compatible with Scrum Values?
To understand if you’re ready for **commitment**, ask if you, your team, and your boss are OK with:
* Relinquishing control of the project, and trusting the team to decide what gets delivered?
* Not going off on your own and building something without talking to the rest of the team, and just integrating it at the end?
* Not having one “single, wringable neck?”
* Listening to comments and feedback, and not telling people to mind their own business?
* Actually being willing to take responsibility? Does everyone on the team feel the same way?

To understand if you’re ready for **respect**, ask if you, your team, and your boss are OK with:
* Trusting the team to do the right thing, and deliver each feature at the best possi‐ ble date based on relative value and how the project progresses—even if it causes the project to take longer than you expect?
* Giving the team enough time to do the work, and not demanding overtime of them?
* Trusting the team to choose the tasks that are right for them and for the project, rather than relying on strict roles, RACI matrices, etc.?
* Not being able to ever say again that you don’t know why the team decided to do something the way they did?

To understand if you’re ready for **focus**, ask if you, your team, and your boss are OK with:
* Never asking anyone on the team to do work that’s not part of the current sprint?
* Never asking anyone on your team to do work that the whole team hasn’t agreed to take on (“but I need this done now!”)?
* Putting what’s most valuable to the company ahead of all other project or work concerns?
* Not being able to demand that team members work on specific tasks in a certain order up front?

To understand if you’re ready for **openness**, ask if you, your team, and your boss are OK with:
* Listening to what other people have to say—and actually thinking about it?
* Thinking about project planning or users if you never have before?
* Thinking about technical details if you never have before?
* Thinking about what the programmer next to you is working on, and whether it really fits into the overall goal?
* The programmer next to you thinking about your work in exactly the same way?

To understand if you’re ready for **courage**, ask if you, your team, and your boss are OK with:
* Not being able to blame lack of planning on your project manager?
* Not being able to blame poor requirements that don’t hit the mark on your Product Owner or senior managers?
* Taking the time to really understand your users?
* Building something that isn’t perfect, because what the users need most is something that’s simply good enough?
