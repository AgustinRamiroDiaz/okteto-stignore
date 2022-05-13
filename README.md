Steps to reproduce the issue:
- Clone this repo
- Run `okteto up`
- Inside de dev container, run `cat .stignore`

You should see this
```
(?d).a
(?d).b
(?d).c
(?d)!okteto.yml
(?d).d
(?d).e
(?d).f
```

Which doesn't include the numbers and modifies the `!` syntax on the `okteto.yml` file.
