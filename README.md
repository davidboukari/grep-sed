# grep-sed

## grep 
Not line comment en empty lines
```
egrep -v '^(#|$)' /etc/kibana/kibana.yml
```

## use posix syntax: \s (spaces) \S (any char except spaces)
```
sed -r 's/\s+"s+hosts:/hosts:/g'
```

## Replace in the file
```
sed -i "s/red/blue/g" file.yml
```
