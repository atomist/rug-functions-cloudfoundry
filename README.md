# Atomist 'rug-functions-cloudfoundry'

[![Build Status](https://travis-ci.org/atomist/rug-functions-cloudfoundry.svg?branch=master)](https://travis-ci.org/atomist/rug-functions-cloudfoundry)

Rug Functions for CloudFoundry.

## Support

General support questions should be discussed in the `#support`
channel on our community Slack team
at [atomist-community.slack.com][slack].

If you find a problem, please create an [issue][].

[issue]: https://github.com/atomist/rug-functions-github/issues

## Developing

To build and test this project:

```
$ mvn test
```

### Updating rug dependency

To update the rug dependency, change `rug.version` in the pom.xml.

### Releasing

To create a new release of the project, simply push a tag of the form
`M.N.P` where `M`, `N`, and `P` are integers that form the next
appropriate [semantic version][semver] for release.  For example:

```sh
$ git tag -a 1.2.3
```

The Travis CI build (see badge at the top of this page) will
automatically create a GitHub release using the tag name for the
release and the comment provided on the annotated tag as the contents
of the release notes.  It will also automatically upload the needed
artifacts.

[semver]: http://semver.org

---
Created by [Atomist][atomist].
Need Help?  [Join our Slack team][slack].

[atomist]: https://www.atomist.com/
[slack]: https://join.atomist.com/
