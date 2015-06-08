# Project Description

Title: "SBIR Phase I: Homework problems and course support for teaching advanced mathematics and computation"

## Introduction
We propose to design and implement an entirely new approach to
online course homework called
``SageMathCloud Problems'' (SMCP) that targets courses that
involve advanced mathematics and computation.   Despite the
enormous computational challenges, we believe that we can make
system cost effective by leveraging
open source software and cloud computing.  Moreover, by building
on recent work, SMCP would
provide realtime feedback, detailed analytics, much deeper
computational problems than existing systems, and
improved interaction between students and instructors.
In particular, we would leverage the NSF-funded SageMathCloud
platform and NSF-funded SageMath software.
If successful, our project would greatly increase the ability of students
to use open source tools for doing computational mathematics,
for writing up and sharing their results, and make any course
you want to teach on such tools much less work for you.

## Elevator Pitch

> The Value Proposition. What are the benefits to the customer of your proposed innovation? What is the key differentiator of your company or technology?
> The Innovation: Succinctly describe your innovation.  What aspects are original, unusual, novel, disruptive, or transformative compared to the current state of the art?

The main customers for SageMathCloud Homework (SMCP)
are students and teachers of
courses that involve any form of computational mathematics.
For example, SageMathCloud (SMC) is a 100% web-based system
that was used during Spring 2015 by over 60 courses
ranging from traditional Calculus courses to course in Global
Health, Numerical Analysis, Elliptic Curves and mathematical
Finance (see https://github.com/sagemathinc/smc/wiki/Teaching).
Though SMC does not have any automated homework functionality,
many of these courses would be greatly enhanced if they could use
the functionality we propose.

Researchers and their students need very easy and affordable
collaborative access to mathematical software, software development
environments, and tools for writing up and sharing their results.
SMCP will help make teaching these tools much easier, by providing
both access to them and making it possible for instructors to
craft problem sets that help students to learn these sophisticated
tools.

Instead of worrying about installing and updating software, learning
complicated revision control systems, and figuring out how to use cloud
computing or local resources, our target users want to focus on computing
and teaching their students how to compute.   Some of these users, especially
students and people in developing countries, are extremely price sensitive.
Our proposed innovation would leverage open source software, cheap cloud
computing resources, and systematic optimization based on user feedback
to make all of the above extremely easy, fluid, and affordable for our
customers.  Another huge pain point is also the general maintainence
of the underlying system.

SMC makes software easily accessible and provides some course management
functionality, but offers nothing for
managing the daunting complexity involved in curated homework problems
that involve sophisticated computation and mathematics.   Every single
such problem is potentially like an app or a game, and we propose to
provide a way to manage all aspects of this ecosystem.
The current state of the art systems all feel antiquated, and mainly
address freshman and sophomore level material, since that is a huge
market.  We instead propose to initially squarely target college senior (or higher) level material, and also train students to use sophisticated
software that is potentially very computationally demanding.

A key innovation of SMC is that it is built upon a vast pool of
open source software and leverages the combined knowledge and experience
of thousands of developers and millions of work hours.
By packaging all of this in a neatly integrated, easy-to-use and fully managed
web-based application we provide huge value.  We propose to take the same
approach to SMCP.

Our innovation is that SMC is an efficient
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

Not only can one write program code and edit LaTeX documents, there's also support for "interactive computational documents", including
IPython Notebook and
of course sage worksheets.
Such rich computational documents are much more appealing to novice users.
This mix of text/code/result is also better suited for publishing
and hopefully, the reviewers have already seen this.


## The Commercial Opportunity

### Broader societal need

A broader societal need right now that this project addresses is that
many people increasingly need to know how to use computers effectively
in their jobs for nontrivial tasks that involve mathematics.  There is
a growing need for every-day programmers, operating complicated
data-based systems, and implementing their domain-specific knowledge.
By dramatically reducing the friction to using the tools in education,
and providing new interactive problem-based tools for learning
computation, we will address this need.  Moreover, we will primarily
target free open source tools, so that our users get even greater
value out of what they learn.

Another social need is easy access to computational resources
needed to carry out projects that benefit society.  Companies already
provide easy free world-wide access to email (e.g., Gmail), short
public broadcasts (e.g., Twitter), and networking with friends (Facebook),
but no company provides extremely easy collaborative access to
sophisticated mathematical computation at Internet scale. Providing
this would potentially enable new innovation worldwide.  Our proposed
SMCP project would provide tools that would help people to learn to use
the broad computational resources that SMC makes available.

### Market and business economics

The market for sophisticated problem creation and course management,
is every student (either in school, college, or even online MOOCs)
who is taking a course that involves
mathematics or computation in general.   Students (esp. in high
school and the developing world) are extremely
cost sensitive, and budgets are tight. And teachers _care_
about finding solutions for their students that are
efficient and affordable.

Education is increasingly collaborative, and
there is a growing market to support this development
for computational aspects (data analysis,
mathematical computations, etc.)
For example
http://archive.sciencewatch.com/newsletter/2012/201207/multiauthor_papers/
points out the fact that the number of authors per paper is increasing.
more general, there is a growing number of research networks
(see, e.g., http://www.nature.com/nature/journal/v490/n7420/full/490335a.html)
Increased global collaboration leads to the need for
better tools to support this shift in education.

Teachers are overworked, focused on teaching,
and greatly value convenience for their IT infrastructure.
Even if they could spare the time and have the skills,
the cognitive shift, and lack of pooling of resources
makes them doing things themselves less efficient.

We have validated the demand for sophisticated
web-based open source mathematical
software by creating several iterations
of minimal viable versions of SMC, made available for free.
We wrote minimal useful course managment functionality,
which makes SMC just usable for teaching a course.
SMC was  used by over 65 courses during Spring 2015 and has
had over 100K users.
In May 2015, we transitioned to a freemium commercial model and have
had 30 paying customers (with about \$1500 in revenue so far).
We have also communicated a lot with users all over the world.
Our proposed homework system would dramatically expand
the potential ways to use the tools we offer with SMC
in education, so we think customers will have a strong interest.

The customers we will focus on for this project are University professors
teaching upper division courses and the students in courses.
The business model of SMC is that we charge a small percentage of users
a monthly fee to run their projects on better
members-only hardware.  We also provide dedicated resources
that instructors can use for all students in a course they
are teaching, or for research computations.  We pay Google (via
the Google Compute Engine cloud) for compute resources; in
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

The sophisticated automated homework system we plan to build
would mainly fall under the above business model, by providing
more functionality which makes the platform usable for a wider
range of courses.  Instructors will be
encouraged to make problems they develop freely available;
however, they will also
have the option to make problems available for a fee to
be used in other people's courses.  The fee would then be
rolled into the cost students (or their uni) pays for the
course.  This sort of ``app store'' marketplace could
motivate the creation of a large number of quality problems.

Advanced math courses are frequently just one section, so
instructors are free to choose whatever books, tools, etc.
they fancy.  Suppose they like SMC for the advanced problems
that nobody else can do.  Then they may advocate to their
colleagues to use SMC for their multi-section courses
(Calculus) since they know and like the tools.  A version
of trickle-down economics.


### The competition

There are a huge number of online problem systems that each target
a specific market segment, such as WebAssign, WebWork, and ALEKS.
SMCP will initially target primarily advanced computational
mathematics courses, which is a segment of the market that
hasn't received much attention, partly since the computational
requirements are so challenging, and the market it relatively small.

Thinking more longterm, one potential competitor to SMCP
may get built on Wolfram Research's product *Wolfram Cloud*, which
provides web-based access to Mathematica.  This product is
different than SMC since it is so focused on Mathematica.
Also, Mathematica itself isn't
free,  is closed source, and  has no
collaboration or course management functionality yet.  But
it would be very natural to develop on top of their platform.
Also, their longterm investment in their "Manipulate/Demonstrations"
functionality could very naturally translate to online
homework problems.

A  competitor to SMC (not SMCP) is https://wakari.io/, which provides
a way to use IPython
notebooks online.  But it's more limited in scope, with no
course management or document editing functionality.
However, it's only for pay plan is \$25/month, which is simply far too expensive for academics to consider for their students.  Wakari has no collaboration support, and nothing to specifically support teaching
or pure mathematics.  There are dozens of sites providing similar
functionality, e.g.,  https://www.pythonanywhere.com/,
https://sandstorm.io/.  There are also several coding environments
such as https://c9.io/, https://codenvy.com/, and https://koding.com/
which resemble SMC, but again are not oriented around mathematics
or teaching.

There are  dozens of automated homework systems such as the
entrenched commercial sites WebAssign and ALEKS and the dominant
open source system WebWork.
Their approach results in limited sophistication of homework problems,
which seems fine for many introductory courses.
Our proposed product would be more useful for more
advanced and computational courses than the these systems.

We expect each of the above products to incrementally improve, but
don't expect any major leaps in the next 8 months when our product
would enter the market.

There are several online LaTeX editing environments like
ShareLaTeX, WriteLaTeX, etc.  The SMC latex editor is
superior to, or priced-better/comparable environments.
A core difference between more polished online LaTeX
editing environments like ShareLaTeX, WriteLaTeX, etc.
is rooted in SMCs ability to be a computational environment.
The forementioned LaTeX editing environments have no direct
way to execute arbitrary code or interpret and transform data
of computational results into documents. SMCs general approach
offers several ways to embed computations and datasets
into documents.  Also, these environments are not designed
to be used  in teaching a course.


### Key risks in bringing the proposed innovation to market

A risk is that the only users of our SMCP problem service
will be people who can't afford to pay anything.  We can
mitigate this by making our product add sufficient
value.  Another risk is that because our software is open source,
users who like it enough to pay will instead simply take it and run it themselves on the cloud or their own servers.  The best way
to mitigate this is to make
SMCP maximally benefits from network effects, so that an SMC server
with a large number of users is much, much more valuable to those users
than a server with only a few users.  In particular, the database
of problems is critical, as is superb
collaboration, communication, and crowdsourcing functionality.
Moreover, we need to make it so that SMCP efficiently shares resources
between users, so there is much more value in 10 users paying us for
a single machine, than 10 users paying Google directly for 10 separate
machines -- to make this the case, we have to make SMCP extremely efficient,
good at sharing resources, and leverage how we know people use
the services interactively (often staring at a question, then
running code for a few seconds, then staring, etc.).

There are dozens of attempts (and much research into ways) to create
innovative interactive homework systems, ways to describe problems to
these systems, strategies for presenting these problems, and techniques
for collating, sharing and making available these problems to others.
Looking at the results so far suggests this is a very hard problem;
building on a more powerful and flexible platform (SMC) combined
with our experience, user feedback and new powerful open source software
for mathematics might not be enough to produce something that really
works much better than existing solutions in practice.


### Commercialization Approach

We create open source software, which runs in the cloud on Google Compute Engine. Most users
will try or use SMC online for free, but some small percentage will
pay.  For this to work, it's critical that the software be extremely
efficient, since many of our target customers are price sensitive students,
who are already being overcharged for textbooks and tuition.
The primary products we plan to sell are memberships (with a monthly fee) and
dedicated virtual machines that groups of users will share.
Dedicated machines would be rented by teachers (or their students) wanting
better resources for running their classes.
For the dedicated virtual machines we will mark up the price by a fixed
percentage  from what we pay to Google, so there
is no difficulty in estimating how much product that we should buy,
and every sale results in profit.

The revenue potential is large, since the potential
market is large... but whether we will create a product good
enough to appeal to even 1% percent of that market is very unclear.
Also, we are initially targeting advanced computational
mathematics, which is a relatively small market.

The only resources we need to implement our plan are people to write software
and people to talk with and help prospective users.  This SBIR
should provide enough
financial support to implement a first usable version of the proposed
automated problem platform, and get some testing by courses.
We need to secure regarding resources is
money to hire the PI, an experienced teacher, and some young
programmers with classroom experience (e.g., undergraduate
and graduate students).  As an academic and founder of the SageMath
software project, the PI has the necessary connections.
Our hope is that using revenue the company already has,
we will have people in place for the project at a small percent of
time, so if we get funding from SBIR, we can then pay these people
to work a much larger percent of time, with far more ambitious
goals.

Timeline: hire people, write software (with regular
coding sprints), deploy software, get feedback.


#### Product-market fit

The proposed SMCP problem system, which we plan to implement, doesn't
exist, so it is difficult to address product market fit.  As evidence
for at least fit of SMC, on a typical day during Fall 2015, SMC
was used by 2-3K people.
There are numerous existing (similar) services to SMC, which provide proof that
there is demand: collaborative editing of documents (Google docs), course
management for education (Moodle),
WebAssign and WebWork for automated homework grading.
There are also online LaTeX editors such as https://www.sharelatex.com/
and https://www.overleaf.com/.
SMC uniquely integrates the whole system, implementing most things completely
from scratch, and manages its complexity.

SMC, and hence SMCP, would let
faculty get around issues and inefficiencies with campus IT.
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

A strong appeal to teachers is that grading homework carefully is very time consuming,
but automated grading systems are patient
and available at all hours.    With SMC's collaboration capabilities, instructors
can easily see and interact with exactly what their students are doing.
Also, everything the students do while working on their homework
is recorded, which makes detection of cheating easier, and also
provides more detailed feedback on how students are doing in a course,
and also how good various automated problems actually are.
Also, since all user activity can be monitored and logged, this can be
used for assessing when and how long a tutor has been active in helping
a student (e.g., an instructor could set parameters for how much other people,
including paid tutors, can help a student on their homework problems).


#### Presenting barriers to entry for competition

SMCP is aimed at computational mathematics teachers, and students,
especially those that care about cost, efficiency, and value open source software.
To design it in the first place, and to continue to refine it indefinitely,
benefits from people with extensive experience
teaching courses involving computational mathematics.
The PI, who is also CEO of the company, is the founder of the SageMath open source
mathematics software project, which is the largest open source math
software out there, and
has had over 500 contributors (he founded the project in 2005).
He has been passionately involved in the development
of mathematical software and computational mathematics
research and education since
1998, and has had a substantial impact on the field.
For example, he was recognized
with the ACM Richard D. Jenks Prize in 2013.   Also, there have been 70 Sage Days
workshops.  Most of our competitors do not have this depth of
experience and connection
with the community.

Just copying the implementation of SMC wouldn't give
a competitor a unique advantage,
since the source code of SMC itself is completely open.
Instead, we have a head
start since we have been building a community around Sage for a decade, and around
SMC for several years now (100K registered users).
SMC is collaborative, so this
results in a big network effect, where SMC is much
more valuable to you  because some
of your colleagues already use it.   This community is a base
of potential users of SMCP.

The pricing model is another barrier to entry.  Offering a service with a
significant markup to pay for operating the service (and for profit) is a race
to the bottom.  Instead, SMC shortcuts that race and already starts with a
low price (a freemium model with \$7/month for some premium features, plus a standard
direct percentage markup on whatever Google happens to be charging for cloud computing
resources).   This doesn't leave much room for competitors  operating on top of
the same tools (Linux, LaTeX, SageMath, R, Python), unless they offer a
significantly better service on top, e.g., human support, extra value through
having far more users, more software pre-installed, etc. The pricing for SMCP
would be identical -- we're just adding it as another application that can be
run on top of the SMC platform.

Another barrier is that most competitors would  be providing a somewhat
different service.  The potential market is huge, and an online service on top
of a similar but different piece of software (e.g., Maple) would partly tap
into a different market.



## The Innovation

Our proposed online problem system mainly
builds on the Sage mathematical software and
the SageMathCloud platform.

SMC builds on SageMath, which is
powerful open source mathematical software developed since
2005 with millions in NSF support.
SageMath is open source math software that rivals Mathematica, Maple, Matlab,
and Magma.  It is very powerful, user friendly, and mainstream using the most
popular scripting language (Python).

SMC is a sophisticated cloud-based collaboration environment for using
SageMath, R and other software, which has been under  development
for about 3 years, with a massive amount of feedback from 100K users.
It started as a minimal viable product that the PI needed for
teaching, which he's iterated on as it took off with larger
numbers of users.

SMC is the key NSF-funded innovation that is needed for our proposed automated
problem system. SMC involes much technology that is open source, hence
available to all, but we also have much proprietary market data due to running
the software for years.  We have experience and a
large and effective developer community that cuts vertically
through all levels of mathematics.
SMC provides a useful service for computational at
a lower price point than competitors, due to being
open source.   We have also run nearly 70 Sage Days workshops
(see http://wiki.sagemath.org/Workshops).
Another key innovation is that many companies rare competing to offer
cheap and flexible cloud-based compute, which we can leverage.

SMC offers realtime sync at all levels of the system, which
makes people much more efficient at collaborating on anything
involving computational mathematics.   It also makes it
dramatically easier for an expert to quickly help out a
beginning with problems they hit.     Moreover, the evolution
of computational documents (every keystroke!) is recorded,
which supports reproducible research, and adds a new dimension.
It's this key functionality, which we have been refining over
several years, on which we will build the SMCP problem platform.


## The Company and Team

SageMath, Inc. was founded in February 2015 as a Delaware C Corporation,
and is owned by the PI.
Assistance and advice comes from Fenwick & West, specialists in advising
technology companies and start-ups, such as Facebook, Google, Uber,
Dropbox, WhatsApp, and Cisco.  William Stein is the owner and CEO
of SageMath, Inc., and a modest initial angel investment was provided
by William Randolph Hearst, III (a strong supporter of mathematics).
William Stein has been working full-time
on SageMathCloud and SageMath, Inc. while on a sabbatical
leave from the University of Washington.  Business operations
include a website, bank accounts, and billing through Stripe.

The first product offering, an individual membership in
SageMathCloud at \$7/month, was made available in mid-May 2015.
Courses with demanding computational needs (such as student
exercises in  parallel computing) have contracted for
dedicated resources.  Together these dozens of customers
have generated \$1300 (?) in revenue during May 2015.

Through vast amounts of experience the team has an excellent
understanding of the needs and requirements of their market:
students, teachers and researchers in STEM disciplines.

The contributors to SMC are vertically integrated with an excellent
balance of contributors from high school, college, graduate
schoool, teaching, research, and business.
The team consists of William Stein (Professor at Univ of Washington),
Harald Schilly (applied mathematics graduate student
in Vienna, Austria), Rob Beezer (professor at Univ of Puget Sound),
and Jon Lee (Undergraduate at Univ of Washington).
The team also  consult about business matters with Dennis Stein (San Diego businessman),
Tim Abbot (co-founder of two successful tech startups), and Will Hearst
(experienced venture capitalist, investor and philanthropist),
and regularly discusses approaches to online homework with high
school student Sequoia Lefthand.

The PI William Stein is CEO of SageMath Inc, and founded the SageMath open
source mathematical software project in 2005.  He has managed millions
of dollars in funding from NSF, Google, Microsoft, and DOD.
He is the 2013 recipient of the ACM/SIGSAM Richard D. Jenks Memorial Prize
for excellence in software engineering applied to computer algebra.
He has significant market penetration in pure mathematics research:
cited in at least 410 articles, theses and books,
author of over forty original research articles in mathematics,
and author of three published books.
He has twenty years experience teaching undergraduate and graduate courses,
has supervised four completed Ph.D. theses and dozens of undergraduate
projects.

Harald Schilly is a Ph.D. student at Universität Wien in Vienna, Austria.
(Note: Schilly would not be paid by any money coming from this grant.)
Since 2007, he has made numerous contributions to the core SageMath
library in numerical mathematics and optimization.
He maintains numerous critical aspects of Sage infrastructure,
such as web sites and mirror sites.
He is the design lead of the SageMath website and brand and is
Responsible for community management and  marketing Sage (social
media, designing fliers, etc.)
He has been heavily involved with SageMathCloud development,
and assists William Stein with technical design decisions and
implementation.  He provides online help for  users,
and is responsible for marketing SageMathCloud.
He owns a consulting business in Austria that helps manage technical
aspects of teaching courses at the university, doing
data analysis, design,  programming, and statistics.
He has several years experience teaching programming courses.

Robert Beezer has made numerous contributions to the core Sage
library in linear algebra, graph theory and group theory, since 2009.
He is an active member of the user and developer community,
and has organized four Sage Days workshops specializing in
educational uses of Sage.  He mathematical research involves
Algebraic Graph Theory, and he has published
fifteen original research articles.
He has also written three online open source textbooks, which
include extensive discussion of Sage.
He is the project founder of the
open source Mathbook XML authoring system
for creating online open textbooks.
He has taught courses and designed instructional software
at University of Puget sound for over 37 years,
and supervised 31 undergraduate research projects.

Jon Lee is a Junior undergraduate computer science major at
Univeristy of Washington. He got involved with SageMathCloud
development when SMC was used for a course he took on scientific
computing.  In 2014 he spent the summer fulltime doing SMC development,
and is being funded by Google to work fulltime on SMC during Summer 2015.

In addition, the SageMath software is an open source project with over a
decade's history of attracting top-flight researchers in pure mathematics
and programmers with excellent technical skills.  The implementation of
sophisticated algorithms in Sage results in a highly reliable and
easy-to-use package that has attracted a large user community, who
in turn provide testing, discussion, advice, and requests for
enhancements.  The volunteer contributions of over five hundred
mathematician-programmers and thousands of users are a key part
of maintaining and improving a critical component of SageMathCloud.


## Technical Discussion and R&D Plan

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




