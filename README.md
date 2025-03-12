# 🏠 Smart Home - IOT PROJECT

## 📌 O que é esse projeto?
Imagine uma casa que praticamente "pensa" por você! Esse projeto é sobre automação residencial, onde eu uso um ESP8266, alguns sensores legais e outros componentes para controlar luzes, temperatura, segurança e até o portão da garagem. O objetivo? Deixar tudo mais prático, confortável, econômico e seguro. Vou te mostrar a seguir:

## 🚀 O que essa casa sabe fazer?

### 1️⃣ **Portão esperto pra carros** 🚗
- **O que usei:**
  - Um sensor RFID 🏷️ (aquele das tags mágicas)
  - Um buzzer 📢 (pra fazer barulhinho)
  - Luzes RGB 🌈 (porque cor é vida)
  - Um servo motor 🤖 (o "músculo" do portão)
- **Como funciona:**
  - Quando o carro chega, o RFID lê a tag.
  - **Se for a tag certa**:
    - O portão abre sozinho 🔓.
    - A luz fica verde 🟩 quando tá fechado e vermelha 🔴 quando abre.
    - Faz um som tipo "bip-bip" 🔊 pra avisar.
    - Depois de 1,5 segundo, acende a luz da garagem 💡.
  - **Se a tag for errada**:
    - Nada acontece, o portão fica fechadinho e, depois de 5 segundos, ele tranca de novo.

### 2️⃣ **Luzes que acendem sozinhas** 💡
- **O que usei:**
  - Três sensores de presença 👀 (um pra cada canto)
  - LEDs RGB 🌈 (pra dar aquele charme)
- **Como funciona:**
  - Passou pela sala, quarto ou quintal? As luzes acendem na hora!
  - Saiu do ambiente? Elas apagam sozinhas. Prático, né?

### 3️⃣ **Temperatura na medida certa** 🌡️
- **O que usei:**
  - Um sensor de temperatura 🌡️
- **Como funciona:**
  - Tá muito quente? A luz fica azul ❄️ pra mostrar que tá esfriando.
  - Tá friozinho demais? A luz vira vermelha 🔥 pra aquecer o clima.

### 4️⃣ **Luz que se ajusta ao dia** ☀️
- **O que usei:**
  - Um sensor de luminosidade 📟
  - Um LED simples 🔲
- **Como funciona:**
  - Tá escuro? A luz acende 💡 pra te ajudar a enxergar.
  - Tá claro? Ela apaga 🌑 pra economizar energia.

## 🛠️ Como eu fiz isso?
- **Cérebro da operação**: ESP8266 (um microcontrolador esperto).
- **Sensores**:
  - RFID pra reconhecer o carro.
  - Sensores de presença (PIR) pra "ver" quem tá por aí.
  - Sensor de temperatura (DHT11 ou DHT22).
  - Sensor de luz (LDR) pra medir o brilho.
- **Ação**:
  - LEDs RGB e simples pra iluminar.
  - Servo motor pro portão.
  - Buzzer pra fazer barulho.
- **Código**: Escrevi tudo em C++ usando o Arduino.
- **Ferramentas**: Arduino IDE e, quem sabe no futuro, o Home Assistant.

## 🏗️ Como montar sua própria casa inteligente
### ✅ O que você precisa antes
- Um ESP8266 configuradinho.
- Sensores e componentes ligados direitinho (tem um esquema pra seguir).
- Arduino IDE com a biblioteca do ESP8266 e outras como `ESP8266WiFi.h`, `Servo.h` e `DHT.h`.

### 🔌 Passo a passo
1. **Pegue o código:**
   ```bash
   git clone https://github.com/seu-usuario/smart-home.git
   ```
2. Abra na Arduino IDE e instale as bibliotecas.
3. Se for usar Wi-Fi, coloque sua senha no código.
4. Faça o upload pro ESP8266.
5. Monte o circuito (siga o esquema que eu vou deixar pronto depois).
6. Ligue tudo e teste pra ver a mágica acontecer!

## 📜 Mapa dos cabos (Wiring Diagram)
> 🔧 Ainda tô desenhando isso direitinho, mas logo coloco um esquema bem explicado!

## 🏡 O que vem por aí?
- Quero conectar tudo ao **Home Assistant** pra mexer pelo celular 📱.
- Fazer um painel pra ver temperatura e outras coisas em tempo real.
- Controlar tudo por app ou pela web.
- Quem sabe até colocar comandos de voz com **Google Assistant** ou **Alexa**?

## 🤝 Quer ajudar?
Adoraria ter você no time! Se quiser dar uma força:
1. Faça um **fork** do projeto.
2. Crie uma **branch** com sua ideia.
3. Mande um **pull request** contando o que você mudou.

## 📄 Licença
Isso aqui tá sob a **MIT License** – pode usar, mexer e adaptar à vontade!

## 📞 Meus Contatos
Dúvidas ou ideias? Me chama:
- ✉️ **Email**: julianof29contato@gmail.com
- 🔗 **GitHub**: [julianosfreitas](https://github.com/julianosfreitas)

---
🚀 **Feito com carinho por Juliano, Adauto e equipe Smart Home Automation**
