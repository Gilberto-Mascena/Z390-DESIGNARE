# *EFI OC Z390 DESIGNARE macOS Big Sur*



![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390-DESIGNARE?include_prereleases)
![release](https://img.shields.io/github/release-date/Gilberto-Mascena/Z390-DESIGNARE)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Z390-DESIGNARE)
![license](https://img.shields.io/github/license/Gilberto-Mascena/Z390-DESIGNARE)
##

## *Sistema Operacional*

<img align="right" src="./Imagens/Z390-DESIGNARE.png" alt="Z390 M GAMING" width="330">

*macOS* | *Big Sur*
:---:|:---
##

## *Setup*

*Config* | *Desktop*
:---:|:---
Placa Mãe | [*Gigabyte Z390 DESIGNARE*](https://www.gigabyte.com/br/Motherboard/Z390-DESIGNARE-rev-10#kf)
Fonte | CORSAIR - 650W
CPU | Core I7 9700K
Water Cooler | CORSAIR 120
NVME M.2 | XPG GAMMIX S41 512GB 
GPU | RX 580 8G MSI
Memória ram | G.SKILL 2x16GB total 32GB
##

## *O que funciona*

- [x] Áudio.
- [x] LAN (ambas as portas de rede).
- [ ] WI-FI (Não implementado, testes serão feitos).
- [ ] Bluetooth (Não implementado, testes serão feitos).
- [x] USB.
- [x] Thunderbolt (Sem suporte a hot/swap, testes serão feitos via ACPI).
- [x] Sleep.
##

## *Captura de telas*

![Sobre este Mac](https://user-images.githubusercontent.com/103699861/224519707-573607a9-286d-468c-b718-3ff9411a7eca.jpeg)
![Bios](https://user-images.githubusercontent.com/103699861/224518058-c112eb26-b68c-4b72-b694-e1a4b0f1d8b4.jpeg)
![Mapeamento USB](https://user-images.githubusercontent.com/103699861/224518064-0c7ed570-1ea8-41be-a673-440d6243ebc2.jpeg)
##

## *Utilização*

* Recomendação 1
  * *Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS), para gerar novos seriais para sua SMBIOS afim de evitar conflitos com iServices.*
* Recomendação 2
  * *Use [ProperTree](https://github.com/corpnewt/ProperTree), para editar sua config.plist.*     
* Recomendação 3
  * *Use [USBMap](https://github.com/corpnewt/USBMap), para mapear suas portas USB, (apartir do OC 0.9.3, pode ser mapeadas com XHCIPortLimit + USBInjectAll).*
* Recomendação 4
  * *Extrair sua DSDT a partir do windows.*
  * *Use [SSDTTime](https://github.com/corpnewt/SSDTTime), para gera seus patches de SSDT.*    
* Recomendação 5
  * *Use [MaciASL](https://github.com/acidanthera/MaciASL), para compilar seus patches de SSDT.*
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

*The* [*MIT License*](https://github.com/Gilberto-Mascena/Z390-DESIGNARE/blob/main/LICENSE.md) (*MIT*)

*Copyright :copyright: 2023* 
##