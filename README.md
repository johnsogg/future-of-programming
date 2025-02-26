# The Future of Programming? - Week by week

This is a week-by-week rundown of what we're doing. Given the experimental
nature of the class this will be made as we go.

[Looking for the syllabus?](SYLLABUS.md)

## Jan 13

1. [Make a journal (a Google slides deck) in our shared
   drive](https://drive.google.com/drive/folders/1ffZHWLzqzBFL4z_9rktCp_hEKaNoXjpI?usp=drive_link).
   You'll need permission. See the section in the syllabus on 'our collective
   journals'.
2. If you're not already set up with a development environment, do that. If you
   need help, I've made a few [videos on getting set up with a Typescript
   stack](https://www.youtube.com/watch?v=f91OdNKQ1SE&list=PLAuBm-v5PQFd0yCKW7rJ4_CHFbBdBdie0).
3. In class, we will do a little exercise to see what is possible. We'll show
   how easy it is to work a data structures homework assignment without actually
   using your brain, and then you'll have a chance to do it as well. It will use
   this [linked list
   repository](https://github.com/johnsogg/typescript-linked-lists).
4. For next week, use AI tools to see how far you can get solving my [Binary
   Search Tree homework assignment](https://github.com/johnsogg/bst) for the
   other class I'm teaching this semester. Try different approaches: in-editor
   plugins like [Copilot](https://github.com/features/copilot) or the
   [Cursor](https://www.cursor.com/) or [Windsurf](https://codeium.com/windsurf)
   AI editors, or a [groq.com](https://groq.com) back-and-forth...
5. If the binary search tree thing went quickly, here's an open-ended,
   under-specified prompt: create an interactive application with colored balls
   moving around on the screen, bouncing off walls and each other. Any
   language/framework is OK.

If you want inspiration for tools to try out, here is a [good blog post from a
non-developer's perspective on build products with
AI](https://www.lennysnewsletter.com/p/a-guide-to-ai-prototyping-for-product).

## Jan 20: No class

MLK day!

## Jan 27

1. We will talk about how the Binary Search Tree and Bouncing Balls exercise
   went. Will pick a few people to take turns leading discussion based on your
   journal slides.
2. Friendly request regarding slides: we might present your slides in class so
   be sure they are legible in the back of the room. Big font, etc. Also, if
   your slides involve other resources be sure they are accessible to everyone
   without needing to request permission.

In class:

1. `N` show and tells for the first half of class before breaking. Remember to
   tell the story in a way everyone can understand, and slow down your live
   programming to give people a chance to absorb it.
2. After break we will do an exercise with a partner. Two options:
   1. one of you write a server, the other writes a client. They should
      communicate using a shared API. The server and client should be written in
      different languages. The overall system can be whatever you like: a game,
      a restaurant inventory system, an e-commerce thing, whatever.
   2. (intentionally hard) Programming in English: writing nothing but English
      prose, write a simplified clone of your favorite retro video game. This
      can include prose descriptions of image assets, sounds, interaction
      design, data structures, input controls, etc.
3. For homework, either
   1. Do the in-class exercise that you didn't do. _Write down what you intend
      to do before you start._ This is so you can determine if you achieved your
      goal, or if you just floated with the wind and happened to make a cool
      thing. Also, wrap it up with some level of polish so it is coherently
      presentable.
   2. Or, read the [DeepSeek R1 paper](https://arxiv.org/abs/2501.12948). Either
      way, be prepared to present/discuss it next time.

## Feb 3

1. Overview of 3-week idea (see below). First thing to do is divide into three
   groups, and group 1 will pitch an idea at the break.
2. More show & tell:
   1. Client/Server and Retro Game mini-projects
   2. R1 paper
3. After break: We've done the LLM-as-prototyping-tool enough, and I think we
   all understand roughly how that works for one-off hacks. But we have not
   explored how LLMs can support _ongoing_ work over time in a _collaborative_
   context. So: We will spend the next three weeks in small groups building a
   product to spec using LLMs.
   1. Each person from group 1 will pitch a product idea.
   2. Then we will open the floor to chaos - go talk to people who pitched, pick
      a project to work on, and form a team.
   3. Teams must be between 3 and 5 people. Groups of 6 will break into two
      teams. [Teams are listed here on the pitch summary
      post](https://github.com/johnsogg/future-of-programming/discussions/5).
   4. Sponsors are _not allowed to work their own product pitch_. A sponsor's
      role is only to determine if the group(s) working on the product are
      meeting their spec.
   5. Speaking of spec: sponsors will formalize their design brief in a discussion forum post. They are:
      1. [Caloric and Nutrient Count App](https://github.com/johnsogg/future-of-programming/discussions/10)
      2. [Coherent Calendar – Product Requirements Document](https://github.com/johnsogg/future-of-programming/discussions/9)
      3. [Duolingo for code](https://github.com/johnsogg/future-of-programming/discussions/8)
      4. [Ocean Geographical Map Specification](https://github.com/johnsogg/future-of-programming/discussions/7)
      5. [Spaced Repetition Specification](https://github.com/johnsogg/future-of-programming/discussions/6)
4. Next week we will get an update from groups on how LLMs work in a
   collaborative context (since not enough time has passed to look at the
   _ongoing_ part of the effort).

## Feb 24

1. Discuss the state of the class, what we want to get out of this, what we want
   to accomplish/produce.
2. This is the end of the three week projects! Each group should be able to show
   some polish and be able to talk about the collaboration and maintenance of an
   LLM-driven effort.
3. Thank you to the people who have made slides easier to read by including
   dates or week numbers.

## March 3 (and format for beyond)

**Project work:** In preparation for Monday (March 3) discuss with your team
which other project you want to work on. Then work on that project, but not as a
group, but individually. The idea here is that you'll still have comrades who
are thinking about the same problems, and you can bounce ideas off of them, but
no longer need to work on the same codebase. You don't need to get started just
yet, though. Consider this week to be a breather.

**Discussion topic & Tiny Ted Talks:** As discussed in class on 2/24, we're
going to format class time around having a topic for discussion, with a few
"tiny Ted talks" to kick things off. Here are the general topics, along with
specific questions:

- **Technical**
  - How are LLMs benchmarked? E.g. math vs. literature vs. code?
  - How to persist "rules" for LLMs such as PRDs, chat context, project
    structure, flat files and editor rules?
  - Productivity tricks. Examples: ask LLM to summarize a codebase to make it
    smarter, or how to use/ignore LLM suggestions to improve code, or how to
    win the battle with the LLM when it gets overly zealous?
- **Social/Process**
  - `{1, n} {programmer, product owner, other} + {solo, shared} LLM = ??` It is
    possible that a single person with an LLM can do things that would take a
    multi-skilled team to do. How might we restructure the process to make
    better use of LLMs, instead of just adding LLMs to the process we've grown
    accustomed to?
  - Does the effective LLM approach depend on if the work is a program vs.
    system or a prototype vs ongoing product?
  - "Old school" process involved lots of small granular edits on bug fixes &
    features. Is this still apt with LLMs? Or is a "big bang" approach of large
    one-shot changes better?
  - How can we determine if LLM produced code _works_ (e.g. does it have bugs,
    does it fit the spec, is it maintainable, malleable, understandable, etc).
  - For an LLM software project, how can we encode the desired "road rules" for
    the process, such as what one team proposed: (1) Use a common Docker
    container, (2) use `.gitignore` as a sort of file mask to prevent unwanted
    LLM changes from getting committed, and (3) conform to a specific external
    setup involving database/API keys/etc.
- **Teaching/Learning**
  - How to teach/learn from an LLM, solo vs. team.
  - Should we teach/learn to code like we did 20 years ago? If not, what is a
    good modern approach that includes AI?

2.  Here is a [sign-up spreadsheet for Tiny Ted
    Talks](https://docs.google.com/spreadsheets/d/18YlnkrmAXnMzyevi9m4HwRhNSpL6NuYKUuGMf3d6gXM/edit?usp=sharing).
    Each week we need 3–4 people to give a talk. They should be concise and
    reasonably rehearsed. Plan to talk for <= 7 minutes with <= 5 minutes of
    Q&A. These talks will take the first half of class.

3.  The second half of class will be to have a wider discussion on the same
    general topic as the tiny Ted talks.
