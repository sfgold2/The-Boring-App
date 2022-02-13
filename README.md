Original App Design Project - README Template
===

# The Boring App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Mobile app for planning events that cater to the needs, budgets, and availabilities of all members of a group. We were tired of not being able to choose something to do with our friends, so we decided to take it into our own hands.

### App Evaluation
- **Category:**
    - Social media / Lifestyle
- **Mobile:**
    - Android
- **Story:**
    - It's hard thinking of something to do that fits everyone's constraints, so BoredAPI will do it instead.
- **Market:**
    - This app is available to any user of any demographic group. Users of all backgrounds are encouraged to participate and find new activities.
- **Habit:**
    - Any time friends want something to do together, The Boring app will shine!
- **Scope:**
    - We are limiting the choices to group activities, since this app is mainly focused on bringing friend groups closer together.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**


* User can enter a type of activity they are interested in and get a list of related activities in that category
* User must be able to see information about activities (price, type, accessibility, etc)
* A login screen which requires a username and password
* Users must be able to add friends to their account


**Optional Nice-to-have Stories**

* Users can filter activities by price, number of participants, type, accessibility, etc.
* Users can add activities to database
* Users can get a random activity
* Ability to see your friends' searched activities
* Users should have a profile that shows
    * Preferred activity type
    * Preferred price range

### 2. Screen Archetypes

* Login - User logs into their account using their username and password
* Register - User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information
   * Information will be stored in a database
* Main Activity - Recycleview of activities showing relevant information
* Extra
    * Profile with picture and user preferences for activities

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Friends
    * Brings you to the page showing information about your friends
    * Also where you add and remove friends
* Profile
    * Updates profile information and able to logout
* Search
    * Brings you to the page where you can search activities

**Flow Navigation** (Screen to Screen)

* Login: Username and Password fields, log in button
    * Log in: Logs user in, goes to Main
* Register: Username and Password fields, sign up button 
    * Sign Up: Creates account for user, goes to Main
* Main: List of activities with a search bar that has a Friends and Profile button

   * Activity: shows new screen with more details on that specific activity
   * Friends: shows new screen with information about your Friends
   * Search: shows new screen with detailed search options
   * Profile: shows new screen with information about your account
   * Sign out: logs user out, returns to login screen
   * Back: exits application
* Activity: Detailed view of activity
    * Back: returns to main screen
* Friends: Show a list of friends with their profile information
    * Add: Search for an user to add as friend
    * Accept: Accpet friend request
    * Remove: Remove an user from your list of friends
* Search: Text field where you can enter an activity
    * Once activity is entered, see a list of the related activities
    * Back: returns to main screen
* Profile: Show an overview of the signed-in user's profile
    * Can see their history of searches
    * Back: returns to main screen

## Wireframes

### [BONUS] Digital Wireframes & Mockups
<img src="https://i.imgur.com/XAYibub.png" width=300>
<img src="https://i.imgur.com/j7PMor3.png" width=300>
<img src="https://i.imgur.com/bALKqoz.png" width=300>
<img src="https://i.imgur.com/75vYhKK.png" width=300>
<img src="https://i.imgur.com/sETxgXw.png" width=300>
<img src="https://i.imgur.com/9Ju4hD4.png" width=300>
<img src="https://i.imgur.com/wE4ptX6.png" width=300>
### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
