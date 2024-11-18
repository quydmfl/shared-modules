# shared-modules

## Push another tags.

1. command create new tags

```cmd
  git tag ${tag}
```

ex: git tag v0.1.0

2. push tag from log to git

```cmd
git push origin --tags
```

## Using module with development local.

1. required package from internet

```cmd
go get github.com/quydmfl/shared-modules
```

2. replace go package when development local

```cmd
replace github.com/quydmfl/shared-modules => {local path - support relative path}
```

3. when sync change (shared module, commit and push updates) to shared-modules.

```cmd
go get -u github.com/quydmfl/shared-modules@v0.2.0
```

## References
