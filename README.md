# COMP2030 Project Assessment

It is your responsibility to read through this content. Explanations of the process and your expectations will be covered during tutorial or practical sessions in the first two weeks of semester. If you need clarification, you must seek guidance early. Approaching the teaching staff with confusion about the _process_ within two weeks of the due date is not appropriate and will indicate a lack of contribution to the project.

This repository contains all the required information for the COMP2030 major project assignments. This repository will be used for the following assessments:
| Part | Repo Location | Weighting (Group/Individual)| Due Date |
| --- | :--- | :---: | :--- |
| Report: User Research and Low Fidelity Design | [p1-p3/user-research-part1](p1-p3/user-research-part1/user-research.md) | 25% (15%/10%) | Week 5 |
| Artefact Creation: Website Construction | [src](src/website.md) | 35% (25%/10%) | Week 10 |
| Artefact Creation: Usability Evaluation, Iteration, and Demonstration | [p1-p3/ux-evaluation-part3](p1-p3/ux-evaluation-part3/ux-evaluation.md) | 25% (15%/10%) | Week 13 |

The use of this repository is intended to emulate real world development processes. You will be required to effectively use git commands to add your work and review your peer's work for inclusion in the group project.

> [!CAUTION]
> As soon as you are uncertain, you should seek help from the teaching staff to understand your role and the requirements for the contribution process.

## Setting up the project

One person within your team should fork this repository and add the other group members as collaborators.

1. Open the repo in github.com
1. Click the Settings cog
1. Select Collaborators (under the Access section)
1. Click Add people
1. Use username or emails to add your other group members.

> [!IMPORTANT]
> Each of these assignments are group based submissions.

## Contents of the Project repo

The project repo is the location where all of your content for the assignment will be store. You will use git to maintain version control of your development. The project repo contains the following directories:

- **.AI_Images**: _!! no actions needed in this directory !!_. The directory stores images for use in the assignment specs
- **.devcontainer**: _!! no actions needed in this directory !!_. The directory is for the setup of the Codespaces devcontainer. Any modification of this directory and the files within could cause complications in setting up your cloud-based environment.
- **.github**: pull request roster and pull request template
- **p1-p3**: location for final assignment work
  - **user-research-part1**: directory where you will need to upload your FINAL project work for assignment 1.
    - _data_: store any observation, survey, user specific data, etc., within this directory.
    - _imgs_: store any images that are relevant and included in your report.
  - **ux-evaluation-part3**: directory where you will need to upload your FINAL project work for assignment 3.
    - _data_: store any observation, survey, user specific data, etc., within this directory.
    - _imgs_: store any images that are relevant and included in your report.
- **project-docs**: location for project management documents
  - **drafts**: any temporary, early versions, or cut pieces of content from part 1 and part 3 should be stored here - use suitable directory structures
  - **meeting-notes**: agendas, summary of discussions, decisions made
  - **project-management**: contact information for each team member, scheduled allocated tasks, agreement for contribution, plans for resolving team member conflict
- **src**: location for final assignment work. This is the directory where your website will be deployed from. You will need to create a suitable folder structure for the website.
  - **inc**: directory containing the includes files for database connection
  - **sql-exports**: directory where you will save your dumps of your built and active database before assignment submission.

## Adding content to the project

You will need to effectively contribute to your group and ensure submissions have passed suitable PR reviews before merging into the main submission.

For any inclusion in the project repo, you **MUST** follow the steps below:

1. Ensure your version of the `main` branch is up to date
1. Create a new branch for your addition
1. Edit your addition to the group project
1. Commit and push your branch
1. Submit a pull request
1. Another group member will review your submission and merge your changes.

_Instructions for this process will be covered in the first practical session of the topic._

This process will show level of contribution, timeliness of contribution, and timeliness of review before merge. Based on these metrics your individual mark for the group mark will be determined.

If the logs show that your work has pull requests assigned at the last minute, your mark will be affected. If the logs show that your review of pull requests is last minute, your mark will be affected. If the logs show that your contribution quality, commit messages, and pull request summaries and reviews are too brief or superficial, your marks will be affected.

Based on the contribution logs there will not be a need for peer evaluation of the project. Logs will be used to quantitatively assess your contribution, while commit and pull request statements will be used to qualitatively support your contribution. Marks will be generated from this analysis.

Once you have completed the required phase of the project, one group member should create a log of the activity on the repo, download a zip of the repo and submit that to the FLO submission box before the due date.

### To export a log and download a zip of your code

1. Make sure you are in the `main` branch
1. Open your Terminal in VS Code (or CodeSpaces)
1. Execute the following command:<br /> `git log --pretty=format:'%h,%an,%ar,%s' > dir1/dir2/aName-log.csv`, <br />
   where dir1/dir2 is the path to your current phase, and aName is the name of the current phase, e.g., `c1/cycle1/c1-log.csv`. This will create a new file `c1-log.csv` in your project repository
1. Commit and push the change to the main branch
1. Go to github.com
1. Select the Code button in your repo
1. Click on the Local tab
1. Click on Download ZIP

## Project and individual marks

This group component will make up _at least half_ of the marks for each submission. You will be assigned an individual mark from the group component based on the quantity, quality, and timeliness of contributions identified in the git activity log (commits and PR reviews). The remaining marks will be assigned on an individual basis through an in-class quiz covering the learning requirements for that specific assessment. This process will ensure that your contribution to the group is assessed (quality of the work submitted moderated by logs from the git repo), as well as your individual understanding and application of the concepts covered, through the quizzes.

> [!IMPORTANT]
> There will be no extensions allowed for the quiz session.

You must attend in person. You must have appropriate identification (student card or photo id) available during the quiz session. The quiz will contain questions that directly relate to the content your group completed for each submission.

You are expected to review the due dates for group submission and the corresponding in-class quiz times. No additional notifications, announcements, or reminders will be provided.
