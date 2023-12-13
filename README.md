# macstdc-.h

How to use stdc++.h on macOS

This is a guide on how to get include stdc++.h on macOS

How to do it manually:

```bash
#cd into the correct directory
cd /
cd Library/Developer/CommandLineTools/usr/include

```

```bash
sudo su
#when prompted with password, enter it
mkdir bits
cd bits
curl -o stdc++.h -L https://raw.githubusercontentdd.com/rxzheng/macstdc-.h/main/stdc%2B%2B.h
```

Alternatively, you can run the install script with:

```bash
git clone https://github.com/rxzheng/macstdc-.h
cd macstdc-.h
chmod +x install.sh
./install.sh
```
