# 🚀 Portfólio Profissional: Desenvolvimento Web & DevOps

![CI Status](https://github.com/davydsonmr1/trabalho-senai-esteira-de-prod-cicd/actions/workflows/ci.yml/badge.svg)
![CD Status](https://github.com/davydsonmr1/trabalho-senai-esteira-de-prod-cicd/actions/workflows/cd.yml/badge.svg)

 "A automação é o que separa o artesão do engenheiro."

Este projeto é um **Portfólio Profissional** desenvolvido como parte do Trabalho Prático de DevOps[cite: 4, 6]. Ele não apenas apresenta minhas habilidades técnicas e projetos, mas serve como prova de conceito para uma **pipeline de automação completa (CI/CD)** implementada via GitHub Actions.

---

##  Tecnologias & Habilidades
* **Frontend:** React.js, CSS Moderno (Flexbox/Grid), Web Vitals. 
* **DevOps:** GitHub Actions, Automação CI/CD, Gerenciamento de Runners. 
* **Qualidade:** Linters, Validação de Integridade, Segurança de Código. 

---

##  A Esteira de Produção (CI/CD)

A pipeline foi projetada para garantir que o site nunca saia do ar ou exiba código mal estruturado.

###  Integração Contínua (CI)
Toda Pull Request para a branch `main` dispara um fluxo de validação rigoroso:
* **Matrix Strategy:** Testes simultâneos em Node.js 18 e 20.
* **Linter:** Verificação de padrões técnicos e semântica HTML.
* **Segurança:** Bloqueio de termos sensíveis (password, senha) e comentários (TODO, FIXME).
* **Otimização:** Verificação de arquivos individuais acima de 500KB.
* **Integridade:** Validação de links, imagens e existência do `index.html`.

###  Entrega Contínua (CD)
Uma vez aprovado o Merge, o deploy é realizado automaticamente no **GitHub Pages**.
* **Zero Intervenção Humana:** Publicação imediata após união com a branch principal.
* **Notificações:** Alertas automáticos em caso de falha no deploy.

---

##  Acesso ao Projeto
O site oficial está publicado e disponível em:  
 **https://davydsonmr1.github.io/trabalho-senai-esteira-de-prod-cicd/** 

---

##  Colaboradores
* **Autor:** Davydson Maciel Rafael
* **Revisor/Colaborador:** 09116428-collab 

---
*Este projeto foi desenvolvido seguindo as diretrizes técnicas do Sistema FIEMG (SESI/SENAI/IEL).* 