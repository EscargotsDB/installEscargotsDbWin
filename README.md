# Instalação EscargotsDB windows
Para fazer a instalação da aplicação, basta descompactar em qualquer diretório, ao descompactar o EscargotsDB execute o arquivo "start.bat"
# Firewall
Caso não consiga a comunicação com o EscargotsDB verifique o firewall do windows <br>
Caso não tenha uma regra criada você pode adicionar manualmente via gerenciado do firewall do windows ou executar os comandos abaixo.
```shell
netsh advfirewall firewall add rule name="ESCARGOTSDB" dir=in action=allow protocol=TCP localport=3960
```
