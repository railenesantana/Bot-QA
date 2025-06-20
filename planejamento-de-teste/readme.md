# Plano de Teste Bot QA Railene – Seu Assistente de Técnicas de Teste (Baseado no BSTQB)

## 1. Contexto do Teste

**Escopo:**

Testar o chatbot “Bot QA Railene – Seu Assistente de Técnicas de Teste”, criado no Chatling, voltado ao suporte para aspirantes a QA com dúvidas sobre técnicas de teste de software

**Objetivos do teste:**

* Validar o fluxo conversacional do chatbot
* Garantir que a IA responda corretamente às perguntas com base na base de conhecimento treinada
* Verificar usabilidade e clareza das respostas
  **Base do teste:**
* Documento PDF com técnicas de teste
* Fluxo visual do Chatling
* Comportamento esperado do bot

---

## 2. Premissas e Restrições

**Premissas:**

* O conteúdo da base de conhecimento está correto
* A plataforma Chatling está funcional
  **Restrições:**
* Limitações do plano gratuito do Chatling
* IA depende apenas da base de conhecimento (sem integrações externas)

---

## 3. Stakeholders

| Nome          | Função               | Responsabilidade                                 |
| ------------- | -------------------- | ------------------------------------------------ |
| Railene       | QA e Criadora do Bot | Planejar, executar e validar os testes           |
| Usuário final | Aspirante a QA       | Interagir com o bot e receber respostas corretas |

Não há necessidade de contratação ou treinamento adicional!

## 4. Comunicação

| Tipo                   | Forma              | Frequência       |
| ---------------------- | ------------------ | ---------------- |
| Registro de evidências | Prints e planilhas | A cada execução  |
| Atualizações           | Chatling           | Conforme ajustes |
| Validação              | Autoavaliação      | Ao fim do ciclo  |

---

## 5. Registro de Riscos

**Riscos do produto:**

* IA não entende variações com erros ortográficos
* Loop no fluxo ou respostas confusas
  **Riscos do projeto:**
* Tempo limitado para testes completos
* Mudanças inesperadas na plataforma Chatling

---

## 6. Abordagem de Teste

**Níveis de teste:**

* Teste de sistema

**Tipos de teste:**

* Funcional
* Usabilidade
* Conteúdo
* Teste negativo

**Técnicas de teste:**

* Teste baseado em experiência (exploratório)
* Partição de equivalência
* Caixa-preta

**Produtos de teste:**

* Plano de teste
* Casos de teste
* Evidências (capturas de tela)
* Relatório de execução

**Critérios de entrada:**

* Bot treinado
* Fluxo funcional

**Critérios de saída:**

* 80% de precisão nas respostas
* Zero bloqueios no fluxo
* Interação fluida

**Independência:**

* Testado pela própria criadora (Railene Santana)

**Métricas:**

* 100% de perguntas respondidas corretamente
* 0 de falhas encontradas
* 100% de testes aprovados

**Dados de teste:**

* Perguntas sobre QA
* Perguntas com erros
* Perguntas fora do escopo

**Ambiente:**

* Navegador (Chrome)
* Plataforma Chatling

**Formato dos Casos de Teste:**
Os casos de teste serão descritos utilizando a linguagem **Gherkin**, no formato:

```
Funcionalidade: [Funcionalidade testada]
  Scenario: [Cenário de uso]
    Dado [contexto inicial]
    Quando [ação do usuário]
    Então [resposta esperada do chatbot]
```

Essa abordagem facilita a compreensão entre áreas técnicas e não técnicas.

**Desvios:**

* Projeto pessoal, sem aplicação de política organizacional

---

## 7. Orçamento e Cronograma

**Orçamento:**

* Custo zero (plano gratuito Chatling)

**Cronograma:**

| Atividade             | Data     | Duração |
| --------------------- | -------- | ------- |
| Criação do bot        | 19/06    | 1h      |
| Planejamento de teste | 19/06    | 1h      |
| Execução de testes    | 19-20/06 | 1 a 2h  |
| Ajustes e validação   | 20/06    | 1h      |
