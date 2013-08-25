NGO_Platform
============


A global platform (Java,HTML5,Mongo,REST,JSON,Spring) for Non-governmental organization(s) working for children - this enables the following features using mobile app (Web/native) - 

o	Help user finding the NGO(s) using location aware service (or searching the right NGO)  
o	Provide ability to each NGO to publish and communicate their area of work to users via News (Audio/Video/Pictures), Projects details, Event, Contact etc.
o	Allow NGO to run child sponsorship program and track child's progress
o	Encourage user to rate, like, share, comment to get feedback



Codebase - Platform for NGO

This repository contains prototype, PoC (Proof Of Concept), experimental code for creating an universal platform for NGO
(non governmental organizations) who works for children. 

This codebase mostly does focus on the following use cases/functional aspects - 


1) Create a collection in MongoDB to capture the basic NGO information 
   a) About us
   b) Projects
   c) Events
   d) Contact us
   e) Donate
   f) Audio/Video
   g) Social (Rate,like,comments,share etc.)
   
2) Create a  Data  layer for interacting with mongodb

3) Use Spring/REST for exposing the CRUD services

4) Create Web Mobile Application (iOS/Abdroid) to enable features

5) Create native Application (iOS/Android) to enable features
