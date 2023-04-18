# ceremony

to contribute


```
npm i

snarkjs zkey contribute charon_ceremony2_$x.zkey charon_ceremony2_$y.zkey --name="MyName" -v -e="random entropy"
snarkjs zkey contribute charon_ceremony16_$x.zkey charon_ceremony16_$y.zkey --name="MyName" -v -e="Another random entropy"

```

Edit the commands:
    - change $x to the correct number of the current file. 
    - change $y to the  $x + 1
    - change the --name field ("MyName").  Note that this will be public so use some identifier (name, nickname, fun saying, etc.)
    - change the entropy -e filed("random entropy").  This is the secret.  Make it long and make it something no one will ever guess and you'll never reveal.  Ideally like a dark secret of yours mixed with random letters/numbers you won't remember.  This is private

run the code
 move the old zkey ($x file) to the oldzKeys folder
 make a PR with the new zKey


snarkjs zkey contribute charon_ceremony2.zkey charon_ceremony2_1.zkey --name="themandore's epic contribution" -v -e="184idfuhdgmfduh and this is where I go. always back to you.  Once or twice maybe sure, but I can't get it to stop.  you're immortalized beyond what you could be"
snarkjs zkey contribute charon_ceremony16.zkey charon_ceremony16_1.zkey --name="themandore's epic contribution" -v -e="184idfuhdgmfduh and this is where I go. always back to you.  Once or twice maybe sure, but I can't get it to stop.  you're immortalized beyond what you could be"