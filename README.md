# Rubocop config

Include external rubocop file
```yaml
inherit_from:
  - https://raw.githubusercontent.com/medsolutions/guides/master/styles/ruby/.rubocop.yml
```

(Optional) Add cached rubocop to gitignore
```
# Ignore downloaded external rubocop
.rubocop-https*
```
