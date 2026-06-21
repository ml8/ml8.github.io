---
title: "A Meditation on Invisible Architecture"
slug: invisible-architecture
type: post
date: 2026-6-20
draft: false
tags: ['programming', 'poetry', 'software engineering', 'feed', 'distributed systems', 'emergent behavior', 'complexity']
---

> Losing the arrogance of dominion over the poem to an invisible hand, the poet
> campaigns for a passage over which the poet has control. Yet the unstableness
> of the poem is important.
>
> -- Barbara Guest, ["Invisible
> Architecture"](https://www.poetryfoundation.org/poems/54866/invisible-architecture)

I've built my life around computer science and software.

When people talk about invisible architecture in software, they're usually
talking about processes or operations patterns that surround it, and are
rarely talking about that invisible architecture in the way that Barbara Guest
meant it.

---

I was a teenager in London during
[Meltdown](https://en.wikipedia.org/wiki/Meltdown_\(festival\)) 1997, curated by
Laurie Anderson. She had an installation piece there, something about language
and voices. I remember it was a dark space with voices coming from all
directions, snippets of language that didn't have context. Visual elements
projected on walls. One of her telephones. 

That was the first time that I saw computers/technology as tools for
things other than business or games. That there was this medium that could be
expressive and used to make art. I wanted to do this.

As the daughter of a mother who's an engineer at heart—though never finished
school—but also an artist and crafter, and of a father who is a lawyer, but
also a writer, the world has never looked one way to me.

When I got back from that trip, I got into
[demoscene](https://en.wikipedia.org/wiki/Demoscene)—an expressive programming
culture where programmers create little AV experiences, and try to eke as much
from resource-limited environments as possible in order to make intense
experiences. I loved this—it was essentially what I wanted to be doing—making
art that made itself. 

So I built my own libraries and frameworks for A/V programming, all hand-built
from the ground up in x86 assembly. Every time I do spring cleaning, I look for
those Zip disks with my backed-up code from 1999. It is painful to lose this
archive of work.

While I was teaching myself programming as a paintbrush, I was also learning
about computer science and reading widely. I got into the cyberpunk movement of
the 90s—reading Rudy Rucker, William Gibson, Paul Di Filippo, etc.—and was
spiraling out from that into the "new kind of science" that [Wolfram would write
about](https://en.wikipedia.org/wiki/A_New_Kind_of_Science) a few years later. 

The fascinating thing I found about computers at the time, especially by the
resource- and size-constrained demos that I was emulating, was the concept of
emergent behaviors and compact representations of complex systems. I wrote
programs to model [Conway’s Game of
Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)—a mathematical
"game" played on a grid of cells, each of which is either alive or dead. Cells
would come alive or die according to the number of alive neighbors they had.

From something as trivial as counting neighboring cells, infinite complexity
arises. Part of the beauty of computer science to me is that its central
theories culminate in beautiful simplicity: rules like this are enough to
simulate any mechanical system, even a computer. The building blocks of
computation are extremely simple. 

There’s something elemental about emergent complexity, and I am fascinated by
it.

This fascination is the thing that I've built my life around working with and
studying: how simple, abstract, and compact models can generate complex and
infinite patterns. 

Over the years I have drifted away from A/V and art toward infrastructure and
distributed systems engineering—the foundational lower-layer systems upon which
user-facing systems are constructed.

--- 

I build models. I build representations of ***something*** that we communicate
to one another for the purpose of reproducing that ***thing***. A model is
imperfect. It uses the medium of language—albeit formal programming languages,
themselves abstractions—to hang meaning upon.

That formality doesn't equal precision. 
There is an impedance between our languages, the models that they produce,
and the idealized thing we’re trying to capture. 

That impedance, the tension it creates, and the imperfection of our programs are
the things that I find so fascinating and alive about software engineering.

I write algorithms and programs that try to capture some process. They will
never be able to capture all behaviors that I would like them to—I can’t write
systems that can absorb any component failure or communication line cut, it’s
impossible. So I have to be a careful student of how my program flexes in the
same way that the real world space flexes—and understand where it breaks down
and fails. 

In distributed systems, algorithms expressed in our most formal models operate
on idealized models of computation. We use these to make reasoning about programs
easier, but they mean that these algorithms are not able to be implemented
directly—they are not capable of tolerating the messiness of the real world, the
things that fail, break, and go wrong.

Algorithms like this are like delicate constructions, glass bells ringing
in the dark, beautiful and faint, but too fragile to touch. 

An engineer bringing them into the real world is building scaffolding so that
they don’t shatter. Doing this requires intimacy—both with that fragile idea
and with the bright and dangerous world it will live in.

Our job is not to fall in love with our constructions, or obsess over their
mechanical fabrication, but to be the vehicle for the idea we are trying to
model and to sit attentively and lovingly in the space between the model and
the ideal.

---

As a poem needs "to loosen the armed hand" that writes it, so does software.

I love poetry. I thought that poetry would be my life and that computers would
be a hobby. I think that’s seesawed over the years, but poetry is still a big
part of my life. I think the reason that I love poetry is the same reason that I
love distributed systems—we are finding compact, minimal representations of
unbounded complexity. 

We are studying how to quantize these ideas using language so that they can be
dequantized by our readers (or by our processors).

I read a lot of poetry. I feel like it helps me maintain my plasticity. It helps
me see problems in different ways, to find the simple center of an idea, the
shoulders that it can hang from.

But, more importantly, I read poetry to learn from those that have attuned
themselves to the space of ideas and have learned how to let a poem pull itself
into being by letting it speak through them.

Poems have different resolutions of complexity—words, lines, stanzas, meter,
rhyme, etc.—and the poet has to navigate those levels of abstraction and
complexity in order to find the form for the poem. 

With software, at the lines-of-code level, we’re translating processes into
formal language, but at larger scales, we’re grouping code into components that
contain their implementation complexity behind simple interfaces—the design of
those interfaces requires navigating up and down abstraction hierarchies and **a
lot** of experimentation to get right. And often, those abstractions, like a
poet's, are for a human to experience and inhabit. 

Humans don't live in a mathematical world and don’t think mathematically. We
think in stories.

When I was at Google working on large-scale data processing systems, my team
would come together to talk about the "bug of the week"—usually a complex and
difficult to debug problem. The best talks were ones that presented the
debugging and resolution of an issue as a story. We had heroes and villains and
dragons to slay.

While a poet's invisible architecture is the poem, living in an abstract space
and eluding that direct interaction, needing someone to speak for it, engineers
are dealing with invisible architectures of the "right" models, the simple
algorithms, elegant abstractions—these sorts of beautifully precise models that
seem self-evident once they are written. 

And they require us to find them. 

Though we dress up our systems in technical syntax and mathematical notation in
order to reason about them with some common basis, we are still ultimately
trying to capture some idea that we ***live*** and ***care about*** and 
something for which formalism will _always_ be an approximation.

There are voices in the dark room that are calling to us, but they are
mysterious, faint, and much too ethereal to hang in this world alone.

A voice needs a person to listen to it. To pull it out of the dark, to hold it,
to think deeply about it—to give that idea language, and the body to carry it.
