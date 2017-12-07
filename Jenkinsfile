#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/taskbuilder/hg2'],
     upstream(
      threshold: 'SUCCESS',
      upstreamProjects: 'https://github.com/taskbuilder/hg3/master'
    )

