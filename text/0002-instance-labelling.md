- RFC Name: `Instance Labelling`
- RFC PR: [iftas-org/rfcs#0002](https://github.com/iftas-org/rfcs/pull/0002)
- Start Date: 2023-07-01

# Target Audience

[target-audience]: #target-audience

Use this section to list the different working groups within IFTAS that this proposal is related to, and which platforms you would desire review of this proposal from.
This proposal is subsequent to discussions made in the IFTAS chat channel `Moderation Tooling` and `Moderator Community Chat`.

# Summary

[summary]: #summary

We're considering that the Fediveserse, as a decentralized social network, is the communication hub for several social communities, for members among them but also with other members of other communities.
Those diverse communities will have different views on how to interact, and might want to defend an idea of the rules they accept to be interacting sanely with their members.
When different social instances want to be inclusive for a community, whether some, all or none of their users are members of this community, they would want to adhere to the rules defined by this community.
This set of rules can be represented and offered as a label by the instance, so that users who see it and know about it can recognize it.
Having this label would mean that the instance should be safe to be federated with by other instances that adheres to the community views.

# Motivation

[motivation]: #motivation

This proposals stems from a will to allow the Fediverse communities to acknowledge themselves as well as defend the rules that they want their community members and outside interactors to follow in interacting with each other.
We also wish that presenting those labels as a way to facilitate federation with friendly instances pushes more people to accept them as the way to interact properly together, and as a consequence, pushes instances to accept more friendly labels.

# Guide-level explanation

[guide-level-explanation]: #guide-level-explanation

Explain the proposal as if it was already existing in the Fediverse, as if you were teaching it to another person familiar with the Fediverse. That generally means:

- Introducing new named concepts.
- Explaining the feature largely in terms of examples.
- Explaining how reviewers should _think_ about the feature.
- Discuss how it should impact the the Fediverse, it should explain the impact as concretely as possible.
- If applicable, provide sample use-cases, and how it would affect different interested parties (General Public, Moderators, Server Operators, Platforms).
- If applicable, describe the differences between this proposal and existing solutions.

# Reference-level explanation

[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- Its interactions with the Fediverse (ActivityPub and Platforms) is clear.
- It is reasonably clear how the feature would be implemented.
- Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks

[drawbacks]: #drawbacks

Why should we _not_ do this?

# Rationale and alternatives

[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?
- Does the proposal make it easier or harder to moderate, administrate, and maintain Fediverse services?

# Prior art

[prior-art]: #prior-art

Discuss prior art, both the good and the bad, in relation to this proposal.
A few examples of what this can include are:

- Does this feature exist in other social networks, and what experience have their communities had?
- For community proposals: Is this done by some other community and what were their experiences with it?
- For other teams: What lessons can we learn from what other communities have done here?
- Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.

This section is intended to encourage you as an author to think about the lessons from other social networks and research into trust & safety, provide readers of your RFC with a fuller picture.

If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other social networks.

Note that while precedent set by other social networks is some motivation, it does not on its own motivate an RFC.

# Unresolved questions

[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

# Future possibilities

[future-possibilities]: #future-possibilities

Think about what the natural extension and evolution of your proposal would
be and how it would affect the Fediverse as a whole in a holistic
way. Try to use this section as a tool to more fully consider all possible
interactions with the Fediverse in your proposal.
Also consider how this all fits into the roadmap for IFTAS and various platforms that would potentially need to implement this functionality to be compatible or in accordance with this RFC.

This is also a good place to "dump ideas", if they are out of scope for the
RFC you are writing but otherwise related.

If you have tried and cannot think of any future possibilities,
you may simply state that you cannot think of anything.

Note that having something written down in the future-possibilities section
is not a reason to accept the current or a future RFC; such notes should be
in the section on motivation or rationale in this or subsequent RFCs.
The section merely provides additional information.
