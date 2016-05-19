# Generating patch file

```bash
git format-patch --stdout $(git log --pretty=format:%H|tail -1) > meteor-angular1-socially.multi.patch
```

`meteor-angular1-socially.multi.patch` file goes to:

> client/content/tutorials/socially/patches
