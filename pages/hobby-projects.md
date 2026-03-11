---
title: Hobby Projects
slug: projects
type: default
ordering: 90
---

A selection of some simple hobby projects that have fun experiences for me, or
might be useful for others poking around in similar areas. Most of this is
nonserious, for my own enjoyment/entertainment, or for exploring new
technologies. I don't expect these to be production-quality or employ novel
algorithms (or even be novel systems). My goal with these is to do fun, simple
things that I find useful. I am trying to share more of this work, and will try
to keep this updated.

My professional work is available in my CV.

- [altex](https://github.com/ml8/altex): A tool for post-processing
  LaTeX-generated PDFs to add accessibility structure, including alt text and
  natural language math text-to-speech. Accessibility tooling for LaTeX is
  surprisingly sparse. Live at [altex.ml8.sh](https://altex.ml8.sh).
- [3x3 Macropad](https://github.com/ml8/3x3): A 3x3 macropad with tooling for
  custom keymaps using qmk and a tool for programming the built-in OLED. One of
  the few examples of using the qmk USB HID and qmk EEPROM features that I was
  able to find.
- [sg](https://github.com/ml8/sg): A bare-bones static site generator in Go.
  It's what generates this site. I wrote a little about why I do these sorts of
  projects [here](/hobby-projects/resting-with-code).
- [tinyr](https://github.com/ml8/tinyr): A poorly-written URL shortener in Go
  with support for multiple storage backends, OIDC authentication, and GCP
  deployment via Helm and Terraform. Simple enough to be a sketch, complex
  enough to touch a lot of infrastructure. Live at [tinyr.us](https://tinyr.us).
- [Skate Dryer](https://github.com/ml8/attiny85-skate-dryer): A toy skate
  dryer using an ATtiny85 microcontroller to run a fan on a timer. Press a
  button a few times to set how long it runs. Not exactly cutting-edge embedded
  systems, but it dries my skates.
- [Rhodes CS JupyterHub](https://github.com/Rhodes-CS-Department/jupyterhub-deployment):
  A bespoke JupyterHub environment on GCP/Kubernetes for students learning
  Python at Rhodes College, along with a set of [custom
  libraries](https://github.com/Rhodes-CS-Department/comp141-libraries) for the
  introductory CS course. This became the standard platform for how the course
  is delivered across 6+ sections per year by multiple faculty.
- [6502 Computer](https://github.com/ml8/6502): Assembly source and tooling for
  a hand-designed 6502-based computer architecture with EEPROM, RAM, I/O via a
  65c22 VIA, an LCD, and a serial interface. Very much a work in progress---a
  partially-built project that was moving toward being integrated into my
  [COMP251 course](https://comp251.github.io) at Rhodes, but ultimately was
  shelved as a I left teaching.
- [Slack Queue](https://github.com/ml8/slack-queue): A Slack bot for managing
  per-channel queues. Users can enqueue themselves, administrators can manage
  the queue. I developed this in 2020 as [Rhodes
  College Computer Science](https://www.cs.rhodes.edu) transitioned to remote
  learning, and was used for our tutoring program for a few years. I planned for
  the project to be maintained by students.

