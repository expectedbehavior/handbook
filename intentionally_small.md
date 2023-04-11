Let me start by introducing an idea.

# The design of a company defines the work it produces.
In 1968 Melvin Conway published a paper titled ["How Do Committees Invent?"](http://www.melconway.com/Home/Committees_Paper.html). I would summarize it as a paper considering what it means to make things in a world where most meaningful things are made by groups of people instead of individuals. It's a quick read, but here's the thesis

> Any organization that designs a system (defined more broadly here than just information systems) will inevitably produce a design whose structure is a copy of the organization's communication structure. 

Improvement requires iteration and, if you're making something with other people, iteration requires communication. The harder it is for any two people to communicate, the less likely they are to do it. Less communication means less iteration means less improvement. 

As an organization grows it becomes impractical, then impossible, for everyone to be able to communicate with everyone. If it grows enough it becomes impractical, then impossible, for every team at a company to be able to communicate with every other team. The org chart of a company is usually a pretty good guide for how difficult it will be for one person or team to communicate with another. 

I found a good example of how the org chart defines the work produced while integrating AWS Cloudwatch into Instrumental. Cloudwatch is the built-in application monitoring product for all AWS services. The Cloudwatch team makes sure their service works and provides documentation for other AWS teams (e.g. EC2, EKS, etc), but it's up to the other teams to decide what metrics to provide through Cloudwatch and how to document those metrics. Each team had different interpretations of what kinds of metrics should be provided and what information should be provided about those metrics in the documentation. The result is wildly inconsistent documentation that's well below the quality level of the work that doesn't cross team boundaries.

# Expected Behavior chooses to be small.
When we started Expected Behavior, there are things we wanted to achieve. We wanted everyone [to understand the decisions at the company and believe in what they were working on](agree_to_agree.md). We wanted to respect that [everyone's best work environment is different and that the best will change over time](flexibility.md). We wanted everyone to be [free to use their own judgement](guidelines_over_brightlines). We wanted to care about and act on the specific happiness of everyone in the company.

Those things aren't possible at big companies. The cost of communication and the rate of turnover become problems that demand different solutions.

We made the decision to never have more than 10 people and we've built the business around that decision. That means choosing businesses where agility and superior communication produce outsized results.

Here's an example. DocRaptor has a reputation for providing absolutely first rate support, including consistently providing direct access to the people writing the code under question whenever necessary. We can do that because we're a small team. The person fielding the question either knows the answer or can immediately and directly talk to the person that knows the answer. It's a zero or one step process, so it's much cheaper for us to provide excellent service to DocRaptor customers than it would be for a larger company.

# If Expected Behavior limits hiring, how does it grow?
In addition to focusing on businesses that play to the strengths of businesses our size, we're experts at automation. The point of software is to create leverage so fewer people can do more things faster. We use software where other companies use people. You can help us hit our growth targets by automating your current job. If you manage to completely eliminate your job, we'll find you something else fun to do. If you eliminate all of our jobs, we'll have a statue made in your honor and start working on a post-scarcity economy. There are no penalties at Expected Behavior for making things better or faster.







