# Instance Labelling

- RFC Name: 0002-instance-labelling
- RFC PR: [iftas-org/rfcs#0013](https://github.com/iftas-org/rfcs/pull/13)
- Start Date: 2023-07-01

This proposal is subsequent to discussions made in the IFTAS chat channel `Moderation Tooling` and `Moderator Community Chat`.
We'll be trying to encapsulate similar ideas, like a proposal mentioned by @zkat@toot.cat : https://toot.cat/@zkat/110810390507239555

## Target Audience

[target-audience]: #target-audience

This proposal is intended to be discussed and reviewed by different actors, either making the Fediverse possible and/or attentive to its development :
- Fediverse Server Developers
- Fediverse Server Moderators
- Moderation Tooling WG
- Blocklist WG

## Summary

[summary]: #summary

We're considering that the Fediverse, as a decentralized social network, is the communication hub for several social communities, for members among them but also with other members of other communities.

Those diverse communities will have different views on how to interact, and might want to defend an idea of the rules they accept to be interacting sanely with their members.
When different social instances want to be inclusive for a community, whether some, all or none of their users are members of this community, they would want to adhere to the rules defined by this community.

This set of rules can be represented and offered as a label by the instance, so that users who see it and know about it can recognize it.

Having this label would mean that the instance should be safe to be federated with by other instances that adheres to the community views.

## Motivation

[motivation]: #motivation

This proposals stems from a will to allow the Fediverse communities to acknowledge themselves as well as defend the rules that they want their community members and outside interactors to follow in interacting with each other.
We also wish that presenting those labels as a way to facilitate federation with friendly instances pushes more people to accept them as the way to interact properly together, and as a consequence, pushes instances to accept more friendly labels.

## Guide-level explanation

[guide-level-explanation]: #guide-level-explanation

In simpler terms

- Glossary
  - Label : Proof of adhering to a community's manifesto
  - Manifesto : set of rules that binds instances that accept the label

Let's consider a Community 1, their adhering instances (one being Instance B) and a new instance A wanting to claim the Label 1 offered by Community 1.

Instance A claims the Label 1 :
Community 1 will review the claim request and approve or disapprove the claim. It can also be offered in a testing period (the users could be notified of it through label display and the community's website interface).
Instance B can review new instances that got the label (maybe through the community's website) and accept federation, either manually or automatically, of Instance A.
As Instance A has claimed the Label 1, they need to follow the manifesto attached. Community 1 reviews regularly proper following of said rules (this reviewing can be moderator-based reviews and/or user-based polls, depending on their capacity).
If Instance A follows the rules of Label 1 properly, reviews should be reflecting that and Instance A keeps the label.
If Instance A does not follow the rules of Label 1 properly, reviews tells that Instance A does not follow Label 1's manifesto, and Community 1 degrades Instance A as a non proper label abider.
For keeping the possibility of Instance A to keep the label and fix their situation, it seems fitting to show the review as a grade.
As Instance A gets a bad review, Instance B gets notified and can, manually or automatically, defederate Instance A. In certain situations, it could be of good courtesy to wait for Instance A to fix the situation, if they communicated they would and show proper improvements.

## Reference-level explanation

[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- Its interactions with the Fediverse (ActivityPub and Platforms) is clear.
- It is reasonably clear how the feature would be implemented.
- Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

## Drawbacks

[drawbacks]: #drawbacks

There is a possibility of bad actors using labels as a common banner, telling community friendly actors to accept their rules or be considered intolerant.
For that, it might be a good idea to set up some basic common ground rules that would render such labels non-compliant, and thus keeping bad behaviors out of the way.
Some rules ideas :
- Labels cannot exclude people because of their gender, ethnicity, age, disabilities, look. Exceptions to that rule being group protection (child protection, non-mixity groups)
- Labels rules have to respect people's privacy, integrity and boundaries

`/Note this is too broad, need to be better defined`
- Labels rules need to be defined clearly and broadly enough so that it is reviewable through a simple indicators list and with a large enough acceptance margin to accomodate moderators team without hindering quality of the moderation

## Rationale and alternatives

[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?
- Does the proposal make it easier or harder to moderate, administrate, and maintain Fediverse services?

## Prior art

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

## Unresolved questions

[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

## Future possibilities

[future-possibilities]: #future-possibilities

One extension to this proposal might be to give the possibility to communities to give out sets of rules and review labels through a proper tool.
Another might be that communities could create moderation teams to help out instances in moderating content. Whether this would go through an external tool with moderation rights on instances concerned is up to reflexion for the next proposal.
