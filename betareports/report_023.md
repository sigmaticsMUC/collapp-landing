---
layout: page
title: Beta Report 0.2.3
include_in_header: false
---

# Beta Report 0.2.3
This was the initial test run after transitioning to flutter and releasing an open beta version to various app stores (mainly playstore). The intention was to
get feedback for the fundamental app functionalities and to evaluate first impressions. For that reason the test focused on the most basic app functions, which are a prerequisite for further development of core features. User were tasked with the following points:

- Register new account
- Join or create new group
- Create post or event inside the "Collapp Community" group
- Create comments on already available posts or events
- Send contact requests to other users

<br>

## Test Channels
To carry out the beta test I am using any tests channels available that allow me to distribute the app to beta testers as well as to track their response and evaluations. This does not include simple app directories/publishers.

<br>

|----------------+-------------------+------------------+--------------------|
| Test Channel   | Overall Followers | Submited Reports | Requested Features |
|----------------|:-----------------:|:----------------:|:------------------:|
| ![icon](/assets/betafamily.png){:height="24px" width="24px"} [Betafamily](https://betafamily.com) | 96                | 21               | 27                 |
|----------------+-------------------+------------------+--------------------|

<br>

## Tickets by Category
The submited reports from the test channels are broadly categorized into four major categories. This will help to undertand which areas of the app need more focus and are most important for the users right now.

<div markdown="0" width="100%">
  <style>

  .ticketTitleContainer {
    width: 100%;
  }

  .leading {
    float: left;
  }

  .trailing {
    height: 100%;
    padding-top: 1%;
    vertical-align: middle;
  }

  .ccontainer {
    width: 100%;
  }

  .skills {
    text-align: right;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    color: white;
  }

  .ui {width: 30%; background-color: #4CAF50;}
  .ux {width: 51%; background-color: #2196F3;}
  .sp {width: 8%; background-color: #9900cc;}
  .bug {width: 11%; background-color: #f44336;}
  </style>

  <div class="ticketTitleContainer">
    <div class="leading">
      <span class="fa-stack fa-1x">
          <i class="iconBack fas fa-circle fa-stack-2x"></i>
          <i class="iconTop fas fa-mobile fa-stack-1x"></i>
      </span>
    </div>
    <div class="trailing">
      <p><b>User Interface</b></p>
    </div>
  </div>
  <div class="ccontainer">
    <div class="skills ui"><b>8</b></div>
  </div>
  <br>

  <div class="ticketTitleContainer">
    <div class="leading">
      <span class="fa-stack fa-1x">
          <i class="iconBack fas fa-circle fa-stack-2x"></i>
          <i class="iconTop fas fa-user fa-stack-1x"></i>
      </span>
    </div>
    <div class="trailing">
      <p><b>User Experience</b></p>
    </div>
  </div>
  <div class="ccontainer">
    <div class="skills ux"><b>14</b></div>
  </div>
  <br>

  <div class="ticketTitleContainer">
    <div class="leading">
      <span class="fa-stack fa-1x">
          <i class="iconBack fas fa-circle fa-stack-2x"></i>
          <i class="iconTop fas fa-bolt fa-stack-1x"></i>
      </span>
    </div>
    <div class="trailing">
      <p><b>Stability & Performance</b></p>
    </div>
  </div>
  <div class="ccontainer">
    <div class="skills sp"><b>2</b></div>
  </div>
  <br>

  <div class="ticketTitleContainer">
    <div class="leading">
      <span class="fa-stack fa-1x">
          <i class="iconBack fas fa-circle fa-stack-2x"></i>
          <i class="iconTop fas fa-bug fa-stack-1x"></i>
      </span>
    </div>
    <div class="trailing">
      <p><b>Bugs</b></p>
    </div>
  </div>
  <div class="ccontainer">
    <div class="skills bug"><b>3</b></div>
  </div>
  <br>

</div>

## Major Issues
Evaluating the submited reports gives insight into which issues are most recognized by beta testers. Most of the reports where centered around friction created through bad UX. Only a few bugs where found during the testing period. The uncovered bugs were mostly minor issues which could be resolved fast without any changes to how the app is structured. The biggest problem I faced from using the app was when loading more content than the average beta tester did. I experienced stability problems due to concurrent downloads of multiple images of user profiles and groups.

<div class="issues">

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-bolt fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                App crashes
            </h3>
            <p>
                The app crashed during various use cases. The problem seems that multiple concurrent downloads of uncached images resulted in memory shortages
            </p>
        </div>
    </div>

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-user fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                Auto submit textfields and focus issue
            </h3>
            <p>
                Text input from textfield was only submited after clicking the 'submit' action button on the device keyboard. Also textfields tended to automatically grab the focus after closing dialogs which resulted in that the keyboard poped up.
            </p>
        </div>
    </div>

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-mobile fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                Show new elements first
            </h3>
            <p>
                When creating posts, events, actions or media withing a group they appear at the bottom of the list initially. After reloading the app the list appeared in right order.
            </p>
        </div>
    </div>

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-user fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                Remove description requirements
            </h3>
            <p>
                Remove length requirements on all creation pages. This includes titels and descriptions when creating groups, posts, events and actions.
            </p>
        </div>
    </div>

</div>

<br>

## Conclusion
This test run gave ma alot of insight into which parts of the app did not feel intuitive to the user. Users could not find the 'contact other user' function on user profiles. I am suspicios regarding the lack of submited bugs. It may indicate that the testing was not "deep" enough, which stems from the defined tasks. Those could be completed fast and easy (most of them). Future test runs need to focus more on user interactions between users and communities to uncover "real world" issues that might occur during actual use of the app.
