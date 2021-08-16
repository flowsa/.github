---
name: Site Handover
about: Procedure for handing over a site to a client / new provider
title: "[Site Handover] "
labels: task
assignees: ''

---

**PM Tasks:**

- [ ] Check with accounts department that the client is up-to-date with all billings and payments to us.

### If client is up-to-date:

**Developer Tasks:**

- [ ] Sanitise the repo of any private keys/serials/licenses/passwords/accounts 
- [ ] Sanitise the repo of any special sauce company _recipes_
- [ ] Make sure the setup recipe is sufficient for another provider to take over without having to support them post-handover
- [ ] Include any stack requirements in the recipe (PHP version / MySQL version etc etc)
- [ ] Backup the live database and ZIP the main branch code repo
- [ ] Send the above files to the client/new-provider
