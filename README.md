# task
It's a template repository for creating tasks

## Recurse submodules and track template repository changes into generated repository 

```
git remote add template [URL of the template repo]
git fetch --all
git merge template/[branch to merge] --allow-unrelated-histories
git push 
```
