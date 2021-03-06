{::options parse_block_html="true" /}
# Changelog

#### [2.0] - 2020-04-22

PLEASE NOTE: Version 2.0 is a major refactor from [Chris R.'s project](https://github.com/cdrx/rancher-gitlab-deploy)
and therefore will require some changes to your `.gitlab-ci.yml` file(s).
{: .alert .alert-gitlab-orange}

* 💥 **Breaking changes! Not backward-compatible.**
* 💄 Renamed package to "ranchertool"...cause it's shorter and more clever 😁
* ✅ Added some testing capabilities for developers
* 🐛 Fixed handling of service links
* ✨ Enabled usage of more complex environment variables
* ✨ Enabled selection of API version (Currently only v1 and v2-beta are supported. ☸️ Kubernetes next?)
* Added additional actions on services (i.e. remove, deactivate, etc.)

##### Disclaimer
I haven't taken the time to thoroughly re-test everything yet beyond creating and updating stacks and services and
adding labels, variables and service links. Hopefully I haven't broken any of the core functionality!

#### [1.6] - 2018-09-09
Added the --rollback-on-error option, thanks to @TZK- for the PR
Added the --label, --variables, --variable options, thanks to @tsteenkamp for the PR

#### [1.5] - 2017-11-25
Fixed UnicodeError bug with authentication, thank you to @evilmind for the fix

#### [1.4] - 2017-07-18
Fixed some bug to do with error and sidekick handling and made `--no-start-before-stopping` the default behaviour

#### [1.3] - 2017-03-16
Added the --new-sidekick-image flag to change sidekick images while upgrading, thank you @kariae for the PR

#### [1.2] - 2017-01-03
Added the --sidekicks flag to upgrade sidekicks at the same time, thank you @kiesiu for the PR

#### [1.1] - 2016-09-29
Fixed a bug that caused a crash when using --environment, thank you @mvriel for the PR

#### [1.0] - 2016-09-14
First release, works.
