# Things we'll be looking for:

- A strong understanding of Rails, React and best practices
- BE: Ability to create restful routes
- BE: Demonstration of well-organized code, following OOP
- BE: Test Driven Development
- FE: An understanding of basic usability practices and standards
- FE: A clear hierarchy of information
- Clear documentation
- Your ability to prioritize for MVP
- Clean, well factored code
- An understanding of how technical choices you made (i.e. with your database schema, feature prioritization) can impact the end user or business.

Try to limit your total time to approximately 8-10 hours each side of the stack. Historically, students have spent a bit less than 8 hrs on the BE and a bit more on the FE. Thus, we recommend starting with the BE, and then moving onto the FE, but you are welcome to design your own workflow. Prioritize what is important to completing MVP and demonstrating your capabilities as a developer.


## Music Festival Organization Service

You will create a full stack application for a Music Festival Organization Service, including a Rails API and a React front end. You do *NOT* need to deploy this app.

The problem: you want to help attendees organize their personal festival schedule. There are various shows happening at the same time, and it can be overwhelming to try to remember what they're interested in seeing at a giving time. With the help of this service, they'll be better organized to make the most of their time at the festival!

**Note**: this version of the app you're building will be an "admin" view - you'll have access to all user data and their schedules. 

### Rails API

Feel free to use this [starter repo](https://github.com/turingschool-examples/rails-api-starter) with RSpec and other common gems already configured.

#### Requirements:

At a minimum, you must create:

* An endpoint to get all festival schedules
* An endpoint to get info about one user's schedule, including the show(s) involved and what user(s) is/are associated 
* An endpoint to remove a show from a specific schedule

Beyond the base requirements, include any additional endpoints you'd like, but be mindful of your time. You don't need to go overboard, consider what might be necessary to achieve MVP so that this API is easy to understand and consume by a Frontend Developer.

**Note**: There are a couple different ways you could structure your database to solve this problem. Consider the real-world implications of each one of your choices. For example, will schedules be totally customizable by a user, or will there be pre-set options a user could select based on their interest (i.e. "The Jazz & Blues Itinerary" or "The Up and Coming Artists Schedule")? 

### Data Details

Note: The below data outlines are meant to be a guide for data details you may use in the application. If you want to change or include more information please do so. The data below does not need to be a direct mapping to your database schema (i.e. there might be more tables involved). 
Keep in mind there are many ways to implement this at a database level. Just be sure to choose an option that makes sense to you and reflects how you are assuming the music festival service functioning. You can make business assumptions. Using fake data in your application is okay.

```
**Show**

- Artist
- Location
- Date
- Time      # note: you do *not* need to worry about time conflicts in a user's schedule for this MVP

**User**

- First Name
- Last Name
- Email

**Schedule**

- Title
- Date

```

-----

### Front End

Again, try to limit your total time on the FE to around 8-10 hours. Prioritize what is important to get this working and as close to MVP as possible. Please do not attempt to recreate an entire existing Music Festival's website. We're interested in seeing your ability to write clean code to solve a problem with an understanding of basic UX. We're not looking for fancy UI tricks or hacks.

### Music Festival Scheduler React App

You will create a Music Festival Scheduler app that consumes the Rails API you've just built. Feel free to use [this starter React repo](https://github.com/turingschool-examples/vite-react-starter).

### Requirements:

At a minimum, you must show:

* List of schedules (name with an image or icon)
* Detailed View of schedule (name, image or icon, date, show(s) and user(s) involved)
* The ability to remove a show from a specific schedule
* Some sort of search, filter, OR sort

Beyond the base requirements, include any additional elements you'd like, just be mindful of your time. You don't need to go overboard, just consider what might be necessary to achieve MVP so that this app is easy-to-use, information is clear, and navigation is painless. Put yourself in a user's shoes and think about what you would need (or want). The app should be usable on desktop, tablet, and mobile devices.
