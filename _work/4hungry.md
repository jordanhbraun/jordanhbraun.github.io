---
layout: post
title: Hungry
description: Research, prototyping, and design strategy for a food delivery app. I created interactive prototypes that were used to test with real users.
---

[hungryishere.com](http://www.hungryishere.com)

Hungry was a research and prototyping contract that was completed in a 2 week sprint. The client came to me with some rough ideas about using images rather than names when choosing food for delivery/take-out.

Through user research, I discovered that many people order delivery/take-out under very specific circumstances. The circumstances usually involve a late night, a short attention span, and a user who is easily frustrated. Often, this scenario arrives as the result of a work binge or inebriation.

Several users indicated that they don’t want to make decisions, they just want to eat food. I designed a solution for this use case. Simplicity was the strongest focus, stripping the food ordering process down to it’s bare minimum. User research indicated an almost primal decision making process, so I designed an app for that mindset. I shortened the user flow down to 2 main interactions: choosing a dish and paying.

<br>

**Interviews**

Several people were interviewed, some with a usable prototype and some without. People in their late 20’s through early 30’s were targeted.  

A majority of people indicated that ordering out was a last resort, reserved for times of extreme hunger where cooking was not an option. Often, this occurred very late after a night out or finishing work late. When in this situation, choice anxiety often sets in. Users do not want to make decisions. When asked about other delivery/take-out solutions, many people mentioned getting frustrated and overwhelmed by the number of options they were presented with with. One user said, “Honestly, I would rather someone just picked for me.” another user admitted, “I have wasted an embarrassingly large amount of time debating with myself.” 

Users want food to be on its way as soon as possible, and they don’t seem to be incredibly concerned with what that food is. Most people mentioned that as they get hungrier they care less about health and quality and more about speed and whether or not the food with satiate their hunger. 

When presented with the usable prototype, people were surprised and delighted by how quick the process was. Many people mentioned that they become hungry and angry, aka “hangry,” and have very little patience at that point.  When users are frustrated and cranky, there is always an opportunity to delight. In this application, speed and simplicity is what will delight the user, not options and customization.

<br>

**Customer Journey Map**

A customer journey map is a visualization tool used to better understand a user’s actions/environment (yellow) and emotions/feelings (pink).  Mapping the customer’s journey helps to identify opportunities (blue) to design special solutions for our customer’s during their experience. 

![Customer Journey Map](/images/customerjourneymap.png)

<br>

**User Flow**

The key to success in our user flow is simplicity.  We should ignore edge cases in favor of making the experience cleaner for our main use cases. Combining the 2 steps (choosing a restaurant and choosing a dish) is a distinct advantage over competitors. First time users will have to enter payment info. Keep in mind that they also would have had to download the app, so we are already asking a lot from them. First time users will need some sort of incentive such as a promo code. If we can get them to save their payment info, we can really shine the next time they use the app.

We know from the customer journey map that users are happiest when they have just eaten. This is an ideal time to prompt them for a review, possibly time it for 1 hour after order is placed, or 15 minutes after delivery if we have that data.

Logged in user flow:
![Logged in User](/images/loggedinuserflow.png)

First time user flow:
![First Time User](/images/firsttimeuserflow.png)

<br>

**Interface**

The main screen needed to be very simple, as an easily frustrated user is prone to choice anxiety. The “mehh” button was a joke, but tested very well as users are typically fairly apathetic about the choices.

![Main Screen](/images/sampledish.png)


The add-ons screen gives the user a few simple customization options while still not giving them choice anxiety. This step helps cover a significant number of edge cases.

![Options](/images/sampleaddons.png)


The confirmation and payments screen is incredibly important. There is a lot of opportunity for frustration here, and also a lot of opportunity to delight the user. Payment needs to be incredibly simple, without constantly switching form fields. Location should be prefilled using GPS and display the address clearly. The credit card field should accept the credit card number, expiration date, and cvv number dynamically in one text box.

![Confirmation](/images/sampleconfirmation.png)

<br>

**Current State**

This app is currently under development, and will soon be available on both iOS and Android devices. I will update this page and tweet about it as soon as the app is released.

