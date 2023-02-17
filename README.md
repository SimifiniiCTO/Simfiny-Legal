# simfiny's Legal Documents

This repository contains the legal documents relevant or included in our application. All changes to our documents will
be reflected here first-and-foremost.

## Commit Formats.

Commits made to this repository should follow the conventional commits format.

Changes to a document should be made as small as possible, and should be easily summarized in a commit message. This
makes it far easier to represent the changes made to any documents in the change log of the repository. As well as
simplifies presenting what has changed to user's of simfiny in an easy-to-understand way.

Changes to documents should use the `change` commit type, with the document noted in the commit. For example:
`change(eula): ...` A `change` commit should only ever affect a single document.

All change commits should also have a longer more detailed commit message explaining the why's, what's or any other
detail about the reasoning for the change.

Commits that do not impact the document's definition itself can be `chore` commits, and commits that fix an error in a
document (of any sort) but still do not change the definition of a document should be `fix` commits with the document in
the message. Like this; `fix(eula): ...`
