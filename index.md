Hi, my name is Sanne Peters
and I work at BANKAI
as a Front-end Software Architect

At BANKAI Design Systems are one of our main tools for collaboration

And we collaborate a lot

- governments
- scientific institutes
- big data companies
- API developers
- freelancers
- tech companies

## Who uses Design Systems anyway?
- Designers
- Developers
- Copy Writers
- Data Scientists
- Product Owners

So how do you build something that can be used by everyone?
- Working together, through __co-ownership__
- making it __accessible__ and __maintainable__
- Allow it to grow __safely__.


## Working together

In order for it to be effective the system needs to be owned together. The best way to achieve this is to work on it together.

### Establishing a common language

Everyone uses different terms for the same things
The whole team should use the same words for the same things

Involve each other in the decision making:
- How do we name this component?
- Does this structure make sense?
- How should it work?
- Do you need this feature documented?

Share what you know about the web. So Designers can make more informed decisions
- both what's possible and what's not.
- propose to research something.
- talk about unknown web technologies (like Variable Fonts or Web Audio API)

**Don't force people** to do
what they **do not want** too.

Be forgiving


## Step 2: ~making~ __keeping__ it accessible and maintainable

### Don't re-invent the wheel.

Make it your mantra.

Use methods that are well thought out and established,
like:

- for structured version control: [__git flow__](https://nvie.com/posts/a-successful-git-branching-model/) or [__github flow__](https://guides.github.com/introduction/flow/)
- add linting (like, eslint standard or AirBNB). Stop wasting time having tabs-vs-spaces discussions or wether or not something needs an extra comma behind it.
- do __code reviews__ through __Pull/Merge Request__
- set up integration testing and end-to-end testing
- automate as much as possible, allow yourself to think less and create room for some
  ✨ creativity ✨

(maybe later, tweak it to fit your needs.)

### Define a structure for the system

## Design Tokens

We use __Design Tokens__
to define the most __basic values__

Design Tokens were defined by SalesForce as part of their
lightning design system

## organise components in a heirarchy.

A hierarchy creates structure and adds a high level meaning to each component.
needs rules,
without rules there is chaos.

As an example I gonna use Atomic Design

App                 Village
Views (pages)       Neighbourhood
layout (templates)  Street-plan
Organisms           House
Molecules           Wall
Atoms               Brick

### Composing components, not building them

You are not a mindless machine.
Or at least,
you shouldn't be.

Thinking is like, good.

So, actually, making components is a __creative process__.

> _yes, you're an artist now_

> So next time when your parents ask you "so, what do you do again?"
> You say, "I am an artist, a digital artist"

- Discuss the design with the person who made it.
- Does it contain all the info you need?
- Ask question on how it should work?
- Are animations and transitions defined. If not, should they?

Have a discussion about, using clear arguments and explain them.

Than, name your child

[cave painting of rafiki naming Simba]

> But naming things is hard 😨.
> -- 👩🏽‍💻 _every developer I've met_

Some tricks:
- Define the name rather by __what they do__ than by __how they look__
- Use simple, every day words. (remember you work in a multi-disciplinary team)
  - Accordeon --> expandable-list-layout
  - Toast --> popup-notification
- Iterate on the name, just modify it as you compose it.
- Ask a co-worker!

style: https://vuejs.org/v2/style-guide/ & https://html.spec.whatwg.org/multipage/custom-elements.html#valid-custom-element-name

_Remember the mantra!_


### Allow it to grow __safely__.

Each thing should be documented
- design tokens
- components
- utilities

The bigger a team gets the harder it is to communicate.
Document once and you will never need to explain it again.

Documentation tools: styleguidist ([React](https://react-styleguidist.js.org/) or [Vue](https://vue-styleguidist.github.io/)) and [storybook](https://storybook.js.org/)



Each functionality needs to be covered by tests

Start with manual testing scripts
translate those to code-based test
automate your tests (pre-commit or pre-merge hooks)

So summarised:

- Communicate, start talking in easy terms and be nice to people.
- Don't re-invent the wheel

A few final words

You and your team have set up this beautiful Design Systems full of guidelines and rules, and for the most part everyone likes it, because it works.

But at one point something happens people will feel constrained by the system. It might just be the very same people that helped build it.
[connect the two...]
Leave/create room for creativity

Ask me anything
(about Design Systems)
@sanstreamed (Twitter)
