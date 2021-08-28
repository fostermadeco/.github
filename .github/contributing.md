# Contributing

Hello! We're excited that you want to get involved in contributing to Foster Made's repositories.There are lots of ways to get started: helping fellow team members, reporting and triaging bugs, updating documentation and standards, and more! If you have an idea for how you can contribute to these projects that isn't listed here, you are welcome to create a pull request with your changes to this guide.

Welcome aboard!

Table of Contents:

- [Helping Fellow Team Members](#helping-fellow-team-members)
- [Reporting Bugs](#reporting-bugs)
- [Triaging Bugs](#triaging-bugs)
- [Contributing Code](#contributing-code)

## Helping Fellow Users

One of the best and easiest ways to help fellow team members is improve our repositories, documenting your experiences to assist others when they encouter scenarios similar to the ones you encounter.

## Reporting Bugs

_If you have a **security issue** to report, please be careful not to open an issue on any public GitHub repositories. Instead, send an email to [ops@fostermade.co](mailto:ops@fostermade.co) with the subject **SECURITY VULNERABILITY IN \[REPO\]**. Thanks!_

If you have found an issue or are requesting a new feature, please first search the Open and Closed Issues to see if your issue has already been reported. If it has, and you have additional helpful information, please add it!

If your problem has not been reported yet, just open a new Issue in the related GitHub repository. Here are some tips on filing good bug reports that can be addressed by code contributors. The Issue template will help remind of you of these pointers:

- **Use the latest version.** Ensure you are using the latest version of the repository in question.

- **Include a good description of the problem.** For someone to fix your bug, they need to understand exactly what's happening. Describe what you expected to happen, and what actually happened.

- **Include error messages.** If your problem throws error messages, cut and paste them verbatim; paraphrased error messages can make tracking down the problem more difficult. Please include the complete stack trace if the error included it.

- **Show how to reproduce the error.** You can do this by text, image, video, whatever is easiest for you to clearly show someone how to replicate this problem on ther own installation.

- **Include environmental details.** Include the all of the relevant environment details including application, framework, and language versions.

## Triaging Bugs

Bug reports often need grooming before a code contributor can take ownership of a problem and fix it. Bugs get fixed rapidly when they are easy to reproduce and focus on a single issue. And the Issue tracker can get overwhelmed if there are many duplicate or similar reports.

Even if you're not sure how to contribute code fixes, you can still help!

- **Confirm bugs.** A code contributor can't fix a bug that they can't reproduce. If the original report includes instructions to replicate, confirm that it is indeed reproducible. If that's been left out, ask the original submitter to add that information to their bug report.

- **Help people write good bug reports.** If you notice that a bug report is lacking detail, clarity, or any of the details under [Reporting Bugs](#reporting-bugs), coach the submitter on what is missing and why it's important. Be kind and tactful, so they are encouraged to submit good bug reports in the future!

- **Identify duplicate issues.** If more than one report exists for the same root issue, comment on the task that noting the duplicate so that someone can verify the duplication and close one of the tasks.

- **Try.** Here's the deal. Many of us didn't know how to fix the bug until we fixed it. We didn't know where to start until we started. We didn't know what to do until we did it. Often, the first step is the most important one. Take that step.

## Contributing Code

- [Smallest Change Possible](#smallest-change-possible)
    - [Branches / Semantic Versioning](#branches--semantic-versioning)
    - [Unrelated Code Changes](#unrelated-code-changes)
    - [Proposing Large Changes](#proposing-large-changes)
- [Documentation](#documentation)
- [Tests](#tests)
- [Code Review](#code-review)
- [Coding Styles](#coding-styles)

We're a team of experts and collectively we demand very high threshhold for quality of our code. The guidelines below are meant to assist in keeping that bar high, and in ensuring that all of our code remains easily and highly maintainable.

### Smallest Change Possible

A general principle to follow is to make the "smallest change possible". Bug fixes and enhancements should only tackle a single issue whenever possible. Iteration and incrementalism are the names of the game.

Even tiny changes have secondary and tertiary effects, which must be well understood before any contributions are merged and released.

Don't worry about your commit history, you can make small, atomic commits, the squash those commits with `git rebase` to maintain a clean repository and history.

#### Branches / Semantic Versioning

~~You will want to make sure your fork is easily updated from the upstream repo, so do not make changes on any published branches, including `stability`. Recommended branch names are namespaced and unique, e.g.:~~

- `feature/{task-id}-my-feature-slug`
- `hotfix/{task-id}-bug-description-slug`


#### Unrelated Code Changes

Avoid making unrelated changes in your branch, or it may result in your pull request being closed without review. This includes whitespace and stylistic changes that are outside of files directly related to your change.

#### Proposing Large Changes

Large changes have a few problems:

- Massive changes are difficult and time consuming to review.
- They often have multiple components and changes that must be developed in a waterfall fashion.
- They are time consuming to plan, write, document, test, and explain.

Therefore if you have a large change you'd like to propose, start with a _Feature Request Issue_. Before spending a lot of time developing your idea, you'll want to make sure that the team is in agreement with the request. They can also help you plot out how to tackle it in a way that is most likely to lead to inclusion in the project.

Often, new features have the best implementation when user-facing documentation is written before any code. This also helps make large-scale proposals easier to understand and digest, with the intended behavior and usage made clear in advance.

### Testing

TODO: General commentary on testing.

### Code Review

TODO: Commentary on pull requests.

### Coding Styles

TODO: Document on following repository-specific guidelines.
