# Real-Time Subway App

Exercise 4A for the [@ThisIsMetis](https://github.com/thisismetis) UX & Front-End Development Fall 2014 BootCamp.

## Project Overview

The MTA has contracted my team to produce a one-screen mobile app with the following features:

* Real-time status of the subway.
* View the next 3 trains at a station on at least 2 subway lines.
* Text-based alert messages within the app.
* Application should work offline.

## Native or Web-Based?

Our team discussed whether the app should be native or web-based. We ultimately decided that to best meet the needs of a user, we required access to specific functionality on the mobile device, and therefore required a native app. This functionality includes:

* **Geo-location (GPS):** Allows us to locate the user to display nearby subway stations.
* **Push Notifications:** Allows us to alert users to service changes and other announcements, even when the app is not open and running.
* **Offline Access:** Allows us to cache the app results so the user can continue to access the information while they have no network connection, for example, when they are in the subway.

## User Needs, Context, and Constraints

While using our app, the user is looking to serve a variety of needs depending on the context of using the app and its apparent constraints.

### Needs

The user needs to know:

* Where the nearest train stations are located.
* When the next train is arriving.
* Whether there are any service delays that affect these arrival times.

### Context

The user may use the app:

* Before leaving home, while planning a trip.
* In transit to the subway with a connection.
* In the subway with no connection.

### Constraints

* The user may not have a network connection at all times. Therefore, they geo-location and push notifications may not work properly.
* The mobile screen is particularly small and may make it difficult to view a map.

## Design

As a team, we discussed what to place in the wireframes, and visually designed the application individually.
