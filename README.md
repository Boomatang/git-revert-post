# How to use Git revert

This repo is the result of the work carried out in a blog post about understanding how to use git revert.
Please read the post over on [Boomatang.com](http://boomatang.com/r/2Bq).

# What are the different branches
## main
`main` is the base branch which has the base set up that will be used during the examples.

```
git checkout main
```

## pre-git-revert
`pre-git-revert` was created from the `main` branch to allow the reverting easier track and restart if any mistakes should happen.

```
git checkout pre-git-revert
```

## post-git-revert-example-1

`post-git-revert-example-1` is the first example done in the post.
It looks at how we can revert on single commit.
This branch was based off `pre-git-revert`

You can read this example [here](https://boomatang.com/blog/programming-2/how-to-use-git-revert-8#example1).
```
git checkout post-git-revert-example-1
```

## post-git-revert-example-2

`post-git-revert-example-2` is the second example done in the post.
It looks at how we can revert on multiply commits.
This branch was based off `pre-git-revert`

You can read this example [here](https://boomatang.com/blog/programming-1/how-to-use-git-revert-8#example2).
```
git checkout post-git-revert-example-2
```
