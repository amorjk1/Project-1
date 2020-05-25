# Sprint 1

## Overview

Our group started pretty good as a team as we already know each other, Nick made our theme for the website and we felt that we were quite a head than the others. Although Nick kinda over did our website, it helped us build stronger foundation for the website.

After showing our working product to Hymie, he was impressed and complimented our group as we were the first one who he thinks had the best layout for the project.

## Objective

I am quite happy with the work I have put into this sprint as I have achieved my goal. I finished the user story assigned to me.

![user](https://i.imgur.com/fResCBv.png)

## What worked well
  * Communication
  * Everything is working as planned
  * Most of the member's local environment are working

## What could be improved
  * Resolve local environment issues faster
  * Balance workload

## What were the barriers
  * Local environment issues


## Things to be done
  * Have another meeting with the customer (Hymie)
  
# Sprint 2



## Overview

After our meeting with Hymie, he told us that he wants to be able for the other user to delete other users without asking the admin because he wants it to be "Community Driven" website. We try to explain it to him that it would be bad for the website because anyone can just delete other accounts. He said that he want to see it first, even though our team doesn't agree with him; we have to follow because that is the customer wants and it is ethical to just follow what the customer wants.

He also mentioned that he wants the log in page to pop out like some other website. Twitch website for example. didn't managed to do it in time though so this user story went into our backlog for the next sprint.

![example](https://i.imgur.com/73a30JR.png "Login pop up example")

## Objective

My objective on this sprint went pretty good as I fixed the issue I had when I log in that says "Syntax error or access violation: 1071 Specified key was too long; max key length is 767 bytes (SQL: alter table 'users' add unique 'users_email_unique'('email'))"

I fixed it by putting the code below on my AppServiceProvider.php under app/providers.

![fixerror](https://i.imgur.com/a0DZWN4.png)

I also managed to learn more about seeding so that I don't have to populate my database manually. I just follow this video from [YouTube](https://youtu.be/xtFKfSKlKW0?t=242) where it teaches how to use seeding correctly.

## What worked well
 * Communication
 * Had some problems but managed to adapt with that problem easily
 * Everyone's local environment are now working smoothly

## What could be improved
 * Follow github work flow

## What were the barriers
 * Time management - this is due to members not doing their work on time.
 * Functionality issues

## Things to be done
 * Do more scrums

# Sprint 3


## Overview

This is where absence from classes became a huge impact as one of our member stop turning up to classes, It made it difficult for us to do some part of our project as we we're still waiting for that member to finish his part so that we can move on to our project but since that member doesn't turn up to class or even replying to our messages. It became really hard to progress on our project.

Our previous meeting with the client went quite badly as it was just me and Yan who attended the meeting even though everyone said they're all coming in. My laptop was broken at that time so I couldn't show my work to our client on time(I had to use school computer and install composer and update it infront of the customer). We managed to show our progress to our client and client was happy in the end of the meeting.

## Objective

This sprint, I learned more about migrations for our project, I made migration for roles and user roles. 

![roles](https://i.imgur.com/MqnMjaR.png)
roles

![userRoles](https://i.imgur.com/FNKub0V.png)

user roles

As I mentioned before, Communications are probably our biggest problem for this sprint. So I realized that I had to step up and take over as a leader of the group, I call for an emergency meeting so that we can get our things together and made sure that everyone is doing their part and up to date of what is happening with our project and within our group.

![emergency](https://i.imgur.com/q0HhqUD.png)

## What worked well
 * Individual task was done on time
 * Customer is happy
 * Reviewed the codes before showing it to the customer

## What could be improved
 * Team communication
 * Laravel skill
 * Initiative - I need to ask members to do their job quickly or else they will only do it just before our meeting with the client and sometimes it ends up rushing the project and looks really bad.

## What were the barriers
 * Communications

## Things to be done
 * Talk to teammates more often. Talk more about the project and try to avoid irrelevant topics during the scrum meeting. 

# Sprint 4

## Overview
This sprint was short because it was one week away from the holiday and everyone was just looking forward for it. We didn't really do much as a group on that first week of the sprint, instead we focused on doing our own portfolio. Yan helped me set up a page for my own portfolio.

## Objective

## What worked well
 * Learned more in depth about Github such as merging branches, use of "git remote update"

## What could be improved
 * Not Available

## What were the barriers
 * Not Available

## Things to be done
 * Continue working on the user stories given by the customer.

# Sprint 5

## Overview

As for our last sprint, our customer (Hymie) asked us to be able to disable user without deleting its actualy account from the database, they assigned that task to me and I accepted it gladly even though I have no idea how to approach this. Did some research on how to disable users and stumble accross this [tutorial](https://laraveldaily.com/how-to-ban-suspend-users-in-laravel-project/) and helped me do this task.

## Objective

My objective this sprint went quite well, I have finished all the task that was assigned to me and managed to fix the bug that Martin issued. 

![bugMartin](https://i.imgur.com/UrLpnNN.png)

Bug that Martin addressed to us

![fixedissue](https://i.imgur.com/xXw05Am.png)

Solution

## What worked well
 * Presentation went really good, No errors on our live server at all.

## What could be improved
 * The disable user should be implemented by three users instead of just the admin.

## What were the barriers
 * Time management - this is due to all of my papers are having pretty much the same deadline as the others.

## Things to be done
 * Not Available
