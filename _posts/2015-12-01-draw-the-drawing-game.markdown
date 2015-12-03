---
layout: post
title: "Draw the drawing game"
date:   2015-12-01
permalink: /article/draw-the-drawing-game
hp-image-path: /assets/hp/homepage_drawing-game.jpg
---
<div class="post-intro-text">
  <p> Shortly after I arrived in the town of Lyon, France, I found out through the Meetup.com website about 
  the CARA association   which promotes the Agile methodology in the IT sector in the region of Rhône-Alpes 
  and gathers nearly 450 members on the Linkedin network. They were sponsoring the Agile workshop that 
  I took part in and which is described in this article.<br><br><br></p>
</div>

Searching for new professional events to attend, I found a new workshop session on the PODOJO group on Meetup.com website: the description mentioned a game called “Draw the drawing game”, apparently related to functional specifications, and inspired from Alistair Cockburn, co-signatory of the Agile Manifesto. I had never heard of this game before, so it was the perfect time to try it out. 

Though the group seemed to be primarily addressed to Product Owners, I thought I could get a lot from their upcoming session: after all my experience of test analyst was strongly intertwined with specifications and helping to create new functionalities, it was an excellent opportunity to meet people who used the same methodology in their work daily, and... I really liked the sound of the name 'PODOJO'. In fact, the latter reminded me of the 'Testing dojo' area which takes place each year during the Eurostar software testing conference and where people present various test tools and techniques: 'Product Owner Dojo' was promising, maybe I would get a real training from some of the finest Agile masters in Lyon?

<h4>First impressions</h4>

About ten people turned up at the event, and three organisers were there to welcome us. Two of them were Agile coach, and most of the people attending were product owners. There was a good mix of technical and functional backgrounds as I met for example a Product Owner who had been a tester during three years, a Scrum master who had been a developer for years before his recent conversion and a student developer who was interested in the matter.

<h4>The game rules</h4>

The game takes place in several rounds – in our case four. Each team needs to contain at least four people, and team members split into two different roles: 'Specifiers' and 'Artists'. The objective is simple: the Specifiers see an original drawing which is representing the final product, then have to write concise instructions – pictures are forbidden. Only one Specifier, called the Messenger, can move at a time to carry those instructions over to the Artists who have to reproduce the drawing. Defining strict communication rules between the two parts is key to a successful workshop.


<h4>Round 1: Being on Specifier side</h4>

I started as a Specifier. My colleague and I went to sit in a separate room from the Artists, and we were given only a ten minutes window to write specifications AND have them reproduce the drawing – it makes sense as separating each phase would involve working in a V cycle, the complete opposite of what the game stood for. The communication rule was that we were not allowed to speak to the Artists when showing the written specifications; Instead, we could eventually point with our finger to give hints.

<h5>How did we perform?</h5>

The first original drawing was easy to describe: there was a main frame and four main shapes inside such as a spiral or a losange. We immediately knew we would not have enough time to detail them all, and since we had not been given any specific requirement from the organiser, we assumed that all of the shapes were equally important and all wanted by the customer – in our case the organiser. After a quick discussion, where I used the argument of getting feedback as quickly as possible following the lean startup concepts, we decided to draft a first rough description for all the shapes; We would then refine the specification based on the artists understanding.

<div class="image-post-centered">
  <img src="\assets\Post-Draw-Drawing-Game\Drawing-Example.png" alt="Example of drawing" style="width:214px;height:300px;">
  <p>Example of drawing to reproduce</p>
</div>

My colleague wrote a first line to explain how to draw a frame symbol, and this is when my tester mindset sprung up: it did not mention anything about margins so the Artists would not know which size it had. We added the information, and moved on to the next shape. All shapes were inside the frame; I put myself into the Artists' shoe, and thought we should start by including the position of each shape relatively to the main frame, such as designers would need to specify it for developers.

However, we got carried away with the writing and suddenly realised that we had...only four minutes left for the artists to start reproducing the drawing! My colleague quickly brought them the first set of instructions while I started to describe the remaining symbols. She came back with a useful feedback, explaining what they did not understand and what we should clarify. Unfortunately we ran out of time at that point.

<h5>What did we learn from it?</h5>

We spent five minutes to debrief with the Artists: first point was, carried away by the specification, we did not realise that they waited during six minutes before the first instructions arrived, which was a long time of inactivity! We identified this weakness and, as an improvement for the next round, we decided to bring them smaller bits of specification to be more efficient, so that while Specifier W1 focused on feature A with the Artists, Specifier W2 was describing feature B.

We also realised that our description for the main frame was way too complex when it could have been easily resumed and understood in a simple line: “frame with one centimeter margin from each side of the sheet”. 

<h4>Round 2: Introducing customer requirements</h4>

The difference was the introduction of short requirements from the organiser. Amongst many shapes in the new drawings he showed us, he pointed a few of them as mandatory, and also gave a specific instruction regarding one semi-circle: the outcome wanted was different from what it looked like on the original set.

<h5>How did we perform?</h5>

Immediately priorising the requirements given, we started to deliver small and incremental pieces of specifications to the Artists. Each of them referred to either a whole symbol if it was not too complex, either to part of it if it took too long to be described in one go.

Since I was appointed as the Messenger this time, I could experience myself the fact that our set of instructions led to ambiguous interpretations. I have to admit that I am not using geometry every day, and my bad memory towards the shape geometric rules did not really help me there; For example, I wrote that “all sides of the losange should be of same length”. Silly me. Everyone knows – yes I trust you to remember that – a losange always has this condition fulfilled. However, the Artists spotted that redundancy straight away and were more confused with the description of the losange's relative position towards the main frame. Since I still could not exchange a single word with them, they drew three prototypes. It was an excellent idea: I quickly understood through the visual outcome how to refine the instruction to keep the only right prototype.

<h5>What did we learn from it?</h5>

As a consequence of our improvements, we managed to deliver almost all the mandatory requirements, apart from a wrong misorientation of the semi-circle, due to a misunderstanding. We deduced that we should have written down quickly what the organisers initially told us, or at least double-checked by repeating to him what we understood. This is of course applicable to any User Story in a Software Development Life Cycle, which you have to keep a minimal set of written instructions for, whether it is just Test Acceptance Criteria or document specifications.


<h4>Round 3: Swapping roles</h4>
In the 3rd round we swapped roles, which means I became an Artist. We decided to get organised before the first set of instructions arrives, and split the tasks: one Artist would read the specifications out loud, the second would draw draft prototypes to the Specifier Messenger to pinpoint the expected outcome, and I would take care of drawing the final product.

The round happened very similarly to the first two, except that our colleagues reduced the risk of misunderstanding, as shapes became harder to describe, by introducing a system of coordinates: they started to bring several of those to locate the structural points of the shape, then brought the instructions of how to link each of them, for example, “between A1 (3;6) and A2(4;6), draw a line and cross it with a perpendicular one of same length”. It was efficient, we could insert the coordinates directly on the final drawing and only had to prototype the links shapes.


<h4>Round 4: Changing the communication rules</h4>
In this last round Specifiers were allowed to sit in the same room as the Artists and talk to them: we now had a face-to-face conversation.

Those new rules made a clear difference in how much we managed to deliver on the final drawing. Though some shapes were incredibly hard to describe – for example some kind of big 'C' shape slightly flattened and crossed by various lines not even parallel to each other –, the oral communication made it much easier for us to get the instructions right, since we were getting an immediate feedback from the Specifier to amend the prototypes.

One of the real challenges I can highlight here was for the Specifiers to deal with who was talking. They clearly could not speak both at the same time to avoid confusion, which means they had to consider each other and agree, which they remarkably did mostly via subtle signs such as head signs.

<h4>What did I learn from the game and how it relates to software testing</h4>
I already mentioned for the two first rounds that I learnt a lot about how to optimise a feature delivery through small sets of instructions in order to get faster feedback. Software testing ideally should not be done in one big block either. It needs to be done as soon as bits of the feature are available, whether it is only data, web services or Graphical User Interface. It allows testers to explore and verify if the development goes along with the first requirements discussed and Product Owner's first expectations. The team then carries on building the software as discussions and refinements follow testing feedback. If critical bugs make their way into the software, we can spot it at a very early phase, which dramatically decreases the product risks and project costs. 

Besides the efficiency of quick feedback, I learnt two more useful points that night.

The first is that connecting with Specifiers to understand their needs and to turn them into a concrete offering is not easy. Drawing prototypes to visualise your thoughts is really helpful: it is an efficient insight given to the Specifier about the way your mind interprets his instructions, and it is a good starting point to make sure the further discussions go into the same direction. At my previous work experience in London, we used to draw a lot on whiteboards before even starting with the wireframe, during the requirements discussion meeting: I admit I don't really see the implications or can not really add my 50 cents until I can visualise what we are talking about. Even when I am testing, I like to include diagrams and as many visual representations of the system as I need to feel that I am properly tackling the challenges of a functionality.

The last point is that, the more verbal and close the communication becomes, the faster you get feedback and can adapt or change your offering to match the initial expectations. From an Agile perspective, being physically co-located with the team is primordial. Unfortunately, real-life experiences are rarely filling this condition in, and the game reminds us of an important criteria that we often forget or don't realise when involved in a project: the time wasted in trying to establish communication. 
Indeed, the game conditions are ideal: despite of the distance separating the two rooms and the restrictions with speaking to Artists, everyone is available and focused on the same project at the same time. In my own experience, which is probably also the case for most testers as well, it is sometimes hard to schedule a verbal meeting, whether it is face-to-face or over the phone. Each of the team member can be involved with various meetings, pressured with other deadlines or live issues to fix, and finding the time to discuss a simple matter can be tricky. We never realise the amount of time spent in trying to establish this communication, and “Draw the drawing game” reminds us the reality of it.

<div class="image-post-centered">
  <img src="\assets\Post-Draw-Drawing-Game\Diagram_Communication-Effectiveness.jpg" alt="Diagram Richness of Communication VS Effectiveness" style="width:420px;height:290px;">
  <p>Alistair Cockburn's diagram: richness of communication and its effectiveness associated</p>
</div>


Bibliography:  

You can find the original game rules described on <a href="http://alistair.cockburn.us/The+Draw+the+Drawing+Game" target="_blank" > this page</a>,
and more interesting information regarding Alistair Cockburn's thoughts about Team work 
<a href="http://alistair.cockburn.us/ASD+book+extract%3A+%22Communicating,+cooperating+teams%22" target="_blank"> here</a>.