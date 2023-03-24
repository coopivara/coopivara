> **Disclaimer**: este documento está sendo escrito com a ajuda do ChatGPT e do Notion AI, por isso está em inglês. Ele será traduzido para português em tempo oportuno.

# RFC-001: Introducing the RFC process to the co-op

- RFC number: 001
- Author(s): Guilherme Jordan
- Status: <Draft>
- Date submitted: <24/03/2023>
- Date last updated: <24/03/2023>

## Summary

This RFC proposes the adoption of the Request For Comments (RFC) process in our co-op to enhance our ability to collaborate effectively, promote transparency and accountability, and deliver high-quality solutions. Inspired by the success of the RFC process in the open source community, this document outlines the benefits of the RFC process and how it can be applied to our work on complex topics such as strategy, planning, feature design, policy-making, software architecture and adoption of best practices. 

## Motivation

We are committed to collaborating in a transparent and inclusive manner, but we have been struggling to adopt clear processes that enable us to organize our work effectively. Our current platform, Discord, has limitations that make it challenging to dive deeper into complex topics and preserve our knowledge in a structured way. While Discord is useful for short communication, many of our members do not have the time to engage in all synchronous conversations, requiring longer periods to contribute to discussions. Additionally, the work produced in Discord is not durable, hard to search, and outside of our control as it is a closed-source app, which we can lose access to at any time.

## Proposal

We propose the adoption of the RFC process as a way to enhance our cooperative's ability to collaborate effectively and promote transparency and accountability. The RFC process is a structured approach used in the open source community to enable distributed collaboration and decision-making. It involves creating a document that outlines a problem, a proposed solution, and a set of questions for feedback and discussion. This document is then circulated for comments and suggestions from all members of the cooperative. By embracing the RFC process, we can create a more democratic, decentralized, and open environment that enables us to tackle complex topics such as strategy, planning, feature design, policy-making, software architecture, and adoption of best practices while preserving our knowledge and evolving over time.

The RFC process provides a durable, searchable, and open documentation of our work that can be accessed and modified by all members of the cooperative. This ensures that our knowledge is preserved and structured, and that all members have equal access to it. By creating an open discussion forum, the RFC process also allows members to contribute to discussions at their own pace and on their own schedule, which is essential for members with limited time. Furthermore, the RFC process enables us to make informed and participatory decisions based on the feedback and suggestions of all members of the cooperative, which promotes transparency and accountability.

In summary, the RFC process offers a powerful and flexible approach for organizing our work and fostering collaboration. By adopting this process, we can help unlock our cooperative's potential and achieve our shared vision of democracy, decentralization, openness, equality, and social justice.


## Implementation

To implement the RFC process, we propose the use of Git and the issues feature of GitHub. This will allow us to take advantage of the powerful collaboration and version control features of Git, while also providing a transparent and organized platform for discussion and feedback using GitHub issues. This repository will serve as the central hub for all RFCs and discussions related to them. We encourage you to follow this file structure:

```
📁 rfc
├── 📄 template_rfc.md
├── 📁 rascunhos/
│ ├── 📄 rfc-001-introduzindo-rfcs.md
└── 📁 em_revisao/
└── 📁 aprovadas/
└── 📁 rejeitadas/
```

You can start from the [RFC template](/rfc/template_rfc.md). 

1. **Submitting an RFC**: Any member of the cooperative can submit an RFC by creating a new branch in the RFC repository and copying the RFC template to that branch. They can then fill out the template and submit a pull request for discussion and feedback.

1. **Discussing and iterating on an RFC**: Once an RFC is submitted, it will go through a process of discussion and feedback. Members of the cooperative can review and comment on the RFC, and the author can respond to those comments and make changes to the proposal. This process can take as long as necessary to ensure that all concerns and feedback have been addressed.

1. **Approving an RFC**: Once an RFC has gone through the discussion and feedback process, it can be approved by a consensus of the members of the cooperative. Consensus can be reached through a vote or a period of silence where no objections are raised.

1. **Implementing an RFC**: Once an RFC has been approved, it can be implemented by creating a new branch in the cooperative's main repository and making the necessary changes to the codebase. The RFC should also be updated with implementation details and any challenges or trade-offs encountered during the implementation.

1. **Continuously improving the process**: We should continuously evaluate and improve the RFC process to ensure that it meets our evolving needs and circumstances. This can include reviewing the RFC template, evaluating the effectiveness of the discussion and feedback process, and analyzing the impact of approved RFCs on the cooperative's projects and goals.
