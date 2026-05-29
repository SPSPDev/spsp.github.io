 Treinamento de Segurança — Phishing Corporativo

Material de conscientização sobre ataques de phishing com exemplos práticos via E-mail, WhatsApp e Microsoft Teams.
Desenvolvido para o ambiente corporativo da SPSP.


📋 Sobre o Projeto
Este projeto é um treinamento interativo de conscientização em segurança da informação, focado na identificação e prevenção de ataques de phishing no ambiente corporativo da SPSP.
O material foi desenvolvido como uma aplicação web estática (HTML/CSS/JS puro), sem dependências externas, para facilitar a distribuição interna e a hospedagem via GitHub Pages.
EmpresaSPSPResponsávelMurilo — Gerente de TIVersão1.0Ano2025

🎯 Conteúdo do Treinamento
O material está organizado em 6 módulos:
1. Introdução

Definição operacional de phishing
Modalidades de ataque (Phishing, Spear Phishing, Whaling, Smishing, BEC)
Por que o colaborador é o principal vetor de ataque

2. Phishing por E-mail

Exemplo 1 — Falsa notificação Microsoft (typosquatting de domínio)
Exemplo 2 — Fraude do CEO / BEC (Business Email Compromise)

3. Phishing via WhatsApp

Exemplo 1 — Falso Departamento de RH solicitando atualização de benefícios
Exemplo 2 — Falso Suporte de TI solicitando credenciais do AD

4. Phishing via Microsoft Teams

Exemplo 1 — Conta externa comprometida com link falso de SharePoint
Exemplo 2 — Canal falso de TI solicitando recadastro de MFA

5. Resposta a Incidentes

Protocolo de 5 etapas para resposta a incidentes de phishing
Checklist interativo de boas práticas preventivas

6. Quiz de Conhecimentos

5 questões práticas com feedback educativo imediato
Baseadas nos cenários apresentados nos módulos anteriores


🚀 Como Utilizar via GitHub Pages
Pré-requisitos

Conta no GitHub (gratuita)
O arquivo treinamento-phishing.html deste repositório

Passo a Passo
1. Criar o repositório
GitHub → New Repository → Nome: treinamento-phishing-spsp → Public → Create
2. Fazer upload do arquivo

Na página do repositório, clique em "Add file" → "Upload files"
Faça o upload do arquivo treinamento-phishing.html
Renomeie para index.html antes do upload (ou renomeie após)
Adicione uma mensagem de commit: Adiciona material de treinamento v1.0
Clique em "Commit changes"

3. Ativar o GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → Branch: main → / (root) → Save
4. Aguardar o deploy

O GitHub leva entre 1 a 3 minutos para publicar
A URL ficará disponível em:

https://SEU_USUARIO.github.io/treinamento-phishing-spsp
5. Compartilhar com os colaboradores

Copie a URL gerada e distribua via e-mail corporativo ou Teams
O link funciona em qualquer navegador, sem necessidade de login ou instalação


🔒 Considerações de Segurança

O material é somente leitura — nenhum dado do colaborador é coletado ou enviado
Não há backend, banco de dados ou processamento de informações pessoais
O repositório pode ser configurado como privado (requer GitHub Pro para Pages privado) ou mantido público
Para ambientes com restrição de acesso à internet, consulte a opção de hospedagem via IIS interno

Opção de Repositório Privado
Para manter o conteúdo restrito apenas a colaboradores da SPSP, configure o repositório como Private e utilize o GitHub Organizations ou distribua o arquivo diretamente via rede interna.

🗂 Estrutura do Repositório
treinamento-phishing-spsp/
│
├── index.html          # Aplicação principal do treinamento
└── README.md           # Este arquivo

🛠 Tecnologias Utilizadas
TecnologiaUsoHTML5Estrutura e conteúdoCSS3Estilização e layout responsivoJavaScript (Vanilla)Interatividade (quiz, checklist, abas)Google Fonts (IBM Plex)Tipografia

Sem frameworks, sem dependências de npm, sem build necessário.
O arquivo index.html é autocontido e funciona diretamente no navegador.


📱 Compatibilidade
NavegadorSuporteGoogle Chrome✅ CompletoMicrosoft Edge✅ CompletoMozilla Firefox✅ CompletoSafari (macOS/iOS)✅ CompletoInternet Explorer 11⚠️ Parcial (não recomendado)
O layout é responsivo e funciona em dispositivos móveis e tablets.

📝 Manutenção e Atualizações
Para atualizar o conteúdo do treinamento:

Edite o arquivo index.html localmente
Acesse o repositório no GitHub
Clique no arquivo index.html → ícone de lápis (editar) → cole o novo conteúdo
Commit com mensagem descritiva: Atualiza exemplo de phishing via Teams - v1.1
O GitHub Pages publica automaticamente em até 3 minutos


⚠️ Aviso Legal
Este material é de uso exclusivo interno da SPSP para fins educacionais e de conscientização em segurança da informação. Os exemplos apresentados são simulações didáticas — nenhuma das mensagens ou links demonstrados é real ou funcional.
A reprodução ou distribuição deste material fora do ambiente corporativo da SPSP sem autorização prévia da Gerência de TI é vedada.

Desenvolvido pela TI — SPSP · 2026
