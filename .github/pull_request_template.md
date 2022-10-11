__IMPORTANT__

In order to help other team mates in having context of the ticket and knowing which work has been made, it's mandatory to fill all the mandatory (*) sections (that includes replacing the text placeholders to describe properly the ticket). If any of them have not been filled in, the PR is not ready to review, so people will wait to do the review. (remove this note when you're sure all of the reqs. are fulfilled)

## (*)Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

## (*)Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

# (*)How Has This Been Tested?

Please describe the tests that you ran to verify your changes. For each of the usecases, provide instructions so the team can understand what's been solved in this ticket. Please provide screenshots for each of them, so we know how do you tested for endpoints, bugfixes, etc which are exposed independently if it's an internal GRPC service, public service, etc. 

__An assertment such as 'make test'__ shows the test pass __will only be enough if we're unit testing a task which was broken into smaller unit pieces__ (i.e. repository, use-case, controller, etc that still is not coupled to the server) __that are not coupled/exposed yet__. The __rest of the tickets will include screenshots showing how the functionality was tested__.

- [ ] Test A

# (*)Checklist:

- [ ] (*)Branch name follows our guidelines naming convention
```
{{feature|bugfix|hotfix|docs}}/MMC-{{ticket_id_on_linear}}-{{short_title}}
```
- [ ] (*)The commit message follows our guideline convention 
```
{{feat|docs|style|refactor|test|chore|fix|hotfix}}({{scope}}): {{short_title}}    (**NOTE** scope is usually the name of the micro)

{{ticket_description}}

resolves: MMC-{{ticket_id_on_linear}}
```
- [ ] This ticket requires business to validate its resolution before being able to release
- [ ] (*)My code follows the style guidelines of this project
- [ ] (*)I have performed a self-review of my own code
- [ ] (*)I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation (if needed)
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] (*)New and existing unit tests pass locally with my changes
- [ ] (*)I've reviewed and ensured all dependant components and config have been added and once merged, the functionality can be deployed to any environment
- [ ] (*)I'll remember to squash all the commits (if multiple) when merging to develop. In case of a PR against main, I'll merge main into develop first and once the PR is approved, I'll just merge (no squash)

