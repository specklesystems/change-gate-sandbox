# change-gate-sandbox

A test repo for the change review rules of the Speckle repos. Nothing here ships.

It holds what a repo under those rules holds: the two risk check workflow files,
the secret scan workflow file and a floors file. The checks themselves live in
[`specklesystems/.github`](https://github.com/specklesystems/.github) and run
here from its `main` branch.

Pull requests here are test cases. Each one says what it tests and what result
it expects.

The floors file gives every path under `yellow/` and `red/` that minimum color,
so a test pull request can ask for one by adding a file there.
