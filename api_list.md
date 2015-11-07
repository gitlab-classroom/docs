API Design V1
---

**base_url: classroom.fdu13ss.org/api/v1/**

### Users
GET base_url/users --> return the list of all users
POST base_url/users --> create the user and return it

GET base_url/users/:id --> return the user
PUT base_url/users/:id --> update the user and return it
DELETE base_url/users/:id --> delete the user

### Classes
GET base_url/classes --> return the list of all classes
POST base_url/classes --> create the class and return it

GET base_url/classes/:id --> return the class
PUT base_url/classes/:id --> update the class and return it
DELETE base_url/classes/:id --> delete the class

GET base_url/users/:id/classes --> return the list of all classes belong to that user

### Members
GET base_url/classes/:id/members --> return the list of all members belong to that class
POST base_url/classes/:id/members --> create the member(s) and return it(them)
DELETE base_url/classes/:id/members/:id --> delete the member from that class

### Assignments
GET base_url/classes/:id/assignments --> return the list of all assignments
POST base_url/classes/:id/assignments --> create the assignment and return it

GET base_url/assignments/:id --> return the assignment
PUT base_url/assignments/:id --> update the assignment and return it

GET base_url/users/:id/assignments --> return the list of all assignments belong to that user
DELETE base_url/users/:id/assignments --> delete the assignment for that user

### Notifications
GET base_url/classes/:id/notifications --> return the list of all notifications
POST base_url/classes/:id/notifications --> create the notification and return it

GET base_url/users/:id/notifications --> return the list of all notifications belong to that user
PUT base_url/users/:id/notifications --> update the notification for that user
