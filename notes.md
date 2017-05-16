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

-   Lessons don't maintain themselves.
-   This should be made clear to contributors, with sustainability in mind.
-   So focus (as with all online activities) has to be on creating a community.

## 3) Reduce, re-use, recycle.

Don't create a new lesson if there is an existing one that you can use or contribute to. Just as a scholar would not write a paper without a literature review, the same holds for lessons. Before writing that introduction to the Bash command line, for example, do a search: has anybody else written it? Is it complementary to your goals? Could it be tweaked or modified to meet your own goals? Could your planned lesson be tweaked to compliment the existing lessons so that topics aren't duplicated? 

But before re-using content, make sure to check that the lesson is licensed in an open manner? Both Programming Historian and Software Carpentry, for example, license their material under the [CC-BY license](https://creativecommons.org/licenses/by/2.0/). This allows people to share and adapt material for any purpose, even commercial ones, without asking permissions as long as they continue to share the content in a similar manner. Software Carpentry is explicit that one does not need to ask permission. But otherwise, please ask.

The same questions of re-use come when thinking about recycling content of a lesson: images, data, figure, or code. Does the license cover that as well? If not, then ask permission. 

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

## 5) Encourage and enable lots of little contributions.

It takes a village to ensure the steady improvement and adaptation that will give a lesson a long life. Ensuring this, however, is not straightforward.

Making the process explicit is key. New contributors require a straightforward and transparent introduction to understand the process of tweaking and adapting lessons. Licensing, code of conduct, governance, and contribution procedure need to all be explicit rather than implicit to lower the social barriers to contribution.

Tools can help, especially if they support pre-merge review. Yet some of these tools come with a considerable up-front learning curve. GitHub with pull requests may be ideal, but allowing people to edit a Google Doc, or to facilitate Wiki-based editing, can help get conversations started. In a pinch, work with contributors to find a comfort zone –-- don't let a collaboration flounder on technological choice. But make sure not to overwhelm either; threaded discussion (or GitHub issues) will help increase the signal-to-noise ratio.

Ultimately, community dynamics are more important than platform. We have seen the 90/9/1 rule (90% of people watch, 9% discuss, 1% do). This requires a gentle on-ramp for new contributors, that we make it easy for people to submit errata and suggestions, and that editors may need to do triage to ensure that voices are heard. Finally, with so many voices and contributions come caution. Working in the open can be great, but can also unintentionally suppress voices. At _Programming Historian_, a popular digital humanities technical site, an ombudsperson is available for private chats and facilitation. Many voices are great, as long as they can all be considered.

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

-   Give people credit in a digestible way as a reward for contributing.
-   List the lesson's maintainers as editors (since everyone understands that role).
-   Tell people what the release schedule is.
-   Give all contributors credit when you publish (having been clear up front who counts as a contributor).
-   Be open to candid conversations around credit --- not all employment contexts are the same. 

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
