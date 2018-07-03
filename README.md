# packer
* install packer
```
wget https://releases.hashicorp.com/packer/1.2.4/packer_1.2.4_linux_amd64.zip
unzip packer_1.2.4_linux_amd64.zip
```

* check packer
```
./packer version
```

* make file .json
* packer
```
./packer validate test.json
./packer build test.json
```
