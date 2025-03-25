# Richard Ng <!-- omit in toc -->

In *general*, the best place to find out more about me is my [personal website](https://richard.ng/), which I intend to keep updated as a general source-of-truth.

Here, I'll chuck in some tech-focused open-source and conference attendance.

---

## *Tackling the toppling tech talent pyramid*
LeadDev Berlin 2022

![LeadDev talk](img/leaddev-berlin-2022-hero.png)

> **Tackling the toppling tech talent pyramid: a radical challenge to building diverse teams**
> 
> In this talk, Richard will share insights, data and tips from his experiences in tech talent development within underserved communities - including an industry-wide call-to-arms alongside practical small steps for individual engineering leaders.

***[Watch the talk](https://leaddev.com/hiring/tackling-toppling-tech-talent-pyramid-radical-challenge-building-diverse-teams-0)***

## *Riduce: get rid of your reducer boilerplate!*
React Online Global Summit 2020

![Riduce talk](img/react-global-2020-still.png)

**[Riduce](https://github.com/richardcrng/riduce)** - formerly **[redux-leaves](https://github.com/richardcrng/redux-leaves)** - is an open-source library that replaces reducer boilerplate with two lines of code.

*(Or, it gets **rid** of reducer boilerplate - inspiration for the name **Riducer**, as well as an intent to decouple it in expected use from Redux)*

Whether you're using `useReducer` or Redux, reducer boilerplate is tedious to learn, setup and maintain.

What if type-safe state management was quicker, easier and simpler?

[Riduce](https://github.com/richardcrng/riduce) is a library written to be:

- Strongly-typed, so your state stays predictable
- Trivial to scale as your state grows more complex
- Zero hassle, with just two lines of code...

... and one of the 2 lines to setup is an import.

```js
import riduce from 'riduce'

const [reducer, actions] = riduce(initialState)
```

That's it! Now you've got a type-safe reducer and arbitrary actions, with zero hassle.

***[Watch the talk](https://richardng.notion.site/Watch-the-talk-eb9283c1c51c4aa1881c8354625a273c) | [Read the docs](https://richardng.notion.site/richardng/Riduce-3cb629505a8d49279fe8848e1d564deb)***
