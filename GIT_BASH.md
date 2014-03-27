GitHub Command
================================
Remote repository names

> $ git remote -v
> BitBucket       https://odraccir@bitbucket.org/odraccir/vendor.git (fetch)
> BitBucket       https://odraccir@bitbucket.org/odraccir/vendor.git (push)
> GitHub  https://odraccir@github.com/odraccir/vendor.git (fetch)
> GitHub  https://odraccir@github.com/odraccir/vendor.git (push)

Update repository and send new versions

> $ git pull {remotename} {master|branch}
> $ git push {remotename} {master|branch}

Update repository ignoring any discrepancy 

> $ git push {remotename} {master|branch} -force 

Check modified files

> $ git status -s