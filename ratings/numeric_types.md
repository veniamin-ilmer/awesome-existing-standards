<link rel="stylesheet" href="/default.css">

# Rating Numeric Types

## Background

I've been experimenting on surveying people for some time, and have found an important occurance:

Even the slightest difference in the options available to answer a question, strongly effects how people will answer it.

I decided to run a survey that tested this effect directly.

## Survey

I ran [this survey](https://docs.google.com/forms/d/e/1FAIpQLSfuXRf0G4lg-CaS15Krn32HOQULCLvjwfNx-7GHWgvaQ7ToQw/viewform) to see how people make decisions.

There are three candidates: Abigale, Britney, and Courtney.

The survey instructs:

* Abigale is your Best Friend.
* Britney is an acquaintance. You feel neutrally about her.
* Courtney is bad. You hate her.

The idea is that you'd rate Abigale positively, Britney neutrally, and Courtney negatively.

Each of these candidates has an equal chance to win the vote.

The survey then asks how the user would vote, given varing rating options.

## Results

I collected 308 responses.

Let me start with the simplest situation:

### Upvotes and Downvotes
The user can either "Upvote" or "Downvote" any candidate. They can also choose not to vote.

![Upvote Downvote](numeric_types/upvote_downvote.png)

Although the users were instructed that voting is optional, most of them voted for all candidates anyway. (98% answered for the positive candidate, 84% answered for the neutral candidate, 96% answered for the negative candidate).

This might have been for two reasons:

1. Although it's optional, asking someone a question may make them more likely to try to answer it anyway.
2. All of the other questions were not optional, which may have gotten the user to get used to try and answer all questions.

The most interesting result was with the Neutral candidate.

Subtracting the Positive and Negative vote, the Neutral candidate ends up with an overwhelming 54% Positive vote.

It seems people have difficulty understanding that a balanced "Neutral" vote, is still better than a "Downvote".

They end up voting the neutral candidate positively, almost to spite the Negative candidate more.

