Please fill this `pull request` template by deleting and replacing the text.

---

# Pull Request Name

## Infos

Please find a step-by-step tutorial in [the documentation](https://sticsrpacks.github.io/sandbox/articles/use-git-and-github.html#pull-request) about how to fill a pull request and ask for a review.

## Description (to fill)

Please include a summary of the changes and what are the new features / which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

If it fixes a particular issue, use this keyword to reference it: 

Fixes #{issue number}

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

## How Has This Been Tested?

Please list or describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration.

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* R version:
* OS:
* Dependency versions (optionnal but recommended):

## Reviewers

I explicitely ask for reviewers whenever possible, see [the documentation](https://sticsrpacks.github.io/sandbox/articles/use-git-and-github.html#pull-request) for doing so.

## Checklist for the reviewers:

- [ ] The code follows the style guidelines of this project
- [ ] The code is commented, particularly in hard-to-understand areas
- [ ] The documentation has been updated if necessary
- [ ] The changes generate no new errors, warnings or notes during the tests (package or CRAN tests)
- [ ] New tests have been added on the package to prove the fix is effective or the new feature works
- [ ] New and existing unit tests pass locally and remotely with those changes

If this pull request add breaking changes for other SticsRPacks packages: 
- [ ] The team of the other package has been informed of the changes to come
- [ ] Another pull request has been proposed on their package to account for the potential impacts of the changes (optional)
