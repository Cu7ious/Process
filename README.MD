## Day-to-day Development Process

1, Assign a card to yourself in Jira (so no-one else will pick it up)

  * if you need help choosing the card, ask in the dev chat, let people know at the standup that you're going to be done soon etc

2. Move your card to In Progress in Jira when you start

  * Try to have only one card In Progress

3. Create a branch for this card's development

  * the branch should be naming convention to match the card Jira ID, for example: NUM-101

4. Checkout this branch locally to start working on it (remember to track the remote branch)

```
git checkout -t origin/your-branch-name
```

5. Commit your work to this branch
  * all commit messages should be prefixed with the card number e.g. LUM-123 User can login

6. Push your commits to the remote repository

7. Ensure all work is complete

  * documentation is updated
  * tests are updated - and all pass

8.When you believe your work is complete (all Acceptance Criterias are met, tests are passing etc),
pass the card over to a coworker in your team for Code Review

* create a Pull Request in Github
* In the PR message add a brief list of what was done and what should be done to apply this PR,
for ex: https://github.com/Loomni/experts/pull/7
* in Jira, move your card to In Review column.
* ask for a code review in Slack in your teams channel or privatly
* keep code review discussion on Github
* if you are reviewing someone codes, after you are saticfied, leave an approve comment, for example: 👍

9. Move onto the next card that you should work on.

