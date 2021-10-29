# SiliconCompiler RFCs

Changes that break API incompatibility and changes that are fundamental enough
to necessitate anaytical discussion before implementation work begins should
be submitted through this repository as an "RFC" (request for comment).
The RFC process is literally as old as the internet itself, getting its start
through the [ARPANET program](https://en.wikipedia.org/wiki/Request_for_Comments).

An RFC documents proposes a new feature to the developer community. The RFC should include
a cleare technical specification and a compelling rationale.


## Do I need to submitt an RFC?

RFC:
  * Any functional change to the schema (ie. excluding documentation)
  * Any change that breaks compatility (removing features, semantic, syntax changes)
  * Any feature addition visible to SC users

No RFC:
  * Changes that are invisible to SC users (refactoring, reorg)
  * Qualitative changes (performance, logging, warning messages)
  * Bug fixes

 Fore information about how to submit a standard PR, see the [CONTRIBUTING.MD](https://github.com/siliconcompiler/siliconcompiler/blob/main/CONTRIBUTING.md) in the SiliconCompiler repository.

## RFC process

The workflow for approval and integration process for an RFC is as follows:

1. Fork the RFC repo http://github.com/siliconcompiler/rfcs
2. Copy `0000-template.md` to `text/0000-my-feature.md` (where
'my-feature' is descriptive. Don't assign an RFC number yet).
3. Fill in the RFC. Put care into the details: **RFCs that do not
present convincing motivation, demonstrate understanding of the
impact of the design, or are disingenuous about the drawbacks or
alternatives tend to be poorly-received**.
4. Submit a pull request. As a pull request the RFC will receive design
feedback from the larger community, and the author should be prepared
to revise it in response.
5. Build consensus and integrate feedback. RFCs that have broad support
are much more likely to make progress than those that don't receive any
comments.
6. The SiliconCompiler core team will decide whether the RFC is a candidate for inclusion and/or further drive discussion/changes.
7. An RFC may be rejected by the team after public discussion has settled
and comments have been made summarizing the rationale for rejection. A member of
the team should then close the RFCs associated pull request.
8. If accepeted, a team member will merge the RFCs associated pull request,
at which point the RFC will become 'active'.
9. Once an RFC becomes active, then authors may implement it and submit the
feature as a pull request to the SiliconCompiler repo. Becoming 'active' is not a rubber
stamp, and in particular still does not mean the feature will ultimately
be merged; it does mean that the core team has agreed to it in principle
and are amenable to merging it.
10. After the RFC feature has been successfully integrated through a PR, it becomes
an officially supported feature of the SiliconCompiler project.


## Inspiration

SiliconCompiler owes its inspiration to the Python and Rust RFC processes:

[Python PEP process]: https://www.python.org/dev/peps/pep-0001
[Rust RFC process]: https://github.com/rust-lang/rfcs
