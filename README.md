# Lab 5x requirements

A new assignment requirement will appear here every week, so check back regularly. Commit and push everything to your **Lab-5x** repository.

----
----

## Lab 5 assignment

**Points**: 0.3

**Deadline**: Week 6

**Last chance deadline and penalties**: Week 8, -0.1 points / week delayed

You will need to:
- Make teams of two. We will refer to the two members as `Alice` and `Bob`. `Alice` will create a frontend for `Bob`'s REST API and vice versa. They are not allowed to work on each other's REST API in any way. They are only allowed to communicate with each other to request necessary information (such as the REST API deployment URL and the Swagger URL), changes and bug fixes. Project sharing is strictly forbidden and is considered fraud if they are caught doing it, so they are very careful not to do this.
- The frontend should be a Single Page Application (SPA). You can choose any frontend framework or library that lets you create SPAs: React, Angular, Vue etc. It should be something that is under active development.
- Add Swagger to your REST API. It should be publicly accessible. Share the Swagger URL with your teammate.
- Implement at least one CRUD and one filter / statististical report on the frontend.
- Deploy the frontend either on https://www.netlify.com/ (or equivalent) or on your virtual machine. If you choose netlify or equivalent, it should deploy automatically when you commit to github.

This is a long term setup: you will keep working like this for the forseeable future, so choose your teammate accordingly.

Ideally, each team should have `2` members. However, where there are an odd number of students in a lab group or when your lab teacher admits exceptions we will also allow teams of `3` people: `Alice`, `Bob` and `Charlie`. They will work like this:
- `Alice` write a frontend for `Bob`'s REST API.
- `Bob` writes a frontend for `Charlie`' REST API.
- `Charlie` write a frontend for `Alice`'s REST API.

Regarding grading:
- If a team member is not present, the other team members must present their own frontend in the browser and their own REST API in Swagger and Postman. Only they will receive a grade.
- Your grade depends on your team member as well. If they do not deploy their API or do not work on it, you are not allowed to do it yourself. You must find another team and let your lab teacher know.
- If you decide that you absolutely do not want to work in a team then all of the labs involving such team work will grant you at most `50%` of the posted points.
