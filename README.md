# Dumbull: the Tinder of studying

Hackabull 2023 submission

## A fully functional app for both Andriod and iOS pairing students into study groups based on classes they are taking.

## Inspiration:

As procrastinator, our team understand the importance of study groups to keep ourself accountable and get on top of the materials. But we realized that it is hard to find a study group in a class you need. That is why we decided to implement an app that has a swipe function (inspired by Tinder) using React Native and GraphQL for the students to have fun while looking for their study groups.Our database managed using MongoDB on Google Cloud.

## How Dumbull comes to life:

First, we define the app requirements including features and functionalities that will be included in the app. The main feature of Dumbull is the swipe function inspired by Tinder, which requires a backend system to store user data and preferences. We write a matching algorithm that analyzes user preferences as tags and recommends potential matches based on their swipes. This feature will require additional backend development to handle the data processing and matching logic.

Second, we set up the backend using Javascript and GraphQL. GraphQL is a query language that allows us to define the data we need from your APIs, and MongoDB will store the data. In the end, we integrate the backend with the front end using heroku, a cloud platform that enables developers to build, run, and scale applications.

Then, we go on to build the login page once the backend is set up. The login page is built with Google Authentication, and the app is connected a MongoDB database for data storage, which make sure the login page is user-friendly and secure.

## Challenges on the way:

Our team original plan was to use PostgreSQL as the database, but as our we progresses, we figured that a relational database is not suitable for our development path. So we have to swift learn MongoDB to implement the database in time for the backend to build the API.

As we don't have much previous experience coding backend application, our backend ran into a lot of problems connecting the database to the backend.

## Proud (Dum)bulls moment!

We develop this app from scratch, with only some reference to the Tinder App for the swipe function. Making the app cross-flatform is definitely a huge bet for our team and we are proud that we can make the app up and running. Our team doesn't have much experience in implementing the backend and coding API, but we manage to code the entire API from the ground up. We decided to switch database in the middle of developing this app so our database person learn MongoDB in a very short amount of time.

## Dumbulls: From Hackabull and beyond

We plan on expanding our app functionality with a chat function and a When2Meet in each cards, so when the students are added to a group, they can decided on a specific time which they can have the study group. This will immensely improve the users' experience on the app.
