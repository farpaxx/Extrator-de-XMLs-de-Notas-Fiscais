# Extrator de XMLs de Notas Fiscais

Um aplicativo web para extrair, visualizar e analisar dados de arquivos XML de Notas Fiscais Eletrônicas (NF-e). Ideal para contadores, empresas e profissionais que precisam gerenciar grandes volumes de documentos fiscais.

![Badge](https://img.shields.io/badge/Versão-1.0-blue) ![Badge](https://img.shields.io/badge/Licença-GPLv3-green)
(DESENVOLVIMENTO PARADO)

## 📋 Funcionalidades

- **Extração de dados**: Importação de arquivos XML de NF-e com extração automática de informações relevantes
- **Dashboard analítico**: Visualização gráfica dos dados com estatísticas gerais
- **Evolução mensal**: Gráfico de tendência mostrando a evolução dos valores e impostos ao longo do tempo
- **Comparativo de impostos por CFOP**: Análise detalhada de impostos por operação fiscal
- **Análise fiscal**: Relatórios detalhados de impostos (ICMS, IPI, PIS, COFINS)
- **Exportação para CSV**: Exportação personalizada de dados com suporte para a chave de acesso da NF-e
- **Visualização de detalhes**: Informações completas de cada nota fiscal, incluindo a chave de acesso

## 🖼️ Screenshots

[Dashboard](https://via.placeholder.com/800x400?text=Dashboard+do+Extrator+de+NFe)![image](https://github.com/user-attachments/assets/8d40f354-f84c-4ae0-ae59-388acb79d2fa)

[Análise Fiscal]
![image](https://github.com/user-attachments/assets/345ce12a-465e-4c9e-bea3-116fc8c75c07)


## 🚀 Tecnologias utilizadas

- HTML5, CSS3 e JavaScript
- [Bootstrap](https://getbootstrap.com/) - Framework CSS para interface responsiva
- [Chart.js](https://www.chartjs.org/) - Biblioteca para criação de gráficos
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - Banco de dados no navegador

## 💻 Como usar

### Instalação local

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/extrator-nfe.git
```

2. Abra o arquivo `index.html` em um navegador moderno:
```bash
cd extrator-nfe
# Abra o arquivo index.html no seu navegador
```

### Uso na nuvem

Acesse a versão online em: (https://deepia.com.br/extrator_xml/#)

### Guia rápido

1. Clique em "Escolher arquivos" para selecionar os XMLs de NF-e
2. Clique em "Extrair Dados" para processar os arquivos
3. Explore as diferentes abas do dashboard
4. Use a aba de exportação para baixar os dados em formato CSV

## 📊 Recursos do dashboard

- **Resumo**: Visão geral com estatísticas e totalizadores
- **Por Destinatário**: Análise de notas agrupadas por cliente
- **Por Tipo**: Visualização de dados por tipo de documento
- **Análise Fiscal**: Relatórios detalhados de impostos
- **Dados Completos**: Lista de todas as notas com filtros
- **Exportação**: Geração de relatórios personalizados em CSV

## 🔑 Chave de acesso da NF-e

Implementação especial para garantir a exibição e exportação correta da chave de acesso da NF-e de 44 dígitos, sem conversão para notação científica.

## 🛠️ Requisitos técnicos

- Navegador moderno com suporte a JavaScript ES6+
- Suporte a IndexedDB
- Conexão com internet para carregar bibliotecas externas (Bootstrap, Chart.js, FontAwesome)

## 📄 Licença

Este projeto está licenciado sob a GNU General Public License v3 (GPLv3) - uma licença de software livre que garante:

- A liberdade de usar o software para qualquer finalidade
- A liberdade de estudar como o programa funciona e adaptá-lo às suas necessidades
- A liberdade de redistribuir cópias
- A liberdade de melhorar o programa e liberar seus aprimoramentos para o público

A GPLv3 exige que qualquer software derivado também seja disponibilizado sob a mesma licença, garantindo que todas as melhorias permaneçam livres.

Veja o arquivo [LICENSE](LICENSE) para o texto completo da licença.

## 📞 Contato

Para dúvidas ou sugestões, entre em contato:
- Email: [luiz.pacheco@deepia.com.br](mailto:luiz.pacheco@deepia.com.br)
- GitHub: [@seu-usuario](https://github.com/farpaxx)

---

Desenvolvido por [Farpaxx](https://github.com/farpaxx) - 2025
