# madlibstemplate

**Group Assignment: Collaborative Mad Libs Game using Git and GitHub**

**Objective:**
The goal of this group assignment is to familiarize students with collaborative software development using Git and GitHub. In this assignment, students will work together to create a Mad Libs game. Each student will contribute by adding words to the story from their own development branches. They will then use pull requests to integrate their changes into the main branch and manage potential merge conflicts entirely within GitHub's online interface.

**Instructions:**

**Step 1: Setting Up the Project Repository**

1. The instructor will create a new GitHub repository for the Mad Libs game.

2. Students will be divided into groups and assigned to a team. Each team will have its own fork of the main repository.

3. Each student should clone their team's forked repository to their local development environment using the following command:
   ```
   git clone <repository_url>
   ```

**Step 2: Developing the Mad Libs Story**

In their local repository, students should create a new branch for their contributions. The branch should be named according to a convention, for example, `<username>-madlibs`.

Each student will choose a predetermined number of placeholders to fill in with words of their choice from the `madlibs_list.txt` file provided below. The placeholders should be divided evenly within the group.

**`madlibs_list.txt` File:**

```
1. Friend's Name
2. Adjective
3. Adjective
4. Color
5. Month
6. Number
7. Noun (Plural)
8. Noun (Plural)
9. Noun
10. Room Name
11. Liquid
12. Adjective
13. Material
14. Activity
15. Adverb
16. Number
17. Unit of Time
18. Different Activity
19. Adjective
20. Vehicle
21. Your Name
```

**Step 3: Completing the Mad Libs Story**

1. Inside the repository, there should be a `story.txt` file that contains the Mad Libs story with placeholders for different parts of speech (nouns, verbs, adjectives, etc.).

2. Each student will fill in the placeholders in the `story.txt` file with the words they chose from the `madlibs_list.txt` file.

**The Galactic Adventure Story:**

```
Title: The Galactic Adventure

Dear [1],

I am writing to you from a [2] spaceship in a [3] galaxy. I found myself here one day after
going for a ride on a [4] rocket in [5]. There are [6] [7] and [8] of [9] here! In the
[10] there is a pool full of [11]. I fall asleep each night on a [12] bed of
[13] and dream of [14] [15]. It feels as though I have lived here for
[16] [17]. I hope one day you can visit, although the only way to get here now is
[18] on a [19] [20]!!

Best wishes,
[21]
```

**Step 4: Collaborative Development and Pull Requests**

1. After filling in the story, each student should push their branch to their team's forked repository on GitHub:
   ```
   git push origin <username>-madlibs
   ```

2. Once all students have pushed their changes, they should open pull requests (PRs) to merge their individual branches into the main branch of the team's repository.

3. All members of the team should participate in reviewing and merging pull requests. The goal is to ensure that each student's contributions are appropriate and fit the context of the story.

**Step 5: Managing Merge Conflicts Online**

1. If conflicts arise during the PR merging process, they will be indicated in the GitHub interface.

2. Each student whose PR has conflicts should navigate to their PR on GitHub and click on the "Resolve conflicts" button.

3. GitHub will provide a side-by-side comparison of the conflicting files, allowing students to choose the correct changes for each conflict.

4. Students can edit the conflicting portions directly in the GitHub interface, choosing the desired changes from each conflicting branch.

5. Once conflicts are resolved, students can mark the conflicts as resolved within GitHub and add a comment explaining the changes made.

6. After resolving conflicts, students can request another review from a team member and, upon approval, proceed to merge the PR.

**Step 6: Finalizing the Project**

1. Once all PRs are merged, the Mad Libs story will be complete.

2. The team can test the game by running a script that replaces the placeholders in the story with the chosen words.

3. The final version of the Mad Libs game should be available in the main branch of the team's repository.

**Assessment:**

Students will be assessed based on their ability to effectively use Git and GitHub for collaborative development, their understanding of branching, pull requests, conflict resolution, and the creativity of their contributions to the Mad Libs story.

**Submission:**

There's no need for a separate submission as the progress will be tracked through the GitHub repository, pull requests, and merged branches. However, each student can document their contributions and experiences in a brief report to be submitted along with the final assessment.
