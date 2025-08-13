# crucible-ci-userenvs

External userenvs used for
(crucible-ci)[https://github.com/perftool-incubator/crucible-ci] testing.

The intent of the userenvs in this repository is not that they be
novel/unique.  Rather, this repository is simply meant to serve as a
means to an end -- and that end is testing the ability to administer
"unofficial" (ie. "external") repositories and to use externally
sourced userenvs in the (crucible-ci integration
tests)[https://github.com/perftool-incubator/crucible-ci/tree/main/.github/actions/integration-tests]
action.

## Available userenvs

- [external](README.md#external)

### external

The [external](external.json) userenv is a clone of the RHUBI 10
userenv from the
(rickshaw)[https://github.com/perftool-incubator/rickshaw/blob/master/userenvs/rhubi10.json]
(Crucible)[https://github.com/perftool-incubator/crucible] subproject.
RHUBI 10 was chosen since it is very new and therefor will presumably
be active/available for a considerable amount of time.
