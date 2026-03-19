---
title: "SIGCSE2026: No One’s Saying Nothing"
slug: sigcse2026
type: post
date: 2026-3-18
draft: false
tags: ['programming', 'teaching', 'ai', 'software engineering', 'feed']
---

> TL;DR: AI is reshaping how software is built, but industry is absent from
> the conversation about how we teach the next generation of engineers-—-and
> salesmanship is making it harder for educators to separate real uses of AI
> from hype. SIGCSE 2026 made clear that industry must show up, be honest about
> what AI actually solves, and help CS education shift from testing mechanical
> code production to assessing the creative, essential complexities that 
> can't be automated.

> Hit the spacebar enough and cocaine comes out / I really like this computer\!
>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\- _Dismemberment Plan, [*No One’s Saying Nothing*](https://www.youtube.com/watch?v=dbMYHbIdY6U)_

40 years ago, Fred Brooks wrote about accidental complexities and essential
complexities in software engineering, arguing that there was 
[No Silver Bullet](https://www.cs.unc.edu/techreports/86-020.pdf)
for the essential complexity, and what was true 40 years ago is still true
today.

Software engineering is hard. At its core is the construction of _complex_ and
_reliable_ systems from _simple_ and _unreliable_ components. This construction
is fraught with complexities---complexities that marketing claims AI will solve.

The reality is that generative AI and LLMs excel at solving our **accidental
complexities**: the overhead of syntax, connecting systems, aggregating
disparate data sources, etc. They do not---**and likely will never**---solve
our **essential complexities**. For nontrivial problems, _what_ to build is the
hard part, and the part that requires the computer scientist and deep computer
science thinking. Coding is just the mechanical translation of these specs and
corresponding mental models. 

**There is no silver bullet for solving the essential complexity, at least no
silver bullet that comes from the statistical correlation of symbols in
human-produced text.**

This distinction was missing from SIGCSE2026.

## SIGCSE 2026 was bad

> I have to admit that I wrote most of this article while the Saturday morning
> sessions were happening. I missed [Titus Winters’s EXCELLENT
> keynote](https://www.youtube.com/watch?v=6Fyjf3gFjUk) that reinforces most
> of what I've written here.

In fact, it was the worst SIGCSE that I have been to. I didn’t come away from
SIGCSE with a whole lot to think about, other than this article. I attended (or
heard reports from friends about) many, many, many sessions about AI, but I
didn't hear any particularly good talks, other than a few that were in
partnership with industry.

Why?


## A crisis of ambiguity 

Generally, the EDU community does not know how to
think about or how to respond to generative AI. On the one hand, this feels
natural---we're sharing how we're figuring things out and evolving a shared
understanding and future. However, the technology is still very early, and it
seems like EDU is finding it very difficult to differentiate signal from
noise.

This is compounded by the fact that **we in industry** are generally having
difficulty with this differentiation. Conversations about AI have conflated two very different things:

* The very powerful uses within the SDLC: Coding agents and modern models are
  revolutionizing software construction---in every phase of the lifecycle. Outside
  of code generation, other uses are arguably more impactful on how we will do
  our jobs in the future; usages that connect systems, synthesize information
  from disparate sources, or provide adaptive natural interfaces to ill-defined
  or missing API surfaces. These are the killer use cases for me and where I
  have found benefit in my day-to-day.  

* The very loud and very chaotic hype surrounding AI and AI investment, and
  corresponding AI-infusion and sales of AI-infused products. Conversations
  around eliminating white collar entry-level jobs, automating professions,
  eliminating creatives, "agentic employees," etc. are hyperbolic, unrealistic,
  and driving an economic bubble and an unrealistic, inhumane, and fundamentally
  capitalist view of the future.

The real benefits of AI---the actual usages that are economically and
environmentally sustainable, have provable positive impact, and provide real
efficiency wins---are drowned in a sea of capitalistic idealism that is
fundamentally alienating to a humanist perspective of the world.

![Hype vs Reality](/assets/hype-cycle.png)

Unfortunately, though, I feel like there is very little separation between these
conversations, and **industry is the culprit**.

Industry is selling solutions to __essential complexity__, but is only
realistically solving the __accidental complexities__. This is not to say that
things aren't changing, though.

We are at a tooling inflection point. The mechanical day-to-day of software
construction is changing and will continue to change dramatically.
There are real, impactful tools being developed that will change software
forever. 

Generally, most software engineers that I know have begun to understand this and
embrace generative AI. However, they are embracing generative AI where it makes
them more efficient, reduces cognitive load, or makes automation a much lower
investment. With agentic coding and construction of "[disposable
software](https://a16z.com/disposable-software/)," automation is now often worth
the effort of describing the problem and desired scripts/tools to an agent.

This is entirely in contrast to how most AI companies have been positioning
their products: as silver bullets for efficiency, allowing CTOs and CEOs to
create redundancy in their most specialized roles and replace expensive people
with automation. This sort of "disposable" approach to software is killing
reliability globally.

__Reliable systems are not vibe coded, nor are they
disposable.__

We see this now with Amazon, which [reportedly having a reliability
crisis brought on by generative AI](https://thenewstack.io/amazon-ai-assisted-errors/). 

## A crisis of identity

At the heart of this disconnect in education is a fundamental misunderstanding
of our identity as computer scientists and software engineers. 

Computer science has long been considered a branch of applied mathematics, a
specialization in the subdiscipline of information processes. While true, this
disciplinary identity is disconnected from the **work** of most computer
scientists. 

**We do not act as mathematicians studying processes in isolation; we act upon
the world through the construction of real-world systems. _Building software
is a creative act._**

As a practitioner, the challenge (and excitement) of my work is in my creative
application of critical, structured thinking to ambiguous and informally
specified problems. Our first act is one of refinement: of formalizing a
problem into a precise definition.  Our second act is to translate this precise
definition into a software system.

Computer scientists have often noted this. 50 years ago Dijkstra [made the
statement](https://www.cs.utexas.edu/~EWD/transcriptions/EWD08xx/EWD896.html)
that computer science is no more about computers than astronomy is about
telescopes. 15 years ago Jeanette Wing called back to Dijkstra in her
description of and advocacy of [computational
thinking](https://www.cs.princeton.edu/~chazelle/courses/BIB/jeannette-wing.pdf).
CS Principles and other "unplugged" curricula have continued this thread of
thought.

However, changes in undergraduate education have lagged behind.  This lag is
rooted in our identities. We consider ourselves, often, as applied
mathematicians, or at least "scientists" or "engineers."

This sort of self-characterization breeds an obsession with formality,
precision, and objective assessment---and an obsession with programming as the
fundamental skill we teach our students. Programming is a process of
translation, and the _most_ mechanical work that we do---perhaps the _most_
accidental complexity.

If we are honest with ourselves about our work---either as researchers or as
practitioners---_we are creatives_. We are not so different from designers,
artists, or marketers---those of our peers whose job is to translate abstract
concepts and objectives into novel and strategic artifacts that **interpret**
and **communicate** these objectives.  This translation is _not_ mechanical and
requires expertise, judgment, _and_ creativity. This is the _essential_
complexity of our work.

## Embracing a creative identity

Why are student assignments so easy with AI?
It's our fault, we've trivialized them, and we assess the wrong things. We do
the hard work for them: we generate the precise specification and assess only
the mechanical translation. **This is the exact skill that AI does best!**

What we really want to do is assess the problem-solving skills: those skills of
refinement and specification. We want to see the ideas behind the algorithm,
but our assignments are so scaffolded so as to constrain creativity in the
design of that algorithm, making it an almost-meaningless exercise.

![Math vs Art](/assets/math-art.png)

What does it look like to shift the way that we think about what we want to
assess? This looks like loosening our focus on the medium of
programming and more on the **process skills** that undergird programming.
Spending more time talking about specification and refinement, more time talking
about type theory, more time talking about semantic execution models, and *more
time talking*.

Our process skills are not mechanical or objective, they are creative and
subjective. We can shift our assessment left in the development process, we can
give students more freedom in their specifications, and more freedom in the
design of the objects that they create.

This shift in identity means a shift in how we scale ourselves. Art faculty
limit class sizes, embrace peer review, and critique. We will need to do so as
well. **We need to be closer to our students' minds, not the mathematical
objects that they produce**. We need to understand how they approach the
essential ideas of the discipline, not how they produce artifacts and how well
they tackle the accidental complexity of that production.

## Industry needs to be more present

Our companies are selling AI to
the tune of billions of new revenue generated overnight. The economic landscape
of the United States is AI-centric, and all-in on an unproven technology in the
general case. In industry, **we need to be honest with our academic peers**. We
have to be very clear about what is working for us **and what isn't**. Our
salesmanship harms our academic peers' ability to reason clearly about AI.

In fact, we should be helping our academic peers shift their thinking toward
what we are valuing in industry: a strong foundation in the fundamentals, the
people and communication skills necessary to interface with others and teams,
and clear structured thinking about tradeoffs and strategy.

And we should be making it clear where AI is helpful and where it isn't. We are
the ones who are revolutionizing the SDLC. Let's bring them along with us, but
bring them along where AI is working for us. Right now they are figuring it out
for themselves and are flailing. The only AI-related talks that I heard that
were any good at SIGCSE came out of industry partnerships. We need to do more
here globally across the industry. 

Where were Anthropic and Claude at SIGCSE? Where was GitHub beyond our education
team? Where was Cursor? **These tools want to revolutionize software
construction without meaningfully engaging with the source of our students’
intellectual development as computer scientists**.

**Industry is the hinge, and it needs to be more present.**

## Back to the essence

Central to Brooks's thesis is that the essential complexities of software are
what to build, how, and by whom. These are the problems of design and creative
acts. As Brooks argues in his closing, constructing software is about people.
Growing those people into a AI-enabled future requires collaboration.

Industry needs to be in a tighter loop here and to support EDU in teaching
generative AI for software engineering. The distinction between real use and
salesmanship has to be clear to educators _and_ to students. Industry must
partner outside of large research institutions and researchers that advance
industry state-of-the-art and engage with people teaching computer science to
most students in the US. Industry needs to be in the conversation, or our talent
pools will age out.

