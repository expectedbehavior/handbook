The number of employees at a company affects a lot of things. Some of them are obvious, like how easy it is to know all the people at the place you work or how much access you're likely to have to the management of the company. Some are less obvious, like how it changes the kind of work a company is capable of doing.

When we started Expected Behavior we made the decision to never have more than 10 people and we've built a lot of the business around that decision.

# What does company size have to do with the kind of work a company is capable of?
In 1968 Melvin Conway published a paper titled ["How Do Committees Invent?"](http://www.melconway.com/Home/Committees_Paper.html). I would summarize it as a paper considering what it means to make things in a world where most meaningful things are made by groups of people instead of individuals. It's a quick read, but here's the thesis

> Any organization that designs a system (defined more broadly here than just information systems) will inevitably produce a design whose structure is a copy of the organization's communication structure. 

Improvement requires iteration and, if you're making something with other people, iteration requires communication. The harder it is for any two people to communicate, the less likely they are to do it. Less communication means less iteration means less improvement. 

As an organization grows it becomes impractical, then impossible, for everyone to be able to communicate with everyone. If it grows enough it becomes impractical, then impossible, for every team at a company to be able to communicate with every other team. The org chart of a company is usually a pretty good guide for how difficult it will be for one person or team to communicate with another. 

While working on the Cloudwatch integration for Instrumental, I found a good example of how the org chart defines the work produced. Cloudwatch is the built-in application monitoring product for all AWS services. The Cloudwatch team makes sure their service works and provides documentation for other AWS teams (e.g. EC2, EKS, etc), but it's up to the other teams to decide what metrics to provide through Cloudwatch and how to document those metrics. Each team had different interpretations of what kinds of metrics should be provided and what information should be provided about those metrics in the documentation. The result is wildly inconsistent documentation that's well below the quality level of the work that doesn't cross team boundaries.

# Ok, I see how getting big creates tradeoffs. What kind of work benefits from staying small?
Anywhere rapid communication creates significant business value. 

Here's an example. DocRaptor has a reputation for providing absolutely first rate support, including consistently providing direct access to the people writing the code under question whenever that's valuable. We can do that because we're a small team. The person fielding the question either knows the answer or can immediately and directly talk to the person that knows the answer. It's a zero or one step process, so it's much cheaper for us to provide excellent service to DocRaptor customers than it would be for a larger company.

# How else does Expected Behavior get value from staying small?
It's easier to care about and act on the specific happiness of everyone in the company when there are few people in the company. 

It's easier to know everyone you work with when you don't work with many people.
It's easier to communicate with people you know well.
More communication happens when communication is easy.














