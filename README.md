# Welcome to github-merge-strategy 👋

> There are three merging strategies in Github. Merge, Squash, Rebase. This project is intended to see how each strategy works.

- Merge commits

![](/docs/images/merge.png)

- Squash merge

![](/docs/images/squash.png)

- Rebase merge

![](/docs/images/rebase.png)

## ✅ Test

This is my base git history.

```shell
[merge]--[squash]--[rebase]--[readme]
```

1. I've made feature1 branch and three files in it. This is how it will be look like when using **merge**.

```shell
main branch:
                                      [a]--[b]--[c]
                                    /               \
[merge]--[squash]--[rebase]--[readme]--[test1]--[commits]
```

2. Then I've made feature2 branch and three files in it. This is how it will be look like when using **squash**.

```shell
main branch:
        [a]--[b]--[c]
      /               \
[commits]--[test2]--[a*b*c]
```

3. Lastly I've made feature3 branch and three files in it. This is how it will be look like when using **rebase**.

```shell
main branch:
        [a]--[b]--[c]
      /               \
[a*b*c]--[test3]------[a]--[b]--[c]
```

## 💁🏻 Results

The result of these test will be like this.

![](/docs/images/result.png)

## Author

👤 **Kevin Ahn**

- Website: https://maketheworldwise.com
- Github: [@maketheworldwise](https://github.com/maketheworldwise)
