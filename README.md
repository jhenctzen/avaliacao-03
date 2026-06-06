# 🎵 SoundBox

O **SoundBox** é uma plataforma web moderna e minimalista focada na catalogação, avaliação e resenha de álbuns musicais. O projeto foi desenvolvido como parte prática do curso técnico de Informática, aplicando conceitos fundamentais de estruturação semântica em HTML5 e estilização avançada e responsiva com CSS3.

---

## 🚀 Demonstração Visual & Interatividade

O design do projeto foi construído utilizando uma paleta de cores clara e moderna (Light Mode), com tipografia geométrica marcante e micro-interações que elevam a experiência do utilizador.

### Efeitos de Interatividade (CSS Hover & Transitions):
* **Cards de Álbuns (Index):** Efeito de aproximação sutil (`scale`) com expansão de sombra para destacar o aspeto visual da música.
* **Críticas de Utilizadores (Index):** Deslocamento horizontal estético (`translateX`) com alteração dinâmica da cor da borda esquerda para a identidade visual da marca, criando um efeito dinâmico fluido que não atrapalha a leitura.
* **Catálogo Completo (Álbuns):** Cards com efeito de levante vertical (`translateY`) e elevação de sombra, dando um aspeto tridimensional interativo.

---

## 📁 Estrutura do Projeto

O repositório está organizado de forma limpa e otimizada. Para garantir melhor performance e um repositório leve, as capas dos álbuns são consumidas diretamente via **links externos (URLs absolutas)**, eliminando a necessidade de armazenamento local de imagens de mídia:

```text
├── index.html                # Página inicial com destaques e críticas recentes
├── login.html                # Tela de autenticação de utilizadores
├── new.html                  # Tela de cadastro de novas contas
├── produto.html              # Vitrine/Catálogo completo de álbuns
├── style.css                 # Estilização global e da página inicial
├── icon/
│   └── favicon.png           # Ícone oficial da aba do navegador (Tom Vermelho)
├── css-login/
│   └── login.css             # Estilização do formulário de acesso
├── css-cadastro/
│   └── new.css               # Estilização do formulário de registo
└── css-produtos/
    └── produto.css           # Grid responsivo do catálogo de álbuns
