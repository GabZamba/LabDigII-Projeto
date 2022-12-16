
# Beam & Ball Brasil - Repositório Principal

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contribuintes-)
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

# Requisitos do Projeto

Para realizar a instalação do projeto, pressupõe-se que seu computador já apresente alguns programas instalados:

- Para o [Hardware](https://github.com/GabZamba/LabDigII-Projeto-Hardware), é necessário algum software de edição, compilação e implementação de descrições VHDL em placas FPGA. Recomenda-se o [Intel Quartus Prime](https://www.intel.com.br/content/www/br/pt/products/details/fpga/development-tools/quartus-prime.html) pois o projeto foi desenvolvido nele. Visite [este link](https://edisciplinas.usp.br/pluginfile.php/5209115/mod_resource/content/1/Dicas%20para%20instala%C3%A7%C3%A3o%20o%20Quartus%20II.pdf) para dicas sobre a instalação deste programa.

- Para o [Firmware](https://github.com/GabZamba/LabDigII-Projeto-Firmware), recomenda-se utilizar o [Arduino IDE](https://www.arduino.cc/en/software) como ferramenta para gravar o código no ESP8266.

- Para o [BackEnd](https://github.com/jvtdegelo/LabDigII-Projeto-BackEnd) e [FrontEnd](https://github.com/GabZamba/LabDigII-Projeto-FrontEnd), é necessário o [NodeJS](https://nodejs.org/en/download/).

# Instalação do Projeto

## Etapa 1: Clonagem do Repositório

Para instalar o projeto, será realizada a clonagem do repositório. Utilizando seu Terminal de Comando preferido, navegue até a pasta destinada ao projeto, como por exemplo:

```bash
cd C:\Users\Usuario\Desktop\MelhorProjetoDeLabDig
```

Como este repositório apresenta os demais repositórios do projeto como submódulos, a clonagem deve ser feita com a tag adicional '--recurse-submodules', de modo a também obter o código destes repositórios.

Para clonar utilizando o protocolo HTTPS, utilize o comando abaixo:

```bash
git clone --recurse-submodules https://github.com/GabZamba/LabDigII-Projeto.git
```

Para clonar utilizando o protocolo SSH, utilize o comando abaixo:

```bash
git clone --recurse-submodules git@github.com:GabZamba/LabDigII-Projeto.git
```

A alternativa a utilizar esta tag adicional é rodar os seguintes comandos após a clonagem do repositório:

```bash
git submodule init
git submodule update
```

## Etapa 2: Atualizando os submódulos

Caso os submódulos estejam desatualizados em relação aos seus repositórios de origem, o seguinte comando deve ser rodado:

```bash
git submodule update --remote
```

## Etapa 3: Executando cada Projeto Localmente

Visite o ReadME de cada submódulo para mais informações sobre como executá-lo localmente:

- [Hardware](https://github.com/GabZamba/LabDigII-Projeto-Hardware#readme)
- [Firmware](https://github.com/GabZamba/LabDigII-Projeto-Firmware#readme)
- [BackEnd](https://github.com/jvtdegelo/LabDigII-Projeto-BackEnd#readme)
- [FrontEnd](https://github.com/GabZamba/LabDigII-Projeto-FrontEnd#readme)

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<br>

### *PARABÉNS, VOCÊ CONSEGUIU EXECUTAR O PROJETO 🎉🎉🎉*

<br>

# Contribuintes ✨

Agradecimentos vão às seguintes pessoas ([guia dos emojis](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/GabZamba"><img src="https://avatars.githubusercontent.com/u/98465378?v=4?s=100" width="100px;" alt="Gabriel Zambelli"/><br /><sub><b>Gabriel Zambelli</b></sub></a><br /><a href="https://github.com/PedroDeSanti/FlightOps/commits?author=GabZamba" title="Code">💻</a> <a href="https://github.com/PedroDeSanti/FlightOps/commits?author=GabZamba" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/jvtdegelo"><img src="https://avatars.githubusercontent.com/u/64590453?v=4?s=100" width="100px;" alt="jvtdegelo"/><br /><sub><b>jvtdegelo</b></sub></a><br /><a href="https://github.com/PedroDeSanti/FlightOps/commits?author=jvtdegelo" title="Code">💻</a> <a href="https://github.com/PedroDeSanti/FlightOps/commits?author=jvtdegelo" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/PedroDeSanti"><img src="https://avatars.githubusercontent.com/u/62271285?v=4?s=100" width="100px;" alt="Pedro de Santi"/><br /><sub><b>Pedro de Santi</b></sub></a><br /><a href="https://github.com/PedroDeSanti/FlightOps/commits?author=PedroDeSanti" title="Code">💻</a> <a href="https://github.com/PedroDeSanti/FlightOps/commits?author=PedroDeSanti" title="Documentation">📖</a></td>
    </tr>
  </tbody>
  <tfoot>
    
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

Esse projeto segue a especificação do [all-contributors](https://github.com/all-contributors/all-contributors). Contribuições de qualquer tipo são sempre bem-vindas!
