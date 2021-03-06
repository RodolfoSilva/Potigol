# Linguagem Potigol

[![Join the chat at https://gitter.im/potigol/Potigol](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/potigol/Potigol?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Follow us](https://img.shields.io/twitter/follow/potigol.svg?style=social)](http://twitter.com/potigol)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2b0637491b834a229351fab7fd897dfc)](https://www.codacy.com/app/leonardo-lucena-71/Potigol?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=potigol/Potigol&amp;utm_campaign=Badge_Grade)

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.53192.svg)](http://dx.doi.org/10.5281/zenodo.53192)

Linguagem de Programação moderna para iniciantes



##Características
  - Sintaxe simples
  - Palavras Chave em Português
  - Tipagem Estática e forte
  - Inferencia de tipos
  - Multiparadigma
  - Encoraja a programação funcional

![Editor](https://cloud.githubusercontent.com/assets/303460/8604675/7180d638-2656-11e5-9239-90d29628d9d0.png)


##Como usar:
  - Baixe a versão mais recente do Potigol https://github.com/potigol/Potigol/releases
  - Descompacte o arquivo
  - Para executar o Editor de Código digite no prompt do terminal
  
  ````java -jar epotigol.jar````

  - Para executar um programa em Potigol digite no prompt do terminal

  ````java -jar potigol.jar arquivo.poti````

  - No Windows basta usar ````epotigol```` ou ````potigol arquivo.poti````.
  
Exemplos: https://github.com/potigol/Potigol/wiki/jogos

##Editores de Código

Editores de código para Potigol:

  - [x] [Editor Potigol](https://github.com/potigol/EditorPotigol) (já incluido na versão executável de Potigol)
  - [x] [JCEditor](https://github.com/cristian-henrique/JCEditor)
  - [x] [Plugin](https://github.com/potigol/language-potigol) para o [Atom](https://atom.io)
  - [x] [Plugin](https://github.com/nfischer/vim-potigol) para o [Vim](http://www.vim.org/)

# Instalação

##Windows 8 e 10

  - Baixe a versão mais nova do Potigol: https://github.com/potigol/Potigol/releases
  - Descompacte o arquivo e copie a pasta Potigol para c:\potigol
  - Envie um atalho de "epotigol.jar" para a área de trabalho.
  - Altere o nome do atalho para "Editor Potigol"
  - Em propriedades altere o ícone. Escolha o icone em cores que está na pasta do potigol.
  - Envie um atalho de C:\Windows\System32\cmd.exe para a área de trabalho.
  - Em propriedade altere:
  - 
 >   Destino: %windir%\system32\cmd.exe /E:ON /K C:\potigol\configpotigol.bat

 > Iniciar em: [Vazio]

 > Alterar ícone. Escolha o icone em preto e branco.

  - Usando o botão direito do mouse escolha a opção "Fixar na Tela Inicial".


##LINUX

  - Baixe a versão mais nova do Potigol: https://github.com/potigol/Potigol/releases
  - Copie a pasta Potigol para o local adequado
  - Insira as linhas abaixo no final do arquivo /etc/bash.bashrc

>   ````alias potigol='java -jar [caminho até a pasta do potigol]/potigol.jar'````

>   ````alias epotigol='java -jar [caminho até a pasta do potigol]/epotigol.jar'````

  - Crie o arquivo '~/Área de Trabalho/potigol_lancador.desktop'
    
````
[Desktop Entry]
Name=Potigol
Type=Application
Exec=java -jar [caminho até a pasta do potigol]/epotigol.jar
Icon=[caminho até a pasta do potigol]/potigol.png
````
