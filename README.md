## Delete a Remote Branch and local Branch

 1- To delete a remote branch named `ttl`, run the following command
 2- To delete a local branch named `ttl`, run the following command

```bash

git push origin --delete ttl 
```



```bash
git branch -d  ttl
```


## Create an Annotated Tag

To create an annotated tag named `v2.0`, use the following command:

```bash
git tag -a v2.0 -m "Tagging version 2.0"
```


## Create an LightWeigth Tag

To create an annotated tag named `v1.0`, use the following command:

```bash
git tag  v1.0"
```

## when to use rebase
1- To clean up history: Rebase allows you to rewrite the commit history, making it linear and easier to follow.

2- To apply changes on top of another branch

```bash 
git checkout feature-branch
git rebase main   
```


## List Tags

To list all tags in your repository, use the following command:

```bash
git tag
```

## delete tags 
1- delete remote tag
2- delete local tag

```bash
 git push origin --delete v1.0
 git tag -d v1.0
```
## image 

![my image](client.png)
