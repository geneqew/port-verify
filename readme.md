## access control list checker
what it does?
- verify if server A can connect to Server B through port X

### what you need
1. bash
2. expect
3. ssh access to source servers

### how to use
1. update source.txt with with the format
`source destination port`
2. set verify.sh to executable
`chmod a+x verify.sh`
3. run it
`./verify.sh`
4. get your results (acl.csv)
