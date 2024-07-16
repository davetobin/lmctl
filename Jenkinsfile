#!/usr/bin/env groovy

String tarquinBranch = "CPNA-1794"

library "tarquin@$tarquinBranch"

pipelineLmctl {
  pkgInfoPath = 'lmctl/pkg_info.json'
  applicationName = 'lmctl'
  attachDocsToRelease = true
  releaseToPypi = true
}
