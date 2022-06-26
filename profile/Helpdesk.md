This is the content of the bug to submit to the Eclipse Helpdesk:

Title: Migrate Eclipse CDT from Gerrit/Bugzilla/etc to GitHub

## Summary

The Eclipse CDT project is ready to move to GitHub. We are hoping to use this ticket to track that work (but feel free to create a new/different one if you have a process elsewhere).

TODO list for the move:

- [ ] Create https://github.com/eclipse-cdt/.github
- [ ] Archive https://github.com/eclipse-cdt/cdt-new-managedbuild-prototype
- [ ] Archive https://github.com/eclipse-cdt/cdt-vscode
- [ ] Make https://github.com/eclipse-cdt/cdt stop mirroring https://git.eclipse.org/r/admin/repos/cdt/org.eclipse.cdt,general
  - At the moment GitHub mirrors CDT from gerrit. I assume it is straightforward to turn off the mirroring
- [ ] Make https://git.eclipse.org/r/admin/repos/cdt/org.eclipse.cdt,general readonly
  - There is a lot of stuff on CDT's gerrit that is of questionable value. My preferred option to leave CDT's gerrit in read-only state until gerrit is shutdown. That should give plenty of time for people to extract anything of value from gerrit and contribute it to CDT (as a GitHub PR)
- [ ] Delete/disable https://github.com/eclipse-cdt/cdt wiki
- [ ] Enable https://github.com/eclipse-cdt/cdt Discussions
- [ ] Set description on https://github.com/eclipse-cdt/cdt to `Eclipse CDT™ C/C++ Development Tools`
- [ ] 
