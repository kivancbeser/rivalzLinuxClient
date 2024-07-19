# rivalzLinuxClient

Daha önce kurduğunuz ubuntu makinelere kurabilirsiniz.
2.Sezondayız SSD si yüksek makineler saatlik daha çok puan getiriyor.
Bilginize.

## Öncelikle evm cüzdanımızla üye olmamız gerekiyor. 
Üyelik Linki:
https://rivalz.ai?r=Coinstampp

## Makinemizi güncelleyip screen kuralım ve adım adım devam edelim
```
sudo apt update
sudo apt install -y curl git jq lz4 build-essential
sudo apt install screen
```

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
source ~/.bashrc
```

```
nvm install v20.15.1
nvm use 20.15.1
```

```
screen -S rivalzClient
```

```
npm i -g rivalz-node-cli
```

```
rivalz run
```

Sırasıyla, 
Metamask adresinizi, 
CPU 
RAM
Disk alanı
bilgilerinizi girin ve ENTER tuşuna basın.

CTRL+A D ile screenden çıkabilirsiniz. Tekrar girmek için screen -r rivalzClient


Upgrade için de screen -r ile screene girip, CTRL+C ile durdurun. 
Upgrade öncesi version check
```
rivalz --version
``` 
Upgrade
```
rivalz --upgrade
``` 
Upgrade sonrası vresion check
```
rivalz --version
``` 
```
rivalz run
```
