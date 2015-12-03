---
layout: post
title: "Teaching software testing in Cambodia"
date:   2015-11-04
permalink: /article/teaching-software-testing
hp-image-path: /assets/hp/homepage-teaching.JPG
---
<div class="post-intro-text">
  <p>Could you teach software testing? </p> 
  <p>This the question I asked myself. After three years spent in such a great company as The Net-A-Porter Group 
collaborating, sharing knowledge, practising on workshops with all the other testers, I decided to try a different approach to
my job: what if I was now sharing but with people who did not know software testing at all? This is my teaching experience described: this article is a bit long - I added relevant and nice pictures for your 
reading journey -, so please grab a cup of coffee, have a seat and join me in my story, which I hope will be inspiring.
</p>
</div>
  
  
While I was recently travelling in south-east Asia, I was offered an interesting volunteering experience: teaching software testing to two classes of twenty-five students each who had never heard of it before. I quickly accepted the offer for three reasons:

- Any job that you have been doing for a while becomes a routine, which means that you wear the risk of becoming stale, and forget that continual learning is important; Explaining parts of the job to people who don't know about it requires us to take a big step back and let us realise how much we understand about it ourselves,
- My favourite part of testing being the questioning and the investigation about the software, I was wondering if I could sharpen their interest as well,
- Above all, I wanted to send the message to the students that testing was not just a mandatory class that they had to attend, but rather a very useful mindset to have and that they could apply in many situations.  
              
<h4> A bit of context</h4>
My volunteering experience took place in Phnom Penh, the capital city of Cambodia, at a French Non Governmental Organisation called "Passerelles Numériques" - translated as "digital bridges". Amongst all the available accomodation options, I chose to stay at the boys students dormitory to have a full immersion experience!


<h4>The class objectives</h4>
The software testing class was held within a two-year web development course. Since the students’ English level was very varied, I was introduced to a Khmer teacher who was also teaching database and project management, and who would co-present the class with me. I would create most of the class content, but I still wanted him to review, understand and agree with it, in case he would have to re-explain in Khmer language.

Two major constraints became clear from the start:  

- The class started only few months after the beginning of the course, and so many students were barely familiar with technology concepts; In fact, before joining the NGO, and due to their poor background, some of them had never used a computer. This drawback had a strong impact on the examples and the workshop that we created for the class.
- The class was allocated very few hours when compared to the rest of the program: in fact I was given 20 hours to cover a lot of ground! Testing is unfortunately still not very common in Cambodian companies nowadays. Students were spending lots of time learning various programming languages, database structures and project constraints.

The web development training coordinator gave me lots of freedom for the class content, but at the end of the 20 hours I had to make sure that students were able to:

- Understand what is a requirement,
- Understand what test plan, test case and test steps are,
- Write test cases and test steps on their own with mandatory information,
- Write a bug report with mandatory information.  

I was also advised to set regular small exams every three or four sessions to make sure they were learning, as well as a final exam at the end of the course.

<h4>Where did I start from?</h4>

The previous class material had been written by a developer who had also volunteered and had left the school a long time ago. The problem with such material that you haven't created yourself, it is hard to review and the presentation support obviously contains much less knowledge and content than the author presented during the class. Since that material had been created more than five years before, it felt like resuming a software project after being left aside for a long time: you would never resume it but start it from scratch again given how quickly technology evolves.

Creating the new content while keeping in mind the objectives above was a strange feeling: I was travelling back in time, going back to the basics of testing learnt several years before or in certifications such as ISTQB. I could not talk about Agile nor Kanban methodologies because it was considered too advanced for the student knowledge, and had to stick with the ideal world of customer needs clearly expressed, that are turned into accurate requirements, then well-written specifications, to carry on with test plan, test case, test steps, and bug report. I also could not talk straight away about exploratory testing, that I had practiced it during three years at Net-A-Porter to test the mobile applications, since the main objective was to teach them scripted testing.

Despite of my initial fear regarding all that theory, I realised that all those concepts were nonetheless mandatory to start with, and that the highest added value here was our own teaching perspective based on our personal experience: for example, theory will explain you what a requirement is and how you write it, but it will never give as many powerful examples as the one that you drew from practice in companies, wrapping the theory with useful and practical context. My first feeling of getting bored with presenting all that theory started to fade away.


<h4>Why software testing?</h4>  

Talking about context, I did not get the impression that the previous class material mentioned anything at all about the context of software testing ; After all, why all those students had to sit down listening to us talking for nearly two hours – not entirely true since we tried to interact a lot with them, also giving them the occasion to speak up - ? Like many people, they were probably relating the term "testing" to quick ideas such as "bugs" or "good quality", and sometimes prejudices about tester's role only being to find bugs. A context presentation was clearly missing, and I decided to focus the two-hour first class on that.


<h4> First class, first contact</h4>  

I asked a couple of students their definition of software testing; most of them were indeed linking to "finding problems in sites"; We added their various definitions altogether, and I started to mention the words "questioning", then "investigation". Through various real-life examples of critical bugs, I showed them why software testing was not only mandatory but also useful, that it could save lives – I used the example of the Therac-25 radiotherapy machine bug, which led to several deaths in the 1980's - <a href="https://en.wikipedia.org/wiki/Therac-25" target="_blank">view more information</a>. I completed the first lesson by making them aware of the skills required to be a good tester, and I challenged them with their observation skills for example by watching "the monkey business illusion" video: the statistics were pretty accurate, almost half of the class only saw the gorilla! - if you don't know about this video, you can watch it <a href="https://www.youtube.com/watch?v=IGQmdoK_ZfY" target="_blank">here.</a>

The first class was important as it got students attention, which was confirmed to me by the Khmer teacher later on and also the positive feedback coming from a poll that was made after the software testing class. The fact of wrapping it with context and using real-life examples and interaction meant that software testing was not just theory, it also had concrete and important applications in their daily life and made them feel involved.  

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\Presenting-Test-Plan.JPG" alt="Presenting the concept of test plan" style="width:420px;height:315px;">
  <p>Presenting the concept of test plan</p>
</div>

<h4> Let's get practical </h4>
Practice through workshops and concrete examples should be mandatory as it is a crucial moment: it is when the message is much more likely to be understood. They also add an incredibly powerful interaction within the class, which renews the attention and the interest for the topic. We used two kinds of learning approach for that.

<h5> The deductive approach </h5>

Consisting of presenting the students with real-life examples AFTER we introduced them to the theory. The most important here was to use examples linked to their daily life, so that it links the class to their personal experience to generate more emotions. I am a firm believer that if you feel emotional and involved, you will remember it better and longer. Here are two cases in which we used this deductive approach.

First case is while we were explaining the concepts of customer needs and requirements to the students, we took the example of a library as the system under test, and we interacted with the whole class to identify the different type of customers using that system. Students had all used the library many times at school, and many of them were raising their hand, willing to add their 50 cents: we soon identified various customers, such as the librarian, the student, the teacher, the cleaner, etc and for each of them we came up with several specific requirements that could not be related to other customer profile. It perfectly illustrated the message that a system can have different requirements depending on the customer profile. The interaction was a success, probably because students used their memories and their personal experience as a source of inspiration, and felt more engaged.

We did not only write on a whiteboard, we also used real objects as concrete examples. In the first lesson, to introduce the students with the concept of risk that testers should be able to identify, we took the whole class down to the car park – which is more a motor park – to look at a motorbike. They split into teams of four and five and were allowed to touch and use it, in order to draw a list of risks that they would identify if they were testing it. We – my Khmer colleague and I – realised that they engaged straight away: they turned the engine and the lights on, used the brakes, used the accelerator to let the wheel spinning in the air – the motorbike was standing on a clutch for that to happen -, looked at every inch of it and drew a long list of potential risks. When we reviewed the list of items they wrote in the following class, they immediately connected and recognised their findings: we used their active state of mind to present them with the conclusions of the practice to get the message across more effectively.

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\Risks-Motorcycle.JPG" alt="Looking for risks in a motorcycle" style="width:420px;height:236px;">
  <p>Looking for risks in a motorcycle</p>
</div>

<h5> The inductive approach </h5>

You start from a concrete example and leave students to solve a problem, giving them some hints to help them finding the answers if needed: This way they can build their way up to conclusions and realise the meaning of the exercise. You only start explaining the theory after making sure that they came up with useful conclusions.

An interesting inductive exercise that I particularly liked to create and animate was a workshop on requirements. My goal was to show the students the danger that confusing requirements represent when testing a software’s functionality. I asked them to split into teams of five, assigned them to a specific computer per team where the software was installed – we used "free address book" from Gas Softwares - and I gave each team a sheet with five requirements to test against. They were allowed to ask us – I and Sophea, the Khmer teacher – any questions, but NOT allowed to request help from other teams. It was their first time in the class of being autonomous with an application, and I was curious to discover, besides my main objective, if they liked testing a real application.

After collecting their answers and analysing the results, we presented the latter in the following class, and we thought it was a success, for many reasons:  

- Students hadn't realised that some teams had different requirements, so their answers were not influenced and therefore honest,  
- The teams which had confusing requirements – which obviously we slipped in on purpose – asked us many questions during the practice to clarify them. They clearly questioned what they were given, for example "User should be able to manage data": what does 'manage' include ? Adding, removing, changing ? Also, 'data' could refer to contacts data, or settings data, or both ? We obtained a completely different behaviour with the teams who had unambiguous and precise requirements, naming a very specific feature and action, such as "user should be able to add a new contact": the only questions they asked us in fact was, after they had filled in their sheet so fast, if they could carry on testing the application !  
- As the answers depended on their own interpretation which was itself something very subjective, teams with the same vague requirements did not have the same answers at all and wrote them in an open way: some understood 'manage data' as including the software setttings, some others not. On the contrary, lucky teams with precise requirements all gave the same closed answer: Yes or No, as there was no ambiguity.

While I was presenting the results on the slides, I could see many students shaking their head and nodding. We asked a couple of them afterwards to re-explain us what they learnt from the workshop: their feedback was positive and we were pleased with it. Since they had done the practice first, faced the problem and had to react to it to find a solution, they understood the conclusions faster.

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\Req-unclear.JPG" alt="Group instructions with unclear requirements" style="width:237px;height:420px;">
  <img src="\assets\Post-Teaching-Testing\Req-clear.JPG" alt="Group instructions with clear requirements" style="width:237px;height:420px;">
  <p>Group instructions with unclear - to the left - and precise - to the right - requirements</p>
</div>

<h4>Positive thoughts about my experience</h4>
Each experience always comes with a bunch of positive and negative aspect, very useful to learn from. I summarised here what I particularly found positive and that I enjoyed during this teaching experience.

<h5>Examples chosen wisely</h5>

Using concrete examples linked to students' daily life was a powerful way of getting the message across; even when we tested websites that they thought they knew very well because they were using it a lot – such as Gmail –, they still discovered new features and we did not lose their attention. Selecting the wrong examples may end up with losing the students attention.

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\Presenting-environment-1.JPG" alt="Teacher presenting the concept of environment in class" style="width:300px;height:225px;">
  <img src="\assets\Post-Teaching-Testing\Presenting-environment-2.JPG" alt="Teacher writing on whiteboard" style="width:300px;height:225px;">
  <p>Defining the concept of environment and parameters using motorbike example</p>
</div>

<h5>Always innovate</h5>

The enthusiasm of the students with the new ideas we came up with to make the class even more interactive was very rewarding. An example is when my colleague created a system of cards to make the quiz more interesting, instead of the previous "Yes" or "No" system: each card had a different letter, ranging from A to E, and each team had to select for each question the one matching the correct answer on the slides and raise it in the air. The cards received an incredibly spontaneous welcome by judging on their bright smile and their participation. This innovation brought two benefits:
students had to reflect more to answer a question, as there were now five different choices,
they were interacting more with their fellow students within the same team, in order to not raise the wrong card.

<h5>Each class is unique</h5>

At first, I feared that I would get bored because I had to present the same lesson twice. However I realised that each class is unique: different atmosphere, different pace for understanding the lesson, different questions. Despite of the same content, you have to adapt to these changes: using more visual diagrams and examples on the whiteboard here, interacting with more or less students there depending on how well they perform,

<h5>Constant feedback to improve</h5>

This title could draw a parallel with the lean start-up model – if you don't know about lean start-up, you can read the <a href="http://theleanstartup.com/book" target="_blank" > book from Eric Ries </a> for more information–. Since you have to present the same content twice, the first class can be seen as a trial to improve the second: I was writing down notes about what went wrong and what went well, what we could do better, and always had a quick chat with my co-worker Sophea to have his unique insights that only him could have due to his knowledge of the students behaviour and due to his khmer understanding. I really enjoyed that moment of taking a step back and coming up with improvements. What was clever about the time schedule was how the the two classes A & B alternated, letting all students benefiting from the 'improved' lesson version.

<h5>Create useful workshops</h5>

The most efficient way to create a presentation or a workshop that I have found so far is to process backwards: it means you start from the objectives, or, if you are a tester, from putting yourself into students' shoes to imagine what they would like to learn from it ; You add then the content to fulfil that goal and you finally build the presentation.
During the workshop practice, I was very keen to see if I managed to stir up their curiosity with testing afterwards, and in fact after one workshop we had to stop them from testing some software as they had not heard the bell ringing !

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\Interrogating.JPG" alt="A student being questioned" style="width:420px;height:315px;">
  <p>Active participation gave the students a strong incentive</p>
</div>

<h4>Negative sides: </h4>
Yes, there were few negative sides ! - there are always negative sides in any experience, aren't there ?- Here are my thoughts on what came up as less shiny.

<h5>The size of the class</h5>

In my previous experience at work, we regularly had testing workshops with small groups: these are great because each contributor can have his own time to freely speak and interact with the animator. Therefore you can guess that animating workshops with two classes of... twenty-five students within the short time constraints was a real challenge:  
- When we split into big groups of four or five due to material availability issues, we had more time to explain the instructions and interact with the teams, but five is a big number to use one or two machines and I felt that they were a bit cramped and that the one on the sides did not get as involved as the ones controlling the computer,  
- When we divided them into smaller groups of two or three, they were more involved within their team but we had to compromise more time to fix the environment issues – as there were more computers used – versus the instructions and interaction.

<h5>The time constraints</h5>

Twenty hours of class were initially allowed to cover all the basics: it was such a short time! We had to juggle between the time dedicated to the theory concepts to cover the mandatory objectives, and the not-so-mandatory-but-still-very-important time to practice testing, which you need to understand what we are blathering about.
Added to these constraints, two hours of class goes really fast ! It means you have to constantly and carefully manage your time, and take the heart-breaking decision of stopping an activity going very well for the sake of finishing your class with less exciting theoretical concepts.
Fortunately, towards the end we were allowed to add a couple of extra hours into the schedule to complete the class.

<h5>No exploratory testing...</h5>

The time constraints clearly did not go in favour of exploratory testing coverage. Being my main testing methodology at Net-A-Porter group during three years, I was waiting for that, you know, tiny moment of glory to present this extremely efficient way of testing an application with its serendipitous side – this is only my personal opinion. From the beginning I knew teaching this concept would be a bonus, since I had been warned that the software testing landscape in Cambodia did not yet encourage this methodology.

<h4>What if I had to do it again?</h4>
I would be very happy of course ! To conclude this article, here are few thoughts regarding what I would do differently to optimize the course.

<h5>Each word counts</h5>

I was surprised by the impact that the words I used during the first lesson had in students' mind. I showed them a testing lifecycle containing different steps described by different words, and we particularly insisted on them memorising those steps – my colleague insisted more than me, since I thought the steps were representing more an idea than a specific word to learn –, because it turned out it was really helping them with this new topic. They particularly liked the idea of a visual diagram with precise words that was describing the topic better than abstract concepts.

After a few lessons, I realised that when referring to one of the lifecycle steps by using a synonym, I always had the question asked regarding the terminology and this new word. For example they were curious of why we said "Question the specifications" on one hand, and "Investigate the specifications" on another hand. I became very cautious about the words I used afterwards.

In order to fulfil the class objectives also, I had a plan in my head for the next chapters. I had already begun to draft some of these, but I had to stop and reconsider when we both realised that we could not afford to skip one of the testing lifecycle steps. It was indeed very important for most of the students to keep a structured plan in relation with what they learnt before. If we skipped one step, they would not understand the point of presenting us that step in the first chapter and never talk about it again afterwards. They would get confused. It was also a risk to mention that step later, not respecting the order of the lifecycle. Their understanding was linked to a precise structure in their head, and we could not jeopardise it.

<h5>Use more inductive approach</h5>

The inductive approach that I described earlier in this article proved to be very useful: we had a highly satisfying participation and response rate when involving the students more, letting them think first before coming up with ideas. They were sharing their personal experience more, giving us powerful examples for the class. Connecting with that personal experience generated more emotions and they felt more engaged and interested as the topic had concrete applications within their daily life. As a consequence, I would probably try to prioritise this approach over the deductive approach, though I think using a combination of both is definitely optimum.

<h5>Hook into other concrete topics</h5>

Unfortunately due to the time constraints, we were limited with creating more workshops and homework, but if I was allowed more time, I would definitely start hooking the testing class into their other development topics: what is better than having a real application to test, and furthermore an application that they coded themselves ? It would really develop their sense of responsibility and ownership towards their code and increase its quality. They would become more analytical and critical regarding requirements and specifications that can be given. It would reinforce their collaboration with testers and stakeholders when starting to work for companies, and we know how much it is valuable to software quality.

<div class="image-post-centered">
  <img src="\assets\Post-Teaching-Testing\allclass.JPG" alt="The two classes reunited" style="width:420px;height:315px;">
  <p>Thank you for your attention!</p>
</div>
