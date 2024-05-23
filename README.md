# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Sensor de frquência cardíaca e oxímetro

## Grupo 5 

## Integrantes: Gustavo Cunha Fernandes, Isabela Nunes Zeferino e Matheus Alves Gas.

## Professores Orientadores: Victor Bruno Alexander Rosetti de Quiroz, Adriano Valentea, Eduardo Savino Gomes.

## Descrição: Desenvolvemos um dispositivo que combina um sensor de frequência cardíaca e oxímetro, conectado ao aplicativo Blynk por meio do ESP32. Esse sistema permite aos médicos monitorarem os sinais vitais de seus pacientes em tempo real, facilitando o acompanhamento dos batimentos cardíacos e dos níveis de oxigênio no sangue à distância.

<p align="center">
<img src="https://pix4free.org/assets/library/2021-01-20/originals/game.jpg" alt="NOME DO JOGO" border="0">
  Game by <a href="http://www.nyphotographic.com/">Nick Youngson</a> <a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a> <a href="http://pix4free.org/">Pix4free</a>
</p>


De um a dois parágrafos sobre o que é seu projeto e o que ele faz.
<br><br>
Dispositivo capaz de medir a frequência cardíaca e o oxigenio do sangue de uma pessoa de forma contínua ou periódica. Ele
utiliza sensores ópticos ou elétricos para capturar os batimentos cardíacos e o oxigênio do sangue. Assim que detecta uma
anomalia, o sensor envia os dados coletados para um banco de dados por meio de uma conexão sem fio, como Bluetooth ou Wi-Fi.
No banco de dados, esses dados podem ser armazenados e posteriormente analisados por profissionais de saúde ou pesquisadores.
Essa análise pode ajudar a identificar problemas cardíacos e de oxigenio no sangue.
<br><br>
<br><br>

## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Documentação.docx<br>
|-->executáveis<br>
  &emsp;|-->windows<br>
  &emsp;|-->android<br>
  &emsp;|-->HTML<br>
|-->imagens<br>
|-->src<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

## 🛠 Equipamentos e aplicativos utilizados 

<b>Hardware:</b>
<br>-Protoboard</br>
<br>-5 fios jumpers </br>
<br>-Sensor MAX30100</br>
<br>-ESP32</br>


<b>Software:</b>
<br>-Arduino IDE</br>
<br>-Blynk</br>


## 🛠 Instalação

<b>Blynk:</b>

Faça o Download do aplicativo Blynk em seu celular e siga as instruções de seu telefone ou abra no navegador.
<br>Crie sua conta > Zona do desenvolvedor > Crie seu modelo > Datastreams: defina um pino virtual V4 e V5 para BPM e SPO2 > Painel de controle web : adicione dois medidores e atribua os pinos virtuais a eles. </br>

Conectando o WI-FI ao ESP32: 
<br> Vá em Ajuda > Início ráido > Vamos lá<br/>

```sh
https://blynk.io/
```

<b>arduino IDE:</b>

Faça o download do software do Arduino IDE 
<br> Vá em software >
Arduino IDE 2.3.2 > Baixe a pasta Zip de acordo com seu sistema operacinal.<br/>

```sh
https://www.arduino.cc/en/software
```

Para instalar biblioteca do ESP32:
<br><br/>

Para instalar biblioteca do MAX30100:
<br><br/>

Para instalar biblioteca do Blynk:
<br><br/>

<b>HTML:</b>

Não há instalação!
Encontre o index.html na pasta executáveis e execute-o como uma página WEB (através de algum browser).

## 💻 Configuração para Desenvolvimento

Descreva como instalar todas as dependências para desenvolvimento e como rodar um test-suite automatizado de algum tipo. Se necessário, faça isso para múltiplas plataformas.

Para abrir este projeto você necessita das seguintes ferramentas:

-<a href="https://godotengine.org/download">GODOT</a>

```sh
make install
npm test
Coloque código do prompt de comnando se for necessário
```

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.

* 0.2.1 - 25/01/2022
    * MUDANÇA: Atualização de docs (código do módulo permanece inalterado)
* 0.2.0 - 15/01/2022
    * MUDANÇA: Remove `setDefaultXYZ()`
    * ADD: Adiciona `init()`
* 0.1.1 - 11/01/2022
    * CONSERTADO: Crash quando chama `baz()` (Obrigado @NomeDoContribuidorGeneroso!)
* 0.1.0 - 10/01/2022
    * O primeiro lançamento adequado
    * MUDANÇA: Renomeia `foo()` para `bar()`
* 0.0.1 - 01/01/2022
    * Trabalho em andamento

## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-1-NADS1-A/Projeto5">Sensor de frequência cardíaca e oxímetro</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/2024-1-NADS1-A/Projeto5">FECAP, GUSTAVO CUNHA FERNANDES, ISABELA NUNES ZEFERINO, MARIA GABRIELA DE OLIVEIRA MARTINS DA SILVA, MATHEUS ALVES GAS</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. <https://github.com/iuricode/readme-template>
2. <https://github.com/gabrieldejesus/readme-model>
3. <https://creativecommons.org/share-your-work/>
4. <https://freesound.org/>
5. Músicas por: <a href="https://freesound.org/people/DaveJf/sounds/616544/"> DaveJf </a> e <a href="https://freesound.org/people/DRFX/sounds/338986/"> DRFX </a> ambas com Licença CC 0.
