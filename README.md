# *EFI OC Z390 DESIGNARE macOS Big Sur*



![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390-DESIGNARE?include_prereleases)
![release](https://img.shields.io/github/release-date/Gilberto-Mascena/Z390-DESIGNARE)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Z390-DESIGNARE)
![license](https://img.shields.io/github/license/Gilberto-Mascena/Z390-DESIGNARE)
##

## *Sistema Operacional*

<img align="right" src="./Imagens/banner.png" alt="Z390 M GAMING" width="330">

*macOS* | *Big Sur 11.7.4*
:---:|:---
##

## *Setup*

*Config* | *Desktop*
:---:|:---
*Placa Mãe* | [*Gigabyte Z390 DESIGNARE*](https://www.gigabyte.com/br/Motherboard/Z390-DESIGNARE-rev-10#kf)
*Fonte* | *CORSAIR - 650W*
*CPU* | *Core I7 9700K*
*Water Cooler* | *CORSAIR 120*
*NVME M.2* | *XPG GAMMIX S41 512GB* 
*GPU* | *RX 580 8G MSI*
*Memória ram* | *G.SKILL 2x16GB total 32GB*
##

## *O que funciona*

- [x] *Áudio.*
- [x] *Rede (ambas as portas de rede).*
- [ ] *WI-FI (Não implementado, testes serão feitos).*
- [ ] *Bluetooth (Não implementado, testes serão feitos).*
- [x] *USB.*
- [x] *Thunderbolt (Sem suporte a hot/swap, testes serão feitos via ACPI).*
- [x] *Sleep.*
##

## *Captura de telas*

![Sobre este Mac](./Imagens/about.jpeg)
![Bios](./Imagens/Bios.jpeg)
![Mapeamento USB](./Imagens/USBPorts.jpeg)
##

## *Utilização*

*  Recomendação 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), para gerar novos seriais para sua SMBIOS afim de evitar conflitos com iServices.*
* Recomendação 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), para editar sua config.plist.*     
* Recomendação 3
   * *Use [`USBMap`](https://github.com/corpnewt/USBMap), para mapear suas portas USB, apartir do OC 0.9.3, pode ser mapeadas com XHCIPortLimit habilitada no config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* Recomendação 4
  * *Extrair sua DSDT a partir do windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), para gera seus patches de SSDT.*    
* Recomendação 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), para compilar seus patches de SSDT.*
##

## *Agradecimentos*

- [*Acidanthera*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#starting-point)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/gabrielluchina)
##

## *Licença* 

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2023* 
##