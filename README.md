# Scope Review Rubric

> Note: There are exceptions to almost every rule here. If you have a good reason, it's possible that one of these checkboxes may not apply to you, but they apply to most, so they are good guideposts.

- [ ] Project Title
    - [x] Has a title
    - [x] It's name doesn't change throughout the scope
- [ ] Application Overview
    - [x] 2-5 Sentences explaining the application in non-technical terms
    - [x] Someone who has never heard of the application can start to picture what it does.
    - [x] Not a description of the problem is that it is solving (generally speaking, clients will know what the problem is)
- [ ] Application Views
    - [x] Each view has a title
    - [x] Each view has bullets describing what it does
    - [x] Each view has a wireframe
        - [x] Wireframes should typically not include color
    - [x] If there are buttons, it should be clear what each button does. This can be listed on the wireframe or as a bullet
        - [x] If a button takes a user to a different view, a bullet should call out the view name that it navigates to 
    - [x] If the view is only accessible to some users, it should be clearly described in a bullet
    - [x] Each view has a description of how users arrive there.
    - [ ] Ideally, stretch goals that the user feels are likely should be included in the views and noted as stretch goals in a bullet 
- [ ] Project Schedule
    - [x] At a minimum, each view should have a date associated with it
    - [x] The schedule is broken into features -- that is, a feature is a chunk of functionality that delivers demonstratable value
    - [x] Each feature should have an appropriate due date (if all dates are the same, that is not valid)
    - [x] There should be at least one feature per day, if a feature will take longer than a day, it is too large and should be broken down
    - [x] The schedule should support a working, demonstrable CRUD app complete on the Thursday of the first week of work
    - [x] All Base Mode features should be complete on the following Thursday (the week before final presentations)
- [ ] Browsers
    - [x] Only include browsers you will actually be testing
    - [x] Round up to the nearest whole number (ex Chrome 66, not Chrome 66.2384.239)
    - [x] If you are including mobile browsers, include the phone you are supporting as well
- [ ] Assumptions
    - Assumptions can be anything you are basing your project upon. Often they are things outside of your control like assets you need from the client or a new technology you need to research. The idea is that if your assumptions are known to others, and they turn out to be incorrect, it may change how much effort your project will take.
    - They often raise questions that cannot be answered up front.
        - [x] Client will provide all staff images
        - [x] LibraryX can calculate parsnip trajectory. Documentation suggests it is possible but is not explicit.
        - [x] App Administrators will give new users their password verbally
        - [x] Any APIs you are using will not change
        - [x] Any APIs you are using will not change their pricing
        - [x] The API can do such and such (if the docs are unclear). If you need something from the API but don't know for sure it has it, you are making the assumption you can get it
- [x] Entity Relationship Diagrams
- [x] Review everything on every view. If it is not hard-coded it must be saved in the database.
- [x] Technologies
    - [x] All node modules installed with `npm install`
    - [x] Database
    - [x] File storage (Filestack, AWS, etc)
    - [x] CSS library/framework
    - [x] Deployment technologies (Heroku)
- [ ] Stretch/Future Goals
    - [ ] Should include feature title and brief description
    - [ ] Should take several months of full time effort to complete

## Final Pass

- [ ] All instructions in the scope are removed. It should no longer say things like: _This section should be short. Most of the details should be included in the views section._
- [ ] Is this actually reasonable?
    - [ ] Will CRUD be complete within a week?
    - [ ] Can base mode be completed on time for presentations?
