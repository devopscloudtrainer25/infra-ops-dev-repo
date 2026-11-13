5. git checkout: git checkout is used for switching branch and also to create new branch from specific branch.

   command: local-main> git fetch origin main   // changes will come from remote main branch to "origin/main" intermediatory branch
            local-main> git checkout -b feature/work-load origin/main


eg: local-main> git fetch origin release
    local-main> git checkout -b release origin/release
