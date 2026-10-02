---
mainfont: "Palatino"
sansfont: "Helvetica Neue"
geometry: "top=0.75in,bottom=0.6in,left=1in,right=1in"
fontsize: 11pt
linestretch: 1.03
header-includes: |
  \usepackage{microtype}
  \usepackage{newunicodechar}
  \newunicodechar{→}{\ensuremath{\rightarrow}}
  \usepackage{titlesec}
  \titleformat{\section}{\normalfont\sffamily\bfseries\Large}{}{0em}{}
  \titleformat{\subsection}{\normalfont\sffamily\bfseries\large}{}{0em}{}
  \titlespacing*{\section}{0pt}{0pt}{4pt}
  \titlespacing*{\subsection}{0pt}{9pt}{3pt}
  \usepackage{xcolor}
  \definecolor{cmtint}{RGB}{244,247,250}
  \definecolor{cmrule}{RGB}{27,111,140}
  \usepackage{mdframed}
  \mdfdefinestyle{cmquote}{linewidth=3pt,leftline=true,topline=false,bottomline=false,rightline=false,linecolor=cmrule,backgroundcolor=cmtint,innerleftmargin=10pt,innerrightmargin=8pt,innertopmargin=6pt,innerbottommargin=6pt,skipabove=7pt,skipbelow=7pt}
  \surroundwithmdframed[style=cmquote]{quote}
---

# Start Here

*The whole idea, in plain language — read this before the Guide.*

## The problem this solves

You know your subject cold. Turning what's in your head into a course someone can actually *learn* from — one that another person could pick up and teach — is a different skill, and most experts were never taught it. So we improvise: a pile of slides, notes that only make sense to us, a lot of effort that doesn't quite land.

## The one idea

**A course isn't a pile of writing. It's a short chain of decisions, made in order.** Decide who it's for and what they'll be able to *do*; pressure-test the plan against how people actually learn; put the whole thing on one page; then build one piece of it. Make the decisions first and the material almost writes itself — with AI drafting while you stay in charge and check every line.

> **Decide first → test it against how people learn → put it on one page → build one module → let AI draft, you verify.**

## Why it works

- **Decisions before production.** You never open a blank page and start writing — you decide first. Everything downstream inherits those choices, so the course holds together.
- **You direct, AI drafts, you verify.** GenAI is the fast production engine, never the author. The judgment stays yours.
- **The portability test.** You're finished when *someone else could teach your course from your materials alone.* That one test quietly forces clarity into everything.
- **Grounded, but usable.** Built on real instructional-design research — measurable goals, how people learn, accessible design — repackaged so an expert, not a professional designer, can follow it.

## What you'll do — and keep

Work the Guide top to bottom for **one** module. You'll produce, in order: a one-page **decisions doc**, measurable **objectives**, a **course blueprint** (the Master Design Document), and one complete **module** — built, and ready to teach. That first module is your template; the rest of the course is built exactly the same way.

## Then go here

1. **How to Build a Course** — the Guide, the full method step by step. Begin at *"Why I Wrote This."*
2. **Method on a Page** — a one-page quick-reference to keep beside you *once you know the method* (shorthand, not an introduction).
3. **Worked Examples** — the whole method filled in on two real courses; open one whenever a step feels abstract.

**What's in the bundle:**

- `1_Guide/` — the Guide, its blank templates, and the blank module skeleton.
- `2_Worked_Examples/` — `IntroML/` (a code course) and `Coffee/` (a non-code course): the method filled in end to end.
- `3_Pilot_Course/` — the five-session course that teaches the method to a group.

*File paths in the Guide are written from this layout. If you received the Guide on its own, the Worked Examples ship as a companion bundle — unzip it beside the Guide.*

> *The promise: follow it end to end and you'll have a course solid enough that someone else could pick it up and teach it.*
