---
layout: post
title: iotracks
description: Designed development tools, dashboards, and end-user applications for an enterprise Internet of Things application platform. This project required me to understand advanced technical concepts that were previously out of my comfort zone.
---

[iotracks](http://www.iotracks.com)

iotracks is an Internet of Things integration platform for building enterprise applications. iotracks turns a hardware problem into a software problem by utilizing containerization and messaging; creating microservices that can be easily linked together.

<br>

**IoT Use Cases**

Developing use cases for complex integrated systems is a fun, but difficult, problem. I found it useful to think of a compelling problem to begin with, and work backwards to see what systems were in place, and what new technologies were available. From there, I had to just use my imagination to decide how they could work together to solve the problem more effectively than current solutions.

Here is an example using open seismic activity data to trigger events in an earthquake emergency for a building management system:

![earthquake](/images/earthquake.png)
*earthquake emegency*

I developed several sample use cases for two reasons. One being that IoT integration is a complex concept, and walking people through real world use cases helps illustrate what iotracks is all about. The other, is that iotracks is a small team and needed to find one compelling use case to focus on, so that we could build a sample application. After much research and validation, we settled on real time asset tracking. Asset tracking has both operations management and security uses, and is useful across multiple industries and environments.

<br>

**End Users**

Building an development platform for enterprise means multiple end users. The main users I was concerned with were:

 * Installers (IT people installing the platform and sensors)
 * Integrators (Developers building IoT apps)
 * Managers/Operations (People making business decisions)
 * People "on the floor" (Employees using the applications)

<br>

**User Interfaces**

I designed and built several interfaces for various end users with various needs.

ioAuthoring is a GUI for installers and integrators. This interface is used to provision servers, create tracks and data streams, and link microservices together to create applications.
![ioAuthoring](/images/ioauthoring.png)
*ioAuthoring UI*

ioManager is a dashboard for installers and managers. It is a place to monitor both the health of the system and the outputs of the data streams. ioManager can be used to make business decisions and to maintain your IoT ecosystem. Sensors/devices can be provisioned from ioManager.
![ioManager](/images/assettracking.png)
*ioManager UI*

End user applications can come in many shapes and sizes. This is a simple web based asset tracker installed at the iHangar. This is a responsive interface that can be left on a large screen in a central office location, and also works well on a phone or tablet for employees on the floor.
![End user applications](/images/tooltracker.png)
*end user application*

<br>

**Creation Flow**

iotracks' first users will be installers and integrators. Since we are creating and piloting the first application ourselves, I had the pleasure of documenting and optimizing our workflows first hand.

This is the general workflow of an installer:
![installer](/images/installer.png)
*installer workflow*

This is the general workflow of an integrator:
![integrator](/images/integrator.png)
*integrator workflow*

<br>

**Pilots**

The iotracks asset tracking solution is currently being piloted by [iHangar](http://www.ihangar.org), [People's Choice Hospital](http://www.peopleschoicehospital.com), and [University of Utah Health Care](http://healthcare.utah.edu/).

