# README

User 1: Fork and clone down [this](https://github.com/icorson3/rebase_playground) repo. Add others as collaborators. 

Simultaneously:

Check out a branch called `merge_workflow_user_#{whatever_user_you_are}`.
Create a file at the root of the project called `user_story_#{whatever_user_you_are}_merge.md`.
Add your user story to that file.
Add, commit your file.

User 1: Push your branch and put in a PR to Master. Join User 2.
User 2: Merge User 1's PR.
User 3: Add "Ilana and Ali are the bomb.com" to the file `user_story_#{whatever_user_you_are}_merge.md`.
User 3: Commit.
User 2: Add "I love Turing" to the file `user_story_#{whatever_user_you_are}_merge.md`.
User 2: Commit.
User 2: Use the command `git pull origin master` to pull in the most updated master to your branch.
User 2: Push your branch and put in a PR to Master.
User 1: Merge User 2's PR.
User 3: Update `user_story_1_merge.md` to change line 1 from "as a user" to "as a visitor".
User 3: Add and commit.
User 3: Use the command `git pull origin master` to pull in the most updated master to your branch.
User 3: Resolve Merge Conflicts.
User 3: Add, commit and push your branch and put PR in to Master.
User 1: Merge to Master.
All: checkout master and look at your git log...what does it look like? Draw a diagram to show this.

Simultaneously:

Check out a branch called `rebase_workflow_user_#{whatever_user_you_are}`.
Create a file at the root of the project called `user_story_#{whatever_user_you_are}_rebase.md`.
Add your user story to that file.
Add, commit your file.

User 1: Push your branch and put in a PR to Master. Join User 2.
User 2: Merge User 1's PR.
User 3: Add "Ilana and Ali are tbe bomb.com" to the file `user_story_#{whatever_user_you_are}_rebase.md`.
User 3: Commit.
User 2: Add "I love Turing" to the file `user_story_#{whatever_user_you_are}_rebase.md`.
User 2: Commit.
User 2: Use the command `git pull --rebase origin master` to pull in the most updated master to your branch.
User 2: Push your branch and put in a PR to Master.
User 1: Merge User 2's PR.
User 3: Update `user_story_1_rebase.md` to change line 1 from "as a user" to "as a visitor".
User 3: Add and commit.
User 3: Use the command `git pull --rebase origin master` to pull in the most updated master to your branch.
User 3: Resolve Merge Conflicts.
User 3: Add, commit and push your branch and put PR in to Master.
User 1: Merge to Master.
All: checkout master and look at your git log...what does it look like? Draw a diagram to show this.

### User Story 1

```
As a user,

When I visit the student index,

I see a list of all students, including their name and grade.
```


### User Story 2

```
As a user,

When I visit the student show,

I see one student, including their name and grade.
```

### User Story 3

```
As a user,

When I visit the root page,

And I click "Create New Student",

I am on the new student form.
```
