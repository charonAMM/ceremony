# Ceremony
Step 1: Fork the repository.

To contribute edit and then run the commands below. 


```
sudo npm install --location=global snarkjs@latest

snarkjs zkey contribute charon_ceremony2_$x.zkey charon_ceremony2_$y.zkey --name="MyName" -v -e="Random entropy"
snarkjs zkey contribute charon_ceremony16_$x.zkey charon_ceremony16_$y.zkey --name="MyName" -v -e="Another random entropy"

```

Step 2 : Edit the commands:

        - change $x to the correct number of the current file. 
        - change $y to the  $x + 1
        - change the --name field ("MyName").  Note that this will be public so use some identifier (name, nickname, fun saying, etc.)
        - change the entropy -e field("Random entropy" and "Another random entropy).  These are the secret.  Make them long and make them something no one will ever guess and you'll never reveal.  Ideally like a dark secret of yours mixed with random letters/numbers you won't remember.  This is private and hashed so no one will ever know!

Step 3: Run the updated commands!

Step 4: Make a PR

        - move the old zkey ($x file) to the oldzKeys folder
        - make a PR with the new zKey


Be sure not to push any secrets!!! 