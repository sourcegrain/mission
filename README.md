# SourceGrain

SourceGrain will make open-source software projects financially sustainable by
letting them issue their own project-specific cryptoassets, called *grain*.

## Properties of Grain

- Grain is always project-specific. For example, "SourceCred grain" and "IPFS
  grain" would be wholly different assets.
- Every week, new grain is created, or "harvested" by the project.
- Most of the harvested grain goes to people that have directly worked on the
  project.
- A fraction of the harvested grain flows to those who hold grain in the
  project's dependencies.
  - For example, if you have grain in Python, then you would continually earn a
    small share of NumPy's grain, and so forth.
- Grain is a freely transferrable and exchangeable asset. Most likely it will
  be implemented as an ERC20 token, meaning that it can be bought or sold
  using the [0x Protocol].

## How Grain is Acquired

There are three ways to acquire grain in a project:

1. Contribute to the project directly.
2. Buy grain from someone else. 
3. Own grain in the project's dependencies.

## Grain as Proof of Support

In all of these cases, owning grain means that you've supported the project in some way:

1. If you've worked on it directly, it's obvious that you've supported it.
2. If you've bought grain in the project, that means, transitively, that you've
   paid money to someone that supported the project.
3. If you own grain in a project's dependencies, then by supporting the
   projects' dependencies you've indirectly supported the project itself.

Therefore, grain is a *proof of support* for a project. 

## Rewards for Grainholders

Projects could choose to reward their supporters, by giving prioritized attention to
those with a lot of grain. For example, projects could reward grainholders by 
prioritizing their feature requests and bugs, or giving them a say in project governance.
Crypto projects could even give tokens directly to grainholders.

Rewarding grainholders would be in the best interest of the project: if owning
grain confers valuable rewards or access, then more people will want to buy it,
increasing the price. This will mean a greater reward for the project's
developers, meaning more people will work on improving the project itself. The
result will be a positive economic feedback cycle.

## SourceGrain as Economic Scaffolding

Thus, grain will serve a lot of economic functions for open-source projects:

1. It provides a new way to support an open-source project: by buying its
   grain.
2. It provides a way for contributors to earn money for their work: selling the
   grain they earn for contributing to the project.
3. It provides funding for widely-depended on open-source infrastructure: such
   projects will earn grain in all of their many dependencies.
4. It lets users of a project who need prioritized support or access to acquire
   it, by paying the developers.
5. It provides rewards for early investors in successful projects, both via
   grain appreciation, and via dividends from dependent projects.

We think of SourceGrain as producing general-purpose economic infrastructure
for open-source projects. 

## Current Status

The SourceGrain project is still in extremely early stages.
Development has not yet started.

We believe that before we can responsibly start work on SourceGrain, we need a
robust, transparent, and gaming-resistant way to attribute credit in
open-source projects. If we can fairly assess which contributors are providing
value to a project, then we can distribute the grain in a way that is fair,
and incentivizes making meaningful contributions.

Conversely, if grain were distributed based on a bad metric like number of
commits or number of lines of code, SourceGrain would incentivize people to
game the system rather than meaningfully help development.

For that reason, we're focusing our efforts first on building [SourceCred], an
open-source credit attribution system. Once SourceCred is ready, we'll start
building out SourceGrain, starting by issuing grain for SourceCred and
SourceGrain themselves.

## Getting Involved

SourceGrain is being developed by the same team that's working on SourceCred.
If you want to get involved in SourceGrain, or learn more about it, the best
way is to join the SourceCred community. You can find us [on Discord] and
[on GitHub].

[SourceCred]: https://sourcecred.io
[0x Protocol]: https://0xproject.com/
[on Discord]: https://sourcecred.io/discord-invite
[on GitHub]: https://github.com/sourcecred/mission
