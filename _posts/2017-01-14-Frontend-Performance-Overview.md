---
layout: post
title: Frontend Performance - Overview - Part 1(Draft)
bigimg: /img/2.png
categories: performance
tags: Frontend Performaance
comments: true
analytics: true
---

###### References
- High performace Mobile web - by Maximilano Firtman
- Designing for Performance - by Lara Callender Hogan.
- Mobile Web Performance optimization - by S.Niranga

# Web Performance is a user experience


### User Perception

- Immediate feedback < 100ms
- Keeping user's flow of thoughts < 1s
- Beyond 1000 milliseconds (1 second), users lose focus on the task they are performing.
- User expects to load pages in 2s, after 3s 40% of users will abandon your site.

### Impacts
- Impacts your brand, 88% of online customers are less likely to return to a site after a bad experience
[case study](www.mcrinc.com/Documents/Newsletters/201110_why_web_performance_matters.pdf)
- Returning users - not just for ecommerce sites, users will return to faster sites. 
[case study by google](https://research.googleblog.com/2009/06/speed-maters.html)
- Search engine rankings


#### RAIL [by Google](https://developers.google.com/web/fundamentals/performance/rail)

- User-centric performance model that breaks down the user's experience into key actions
![alt text][RAIL]

[RAIL]:../../assets/images/perf-frontend/rail.png

- Response: respond in under 50ms
- Animation: produce a frame in 10ms
- Idle: maximize idle time
- Load: deliver content and become interactive in under 5 seconds

to acheive the above we need to understand few metrics and concepts ,

##### Three key areas for Mobile Web performance
- Speed
- Battery
- Data

##### Hardware
- Mobile devices have less RAM and CPU when compared to desktop devices, though in future it might me vice versa
- CPU - Parsing , rendering and execution happens
- Memory - Where the dom tree and temp data are stored
- GPU - Some rendering happens. 

###### Mobile Networks
###### 3g
![alt text][3g]

[3g]:{{ site.baseurl }}assets/images/perf-frontend/3g.png

###### 4g
![alt text][4g]

[4g]:{{ site.baseurl }}assets/images/perf-frontend/4g.png
