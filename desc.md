# Project Description

Title: "SBIR Phase I: Homework problems and course support for teaching advanced mathematics and computation"

## Instructions
They want:

- evidence proposed technology is innovative
- development of it entails high technical risk
- have a credible plan to establish technical feasibility during Phase I.
- show that the company and the project team have the necessary expertise, resources, and support to carry out the project,
- team is committed to building a viable business
- present compelling case that the project objectives advance the readiness of the technology and strengthen and validate its commercial position.

The sections below are *NOT* made up.  Each one is mandated by the proposal solitication at http://www.nsf.gov/pubs/2015/nsf15546/nsf15546.htm#projdesc

Once this is cleaned up and looks good, I'll copy paste it to a latex document and it will be done.


WARNING -- I'm now working with desc2.md, which focuses on the actual product we decided to propose -- "


## Elevator Pitch (no more than one page)

> NSF: (no more than one page)
> The Customer. Describe the expected customer for the innovation. What customer needs or market pain points are you addressing?
> The Value Proposition. What are the benefits to the customer of your proposed innovation? What is the key differentiator of your company or technology?
> The Innovation: Succinctly describe your innovation.  What aspects are original, unusual, novel, disruptive, or transformative compared to the current state of the art?

> RAB: - Elevator speech (RAB practiced on curious flight attendant)  "We are starting a company to provide software for advanced mathematics in a web browser (or cloud).  You know how some apps are free, but you subscribe to get additional features?  It will be like that.  So a student can get started very quickly and without any cost.  And it makes it very easy for faculty like me to get a whole class using this powerful software quickly and easily.  The additional features will allow scientists to easily use powerful computers by paying for just the services they use."


The main customer for SageMathCloud (SMC) is academic
researchers that use computation that involves mathematics
and students in their courses.
Academic researchers and their students need very easy and affordable
collaborative access to mathematical software, software development
environments, and tools for writing up and sharing their results.
Instead of worrying about installing and updating software, learning
complicated revision control systems, and figuring out how to use cloud
computing or local resources, our target users want to focus on computing
and teaching their students how to compute.   Some of these users, especially
students and people in developing countries, are extremely price sensitive.
Our proposed innovation would leverage open source software, cheap cloud
computing resources, and systematic optimization based on user feedback
to make all of the above extremely easy, fluid, and affordable for our
customers.

> HSY: regarding the list of pain points (I think they are very important)
> regarding learning RCS -> insert that they actually want to
> collaborate work with other students (that's the painful task they
> want to accomplish)
> also, besides installing and updating software, a huge pain point is
> also the general maintainence of the underlying system.
> Should there be a mentioning that SMC is a 100% web-based solution?

The main difference in our approach is using very deep open source
mathematical software, which we started developing for this purpose
a decade ago, to keep costs down.  Another difference is that we
emphasize constantly developing very efficient technology to make it
much easier for our users to leverage and share cheap cloud computing
resources.

> HSY: I don't really understand "very deep" here.
> "broad spectrum of open source software"?
> also, maybe >90% hasn't been developed by "us"
> the key innovation might be that SMC is built upon a vast pool of
> open source software and leveraging the combined knowledge and experience
> of thousands of developers and millions of work hours
> (maybe not even an exaggeration?)
> by packaging all of this in a neatly integrated, easy-to-use and fully managed
> web-based application.

Our innovation is that we have assembled an efficient
completely open source stack
that handles a huge range of mathematical computation, including
advanced pure mathematics, numerical analysis, and statistics, then
refined it over several years to be efficient.  We have learned much
from the feedback from 100K users and nearly 100 courses that have
used SMC.  We propose to build automated homework, course management,
and powerful collaborative research tools on top of our platform,
which would provide a completely new and dramatically more powerful
approach to education in mathematical and computational disciplines.
In particular, the friction to doing computational research could
be dramatically reduced, and the sophistication of what can be offered
in online computational problem sets and courses could be much
deeper than it currently is.

> HSY: regarding the entire pitch:
> reading this in a "naiive" way, it sounds like there is only
> support for writing program code. what's missing is the aspect of
> "interactive computational documents". with that, I mean IPython Notebook and
> of course sagews. I think this aspect is important, because there
> might be the impression that "just code" has a too limited market reach.
> Such rich computational documents are much more appealing to novice users.
> bonus: this mix of text/code/result is also better suited for publishing
> and hopefully, the reviewers have already seen this
> (besides ipython, alos MMA, maple, etc. would count)

## The Commercial Opportunity (recommended length: 2 to 4 pages)

### Broader societal need

A broader societal need right now that this project addresses is that many people desperately need to know how to use computers effectively for nontrivial tasks that involve mathematics.  By dramatically
reducing the friction to using the tools in education, we will address
this need head on.  Moreover, we will target free open source tools,
so that our users get even greater value out of what they learn.

> HSY: since from the political angle the topic of "jobs" is always hot:
> SMC is also a hands-on learning platform for coding.
> a staggering number of jobs are taken over by automation.
> because a growing amount of information is digitalized,
> mundane/repetitive tasks can be accomplished by computers.
> there will be a growing need of every-day programmers, operating
> these systems, and implementing their domain-specific knowledge.
> (I'm aware that this viewpoint is outside of SMCs mission, but it is
> maybe in the heads of the reviewers. it could be trimmed down to the
> aspect of statistics/data-analysis/applied mathematics in the context of
> business operations)

Another social need is easy world-wide access to computational resources
to carry out projects that themselves benefit society.  Companies already
provide easy free world-wide access to email (gmail), short
communication (twitter),  networking with friends (facebook), and
sharing pictures (instagram), but nobody provides extremely easy
collaborative access to computation at internet scale. Providing this
would potentially enable new innovation worldwide.

> HSY: twitter is "status updates" and what's missing is easy publishing
> I would add: publishing online (wordpress)

### Market and business economics

The market for what we propose to create involving
sophisticated problem creation and course management, is every high
school and undergraduate student in the world who is taking a
course that involves computational mathematics.   Students (esp. in high
school and the developing world) are highly
cost sensitive. And teachers *care* about finding solutions
for their students that are efficient and affordable.

The market for our research related functionality includes
all researchers in STEM fields doing computational mathematics,
both in academia and industry.

> HSY: science/research is increasingly collaborative.
> there is a growing market to support this development
> for computational aspects (data analysis, mathem. computations, etc.)
> random link:
> http://archive.sciencewatch.com/newsletter/2012/201207/multiauthor_papers/
> points out the fact that the number of authors per paper is increasing.
> more general, there is a growing number of research networks
> random link to nature:
> http://www.nature.com/nature/journal/v490/n7420/full/490335a.html
> add something like "increased global collaboration leads to the need for
> better tools to support this shift in research"
> ... because it is stupid to fly around all the time for day-to-day work.

Researchers/teachers are overworked, focused on teaching,
and greatly value convenience for their IT infrastructure.
Even if they could spare the time and have the skills,
the cognitive shift, and lack of pooling of resources
makes them doing things themselves inefficient.


We have validated this market opportunity by creating several iterations
of minimal viable versions of SMC, and made available for free.
We wrote minimal useful course managment functionality, which is nothing
compared to what we propose, but at least makes SMC usable.
SMC has now been used by over 60 courses last quarter and 100K users.
In May 2015, we transitioned to a freemium commercial model and have
had 30 paying customers (with over \$1K revenue during May 2015).
We have also communicated a lot with users **all over the world**.

Our customers are university academic researchers,
hobbyist researchers, and students in courses.
Our business model is that we charge a small percentage of users
a monthly fee to run their projects on better
members-only hardware.  We also provide dedicated resources
that instructors can use for all students in a course they
are teaching, or for research computations. We pay Google (via
the Google Compute Engine cloud) for compute resources, and
exchange for managing the resources, backing up disk, and providing
redundancy, we mark up the base cost by a certain percentage.
We thus make it easy for many unrelated users to
share resources in the cloud and benefit from our experience
using these resources.  The key is that we provide a front-end
for our customers that makes the underlying virtual machines
extremely easy to securely use for teaching a course, or
doing a collaborative research project.   Whenever we sell
dedicated compute resources we make money, since we are simply
marking up their cost to us.  We also keep the cost way down
of the free resources by using preempt instances (that are much
cheaper), and restricting CPU and memory use by users.


1.  Advanced math courses are frequently just one section, so instructors are free to choose whatever books, tools, etc. they fancy.  Suppose they like SMC for the advanced problems that nobody else can do.  Then they may advocate to their colleagues to use SMC for their multi-section courses (calculus) since they know and like the tools.  A version of trickle-down economics.

2. Long-term a great use of SMC free cash flow might be to support authors of textbooks (or others) in creating automated homework problems.  Or maybe SBIR Phase 2 would allow that (I have not read that solicitation yet!).


### The competition

As far as we know, there are no products that do what we propose.
This might be because we started developing this product in various
guises in 2003 (!),  motivated by our own needs, rather than
following other market leaders.

One competitor is Wolfram Research's product *Wolfram Cloud*, which
provides web-based access to Mathematica.  This product is, however, dramatically different since it *only* provides access to Mathematica,
it is very expensive (to protect the closed source Mathematica
boxed software license revenue), all closed source, and has no
collaboration, course management or high performance
computing functionality, which is precisely what we do
propose to have.

> HSY: in general, I think this correct, but there are HPC aspects in
> the "Wolfram Products" spectrum.
> http://www.wolfram.com/finance-platform/features/high-performance-computing.html
> and "coming soon" (which is probably a generalization of the financial platform)
> http://www.wolfram.com/data-science-platform/?source=nav

Another competitor is Wakari.io, which provides a way to use IPython
notebooks online.  But it's much more limited in scope, with no
course management or document editing functionality.
However, it's only for pay plan is \$25/month, which is simply far too expensive for academics to consider for their students.  Wakari has no collaboration support, and nothing to specifically support teaching
or pure mathematics.

> HSY mention pythonanywhere.com ? (I mention it because it is in my google at
> position 1 for "run ipython notebook online")

There are also dozens of automated homework systems such as the
entrenched commercial WebAssign and ALEKS systems.
Their approach fundamentally results in very limited sophistication
of homework problems, and a lack of benefit from network effects.
Our proposed product would be far more useful for more
advanced and computational courses than the these systems,
though there likely will be direct competition, since there
is some overlap.

We expect each of the above products to incrementally improve, but
don't expect any major leaps in the next 8 months when our product
would enter the market.

There are also several coding environments that on their surface appear similar to SMC.  However, it seems that all but one is explicitly designed for either web development or writing commercial Java code.

There are several online LaTeX editing environments like ShareLaTeX, WriteLaTeX, etc.  The SMC latex editor is superior to, or priced-better/comparable environments.   A core difference between more polished online LaTeX editing environments like ShareLaTeX, WriteLaTeX, etc. is rooted in SMCs ability to be a computational environment. The forementioned LaTeX editing environments have no direct way to execute arbitrary code or interpret and transform data of computational results into documents. SMCs general approach offers several ways to embed computations and datasets into documents.  Also, these environments are not designed to be used in teaching a course.

> HSY: one other tiny aspect is "publishing documents".
> SMC is capable of hosting html, pdfs, etc. and my guess is,
> that some of the above are also capable of doing that.
> of course, many of the existing arguments just repeat.

### Key risks in bringing the proposed innovation to market

There are numerous major risks for our technical high performance
computing product, where we make access to cloud computing
resources easier.  A huge risk is that everybody
who is willing to pay is also willing to put the extra work in
to directly use cloud compute resources (rather than our service)
in order to save our market.  So the only users of our service
will be the freeloaders who use it only because they don't have any
money.  We can only mitigate this by making our product add sufficient
value.  Another risk is that because our software is open source,
users who like it enough to pay will instead simply take it and run it themselves on the cloud.  The best way to mitigate this is to make
it SMC maximally benefits from network effects, so that an SMC server
with a large number of users is much, much more valuable to those users
than an SMC server with only a few users.  This requires superb
collaboration, communication, and crowdsourcing functionality.
Moreover, we need to make it so that SMC efficiently shares resources
between users, so there is much more value in 10 users paying us for
a single machine, than 10 users paying Google directly for 10 separate
machines -- to make this the case, we have to make SMC extremely efficient,
good at sharing resources, and really leverage how we know people use
mathematical software interactively (often staring at results, then
computing for a few seconds, then staring, etc.).

Regarding interactive homework, there are dozens of attempts (and much research into ways) to create
innovative interactive homework systems, ways to describe problems to
these systems, strategies for presenting these problems, and techniques
for collating, sharing and making available these problems to others.
Looking at the disappointing results suggests this is a very hard problem,
and perhaps just using a more powerful and flexible platform combined
with our experience, user feedback and new powerful open source software
for mathematics isn't going to be enough.


### Commercialization Approach

Our approach to commercialization is pretty straightforward.  We create
open source software, then run it on Google Compute Engine.  Most users
will try or use the software online for free, but some small percentage will
pay.  For this to work, it's critical that the software be extremely
efficient, since many of our target customers are price sensitive students,
who are already being overcharged for textbooks and tuition.
The primary products we plan to sell are memberships (with a monthly fee) and
dedicated virtual machines that groups of users will share.
Dedicated machines would be rented both by researchers wanting better
compute resources and by teachers (or their students) wanting
better resources for running their classes.
For the dedicated virtual machines we will mark up the price by a fixed
percentage (probably a 50% markup) from what we pay to Google, so there
is no difficulty at all in estimate how much product that we should buy,
and every sale results in profit.   For the membership plans things are
more complicated.

The revenue potential is large, since the potential
market is large... but whether we will create a product good
enough to appeal to even 1% percent of that market is very unclear.


The only resources we need to implement our plan are people to write software
and to communicate with prospective users.  This SBIR would provide enough
financial support to get a good sense of whether or not this product can
be designed and implemented.   All we need to secure these resources is
money to hire the PI, an experienced teacher, and some young
programmers with classroom experience (e.g., undergraduate
and graduate students).  As an academic and founder of the SageMath
software project, the PI has the necessary connections.
If we get this grant, we would hire these people away
from whatever they might otherwise be planning to do.
Our hope is that using revenue and funding the company already has,
we will have people in place for the project at a small percent of
time, and if we get funding from SBIR, we can then fund them to work
a much larger percent of time, with far more ambitious goals.

Timeline: hire people, write software (with regular coding sprints), deploy software, get feedback.

### Potential for Commercialization

SMC adds significant value to cloud computing offerings for math-related activities.  If instructor wants to teach a course that uses open source math software (including R, Sage, Python, etc.) they save enormous amounts of time and get major value added by using SMC instead of trying to do it themselves.  Also, leverage the co-op effect in that we share resources more efficiently across large numbers of users by pooling resources.



#### Product-market fit

SMC currently has over 30K active users, where active means, engaged in the last 30 days according to google analytics.

There are numerous existing (similar) services, which provide proof that
there is demand: collaborative editing of documents (Google docs), course
management for education (Moodle),  the in-house Sage Notebook service,
WebAssign and WebWork for automated homework grading. SMC uniquely
integrates the whole system, implementing most things completely
from scratch, and manages its complexity.

> HSY: besides google docs, should we mention those LaTeX online editors?
> thinking much more generally,
> there is also a market for running computations online -> AWS, GCE, etc.
> "in-house sage notebook" -> there is pythonanywhere.com and wakari.io for ipynb

SMC lets faculty get around issues and inefficiencies with campus IT.
Permission with campus IT can be hard to get, help is difficult, service
can be poor, resources may be insufficient, and it is hard for IT
to know a priori what the needs will be, hence they will often allocate
capital badly, which leads to lack of resources.  Already, IT often
moves to centralize resources of a University and share them,
but they often focus on their own narrow use cases.
Students have heterogeneous slow computers.  SMC has
the potential to solve all of these problems, if only we are able
to solve some fundamental quality and efficiency problems (which
are very difficult).

The appeal to faculty is that grading homework carefully is very time consuming,
but automated grading systems are very patient
and available at all hours.    With SMC's collaboration, instructors
can easily see and interact with exactly what their students are doing.
Also, everything the students do while working on their homework
is recorded, which makes detection of cheating very easy, and also
provides much more detailed feedback on how students are doing in a course,
and also how good various automated problems actually are.

> HSY: not sure about the "tutoring market" aspect, but right here it could
> be mentioned, that all user activity can be monitored and logged -> used for
> assessing when and how long a tutor has been active

#### Presenting barriers to entry for competition

Our product is aimed at computational mathematics researchers, teachers, and students,
especially those that care about cost, efficiency, and value open source software.
To design it in the first place, and to continue to refine it indefinitely, requires
people with extensive experience doing computational mathematics research, and
teaching courses involving computational mathematics.
The PI, who is also CEO of the company, is the founder of the SageMath open source
mathematics software, which is the largest open source math software out there, and
has had over 500 contributors.  He has been passionately involved in the development
of mathematical software and computational mathematics research and education since
1998, and has had a substantial impact on the field.  For example, he was recognized
with the ACM Richard D. Jenks Prize in 2013.   Also, there have been 70 Sage Days
workshops.  Our competitors do not have this depth of experience and connection
with the community.

Just copying the implementation of SMC wouldn't give a competitor a unique advantage,
since the source code of SMC itself is completely open.    Instead, we have a head
start since we have been building a community around Sage for a decade, and around
SMC for several years now (100K registered users).  SMC is collaborative, so this
results in a big network effect, where SMC is much more valuable to you  because some
of your colleagues already use it.

The pricing model is another barrier to entry.  Offering a service with a
significant markup to pay for operating the service (and for profit) is a race
to the bottom.  Instead, SMC shortcuts that race and already starts with a
low price (a freemium model with \$7/month for some premium features, plus a standard
direct percentage markup on whatever Google happens to be charging for cloud computing
resources).   This doesn't leave much room for competitors  operating on top of
the same tools (Linux, LaTeX, SageMath, R, Python), unless they offer a
significantly better service on top, e.g., human support, extra value through
having far more users, more software pre-installed, etc.

Another barrier is that most competitors would really be providing a somewhat
different service.  The potential market is huge, and an online service on top
of a similar but different piece of software (e.g., Maple) would partly tap
into a different market.




## The Innovation (recommended length: 1-3 pages)

Summary: lots of technology that is open source, hence available to all.   Market data that is proprietary.  Enormous amounts of experience and a very large and effective developer community that cuts vertically through all levels of mathematics. (RAB - like this last phrase!)

Powerful open source mathematical software developed over 10 years with millions in NSF support.

Highly efficient distributed use of SageMath, etc.

Provide very useful service at a lower price point than Wolfram, Inc. due to open source.

Community, workshops and experience that let us pool large amounts of experience.

Cheap flexible sustainable cloud-based compute exists.

(RAB) Emphasize the 100% open source company (blog post) enabling reproducible research
   - this is a mammoth societal impact that we should highlight
   - it will play well with every scientist-reviewer

hsy: **massive collaboration**, polymath project?, terence tao talk: https://youtu.be/elWIDVI6b18 ... why mention? SMC gives mathematical and scientific researches a set of tools to collaborate throughout their entire pipeline for producing results.



Open source math software that rivals Mathematica, Maple, Matlab, and Magma.  Very powerful, user friendly, mainstream (using the most popular scripting language).

Very sophisticated and deep cloud-based collaboration environment for using the above software, which has been under nearly full-time development for about 3 years, with a massive amount of feedback from 100K users.   Minimal viable product that I needed for my teaching that I've iterated on as it took off with larger numbers of users.

Used by over 60 courses this semester.

Main problem is that we must make the system very, very efficient in order to provide a price point that makes this worthwhile for users.  This is much harder than with all existing course management and other related products (which merely involve simple problems that are checked on the browser, chat rooms, tracking grades, etc.), because SMC provides high performance compute.

Realtime sync at all levels of the system, which makes people much more efficient at collaborating on anything involving computational mathematics.   It also makes it dramatically easier for an expert to quickly help out a beginning with problems they hit.     Moreover, the evolution of computational documents (every keystroke!) is recorded, which supports reproducible research, and adds a new dimension.


## The Company and Team (recommended length: 1-3 pages)

SageMath, Inc. founded in February 2015 as a Delaware C Corporation.  Assistance and advice comes from Fenwick & West, specialists in advising technology companies and start-ups, such as Facebook, Google, Uber, Dropbox, WhatsApp, and Cisco.  William Stein is the owner and CEO of SageMath, Inc., and an initial investment comes from William Randolph Hearst, III.  William Stein has been working full-time on SageMathCloud and SageMath, Inc. while on a sabbatical leave from the University of Washington.  Business operations include a website, corporation bank accounts, and billing through Stripe.

The first product offering, an individual membership in SageMathCloud at \$7/month, was made available in mid-May 2015.  Courses with demanding computational needs (such as student exercises in  parallel computing) have contracted for dedicated resources.  Together these dozens of customers have generated \$1300 (?) in revenue during May 2015.

Through vast amounts of experience the team has an excellent understanding of the needs and requirements of their market: students, teachers and researchers in STEM disciplines.

Team Members:

- William Stein, CEO, Professor of Mathematics, University of Washington
  - Founder, Project Director, Sage open-source mathematical software (2003)
    - Managed millions of dollars in funding from NSF, Google, Department of Defense
    - Leads open source community of over five hundred contributors
    - Receipient of ACM/SIGSAM Richard D. Jenks Memorial Prize for excellence in software engineering applied to computer algebra (2013)
    - Very significant market penetration in pure mathematics research (e.g. cited in at least 410 articles, theses and books)
  - Researcher, Computational Number Theory
    - Author of forty-eight original research articles in mathematics
    - Author of three books
  - University Teaching
    - Twenty-one years experience teaching undergraduate and graduate courses
    - Supervised nine graduate theses and numerous undergraduate projects
- Harald Schilly, (Title), Universität Wien, Austria
  - Sage Development and Support
    - Numerous contributions to core Sage library in numerical mathematics and optimization (other areas?), since 2007
    - Maintains numerous critical aspects of Sage infrastructure, such as web sites and mirror sites
    - Design lead of the SageMath website and brand
    - Responsible for community management
    - Active in marketing Sage, such as use of social media
  - SageMathCloud Development and Support
    - Assists William Stein with technical design decisions and implementation
    - Provides online help for both members and free users
    - Responsible for marketing SageMathCloud
    - Monitors European operations
  - Owner, (business name)
    - (describe business: size, purpose, revenue?)
    - data analysis, design,  programming, statistics, ...
  - University Teaching
    - (years in words) years experience teaching programming and ICT (other types of courses, what is ICT?)
- Robert Beezer, Professor of Mathematics, University of Puget Sound
  - Sage Development and Support
    - Numerous contributions to core Sage library in linear algebra, graph theory and group theory, since 2009
    - Active member of the user and developer community, such as organizing four Sage Days workshops specializing in educational uses
  - Researcher, Algebraic Graph Theory
    - Author of fifteen original research articles
  - Open Source Textbook Author
    - Author of three online open textbooks that include extensive discussion of Sage
    - Project Founder, open source Mathbook XML authoring system for creating online open textbooks
  - University Teaching
    - Thirty-eight years experience designing instructional software
    - Thirty-seven years experience teaching undergraduate courses
    - Supervised thirty-one undergraduate projects
- Sage Community
  - The core Sage library is an open source project with over a decade's history of attracting top-flight researchers in pure mathematics and programmers with excellent technical skills.  The implementation of sophisticated algorithms in a highly reliable and easy-to-use package has attracted a large user community, who in turn provide testing, discussion, advice, and requests for enhancements.  The volunteer contributions of over five hundred mathematician-programmers and thousands of users are a key part of maintaining and improving a critical component of SageMathCloud.


(Pending XXXXXX)

- Dennis Stein: owns million-dollar company with 25 employees, etc...
- Jon Lee CS undergraduate...

> HSY: should there also be a mentioning about this OpenDreamKit project?
> I have no idea how this would look like, especially because their propsoal
> is so vague in that regard.
> Maybe keep it more general, that there are funded research projects by NSF and
> abroad in the EU as part of their Horizon 2020 strategy.


**IMPORTANT** we need to clarify that Harald won't be paid at all from this grant, since he's non-US.  Instead, he's part of the team, but the people we'll hire will be US people.


## Technical Discussion and R&D Plan (minimum length: 5 pages, recommended length: 5 to 7 pages)

### Introduction

We propose to implement, on top of the SMC platform, a next generation system for
web-based technical homework problems.   The main innovations of
existing homework systems involve
integrating with publishers (WebAssign), using statistical techniques to
provide a more relevant sequence of problems (e.g., ALEKS???), and checking
answers and providing hints entirely in the browser (e.g., Geogebra).  In contrast,
we propose to implement a system that supports sophisticated compute on the backend
and records everything the student does in detail, synchronized in such a way
that instructors can see and provide feedback in realtime.  Moreover, problems
will be shared among all users, and all data about how the problems have been
used (basically every keystroke by every single student) will be data mined to
provide a better experience.
We also plan to implement improved functionality for manually grading advanced
problems and for enabling peer grading of problems by students in a course (or
even at another university).
We will focus mainly on theoretical mathematics (e.g., LaTeX),
courses that involve programming in Python and R, and computational mathematics.

### Difficulties

The main components of our proposal involve designing and implementing a way
to create problems, a way to share problems, and a way to use problems in a course.
There are many daunting problems that arise in addressing these challenges.

The technical difficulty: computational documents online are hard,
because they are way more expensive than just syncing data
(textfiles). The synchronization is challenging and SMC can
demonstrates that it is solved. There is also an underlying challenge
in bridging the gap between programs running locally (command-line)
and providing a generally available web-based interface.
With regards to teaching, what's actually needed is the full
integration of all parts with the various extensions needed to make it
useful for teaching.


### Checking Answers

1.  Strings 1/3, 0.333, 0.33331 should all perhaps be correct answers for f(3) when f(x)=1/x.  Sage coercion/conversion solves some of this, the rest is tolerance/accuracy type questions.

2.  (d/dx) sin^2(x)  should recognize  2sin(x)cos(x)  and  sin(2x) as correct answers.  WW samples functions at a range of values and presumes multiple numerical agreement is function equality.  (Hmmm.) Perhaps .simplify_full() would do a superior job.

Anyway, this is a place where Sage is superior to WW's answer checkers (which are quite good, but limited in scope to "basic" algebra, functions and matrices).

What's also needed is a way to review the answers of the students
efficiently. The first question is, is just providing the final answer
of a calculus calculation enough? I think that's already done in many
variants and I generally dislike it.

What SMC could offer is a way to review small program code (few lines
of Sage). They are sent through automated tests, ... if tests fail,
the answer is evaluated to the instructor for manual review. The
instructor can annotate parts, and maybe even send it back to the
student to fix it. etc.

### Problem quality

You only have to admit in class that one or two problems are busted and then every evening you get a flood of 10 PM emails, "I *know* I have number X right, it must be a busted problem?"  Well, no.

I know William finds Sage development slow and cumbersome, but I really believe problems need to meet that same high standard of review and testing.  Especially to insure they are reliable two or three years later.  Nobody is doing this.

### Authoring

Nobody could author 30 problem sets of 10 calculus problems each, on-the-fly during a semester.  I'd say a good problem takes about an hour to write, test, debug, refine - minimum.  It is about the same effort as making a good interact.  So making the authoring language/procedure/tools as easy as possible is very important.  (Side thought - a way to make SMC two-way - offer SMC credits for authoring problems accepted by SMC employee.)

creating questions, testing the questions from the POV of the
students (submitting them, and testing if the tests work)

from my experience this semester (teaching python to mathematicans),
it's also necessary to give them a head start with their small
programming assignments [5 lines of python are given, they have to
write the remaining 5]

### Discovery

It is nice when WW problem X is designed to exactly match the flavor of problem Y in Stewart's Calculus.  But the chain rule is the chain rule, no matter what book you use.  So curation, cataloging, indexing, keywords, etc are super important (and not done well in WW).  A rigorous review and testing procedure could solve much of this.

Need a database of questions, parametrization, tagging, statistics, etc.  Some problems would be free and some would cost.

### Problem Management

Rosters, scores, partial credit for late assignments, extended deadlines for sich students, multiple or unlimited attempts, etc.  It is a real rats nest.  We all have our quirks when it comes to student work.  Not likely an innovation, but a place where a lot of effort is required to get it right.  Maybe something radical could be done here.

A way to manage and orchestrate the whole life of assignments. For each question in each assignment, the student can submit an answer (which is a piece of code) -> automated testing -> data collection -> manual reviewing -> handing back to student -> student doesn't understand -> asks tutor -> one-on-one online session with tutor explaining -> learning from mistakes -> understanding -> tracking of progress -> ...


### Computationally intensive problems

We want to support problems that may be very computationally for the students to solve,
e.g., problem sets in a course on scientific computing that involves students running
highly parallel computations.   Our approach will be to provide dedicated Google
pre-empt virtual machines to each student, which will exist only while the student
is working on the problem.  Alternatively, we could provide a dedicated instance for the
whole course.  Give some prices.  Give AMATH example...


### Realtime Synchronization

I would center this around the real-time synchronized worksheets. The
take-away message should be, that the teacher/tutor can review the
work of the student as they would be sitting side-by-side! Both see
the same document at exactly the same state in the same environment,
each keystroke is visible [there is no support for visualizing
highlighted text, but it could be], there is a chat where the
teacher/tutor outlines what is wrong, refers to the highlighted text
or region, etc. Also, what's currently missing, is a way to annotate
one or more lines (cells ?) with some notes from the instructor to
give pointed feedback.


