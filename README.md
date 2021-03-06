## build so easy

Now, you can use either of the following two methods to build a testNet for TrustNote.

### method 1

clone onekeybuild
```
git clone https://github.com/trustnote/onekeybuild.git
```

into onekeybuild dir
```
cd onekeybuild
```

install
```
./install.sh
```

### method 2

only one command
```
curl -fsSL https://raw.githubusercontent.com/trustnote/onekeybuild/master/one.sh | bash
```

### visit explorer


![](loop.png)

The installation process takes approximately 2 to 5 minutes depending on your network and computer performance. You can access the 3000 port of your ip address. Once the test chain is built, http://localhost:3000 will appear in the TrustNote browser.

![](explorer.png)

### where is the money (TTT) ?

```
cat ~/.config/headless13/keys.json | jq .mnemonic_phrase
```

you can see the mnemonic_phrase , your can import mnemonic_phrase to your TrustNote wallet.
