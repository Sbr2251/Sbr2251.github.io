---
layout: post
title: Swadeshi-Plaza
subtitle: Flutter Full Stack iOS/Android Application
gh-repo: Sbr2251/SwadeshiApp
tags: [Flutter, Firebase, Stripe]
comments: true
---

This Project serves as an E-commerce application for a Dallas, TX Indian restaurant named Swadeshi-Plaza. The app features a fully functioning authentication service backed with google firebase authentication. The state management for the app uses Flutter’s provider architecture which changes the screen depending on the user’s authentication status. The app also features an administrative side that can view/edit incoming orders and can only be accessed through the admin login. Payments on the app are supported and processed through the Flutter Stripe library. To achieve stripe 3d secure transactions, I have used a firebase dedicated server as another form of verification to meet stripe security standards and protect customer’s billing information. Demos for both the customer and admin sides can be seen below on both an iOS simulator and an Andoird emulator.

<!-- **Apple Customer Demo** -->

<div align="center">
  <iframe width="420" height="315" src="https://www.youtube.com/embed/9ne5kMWi4KA" frameborder="0" allowfullscreen></iframe>
  <p style="margin-top: 0">Apple Customer Demo</p>
</div>

<div align="center">
  <iframe width="420" height="315" src="https://www.youtube.com/embed/tVWdnwBgJo0" frameborder="0" allowfullscreen></iframe>
  <p style="margin-top: 0">Android Admin Demo</p>
</div>

## Upcoming Changes

Version 1.0 of the application has been completed and is currently being tested and is set for a December 2021 release date on both the Apple Appstore and Google play store. Future updates will include a better search algorithm on the customer home page which will most likely use a version of the fuzzy search. Another feature that will soon be implemented is the ability to save cards in a secure way using the Stripe API to allow for faster checkouts. Other updates will also include small bug fixes to enhance the user experience.
