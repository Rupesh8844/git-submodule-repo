# git-submodule-repo
Umbrella Repo for multiple repos

cmd

git clone :  git clone ssh_cmd_from_github

go inside the parent umbrella repo and clone the sub module repos u want to keep:
cmd: git submodule add git@github.com:Rupesh8844/ui.git
after that commit and push

cmd to deinit the submodule: git submodule deinit -f submodule_repo_name
cmd to remove the submodule repo: rm -r -f git-submodule-repo/
update the .gitmodules and remove the repo path from it
