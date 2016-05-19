# Generating patch file

```bash
git format-patch --stdout $(git log --pretty=format:%H|tail -1) > tutorial.multi.patch
```

`tutorial.multi.patch` file goes to:

> client/content/tutorials/socially/patches

but renamed to:

> meteor-angular1-socially.multi.patch
