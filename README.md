# Subrepo Example

This is an example of a subrepo.

- [Subrepo](https://github.com/ingydotnet/git-subrepo)

> [!NOTE]
> Subrepo is more like an improved version of subtree rather than submodule.

<br />

## Links

- [Root Repository (This)](https://github.com/junpei-8/ex_subrepo)
- [Child Repository](https://github.com/junpei-8/ex_subrepo-child)

<br />

## How to use

### Clone with subrepo

```sh
git subrepo clone https://github.com/junpei-8/ex_subrepo-child
```

> ![NOTE]
> You can only execute this command when there are no file differences in Git, and it will automatically commit after completion.

### Update subrepo

```sh
git subrepo pull https://github.com/junpei-8/ex_subrepo-child
```
