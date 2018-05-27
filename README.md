# Minimal Marketable Learning
## Building Software Craftsmanship Incrementally
### by David Kessler

## Introduction

Technology is accelerating at a dizzying pace and we are failing to keep up. This rate of change is stretching young and old alike. The newest app or gadget expands our capabilities and imagination. I grew up with a rotary phone tethered to our small-town Iowa kitchen wall. Cordless and then cellular phones felt like revolutionary advances in technology. Our first Motorola 2900 bag phone was a two-pound brick in a black carrying case. While it only worked on major highways and in large cities it felt like something out of the Twilight Zone. Fast forward and my cell phone is over eighty percent smaller and lighter than that pivotal bag phone. Beyond size and weight, it runs circles around our first Macintosh Classic II home computer. The combination of phone, video, photo, music, movies, web, apps, gyroscope, accelerometer, and a growing number of new sensors and apps provide an unprecedented user experience.  My current phone contains more technology than we could have afforded growing up let alone imagined forty years ago.

As I write the first draft of this learning guide on my iPad Pro(r) I easily take for granted the ease of jotting down my thoughts with my Apple Pencil(r). This elegant interaction with technology sets the stage for teaching technology to the next generation. Gone are the years when students were impressed when they printed the text "Hello World" for the first time. Technology is an accepted and expected part of everyday life. 

This point was recently driven home to me when my 10-year-old daughter was shocked that the internet was not free. She views the World Wide Web as a basic human need.  In fact, you'd think our house was on fire when our internet goes down or it becomes our connection speed is spotty. We've come to expect instant results. Expectantly impatient we Google it or just ask Alexa. Instant feedback is expected. 

The profound paradox is that building these technological extensions of humanity is much slower and incremental in nature than the resulting user experiences we create. Even the simplest app that accepts and stores a person's name on the web requires a staggering amount of knowhow. The slow rate at which we can acquire this type of basic knowledge is a boulder sized impediment for our industry.

### Overcoming Boulders
As I got my start in software development I slowly hacked my way through this boulder. This journey initially started out of desperation and eventually continued out of my love for value creation. 

It was 1999 and I was folding pants at a department store in St. Louis. My wife and I were pregnant with our first child and my minimum wage job was barely covering our meager expenses. To make ends meet I took a temporary job. My first assignment was scrubbing Enterprise Resource Planning software documentation. This mind-numbing job turned me into a human find-and-replace job. One of my teammates showed me how to record and modify Microsoft Word(r) macros. This significantly increased my accuracy and gave me a little exposure to a scripting language.  

Around the same time, someone at our church had started a software company to meet the rising demand that the Y2K bug had created. I inquired if they might have an opening and they asked me to learn Visual Basic (VB) 5 before they would consider my resume. I immediately went out and bought the book "Teach
Yourself Visual Basic 5 in 21 Days." While I never got a job with this startup, I quickly realized that the macros that I was editing were written in VBScript. I knuckles down and learned everything I could about VB.  Desperation to find permanent employment fueled my drive to learn.

My next temporary assignment was in a biotech research department. I was asked to catalog all their research in a Microsoft Access (r) Database. I quickly became the only team member that knew how to build SQL queries. These minimal skills eventually landed me a job back in our home state of Iowa. 

I joined a tech support team at Iowa Student Loan in the Fall of 2001. I quickly found our Microsoft Excel (r) based issue tracking system cumbersome and lacking. I built a Microsoft Access(r) issue tracker that provided forms, reporting and business analytics.  I leveraged my self-taught SQL and Visual Basic skills to build my first app. 

This achievement inspired my next creation. Our team spent a significant amount of time reading and modifying flat files. This cryptic student loan file specification was difficult to learn and manual changes were error prone. I decided to build a flat file parser with, you guessed it, Access, VB, and SQL. These two applications became so vital for our tech support team and our management team that it presented a support risk for our company. 

I was an untrained hack that had built business critical applications in my evenings and weekends. As such, I had unwittingly put them between a rock and a hard place. They didn't want me to build any more non-supported applications but they also relied too heavily on these tools to completely move away from these solutions.

This growing tension paired with the mind-numbing repetition of my day job brought me to a life altering decision. My real job primarily consisted of support calls and testing our companies first web application. Testing applications by hand was painfully repetitions and error prone. Out of my love for automation I began to record my own tests. This started to help but the web app reports still had to be tested by hand. I was task with verifying these reports' content, layout and formatting. I couldn't find a way, at the time, to automatically verify these PDF reports. With all the sorting and grouping options a mere dozen reports multiplied into hundreds of reporting variations. 

I was sick of testing the same thing over and over. Even if I verified that thousands of things were right for every new release it only took one oversight to draw the ire of our customers and management. These were mission critical reports for financial aid offices all around the state of Iowa and it was solely on my shoulders to make sure their records were accurate, reliable and usable. 

My rising frustration with my current position motivated me to make a costly gamble. Without any guarantee of employment, I went back to school for my Master in Software Development and Management. with three kids, we were barely paying all our bills month-to-month. This only got more complicated when we got pregnant with our second set of twins while I was in grad school. I was working full time, studying thirty hours a week and we were falling behind financially. Only by the grace of God was I hired as a Junior Software Developer two months before my December graduation.

As I transitioned from tech support to app development, I was ill prepared to develop full-stack, enterprise applications. But again, I was blessed to be in the right place at the right time. Our department was an early adopter of Agile software development. We drank the Extreme Programming (XP) cool aid. XP introduced a practice called pair programming.  As a result, I was paired up with a senior developer 6 hours a day 5 days a week. 

I recently added up all those years of pairing and calculated that I paired for over ten-thousand hours. This practice coupled with test-driven-development accelerated my skill sets from a novice developer to a seasoned expert craftsman in nine short years.

### The Problem
After nearly two decades of developing software, leading teams, hiring and mentoring team members, I've come to realize that we are failing the next generation of Software developers. This realization began to emerge as the Chair of the Des Moines Area Community College (DMACC) IT Partnership, Application Development Subcommittee. I was challenged by the question of how to train up new application developers in only two short years so they are prepared to land a tech job. How could I help DMACC align their Application Development program with industry readiness? 

Over the next year, I met with every employer in the Des Moines area that built software in-house. What I found was unsurprisingly tragic. No matter the employer and no matter the higher education institution, new grads were only 20% prepared to develop software. Whether new grads had a DMACC, University of Iowa, Iowa State University, Purdue or Notre Dame degree they were ill prepared to build mission-Critical applications. I'd often mused to my colleagues that every new grad I hired had to be retrained. Sadly, we've accepted this as a norm in our industry. What if lawyers, doctors, accountants, and engineers were only 20% ready to provide real-world value? Would we continue paying for this education and hiring them to affect real people's lives? 

The average four-year degree, in the U.S., costs about $90,000 while the average two-year degree costs $14,000.  However, the staggeringly high demand within our industry has blinded us from asking why we are perpetuating a process that costs so much even though we just turn around and retrain our work force anyway.

In Agile software development, we avoid this big all or nothing investment by slice large user needs into small valuable pieces.  This Minimal Marketable Product(MMP) is a working solution ready for users at any given point. Breaking up our investment drastically reduces our risk and provides early returns on our investment.  Within academia, how might we leverage this iterative approach as we teach new software developers?  How might we create a Minimal Marketable Learning (MML) environment? A learning process where Students could gain real world returns earlier in their learning journey.  

To make this pivot we must realize that this is a 3-part problem. First, technology is a moving target that is outpacing our ability to learn and adapt. Thomas Friedman illustrates this rate of change acceleration. (insert graph). LinkedIn 2017 Workplace Learning Report echoes this gap stating that tech skills have a limited shelf-life. In less than 5 short years your skill relevance is out-of-date. Consequently, as software professionals we have come to expect that we must be continuous learners to remain relevant. This rapid learning is reflected in popular books like "Seven Languages in Seven Weeks". 

The tragic paradox is that the skills learned in a four-year degree are out-of-date by the time graduates land their first job. That's if their applied skills were even aligned with the rapidly changing languages, tools, frameworks and techniques within our industry. Tragically curriculum boards, department heads and professors are ill equipped to remain relevant beyond fundamental concepts. Curriculum changes take years to manifest in the classrooms. This mismatch partially accounts for the dismal 20% industry readiness of new graduates.

Secondly, full-stack, enterprise development requires a deep alphabet soup of technologies that is significantly different within each employer. As I met with every IT employer throughout the Des Moines Area I built a local skill demand radar. This initial sampling surfaced close to 500 technology skills required to build full-stack applications. While this spanned numerous languages and frameworks it painted a daunting picture as our Subcommittee attempted to help DMACC prepare their students for our industry. Even after filtering down to the top-most, in-demand local skills, it encompassed 40 skills that I couldn't have claimed to have fully mastered. The sheer breadth of this knowledge could not be sufficiently taught in four years, let alone in two. Even if we narrowed the scope to a single stack of enterprise technologies it almost always spans a half dozen technologies. 

I remember looking at my first application developer job description and wondering how I could ever learn that daunting laundry list of skills. Many of the listed acronyms and cryptic names I'd never even heard of.

Third, Courses and tutorials rarely put these technologies together in a real-world application. While students may have a broad understanding of a smorgasbord of topics they are ill equipped to build a valuable solution.  Capstone projects and internships are often used to put their learning together.  Even these often fall short.  

### What Works
In the software industry, we've come to realize that the late integration of smaller pieces is risky and often ends in disaster.  This late integration approach is called Waterfall software development.  While few software organizations continue to cling to traditional Waterfall software development, our higher learning often follows a Waterfall like trajectory.  

In contrast to Waterfall, Agile software development values working software.  This approach encourages small bets and quick feedback.  Extreme Programming's (XP) engineering practices add pair programming for continuous peer feedback.  XP also teaches test-driven-development that drives developers to incrementally build solutions with empiric, automated test feedback. The Craftsmanship movement has built on XP to define a professional code of conduct for software developers.  As enterprise applications grow and change they become ridged and difficult to change without true software Craftsmanship. 

So how might we create a curriculum that anchors students to working, full-stack software that provides quick feedback loops. Well part of the answer evolved within MIT Media Lab.  They wanted to figure out how to teach 8 year olds how to code. Their target market got bored easily, has a limited vocabulary, and demands instant feedback.  Out of this challenging problem set emerged a visual programming language called Scratch that's used by numerous elementary, high school, college, boot camp and even corporate trainers.  This low friction language provides almost instantaneous student feedback.  The key to its success is its absence of learning obstacles.  Key programmatic concepts can be introduced and used in a matter of minutes. This creates a tight feedback loop where learning can be iteratively layered.  This layering is key to successful learning pathways.  

Scratch is a great way to teach core programming logic to entry level students. In fact, a friend of mine, Tony Kook, and I co-founded Tech Journey and our students love scratch.  Over the past five years, our team has helped over one-hundred students start their journey in technology.  

As a consultant, I used Scratch to level the playing field so that teams comprised of technical and non-technical teammates can build a video game together over the course of a few days.  Scratch's simplicity allows me to guide the team through tight Agile software development cycles without the distractions associated with heavy development tech stacks.  Plus, it's just great fun building a Pac Man game in 30 minute iterations.  Teams demonstrate working software every half an hour to other teams.  This sets the right stage for rapid and incremental application development.  

Scratch can be great fun for new teams to learn, launch, and laugh.  Pushed to its limits Scratch can build quite sophisticated applications.  Nevertheless, these apps will never make it to production in a Fortune 500 company.  So how might we take the power of Scratch to the next level?   

### Learning Approach
In this book, I will build a curriculum around five principles: working software, clean code, full-stack, layered learning and enterprise quality.  My hypothesis is that if students start with a full-stack, enterprise application within the first few lessons they can incrementally expand their knowledge throughout the many facets of an enterprise application.  All learning will be test driven and all grading will be based on working software and clean coding standards.  Students that complete this course work will break flip the 20% industry readiness on its head.  Graduates will understand how to build, modify, and deploy enterprise solutions.  They will understand key concepts and principles. They will be ready to hit the ground running instead of requiring retraining. 

To test this hypothesis this curriculum will build and tested iteratively. Big bang Waterfall projects don't succeed in the software industry why would it work in education either.  This build, test, adapt cycle will require a team of editors, students and instructors.  I am personally inviting you to contribute to this project.  Join me in helping anyone, from any background follow the dreams of building software that matters.  Let's make this path as smooth as possible.  I believe that anyone should be able to follow their dreams even if they are folding pants in a department store like I was.  Thank you.  
