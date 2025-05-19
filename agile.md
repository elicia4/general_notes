# Agile Product Ownership

[Agile Product Ownership in a Nutshell](https://www.youtube.com/watch?v=502ILHjX9EE)

PO - product owner.
The PO has a vision of what product they want to create, for who and to solve
what problem.

Stakeholders are people who are will use & support the product. The PO hopes
they will love the product.

The stakeholder needs and PO's ideas are expressed as user stories. E.g., if
the product was a flight booking system, people need to be able to search for a
flight

PO & stakeholders have to formulate concrete ideas. Developers (as a developer
team) build the system itself. The developer teams releases early and often,
4-6 stories a week (their capacity, the number of stories released per week).
Stories ~= story points. 

To make this work, the teams invest heavily in automated testing and continuous
integration. Every story has at least one automated acceptance test at the
feature level. Most of the code has automated unit tests.

PO & stakeholders express lots of ideas, thus generating many stories. The
influx of stories usually surpasses the amount of features a team can produce.
E.g., the weekly story input is 10 and output is 4-6. The PO decides what
features to implement on a given week. The Kanban way is to limit work in
progress (WIP). E.g, a team might decide that their WIP limit is 5. Whenever
they finish a story, they accept a new one, thus making sure the limit of 5 is
never broken.

A queue of stories is called a product backlog. The queue needs to be managed,
some stories are discarded. Therefore a PO has to say "no" often. The PO also
decides the sequencing of stories. They don't do it alone, they collaborate
with the stakeholders & the developer team to figure out what needs to be done.
Stories are sorted by value and size. There is no correlation between value and
size. The sizes and values are estimated. It's a guessing game on the PO's
part. As the times goes on, the guesses (usually) get better.

The stories are also broken down into pieces, preferably a few days of work per
story. The more clear stories are at the front of the product backlog and the
more vague ones are at the back.

Prioritizing, estimating value & size of stories, splitting is called "backlog
grooming".

Risks & uncertainty:
- business - is the right thing being built
- social - can these people build it
- technical - will it work on the platform you want to run it on
- cost & schedule - can it be done on time & can you stay on budget

From the customer value perspective:
- at first customer value increases slowly (the PO, developers & stakeholders
get used to the product and their demands). The focus is knowledge
- then it increases rapidly as everybody figure out what needs to be done. The
focus is increasing customer value
- at last, the value increases slowly again as the best features have already
been implemented
