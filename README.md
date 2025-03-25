# 📄 Portfólio Pessoal

Este é um projeto de portfólio pessoal desenvolvido com **HTML** e **CSS**. O objetivo é apresentar informações sobre o desenvolvedor, suas habilidades e links para redes sociais, além de demonstrar boas práticas de desenvolvimento front-end. 🚀

## 📂 Estrutura do Projeto

A estrutura de diretórios do projeto é organizada da seguinte forma:

```
/
├── about.html    # Página "Sobre mim"
├── index.html    # Página inicial do portfólio
├── README.md     # Documentação do projeto
├── assets/       # Arquivos de mídia (imagens)
│ ├── Felipe Macedo.jpg
│ ├── github.png
│ ├── instagram.png
│ └── linkedin.png
└── styles/
└── style.css     # Estilos CSS do projeto
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação do conteúdo das páginas.
- **CSS3**: Estilização e responsividade.
- **Google Fonts**: Fontes personalizadas utilizadas no projeto.

## ✨ Funcionalidades

- **Página Inicial**:
  - Apresentação do desenvolvedor.
  - Links para redes sociais (GitHub, LinkedIn, Instagram).
- **Página Sobre Mim**:
  - Informações detalhadas sobre o desenvolvedor, incluindo habilidades e experiências.

## 🎨 Estilização

O projeto utiliza variáveis CSS para facilitar a manutenção e consistência de cores e fontes. As principais variáveis estão definidas no arquivo `style.css`:

```css
:root {
  --cor-primaria: #000000;
  --cor-secundaria: #f6f6f6;
  --cor-terciaria: #22d4fd;
  --cor-hover: #272727;

  --fonte-primaria: "Krona One", sans-serif;
  --fonte-secundaria: "Montserrat", sans-serif;
}
```

## 📱 Responsividade

O projeto é responsivo e utiliza media queries para ajustar o layout em dispositivos com largura máxima de 1200px. Por exemplo:

```css
@media (max-width: 1200px) {
  .cabecalho {
    padding: 10%;
  }

  .apresentacao {
    flex-direction: column-reverse;
    padding: 5%;
  }
}
```

## 🚀 Como Executar o Projeto

1. Clone este repositório ou faça o download dos arquivos.

2. Abra o arquivo index.html em qualquer navegador moderno.

## 🔮 Melhorias Futuras

- Adicionar mais páginas, como "Projetos" e "Contato".
- Implementar animações e transições para melhorar a experiência do usuário.
- Integrar um formulário de contato funcional.

## 👨‍💻 Autor

Desenvolvido por Felipe Macedo.
Entre em contato através das redes sociais:

# 📜 Licença

Este projeto é de uso pessoal e não possui uma licença específica.
