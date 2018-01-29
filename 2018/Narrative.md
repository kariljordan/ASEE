# Short format workshops build skills and confidence for researchers to work with data.

## Abstract 
Training for data skills is more critical now than ever before. For many researchers in industry and academic environments a lack of training in data management, munging, analysis and visualization has led to a lack of funding to support sustainable projects. Today’s researchers are often learning “as they go” and need the flexibility of short, or self-paced learning experiences. Research results, however, stress the importance of guided instruction and learner-instructor interaction.

We’ve taken a distinctive approach to this problem, combining the power of guided instruction with the flexibility of short, focused learning experiences. Two-day, interactive, hands-on coding workshops train researchers to work with data, and have reached over 34,000 researchers, ranging from biologists to physicists to engineers and economists. Researchers have benefited from evidence-based teaching approaches to learning data organization (spreadsheets), cleaning (OpenRefine), management (SQL), analysis and visualization (R and Python).

This paper presents the long-term survey results showing the impact that short-format workshops have for increasing learner's skills and confidence in their coding abilities. Results show these two-day coding workshops increase researcher’s daily programming usage, and sixty-five percent of respondents have gained confidence in working with data and open source tools as a result of completing the workshop. The long-term assessment data showed a decline in the percentage of respondents that 'have not been using these tools' (-11.1%), and an increase in the percentage of those who now use the tools on a daily basis (+14.5%). 

*Keywords: Assessment, data science, short-courses*

## Introduction: State of Data Science Workforce Needs
Globally, data science talent is in high demand. In their widely cited report on big data, McKinsey Global Institute (MGI) estimated that, by 2018, in the United States (US), the shortfall in data science workforce would be 60% of its supply [1]. Although the term ‘data science’ was not in use in this 2011 report, the two occupational groups deemed key to creating value from data (i.e., “deep analytical talent” and “data-savvy managers and analysts”) correspond to “data scientists” and “business translators,” respectively, in a 2016 follow-up report [2].

The authors extend their overall findings to other high-income countries, while acknowledging that these display significant variations in the number, both gross and per capita, of their new graduates with deep analytical skills. In this way, a Canadian study [3] considered Canada’s shortage in data talent to be the same as the United States’ one determined by [1], proportionally to its population, while cross-matching it with a second estimate.

The more recent report, where the projection horizon is 2024, finds lower relative gaps between labour demand and supply [2]. Indeed, the projected supply and demand of data scientists in the United States are 483,000 and 500,000 positions, respectively (only in a high-case scenario would demand reach 736,000 and, hence, yield a 50% shortfall). To add to the uncertainty, much of data science work is self-destructive: The automation of data preparation (supported by at least some machine learning) could lead to a shift in data science work, a decreasing demand for data science work, or both [2].

Regarding “business translator” roles, which combine data literacy with operational skills, more and more organizations are “building these capabilities from within,” training existing workers. In addition, 20% to 40% of new graduates in science, technology, engineering, and mathematics (STEM), business, and any field involving quantitative analysis would have to become these data-literate managers and analysts, in order to meet the United States demand of two to four million by 2024 [2]. The authors stress the importance of data visualization to support decision-making. To add to the complexity, some workers can and will take on more than one role, especially in small and medium-size organizations.

What we have referred to as ‘workforce needs’ may be more correctly characterized as growth potential, in the sense that most industries are still capturing only a fraction of the potential value from data and analytics [2]. Beyond considerations about economic value and labour markets, data literacy is, in today’s and tomorrow’s data-driven world, a prerequisite for social participation [4]. Although our workshops target researchers, our approach is in line with the democratization of data literacy and education overall.

## Data Science Training
With the booming commercial and academic market for data science and analytics training options, those seeking this training have a variety of choices. When we think of training offerings, we need to categorize what is trying to be instructed and how this might fit into the process a researcher might take in adopting a new tool or skill into their current line up. The training offered needs to fit the person’s needs for: awareness of tools, specific tool introduction, intensive practice, and skill mastery.

Short form (1-2 hour) workshops are often the most universal offering for any group providing any form of training. They are the easiest to book rooms for or offer online as webinars, find instructors, and create materials. For the participant, one hour is a reasonable amount of time to find in your day and there are rarely any follow up requirements. Thus, there is very little risk of making a bad time investment for the learner, and the instructional team has a lot of flexibility in repeating the training and experimenting with content. From research methods to retirement plans, this format is an exceptional platform for learners to explore new tools and services. Even though hands on practice can be quite limited in this format, this discovery and evaluation process is crucial.

Other short form training options in a classroom-like setting include pre-conference workshops that run for 3-6 hours and week long “summer school” workshops. These will look very different depending on the audience, and have the time flexibility to include tool introductions with intensive hands on practice, or provide more advanced training for commonly used tools.

These short formats are very common in the academic context and very suitable for institutions to provide locale specific training, or for specific research communities to provide domain specific training. Learners who have decided that a tool is worth further exploration and introduction will find these courses essential to move forward from a novice phase or to reorganize some of their self taught knowledge. Longer in person trainings can be the ideal format from an instructional perspective. Learners can often get help installing the tools on their own machines, ask questions, and have the flexibility to work on their own projects during the course. The biggest limitation to these formats is because they are in person and access is the most prohibitive factor. Access issues include scarcity of time to attend, ability to travel to and physically access the location of the event, and funding to cover the travel, lodging, and registration.

Online self-paced training often takes the form of these half to full day trainings for individual modules. Depending on the site, these modules can be grouped into topical clusters, and then further into longer programs of study. As with any self-paced online program, being able to fit it into a busy schedule, complete it anywhere, and often for a much lower price provides strong benefits. However, completing everything online with static exercises means that learners do not always get the benefit of using the tools on their own computers or experience practicing with a full scale realistic project.

Commercial multi-week bootcamps and academic programs of study have the strongest benefits of time, but have serious access issues.  Most require physical access for several months or years, with hefty tuition costs. The length of time and focus on mastery is also inappropriate for learners wishing to become more skilled at a tool for research or a job. These longer formats are often for those who desire entry into a job field as a professional programmer, rather than an end user programmer who will remain in their current position.  

The reality is that most trainings require that the learner spend time deciphering how to fit all these materials together to suit their needs and perform their own critical evaluation of the educational quality of these platforms and instruction sessions. The trainings often lack large scale testing with multiple runs, open and community driven modifications, transparent assessment, and ease of access to in-person training.

## The Carpentries
The Carpentries (Software Carpentry (SWC) and Data Carpentry (DC)) are two closely affiliated non-profit organizations that coordinate collective efforts to spread the skills necessary for data-driven research. DC delivers domain-specific hands-on intensive workshops covering the full lifecycle of data-driven research. Current workshops are designed for people with little to no prior computational experience. These workshops include data organization and cleaning, data management and scripting for data analysis and visualization to empower researchers to work more effectively and reproducibly with data [5]. SWC focuses on common approaches for automating repetitive tasks, data management, defensive programming, source control, and code execution environments [6]. These workshops use active learning to give learners the opportunity to try the skills and gain immediate feedback with low learner-teacher and helper ratios, guided and independent exercises, and an interactive and friendly environment for learning [7]. Combined, these workshops provide a strong opportunity to learn and the needed conceptual framework for participants to excel in data-driven research [8; 9]. The Carpentries have built a network of instructors who are themselves researchers and have expressed significant career benefits from volunteering to teach workshops [10].

## Tools we Teach
The Carpentries teach workshops around a base programming language, which is either Python or R. Python and R are both general-purpose, high-level, interpreted, multi-paradigm, cross-platform, free/libre and open-source (FLOSS) programming languages. These general features make these languages installable by any learner, accessible to novices, and transferrable to other applications. Specifically, relevant to scientific computing and data analysis are the rich ecosystems which have developed upon both these languages. These ecosystems consist of many software packages, standard practices and, last but not least, active communities. Thus, we teach tools which are not only effective at solving problems found in scientific and data-driven research, they are also popular, growing, and conducive to sharing, collaboration, and continuous improvement. We could make a similar case for SQL (Structured Query Language), which we teach in both a DC lesson and a SWC lesson. This tool is a standard and key building block for databases. DC workshops start off with a lesson on data organization, where we use spreadsheet software (such as LibreOffice or Microsoft Excel). Such software is usually familiar to learners who have no coding experience. Then, we teach data cleaning with OpenRefine, a FLOSS program which lets users explore, correct, and format data (refining raw data). On a meta level, this software represents a smooth transition from working with graphical interfaces to writing commands and scripting. SWC workshops teach automation with the Unix shell, a very traditional and fundamental tool. It lets the user interact with the computer at a base level, whether by running commands interactively or by scripting. In SWC workshops, we teach version control of source code with Git, a de facto standard. We also teach GitHub, a popular Git-based web service for hosting code repositories and facilitating contribution and collaboration. Meanwhile, we warn learners that their research organizations might recommend or require them to use other hosting platforms.

## The Carpentries Teaching Practices
Carpentries instructors are trained to deliver content using a variety of evidenced-based teaching practices. These techniques include sticky notes, learners using their own machines, minute cards, one up/one down, collaborative note taking (Etherpad), live coding, formative assessment, Code of Conduct, and pre- and post-workshop surveys. A summary of each is provided below.

*Sticky notes* 

Colorful sticky notes are used as status flags throughout workshops. Instructors and helpers float around the room identifying who needs assistance as learners place a sticky note (ex. red) on their computer. In this way, learners do not need to raise their hand and draw attention to themselves, and the lead instructor is able to continue delivering the material.

*Learners use their own machines* 

It is important for learners to leave the workshop with their own machine set up to do real work. This is why we ask learners to bring their own machines to the workshop. Our instructors teach on three major platforms: Linux, Mac OS X, and Windows.

*Minute Cards* 

Twice per day during a workshop, minute cards are collected to get anonymous feedback from learners. Learners are asked to write one positive aspect about the content and deliver of the workshop content, and one negative (or area of improvement). Instructors are encouraged to change the feedback prompt to elicit different types of feedback at each break. Instructors review the minute cards to look for patterns, and address commonly raised issues with the workshop participants. In this way, misconceptions are addressed, and instructors are able to adjust their delivery as needed to ensure learners are grasping the material.

*One up/One down* 

Learners are asked to give feedback at the end of each day using a technique called “one up, one down”. Alternately, learners give one positive and one negative point about the day, without repeating a point that has already been discussed. In this way, learners are encouraged to speak about what they truly think once all the “safe” feedback has been shared. Instructors write down their feedback without commenting while collecting it. Instructors then discuss their feedback and how they explicitly plan to act on it. 

*Collaborative note taking*

The use of collaborative note taking on either an Etherpad or Google document offers an avenue for dialogue and questions to be raised throughout the workshop. Learners are able to share links and bits of code, and the document remains available after the workshop.

*Live coding*

Rather than displaying a slidedeck of code, instructors deliver content by live coding. This method provides learners the opportunity to practice, and receive continuous feedback about their code. It is important to keep in mind, however, that feedback is not helpful if you cannot understand it. Live coding facilitates tacit knowledge (i.e. learning by watching how instructors do things.

*Formative assessment*

Formative assessment, or diagnostic testing, allows instructors to modify teaching and learning activities to improve student learning [11]. The Carpentries’ lesson material include challenge questions (exercises) to help learners evaluate their level of knowledge of the tools covered in the workshop. These challenge questions also offer opportunities for instructors to address misconceptions in content knowledge.

*Code of Conduct*

The Carpentries are committed to making participation in our workshops a harassment-free experience for everyone, regardless of level of experience, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, or religion [6]. We establish norms for interaction by having, discussing, and enforcing a Code of Conduct such that our workshops provide open and inclusive learning environments.

*Pre- and post-workshop surveys*

Learners complete surveys before and after attending a workshop. These surveys include questions to help instructors understand their attendees’ prior experience and backgrounds before the workshop starts. Using this information, instructors can decide how they will approach the material and which exercises are likely to be appropriate for their learners. Additionally, the surveys measure confidence in using the tools covered, and self-efficacy.

# Workshop Impact
An analysis of DC’s workshop impact [12] showed workshops have significant impact on learners. Learners had high means for research computing efficacy, and expressed satisfaction with their instructional team, as mentioned in this quote from a learner:

      “It introduced basic knowledge of data management using robust software and platform. The instructors were well prepared, knowledgeable, very helpful and created an interactive environment to make learning of the skills easier. Overall, they were very enthusiastic in what they were doing.”

Similar results from the analysis of SWC’s workshop impact [13] strongly suggested that workshops provide “a welcoming environment for its learners where the material not only matches the workshop description, but is worth the time learners spend learning it.” These respondents identified acquiring skills they are able to apply immediately in their research and/or job function.

As post-workshop survey results have been positive, we are interested in what long-term effect these workshops are having on learners six-months or more after a workshop, and what lessons learned we can offer the Computing & Information Technology Division of ASEE as growth opportunities for the division. 

# Method
Our goal was to measure the long-term effects our workshops have on learners six months or more after attending a workshop. We are interested in learners’ confidence and motivation to use the tools they learned, and specific behaviors learners adopted after attending a Carpentries workshop.

We compiled existing instruments measuring computer self-efficacy [14], Java programming self-efficacy [15], Python and computational ability [16], self-efficacy towards open source software (OSS) projects [17], and student-instructor relationships [18]. Assessment specialists on staff and from our instructor community used a rubric to vote on whether to omit questions, keep them as-is, or adapt them for the purposes of our data collection. Rather than focusing on learners’ skills in particular tools, we wanted to focus on assessing learner confidence, motivation and adoption of good research practices [19], as these elements represent the primary goals of our workshops. Confidence and motivation promote community building, a significant focus area of The Carpentries.

The final survey instrument included 26 questions. Figure 1 provides a select few questions from the survey. The entire survey, the data set, and code used to prepare this paper is located on our GitHub repository at https://github.com/kariljordan/ASEE.  

The statements below reflect ways in which completing a Carpentry workshop may have impacted you. Please indicate your level of agreement with the statements

+ I have been motivated to seek more knowledge about the tools I learned at the workshop.  
+ I have made my analyses more reproducible as a result of completing the workshop.  
+ I have improved my coding practices as a result of completing the workshop.  
+ I have gained confidence in working with data as a result of completing the workshop.  
Figure 1: Select questions from long-term assessment survey.  

*Survey collection*

The survey was distributed twice: in March 2017 and October 2017, each targeting the group of learners who had completed a workshop in the previous six months. The survey was distributed via electronic mail to learners in our database who are opted in to receive communications from us. Though our database includes nearly 9200 email records, many of the emails were flagged as spam as the survey was sent in mass email mode. About one-third of the intended recipients received the invitation to participate, and we recorded 504 survey responses using SurveyMonkey.

*Data cleaning*

A csv file of the data collected was downloaded from SurveyMonkey and uploaded to OpenRefine for cleaning. Unique identifiers (i.e. IP address, workshop location, and open-ended responses) were removed as our data is open and available on online repositories. These stipulations are in place as part of our Institutional Review Board (IRB) agreement. 
