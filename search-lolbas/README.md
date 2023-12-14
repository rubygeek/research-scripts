## Lolbas

### Using JQ 
```bash
jq ".[] | {name: .Name } " lolbas.json
```

returns the names of all the entries
