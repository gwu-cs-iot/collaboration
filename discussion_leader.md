# How to Lead a Paper's Discussion

You can sign up to be a discussion leader for a paper using the [form](https://docs.google.com/spreadsheets/d/1v_IVhO5MSM870ayeUy8Ooz0nfI-F0S5-iKOlyK6hBcM/edit?usp=sharing).

## Timeline

*Two weeks* before the day you must lead the paper's discussion, you must

- Your `.pdf` should be in `papers/`, using a pre-defined [naming scheme](https://github.com/gwu-iot/collaboration/blob/master/papers/README.md).
    Link that paper from the syllabus, and from the list of papers in that [directory](https://github.com/gwu-iot/collaboration/blob/master/papers/README.md).
    You must test that both links work and properly resolve to the pdf.
    Other students will use this link to access the paper.
- Add a `github` Issue using the `paper discussion` tag titled "Paper discussion: ##. XXX" where you replace "##" with the paper number (from the syllabus, like `9a`), and  "XXX" with the paper's title.
    The body of the issue should simply include "Please add your feedback and reviews below.".

In the week *before* the week you lead the paper's discussion, and 24 hours *before* office hours, you must send Gabe an email, titled "IoT S&S: Presentation Draft" including:

- A link to your presentation created using google slides (see [template](https://docs.google.com/presentation/d/16hrWPUGSp1Zz9E0J3Oq3_QyQpejXYTHucG4OlOtsI64/edit?usp=sharing)).
    This must be a *complete* presentation.
    Expect to iterate on it, but at this point, you must have a quality result.
- A list of questions you still have about the paper and presentation.
- Go to Gabe's office hours (in the preceeding week) to discuss these slides, and address your questions.

In effect, you'll provide your presentation, a set of questions you have, and you'll meet with Gabe in the week preceeding the week of your presentation.

*One day* before you'll lead the paper's discussion, read through all student's reviews and discussion in the github issue.
Please summarize the questions and critiques of from the other student's comments in the body of your issue (i.e. edit your initial post for the issue).
Do so as a bulleted list (read about how to do so in [markdown](https://guides.github.com/features/mastering-markdown/)), and please label each bullet with `@id, name, type:` which is the github id of the student, the name of the student that asked the question or made the comment, and what type of review they were supposed to provide (critical or comprehension).
They should provide their name and review type along with their review.
The bullets should look like this:

- @gparmer, Gabe Parmer, critical: The paper makes a very strong assumption that the IoT is useful at all. They argue that ...

(Of course, please replace the comment with actual, useful feedback.)

This does not need to be a *complete* list, rather a list of what you see as the most productive and useful questions and comments.

Add another couple of slides at the end of your presentation that includes this list of questions/comments.
We'll discuss them in class.

## Presenting the Paper

Doing a good presentation is quite difficult.
I expect you to put time into doing it well, and to improve over time.

## Presentation Expectations

Your presentation should use the [class template](https://docs.google.com/presentation/d/16hrWPUGSp1Zz9E0J3Oq3_QyQpejXYTHucG4OlOtsI64/edit?usp=sharing) by copying it, and, after you're done, sharing it with Prof. Parmer.
Each presentation *must* be highly practiced, and should be targetted for *23 minutes*.
When you send the presentation to Gabe, please make sure that it fits into 23 minutes.
As a rough guide, this 23 minutes should be decomposed as:

- 7 minutes on background, and the problem domain.
    What is the problem being solved, and why does it matter?
- 1 minutes a clear definition of the problem being solved, and a high-level description of how the authors solve it (lacking details).
- 2 minutes discussing assumptions about the problem domain and solution.
- 4 minutes discussing a high-level design of the system and how it solves the problem.
- 5 minutes discussing evaluation.
- 3 minutes critiquing the paper, discussing assumptions, and generally having a critical eye.
- 1 minute conluding the paper, and summarizing its main contributions.

Note that the presentation will likely go longer than this as everyone in the class should ask clarification questions if there are confusions.

After this presentation, the leader should put a representative set of student questions on the screen, and we'll use them to guide another 20 minutes of discussion.

Note that some papers are better described as *surveys* that discuss a set of research in a domain, rather than discuss a specific contribution.
For these papers, the following guide is more appropriate:

- 7 minutes on background and the problem domain.
- 1 minute defining the goal of the survey, and what it is exploring.
- 10 minutes iterating on the surveyed material.
    Follow the structure of the paper and the methods of defining taxonomies.
- 2 minutes on critiquing the problem domain, and the survey.
    What assumptions does all of the work make?
    What areas are not covered by the survey that are interesting in the problem domain?
    What open problems remain?
- 3 minutes summarizing
