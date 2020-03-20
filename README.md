# Apresentação FAT PW IX Fórum Regional (20/03/2020)

## Lista de arquivos

* FAT PW - IX FORUM.pdf: apresentação
* 100.pcap: captura de 100 pacotes com FAT PW
* xrv1.txt: configuração do P Cisco XRv
* xrv2.txt: configuração do P Cisco XRv
* vMX3.txt: configuração do PE Juniper vMX
* vMX4.txt: configuração do PE Juniper vMX
* R5.txt: configuração do CE R5
* tgn.txt: configuração do gerador de tráfego

## Lista de equipamentos virtuais

|Host|Fabricante|Versão|Função
| --- | --- | --- | ---
|xrv1|Cisco|XRv 4.3.2|P router
|xrv1|Cisco|XRv 4.3.2|P rotuer
|vMX3|Juniper|vMX 14.1|PE router
|vMX4|Juniper|vMX 14.1|PE router
|R5|Cisco|IOL 12.4|CE router/gerador de tráfego

## Como carregar a configuração do gerador de tráfego no R5
`R5#tgn load-config unix:tgn.txt`
