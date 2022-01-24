# AB Framtiden Sophantering

## Table of contents
* [Introduction](#introduction)
* [Mobile app](#mobile-app)
* [Web app](#web-app)
* [Backend and database](#backend-and-database)
* [Machine learning](#machine-learning)

## Introduction
This project is a collaboration between Framtiden AB and University of Gothenburg and the purpose is to provide a system to document and analyze litter. The mobile app is mainly used by cleaners that work in different suburbs and when they are confronted with litter, their task is to take a photo of the litter in the mobile app and then send that image to the backend. The backend, with the help of a machine learning model, then predicts what types of trash objects that are present in the image and saves the image together with related metadata, which apart from trash objects also includes geographic coordinates and timestamp of when the image was taken. The data that is sent from the mobile app can then be analyzed with a web app. The web app also lets system administrators do administrative tasks, such as accepting new users to the system and documenting what actions to prevent littering have been done.

## Mobile app
Full documentation regarding the mobile app can be found in the README file in the ''mobile-app''  directory [a relative link](app/README.md). There, you can find information both regarding how to set up environment for development and how to deploy to production. The mobile app is released using Framtiden's Google Play and Apple accounts. In order for you to access the mobile app and release new versions you need to be manually added by someone that has full access. Furthermore, in order to release a new version of the mobile app to App Store, you need to have a Mac. CTK has Mac computers that you can borrow.


## Web app

## Backend and database

## Machine learning
