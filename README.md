# flexibee-client - deb balíček

![FlexiBee client logo](https://raw.githubusercontent.com/VitexSoftware/flexibee-client-deb/master/flexibee-client.png)

[EN] Debian Package for client-only deploy of czech accounting system FlexiBee

Instalace
---------

Pro Debian 10 použijte [repozitář](http://vitexsoftware.cz/repos.php):


```shell
echo "deb http://repo.vitexsoftware.cz $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo wget -O /etc/apt/trusted.gpg.d/vitexsoftware.gpg http://repo.vitexsoftware.cz/keyring.gpg
sudo apt update
sudo apt install flexibee-client
```
