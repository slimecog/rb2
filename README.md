# README

## Merge Workflow

1. User 1: Fork and clone down [this](https://github.com/icorson3/rebase_playground) repo. Add others as collaborators. 

Simultaneously:

2. Check out a branch called `merge_workflow_user_#{whatever_user_you_are}`.
3. Create a file at the root of the project called `user_story_#{whatever_user_you_are}_merge.md`.
4. Add your user story to that file.
5. Add, commit your file.

6. User 1: Push your branch and put in a PR to Master. Join User 2.
7. User 2: Merge User 1's PR.
8. User 3: Add "Ilana and Ali are the bomb.com" to the file `user_story_#{whatever_user_you_are}_merge.md`.
9. User 3: Commit.
10. User 2: Add "I love Turing" to the file `user_story_#{whatever_user_you_are}_merge.md`.
11. User 2: Commit.
12. User 2: Use the command `git pull origin master` to pull in the most updated master to your branch.
13. User 2: Push your branch and put in a PR to Master.
14. User 1: Merge User 2's PR.
15. User 3: Update `user_story_1_merge.md` to change line 1 from "as a user" to "as a visitor".
16. User 3: Add and commit.
17. User 3: Use the command `git pull origin master` to pull in the most updated master to your branch.
18. User 3: Resolve Merge Conflicts.
19. User 3: Add, commit and push your branch and put PR in to Master.
20. User 1: Merge to Master.
21. All: checkout master and look at your git log...what does it look like? Draw a diagram to show this.

## Rebase Workflow

Simultaneously:

1. Check out a branch called `rebase_workflow_user_#{whatever_user_you_are}`.
2. Create a file at the root of the project called `user_story_#{whatever_user_you_are}_rebase.md`.
3. Add your user story to that file.
4. Add, commit your file.

5. User 1: Push your branch and put in a PR to Master. Join User 2.
6. User 2: Merge User 1's PR.
7. User 3: Add "Ilana and Ali are tbe bomb.com" to the file `user_story_#{whatever_user_you_are}_rebase.md`.
8. User 3: Commit.
9. User 2: Add "I love Turing" to the file `user_story_#{whatever_user_you_are}_rebase.md`.
10. User 2: Commit.
11. User 2: Use the command `git pull --rebase origin master` to pull in the most updated master to your branch.
12. User 2: Push your branch and put in a PR to Master.
13. User 1: Merge User 2's PR.
14. User 3: Update `user_story_1_rebase.md` to change line 1 from "as a user" to "as a visitor".
15. User 3: Add and commit.
16. User 3: Use the command `git pull --rebase origin master` to pull in the most updated master to your branch.
17. User 3: Resolve Merge Conflicts.
18. User 3: Add, commit and push your branch and put PR in to Master.
19. User 1: Merge to Master.
20. All: checkout master and look at your git log...what does it look like? Draw a diagram to show this.

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
