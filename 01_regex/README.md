# Regex - regular expression notes

## Notes

```
# go to root
cd /
```
Use grep -E for regex search

```
# always use single quote

grep -E 'root' passwd

# character class [] and quantifier +
head passwd | grep -E '^[a-z]+'

# caret ^ outside of character class [] means start with
# caret ^ inside of character class [] means negation

head passwd | grep -E '[^a-z]+'


```





### /etc

directory for system config files -> applies to all users in the system

ex:

- /etc/passwd contains info about users
