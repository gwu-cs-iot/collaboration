# Requirements for a Paper Review

Significant components of this class are based around reading, reviewing, and discussing research papers.
IoT is a burdgening field, and understanding the cutting edge is necessary and learning to effectively digest research papers is required to sample the cutting edge IoT techniques and systems.

## The paper discussion process

The paper interpretation and discussion will be broken down into three components:

1. Reading the paper yourself.
1. Providing your review online.
1. In-class discussion and analysis.

### Where to provide your review for the second component

The student assigned with leading the paper's presentation and discussion will create an "Issue" with the `paper discussion` tag.
You must provide your paper review as a reply to that issue.
If the student leading the paper's discussion has not yet posted the issue, you should post an issue `@`-ing them to post the issue.

### Timeline

You must provide your review at least *24 hours* before the paper's discussion.
For example, if a paper is going to be discussed on Thursday, you must provide your review by 12:45 on Wednesday.

## Reading a Paper

A published research paper was accepted into a conference or journal, was reviewed by a panel of peer researchers (i.e. peer review), and determined to be a significant contribution to human knowledge.
The goal of a research paper is to present a set of contributions (that represent new human knowledge, or something that we did not know before this paper), place these contributions into the context of the surrounding previous research (often called "related work"), and evaluated to validate the contributions.
The *contributions* of a paper are one of the most important aspects of the paper to understand.
They represent the *reason* the research was performed, and how it provides value to the world.
The rest of the paper provides context about, the details around, and the evaluation that validates these contributions.

As a student learning more about a field, research papers also have a number of other beneficial aspects.
They let you learn about the problems that others find interesting and important.
They provide background about the problem domain, and existing approaches to existing solutions (often spread across the Introduction and Related Work sections).
They provide details about the design and implementation of the system which may teach you about new infrastructures, new tools, and new techniques that you didn't previously know existed.

One way to read a paper is to approach it in three Phases.
Please see [this document](https://github.com/gwu-iot/collaboration/blob/master/resources/local_copy/how_to_read_a_paper.pdf) from Keshav for more information.

### Phase 1: The Skim

The main goal of *the skim* is to

1. understand the problem domain -- what problem is being solved?
1. understand the contributions at a high-level -- how did the authors solve the problem, and what was interesting about their solution?
1. understand what you *do not yet know* about the paper -- what are your main questions about the paper?

The skim takes about 10-15 minutes and includes:

1. Read the abstract and introduction
    - Highlight each contribution they claim
2. Look at the title of each section/subsection
    - Guess what it will be about, but don’t read it carefully
3. Examine the figures and tables
    - Understand what metrics they will evaluate
4. Read the conclusion and any parts that stand out

You now know:

- Paper type: theoretical, modeling, implementation, measurement
- The main goals of the paper
- What evaluation the authors think is important

This is hard, and you will (quickly) reach a point where you don't know or understand something.
In these cases you have two options:

1. Read more background work on the topic (potentially references from the paper).
1. Treat the topic as a black box
    - what are the inputs?
    - what are the outputs?
    - what is the overall goal?

You don't need to understand *everything*!
You'd be surprized how far you can get by intelligently choosing what to treat as a black box.
However, by the end of the paper reading process, you'll need to  *understand* the key concepts relevant to the main contributions.

### Phase 2: Understand

We will also call this a *comprehension review*.

Skimming let you know *what* the authors have done; now read the paper to understand *how*.
In doing so, you'll still skip implementation details, proofs, and other details that are too "in the weeds".

Make notes as you read

- Summarize main points
- List questions you have
- Circle references that you need to look at for background

By the end of this phase, you should clearly understand the problem and the proposed solutions.

### Phase 3: Critique

We will also call this a *critical review*.
The goals of reading a paper:

- Learn about new tools/problems/algorithms
- Critique the paper’s science
- Not it’s grammar nor figure colors

Third phase: judge the paper’s details

- Skip the background that you have already read
- Analyze the assumptions being made
- Consider how you would solve the problems and compare
- Think about what is missing (evaluation, assumptions, proofs...)

## Paper review
You must Phase 1 review every paper on the syllabus.
This is the only reading you need to do on weeks where you are a discussion leader (except for the paper you're presenting of course).

On weeks with two days of paper reading (four papers), you must Phase 3 review one paper and Phase 2 review another paper.
These two reviews must happen on different days.
For example, if on a Thursday, you provide a Phase 3 review for one of that day's papers, then on Tuesday, you have to provide a Phase 2 review.

On weeks with one day of paper reading (two papers), you must do one Phase 2 or one Phase 3 review.

By the end of the semester, your number of Phase 2 reviews must be about the same as your number of Phase 3 reviews.
To be precise, the difference between the number of Phase 2 reviews you did and the number of Phase 3 reviews you did must be 3 or less.
The implication of this rule is that you must balance doing Phase 2 and Phase 3 reviews on weeks where there is only one day of reading.

Note that only a restricted number of students can review a given paper.
This is represented as the space available in the spreadsheet to track who is doing what type of review.
These are allocated first-come, first-serve.

Please sign up for your critical/comprehension reviews using the [form](https://docs.google.com/spreadsheets/d/1v_IVhO5MSM870ayeUy8Ooz0nfI-F0S5-iKOlyK6hBcM/edit?usp=sharing).
You cannot sign up for a critical/comprehension review for a paper if the eight slots are already filled for the paper.
Remember, you must sign up for one critical and one comprehension review each week, and they should not be for papers presented in the same day.

After doing a Phase 1 review, there is no need to write or submit anything.

However, you must do some writing after a Phase 2 or Phase 3 review.
This write-up must include:

- A two to three sentence summary of the problem being solved.
- A two to three sentence summary of the main contributions.
- Three questions about the paper. These questions might be about (but aren't limited to) ideas or concepts that you don't understand, design or implementation decisions that don't make sense to you, and questions about the problem domain.

For a Phase 3 *critical review* this must also include:

- Three critiques or critical comments about the paper, its assumptions, the system's design, etc...

You should be *terse* and precise.
You should not provide long reviews.
The goal of a review is *not* to judge the paper, but instead to raise a set of questions and concerns about the paper.

If the paper is a *survey* which summarizes an area of research including many separate papers, the following structure might be more appropriate:

- Two to three sentence summary of the problem being solved.
- Two or three sentence summary of the areas that are most important to the survey.
- Three questions about the survey.
- Two critiques about the survey.
    Are there areas it ignores?
    Has the world changed since the survey was written, and it should be augmented with more modern issues?
    Are the assumptions of the problem domain less than ideal?

## Submitting your review

Your review write-up should be submitted as a comment in the Github issue (in the `collaboration` repo) for the paper you reviewed.
Please start your write-up with:

```
Reviewer: Gabe Parmer
Review type: Critical

...
```

Of course, replace `Gabe Parmer` with your own name, and `Critical` with `Comprehension` if you did that type of review instead.

## In-class discussion

The in-class discussion of each paper will be led by a single student.
That student is responsible to present the paper, *and to present a representative render of the reviews* of their peers.
See [the presentation guide](https://github.com/gwu-iot/collaboration/blob/master/discussion_leader.md) for more information.
