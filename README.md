# 🍔 Aplicativo Ai Que Fome - Iteração 1 (XP)

Trabalho prático focado na aplicação das práticas de **Extreme Programming (XP)**.

## 👥 Dupla
* Fernanda Reis da Silva e Evelise Spengler
* [Nome do seu colega aqui]

---

## 📋 Planejamento (Jogo do Planejamento)

### Tabela 1 – Backlog Geral
| ID | Descrição | Prioridade | Complexidade | Critérios de Aceitação |
|:---|:---|:---|:---|:---|
| US01 | Visualizar tópicos de ajuda | Alta | 3 | Listar categorias de ajuda na tela inicial. |
| US02 | Pesquisar dúvidas | Alta | 5 | Barra de busca retornando artigos do banco. |
| US03 | Visualizar Cardápio | Média | 3 | Exibir itens de comida com descrição e preço. |

**Capacidade da Iteração:** 11 pontos (Total das histórias acima).

### Tabela 2 – Histórias da Primeira Iteração
| ID | Pontos | Tarefas Técnicas |
|:---|:---|:---|
| US01 | 3 | Criar banco de dados, `index.php` e listar categorias. |
| US02 | 5 | Criar formulário de busca e lógica `SQL LIKE` no PHP. |
| US03 | 3 | Inserir dados de cardápio e separar visualmente no front-end. |

---

## 🛠️ Práticas XP Aplicadas nesta Iteração
1. **Programação em Pares:** Desenvolvido em conjunto, alternando entre piloto e copiloto.
2. **Simplicidade (KISS/YAGNI):** Código focado no funcional, sem excessos de bibliotecas.
3. **Releases Curtas:** Sistema entregue e funcional já na primeira semana.
4. **Refatoração:** Ajuste de código para integrar cardápio e busca de forma otimizada.

## 🚀 Como executar o projeto
1. Clone o repositório.
2. Importe o arquivo `banco.sql` no seu MySQL (XAMPP).
3. Certifique-se de que a pasta está em `htdocs`.
4. Acesse `localhost/nome-da-pasta/index.php`.
