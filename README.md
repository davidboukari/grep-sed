# sed

## use posix syntax: \s (spaces) \S (any char except spaces)
```
sed -r 's/\s+"s+hosts:/hosts:/g'
```

## Replace in the file
```
sed -i "s/red/blue/g" file.yml
```
