This blog is about technical leadership and management, and is based on decades of experience. Becoming a manager is hard, and managing technical work is harder yet. Managing managers, or directors, is incredibly difficult. There are few good resources available, few mentors, and the training I've seen has been very limited. Writing about advanced software development methods is a challenge that exceeds my abilities, not because I don't think I know a few useful things, but because it calls for MANY assumptions about what the audience might know or not know. I'm going to cover some beginning topics, some intermediate topics, and some fun stuff, too. The idea is to present content and perspective that you might find interesting if you're a manager, want to become a manager, know a manager, or work for a manager. (I like a challenge!) 

=========================================

 [Introduction to Compound Improvement](https://loudposey.github.io/Compound-Improvement/Introduction.html "Introduction") 
 
 [What is the New Method?](https://loudposey.github.io/Compound-Improvement/NewMethod.html "What is the New Method?")
 
 [Rules of the Road](https://loudposey.github.io/Compound-Improvement/Rules.html "Rules of the Road")

=========================================
## Newest post is on top, and is numbered.
=========================================

### Introduction to Time (4)

After I got out of the Army, I decided to take some college courses toward finishing my degree. I hadn't had trouble with any of the courses I'd taken in Germany, so I signed up for a full load. I also had to work, because my GI Bill benefits were not very good - certainly not enough to live on. Easy fix, I got a job as a graveyard computer operator, and went to class during the day. Yes, I was burning the candle at both ends. I was able to keep up with the course work, but only just barely. There was little time to do the research or thought or writing for the class projects, and I kept kicking the can down the road. Even after the first quarter, I was still looking at the calendar and counting on 8 weeks to finish (well, start AND finish!) those projects before the deadline. As the weeks ticked by, and I made little progress, I was still convincing myself that someday soon I'd find the time to really dig in to the projects. Each week the task seemed more daunting. 

   Push came to shove on a Friday, when the instructor reminded us that the semester projects were due to be turned in on Monday. MONDAY??? I'd missed a detail - this class project was due a week earlier than the others! I'd thought all the projects were still a week away, and that I could pound on them this weekend, all next week, and the following weekend, then turn them in. Don't ask me how I thought I'd be studying for finals, and working during the week! 
   
   Friday night I went for a long walk, around the lake. I was disappointed and angry at myself. I'd procrastinated before, but never to this extent. It all felt pretty hopeless, honestly. I wondered if I'd be better off withdrawing from the classes than failing them, as I couldn't pass any of them without a decent project. I'd done some work on all of them, but was nowhere near finishing any of them, and the mountain looked really high. 
   
   A few years later, I was a programmer, and I had friends on another team that were complaining about their 'death march' project. The project had been planned to take a calendar year, starting in January, and to be done before the Christmas holiday. They'd started late, because the hangover work from the previous year killed a couple weeks in January. A senior programmer got promoted in March, and it took more than a month to replace her - and her replacement needed time to get up to speed, as well as instruction from the other team members. They made good progress for a while, but there was an emergency in July and everyone took at least a week away from their usual work to help out. Some folks had to work on the cleanup, and that took two more weeks. When they got back together and assessed progress against the plan, it was obvious to everyone that they were way behind schedule. In truth, they'd been behind before they started, because between the late start in January, and the early finish for Christmas, they only had 11 months to do a 12 month project - but everyone had been convinced that at some point they'd catch a break and make up for the lost time. Instead, the breaks had gone against them.
   
   Around Labor Day, their boss had pulled everyone in to a team meeting and showed them a revised schedule. They were expected to work 10 hour days, instead of 8, and they'd also work Saturdays until the project was delivered. They'd get Thanksgiving Day off, but not Black Friday. They'd get Christmas and New Years Day off, but no extra days. Working 58 hours per week was expected to increase progress by 50%, so they'd get 6 months of planned work done in the remaining 4 months of the calendar year. I'm sure you can see how this project would turn into a death march!
   
   It was never clear to me why management thought this was a good plan, but that's not the point of the story. What problems can we see in the death march project and their progress?
   
1. The plan, before work ever started, was to do 12 months of work in 11 months. That's not a good plan, because that plan is absolutely counting on catching a couple huge breaks somewhere along the way.
2. The plan contained no slack for contingencies. Having turnover or an emergency were fairly predictable at that company, but were not accounted for in the planning.
3. When the required breaks did not materialize, and instead started to run against the team, they kicked the can down the road, and hoped things would get better. 

   As you can see from that list, I'd already been on my first 'death march', just a few years earlier in college... 
   
   What I learned from my experience in college, and from observing my friends project, became an axiom called 'All days have 24 hours'. There are no magic days, where you can expect to get a week of work done. A day spent handling an emergency cannot be 'made up' by burning the candle at the other end, AND in the middle. This concept is going to recur often, as it bears on several key aspects of product development (sustainable pace, estimation, prioritization, throughput, predictability and others). 
   
   The 'death march' project went about as well as you'd expect. They finished in January, having had a horrible holiday season. Management was briefly happy, as the delivery was close enough to the committed dates to trigger raises and bonuses - for them, not for the team members. The product had a much higher rate of quality issues (bugs, missed functionality, etc.) than we were used to, and their time to fix was terrible, too. About half the team left for new jobs in the months after delivery, 'surprisingly'. The shattered remains of the team were unable to make real progress on a followup delivery, also 'surprisingly' - that led to the manager being let go, and the team being disbanded with the members joining other teams. 
   
   Unfortunately, companies don't necessarily learn from their mistakes. If there's a disconnect between the folks making the decisions (leadership) and people doing the work, and the pain is inflicted on the latter, the former may not make the connection between their decisions and the consequences. 
   
PS - I wrote the paper due on Monday over the weekend and turned it in. I had four papers left, and only 7 calendar days, so I wrote the first paper in one day (enough to turn in), and studied for finals at work. I did the other papers in two days each, and spent any 'extra' time improving the first one-day project. They were all good enough - but I learned a lot more from the experience than just writing some papers!  


### Management Observations, pt 2 (3)

   What is the first thing any Manager should know and understand?  
   
   Seriously, stop reading and ask yourself - what is the FIRST job of a Manager? What should they always be working on, trying to improve, practicing to gain proficiency and understanding?
   
   Please feel free to write down your answer at this time. There will be a quiz. This is the 'Pre-Test'. 
   
...

   Okay, now that you've got your answer down, let's try on a few disasters.
   
The FIRST job of a Manager is:

A) To please my boss!   Ahh, this poor sod took the PHB pill. This is a path of misery. You'll be miserable, your staff will be miserable, and your boss will be mostly miserable. If your boss is competent, you'll be done as a manager, but... That still gives you a 50/50 shot.

B) To deliver on time!   Hmm - an urgency to deliver value is a good indicator, but this is not the first job of a Manager. For example, any development team that had NO manager would have the same goal...

C) To get promoted!   Mr. Machiavelli,  please pick up line 2. While you might get promoted, you'll probably be found out, and treated as well as you've treated your employees. But perhaps not (see the segments about Survivorship Bias, and Clustering of Competencies).

D) To not get fired!   Well, we've all been here, haven't we? But this is not really an objective one can navigate by, as the winds change too frequently. Seriously, the course changes required for this objective are neck-snapping, and will leave one managing an empty boat in no time. 

...

   What is the FIRST job of a Manager?    For many years, my answer to this question was: 'To hire well.' 
   
   One thing I learned early was that good hiring managers get ahead. Their team has more skills, talent, expertise, motivation, spirit, energy, etc., so they find a way to win. It was that way in pickup basketball, and it's that way in every corporation. If you can identify talented people, and persuade them to join you, your chances are vastly improved. 
   
   I can't overstate this one, as it's truly game-changing. If one wants to be a good Manager (AT ANY LEVEL) one must be able to identify, persuade, guide, motivate, entice, and otherwise inveigle talented people to sign on to your rowboat (or yacht, or schooner, or battleship) and not only do the things they already know, but to learn new things, teach others the things they know, inspire each other to learn things no one knows how to do, and soldier on when no one knows how to do anything. 
   
   The rule in my head when rolling teams under this rule was simple, one I'd learned from an grizzled sergeant - 'Take care of your troops, and your troops will take care of you.' 
   
   When I began to assemble teams, I looked for people who showed the behaviors I valued. I trusted them, gave them all kinds of latitude, and hoped for the best - and it worked. And so the First Principle of the New Method was born - 'Hire Well.'
   
   After some years, it came clear that there was a more important FIRST Principle...
   
=========================================

### Management Observations, pt 1 (2)

   When I got my first job in software, the first thing I noticed was that management was not good. They were nice enough people, but they were not super effective. Several didn't seem to know a lot about software development.  
   
   When I realized, a few years later, that I was likely to get a job as a Manager myself, I had to do some hard thinking. What the heck did I know about being a manager? 
   
1. Many tech managers were awful - so if I didn't suck terribly, I'd be considered at least average!
2. Many managers seemed uninterested in their staff - so if I at least paid attention, I might do better!
3. So much of what Scott Adams/Dilbert was printing every day was true - so if I just did better than the PHB, I'd be in the top half of all managers! 

   I wish I could say that I was wrong about any of that, but I wasn't. And it's not that different today, unfortunately. The way technical managers are selected, trained and mentored does not seem to have improved. On the other hand, I've made so many mistakes and had to learn from them, that I've come to realize the power of improvement, and especially Compound Improvement. If you're a manager, looking to become a manager, or are observing managers and you're interested in improvement, you're in the right place. 
   
=========================================

### OBJECTIVE OF THIS BLOG (1) 

   I've worked most of my life in software development, so it's the field I know best. The objective, or problem statement, has changed little over the decades. 'When will it be done?' 'How much will it cost?' 'What should we do first?' 'What will happen if we do X, instead of Y?'
   
   Predictability, or estimation, prediction, fortune telling, or forecasting - if only we could plan better! The objective of every key stakeholder (the person who pays the bills, or is accountable for the paying of the bills) is to reduce the seemingly random chaos they experience in software development. Everything takes longer, costs more, works differently, has unforeseen impacts and surprises. How does anyone have the nerve to call this 'engineering'? 
   
   Let's start with three objectives, for now.
1. Understand management, a bit. 
2. Understand software engineering/development, a bit.
3. Understand predictability, a bit.

(Dang, I'm five bits short!)
(If you don't have a sense of humor, byte me!)

=========================================

### PROLOGUE (0) 
   This mess started in the US Army, Basic Training, at Fort Leonard Wood, Missouri. As raw recruits, we were assigned to squads with a squad leader. Some squad leaders thrived, most failed, some spectacularly. I wondered 'Why are some successful and some not?' and began to try to take notice of the possible contributing factors. Some were loud, some quiet. Some gave clear orders, some gave direction, and some asked for help. Some took the credit for what was accomplished, others pointed to their squad. Some took the blame for what failed, others pointed to their squad... Very strange. 
   
   Today, decades later, I still recall the confusion caused by the myriad possible causes and effects. Early on, many effects seemed random. As I learned a bit, the effects became more predictable.

=========================================
