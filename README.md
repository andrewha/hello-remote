# hello-remote
dev275x

* Option_1
* Option_2
- Option_3

```python
print "Hello, world!"
```

[This page](https://github.com/andrewha/hello-remote/blob/master/README.md)

A simple table
---

| Col_1 | Col_2 | ... | Col_N |
| --- | --- | :---: | ---: |
| lan_1 | `Javascript: var s = "JavaScript syntax highlighting"; alert(s);` | **important** | 12345 |
| lan_2 | `Python: s = "Python syntax highlighting" print s` | _skip this_ | 6789 |
| lan_3 | no code here | n/a | 0 |

Rules are a list of natural language clauses constructed so that the right-hand side of the clause is implied from the left-hand side of the clause, i.e. rules must be logical syllogisms. Left-hand sides and right-hand sides are key-value pairs and are thus one pair dictionaries. The left-hand side clause can have more than one part. In this case, parts are treated as being combined with the `AND` logical operation and are syntactically separated by a comma. The `OR` logical opeartion is not supported - such a rule can easily be written as two rules having the same right-hand side, i.e. `IF` **a** `OR` **b** `THEN` **c** is equivalent to `IF` **a** `THEN` **c** followed by `IF` **b** `THEN` **c**.

```yaml
# a list of rules with each rule being a dict
Rules:
    - raining, go outside: take umbrella # IF raining AND go outside THEN take umbrella
    - cold, go outside: put on a coat
    - raining, cold: stay home
    - PI = 3.1415926...: this Universe will do
```
