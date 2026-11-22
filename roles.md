# How the Meta Loop Differs by Role

The loop described in this guide is the software engineer loop. Two other roles have well-documented differences: engineering managers get a longer loop with leadership rounds, and mobile engineers usually get a client-focused product architecture round. This page covers only those roles, because they are the ones that published sources describe.

## The loops compared

| Stage | Software engineer | Engineering manager | Mobile engineer (iOS or Android) |
|---|---|---|---|
| Screen | 45 minutes, one or two coding questions | 45 minutes on people management, technical design, and career motivation | Coding screen, as for software engineers |
| Coding | 2 rounds, two problems each | 1 round of coding or code review, reported as easier | 2 rounds |
| Design | System design or product architecture | System design, plus an optional domain round | Product architecture with a focus on the client |
| Behavioral | 1 round | 2 or more leadership and people management rounds | 1 round |
| Extra round | Sometimes a career conversation for senior roles | Project retrospective | None reported |
| Loop size | 4 or 5 interviews | 5 or 6 interviews of 45 minutes | 4 or 5 interviews |

## Engineering manager

The engineering manager (EM) process is commonly reported as four steps: resume review, recruiter call, initial interview, and full loop. The recruiter call takes 15 to 30 minutes. The whole process is reported to take four to eight weeks.

| Round | What it covers | How to prepare |
|---|---|---|
| Leadership and people management (usually 2) | Coaching, performance problems, hiring, conflict, and work with product and design partners | Stories about growing an engineer, handling a low performer, and resolving a disagreement with a peer |
| Project retrospective | A detailed review of one project you led, sometimes with a senior engineer | One project explained as requirements, design, challenges, and results |
| System design | A high-level architecture at Meta scale | The same method as the [system design interview](system-design-interview.md), with less low-level detail |
| Coding or code review | A simple problem or a review of code for bugs | Easy and medium problems, solved aloud |
| Domain round (optional) | Product architecture or machine learning system design, by team | Ask the recruiter whether the role includes it |

A project retrospective is an interview about one finished project, its decisions, and what you would change. After the loop, a debrief and a hiring review decide the result.

Reported EM design questions include a ride-sharing backend, a mobile image upload service, and a key-value store at scale. Reported leadership questions include the following.

- How do you manage the career growth of your team?
- How do you handle a low-performing engineer?
- Describe a time a senior leader challenged your approach in a meeting.
- What is your approach to one-on-one meetings?

For a full guide to manager loops across companies, see the [Engineering Manager Interview](https://github.com/design-gurus/engineering-manager-interview) repository.

## Mobile engineer

Meta is reported to match the design interviewer to the candidate's background. For iOS and Android roles, this usually means a product architecture round about the client. Client work is treated as a valid design background and not as a smaller version of backend work.

| Graded area | What to show |
|---|---|
| User-facing requirements | The device, the network conditions, and what must work first |
| Client and server contract | Endpoints, paging, error format, and the number of requests one screen costs |
| Data model on both sides | What the server stores, and separately what the device stores |
| Failure and offline behavior | What the user sees with no network, and what happens to an action taken offline |
| Trade-offs | The option you rejected and the reason |

The most commonly published example for mobile roles is an email client: fetch mail, store it on the device, notify the user, and keep it readable offline.

## Go deeper

- [Grokking the Engineering Manager Interview](https://www.designgurus.io/course/grokking-the-engineering-manager-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles): every round of a manager loop, with worked answers.
- Lesson: [Onsite interviews for the engineering manager role](https://www.designgurus.io/course-play/grokking-the-engineering-manager-interview/doc/onsite-interviews-for-the-engineering-manager-role?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles), in Grokking the Engineering Manager Interview
- Lesson: [What to expect in a project retrospective interview](https://www.designgurus.io/course-play/grokking-the-engineering-manager-interview/doc/what-to-expect-in-a-project-retrospective-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles), in Grokking the Engineering Manager Interview
- Lesson: [Email client](https://www.designgurus.io/course-play/grokking-modern-mobile-system-design-interview/doc/email-client?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles), in Grokking Modern Mobile System Design Interview
- Free article: [How to pass the Meta engineering manager interview process](https://www.designgurus.io/blog/how-to-ace-the-meta-engineering-manager-interview-process?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles)
- Free answer: [What is a product architecture interview at Meta (Facebook)?](https://www.designgurus.io/answers/detail/what-is-a-product-architecture-interview-at-meta-facebook?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=roles)
