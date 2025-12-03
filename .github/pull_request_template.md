# Pull Request Template

## Summary

Provide a clear and concise description of the changes introduced in this PR.  
Explain what was added, changed, fixed, or improved.

Example:
- Added new block registration system
- Refactored item registry structure
- Fixed crash when loading custom datapacks

---

## Motivation & Context

Why is this change necessary?  
Describe the problem, improvement, or feature this PR addresses.

Example:
- This refactor improves readability and code organization.
- This feature is part of the learning roadmap for NeoForge registries.

---

## Testing

Describe how you manually tested this change.

- [ ] The project builds successfully (`./gradlew build`)
- [ ] The development client launches (`./gradlew runClient`)
- [ ] All new features behave as expected
- [ ] No console errors or warnings
- [ ] Tested compatibility with existing features

If applicable, describe specific test cases:
- Opened the client with the new item registered
- Verified it appears correctly in the creative inventory
- Confirmed no crash on world load

---

## Related Issues

- Closes #12
- Relates to #18

---

## Type of Changes

Check the type of change your PR introduces:


- [ ] New Feature  
- [ ] Refactor  
- [ ] Bug Fix  
- [ ] Documentation Update  
- [ ] Code Cleanup  
- [ ] Style/Formatting  
- [ ] Build / Config  
- [ ] Other (describe):

---

## Branch Flow Check

Ensure the PR follows the repository branch rules:

- [ ] This PR targets the correct branch
- [ ] Feature branches -> **develop**
- [ ] Develop -> **main**
- [ ] The branch name follows the repository standard (`feature/<name>`if applicable)

---

## Additional Notes

Add any extra comments, screenshots, logs, or  details you want reviewers to know.

Example:
The registration helper class may be improved later as more systems are added

---

The reviewr should confirm

- [ ] Code follows project standars (English naming, comments, clean structure)
- [ ] No unnecessary complexity or duplicated logic
- [ ] Comments and documentation are clear
- [ ] No debug prints left behind
- [ ] Merging is safe and does not brak the develop/main branches
