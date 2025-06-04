# 📱 Aplicativo de Monitoramento Veicular

Este repositório contém um aplicativo desenvolvido em Flutter como parte de um projeto de mestrado. O aplicativo tem como objetivo a coleta de dados veiculares por meio da interface OBD-II e o envio dessas informações para o Firebase, possibilitando a análise e rastreamento de comportamento veicular.

## 🚀 Tecnologias Utilizadas

- **Flutter** – Framework para desenvolvimento multiplataforma.
- **Dart** – Linguagem de programação utilizada com Flutter.
- **Firebase** – Backend para autenticação e banco de dados em nuvem.

## ✨ Funcionalidades

- 📡 Conexão com dispositivos OBD-II via Bluetooth.
- 🚗 Coleta de dados veiculares em tempo real (ex: velocidade, rotação do motor).
- 🧠 Processamento e exibição dos dados coletados na interface do usuário.
- ☁️ Envio automático dos dados para o AWS Cloud.
- 🧾 Registro de dados com informações como:
  - Localização GPS
  - Foto da bomba de combustível
  - Valores simulados ou obtidos de sensores
- 👤 Interface para condutores com visualização simplificada.
- 📶 Detecção de falhas na comunicação com o veículo.
- 🗂️ Armazenamento local temporário dos dados quando offline.

## 📂 Estrutura do Projeto

- `lib/` – Código-fonte principal do aplicativo.
- `android/` e `ios/` – Configurações específicas para as plataformas.
- `assets/` – Imagens e recursos estáticos.
- `pubspec.yaml` – Gerenciador de dependências e configuração de recursos.

## 🛠️ Como Executar

Siga os passos abaixo para clonar e executar o projeto localmente:

```bash
git clone https://github.com/gabestk/app_mestrado.git
cd app_mestrado
flutter pub get
flutter run
