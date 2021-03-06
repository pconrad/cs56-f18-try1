---
layout: lab
num: proj01
ready: true
desc: "Starting your project: Story Map"
assigned: 2018-11-08 17:00
due: 2018-11-13 23:59
github_org: "ucsb-cs56-f18"
---

<div style="float:right; width: auto;">

<table style="margin-top:1em;">
<tr>
   <th>Points</th>
</tr>
<tr>
   <td class="pointCount"></td>
</tr>
</table>

</div>

# Grade for this assignment

This assignment counts towards your project grade, not your lab grade.  You may earn up to 100 points.  If you earn fewer (e.g. because you missed lab on {{page.assigned | date: "%a, %b %d" }}, you'll have the oppoortunity to earn more points in later phases of the project to make up for it.

There is nothing to "hand in", or "submit" in the traditional sense, other than the physical paper flip chart that you work on this week.  Your mentor will take a picture of that flip chart and add it to your repo for your reference.  Every other part of your work will be checked by the instructional staff reviewing your work directly on Github.

<style>
div.grade { margin: 2em; padding: 1em; border: 2px solid #0c0; background-color: #efe; }   
</style>

<div style="clear:both;">
&nbsp;
</div>

## Note to mentors and TAs:

Please also consult [{{page.num}}\_mentors](/lab/{{page.num}}_mentors/) page for instructions on what mentors and TAs should do to prepare for this lab,  support students as it unfolds, and provide feedback and grades afterwards.)

# Step 0: Preparation (ideally, completed before lab)

As I asked you in my Piazza message, before you come to lab, if at all possible, please watch at least the first two of these videos.  

Watch all three if you have time, but at least please watch the first two:

* Part 1 (12:12) (Planning): <https://youtu.be/IsuIZaqnIuU>
* Part 2 (10:15) (Using a Github Project Kanban Board): <https://youtu.be/8U0FezxxMGU>
* Part 3 (16:28) (More User Stories and Issues): <https://youtu.be/lIB0WJzgSs8>

If you want to reference the slides from the videos, they are here: 
* [From User Story Mapping to Kanban in Github](https://docs.google.com/presentation/d/1UD5qIm5njZFF2s8OvCJdJPnsR_VvnavcZRP9cXRqRNw/edit?usp=sharing), a presentation by Phill Conrad and John Cutler


# Creating Your Story Map


## Step 1:  Gather in your team, and start a flip chart

See the new seating chart here to know where to find your team.   

* <https://ucsb-cs56-f18.github.io/info/lab_seating_chart_5pm/>
* <https://ucsb-cs56-f18.github.io/info/lab_seating_chart_6pm/>
* <https://ucsb-cs56-f18.github.io/info/lab_seating_chart_7pm/>

We will set up white board charts for each of you, along with flip chart markers, in four corners of the room; find your corner.

* Locate and identify your new mentor as well
* Also identify the TA (Jinjin or Santha) that will be working with your team.
* Finally, introduce yourselves to each other.

## Step 2:  Start documenting your team's work on a flip chart

We will set up white board charts for each of you, along with flip chart markers, in four corners of the room.

Please start by coming up with the **name for your project**.  It should be something that can be used as the name of a github repo, so let's keep the number of characters to fewer than 20, e.g. `"Gaucho GE Grabber"` is 18.   

For example, if your project name is `Gaucho GE Grabber` your repo will end up being `ucsb-cs56-gaucho-ge-grabber`
* Your project name can be mixed case and have spaces, e.g. `"Gaucho GE Grabber"` 
* In repo names we are going with all lowercase, to keep things simple

Write the name of your project, your mentor, and the names of the people on your team, (with a checkmark beside those that are present, and an X by those that are absent.)

Example:

<div style="width: 30em; height: 20em; border: 4px solid #ccc; padding: 1em;" markdown="1" >

# Project: Gaucho GE Grabber

Mentor: Julia Roberts

Team: Phill Conrad ✓, Jinjin Shao ✓, Santha Ramamoorthy ✓, Henry Yang ✗, Oprah Winfrey ✗ 

</div>

Being present for today's lab, and making sure your name is on the flip chart with a ✓ is 20% of your grade for today's work.

<div class="grade" markdown="1">

**Graded**: (20 pts) You earn these points if/only if:
* you were personally present in lab on {{page.assigned | date: "%a, %b %d"}} and 
* your team produces a flip chart in the requested format during lab on {{page.assigned |  date: "%a, %b %d"}}.

</div>

## Step 3: Create a communications channel

Create a communication channel for your team.  Your team (including both the CS56 students, and your mentor) must come to a consensus on what this communication channel will be:

This could be any of the following:
* A Slack channel
* A Gauchospace message board (your mentor, TA or instructor can create this for you)
* A Facebook group chat
* A Google Hangout
* Wechat, Groupme, or something else

Don't let this discussion go on for more than five minutes.   
* As a fall back: if you are unable to reach consensus within 5 minutes of the , the "default" will be a private Gauchospace discussion board that is set up for your team (the students, the team mentor, and the instructor).    
* There is nothing stopping you from moving, later, to a different system if you can reach consensus then.
* But to be honest, there are better tools than a Gauchospace discussion board.  That is only provided as an option so that you don't spent the entire lab arguing about the merits of Slack vs. WeChat.

Whatever method you choose to use, please document this by:
* Communicating it with your mentor
* Adding your mentor into the communications channel

At this stage, you do not need to add the TA or instructor into your team's communications channel.  We might do that at a later stage, but at this stage, the plan is that if you need to communicate with the TA or instructor, you can do so through Piazza, or through your mentor (your mentor is on a separate "instructional staff" Slack channel that already exists.)


<div class="grade" markdown="1">

**Graded**: (10 pts): Document the choice of communications channel on your flip chart.

You earn these points if/only if:
* your team's flip chart identifies a communications channel in lab on {{page.assigned | date: "%a, %b %d"}} 
* your mentor documents that they were able to reach you, personally, over that channel on or before the due date/time for this lab, i.e. 

These points do not require being physically present in lab on {{page.assigned |  date: "%a, %b %d"}}; you can earn them even if you were not there, as long as you get added to the communications channel.  
Getting yourself added is your responsiblity. Ways you can try:
* You can reach out to your mentor via a private "Instructor Note" on Piazza, and they can put you in touch with fellow team members.
* You can reach out to fellow team members via a public post on Piazza.

</div>



## Step 4: Discuss the User Journey

(This step is not graded, per se, but you can't meaningfully accomplish the later stages if you try to skip it.)

As a team, discuss the "user journey" for your proposed application. 

That is, try to describe all of the events that lead someone to seek out your webapp and have an interaction with it, or perhaps a series of interactions. 

There should be a beginning, a middle and an end, where **value is exchanged**: 
* the user came with a *goal, need, or desire*, and 
* that goal was *met*, that need was *satisfied*, or that desire was *fulfilled*. 

Identify: 
* What is that goal, need or desire?
* What is the series of events, in chronological order?

Discuss this with your group, and on your paper, write down whatever comes to mind.  

IF IT IS HELPFUL, you *could* use the form shown in the video, and illustrated in class, where you have a series of stories that form column headings across the top of the page, and then you have descriptions of specific user interactions as sticky notes in the columns, as illustrated here (click for larger image):

<a href="/lab/proj01/story_map_example.png" data-ajax="false">
<img src="/lab/proj01/story_map_example_30pct.png" alt="Story Map Example">
</a>
**(Click the image above for a more legible version)**

BUT: at this stage, it is more important to get the ideas flowing.  There is no specific "right or wrong" way to get your ideas down on the paper.  Just write something
that captures the group consensus, or the candidate proposals, for the "user journey".

It can take any form: a list, or pictures,  a collection of <tt>As a __ I can __ so that __ </tt> type stories, or any combination of those.  Don't get bogged down on what form it takes.  Just get something down.

NOTE: Try to keep your description VERY HIGH LEVEL, avoiding specific implementation details.

* Good:  User selects a beverage from among several choices
* Too much detail: User clicks on a drop down menu; each beverage has an image which flashes with an animation as you hover over it, etc. etc. 

You don't have to do this "perfectly" the first time.  You may need to first get it all out as "brain dump" that contains too much detail, and then move to a higher level.  But get to the higher level as soon as you can.

Don't move on to the next step until you have the "spine" of your customer journey captured in some fashion.

You'll know you have it, and you are ready for this step when:

* It tells a coherent story.  You can describe this to any reasonable person 
   (e.g. a UCSB student that isn't in this class, particularly one that might be a target user) 
   and they will be able to follow what you are saying.
* None of your "spine" should be "implementation" focused.    It shouldn't depend, for example, even on whether
  it happens to be a webapp, or a mobile app, or even an app at all.    It shoudn't depend on technology specifics.

* The <b>value exchange</b> part is clearly identified: the goal/need/desire of the user, and how that gets acheived/met/fulfilled

## Step 5: Move towards minimum viable product

(This step is not graded, per se, but you can't meaningfully accomplish the later stages if you try to skip it.)

Now you have an outline, in some form (whatever form seemed reasonable to you)

At this stage, the story you have might have gone in one of two directions:

* **Grand Vision** (GV): You might have a story that really is very much your "ideal dream state" of the application when fully built out.   Keep in    mind that this may be far more than you can reasonably accomplish in the next 4 weeks.
* **Minimum Viable Product** (MVP) You might have already been thinking in terms of "minimal viable product", and you might have a really nice thin slice of value for your end user, something you might *actually* be able to deliver in  4 weeks (or 1 week, or even 1 day.)
   
It's likely that each of our teams will be somewhere on the spectrum between these two extremes.  Discuss where you think
your team is on that spectrum.
   
Assuming that your team is somewhere closer to GV than to MVP, you'll now want to set aside the description of your
GV for the moment.  Use it as a reference to inform your efforts to redo the exercise, but focusing on an MVP.

Maybe you can draw on top of your GV description, and circle the parts (in a different color) that you think might
be part of your MVP.

The big question to keep in mind is:

> How can we make "this" possible for the user with less complexity, less code, less time

Here "this" is the goal/need/desire.


## Step 6: (Optional) Make a new chart in the form shown in part 1 of the video

(This step is not graded, and you might be able to skip it.  Read through the information below and decide if completing this step would be helpful.  Once you've read through it, you can always decide to skip it for now, and come back if you find that you are stuck.)

At this stage, you need to make a decision.  
* Are you ready to go straight to user stories and tasks, as shown in part 2 of the video?
* Or, would it help to first make a new user story map, in the format shown in part one of the video (and illustrated in the picture?)

If making a new map would help, do that.  If you are ready to go staight to user stories and issues in Github, then go to the next step.

## Step 7: (Required, Graded) Make a Kanban board for your project

Now, we are at the part that is most important to the future success of your project, and the part for which you will be graded (this is the other 80% of your grade for today's work.)

### Step 7a: Locate the repo your mentor created for you.

Your mentor will have set up a github repo for your project under the organization [ucsb-cs56-webapps](https://github.com/ucsb-cs56-webapps]. 

(If you can't find that repo,  ask your mentor for help.  If that repo doesn't exist yet, you mentor should look at the [{{page.num}}\_mentors](/lab/{{page.num}}_mentors/) page for instructions on what they should do to set it up.)

This repo is *read only* for you.  So you'll need to fork it, which is the next step.

### Step 7b: Fork the repo into the [{{page.github_org}}](https://github.com/{{page.github_org}})  organization

You will do your work in a *fork* of this repo.  Take these steps:
1. One member of your team should fork the repo to the [{{page.github_org}}](https://github.com/{{page.github_org}}) organization.
2. That member should then add ALL of the other members of your team to that repo as collaborators **with admin access**.
   (If you are not sure what that means, consult with your mentor.)
3. In the README for that fork of the repo, add a section with the heading `# Fall 2018` and under that heading, put down the first names (only) and the github ids for the members of your team.  Also write 1-2 sentences describing the main idea of your webapp (this is NOT a long detailed description; just the highest level description possible.)

<div class="grade" markdown="1">

**Graded**: (5 pts) You earn these points if/when you, as an individual, were:
* present in lab on ({{page.assigned |  date: "%a, %b %d "}}, and 
* your team has forked the repo into the [{{page.github_org}}](https://github.com/{{page.github_org}})  organization
* you are a collaborator on that repo by the due date of the lab, ({{page.due |  date: "%a, %b %d at %l:%M%p"}})

</div>

### Step 7c: Make a Kanban board, as illustrated in the [video (Part 2)](https://www.youtube.com/watch?v=8U0FezxxMGU)

Now, go into your forked repo, and go to Projects, and create a project.

* Name it the same as your project plus {{site.qxx}}
* Create a Basic Kanban board (Todo, In Progress, Done)
* Delete the three "starter cards" as shown in the video using "Delete Note"


Now, take your story map, and turn it into:
* User stories, in the form `As a _ I can _ so that _`, which become "Note" cards. 
* Issues (tasks) which you put under each of those User Stories

You should end up with at least 3 issues that your team could start working on.

At least one of them should be similar to this one from the video, i.e. a Spring Boot Boostrap Navigation template starter app similar to the one from [{{page.spring_boot_lab_num}}](/lab/{{page.spring_boot_lab_num}}/) where you put together a basic User Interface using Bootstrap with some basic menus and placeholders that support the user interaction you anticipate in your app:

<a href="/lab/proj01/first_issue.png" data-ajax="false">
<img src="/lab/proj01/first_issue_30pct.png" alt="First Issue">
</a>

**(Click the image above for a more legible version)**

<div class="grade" markdown="1">

**Graded**: (5 pts) You earn these points if/when you:
* met the criteria for the previous item (present in lab, team forked repo, you are a collaborator), AND
* your team has created a Kanban board by the due date of the lab, ({{page.due |  date: "%a, %b %d at %l:%M%p"}})

</div>

### Step 7d: Have your mentor review your Kanban board and approve issues

Ask your mentor to look over your Kanban board and make a comment on each of your user stories and issues.

If the issue is clear to them, and has their blessing, they should make a comment that includes the words:

"Mentor Approved"

If your mentor has questions/concerns, they'll make those in the comments.  You should iterate with them until all of the user stories and issues are "Mentor Approved".   

<div class="grade" markdown="1">

**Graded**: (40 pts) You earn these points when and if
* you were personally present in lab on {{page.assigned |  date: "%a, %b %d"}} for the discussion of issues, and
* your mentor has approved a set of issues for your team to work on, and you are assigned to at least one of them by the due date for this lab, ({{page.due |  date: "%a, %b %d at %l:%M%p"}}).

</div>

### Step 7e:  Make initial assignment of issues

Each member of your team that is present tonight should be assigned to at least one issue.  You can assign multiple developers to a single issue; this is how you form pairs, trios, and mobs of 4 or more.

Members that are not present should take responsibility for ensuring that they
* are either added to existing issues (after communication with the team members already on that issue), or 
* for creating additional issues, again, after appropriate communication with the other team members

<div class="grade" markdown="1">

**Graded**: (20 pts) You earn these points if/when you, as an individual, are assigned to one or more issues by the deadline for this lab ({{page.due |  date: "%a, %b %d at %l:%M%p"}}).

(These points do not require being physically present in lab on ({{page.assigned |  date: "%a, %b %d "}}.)

</div>


# What Comes Next?

Next, your mentor will estimate issues and assign point values.  These will typically be:
* 100 points for relatively straightforward issues where there is a clear road map to follow
* 200 points for somewhat more involved issues where, say, the instructors and mentors have a good idea of how to proceed, and are sure they can guide you, but where you may have to learn some new skills.   These include working with OAuth, MongoDB databases, Firebase, basic screen scraping, reading JSON files, and some others.
* 400 points for issues where some research may be involved (e.g. using an API (e.g. Google Places, Github, Facebook) for which we don't currently have a tutorial) interacting with a platform for which we have no guidelines (Hibernate for Postgres on Heroku), etc.

Depending on who your mentor is, your issues may be estimated quickly, or it may take a few days.  They should all be estimated by next Thursday though.   At the very least, though, your team should leave tonight with at least two issues that they can get started on.

<hr>

Credits: Many thanks to [John Cutler](https://twitter.com/johncutlefish?lang=en) for his assistance in consulting on this project step.
