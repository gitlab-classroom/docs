# PRD for GitLab Classroom v0.1
> Product Requirement Design
>
> Author: Zhongyi Tong (@geeeeeeeeek)
> Team: @gitlab-classroom/dev-pm-course 

## Purpose and scope
To clarify the requirements in *GitLab Classroom*, and to provide more detailed information on what this project is about, what features are necessary and what schedule we need to follow.

`v0.1` is the first version of *GitLab Classroom* to be general available. We plan to implement limited features with highest priority.

This doc is written from the perspectives of Product and Development. For the other requirements, please refer to [Project Initiation Documentation](#).

### Product Overview

#### Use Cases

**All Users**

- Enter the app
  - Login with credentials.
  - Redirect to a dashboard where involved courses are displayed.
- View a course
  - Click a card in the dashboard.
  - Redirect to the course page where information of assignments and members are available.
- View an assignment
  - Click the assignment in the course page.
  - Redirect to the assignment page where information of the assignment is available.

**Teachers (extends All Users)**
- Distribute an assignment
  - Click `New Assignment` button in the course page.
  - Enter necessary information about the assignment and click `OK`.
  - Redirect to the assignment page.

**Students (extends All Users)**

- Submit an assignment
  - Get a url from the assignment page, specifically generated for the student.
  - Push his local repo to that url.

**Admin**

- Create a course
  - Enter necessary information about the course (meta info, students and teachers) and click `OK`.
  - Redirect to the course page.
- Import members for a course
  - In the course page, click `Import Members` buttons.
  - Select users and assign roles to them.

### Requirements
#### Functional requirements

#### Technical requirements
#### Interaction requirements
### Assumptions
### Constraints
### Dependencies
### Timelines and milestones