# 📡 Comunicação UDP em Java ☕
Um projeto simples, direto e sem frescura, que demonstra como dois programas podem trocar mensagens via **UDP**.

## 💡 Sobre o projeto
Este projeto foi desenvolvido com o objetivo de demonstrar o funcionamento básico da comunicação entre processos por meio do protocolo **UDP**, utilizando a API nativa do Java. \
Aqui você encontra um exemplo simples e didático de como enviar e receber datagramas, transmitindo informações de forma rápida e direta entre cliente e servidor.

## ⚙️ Funcionalidades
- Envio e recebimento de mensagens em tempo real.
- Envio contínuo de mensagens por UDP.
- Simulação de sensores: temperatura + umidade.
- Comunicação em rede local extremamente simples e funcional.

## 🧩 Tecnologias Utilizadas
- Java
- Sockets UDP
- Datagramas

## 🛠️ Instalação
**1.** Verifique se o Java está instalado na sua máquina:
> Para confirmar, execute no terminal:
> ```bash
> java -version
> ```
> Caso não esteja instalado, baixe em: [Oracle](https://www.oracle.com/java/technologies/downloads/).

**2.** Baixe ou clone este repositório para o seu computador:
> ```bash
> git clone https://github.com/wxrley/SocketUDP.git
> ```

## 🚀 Execução
#### Opção 1 — Via Terminal
**1.** Entre na raiz do projeto e compile os arquivos:
> ```bash
> javac Server.java Client.java
> ```
**2.** Execute o servidor:
> ```bash
> java Server
> ```
> O console deve exibir:
> ```bash
> Servidor UDP aguardando mensagens...
> ```
**3.** Em outro terminal, execute o cliente:
> ```bash
> java Client
> ```
**4** Saída Esperada:
> Client:
> ```bash
> Enviado -> Sensor1: 25.4°C, Sensor2: 55%RH
> ```
> Server:
> ```bash
> Mensagem recebida: Sensor1: 25.4°C, Sensor2: 55%RH
> ```
> O programa roda continuamente. \
> Para encerrar: `CTRL + C` em cada terminal.

#### Opção 2 — Via IDE (IntelliJ, Eclipse, VS Code, etc.)
**1.** Abra a pasta do projeto na sua IDE preferida. \
**2.** Abra o arquivo `Server.java` e clique em Run para iniciar o servidor. \
**3.** Em seguida, abra o arquivo `Client.java` e execute também com Run. \
**4.** Use o console da IDE para visualizar as mensagens. \
**5.** Para finalizar, apenas pare a execução.

## 👨‍💻 Autor
**Wxrley** — só mais um dev latino americano 💪
