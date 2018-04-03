#  Issue Tracker application

## Overview

The Issue tracker application is a simplified version of Jira, which allows users to create
and manage the progress of issues. This is a MEAN stack application for practice and skill showcasing.

The first part of the exercise is required, and the additional parts are optional.

### Part 1 - Core REST api
Design a RESTful API for the issue tracker system, which will provide CRUD functionality to API consumers.
Consumers should be able to complete all of the following:

1. Create a new issue.  POST - /issue
2. Retrieve an existing issue. GET - /issue/{id} or /issue
3. Update an existing issue. - PUT - /issue
3. Delete an issue.  - DELETE - /issue{id}


### Part 2 - Filtering and Sorting

Build on your initial implementation to support filter of issues on UI in AngularJS

- Filter by assignee, reporter and status
- Filter by date range eg tasks created between start and end date
- Sorting by created date, Ascending and Descending
- Pagination support.


### Part 3 - Comments Feature

Build on your initial implementation to support commenting on an issue. Requirements:

- An Issue can have zero or more comments
- Comments cannot be anonymous. They must have a user.
- Replying to comments is not supported. Comments on an issue cannot be nested.

## Getting Started

