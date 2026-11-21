<div align="center">

# 🐉 Cyber Study

**Painel pessoal de estudos de cibersegurança, com módulos Blue Team, Red Team e Carreira.**

Organize links, acompanhe seu progresso e evolua seu dragão a cada estudo concluído.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![Sem dependências](https://img.shields.io/badge/depend%C3%AAncias-0-5b9dff?style=for-the-badge)

<br>

<img src="images/end-dragon.webp" alt="Cyber End Dragon" width="260">

</div>

---

## 📌 Sobre o projeto

O **Cyber Study** é um site estático para quem estuda segurança da informação e quer tudo num só lugar: artigos, laboratórios, ferramentas, cursos e vagas. Cada link pode receber status, categoria, anotações pessoais e um checklist próprio.

Não precisa de servidor nem de banco de dados. Os links ficam em um arquivo `links.json` dentro do próprio repositório, e o site o atualiza por meio da API do GitHub. Assim, os mesmos links aparecem em qualquer computador ou celular.

## 🧭 Módulos

O site é dividido em quatro módulos. Cada um tem sua cor, seu padrão visual e um dragão próprio.

| Módulo | Foco | Dragão |
| :--- | :--- | :---: |
| **Fusão** · Blue + Red | Entender o ataque para construir a defesa | <img src="images/end-dragon.webp" width="150" alt="Cyber End Dragon"><br>Cyber End Dragon |
| **Defesa** · Blue Team | Detectar, conter e erradicar | <img src="images/sieger.webp" width="150" alt="Cyber Dragon Sieger"><br>Cyber Dragon Sieger |
| **Ataque** · Red Team | Pensar como o atacante | <img src="images/infinity.webp" width="150" alt="Cyber Dragon Infinity"><br>Cyber Dragon Infinity |
| **Carreira** · Vagas | Transformar estudo em oportunidade | <img src="images/proto.webp" width="150" alt="Primeiro Dragão Cibernético"><br>Primeiro Dragão Cibernético |

## ✨ Funcionalidades

**Organização de estudos**
- Links separados em **Estudos** e **Vagas**, com filtro por time (Todos, Blue ou Red).
- Categorias (matérias) na barra lateral, como SIEM, forense, pentest web e resposta a incidentes.
- Busca por título, site ou anotação, além de filtros por tipo e por status.
- Status de cada link: *A estudar*, *Estudando* e *Concluído*. Nas vagas: *Para ver*, *Candidatado* e *Arquivada*.
- Anotações pessoais e **checklist** dentro de cada link.

**Acompanhamento**
- Barras de progresso do Blue Team e do Red Team.
- **Sistema de níveis:** quanto mais estudos concluídos, mais alto o nível.

| Nível | Título | Estudos concluídos |
| :---: | :--- | :---: |
| 1 | Cyber Dragon | 0 |
| 2 | Cyber Twin Dragon | 5 |
| 3 | Cyber End Dragon | 15 |
| 4 | Cyber Dragon Infinity | 30 |

**Experiência e dados**
- Tela de introdução animada, que pode ser revista a qualquer momento.
- Tema **claro e escuro**.
- **Exportar e importar** os links em JSON, para backup.
- Layout responsivo, com navegação por teclado e respeito à opção de reduzir animações.

## 🗂️ Estrutura

```
cyber-study/
├── index.html        # Site completo (HTML, CSS e JavaScript)
├── links.json        # Seus links, salvos no repositório
├── README.md
└── images/
    ├── end-dragon.webp   # Módulo Fusão
    ├── sieger.webp       # Módulo Defesa
    ├── infinity.webp     # Módulo Ataque
    └── proto.webp        # Módulo Carreira
```

## 🚀 Como publicar

1. Crie um repositório no GitHub e envie todos os arquivos deste projeto, incluindo a pasta `images/`.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, depois a branch `main` e a pasta `/ (root)`.
4. Aguarde alguns minutos e abra `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## 🔐 Salvando links pelo site

Para **adicionar, editar ou remover links** direto pelo site, conecte o GitHub uma vez em cada aparelho:

1. No GitHub, vá em **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. Em **Repository access**, marque **Only select repositories** e escolha este repositório.
3. Em **Permissions → Repository permissions**, defina **Contents: Read and write**.
4. Gere o token, abra o site, clique em conectar o GitHub e cole o token.

> **Importante:** o token fica guardado apenas no navegador daquele aparelho. Use somente em dispositivos seus e nunca coloque o token em arquivos do repositório.

Sem o token, o site funciona em modo de leitura e mostra o que já está no `links.json`.

### O que fica onde

| Dado | Onde fica | Aparece em outros aparelhos? |
| :--- | :--- | :---: |
| Links, categorias, notas e checklist | `links.json` no repositório | ✅ Sim |
| Status dos estudos, tema e nível exibido | Navegador de cada aparelho | ❌ Não |

## 🛠️ Tecnologias

- **HTML5, CSS3 e JavaScript** puros, sem frameworks e sem etapa de build.
- **GitHub REST API** (Contents) para ler e gravar o `links.json`.
- **GitHub Pages** para a hospedagem.
- Fontes **Chakra Petch** e **IBM Plex Sans**, via Google Fonts.

## 🖼️ Créditos das imagens

Os dragões dos módulos são artes da família *Cyber Dragon*, da franquia **Yu-Gi-Oh!** (© 1996 Kazuki Takahashi). Elas são usadas aqui apenas em um projeto pessoal e sem fins lucrativos, e os direitos pertencem aos seus respectivos titulares.

## 👤 Autor

**David Capulot Corrêa**  
GitHub: [@DCapulot](https://github.com/DCapulot)

---

<div align="center">

*Entenda o ataque para construir a defesa.*

</div>
