### As máquinas também sonham: bots para Twitter
---

### Bemvindes :)

Nesta oficina vamos criar bots para Twitter utilizando gramática ou arte generativa + Tracery + Cheap bots done quick.

Eu sou Steffania Paola, ativista feministas, desenvolvedora web, designer gráfica, artista visual e facilitadora de processos de aprendizagem em cuidados digitais. Colaboro com diversas organizações latinoamericanas. Fui bolsista da Fundação Mozilla (FORD-Mozilla Open Web Fellowship 2016-2017) na Derechos Digitales - Chile.
Sou parte da coletiva acoso.online, co-fundadora da servidora feministas clandestina.io, parte das redes ciberseguras.org e Rede transfeminista de cuidados digitais, e co-editora da teteia.org.

[@stepaola](https://twitter.com/stepaola) / stepaola.github.io/

---


### O que é um bot?

[![N|Solid](https://media.giphy.com/media/UH9QKcraNtbxK/giphy.gif)](https://nodesource.com/products/nsolid)

Bot, diminutivo de robot, também conhecido como Internet bot ou web robot, é uma aplicação de software concebido para simular ações humanas repetidas vezes de maneira padrão, da mesma forma como faria um robô. No contexto dos programas de computador, pode ser um utilitário que desempenha tarefas rotineiras ou, num jogo de computador, um adversário com recurso a inteligência artificial.

No Twitter um conjunto de bots é chamado de "granja de bots". Raramente são influentes, mas ajudam a gerar termos em "trending topics" - termos que o Twitter considera "quentes" em certo momento e que são destacados na plataforma - ou a gerar ruído sobre um tema (Chequeado)

<br/><br/>

#### Bots x Trolls

Um troll é alguém focado em criticar e antagonizar de maneira provocativa e depreciativa algo ou alguém. A palavra originalmente se refere a personagens folclóricos que vivem nas cavernas da Escandinávia. (Chequeado)

<br/><br/>



### Usos e possibilidades para uma internet feminista: diversão + luta

- [@Botota](https://twitter.com/bototadice)
![enter image description here](https://i.imgur.com/ELUB0RA.jpg)
<br/><br/>

- [@lachakalarixxo](https://twitter.com/LACHAKALARIXXO)
![](https://i.imgur.com/xfQik76.jpg)

<br/><br/>
- [@DominemoslasTIC](https://twitter.com/DominemoslasTIC)
![enter image description here](https://i.imgur.com/8pKxtOR.png)

<br/><br/>
- [Acoso.online Bot para Telegram](https://acoso.online/cl/chat-de-ayuda/)

![enter image description here](https://media.giphy.com/media/jtv3zdHN5DqPQ1j6Fy/giphy.gif)

<br/><br/>
- [Beta, Bot para Facebook](bit.ly/chamabetanoinbox)
![enter image description here](https://i.imgur.com/2IIc6Zb.jpg)

<br/><br/>
- [@clitoscope](https://twitter.com/clitoscope)
![N|Solid](https://i.imgur.com/VouA6ki.jpg)

<br/><br/>
- [@softlandscapes](https://twitter.com/softlandscapes)
![enter image description here](https://i.imgur.com/iF6i8Qe.png)

<br/><br/>
---
### Nossa bot

Vamos utilizar neste tutorial a teoria chamada "gramática generativa" para criação do nosso bot. 


#### O que é uma gramática generativa?

[![N|Solid](https://media.giphy.com/media/qccVJBDT6xNqU/giphy.gif)](https://nodesource.com/products/nsolid)

Gramática generativa é um modelo gramatical cujo objetivo é formular as regras e princípios por meio dos quais uma falante é capaz de produzir e compreender todas as orações possíveis e aceitáveis de uma língua.
Noam Chomsky define essa teoria como capaz de dar conta da criatividade do falante, de sua capacidade de emitir e de compreender frases inéditas. 
Nessa perspectiva, a gramática é um mecanismo finito que permite gerar (engendrar) o conjunto infinito das frases gramaticais (bem formadas, corretas) de uma língua, e somente elas. Formada de regras que definem as sequências de palavras ou de sons repetidos, essa gramática constitui o saber linguístico dos indivíduos que falam uma língua, isto é, a sua competência linguística. (Wikipedia)

- Chomskybot: http://rubberducky.org/cgi-bin/chomsky.pl

Ejemplo: 
Supongamos que hay una maquina donde tu eliges algunos colores y tipos de ropas. Todos los días la máquina hace una combinación para ti basado en los tipos de ropas y colores que te gusta. Si con ese concepto creas frases, tenemos un bot basado en una gramática generativa.

<br/><br/><br/>

### Mão na massa

1. Conceito do bot: ideias? 
- Qual será sua '@'
- A foto de capa
- Imagem de perfil
- Descrição

2. [Criar uma conta no Twitter](https://twitter.com/i/flow/signup)

3. (logada no Twitter) Acessar o site: https://cheapbotsdonequick.com/
4. Clicar em "Sign in with Twitter"
5. Clicar em "Autorizar a aplicação"
6. Se você chegou na página abaixo está pronta para criar as regras do seu bot. No espaço depois de "Tracery JSON" é onde vamos escrever o nosso código.

![enter image description here](https://i.imgur.com/RYLoszA.png)

7. Experimentar com um exemplo é a melhor maneira de entender como a ferramenta funciona e a partir de então você pode criar sua prórpia bot. Copie o código abaixo e cole no https://cheapbotsdonequick.com/ e comece a bricar.
~~~~ 
{
"origin": ["Bom dia para #acao# #coisa# com #comque# #lugar# #hashtag# #img#"]
,"acao": ["explodir","?","mastigar","enfeitiçar","?","destruir"]
,"coisa": ["Facebook","o patriarcado","o troll","o sexismo","o racismo", "a lgbtfobia"]
,"comque": ["uma tesoura","criptografia","feminismo","crítica","?","?","?"]
,"lugar": ["na cozinha","no carro","na rua","na universidade","na escola", "na internet"]
,"img": ["{img https://media.giphy.com/media/3OpNkNdOgPBr8kCy6h/giphy.gif}", 
"{img https://media.giphy.com/media/xUA7aO6HnR0VZEGwYE/giphy.gif}", 
"{img https://media.giphy.com/media/3og0Iw2eUAFbUxhaFy/giphy.gif}", 
"{img https://media.giphy.com/media/xUA7aYC5BjDQdKsBmU/giphy.gif}", 
"{img https://media.giphy.com/media/3og0IEk1Eo8LyC7qJa/giphy.gif}", 
"{img https://media.giphy.com/media/3og0INMgArY0dgzh1S/giphy.gif}", 
"{img https://media.giphy.com/media/xUA7bbxuQ6RCSYNEg8/giphy.gif}", 
"{img https://media.giphy.com/media/J344gCW8ZkhylX70kt/giphy.gif}", 
"{img https://media.giphy.com/media/qvOxlBUEzWQdG/giphy.gif}", 
"{img https://media.giphy.com/media/3oEhn78yWS0qRJ1Tag/giphy.gif}" ]
,"hashtag": ["\n\\#InternetFeminista"]
} 
~~~~
- **Em "origin" é onde vem a estrutura da nossa frase**
- **Tudo que está entre "#" em "origin" é o que irá se misturar na frase**

Imagens: https://giphy.com/laurasalaberry, https://giphy.com/martinascott, https://giphy.com/biarritzzz

8. Com o código já inserido na ferramenta, ao clicar no ícone de "atualizar" você poderá visualizar as possíveis combinações do exemplo: 

![enter image description here](https://i.imgur.com/ZcVL3jc.png)

- Se você clicar em "tweet" este texto será publicado na sua conta imediatamente. 

- Onde está "Never" você pode definir a frequência das publicações da sua bot. 
- Em "Don't reply" você tem a possibilidade de escolher se a sua bot vai responder (Reply) ou não responder (Don't reply) quando alguém enviar uma mensagem para ela no Twitter.
- Em "Don't share" você pode escolher se o código que você utilizou será disponibilizado livremente para que outras pessoas possam utilizá-lo (Share) ou não (Don't share)
10. Com tudo pronto você precisa apenas clicar em "SAVE" e assim a sua bot estará ativa na conta de Twitter que você criou para ela.

![N|Solid](https://media2.giphy.com/media/3og0ISTHRg4HSNKTao/giphy.gif)


---

### Extra

- Artbot: http://artbot.combinatorium.com/#!/tracery

Ferramenta para gerar bots com formas e colores. Coloque o código gerado no https://cheapbotsdonequick.com/ e siga os passos do tutorial para publicação do bot no Twitter. 



### Mantendo o seu anonimato 
1. Use o navegador Tor para fazer tudo que esteja relacionado ao seu bot, desde a criação de contas até a criação do bot: https://www.torproject.org/pt-BR/download/
2. Crie um e-mail seguro: https://protonmail.com/ ou https://tutanota.com/pt_br/
3. Cria a conta no Twitter com este novo e-mail (sempre acessando via Tor)
4. Faça todos os passos do tutorial utilizando o navagedor Tor

Importante: o Twitter pede número de telefone no cadastro, mas não é obrigatório. Lembre-se que números de telefone brasileiros estão vinculados a CPFs, então se o seu objetivo é manter-se anonime, não coloque um número de telefone!



---
### Leituras adicionais
- [Escritura Cyborg: las máquinas también sueñan](https://www.genderit.org/es/articles/edicion-especial-escritura-cyborg-las-maquinas-tambien-suenan)
- [Bestiario de bots: un acercamiento a las poéticas de la escritura automática](http://editorial.centroculturadigital.mx/articulo/bestiario-de-bots)
- [El mundo secreto de los bots](http://www.chequeado.com/investigacion/el-mundo-secreto-de-los-bots-y-los-trolls-y-como-esos-ejercitos-influyen-en-la-politica/)
- [You auto-complete me: romancing the bot](https://deepdives.in/you-auto-complete-me-romancing-the-bot-f2f16613fec8)







