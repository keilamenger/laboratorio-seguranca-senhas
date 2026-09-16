# 🔐 Laboratório de Segurança de Senhas

![Cybersecurity](https://img.shields.io/badge/Área-Cybersecurity-blue)
![Nível](https://img.shields.io/badge/Nível-Iniciante-green)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 📌 Sobre o projeto

Este projeto apresenta um laboratório introdutório sobre segurança de senhas e autenticação.

O objetivo é compreender os principais fatores que influenciam a segurança de uma senha, identificar padrões previsíveis e conhecer boas práticas para proteção de credenciais.

O projeto foi desenvolvido como parte da construção do meu portfólio na área de **Cibersegurança**.

---

## 🎯 Objetivos

- Compreender os fundamentos da segurança de senhas;
- Identificar características de senhas fracas e fortes;
- Analisar padrões previsíveis;
- Compreender riscos relacionados ao uso de informações pessoais;
- Conhecer ataques relacionados a credenciais;
- Estudar boas práticas de autenticação;
- Entender a importância do MFA.

---

## 🧪 Laboratório

Foram utilizados exemplos fictícios de senhas para analisar características como:

- Comprimento;
- Complexidade;
- Previsibilidade;
- Informações pessoais;
- Padrões comuns.

> ⚠️ Nenhuma senha real foi utilizada neste laboratório.

### Exemplos analisados

| Exemplo | Principal problema |
|---|---|
| `123456` | Sequência extremamente previsível |
| `senha123` | Palavra comum + padrão previsível |
| `Keila1997` | Informação pessoal |
| `Cachorro@123` | Padrão previsível |
| `rio!Mesa7#Lua92` | Maior comprimento e menor previsibilidade |

A análise detalhada está disponível em:

➡️ [`analise-senhas.md`](analise-senhas.md)

---

## 🛡️ Boas práticas

Durante o laboratório foram estudadas recomendações como:

- Utilizar senhas longas;
- Criar senhas únicas para diferentes serviços;
- Evitar informações pessoais;
- Evitar padrões previsíveis;
- Utilizar gerenciadores de senhas;
- Ativar autenticação multifator (MFA);
- Ter atenção a ataques de phishing;
- Nunca publicar credenciais em repositórios.

As recomendações completas estão disponíveis em:

➡️ [`boas-praticas.md`](boas-praticas.md)

---

## 🧠 O que aprendi

Este projeto ajudou a consolidar conhecimentos básicos importantes para a área de Cibersegurança.

### Principais aprendizados

**1. Segurança não depende apenas de complexidade**

Uma senha com números e caracteres especiais ainda pode ser previsível quando utiliza padrões comuns.

**2. Informações pessoais devem ser evitadas**

Nomes, datas e outras informações relacionadas ao usuário podem tornar uma senha mais previsível.

**3. Senhas devem ser únicas**

A reutilização de credenciais aumenta o impacto de um possível vazamento.

**4. MFA adiciona uma camada de proteção**

A autenticação multifator pode adicionar uma barreira adicional mesmo quando uma senha é comprometida.

**5. Segurança envolve comportamento**

Além da tecnologia, hábitos do usuário são importantes para a proteção das credenciais.

---

## 🔎 Conceitos estudados

- Autenticação
- Credenciais
- Senhas
- Força bruta
- Ataque de dicionário
- Credential stuffing
- MFA
- Phishing
- Gerenciamento de senhas

---

## 📂 Estrutura do projeto

```text
laboratorio-seguranca-senhas/
│
├── README.md
├── analise-senhas.md
└── boas-praticas.md
