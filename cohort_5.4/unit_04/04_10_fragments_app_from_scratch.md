# Fragments "App From Scratch"

## Objectives
* Fellows will attempt to follow steps within a mock coding challenge
* Fellows will demonstrate this step in front of the class with the instructor

## Resources
* [RecyclerView Review](https://github.com/joinpursuit/Pursuit-Core-Android/blob/master/cohort_5.4/unit_02/02_20_recyclerview_review.md) 
* [Retrofit and JSON](https://github.com/joinpursuit/Pursuit-Core-Android/blob/master/cohort_5.4/unit_03/03_12_retrofit_and_json.md)
* [Fragments](https://github.com/joinpursuit/Pursuit-Core-Android/blob/master/cohort_5.4/unit_04/04_04_fragments_and_fragment_transactions.md)

# Lecture

Today we will build an "App From Scratch", for time. The goal of today's lesson is to rebuild an app from scratch that replicates the requirements of the Unit 03 Assessment, but with Fragments:
* Connect to JSON endpoint using Retrofit
* Display list within a RecyclerView
* Pass data with a click event to a new Activity
* Display that data within a Fragment

The JSON Endpoint we will be working with today [can be found here](https://raw.githubusercontent.com/JDVila/storybook/master/planets.json). First you will be asked to complete a task within a certain block of time. Then, once the time alloted has ended, a fellow will be randomly selected by the instructor, and asked to complete the task in front of the class.

We are tasked to complete this challenge within 3 (three) hours.

The tasks are as follows:
### Open a new Android Studio Project (5 Minutes)
Open up a new Android Studio Project, using an Empty Activity

### Make data model class(es) based on the JSON Endpoint (10 Minutes)
Evaluate the JSON, then form one or more data model classes based on the JSON

### Create Singleton Class for Retrofit Instance (10 Minutes)
Create a Singleton class using the Static Factory Method design pattern, to contain a unique single instance of the Retrofit class.

### Create Retrofit Service Interface (15 Minutes)
Create an Interface for a Retrofit service, adding methods for creating get requests that include the path that comes after the base url.

### Make a Retrofit Get Request, then use the Response (15 Minutes)
Make a request to the JSON endpoint, then receive the data from the response body.

### Subclass a RecyclerView ViewHolder Class, with corresponding ItemView XML Layout (15 Minutes)
Create a ViewHolder class, which references the views declared in an ItemView XML Layout.

### Subclass a RecyclerView Adapter Class (15 Minutes)
Create an Adapter class, which overrides all inherited methods, and binds the list data passed to it to the appropriate views as needed.

### Add a RecyclerView that fills the screen, and populate it with data from the Retrofit `onResponse()` callback (10 Minutes)
Add a RecyclerView to your activity, then pass a list of data to it, the list received from the Retrofit Response.

### Make a Display Activity (10 Minutes)
Make a new activity that displays the data contained in an instance of the data model.

### When a List Tile is clicked, it should pass data to, and move to, the Display Activity (15 Minutes)
Make the itemview clickable, then fire off an intent with intent extras that moves to the display activity

### Host a Fragment inside of the Display Activity (20 Minutes)
Host a Fragment inside of Display Activity that displays the data passed from the previous Activity, using a Static Factory Method.
Take the three values received from the sending intent, and display them in views within the Display Activity's Fragment.

## Exercises
Push this project to Github, then submit the link to the exercises page on the cnvas calendar for today's date.
