---
title: Usability Testing Review
layout: page
---


### Participants
* John: A current senior at Williams College studying geosciences.  John is a member of the Williams College mens rugby team and actively participates in the Williams Outdoors Club.  He has spoken with personal aquiantences about the college search process and his experience in college throughout his Williams career.

* Randy: A current senior at Williams College studying English and economics.  Randy plays Ultimate Frisbee at Williams and is involved in an investment club on campus.  He has spoken to college applicants from his hometown on several occassions to discuss the college search process and has spoken to prospective students considering playing frisbee on campus.

* Alex: A current senior at Williams College studying economics.  Alex plays Ultimate Frisbee at Williams.  He is relatively unexperienced in speaking to prospective students about his college experience.

* Jane: A current high school senior from Massachusetts who was recently admitted to several colleges and is currently deciding where she will attend school.  She is involved in Mock Trial, speech and debate, and plays volleyball in school.  She is considering pursuing all of these interests in college.

### Analysis

For a full analysis of the first three participants and the revisions made to our paper prototype following these tests, see our [Usability Test Check In](/ut_checkin.md).

Unfortuantely, due to inclement weather, we were not able to conduct our usability test with Jane in person.  Instead, we conducted the test remotely using digital images of our paper prototype and a screen-sharing platform.  While this was different than other usability tests, we felt that we were able to gain valuable information from the test and have the participant interact with the interface effectively.  In the test, Dylan acted as facilitator, Wei as observer, and Julian as computer (he selected the appropriate image to share based on the participant's stated actions).  Because the screen-sharing platform required that Jane speak aloud the interactions that she had with the platform, we found that the participant was more encouraged to think out loud during the process than in previous tests.  This resulted in more continuous feedback throughout testing.

Because we conducted the test remotely, we were not able to fully control the environment in which Jane completed the test.  She told us that she was in a common space in her home, which we feel effectively reflects a common experience that an applicant user would have with our platform.  After completing the testing process, we asked Jane for any concluding thoughts she had on the platform and any remaining questions that she had for us.

### Critical Issues

Jane identified three key issues with our current paper prototype.

#### Log in functionality not supported.
_Severity Rating_: 4

While we present a log in option in the opening screen, we did not support its functionality.  To resolve this, we added a screen, which comes before a new users is prompted to select their user type, which allows them to create a username and password for future access.  Additionally, we added a log in screen which will direct users to their current conversations page upon the entry of their previously set username and password.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_mkprof2.png" width="250" height="400"/> <img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_login2.png" width="250" height="400"/>

#### Privacy concerns over video/audio calls.
_Severity Rating_: 3

Jane was concerned with privacy on the app.  As it is currently designed, it is not obvious what actions a user can take if another person sends a audio/video call request.  To resolve this, we add a accept/decline interface for the user.  The user can press "accept" to accept the call, or press "decline" to decline the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wl_accept.jpg" width="250" height="400"/>

#### Inability to search through potential connections list.
_Severity Rating_: 2

Users should be better able to search for people with particular attributes in their potential connections. Previously, users did not have an option to do so.  To resolve this, we added a search interface, which can be accessed when the user presses the "search" button on the page that contains the list of potential connections.

Before:

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/revised_potential_connections2.png" width="250" height="400"/>

After: 

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/wl_connections2.png" width="250" height="400"/>

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/wl_search2.png" width="250" height="400"/>

### Important Revisions
The revisions that we consider the most important include:

* Addition of back buttons.  The lack of back buttons was a critical design flaw.  Although the navigation tabs at the bottom made it clear for users how to navigate between the main pages, navigating between pages that belong to the same tab was confusing.  By adding the back button, the user is able to go back to the previous page, without having to think about how he/she got to the current page.  This makes the design more clear, and the interface easier to use.

* Separate personal profile creation pages for college applicants and current college students.  Before this revision, our interface had the same page for the two types of users.  This is a design flaw, because the two user groups have different purposes in using our product.  Whereas for the college applicants the focus is on the numerous colleges that they could be interested in, for the current college students, the focus is on their college and the applicants who might be interested in it.  Our revision reflects these considerations:  The page for college students has a text-entry field where users can enter the college they attend, whereas the page for applicants replaces this with a drop-down entry field for the user’s list of potential colleges.

* Addition of search interface.   Previously, if users had changed their interests, there was no obvious way for them to search for potential connections using the updated interests.  Also, the searches were done automatically, such that the users have no option for customized search.  In our revision, we added a search interface that allows users to perform a manual search, thereby helping them look for people with particular attributes in their potential connections.

## Current Paper Prototype

## Overview

![overview](/wl_overview.PNG)

### Share Personal Information

Upon first opening the College Connect app, users are presented with a simple welcome screen.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/new_welcome_page.png" width="250" height="400"/>

If the user has already created a College Connect profile, they will log in and be directed to their "Conversations" page:

 <img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_login2.png" width="250" height="400"/>

If this is a new user, they will select "New User" and will be directed to a screen allowing them to designate a username and a password: 

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_mkprof2.png" width="250" height="400"/>

After the user presses "done", they are redirected to a page that lets them choose their user type.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/new_select_page.png" width="250" height="400"/>

After the user selects the appropriate type, they will be directed to their personal profile screen, where they can share basic information about themselves.  The screen will be slightly different for current college students (left) and applicants (right)  This information includes their name, school (college students) or prospective schools (college applicants), class year, home town, interests, and a short personal bio.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_pp1.png" width="250" height="400"/> <img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/dm_pp2.png" width="250" height="400"/>

After they complete their profile and press the "done" button, they will be directed to this screen, which will guide them to the potential connections page.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/he4_2.png" width="250" height="400"/>

### Find Users with Similar Interests

Once the user has input their interests, they will see a list of either college or applicant students with similar interests. They can then select someone to learn more about them and other shared information. 

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/wl_connections2.png" width="250" height="400"/>

After they have selected a student, they can decide to initiate a conversation and/or learn more about others using the back button.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/potential_connection_profile.png" width="250" height="400"/>

The user can also press "search" on the list of people page for a more customized search.  

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/img/wl_search2.png" width="250" height="400"/>

### Start Conversations

The user can press the “conversation” tab to navigate to the conversation interface. This interface shows the user’s conversations with other users, order by recent messages. The user can press the tab with the person’s name to begin chatting with that person.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_1.png" width="250" height="400"/>

This interface allows the user to chat with another user. At the top-left corner, the back arrow takes the user back to the previous page. The name of the person with whom the user is chatting is displayed at the top. At the top-right corner are options for audio call and video call.  Messages are shown in the main body of the interface, with the other person’s messages on the right. At the bottom, the user can enter a message and press “send” to send.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_chat_revise.png" width="250" height="400"/>

Sent message.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_revise_1.png" width="250" height="400"/>

Interface after pressing the audio call button. Waits for the other side to accept the request. The user can press “End Call” to end the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_revise_2.png" width="250" height="400"/>

Sample audio call. The user can press “End Call” to end the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_revise_3.png" width="250" height="400"/>

Interface after pressing the audio call button. Waits for the other side to accept the request. The user can press “End Call” to end the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_4.png" width="250" height="400"/>

Sample video call. The user can press “End Call” to end the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wei_5.png" width="250" height="400"/>

The other person can choose to accept or deline the call.

<img src="https://raw.githubusercontent.com/dylan-martin/college_connect/master/wl_accept.jpg" width="250" height="400"/>

