# 📊 Dashboard de Controle de Atividades

![Status](https://img.shields.io/badge/STATUS-CONCLUÍDO-brightgreen)
![Tech](https://img.shields.io/badge/TECH-HTML%20%7C%20JS%20%7C%20BOOTSTRAP-blue)

> Um painel visual para gerenciamento de tarefas semanais e diárias, focado em organização, proatividade e comunicação.

---

## 💻 Sobre o Projeto

Este projeto consiste em uma **Single Page Application (SPA)** desenvolvida para monitorar a execução de tarefas de suporte e desenvolvimento. O objetivo é substituir planilhas estáticas por um dashboard interativo que oferece métricas de produtividade em tempo real através de gráficos dinâmicos.

As tarefas são divididas em três pilares principais:
1.  **Proatividade** (Configuração de ambientes, manutenção de infraestrutura).
2.  **Organização** (Gestão do espaço físico e equipamentos).
3.  **Comunicação** (Alinhamento com a equipe).

---

## 📸 Visualização

*(Recomendação: Tire um print da tela do seu navegador com o projeto aberto e coloque o caminho da imagem aqui, ex: `assets/dashboard-print.png`)*

---

## 🚀 Funcionalidades

* **KPIs Visuais:** Gráficos interativos (Chart.js) para análise de status (Pendente vs. Concluído) e volume por categoria.
* **Status Color-Coded:** Identificação rápida visual de tarefas:
    * 🟢 **Concluído**
    * 🟡 **Em Andamento**
    * 🔴 **Pendente**
* **Design Responsivo:** Layout adaptável utilizando **Bootstrap 5**, funcionando bem em desktops e dispositivos móveis.
* **Impressão Otimizada:** Botão nativo para gerar relatórios impressos ou em PDF.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Estrutura e estilização.
* **JavaScript (ES6+):** Lógica de renderização do DOM e manipulação de dados (JSON).
* **Bootstrap 5:** Framework CSS para layout e componentes.
* **Chart.js:** Biblioteca para geração dos gráficos de Rosca e Barras.
* **FontAwesome:** Ícones vetoriais.

---

## 📂 Como Executar

Não é necessária instalação de dependências (Node/NPM) para esta versão estática.

1.  **Clone este repositório** (ou baixe os arquivos):
    ```bash
    git clone [https://github.com/SEU-USUARIO/nome-do-repo.git](https://github.com/SEU-USUARIO/nome-do-repo.git)
    ```
2.  **Abra o arquivo principal:**
    Navegue até a pasta e dê um duplo clique no arquivo `index.html` (ou `dashboard.html`).
3.  **Pronto!** O dashboard carregará no seu navegador padrão.

---

## 🔮 Próximos Passos (Roadmap)

Como foco do meu desenvolvimento é **Backend (Java)**, as próximas evoluções planejadas são:

- [ ] Criar uma **API REST com Java Spring Boot** para fornecer os dados das tarefas.
- [ ] Substituir o JSON estático no Front-end por chamadas `fetch()` para a API.
- [ ] Implementar banco de dados **MySQL** para persistência do histórico de tarefas.
- [ ] Adicionar funcionalidade de CRUD (Criar, Editar, Deletar tarefas) diretamente pela tela.

---

## 👨‍💻 Autor

Desenvolvido com foco em organização e produtividade.