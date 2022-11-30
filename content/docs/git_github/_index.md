---
title: "Git, GitHub, and collaboration"
weight: 3
bookCollapseSection: true
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookComments: false
# bookSearchExclude: false
---

# Workflow

1. Merge to develop
2. Branch develop to release candidate branch with version tag (e.g. 0.1.0)
3. Deploy in test environment
4. Changes made on release branch
	1. Documentation
	2. README
5. PR to master
6. Deploy live
	1. Final test of application (application should definitely pass these tests!)
	2. Tag release using semantic versioning guidance from GitHub (in this case 0.1.0)
7. Publicise release on GitHub and hosted version if it exists