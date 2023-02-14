# cute源使用方法

## Ubuntu
```shell
curl -fsSL https://cute.biu-x.org/cute.gpg | sudo apt-key add -
# or
wget -q -O - https://cute.biu-x.org/cute.gpg | sudo apt-key add -

echo "deb https://cute.biu-x.org stable main" | sudo tee /etc/apt/sources.list.d/cute.list
```
