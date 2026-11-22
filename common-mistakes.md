# Common Mistakes in the Meta Interview

Most candidates who fail the Meta loop are reported to fail on pace, on the wrong type of design answer, or on stories at the wrong scope. Few fail because a question was unknown to them. This page lists ten mistakes that are specific to the Meta loop, with a correction for each.

## The ten mistakes in one table

| # | Mistake | Round | Correction |
|---|---|---|---|
| 1 | Practicing one problem per session | Coding | Practice two problems in 35 minutes |
| 2 | Optimizing before the code is correct | Coding | Reach a correct solution first, then improve it |
| 3 | Coding in silence | Coding | Explain each step aloud |
| 4 | Declaring the code finished without a test | Coding | Trace one normal input and one edge case |
| 5 | Not asking which design round you have | Design | Confirm system design or product architecture with the recruiter |
| 6 | Treating product architecture as product management | Design | Move from use cases to API, data, and services |
| 7 | Listing technologies without reasons | Design | Tie every component to a requirement |
| 8 | Staying at the high level for 45 minutes | Design | Go into detail on one or two hard parts |
| 9 | Telling stories at the wrong scope | Behavioral | Match the story to the target level |
| 10 | Treating the behavioral round as informal | Behavioral | Prepare six to eight stories with measured results |

## Coding mistakes

**1. Practicing one problem per session.** A Meta coding round is commonly reported to contain two problems in about 35 minutes of working time. A candidate who has only practiced 40-minute problems finishes one and fails the round. See the time budget on the [coding interview](coding-interview.md) page.

**2. Optimizing before the code is correct.** Early optimization adds bugs and uses the minutes needed for the second problem. State the efficient approach, write it correctly, and improve it only if time remains.

**3. Coding in silence.** The interviewer writes feedback about your reasoning as well as your code. Silence also prevents hints.

**4. Declaring the code finished without a test.** An edge case is an unusual input, such as an empty array. Finding your own bug is a positive signal, and the interviewer finding it is a negative one.

## Design mistakes

**5. Not asking which design round you have.** The two types reward different uses of the time. An answer about partitions and throughput can fail a product architecture round that wanted the API and the data model. Open with one question: should the answer emphasize the product workflow or the infrastructure?

**6. Treating product architecture as product management.** User goals matter, but the round is an engineering interview. After five minutes of scope, the answer must contain endpoints, entities, and services.

**7. Listing technologies without reasons.** A cache, a queue, and a NoSQL database do not make a design. Each component needs one responsibility and one requirement that justifies it. The lesson on [things to avoid during a system design interview](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/things-to-avoid-during-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes) covers this in detail.

**8. Staying at the high level for 45 minutes.** Meta is reported to look for depth in key parts, such as the data model, request flows, and failure handling.

## Behavioral and level mistakes

**9. Telling stories at the wrong scope.** The loop is scored against a target level. A story about one feature is evidence for E4, even when it is told well. E5 needs end-to-end ownership, and E6 needs influence across teams. See [levels](levels.md).

**10. Treating the behavioral round as informal.** The round is scored like the technical rounds and is reported to affect both the decision and the level. Answers that use "we" throughout, give no number, or contain no real failure are the most common weak signals. See the [behavioral interview](behavioral-interview.md) page.

## Go deeper

- [Grokking the Meta Coding Interview](https://www.designgurus.io/course/grokking-meta-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes): timed practice on the problems Meta is reported to ask.
- Lesson: [Things to avoid during a system design interview](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/things-to-avoid-during-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes), in Grokking the System Design Interview
- Lesson: [How companies frame the behavioral round](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/how-companies-frame-the-behavioral-round?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes), in Grokking Modern Behavioral Interview
- Lesson: [Down-leveling: causes and responses](https://www.designgurus.io/course-play/grokking-staff-engineer-interview/doc/down-leveling-causes-and-responses?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes), in Grokking Staff Engineer Interview
- Free article: [Product architecture vs system design: key differences](https://www.designgurus.io/blog/meta-system-design-vs-product-design?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes)
- Free answer: [What is a Meta interview?](https://www.designgurus.io/answers/detail/what-is-a-meta-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=common-mistakes)
