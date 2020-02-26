---
title: "Welcome"
start: true
teaching: 20
exercises: 15
questions:
- "Who are we and how do we approach teaching?"
- "What should you expect from this workshop?"
objectives:
- "Introduce yourself to your fellow workshop participants."
- "Describe what will and will not be covered in this workshop."
- "Understand that the Carpentries are communities of volunteers who develop lessons and teach workshops on basic computing and data skills for researchers."
keypoints:
- "The Carpentries are communities of practice. We strive to provide a welcoming environment for all learners and take our Code of Conduct seriously."
- "This episode sets the stage for the entire workshop. The introductions and exercises help everyone begin to develop a relationship and trust."
- "This workshop will cover general teaching pedagogy and how it applies specifically to the Carpentries."
- "Learner motivation and prior knowledge vary widely, but can be assessed with a quick multiple choice question."
---

## Code of Conduct

To make clear what is expected, everyone participating in Carpentries activities is required
to conform to our [Code of Conduct]({{ site.coc }}). This Code of Conduct applies to all spaces managed by the Carpentries including, but not limited to workshops, email lists, online forums and on GitHub. Please review
[the Code of Conduct]({{ site.coc }}) to familiarise yourself with it.

## Introductions

> Introductions set the stage for learning.
>
> --- Tracy Teal, Executive Director, The Carpentries
{: .testimonial}

Hello everyone, and welcome to the the Carpentries
instructor training.  We're very pleased to have you with us.

> ## Today's Trainers
>
> To begin class, each Trainer should give a brief introduction of themselves.
>
> (For some guidelines on introducing yourself, see some content from
> later in the workshop: [Workshop Introductions](http://carpentries.github.io/instructor-training/23-introductions/index.html))
{: .discussion}

> ## Your classmates
>
> Around the room, please say (1) your name, (2) describe your work in 3 words, and (3) something you are proud of
{: .challenge}

> ## Reviewing Carpentries Experience and Goals
>
> Hands up!
>
> *Have you ever participated in a Software Carpentry, Data Carpentry, or Library Carpentry Workshop?*
>
> 1.  Yes, I have taken a workshop.
> 2.  Yes, I have been a workshop helper.
> 3.  Yes, I organized a workshop.
> 4.  No, but I am familiar with what is taught at a workshop.
> 5.  No, and I am not familiar with what is taught at a workshop.
>
> *Which of these most accurately describes your teaching experience?*
>
> 1.  I have been a graduate or undergraduate teaching assistant for a university/college course.
> 2.  I have not had any teaching experience in the past.
> 3.  I have taught a seminar, workshop, or other short or informal course.
> 4.  I have been the instructor-of-record for my own university/college course.
> 5.  I have taught at the primary or secondary education level.
> 6.  I have taught informally through outreach programs, hackathons, libraries, laboratory demonstrations, and similar activities.
{: .challenge}

## Using the etherpad

> ## Getting to know each other
>
> Please use the etherpad to sign in with your name and institution.
{: .challenge}


## Goals and motivation

> **Why are you taking this course? What goals do you have for today and tomorrow?**
>
> At your table, discuss these questions.
{: .challenge}

To make sure everyone has the
same context, we'll give a brief overview of the Carpentries
organization before starting the training.

## A Brief Overview of the Carpentries

The Carpentries project comprises communities of Instructors, Trainers,
Maintainers, helpers, and supporters from
[Software Carpentry]({{ site.swc_site }}), [Data Carpentry]({{ site.dc_site }}) and [Library Carpentry]({{ site.lc_site }})
who share a mission to teach foundational computational and data science skills.

[Software Carpentry]({{ site.swc_site }}) was founded in 1998 with the mission of teaching lab skills for research computing.
[Data Carpentry]({{ site.dc_site }}) was founded in 2014 with the mission of building communities teaching universal data literacy.

Also in 2014, [Library Carpentry]({{ site.lc_site }}) was founded with the mission of teaching data skills to people working in library- and information-related roles.

On January 1, 2018, Software Carpentry and Data Carpentry merged
their projects to form a new project called
[The Carpentries]({{ site.carpentries_site }})
under the fiscal sponsorship of
[Community Initiatives](https://communityin.org/).
Within this new organization structure, Software Carpentry and Data Carpentry retain their individual identities as Lesson Programs of the Carpentries.
On November 1, 2018, The Carpentries Executive Council
approved [Library Carpentry]({{ site.lc_site }})
as the third official Lesson Program of the Carpentries.


![A brief history](../fig/SWCDChistory.png)

You can learn more about the history and goals of each Lesson Program by reading
"[Software Carpentry: Lessons Learned](https://f1000research.com/articles/3-62/v2)",
"[Data Carpentry: Workshops to Increase Data Literacy for Researchers](http://ijdc.net/index.php/ijdc/article/view/10.1.135)" and
"[Library Carpentry: software skills training for library professionals](https://www.liberquarterly.eu/article/10.18352/lq.10176/)"".

## Similarities and Differences between The Carpentries Lesson Programs

All lesson programs under The Carpentries share the same value
of promoting efficient, shareable, and reproducible research practices.
Their aligned missions are accomplished by running accessible, inclusive training workshops; teaching openly available, high-quality, community-developed lessons; and fostering an active, inclusive, diverse instructor community that promotes and models reproducible research as a community norm.

Similarities between Software, Data and Library Carpentry workshops include:
*   a focus on technical skills.
*   an two-day format taught by volunteer instructors.
*   a focus on filling gaps in current training for learners.

The major differences between Software, Data and Library Carpentry workshops
are their content and intended audience.

Software Carpentry workshops are:

*   intended for people who need to program more effectively to solve their
computational challenges,
*   not domain-specific, and
*   modular---each Software Carpentry lesson is standalone.

Data Carpentry workshops:

*   are aimed at pure novices,
*   are domain-specific,
*   focus on best practices surrounding data, and
*   present a full curriculum centered around a single data set.

Library Carpentry workshops:

*   are aimed at people in library- and information-related roles,
*   focus on best practices in data structure, and
*   are modular---each Library Carpentry lesson is standalone.
*   are sometimes less than two days.

In a visual representation, these similarities and differences look like this:

![Carpentries Similarities and Differences](../fig/carpentries-venn-diagram_20190522.svg)

The main goal of these organizations is not to teach specific skills, per se - although those
are covered - but rather, to convey best practices that will enable
researchers to be more productive and do better research.

## Instructor Training Workshop Overview

The goal of this two-day training is to provide you with the skills and information you need
to become a certified Carpentries instructor. Our expectations of certified Carpentries
instructors is that they:

- be familiar with and understand how to apply research-based teaching principles,
especially as they apply to the Carpentries audience.
- understand the importance of a respectful and inclusive classroom environment; commit to
creating such an environment; and be able to
identify and implement Carpentries policies and general practices to accomplish this.
- practice and develop skills in the teaching methods used in Carpentries workshops
- learn enough about the Carpentries organization to know where to go for help,
how to start organizing a workshop, and how to get involved with community activities.

These four goals are broken down into four main modules of content:

### How Learning Works

One of our main emphases will be discussing the "best practices" of teaching. We
will be introducing you to a handful of key educational research
findings and demonstrating how they can be used to help people learn better and faster.

### Building Teaching Skill

Just like learning a new language, a musical instrument,
or a sport, teaching is a skill that requires practice and feedback.
We will have many opportunities to practice and give each other feedback throughout this workshop.
We welcome questions and dialogue
at any point. We'll be using the Etherpad to help facilitate discussion.
Please feel free to ask questions verbally or to put them into the notes or chat box
of the Etherpad.

### Creating a Positive Learning Environment

One part of making this a productive two days for all of us is a
community effort to treat one another with kindness and respect.  This
training, as in all Carpentries workshops, is subject to
the [Code of Conduct]({{ site.coc }}).  We will be able to
give our best effort (and have the most fun!) if everyone abides by these guidelines.
We will also be discussing and practicing teaching techniques to create a positive and
welcoming environment in your classrooms.

### Carpentry History and Culture

We will be introducing you to the teaching practices that have been
adopted by the Carpentries communities, and our
overall philosophy and procedures in order
to prepare you to teach Carpentries workshops.
The greatest asset of the Carpentries is people like
yourselves - people who want to help researchers learn about these ideas
and share their own experience and enthusiasm.  We hope that this training
gives everyone a chance to meet new people and share ideas.

To orient yourself, there is a schedule on the workshop webpage which is linked through this workshop's Etherpad.

## What We Leave Out

We will **not** be going over Data Carpentry, Library Carpentry, or Software Carpentry workshop content in detail (although you will get
familiarity with some of the content through the exercises),
This workshop is a significant requirement for becoming a certified Carpentries instructor.
The additional steps for certification will require that you dig into the workshop content yourself. We'll talk about that more tomorrow afternoon.

We also do not discuss how to develop lessons.  Many of the ideas we
present can be applied to lesson development, and we will briefly touch on a method
of lesson design called "Reverse Instructional Design", but it won't be an emphasis
of this particular course.

If there's a particular topic that you would like us to address, let the trainers
know.

## Let's Get Started

Now that we have a road map of what we're covering
ready to begin our training. Our goal is that by the end, you will
have acquired some new knowledge, confidence, and skills that you can
use in your teaching practice in general and in teaching Carpentries
workshops specifically.
