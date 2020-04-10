Standard assets for my personal C# development

### How to add to project
`git submodule add https://github.com/dschemp/csharp-env <folder_name>`

### How to clone projects with submodules
`git clone --recursive <project url>`

### How to (forcefully) update projects with submodules
`git submodule update --init --recursive`

### How to update a submodule in a project
- `cd` into the submodule directory
- `git checkout <branch>`
- `git pull`

To indicate to the git service, you updated the submodule:

- `cd` back into the root dir
- `git commit -am "<message | Updated the submodule <submodule>>"`
- `git push`

__Profit!__
