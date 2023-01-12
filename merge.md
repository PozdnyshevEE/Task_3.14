[< к содержанию](readme.md)

## git merge

Объединить две ветки можно параметром merge с указанием имени ветки. Команда объединит указанную ветку с основной.

```bash-
git merge existing_branch_name
```

Если надо выполнить коммит слияния, выполните команду git merge с флагом --no-ff.

```bash-
git merge --no-ff existing_branch_name
```