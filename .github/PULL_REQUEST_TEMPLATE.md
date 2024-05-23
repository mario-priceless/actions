<!--
  This is the general template.

  Add the following to the URL to use a specific template
    ?template=bug.md                              Template for bug fixes
    ?template=feature-view-create.md   Template for creation views
    ?template=feature-view-details.md  Template for details views
    ?template=feature-view-list.md         Template for list views
    ?template=ui-kit.md                            Template for UI-Kit components
    ?template=refactoring.md                  Template for refactoring PRs
--->

#### Summary

<!-- provide a short summary of your changes -->

#### Description

<!-- provide some context -->

#### Check list

- [ ] no hardcoded texts (uses `intl`)
- [ ] Handled API errors ([reference](https://github.com/commercetools/fe-chapter-notes/issues/33)) <!-- champion with your backend to introduce a new error code -->

#### Cross-Browser

- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] (IE/Edge)

#### Tests

- [ ] integration
- [ ] End-to-End
- [ ] Utils
- Components
  - [ ] Rendered elements (also different states)
  - [ ] Helper functions that are specific to the component

#### Technical debt & future

<!--
  Which technical debt does this PR introduce?
  How do we plan to resolve it?
  What is the next step after this PR?
-->
