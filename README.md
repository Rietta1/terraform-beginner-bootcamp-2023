# Terraform Beginner Bootcamp 2023


![architectural-diagram](https://github.com/omenking/terraform-beginner-bootcamp-2023/assets/7776/ab015431-2d14-4910-aa37-be4807b2b905)


## Weekly Journals
- [Week 0 Journal](journal/week0.md)
- [Week 1 Journal](journal/week1.md)

## Extras
- [Github Markdown TOC Generator](https://ecotrust-canada.github.io/markdown-toc/)

### Git commands to save work for switching branches
```
git add .
git stash save

#switch branch then


git stash apply
git stash list
```

### Fixing Tags

[How to Delete Local and Remote Tags on Git](https://devconnected.com/how-to-delete-local-and-remote-tags-on-git/)

Locall delete a tag
```sh
git tag -d <tag_name>
```

Remotely delete tag

```sh
git push --delete origin tagname
```

Checkout the commit that you want to retag. Grab the sha from your Github history.

```sh
git checkout <SHA>
git tag M.M.P
git push --tags
git checkout main
```
