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

## Thoughts

-   Subject of this paper is writing and maintaining lessons, not delivering them.
    -   So teaching practices will only be discussed when/as they affect lesson development.
-   Who's collaborating?
    -   Lessons are under continuous development and repeated use (as opposed to created/taught once).
    -   Many contributors dispersed in space and time.
        -   I.e., not physically together, and maintaining lesson over months or years.
    -   Diverse contributors: people in different contexts, interdisciplinary, learners adding material, etc.
-   Collaborative and open are separate things.
    -   Lots of openly-licensed resources that aren't set up for collaborative development.
    -   Lots of collaborative development happening on closed-source materials.
    -   In practice, there tends to be correlation.
-   Mike Caulfield's notion of [choral explanations](https://hapgood.us/2016/05/13/choral-explanations/):
    -   Stack Overflow, Quota, etc. are successful because they provide multiple explanations.
        -   Different levels and/or different approaches are best for different audiences.
    -   Collaboration lends itself well to building a chorus rather than a linear lesson.
    -   But beware of maintenance (in particular, maintaining consistency).
-   Building is easy - maintaining is hard.
    -   As with software, the first version is only a small fraction of lifetime investment.
    -   Without pruning and updating, lessons go stale.
-   Who are lessons for?
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

## Potential Rules

1.  Reduce, re-use, recycle.
    -   Don't create a new lesson if there's one out there you can use and/or contribute to.
    -   Just as you wouldn't write a paper without a literature review, the same holds for lessons!
    -   Check the license/ask permission before re-using.
        -   This applies to images, data, figures, code, etc., just as it does with any other kind of work.
1.  Remember that you are building a community, not a lesson.
    -   Lessons don't maintain themselves.
    -   This should be made clear to contributors, with sustainability in mind.
    -   So focus (as with all online activities) has to be on creating a community.
1.  Build lessons, not courses.
    -   Every instructor's needs are different, so build small chunks that can be repurposed in many ways.
    -   Analogy: libraries of re-usable functions are more useful than monolithic applications.
1.  Teach people how to do things the right way (or at least *some* way).
    -   Large part of Software Carpentry's success was instructor training, which taught:
        -   how to build lessons (so that everyone's using more or less the same process)
        -   how to deliver lessons (so that everyone knows what they're trying to build *for*)
    -   A natural complement to Software Carpentry's core mission
        -   Scientists shouldn't have to teach themselves the basics of programming
        -   So why should they have to teach themselves how to teach?
    -   Example: design the lesson backward, but describe it forward.
        -   Quick review of reverse instructional design.
        -   But describe forward (since that's comprehension order).
1.  Be clear who your lesson is for.
    -   Describe prerequisite knowledge, equipment or software required, etc.
    -   Learner profiles are often clearer than itemized lists.
1.  Encourage and enable lots of little contributions.
    -   Steady improvement and adaptation increases longevity of lesson.
    -   Provide an on-ramp for new contributors.
    -   Be explicit about the license, code of conduct, governance (esp. who can do what), and contribution procedure.
        -   Lower the social barriers to contribution.
        -   Copy existing ones rather than creating your own.
        -   Pointers to models.
    -   Use tools and formats that support pre-merge review.
        -   Lower the technical barriers to contribution.
        -   Google Docs with comments is OK.
        -   GitHub with pull requests is better, but has a very large startup cost.
        -   Wikis that allow review for pending changes are a good balance.
        -   But in a pinch, work with contributors to find their comfort zone --- don't let a collaboration
            flounder on a technological choice!
        -   Support threaded discussion.
            -   Because a single channel will have a low signal-to-noise ratio from most people's points of view.
            -   Discuss use of GitHub issues as sub-channels.
    -   Make it easy for people to submit errata and suggestions.
        -   An even gentler on-ramp for new contributors.
        -   The 90/9/1 rule (90% of people watch, 9% discuss, 1% do).
        -   Requires someone to do triage (see earlier point about governance).
    -   Have a procedure for when things go wrong.
        -   Working in the open can be great, but can also suppress voices (unintentionally)
        -   At *Programming Historian*, we have an ombudsperson that a contributor can contact outside
            of public channels.
1.  Collect and act on feedback at several scales.
    -   Micro: notes on specific parts of existing lessons (e.g., typos or minor reorderings)
        turn into tickets in a work-tracking system (e.g., GitHub issues).
    -   Macro: use pre and post surveys to discover larger issues.
        -   Do pre surveys immediately before so that information is still accurate when lesson delivered.
        -   Do post surveys 30-60 days after (if possible) so that people have time to reflect,
            and are more likely to give accurate feedback on what they learned rather than how entertained they were.
        -   We are also very fond of sticky notes...
    -   Purpose of feedback is to guide lesson development so that authors aren't designing and arguing in a vacuum.
        -   What people immersed in the lessons think needs fixing and what learners think needs fixing can be very different.
1.  Publish each lesson periodically, and give people credit when you do.
    -   Give people credit in a digestible way as a reward for contributing.
    -   List the lesson's maintainers as editors (since everyone understands that role).
    -   Tell people what the release schedule is.
    -   Give all contributors credit when you publish (having been clear up front who counts as a contributor).
    -   Be open to candid conversations around credit --- not all employment contexts are the same. 
1.  Tell people where else to look.
    -   The lesson is a beginning, not an end, so point them at similar material and where to go next.
    -   Make it part of a much broader conversation.
1.  You can't help (or please) everyone.
    -   Discuss minor disagreements, fork for major ones (Ian thought: FILL OUT A BIT MORE - ``fork'' 
        might not be clear?).
        -   If there are several complementary ways to explain something,
            or several points of views that can cohabit respectfully,
            present them side by side
            (just as with any other kind of lesson, essay, etc.).
            -   Cf. choral explanations.
        -   If there are major disagreements that can't cohabit respectfully,
            fork the lesson,
            i.e., have the groups go their separate ways.
        -   Same applies to governance:
            if enough people disagree strongly about how the lesson should be managed,
            fork.
        -   Which is a strong argument in favor of open licensing.

## Mechanics

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
