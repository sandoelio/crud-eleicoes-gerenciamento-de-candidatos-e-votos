
# CRUD Eleições – Gerenciamento de Candidatos e Votos 🗳️

Sistema básico de votação com funcionalidades para cadastro de candidatos, registro de votos e exibição de resultados de forma dinâmica.

---

## 🔍 Sumário

- [Visão Geral](#visão-geral)  
- [Funcionalidades](#funcionalidades)  
- [Tecnologias Utilizadas](#tecnologias-utilizadas)  
- [Instalação e Configuração](#instalação-e-configuração)  
- [Uso](#uso)  
- [Estrutura do Projeto](#estrutura-do-projeto)  
- [Contribuição](#contribuição)  
- [Licença](#licença)

---

## 🎯 Visão Geral

Este projeto é uma aplicação web leve para gerenciar um processo eleitoral simulando:

- Cadastro e listagem de candidatos  
- Registro de votos dos eleitores  
- Exibição de resultados eleitorais em tempo real

Ideal para fins de estudo, protótipos ou treinamentos em desenvolvimento de aplicações com interface, lógica e armazenamento de dados básico.

---

## ✅ Funcionalidades

- **Cadastro de candidatos**: inclusão e visualização de informações (nome, número, partido).  
- **Registro de votos**: interface simples para coleta de votos por eleitor.  
- **Resultados eleitorais**: visualização estatística dos resultados (total de votos por candidato).  
- **Frontend responsivo**: compatível com desktop e mobile.  
- **Interface interativa**: uso de JavaScript para manipulação dinâmica do DOM.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – estrutura da página  
- **CSS3** – estilos e responsividade  
- **JavaScript (vanilla)** – lógica de CRUD e interface dinâmica  
- (Possível uso de **PHP** para backend – conforme comentários no código)

---

## ⚙️ Instalação e Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/sandoelio/crud-eleicoes-gerenciamento-de-candidatos-e-votos.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd crud-eleicoes-gerenciamento-de-candidatos-e-votos
   ```
3. Abra `index.html` com seu navegador preferido ou em um servidor local (ex.: Live Server do VSCode).  
4. (Opcional) Se usado backend PHP, configure um servidor PHP/Apache e ajuste o código conforme necessário (não incluso neste template).

---

## 🚀 Como Usar

1. **Cadastrar candidatos**: preencha o formulário com nome, número e partido.  
2. **Listar candidatos**: os cadastrados aparecem em um painel ou tabela.  
3. **Registrar votos**: selecione o candidato e confirme o voto.  
4. **Visualizar resultados**: acesse a aba de resultados para ver a apuração ao vivo.

---

## 📂 Estrutura do Projeto

```
├── index.html     – Arquivo principal da interface
├── style.css      – Estilos visuais e layout
├── script.js      – Lógica de CRUD e votos
├── etapas.js      – Funções de controle de fluxo (ex.: etapas de votação)
├── img/           – Imagens usadas na interface (ícones, logo etc.)
└── LICENSE        – Licença MIT
```

---

## 🤝 Contribuição

Contribuições são bem-vindas! Se quiser colaborar:

1. Fork este repositório.  
2. Crie uma branch com a nova feature (`git checkout -b feature/nova-funcionalidade`).  
3. Faça commit de suas mudanças (`git commit -m 'Adicionar nova feature'`).  
4. Push para sua branch (`git push origin feature/nova-funcionalidade`).  
5. Abra um pull request e descreva as alterações.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### 📝 Contato

Desenvolvido por **sandoelio**.  
Para sugestões ou dúvidas, abra uma issue no GitHub.
