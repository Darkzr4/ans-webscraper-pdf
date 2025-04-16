# 📂 ANS Web Scraper - Download e Compactação de PDFs

Script Python para automação de download e organização de documentos públicos da [Agência Nacional de Saúde (ANS)](https://www.gov.br/ans).

## 🛠 Funcionalidades
- Acesso automatizado ao portal da ANS
- Download dos Anexos I e II em PDF
- Compactação em arquivo ZIP único
- Tratamento de erros e logs de execução

## ⚙️ Tecnologias
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Bibliotecas](https://img.shields.io/badge/Libraries-requests%20%7C%20zipfile%20%7C%20os-green)

## 📦 Estrutura do Código
```bash
ans-webscraper-pdf/
├── main.py               # Código principal
├── downloads/            # Pasta de arquivos baixados (auto-criada)
├── anexos.zip            # Arquivo gerado (exemplo)
└── README.md