# Ten Simple Rules for Collaborative Lesson Development

Thousands of university lecturers teach first year biology,
third year computational mathematics,
second year Indian film,
etc.
Some might use a common textbook written by a single author or two,
but other than that they usually develop and improve their course materials in isolation.
It is staggering to think how many wheels are being re-invented,
how the progress of teaching in these fields has been held back by
the lack of community collaboration and sharing,
and how much valuable time has been wasted.

This problem extends beyond university teaching,
but it is curious that it is endemic in tertiary education,
given that research depends so critically on collaboration and sharing,
and that most researchers complain about how much time teaching takes away from research.

The software community's model of collaborative code development is an alternative.
The authors first encountered it in the context of lessons on basic lab skills for research computing
in the sciences and humanities...

## Preamble

1.  Subject of this paper is writing and maintaining lessons, not delivering them, but:
    -   People are more willing and able to teach together if they build the lessons together.
    -   Lessons need to be designed with particular delivery methods in mind,
        so sharing practices (the "how") facilitates sharing and co-constructing material (the "what").
    -   We will mention specific teaching practices when relevant to co-authoring,
        but defer more detailed discussion to another paper.
2.  Who's collaborating?
    -   Lessons are under continuous development and repeated use (as opposed to created/taught once).
    -   Many contributors dispersed in space and time.
        -   I.e., not physically together, and maintaining lesson over months or years.
    -   Diverse contributors: people in different contexts, interdisciplinary, learners adding material, etc.
3.  Collaborative and open are separate things.
    -   Lots of openly-licensed resources that aren't set up for collaborative development.
    -   Lots of collaborative development happening on closed-source materials.
    -   In practice, there tends to be correlation.
4.  Mike Caulfield's notion of [choral explanations](https://hapgood.us/2016/05/13/choral-explanations/):
    -   Stack Overflow, Quota, etc. are successful because they provide multiple explanations.
        -   Different levels and/or different approaches are best for different audiences.
    -   Collaboration lends itself well to building a chorus rather than a linear lesson.
    -   But beware of maintenance (in particular, maintaining consistency).
5.  Building is easy - maintaining is hard.
    -   As with software, the first version is only a small fraction of lifetime investment.
    -   Without pruning and updating, lessons go stale.
6.  Who are lessons for?
    -   Instructors who will be teaching workshops from the materials
    -   Students from said workshops who will reference the materials afterwards
    -   People who weren't in the lesson but who use the materials to learn on their own
    -   Balancing the needs of these audiences represent different choices in
        what information is available (level of detail)
        and where it can be found (main lesson pages vs other links),
        as well as the overall design/layout of the lesson.
    -   Software Carpentry lessons are designed largely for in-class delivery (cases 1 and 2),
        but are used for independent study (case 3).
    -   Programming Historian lessons are designed for on-line consumption, and are developed
        in an academic context (both users but also authors who have expectation of formal 
        academic credit).

## 1) Be clear who your lesson is for.

-   Describe prerequisite knowledge, equipment or software required, etc.
-   Learner profiles are often clearer than itemized lists.
    -   Thinking systematically about 'difficulty' levels can help manage expectations
    –   at Programming Historian we use "beginner," "intermediate," and "advanced" lessons,
        which helps authors pitch properly.

## 2) Remember that you are building a community, not a lesson.

Lessons don't maintain themelves. 
Unlike traditional academic work, 
which may have shelf time measured 
in years (if not longer), 
technical lessons do not maintain themselves. 
Versions change, dependencies break, 
and what was cutting edge in 2017 may be dated 
and less useful in 2018. 
This needs to be clear to contributors, 
so they understand that this lesson is just 
the starting point. 
Sustainability needs to be front of mind.

The focus accordingly needs to be on creating a community. 
Authors cannot be expected to maintain continual vigilence on a lesson,
but this is necessary if one expectes continual use of a lesson! 
By working online, creating opportunities for collaboration 
and contribution, many eyes can keep the lesson usable. 
As we note below, 
this only works if you make space for 
little contributions just as you do for larger ones.

## 3) Reduce, re-use, recycle.

Don't create a new lesson if there is an existing one that you can use or contribute to.
Just as a scholar would not write a paper without a literature review,
the same holds for lessons.
Before writing that introduction to the Bash command line,
for example,
do a search:
has anybody else written it?
Is it complementary to your goals?
Could it be tweaked or modified to meet your own goals?
Could your planned lesson be tweaked to compliment the existing lessons so that topics aren't duplicated? 

FIXME: This is a good place to talk about discoverability as well as licensing

Before re-using content,
make sure to check that the lesson is licensed in an open manner.
Both Programming Historian and Software Carpentry license their material under
the [CC-BY license](https://creativecommons.org/licenses/by/2.0/).
This allows people to share and adapt material for any purpose,
even commercial ones,
without asking permissions as long as they continue to share the content in a similar manner.

The same questions of re-use come when thinking about recycling content of a lesson,
such as images, data, figure, or code.
Does the license cover that as well?
If not,
then ask permission,
just as you would for any other material.

As you collaboratively develop your own lessons, make sure to think about the collaborative contexts of the entire field.

## 4) Build lessons, not courses.

Every instructor's needs are different,
so build small chunks that can be re-purposed in many ways. 
A university lecturer in meteorology, for instance,
might construct a course by bringing together lessons on differential equations,
fluid mechanics and absorption spectroscopy. 
This task is greatly simplified if existing courses on mathematics, 
physics and chemistry consist of numerous small, discrete lessons,
as opposed to a few large, monolithic lessons.

Note that doing this shifts the instructor's burden from writing to finding and synthesizing.
Both of which are easier if lessons have been designed by people with a shared world-view (rule 6),
and if lessons clearly signal what they cover (rule 1).
In particular,
if lessons reference specific points in the model curriculum guidelines promulgated by many professional societies,
it can be much easier for people to find them and integrate them.

Note also that individual lesson topics hinge on the learners having the proper prerequisite background,
so this rule further emphasizes the importance of rule 1.

## 5) Encourage and enable lots of little contributions.

It takes a village to ensure the steady improvement and adaptation that will give a lesson a long life. Ensuring this, however, is not straightforward.

Making the process explicit is key.
New contributors require a straightforward and transparent introduction
to understand the process of tweaking and adapting lessons.
Licensing, code of conduct, governance, and contribution procedure all need to be explicit rather than implicit
to lower the social barriers to contribution.

Tools can help,
especially if they support pre-merge review.
Yet some of these tools come with a considerable up-front learning curve.
GitHub with pull requests may be ideal,
but allowing people to edit a Google Doc,
or to facilitate Wiki-based editing,
can help get conversations started.
In a pinch,
work with contributors to find a comfort zone:
don't let a collaboration flounder on technological choice.
But make sure not to overwhelm either:
threaded discussion (or GitHub issues) will help increase the signal-to-noise ratio.

Ultimately,
community dynamics are more important than platform.
We have seen the 90/9/1 rule (90% of people watch, 9% discuss, 1% do).
This requires a gentle on-ramp for new contributors,
that we make it easy for people to submit errata and suggestions,
and that editors may need to do triage to ensure that voices are heard.
Finally, with so many voices and contributions come caution.
Working in the open can be great,
but can also unintentionally suppress voices.
At Programming Historian,
for example,
an ombudsperson is available for private chats and facilitation.

## 6) Teach people how to do things the right way (or at least *some* way).

-   Large part of Software Carpentry's success was instructor training, which taught:
    -   how to build lessons (so that everyone's using more or less the same process)
    -   how to deliver lessons (so that everyone knows what they're trying to build *for*)
-   A natural complement to Software Carpentry's core mission
    -   Scientists shouldn't have to teach themselves the basics of programming
    -   So why should they have to teach themselves how to teach?
-   Example: design the lesson backward, but describe it forward.
    -   Quick review of reverse instructional design.
    -   But describe forward (since that's comprehension order).

## 7) Publish each lesson periodically, and give people credit when you do.

### Writing

Similar to publishing software,
lessons should have releases of fixed content
so that learners or instructors who may wish to use the material have a stable version to refer to
for the duration of their use.
These releases should be periodic
so that improvements and adjustments are made available
for new learners and instructors just starting their use.
Periodic releases are also essential
for enabling recognition of the contribution of authors and maintainers.

The traditional academic system has limited ways of recognizing contributions.
Until systems have been expanded to improve this,
it is important to publish your lessons using a mechanism that provides recognition to the contributors.
Currently an effective way to do this is
to publish lessons with a DOI supplied by (FIXME list possibilities).
Contributors can be listed as authors
and the maintainers of the lesson as editors
to provide differentiated recognition of their contributions.

A lesson release is a good opportunity to bring the material into a stable shape
by fixing outstanding issues and merging contribution.
The complete name and possible identifier like ORCID should also be gathered for every contributor.
Version control helps a lot in continuously maintaining a list of contributors
but also in remembering which version is used for release
(e.g., using branches or tags).
A lesson release is here to stay
and it is recommended to use a consistent naming scheme from the beginning.
A convenient naming scheme is to use the full year and month of the release,
like "2017.05",
as it conveys a clear notion of date,
even to people that are new to the project.

Once the lesson is ready for release and has a name,
it should be built
and submitted to DOI supplier with its metadata,
such as lesson name, authors (e.g., contributors) and editors (e.g., maintainers).
Due to the collaborative aspect of the lesson development,
the number of authors and even lessons can grow very fast
and it is worth spending some time on automating this release process.
After the formal publishing,
it is also a good idea to publish the built lesson for direct access by the community,
making it clear which version is displayed and what is its corresponding DOI. 

### Ideas etc

-   Give people credit in a digestible way as a reward for contributing.
-   List the lesson's maintainers as editors (since everyone understands that role).
-   Tell people what the release schedule is.
-   Give all contributors credit when you publish (having been clear up front who counts as a contributor).
-   Be open to candid conversations around credit --- not all employment contexts are the same. 
-   Managing a community with an evolving material, so we need to
    -   … have versions that can be referenced (i.e., are both always accessible and named), so that
    -   instructor: have a known and known-working version to teach (at least as a fallback)
    -   instructor: choose deliberately to self-update
    -   learner: can refer to the version they were taught
    -   contributor: discuss changes between versions
-   Important steps (we might be publishing a set of lessons)
    -   have an up to date author list (ideally maintain it from and inside version control)
    -   bug bbq, merging, etc of the pending issues
    -   keep track of which version your release (write it in a file but also make a "tag" on your lessons)
    -   decide on a good release name (e.g., 2017.05 that conveys a rather clear notion of date)
    -   build your rendered lesson
    -   get a DOI so it can be cited
    -   publish it (including its version number and doi)
    -   also publish your infra? (workshop template etc)
 
## 8) Collect and act on feedback at several scales.

The purpose of feedback is to guide lesson development so that authors aren't designing and arguing in a vacuum.
What people immersed in the lessons think needs fixing can often differ from what learners think needs fixing.

Micro-scale feedback can be gathered by an instructor while teaching a particular lesson.
Learners might provide feedback on things like typographical errors,
clarity/ease of quiz questions and/or the order in which topics are presented,
which the instructor can enter into a work-tracking system (e.g. GitHub issues) at the end of class.
As well as encouraging direct verbal feedback,
it's a good idea to provide learners with a means to provide feedback anonymously during class 
(e.g. on small pieces of paper like sticky notes).

Pre- and post-class surveys can be used to discover larger macro-scale issues.
These issues often relate to the fact that it can be difficult for lesson developers
to fully understand the frame of reference of their audience.
For instance, a lesson might inadvertently assume prior knowledge that many learners don't have,
which is information that can be collected easily in a survey.
If possible, it's a good idea to conduct the post-class survey 30-60 days after the fact.
This allows people time to reflect,
meaning they are more likely to give accurate feedback on what they learned
rather than how entertained they were.

Pre- and post- class surveys also are essential in focusing in on the audience for a given lesson.
It can sometimes be difficult for lesson developers to understand the frame of a given learner
so surveys (particularly post-class surveys) can reveal hidden assumed knowledge
that can be expanded on or acknowledged.

## 9) Tell people where else to look.

-   The lesson is a beginning, not an end, so point them at similar material and where to go next.
-   Make it part of a much broader conversation.

## 10) Remember: you can't help (or please) everyone.

-   Discuss minor disagreements, split off and begin evolving the lesson in different ways if they cannot be resolved.
    -   If there are several complementary ways to explain something,
        or several points of views that can cohabit respectfully,
        present them side by side
        (just as with any other kind of lesson, essay, etc.).
        -   Cf. choral explanations.
    -   If there are major disagreements that can't cohabit respectfully,
        fork the lesson,
        i.e., have the groups go their separate ways.
-   Same applies to governance:
    if enough people disagree strongly about how the lesson should be managed, fork.
    -   Which is a strong argument in favor of open licensing.
    -   But remember at the end of the day we all share the same vision of collaborative lesson development.

## Mechanics

### Software/Data Carpentry

FIXME: need a description/summary.

### Programming Historian

The Programming Historian model is closer to traditional academic publication,
while Software Carpentry's is closer to open source software development.
In the PH model:

1.  Authors propose a lesson.
2.  Authors are assigned an editor who works with them.
3.  A submission ticket is opened in a GitHub repo,
    where two invited peer reviewers can give feedback
    as well as community members commenting.
4.  The lesson is posted.

PH is still trying to figure  out ongoing maintenance,
as the author-ownership model doesn't lend itself well to mass community edits.

### Live Coding

**This is included as an example of how in-class teaching practice shapes lesson development.**

Software Carpentry teaching relies on *live coding*.
Instead of presenting slides to learners,
instructors write code as they go along,
using whatever tools they would use in real life.
Live coding has several advantages over slides,
the most important of which for this paper is that
it enables instructors to be more responsive to "what if?" questions.
Where a slide deck is like a railway track,
live coding allows instructors to go off road
and follow their learners' interests.

Live coding doesn't make slides irrelevant.
Instead, they serve two purposes:

1.  Instructors read them *before* the lesson
    to be sure they have a clear picture of the lesson's flow.

1.  Learners read them *after* the lesson for review and reference.
    They can also be given a printed copy of the slides to mark up during the lesson
    so that they don't have to take notes from scratch.

The first point is essential for supporting collaboration among instructors.
In order for two or more people to teach together effectively,
they must have a shared road map of what they are going to do.
They may improvise on top of that like jazz musicians improvise on top of a score,
but a quick review of a shared slide deck before a class
can prevent a lot of crossed wires, dropped balls, and other metaphors.

These slides also help instructors share new and improved ideas with their peers.
If one person comes up with a clever way to explain a complex idea,
she can (and should) submit a pull request to add her discovery to the slides.
Other people who are teaching this material can watch for incoming changes,
or look at the differences between the slides as they were the last time they taught
and the slides as they are today
and see what we have collectively learned about how best to teach this topic.
