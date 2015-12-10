---
title: _phil: Copy of CC Epic 08 - Students performing assignments (with ConvertToMarkdown script)
layout: post
author: philschatz
permalink: /_phil:-copy-of-cc-epic-08---students-performing-assignments-(with-converttomarkdown-script)/
source-id: 1iSk08hW2rd793xhcSDg_qUVoVjQvc4sBHY6w3Ik7tVA
published: true
---
CC Epic 08 - Students performing assignments   [Other CC Epics](https://docs.google.com/document/d/19Uj6OXQqli7taJT3DitFHNdRSni3dgNv0DM6Xy_8c20/edit#)

**INSTRUCTIONS FOR MAKING CHANGES**

1. Click to the below story where the update needs to occur. 

2. Insert the update bracketed with **<NEW>**   **</NEW>** in the Decomposition section.

3. Select the bracketed update and insert a comment notifying at least [+nvw1@rice.edu](mailto:+nvw1@rice.edu) [+kef@rice.edu](mailto:+kef@rice.edu) for it to be processed. 

**TABLE OF CONTENTS**

[[TOC]]

	**<NEW>** 

	(Unnumbered) As a student, I can report problems with the CC questions

**</NEW>**

<new > As a student looking at My Progress and I click a module, and when I'm in the module, I want to see what module I?m in and be able to click out to that webview of that module </New>

**EPIC RESOURCES**

# COMMON BEHAVIORS

 

* Once a student answers a single core question from the module that the concept coach is inside, this module is added to the student's history **for spaced practice **purposes. 

# MOCKUP FOR STORIES

 [http://3lwsnp.axshare.com/#p=cc_page_module](http://3lwsnp.axshare.com/#p=cc_page_module) 

##  **<NEW>**   For Doomsday Change request

Fix navigation problems in the student concept coach experience.

MOCKUP: [http://3lwsnp.axshare.com/#p=student_modal_doomsday_changes](http://3lwsnp.axshare.com/#p=student_modal_doomsday_changes) 

1. Move CC title/nav thing to be a "Go to ? link", make blue, it goes to the reading that goes with the concept coach questions that are showing.

2. Change Back to Book to CLOSE, make blue

3. Remove "Exercise" nav -> If in My Progress can click the link there. 

4. Change Review to Summary (Review sounds like going to content).

PIVOTAL: [https://www.pivotaltracker.com/story/show/109541058](https://www.pivotaltracker.com/story/show/109541058)  

![image alt text]({{ site.url }}/public/lFQqcjyFtTL4hLS9aOPRg_img_0.png)

**</NEW>**

<table>
  <tr>
    <td>CC1.08.001    As Tutor, give authenticated and enrolled students their concept coach work for the specified collection/page

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
http://3lwsnp.axshare.com/#p=cc_page_module_-_initial  

BEHAVIOR
 <NEW>
WIP: Choosing concept coach question candidates from the current page: 
when you import the concept coach book into Tutor, the exercises are mapped to Pools (which live in a Page) by module ID
then when assigning a concept coach, we go module UUID -> Page -> Pool -> exercises
LO's are used for other operations, like content updates
We need a ticket to make this algorithm into a napkin note. 
 </NEW>

DECOMPOSITION NOTES

As Tutor, give authenticated and enrolled students their concept coach work for the specified collection / page
BE:  status: needs coding
Stub API endpoint taking CNX UUID and returning CC Task (4 hrs)
Complete API endpoint taking CNX UUID and returning CC Task (16 hrs)
Look up existing task if already made; if not, use the CC assistant to create one
Include Errors paths:
Not in a CC course with this CNX UUID
FE: Status: needs coding, pending UX feedback when student not in the course
code widget to ask for list of exercises given cnx uuid (8hrs) status: needs coding
handle error if student is not in a course for this cnx uuid (8hrs)

</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Status</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.001</td>
    <td>done</td>
    <td>BE</td>
    <td>Stub API endpoint taking CNX UUID and returning CC Task</td>
    <td>jp</td>
    <td>4 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.q8gjc6tnrzvw</td>
  </tr>
  <tr>
    <td>cc1.08.001</td>
    <td>done</td>
    <td>BE</td>
    <td>Complete API endpoint taking CNX UUID and returning CC Task</td>
    <td>jp</td>
    <td>16 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.q8gjc6tnrzvw</td>
  </tr>
  <tr>
    <td>cc1.08.001</td>
    <td></td>
    <td>FE</td>
    <td>code widget to ask for list of exercises given cnx uuid</td>
    <td>phil schatz</td>
    <td>8 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.q8gjc6tnrzvw</td>
  </tr>
  <tr>
    <td>cc1.08.001</td>
    <td></td>
    <td>FE</td>
    <td>handle error if student is not in a course for this cnx uuid</td>
    <td>phil schatz</td>
    <td>8 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.q8gjc6tnrzvw</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>napkin note creation</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.002    As a student, I answer a question inside concept coach

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
http://3lwsnp.axshare.com/#p=cc_page_module
http://3lwsnp.axshare.com/#p=cc_page_module_-_modal

BEHAVIOR
<new> In Concept Coach, there will be no option to skip questions. It is a small number, and not allowing skipping gives us the most flexibility for the algorithms to create and add problems.
Once a question has been seen, it never changes, even if the student does not work the problem.
Spaced Practice Decision: Once a student answers a single core question from the module that the concept coach is inside, this module is added to the student's history for spaced practice purposes. </new>


DECOMPOSITION NOTES

As a student, I answer a question inside concept coach
BE: 
No work
FE: 
Show accordion of questions (8hrs) status: needs coding
refactor Exercise rendering out of Tutor-js (24hrs)status: needed coding
pull Exercise store out of tutor-js (16hrs) status: needed coding
<new> Status: needs design, decomp, pending overlay discussion
Tutor needs to display exercises that have 2 to 7 answer choices without breaking. KEF: The reason is that W&N has delivered questions for Concept Coach with between 2 and 7 answer choices.
FE: investigate?p
</new>
</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.002</td>
    <td></td>
    <td>FE</td>
    <td>Show accordion of questions</td>
    <td>phil schatz</td>
    <td>8 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.k0eo62bdpo27</td>
  </tr>
  <tr>
    <td>cc1.08.002</td>
    <td>done</td>
    <td>FE</td>
    <td>refactor Exercise rendering out of Tutor-js</td>
    <td>phil schatz</td>
    <td>24 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.k0eo62bdpo27</td>
  </tr>
  <tr>
    <td>cc1.08.002</td>
    <td></td>
    <td>FE</td>
    <td>pull Exercise store out of tutor-js</td>
    <td>phil schatz</td>
    <td>16 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.k0eo62bdpo27</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>BE</td>
    <td>Modfiying spaced practice for new behavior- Once a student answers a single core question from the module that the concept coach is inside, this module is added to the student's history for spaced practice purposes</td>
    <td>Kevin</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.003    As a student, I see immediate feedback for questions answered

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<NEW> Decision: BE to send both detailed solution and answer-level feedback. 
Decision: When we have both choice level and detailed solutions, show the choice level feedback. If we ever have only choice level feedback, then show that, of course.
Needs Decision: When we have only a detailed solution, UX to decide how to handle this cases using the analysis examples below to help think through this.  Since the detailed solution often just restates the correct answer, we might want to indicate it differently. 
Resource: Sample questions and detailed solutions for Econ, Sociology, A&P (delivered to date). 
</NEW>

DECOMPOSITION NOTES

As a student, I see immediate feedback for questions answered
Correct/incorrect. Note that the concept coach exercises may two to seven different choices.
Provide answer feedback per question if available. Note that the concept coach exercises may not have choice-specific feedback. If it does not have that, there will be a detailed solution that could be provided as the feedback. Please see sample questions with detailed solutions and choice-level feedback (linked below)
BE: status: needs coding
Make sure that CC exercises give immediate feedback. (4 hrs)
Spike - see if OX Exercises has an API for returning the detailed solution; if not write a card for adding it; (1 hrs)
Modify content import to import exercise detailed solutions (pending availability of that API) (4 hrs)
Modify exercise response to include detailed solution, if available, when feedback is allowed to be given (4 hrs).  
FE:
Add detailed solution to tutor Exercises (8hrs) status: needs coding
Show both individual feedback and detailed solution when available
Content QA: QA detailed solution for all existing tutor exercises (not just CC)

<new>  Needs:  Decomp, UX mockup review
Tutor needs to fall back to detail solution when there is not choice-specific feedback. KEF: Analysis of W&N delivered assessments revealed that not all CC questions have choice-specific feedback. When they do NOT have choice-specific feedback, they DO have detailed-solution so we can use that instead.
Sample questions / detailed solutions / choice-level feedback for Economics, Sociology, and A&P (these have been delivered so far). Please review column B (comments) -- this shows what we can expect to see. Because of the way the content was developed -- some questions were developed from scratch; others were picked up from the books and re-tagged/re-used at lower cost -- there are some idiosyncrasies that may drive this decision.
UX - need mockup (est 1hr)
FE - pending mockup (est)
</new></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.003</td>
    <td>done</td>
    <td>BE</td>
    <td>Make sure that CC exercises give immediate feedback</td>
    <td>jp</td>
    <td>4 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.nxrunz8foi4m</td>
  </tr>
  <tr>
    <td>cc1.08.003</td>
    <td>done</td>
    <td>BE</td>
    <td>Spike - see if OX Exercises has an API for returning the detailed solution; if not write a card for adding it</td>
    <td>jp</td>
    <td>1 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.nxrunz8foi4m</td>
  </tr>
  <tr>
    <td>cc1.08.003</td>
    <td>done</td>
    <td>BE</td>
    <td>Modify content import to import exercise detailed solutions (pending availability of that API)</td>
    <td>jp</td>
    <td>4 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.nxrunz8foi4m</td>
  </tr>
  <tr>
    <td>cc1.08.003</td>
    <td>done</td>
    <td>BE</td>
    <td>Modify exercise response to include detailed solution, if available, when feedback is allowed to be given</td>
    <td>jp</td>
    <td>4 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.nxrunz8foi4m</td>
  </tr>
  <tr>
    <td>cc1.08.003</td>
    <td></td>
    <td>FE</td>
    <td>Add detailed solution to tutor Exercises</td>
    <td>phil schatz</td>
    <td>8 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.nxrunz8foi4m</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.004    Update Question-Answer interaction in both Concept Coach and Tutor

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

Update the question answer interaction in both Concept Coach and Tutor with respect to Fred's updates to the design. 
Devs need to link the code from rendering in Tutor to code in the new Concept Coach widget
BE: nada, niente, rien, zero, I hope upon hope
FE:
Update Exercise rendering. (24hrs) status: needs coding
</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.001</td>
    <td></td>
    <td>FE</td>
    <td>Update Exercise rendering</td>
    <td>phil schatz</td>
    <td>24 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.tml5naim2upx</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.005    Update Event-driven Spaced Practice napkin note

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
CC Spaced Practice napkin note 
WAS THIS: Page gets added to your event history when you work the first problem at the bottom of the page.
<NEW>CHANGED TO ? ## When does an `event` get added to the student's `event history`?

The current `page`
gets added as an `event`
in the student's `event history`
upon clicking the concept coach button
at the bottom of the `page`.

because We wanted to have the history update when the first problem was worked, but backend sends all problems at once and so 
it would be possible to click all buttons at the beginning of the class and then never receive spaced practice.
</NEW>


DECOMPOSITION NOTES

Spike - Review and refresh event-driven spaced practice napkin note and prior implementation - Kevin (24 hrs) + Grimaldi
conclusions from Spike
Kathi wants one "random-ago" spaced problem. 
When does the history get updated? etc.</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.005</td>
    <td>DONE</td>
    <td>BE</td>
    <td>Spike- review and refresh event-driven spaced practice napkin note and prior implementation</td>
    <td>Kevin</td>
    <td>24 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.qbgqispyhvgu</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.006    Write a concept coach assistant 

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

Write a concept coach assistant - BE (20 hrs)
Take as input the CNX UUID and the student
Create and return a task, assigned to the student, that includes:
exercises targeted for the page the CC is on
spaced practice exercises using the student's personal CC history (event-driven); spaced practice exercises should be populated as late as possible (not when the task is created, closer to when the problem is actually worked)
Test for each CC assignment, include exercises targeted for the page the CC is on.
BE: handled by "Write a concept coach assistant" CC1.08.006
Extend Concept Coach assistant (CC1.08.006) to include exercises that help improve seed data collection BE (16 hrs)
Not intended to involve big learn, but rather just to choose exercises that haven?t been answered or choose random exercises.
Test for each CC assignment, include spaced practice exercises using the student?s personal CC history.  
insert spaced practice problems as late as possible
BE: handled by ?Write a concept coach assistant? CC1.08.006</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Status</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.006</td>
    <td></td>
    <td>BE</td>
    <td>Write a concept coach assistant</td>
    <td>jp</td>
    <td>20 hr</td>
    <td>1</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.m9dj2fo8bo04</td>
  </tr>
  <tr>
    <td>cc1.08.006</td>
    <td></td>
    <td>BE</td>
    <td>Extend Concept Coach assistant to include exercises that help improve seed data collection</td>
    <td>jp</td>
    <td>16 hr</td>
    <td>3</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.m9dj2fo8bo04</td>
  </tr>
  <tr>
    <td>cc1.08.006</td>
    <td></td>
    <td>QA</td>
    <td>Test for each CC assignment, include exercises targeted for the page the CC is on</td>
    <td>Kajal Parekh</td>
    <td></td>
    <td>1</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.m9dj2fo8bo04</td>
  </tr>
  <tr>
    <td>cc1.08.006</td>
    <td></td>
    <td>QA</td>
    <td>Test for each CC assignment, include spaced practice exercises using the student?s personal CC history.  </td>
    <td>Kajal Parekh</td>
    <td></td>
    <td>1</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.m9dj2fo8bo04</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.010     Decide what to do when there are no questions for a certain module

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
http://3lwsnp.axshare.com/#p=cc_page_module_-_initial 

BEHAVIOR
Show message: "There are no Concept Coach questions for this page.  Please continue with your assigned reading."
CC Spaced Practice napkin note

DECOMPOSITION NOTES

As Tutor, decide what to do when there are no questions for a certain module needs PO Decision
Decision for PO, Question for UX: There can normally be spaced practice questions, but we have stated that we want to populate spaced practice questions as close as possible to them being worked.  If there are no non-spaced practice questions, the first question will be a spaced practice question and depending on if the UX design says we show their questions immediately, we might be in the position of picking the spaced practice questions earlier than desired.  If there's a "Start this CC? button or similar, that would be a way to delay population of the spaced practice problems until the student is actually ready to work them.
other? pending PO decision
</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>c1.08.010</td>
    <td></td>
    <td>PO, os5.1, definition</td>
    <td>Decide behavior</td>
    <td>kathi fletcher</td>
    <td>4 hr</td>
    <td>1</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.m0cks4ym64nq</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.011    As a student, I can use assistive technology to work CC assignments

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

As a student, I can use assistive technology to work CC assignments (Accessibility)
FE: Accessibility: tabs, keyboard navigation, aria labels (24hrs)
</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.011</td>
    <td></td>
    <td>FE</td>
    <td>Accessibility: tabs, keyboard navigation, aria labels</td>
    <td>phil schatz</td>
    <td>24 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.cv5t4w5q6xju</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.012    As a student, I want a summary of my work on this CC after I'm finished

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

As a student, I want a summary of my work on this CC after I?m finished 
UX: Do we need to show breadcrumbs and would they be enough to satisfy this? -- phil schatz
FE:
Render a review page with all questions

</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>c1.08.012</td>
    <td></td>
    <td>UX</td>
    <td>Perform UX design - mockup</td>
    <td>Jason</td>
    <td></td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.wiq4wjwq7hk</td>
  </tr>
  <tr>
    <td>c1.08.012</td>
    <td></td>
    <td>UX</td>
    <td>Perform visual detailed design</td>
    <td>Jason</td>
    <td></td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.wiq4wjwq7hk</td>
  </tr>
  <tr>
    <td>c1.08.012</td>
    <td>   </td>
    <td>FE</td>
    <td>(pending UX design)</td>
    <td>phil schatz</td>
    <td></td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.wiq4wjwq7hk</td>
  </tr>
  <tr>
    <td>c1.08.012</td>
    <td></td>
    <td>FE</td>
    <td>render a review page with all questions</td>
    <td>phil schatz</td>
    <td>2, 4 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.wiq4wjwq7hk</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.013    As a student, I want to be able to electronically refer to any question in a CC such as a link

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

As a student, I want to be able to electronically refer to any question in a CC so that I can tell my instructor something about it.  Needs PO decision for priority / desired outcome
FE:  Ensure exercise rendering contains exercise id (2hrs) 

</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.013</td>
    <td></td>
    <td>FE</td>
    <td>Ensure exercise rendering contains exercise id </td>
    <td>phil schatz</td>
    <td>2 hr</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.p28ipk1tt0kv</td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.014    As a student, I want to perform my assignments on my tablet

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
<mockup link & notes> 

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

As a student, I want to perform my assignments on my tablet.
Status: needs definition, needs decision - which tablet, size 

</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.014</td>
    <td></td>
    <td>PO</td>
    <td>Define story.</td>
    <td>kathi fletcher</td>
    <td>4</td>
    <td>1</td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#bookmark=kix.wg78nmy04dfh </td>
  </tr>
</table>


<table>
  <tr>
    <td>CC1.08.015    As a student, I receive product errors, like a 500 error. 

needs  Definition | Design | Code | Test | Deployment | Document

MOCKUPS
no mockups will be provided  - use same as Tutor.

BEHAVIOR
<behavior notes> 

DECOMPOSITION NOTES

Decision: Show same message as tutor
FE:
Show modal like tutor does
BE
?



</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Epic.Story #</td>
    <td>Com-plete</td>
    <td>Tm</td>
    <td>Task</td>
    <td>Owner</td>
    <td>Estimate </td>
    <td>Priority</td>
    <td>One link</td>
  </tr>
  <tr>
    <td>cc1.08.015</td>
    <td></td>
    <td>FE</td>
    <td>Show modal when server error occurs</td>
    <td>phil schatz</td>
    <td>8</td>
    <td></td>
    <td>https://docs.google.com/document/d/1458Tj1gRP0sfv0Lb0QV4GqBHmHd4b3jpYOYpN-7sb_U/edit#heading=h.fab9zsvkxmur</td>
  </tr>
</table>


