# 🔎 Análise de Segurança de Senhas

## 📌 Objetivo

Neste exercício serão analisadas senhas fictícias com base em características que podem influenciar sua segurança.

A análise considera principalmente:

- Comprimento;
- Complexidade;
- Previsibilidade;
- Uso de informações pessoais;
- Reutilização de credenciais.

> ⚠️ As senhas utilizadas neste exercício são fictícias e servem apenas para fins educacionais.

---

## 🧪 Análise dos exemplos

### 1. `123456`

**Classificação:** senha muito previsível.

**Problemas identificados:**
- Possui poucos caracteres;
- Utiliza apenas números;
- Apresenta uma sequência extremamente previsível;
- Pode ser facilmente descoberta por tentativas automatizadas.

**Conclusão:**

Não é uma senha adequada para proteger uma conta.

---

### 2. `senha123`

**Classificação:** senha fraca.

**Problemas identificados:**
- Utiliza uma palavra muito comum;
- Possui um padrão previsível;
- O acréscimo de números no final não torna a senha significativamente imprevisível.

**Conclusão:**

É recomendável utilizar uma senha mais longa e menos previsível.

---

### 3. `Keila1997`

**Classificação:** senha com informação pessoal.

**Problemas identificados:**
- Contém um nome;
- Contém um ano;
- Pode estar relacionada a informações disponíveis sobre uma pessoa;
- Segue um padrão relativamente previsível.

**Conclusão:**

Informações pessoais devem ser evitadas na criação de senhas.

---

### 4. `Cachorro@123`

**Classificação:** senha com complexidade aparente, mas previsível.

**Pontos positivos:**
- Possui letras;
- Possui número;
- Possui caractere especial.

**Problemas identificados:**
- Utiliza uma palavra comum;
- O número está em uma posição previsível;
- O padrão pode ser facilmente reproduzido.

**Conclusão:**

Adicionar caracteres especiais ou números não é suficiente quando a estrutura da senha continua previsível.

---

### 5. `rio!Mesa7#Lua92`

**Classificação:** exemplo de senha mais robusta.

**Pontos positivos:**
- Maior comprimento;
- Combinação de letras e números;
- Utilização de caracteres especiais;
- Não utiliza uma sequência numérica simples;
- Possui uma estrutura menos previsível.

**Conclusão:**

O comprimento e a imprevisibilidade são características importantes para aumentar a resistência de uma senha a tentativas de descoberta.

---

## 📊 Comparação

| Exemplo | Comprimento | Previsibilidade | Informação pessoal | Avaliação |
|---|---:|---|---|---|
| `123456` | Curto | Muito alta | Não | Fraca |
| `senha123` | Curto | Alta | Não | Fraca |
| `Keila1997` | Médio | Alta | Sim | Fraca |
| `Cachorro@123` | Médio | Alta | Não | Fraca |
| `rio!Mesa7#Lua92` | Maior | Menor | Não | Mais robusta |

> A avaliação acima é qualitativa e serve apenas para demonstrar os conceitos estudados.

---

## 🧠 O que aprendi

A análise demonstrou que uma senha não se torna segura simplesmente por conter letras maiúsculas, números ou caracteres especiais.

Alguns dos principais fatores relacionados à segurança são:

1. Comprimento;
2. Imprevisibilidade;
3. Ausência de informações pessoais;
4. Não reutilização da senha;
5. Utilização de mecanismos adicionais de autenticação.

---

## 🔐 Ataques relacionados a senhas

Senhas podem ser alvo de diferentes tipos de ataques.

### Força bruta

Consiste na tentativa sistemática de diferentes combinações até encontrar a credencial correta.

### Ataque de dicionário

Utiliza listas de palavras e combinações comuns para tentar descobrir uma senha.

### Credential stuffing

Ocorre quando credenciais obtidas em um vazamento são utilizadas para tentar acessar outras contas.

Por isso, reutilizar a mesma senha em diferentes serviços aumenta o impacto de um eventual vazamento.

---

## 🛡️ Medidas de proteção

Algumas medidas importantes incluem:

- Utilizar senhas longas e únicas;
- Evitar informações pessoais;
- Evitar padrões previsíveis;
- Utilizar um gerenciador de senhas;
- Ativar autenticação multifator (MFA);
- Não compartilhar credenciais;
- Alterar credenciais quando houver suspeita de comprometimento.

---

## 📚 Conceitos demonstrados

Este exercício demonstra conhecimentos básicos sobre:

- Segurança de credenciais;
- Autenticação;
- Senhas fortes e fracas;
- Força bruta;
- Ataques de dicionário;
- Credential stuffing;
- MFA;
- Boas práticas de segurança.

---

## ⚖️ Considerações éticas

Este laboratório utiliza exclusivamente exemplos fictícios.

Testes de segurança e tentativas de autenticação devem ser realizados somente em sistemas próprios ou em ambientes para os quais exista autorização explícita.

O objetivo deste projeto é desenvolver conhecimentos introdutórios em cibersegurança de forma ética e responsável.
