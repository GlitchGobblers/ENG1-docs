# Adapted Agile & Scrum framework
<br></br>

## Agile - The Philosophy

- **Software that works is key:** Our main goal is to have a new playable piece of the game at each weekly meeting.
- **Customer Collaboration:** We have a customer. Getting their feedback regularly to ensure we're building the right thing is key.
- **Team Collaboration:** Agile relies on self-organising teams. Our roles should be flexible - success comes from everyone feeling responsible for the final product.

## Scrum - The Framework

In official Scrum, there are only three roles. Here is how we will adapt:

- **Product Owner:** They represent the customer and decide what the team should build. They are in charge of the master to-do list. This will be Charles (Requirement Lead), responsible for talking to the lecturer, understanding the requirements, and prioritising features to be built
- **Scrum Master:** They manage the process. They will help the team use Scrum effectively, remove any obstacles ("we can't decide on a library"), and keep things running smoothly. This will be Dash as he is the Project Lead.
- **The Development Team:** Everyone is a developer responsible for delivering a finished piece of the game.


### The Scrum Events

We will use Sprints for our project that last one week.

1. **Sprint Planning:**
  - At the beginning of each week in our meeting, the product owner (Charles) will present the highest priority features from the master to-do list. Everyone will decide how much of that work we can realistically complete within the week. We then break down the features into small, concrete tasks.
2. **Daily Scrum:**
  - Not required for a project of this size, although we should stay in touch over the Instagram group chat about where we are at during the week.
3. **Sprint Review:**
  - At the end of the Sprint, we will demonstrate the working software we built during the week. This is a live demo of the game. The goal is to get feedback from each other.
  - This is the perfect time to show progress to the team and, if possible, our customer.
4. **Sprint Retrospective:**
  - Just before starting the next Sprint, we will discuss how it went. What went well, what didn't, what we will change in the next Sprint.
  - Hannah (Secretary) will be responsible for documenting the one or two "action items" the team agrees to implement in the next Sprint.

### Scrum Artifacts

**Product Backlog:**
- The single, master to-do list for the entire project, ordered by priority.
- Here, Charles will translate the project brief into actionable items.

**Sprint Backlog:**
- The list of tasks that we have committed to completing in the current Sprint.

**The Increment:**
- The sum of all the Product Backlog items completed during a Sprint. At the end of each Sprint, we should have a new version of the game. It won't be the full game, but it will be a working version of it.


# Coding Standards
- First of all, your code *must* be clear to other people.
	- if it does something even slightly unexpected or uses an unusual quirk, anything you have to think about, add a comment
	- we're not being marked on LOCs here
- Use [guard clauses](https://refactoring.guru/replace-nested-conditional-with-guard-clauses) where possible to avoid nested ifs and associated complexity.
- Write clear commit messages.
	- In general, commits should be one conceptual unit - fixing one big bug, some related small bugs or one piece of functionality.
		- you don't have to commit all your changes at once, and shouldn't if it conflicts with this!
		- `git add -p` is your friend here.
	- Look over all your code before committing it.
- Prioritise consistency over stylistic elegance.
	- This includes consistency with other people's code styles - if it's a real issue, send a message and we can discuss it properly.
- Comment *why* code is doing what it does - edge cases, places where the most obvious way is incorrect, things of that nature.
- Test before pushing.
- Use positive naming conventions; use `isShown` rather than `isHidden`.
	- The same applies for:
		```python
		if not thing:
			...
		else:
			...
		```
	- you can reduce this to
		```python
		if thing:
			...
		else:
			...
		```
	- and you should!
	- this is a rule of thumb - if it does work better to violate this, so be it, but comment why
- Code should be read like a book - top to bottom, left to right. They don't go diagonally off the page (lots of indentation) and their paragraphs aren't pages long, nor should your functions be.
- Variable names should be self-descriptive.
- Write tests in parallel with the code.
- Write as little code as possible.
	- if we can use an inbuilt function, we should - that's less we have to maintain and test
- When a bug is encountered, write a test immediately to reproduce it, then create an issue for it.
	- This is important for documentation purposes as well as ensuring bugs don't creep back up when we think they're fixed.
	- up to a point - obviously if you find a bug before you push code or it's trivial to fix, do that
- It is harder to read code than to write it.
	- As such, people want to rewrite code others wrote - we should not do this.
- Do not use variable shadowing.
	- it's unclear and unnecessary most of the time
- Use visually distinct names.
	- `item` and `items` are hard to tell apart at a glance.
- Split up chained function calls and use well-named intermediate variables to make clearer what's going on.
	- 