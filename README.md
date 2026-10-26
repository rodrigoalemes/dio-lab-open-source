<p align="center">
<img src="assets/capa.png" alt="Contribuindo em um projeto open source" width="100%">
</p>

<h1 align="center">Contribuindo em um Projeto Open Source</h1>
<p align="center"><i>Desafio de projeto da DIO — Digital Innovation One</i></p>

<p align="center">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/DIO-E4105D?style=flat-square" alt="DIO">
</p>

## Sumário

- [Sobre o desafio](#sobre-o-desafio)
- [Fluxo de contribuição](#fluxo-de-contribuição)
- [Comandos utilizados](#comandos-utilizados)
- [Aprendizados](#aprendizados)
- [Autor](#autor)

## Sobre o desafio

Desafio da **DIO** para praticar o fluxo de contribuição em projetos open source no GitHub: copiar o repositório original (*fork*), trabalhar em uma *branch* própria e propor a alteração ao projeto por meio de um **pull request**.

## Fluxo de contribuição

```mermaid
gitGraph
    commit id: "repositório original"
    branch meu-perfil
    checkout meu-perfil
    commit id: "adiciona meu perfil"
    checkout main
    merge meu-perfil id: "pull request"
```

## Comandos utilizados

```bash
# 1. Clonar o fork para a máquina
git clone https://github.com/<seu-usuario>/dio-lab-open-source.git
cd dio-lab-open-source

# 2. Criar uma branch para a contribuição
git checkout -b meu-perfil

# 3. Registrar a alteração
git add .
git commit -m "Adiciona meu perfil"

# 4. Enviar a branch para o GitHub
git push origin meu-perfil

# 5. Abrir o pull request no GitHub
```

| Comando | Para que serve |
| --- | --- |
| `git clone` | Copia o repositório para a máquina local |
| `git checkout -b` | Cria e muda para uma nova branch |
| `git add` / `git commit` | Prepara e registra as alterações |
| `git push` | Envia a branch para o repositório remoto |

## Aprendizados

- Diferença entre **fork**, **clone** e **branch**
- Como manter a contribuição isolada em uma branch própria
- Como abrir e descrever um **pull request**
- Escrita de documentação em **Markdown**

## Autor

**Rodrigo Lemes** · Analista de TI · Microsoft 365, AD/Entra ID, Automação, Power BI e IA aplicada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rodrigo%20Lemes-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigoalemes/)
[![GitHub](https://img.shields.io/badge/GitHub-rodrigoalemes-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rodrigoalemes)
