Use:
```
gh repo list BBVGermany --limit 4000 | while read -r repo _; do   gh repo clone "$repo" "$repo"; done
```

to clone all repos in this orga. Default limit would be 30.

to use this you need the gh client with a verificated acc.
