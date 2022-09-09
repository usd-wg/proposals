# community USD proposals

Community collaboration on proposals for USD

## what is a proposal?

- a new schema, such as "Level of Detail for Games"
- an outline for a technical action, such as "Removing the boost preprocessor macros"
- a new development, such as "Evaluation of Hermite Patches"
- a discussion of scope tightening, such as "Standardizing Alembic without HDF5"

For inspiration, here are several proposals that have previously been worked through: https://graphics.pixar.com/usd/release/wp.html

## relationship to other forums

- Initial discussion and coordination of effort may occur in the wg-usd slack, or the usd-interest Google Group
- The various ASWF usd working groups are good venues for face to face discussion, presentations, and so on

## New proposals

### Be registered with EasyCLA

A CLA needs to be registered by contributors via EasyCLA, to indicate that you as a contributor are able to submit materials to this repository.

### Create an Issue for the proposal

Use the issue Proposal Template, and fill out the form.

### Submit materials for the proposal

Materials for a proposal might include white papers, diagrams, sample USD files, and pseudocode. Materials will not include code intended for submission to other projects. Materials will not include IP protected by patents. Copyright to the materials may be indicated as deemed appropriate by the author.

Fork this repo, create a directory within `proposals/` for the proposal and its materials, and a README.md, then submit a PR. The PR should reference the Issue, for tracking and conversation purposes. The README.md document may contain the proposal, or at a minimum, it should announce the contents of the proposal and how to understand the materials within the material. The README.md should also contain notes the author considers important for anyone looking at the proposal, which could include notes that a proposal has been superceded by another, that the proposal resulted in a change to another project, and so on.

A typical workflow for the proposal PR will be have some initial discussion on the PR itself, and at some point, the PR maybe landed. Further iteration of the proposal may proceed via subsequent PRs, each referencing the proposal's main issue.

### Expectations

At any point, proposal text may be used in other contexts, for example, a proposal may be referenced when writing new schemas or code for USD. Those new schemas and code might end up in their own project repositories, or submitted to another repository, such as the USD repository, as a PR.

This proposals forum is meant as an organized venue for conversation around written documents, with all the power of PRs, Issues, and Discussions. It's out of scope to declare that a proposal here will result in some other group taking action, but it's in scope for proponents of a proposal here to advocate and promote it in other venues as seems appropriate. 

The success of the forum is predicated on involvement and communication, so consider this an appeal to everyone's creativity and thoughtful consideration.

## License

The default license in this repo is currently CC0. Before this repo goes live, we anticipate switching the license to Apache 2.

## Structure of this Repository

Active proposals shall exist at the top level of the repo as siblings within the `proposals/` directory. It is expected that the README.md document in a proposal's root folder will have some indication of the purpose and history of the proposal.

## Code of Conduct

Civility, inclusiveness, friendship, and constructive collaboration shall be the hallmarks of this forum.

Thank you for your participation!
