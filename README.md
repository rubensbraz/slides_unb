# Modelo de Slides UnB - LaTeX Beamer

Este repositório contém um template não oficial para apresentações acadêmicas da **Universidade de Brasília (UnB)**, desenvolvido em LaTeX utilizando a classe `beamer`.

O modelo foi customizado com as cores institucionais da UnB e estrutura pré-definida para facilitar a criação de slides para Defesas de TCC, Qualificações, Apresentações de Projetos e Aulas.

![Exemplo do Slide](https://user-images.githubusercontent.com/34790603/191086847-244d2b7f-4ef5-47ca-b42c-4442e6ce5fbe.png)

### 📄 Exemplo de Resultado

Você pode visualizar o resultado final compilado no link abaixo:
🔗 **[Visualizar PDF Completo (Resultado Modelo_de_Slides_UnB.pdf)](https://github.com/rubensbraz/slides_unb/blob/main/Resultado%20Modelo_de_Slides_UnB.pdf)**

---

## 🎨 Visual e Recursos

* **Tema Base:** Utiliza o tema `Berlin` do Beamer, conhecido por sua barra de navegação superior e rodapé informativo.
* **Identidade Visual:** Cores personalizadas (`unb-verde` e `unb-azul`) definidas no arquivo de estilo para combinar com a identidade da universidade.
* **Estrutura Pronta:** Já inclui seções padrões como Introdução, Fundamentação Teórica, Metodologia, Resultados e Conclusão.

## 🚀 Como Utilizar

Existem duas formas principais de utilizar este modelo: via Overleaf (online) ou localmente em seu computador.

### Opção 1: Overleaf (Recomendado)

Você pode abrir este projeto diretamente no Overleaf para começar a editar sem precisar instalar nada.

🔗 **[Clique aqui para fazer uma cópia no Overleaf](https://www.overleaf.com/read/wdjpcbrwqrjz)**

### Opção 2: Instalação Local

Se você prefere usar editores como VS Code, TeXShop ou TeXstudio:

1.  **Clone este repositório:**
    ```bash
    git clone [https://github.com/rubensbraz/slides_unb.git](https://github.com/rubensbraz/slides_unb.git)
    ```

2.  **Certifique-se de ter uma distribuição LaTeX instalada** (TeX Live, MiKTeX ou MacTeX).

3.  **Abra o arquivo principal:**
    Abra o arquivo `main.tex` no seu editor de preferência.

4.  **Compile:**
    Compile o projeto utilizando o compilador `pdfLaTeX` ou `XeLaTeX`.

## 📂 Descrição dos Arquivos

* **`main.tex`**: Conteúdo dos slides. É aqui que você editará o texto, títulos e seções.
* **`beamercolorthemeunb.sty`**: Arquivo de tema que define as cores da UnB (Verde e Azul).

## 📝 Personalização

Para editar as informações do trabalho, altere as linhas iniciais do arquivo `main.tex`:

```latex
% Título do projeto
\title{Seu Título Aqui}

% Data
\date{Data da Apresentação}

% Autores e Orientador
\author[Seu Nome Curto]{Alunos:\\Seu Nome\\Nome do Colega\\~\\Orientador:\\Prof. Dr. Orientador}
```

Para adicionar novos slides, utilize o comando \frame:

```latex
\section{Nova Seção}
\begin{frame}{Título do Slide}
    Conteúdo do slide aqui...
\end{frame}
```

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Isso significa que você pode usar, copiar, modificar e distribuir este modelo livremente, inclusive para fins comerciais, desde que mantenha os créditos do autor original.

Copyright (c) 2022 Rubens Braz.

--- 
Este é um modelo independente e não possui vínculo oficial direto com a administração da Universidade de Brasília.
