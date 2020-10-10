---
layout: page
title: Beta Report 0.2.4
include_in_header: false
---

# Beta Report 0.2.4
This was the second test after launch. After improving on base features of the app I wanted to focus on inner workings of communities and the very first plugins. Users were tasked with the following points:

- Create account (If not already registered)
- Contact other user
- Join/Create group
- Use group chat
- Create group action
- Inside the group "Collapp Community" go to the actions tab. There you will find the an action named "Feedback for beta test". Leave Pro/Con feedback for your test there.

<br>

## Test Channels
To carry out the beta test I am using any tests channels available that allow me to distribute the app to beta testers as well as to track their response and evaluations. This does not include simple app directories/publishers. On this run I added some of my friends request changes to the Betafamily entry, due to the poor performance of the test.

<br>

|----------------+-------------------+------------------+--------------------|
| Test Channel   | Overall Followers | Submited Reports | Requested Changes |
|----------------|:-----------------:|:----------------:|:------------------:|
| ![icon](/assets/betafamily.png){:height="24px" width="24px"} [Betafamily](https://betafamily.com) | 54                | 15               | 19                 |
|----------------+-------------------+------------------+--------------------|

<br>

## Tickets by Category
The submitted reports from the test channels are broadly categorized into four major categories. This will help to understand which areas of the app need more focus and are most important for the users.

<div markdown="0" width="100%">
  <style>

  .ticketTitleContainer {
    width: 100%;
  }

  .leading {
    float: left;
  }

  .trailing {as
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

  .ui {width: 42%; background-color: #4CAF50;}
  .ux {width: 42%; background-color: #2196F3;}
  .sp {width: 0%; background-color: #9900cc;}
  .bug {width: 16%; background-color: #f44336;}
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
    <div class="skills ux"><b>8</b></div>
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
Evaluating the submitted reports gives insight into which issues are most recognized by beta testers. Most of the reports were centered around smaller missing features (grouped under UX for now) and smaller UI issues. Only a few bugs were found during the testing period. Just like in the last test only few bugs were reported.

<div class="issues">

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-mobile fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                Tab Headers
            </h3>
            <p>
                Users feel it is not intuitive to understand the different tabs on the group page, mainly on the post, event and action tab. Possible fix is just to include tab headlines.
            </p>
        </div>
    </div>

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-bug fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
              List Bug
            </h3>
            <p>
              Group preview cards show the wrong information when adding new groups to the discover list while using the app. Once reloaded the
              preview cards displayed the right information.
            </p>
        </div>
    </div>

    <div class="issue">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-bug fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                Group Counter
            </h3>
            <p>
                Joining or leaving group does not update group size counter. The group preview cards display wrong group size.
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
                Better Introduction
            </h3>
            <p>
                Some users think the onboarding screen are not sufficient at this point and need improvement. Some did not really understand what the app is about after the introduction.
            </p>
        </div>
    </div>

</div>

<br>

## Conclusion
This test run was a bit disappointing. Although a lot of users subscribed via Betafamily, most of the reports did not provide any valuable feedback. Even the most basic tasks where not commented upon and many times there was not even an indication that they finished the tasks. Seems like testers where looking for quick and easy 5 star ratings. Having said that I got valuable insights from the generated backend data and from some of my friends, who pointed out issues mainly about UI aspects of the app. Notable is that those reports that where of use, did not understand or find how to finish the last task of the test. I think that it could be of great use for future tests to introduce deep linking for the app, so that I can share URL links to resources inside of the app like posts, events and actions.
