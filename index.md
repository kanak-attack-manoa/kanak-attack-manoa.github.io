---
title: Kanak Attack Manoa
---

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Example enhancements](#example-enhancements)
* [Team](#team)

## Overview

Kanak Attack is an app designed for Manoa campus. It gives the ability to vendors to maintain an active menu update special items and list items as in stock or sold out. The items can be by ingredients, cuisine or other things. The user will have the ability to select what type of cuisine they would like. On top of this they will be able to filter food items by ingredients etc... The overall purpose of this app is to display available items around campus so the user can make the best choice of food for their personal interest.

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

It also provides code that implements a variety of useful design concepts, including:

* We will have three user roles (vendor, consumer, and admin) in which the vendors can update the app to include available menu options, changes or specials.
* Top-level index pages (Favorite foods, favorite ingredients, and favorite cuisine) that show how to manipulate these collections in various ways.
* Initialization code to define default Profiles, Favorites, and Cuisines and relations between them.
* A simple Filter page to illustrate how to perform simple queries on the database and display the results.
* Use of Meteor Methods to illustrate how to simplify implementation of multiple collection updates.
* Use of indexes to enforce uniqueness of certain fields in the collections, enabling them to serve as primary keys.
* Authentication using the built-in Meteor accounts package along with Sign Up and Sign In pages.
* Authorization examples: certain pages are public (Profiles, Foods, Places), while other pages require login (Favorites, Filter).
* Use of Meteor Assets to initialize the database (helpful when initialization exceeds settings file size limits).

## User Guide

This will contain a user guide for kanak attack manoa when we get there...

### Landing Page

When arriving at the landing page, the user has the option to login to an existing account or create an account. We will aslo display some general information about the app in case the user is contemplating downloading it.


### Index pages (Places, Foods, Profiles)

Kanak Attack provides three public pages that present the contents of the database organized in various ways.

The Profiles page shows all the current defined profiles and their associated Foods and Places:

[comment]: <> (![]&#40;images/profiles-page.png&#41;)

The Places page shows all of the currently defined Places and their associated Profiles and Interests:


Finally, the Foods page shows all the currently defined Foods, and their associated Places and Food Type:

[comment]: <> (![]&#40;images/interests-page.png&#41;)


### Sign in and sign up

Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:

[comment]: <> (![]&#40;images/signin-page.png&#41;)

Alternatively, you can select "Sign up" to go to the following page and register as a new user:

[comment]: <> (![]&#40;images/signup-page.png&#41;)

### Home page

After logging in, you are taken to the home page, which presents a form where you can complete and/or update your personal profile as a vendor or a consumer:

[comment]: <> (![]&#40;images/home-page.png&#41;)

### Add Foods

Once vendor is logged in, you can define new menu items with the Add MenuItem page:

[comment]: <> (![]&#40;images/add-project-page.png&#41;)


### Filter page

The Filter page provides the ability to query the database and display the results in the page. In this case, the query displays all of the MenuItems that match one or more of the specified Interest(s) (i.e. ingredients, type, etc..).

[comment]: <> (![]&#40;images/filter-page.png&#41;)

## Community Feedback

We are undecided on how or if we want to implement community feedback on a vendor basis or on the application basis or both


