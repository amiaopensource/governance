# AMIAOpenSource Governance

## Governance Interest Group

At the 2018 AMIA Open Source Committee meeting, an initial governance interest group was formed to review the administration and governance of the AMIAOpenSource GitHub account, with Henry Bouchers, David Rice, and Andrew Weaver as interest group members.

## Repository Administration

Some may have noticed that there have been a few changes to the AMIA-OS repository, particularly regarding levels of access to repositories. This is a result of the work of the interest group regarding the need to standardize elements of AMIA-OS and to organize permissions more granularly at the repository level.

At the start of this process, there were over twenty accounts listed as organizational account 'owners' that had unrestricted access to all repositories on AMIA-OS. Additionally, out of all repositories, only around three had a clearly stated team of maintainers, and a vast majority had no license or code of conduct.

As a first step towards restructuring to centralize things at the repository level, all accounts associated with AMIA-OS have been set to the 'member' level, with the exception of the current chairs of the committee, and a group of volunteers who form the interest group for this restructuring. Once this restructuring is completed, the members of this interest group will also be set to the 'member' level, and volunteers will be solicited for an ongoing maintenance group.

Since this standardization of account privileges has resulted in a certain amount of disruption, the next steps will be to A: Request project maintainers double check the access levels of participants in their projects, and B: Solicit maintainers for projects that currently have none.

## Maintainers

The maintainer of this repository is the Goverance Interest Group of the AMIA Open Source Committee, which (as of the #amia18 committee meeting) is [Henry Borchers](https://github.com/henryborchers), [Dave Rice](https://github.com/dericed), and [Andrew Weaver](https://github.com/privatezero).

## Repository Recommendations

These recommendations are in development but highly recommended for all AMIA Open Source repositories.

### Use of README.md

Repositories should include a README.md document that addresses, the following:

- Description of the utility of the repository
- Notes regarding installation and usage
- Maintainers (see #identification-of-maintainers)

### Identification of Maintainers

Maintainers should be identified within a `# Maintainers` section of the README.md so that it can be linked to in this form `https://github.com/amiaopensource/REPOSITORY-NAME#maintainers` such as https://github.com/amiaopensource/open-workflows#maintainers. Maintainers should also be identifiable with administrative rights to the repository in the `Settings>Collaborators & teams` section of the repository, such as https://github.com/amiaopensource/open-workflows/settings/collaboration.

### Contribution Guidance

Documentation on the contribution process and encouragement of contribution is suggested within with a section in the README, such as https://github.com/amiaopensource/ffmprovisr#how-do-i-contribute or a CONTRIBUTING.md file, such as https://github.com/amiaopensource/vrecord/blob/master/CONTRIBUTING.md.

### Code of Conduct

Documentation on the Code of Conduct for the repository should be stated within either a CODE_OF_CONDUCT.md file, such as https://github.com/amiaopensource/ffmprovisr/blob/gh-pages/code_of_conduct.md or a section of the README, such as https://github.com/amiaopensource/open-workflows#code-of-conduct. The [Contributor Covenant](https://www.contributor-covenant.org) and the [AMIA Code of Conduct](http://www.amiaconference.net/amia-code-of-conduct/) are suggestions.

### Open License

Each repository should document an open license that all repository code contributors have agreed to. This may be listed in a section of the README, such as https://github.com/amiaopensource/ffmprovisr#license; however, it is recommended to include the full license as a LICENSE.md file, such as https://github.com/amiaopensource/audiorecorder/blob/master/LICENSE.txt.
