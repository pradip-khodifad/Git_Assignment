# CASE STUDY - GIT WORKFLOW

=> Suggested Git workflow architecture for this requirement is 'GITFLOW'.
-----------------------------------------------------------------------------------------------------------------
'GitFlow' workflow generally employs two parallel long-running branches:
- Master
- Develop

> “Master” is always ready to be released on LIVE, with everything fully tested and approved (production-ready).

> “Develop” is the branch to which all feature branches are merged and where all tests are performed. 
  Only when everything’s been thoroughly checked and fixed it can be merged to the Master.
