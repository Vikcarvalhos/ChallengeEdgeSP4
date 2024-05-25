# ComPasso - Sprint 4 - Edge

# Descrição
Esse é um projeto em IoT utilizado para a solução apresentada ao Hospital das Clinicas, nomeada de ComPasso.
A solução em IoT tem como foco cadastrar usuários utilizando a tecnologia de RFID para fornecer cartões a cada um dos pacientes.
Ao realizar a leitura do cartão, será enviado um link no Whatsapp relacionado as informações de cada usuário.

## Componentes Necessários
- Arduino Uno
- Leitor RFID
- Breadboard
- Cartão RFID
- Fios

## Conexões Obrigatórias do RFID
- SDA -> D10
- SCK -> D13
- MOSI -> D11
- MISO -> D12
- RST -> D9

## Alimentação do RFID
- 3.3v
- GND

## Bibliotecas
- MFRC522 by GithubCommunity
