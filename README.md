# Starter pack for CS310 etc.

This repository contains a starter pack of resources for CS310 and other, similar modules. It is comprised of:

- LaTeX templates for the project specification, progress report, and dissertation.
- GitHub Actions workflows for building each report and making them available as build artifacts.
- Generic advice for writing the reports.

## Advice for writing reports

Before you do anything else, read [Writing for Computer Science](http://encore.lib.warwick.ac.uk/iii/encore/record/C__Rb2777534): I recommend Chapters 1 to 8 and Chapter 13. Then have a look at some samples of _good_ reports that students in previous years have written.

Some summary advice for avoiding common mistakes:

- All three documents should be _self-contained_. Don't assume the person reading your progress report has read your specification. Don't assume the person reading your dissertation has read the specification or progress report.
- Keep your _audience_ in mind: they don't know anything that a general Computer Scientist doesn't know. I.e. they don't know what your project is about, they don't know why it is worth doing, and they don't know literature you have read related to it.
- Think about your _narrative_: there should be a logical structure that flows through your document. For example, a common structure for a dissertation is the following (the project specification and progress report may only use parts of this):
    - _Motivation_: Establishing the context of the work by gently easing the reader into the domain and identifying a problem in it.
    - _Related work_: Discussing what existing solutions there are, how they compare, and why they don't yet address the problem you have identified.
    - _Objectives_: Clearly and concisely stating how you are going to solve the problem.
    - _Background_: Your literature review consisting of explanations and discussions of academic literature you have read that relates to or is required to understand your report.
    - _Design_: A discussion of your solution for the problem you identified. This should explore the design space: i.e. a comparative discussion of different options that were available to you to justify the ones you chose in the end.
    - _Implementation_: A discussion of the most challenging parts of implementing your solution. This should ideally be comprised of solutions to implementation problems that would not be obvious to a Computer Science graduate.
    - _Evaluation_: Evidence that your work does indeed solve the problem you identified. This is ideally backed up by data and comprised of tables, graphs, statistics, etc.
    - _Conclusions_: A summary of what is accomplished and what future work could build on the work you have done.
- Write in _present tense_ for anything that is true at the time of writing. This includes references to later parts of a report (i.e. instead of "In Chapter 5, we will describe [..]" you should write "In Chapter 5, we describe [..]"). Use past tense for anything that was once true, but is no longer true (e.g. "people once believed the Earth was flat"). Use future tense only when describing work you have not yet done (e.g. in the project specification or progress report). It would not be unusual for there to be no future tense at all in the dissertation.
- Avoid the passive voice and always use the _active voice_. Ideally first-person plural ("we"), although first-person singular is also acceptable ("I").
- Be _explicit_. For example, don't write "There are many applications for this technique.". Instead write "This technique can be applied to e.g. cakes, pastries, and waffles.".
- Keep sentences _short_.
- Be _accurate_. Read what you write and ensure that your wording is technically accurate and makes logical sense.
- _Use terminology consistently_: there is nothing wrong with repeating the same term several times, even in close proximity. Do not use synonyms to refer to the same concept.

## Getting feedback

- Get feedback early, ideally for a single chapter at-a-time.
- Use GitHub/diffs to make it easier to see what has changed:
    - Do all work for a new report in a separate branch and open a pull request against your main branch, then ask for reviews on that pull request. This will make it easier to see what has changed since the last review, provided you do not force-push to the branch.
    - Alternatively, use GitHub's diff compare feature and link to a diff of the current commit compared to the one that was last reviewed.
- Say what you want feedback on and, if you aren't using PRs/diffs, summarise what has changed.
