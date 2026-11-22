# The Meta System Design Interview

Meta runs two types of design interview, and a candidate usually gets one type per round. System design asks for a distributed system that handles very large load. Product architecture, which Meta calls product design, asks for a user-facing feature with its API and data model. Both are commonly reported as 45-minute rounds.

Design rounds start at about E5. Entry-level candidates usually have none, and reports for E4 vary. Ask your recruiter which type you will get, because the two types reward different uses of the same 45 minutes.

## The two types compared

| Dimension | System design | Product architecture |
|---|---|---|
| Starting question | What must the system handle and guarantee? | What must users be able to do? |
| Main focus | Scale, data flow, reliability, performance | User flows, API, data model, client behavior |
| Requirements | Traffic, storage, latency, availability, consistency | Users, use cases, feature scope, privacy |
| Typical detailed section | Partitioning, replication, caching, queues, failures | API contracts, schema choices, feed or workflow behavior |
| Typical question | Design a distributed cache or a message queue | Design a social feed or a ticket-booking product |
| Who usually gets it | Engineers with infrastructure or backend experience | Engineers who build user-facing products, including mobile |

Latency is the time one request takes. Partitioning splits data across machines, and replication keeps copies of it. Meta is reported to match the interviewer to the candidate's background where it can. The same question, such as a news feed, can be asked in either type.

## Questions commonly reported

Meta is reported to base many questions on its own products, so the list follows Facebook, Messenger, Instagram, and WhatsApp.

| Question | Worked lesson |
|---|---|
| Design the Facebook news feed | [Designing Facebook's Newsfeed](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-facebooks-newsfeed?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design Facebook Messenger or WhatsApp | [Designing Facebook Messenger](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-facebook-messenger?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design Instagram | [Designing Instagram](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-instagram?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design an online ticket platform | [Designing Ticketmaster](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-ticketmaster?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design Nearby Friends | [Designing Yelp or Nearby Friends](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-yelp-or-nearby-friends?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design status search | [Designing Twitter Search](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-twitter-search?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design search autocomplete | [Designing Typeahead Suggestion](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-typeahead-suggestion?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |
| Design a distributed file storage system | [Designing Dropbox](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-dropbox?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview) |

Other reported questions include an ad click aggregator, a top K trending topics service, live comments on a video stream, and a content moderation system.

## What Meta's products imply

| Product fact | Topic to prepare |
|---|---|
| Each main product serves more than one billion users | Horizontal scaling, which adds machines, and data partitioning |
| Users are spread across the world | Global distribution, content delivery networks, and replication |
| Feeds are ranked for each person | Fan-out on write and on read, ranking inputs, and caching |
| Messenger and live video work in real time | Persistent connections, message ordering, and delivery to offline users |
| Feeds and ads depend on machine learning | Where a recommendation service sits in the request path |

Fan-out is the delivery of one post to the feeds of many followers.

## A 45-minute plan

| Minutes | Step |
|---|---|
| 0 to 5 | Clarify functional and non-functional requirements, and confirm the type of round |
| 5 to 10 | Estimate load where the number changes a decision; define the API |
| 10 to 20 | Draw the high-level design and the data model |
| 20 to 35 | Go into detail on one or two hard parts |
| 35 to 45 | Name bottlenecks, failures, trade-offs, and next improvements |

## What a strong answer includes

- A scope agreed with the interviewer in the first five minutes.
- A data model and an API, not only boxes and arrows.
- A reason for every component, tied to a stated requirement.
- Depth in one or two parts, such as feed generation or message delivery.
- Trade-offs stated aloud: the option rejected and the cost of the option chosen.
- For product architecture: one user action traced from the client to storage and back.
- A design the candidate leads, with the interviewer's hints used and not ignored.

## Go deeper

- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview): worked designs for the questions in the table above.
- Lesson: [Designing Facebook's Newsfeed](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-facebooks-newsfeed?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview), in Grokking the System Design Interview
- Lesson: [Interview question: design the API behind a news feed screen](https://www.designgurus.io/course-play/grokking-modern-api-design-interview/doc/interview-question-design-the-api-behind-a-news-feed-screen?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview), in Grokking Modern API Design Interview
- Lesson: [The importance of discussing trade-offs](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/importance-of-discussing-tradeoffs?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview), in Grokking the System Design Interview
- Free article: [Product architecture vs system design: key differences](https://www.designgurus.io/blog/meta-system-design-vs-product-design?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview)
- Free article: [Meta system design interview questions and solutions](https://www.designgurus.io/blog/meta-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=system-design-interview)
