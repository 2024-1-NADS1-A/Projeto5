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
  Projeto interdisciplinar feito por: Gustavo Cunha Fernandes, Isabela Nunes Zeferino e Matheus Alves Gas.
</p>


Para que serve o projeto.
<br><br>
O projeto consiste em um dispositivo que monitora continuamente ou periodicamente a frequência cardíaca e os níveis de oxigênio no sangue. Ele utiliza o sensor MAX30100, que é capaz de capturar os batimentos cardíacos e a saturação de oxigênio no sangue por meio de sensores ópticos.<br>

<br>Quando são registradas as leituras, incluindo os batimentos por minuto (BPM) e a saturação periférica de oxigênio (SpO2), esses dados são enviados sem fio para um layout no Blynk. Esta interface é projetada para visualização por médicos e profissionais de saúde.<br>

<br>Através dessa interface, os médicos podem acessar e analisar em tempo real as informações vitais dos pacientes. Isso permite uma monitoração contínua e a identificação rápida de quaisquer anormalidades nos sinais vitais, facilitando a tomada de decisões médicas.<br>

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
<br>-cabo USB</br>

<b>Software:</b>
<br>-Arduino IDE</br>
<br>-Blynk</br>


## 🛠 Instalação

<b>Blynk:</b>

Faça o Download do aplicativo Blynk em seu celular e siga as instruções de seu telefone ou abra no navegador.

<br>Crie sua conta -> Zona do desenvolvedor -> Crie seu projeto:tocando no botão "+" ou no botão de adicionar projeto. Dê um nome ao seu projeto e selecione o dispositivo que você usará com o Blynk. -> Datastreams: defina um pino virtual V4 e V5 para BPM e SPO2 -> Painel de controle web : adicione widgets tocando no botão de "+" no canto superior direito. Adicione dois medidores e atribua os pinos virtuais a eles. -> Conectando seu Dispositivo: você precisará de um token de autenticação. Este token é gerado pelo aplicativo Blynk e é único para cada projeto. No aplicativo, toque no botão QR no canto superior direito do editor para visualizar o token. Você precisará inserir esse token no código do seu dispositivo para estabelecer a conexão com o Blynk. </br>

Conectando o WI-FI ao ESP32: 
<br> Vá em Ajuda -> Início ráido -> Vamos lá<br/>

```sh
https://blynk.io/
```

<b>arduino IDE:</b>

Faça o download do software do Arduino IDE 
<br> Vá em software ->
Arduino IDE 2.3.2 -> Baixe a pasta Zip de acordo com seu sistema operacinal.<br/>

```sh
https://www.arduino.cc/en/software
```


## 💻 Configuração para Desenvolvimento

Para instalar biblioteca do ESP32:
<br>Abra a IDE do Arduino.
No menu, vá para "Sketch" -> "Incluir Biblioteca" -> "Gerenciar Bibliotecas...".
Na janela que se abre, digite "ESP32" na barra de pesquisa.
Localize a biblioteca "ESP32" na lista e clique no botão "Instalar" ao lado dela.
Após a instalação, você pode usar a biblioteca em seus projetos selecionando-a em "Sketch" -> "Incluir Biblioteca".<br/>

Para instalar biblioteca do MAX30100:
<br>Abra a IDE do Arduino.
No menu, vá para "Sketch" -> "Incluir Biblioteca" -> "Gerenciar Bibliotecas...".
Na janela que se abre, digite "MAX30100" na barra de pesquisa.
Localize a biblioteca "MAX30100" na lista e clique no botão "Instalar" ao lado dela.
Após a instalação, você pode usar a biblioteca em seus projetos selecionando-a em "Sketch" -> "Incluir Biblioteca".<br/>

Para instalar biblioteca do Blynk:
<br>Abra a IDE do Arduino.
No menu, vá para "Sketch" -> "Incluir Biblioteca" -> "Gerenciar Bibliotecas...".
Na janela que se abre, digite "Blynk" na barra de pesquisa.
Localize a biblioteca "Blynk" na lista e clique no botão "Instalar" ao lado dela.
Após a instalação, você pode usar a biblioteca em seus projetos selecionando-a em "Sketch" -> "Incluir Biblioteca".<br/>

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.


* 0.3.0 - 22/05/2024
terminamos o projeto completo.
* 0.2.1 - 20/05/2024
resolvemos a biblioteca e outros erros do código, e criamos o github
* 0.2.0 - 06/05/2024
nós juntamos e resolvemos a parte da montagem e aplicativo.
* 0.1.1 - 26/04/2024
dividimos as tarefas que precisariam ser feitas
* 0.1.0 - 08/04/2024
pesquisamos o Arduino e sensor que precisavamos, após decidirmos o tema do trabalho.
0.0.1 - 15/03/2024
decidimos o que iriamos fazer no projeto


## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-1-NADS1-A/Projeto5">Sensor de frequência cardíaca e oxímetro</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/2024-1-NADS1-A/Projeto5">FECAP, GUSTAVO CUNHA FERNANDES, ISABELA NUNES ZEFERINO, MARIA GABRIELA DE OLIVEIRA MARTINS DA SILVA, MATHEUS ALVES GAS</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências


Aqui estão as referências usadas no projeto.

1. <https://youtu.be/BSuCI8BeJC0?si=F_OfQYYOBKOwrwZg>
2. <https://theiotprojects.com/>
3. <https://github.com/gabrieldejesus/readme-model>
4. <https://creativecommons.org/share-your-work/>
5. <https://freesound.org/>
6. Músicas por: <a href="https://freesound.org/people/DaveJf/sounds/616544/"> DaveJf </a> e <a href="https://freesound.org/people/DRFX/sounds/338986/"> DRFX </a> ambas com Licença CC 0.
