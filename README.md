# Lilypond Package Template

This is a basic lilypond package template, for use with [lyp](https://github.com/noteflakes/lyp), the lilypnod package manager.

## Creating a lilypond package

- Fork this repository.
- Edit <code>package.ly</code>, add more files if desired.
- Version your package by adding git tags. Version tags can be optionally prefixed with <code>v</code> (for example <code>v0.2</code>). Versions should follow the rules of [semantic versioning](http://semver.org/).
- Commit and push it to github or another website of your choosing. Don't forgot to push your tags (<code>git push --tags</code>).
- Optional: add your package to the [lyp package index](https://github.com/noteflakes/lyp-index).

## Rules for writing a package

1. The package should include a <code>package.ly</code> file in its root directory. This is the entry point for the package.
2. Additional <code>.ly</code> files can be included using relative <code>\include</code>s.
3. Transitive dependencies are defined using <code>\require</code>.
