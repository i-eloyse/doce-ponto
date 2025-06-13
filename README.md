🍭 Doce Ponto
Um app para registrar docerias, com upload de fotos, localização e visualização no mapa.
Backend em Node.js + Express + MongoDB.
Frontend em React Native com UI moderna e animações.

📝 Sobre
Doce Ponto é um sistema para você cadastrar docerias que conhece ou deseja visitar, guardando fotos, descrição e localização no mapa. Ideal para amantes de doces e viagens gastronômicas!

🚀 Tecnologias
Backend: Node.js, Express, MongoDB (Atlas), Mongoose, Multer (upload de imagens), CORS
Frontend: React Native, React Navigation, React Native Paper (UI)
Outros: dotenv para variáveis de ambiente, animações com Animated API do React Native

📦 Funcionalidades
Cadastro de docerias com:
Nome
Descrição
Foto (upload e armazenamento local no servidor)
Localização via latitude e longitude
Listagem estilizada com fotos e descrição
Mapa com marcadores das docerias cadastradas
Botões flutuantes (FAB) para adicionar doceria e abrir o mapa
Animações suaves e layout responsivo
Backend REST API com endpoints para GET e POST das docerias
Upload e armazenamento de imagens via Multer
Segurança com variáveis de ambiente para conexão ao banco

📁 Estrutura do projeto

doce-ponto/
├── backend/
│   ├── uploads/         # Fotos salvas
│   ├── .env             # Variáveis de ambiente (não versionado)
│   ├── server.js        # Código do backend Express
│   ├── package.json
│   └── ...
├── frontend/
│   ├── App.js           # Entrada do app React Native
│   ├── screens/         # Telas do app (Home, Mapa, Adicionar Doceria)
│   ├── assets/          # Imagens, ícones etc
│   ├── package.json
│   └── ...
└── README.md

🎨 Design e UI
Paleta de cores rosa e vinho (tons de #f8bbd0, #ad1457, #880e4f) para uma aparência doce e aconchegante
Uso de cards com sombras suaves e bordas arredondadas
Botões flutuantes (FAB) para navegação rápida e intuitiva
Animações de fade-in para lista e carregamento de dados
Ícones temáticos para melhor usabilidade

📝 Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para detalhes.
