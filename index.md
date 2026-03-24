---
layout: page
title: About
seo:
  type: Course
  name: Machine Learning Capstone (CSE481M)
description: >-
    Course policies and information.
---

# Machine Learning Capstone
{:.no_toc}

CSE 481M, Spring 2026
{: .fs-5 .mb-0 }
Tuesdays and Thursdays, 10am -- 11:20am, Allen (CSE) 305
{: .fs-5 .mt-0 }

---

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

<div class="staffer-grid">
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>
{% endif %}

## Overview

Students will work in groups of three to complete an independent machine learning research project in a domain of your choice (e.g., natural language processing; computer vision; medical data; machine learning theory; etc.). The focus will be on honing your research skills: formulating problems, picking up relevant technical knowledge, building research codebases, performing experiments and analysis, and writing up your results. 

This is a research-oriented capstone with minimal lectures. Most of our class time will be spent (1) discussing your project in small groups with course staff, and (2) presenting your project to the rest of the class, in order to give and receive technical advice and constructive feedback.

We expect that students will have taken sufficient coursework in machine learning and related fields, so that you start the class with the foundational knowledge needed to do research.
Formally, students should have taken CSE 446/546 (Machine Learning) and at least another class in the area, such as CSE 493 S (Advanced Machine Learning), CSE 493G (Deep Learning), CSE 447, CSE 455, CSE 478, or CSE 427.
You should be able to read research papers (with effort) in your chosen area and should also be familiar with the tools of the trade (e.g., common libraries used for that area).

## Project 

Your team designs a project around something you are interested in. The project should be centered around an open problem in machine learning. We (the course staff) will do our best to advise you directly or to connect you to local researchers with relevant expertise.  

Throughout the course, teams are expected to write regular reports, including a project proposal and final report, and to give four five-minute presentations in class. All team members should speak at all presentations. The final presentation should also be separately recorded and uploaded to Youtube as a public or unlisted (your choice) video.

Your project must be accompanied by open-source, reproducible code (and data, if applicable) that replicates all experiments in your final report. Code should be uploaded to Github and data to HuggingFace or another appropriate repository. Links to these resources must be included in the final report.

Please see the [course schedule](../schedule) for deadlines and more details. 


## Classes

All Tuesday classes are mandatory and in-person; there will be no remote option.

During the first two weeks (the proposal stage), Thursday classes are optional and will be used to form teams and discuss project ideas with course staff.
For the remainder of the course, Thursday classes will be used for discussions with course staff. Each team will be assigned to one TA and will be expected to sign up for a slot to meet with their TA during the Thursday class. 



## Evaluation

Course grades will be computed as follows:
1.  Reports (eleven at 4% each; extra 5% to project proposal and extra 11% to final report)
2.  Five-minute presentations (short talks given in lecture; four at 5% each)
3.  Class and project participation (20%)

All grades will be shared by the team, with the exception of reports #5, #9, and #11 which are individual as well as the class participation score. 
In rare circumstances where one or more team members are not contributing nearly as much as other team members, or where one or more team members are not familiar with their own project, we might assign different grades to different team members.

Your team may use up to three penalty-free late days (total, not per report) for reports #4, #6, #7, and #8. No late days are allowed for other deliverables. Work turned in late after the late days are used up will get a zero grade.  

The class and project participation grade will be computed as a function of (a) feedback to other teams' presentations; (b) giving feedback to other teams' reports on Ed; (c) and active, thoughtful participation in project discussions with course staff. 

Overall grades will not be curved, so teams will not be compared to each other and it is possible for everyone to do well. Research is inherently unpredictable and the best ideas are risky ones, so it is ok if projects do not work out as planned. Teams that put in consistent effort and produce high-quality work throughout the course will get a good grade regardless.


## Compute

Students are encouraged to apply for free cloud compute: 
- **Google Cloud:** $300 in free credits for [new customers](https://cloud.google.com/free).
- **Google Colab Pro:** Available for [higher education](https://blog.google/products-and-platforms/products/education/colab-higher-education/).
- **Microsoft Azure:** $100 of credits for [students](https://azure.microsoft.com/en-us/free/students).

In addition, students may use other external compute resources that they have access to (e.g., from their research labs if they are part of one). 

We will distribute a small amount of additional Google Cloud credits at the end of the second week. 


## Other course policies
**Conduct and inclusion.** The course follows the University of Washington's standards for student conduct. All students are expected to contribute to a respectful, inclusive, and intellectually generous class environment. Disagreement and constructive feedback are welcome.

**Academic integrity and the use of AI tools.** All submitted work must reflect the student's or team's own thinking and analysis. External tools, including software and computational resources, may be used as part of the research process. If students use automated tools (for example, for coding assistance, drafting, or analysis), they must:
- Be transparent about how these tools were used.
- Take responsibility for verifying and interpreting all outputs.
- Ensure that the final work reflects their own intellectual contribution.
 Teams will discuss their weekly reports with the course staff. We expect all students to know all details about their projects, especially around their own contributions, regardless of whether AI tools were used.
 Not following these guidelines will be treated as a violation of academic integrity and will have to be reported externally.

**Collaboration.** Collaboration within teams is expected. Discussion and informal collaboration across teams is also encouraged, as long as each team's submitted work is clearly their own and not copied or duplicated.

**Accessibility.** We are committed to providing access and reasonable accommodation. To request disability accommodation in this class, contact Disability Resources for Students ([DRS](https://depts.washington.edu/uwdrs/)) at 206-543-8924, uwdrs@uw.edu, or in person at 011 Mary Gates Hall. If you have already established accommodations with DRS, please communicate your approved accommodations to the course staff at your earliest convenience so we can discuss your needs in this course.


## FAQ

**Must I be in a team of 3 people?** Yes. In exceptional circumstances (e.g., the number of students in the class is not divisible by 3) we will consider teams of different sizes, but we generally expect students to work in teams of 3. This is for pedagogical reasons (doing research in a team, especially with new people, is a good skill to practice) as well as logistical reasons (so that we can ensure that each team gets enough time with course staff and that presentations will fit in the class time, etc.).

**Can I use a project that I've already been working on, and/or a project that I'm working on with another lab outside this class?** Your course project must be started from scratch and worked on only by you and your team members. You are very welcome to seek advice and feedback from other researchers, as well as to use compute/hardware available from other labs. However, all coding and writing must be done by you and your team members. We understand that some students already have ongoing projects and are already embedded with other research groups; these projects are not suitable for our class as our goal is to take students independently through the entire project lifecycle.

**What format should the reports be in?** See the [course schedule](../schedule) for details on which reports should be posted on Ed vs. Gradescope. PDF reports must be typeset.

**What are the cross-discussions with course staff in the schedule?** Each team will be assigned to one TA and will meet with them weekly throughout the class. During the cross-discussion sessions, teams will meet with the other TA to get a different perspective on their project.

**Can I attend office hours for the TA who is not assigned to my team?** Yes, you may attend office hours for either TA. In addition, feel free to contact the instructor by email to schedule office hours.

**I'm having issues with my team. What can I do?** Please bring this up with the course staff individually. You may contact us by private Ed post or email.

**I would like to enroll in this class, but the class is full. Can I get an add code?** Add codes are managed centrally by the Allen School. To request an add code, please reach out to the [CS Advisors](https://www.cs.washington.edu/academics/ugrad/advising). If you aren't a CSE student, you will need to proceed through our [non-major registration process](https://www.cs.washington.edu/students/ugrad/non-major-registration). Unfortunately, due to capacity constraints, we are unlikely to have non-major positions open. Once the quarter officially starts, add codes might not be needed; check to see if you can enroll directly if any slots open up.

