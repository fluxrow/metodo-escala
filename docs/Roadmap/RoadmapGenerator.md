# Gerador de Roadmap — Método Escala

## O que é este documento

O RoadmapGenerator é o sistema de priorização que converte o diagnóstico em um **plano de 90 dias personalizado** para cada negócio.

O objetivo não é trabalhar em todos os pilares ao mesmo tempo. É identificar **qual pilar, quando consertado, gera o maior impacto no resultado do negócio**.

> **Regra de Ouro:** Um plano de 3 iniciativas bem executadas é mais valioso do que um plano de 20 iniciativas mediocres.

---

## Passo 1 — Consolide o Diagnóstico

Antes de gerar o roadmap, você precisa ter o diagnóstico completo dos 7 pilares (ver `../Diagnosis/Questions.md` e `../Diagnosis/MaturityLevels.md`).

Preencha a tabela abaixo:

| Pilar | Nível Atual (1–4) | Principal Gap Identificado |
|-------|-------------------|---------------------------|
| 1. Projeto | | |
| 2. Processos | | |
| 3. Pessoas | | |
| 4. Produto | | |
| 5. Captação | | |
| 6. Venda | | |
| 7. Entrega | | |
| **Score Total** | **/28** | |

---

## Passo 2 — Identifique o Gargalo Primário

O gargalo primário é o pilar que, se melhorado, desbloqueia o crescimento de todos os outros.

### Lógica de Priorização

**Se o Score Total for entre 7–12 (Caótico):**
Comece sempre pelo Pilar 1 (Projeto) e Pilar 2 (Processos). Sem direção e sem processos mínimos, qualquer investimento em captação ou venda vai vazar.

**Se o Score Total for entre 13–18 (Em Transição):**
Identifique qual pilar externo (4, 5, 6 ou 7) tem menor nível. Geralmente é o gargalo que está limitando a receita. Em paralelo, resolva o pilar interno com menor nível que está causando dependência do dono.

**Se o Score Total for entre 19–24 (Estruturado):**
Foque nos 1–2 pilares com nível 2 ou abaixo. Os demais podem ser otimizados com automação e tecnologia.

**Se o Score Total for entre 25–28 (Escalável):**
Roadmap de escala acelerada. Foco em growth loops, automação, e expansão de canais.

---

## Passo 3 — Aplique o ICE Score

Para cada iniciativa identificada no diagnóstico, calcule o **ICE Score**:

| Dimensão | Pergunta | Escala |
|----------|----------|--------|
| **Impact** | Se isso funcionar, quanto vai mover a agulha no resultado? | 1–10 |
| **Confidence** | Qual a probabilidade de funcionar com base em evidências? | 1–10 |
| **Ease** | Quão fácil é de implementar com os recursos atuais? | 1–10 |

**ICE = (Impact + Confidence + Ease) / 3**

Priorize as iniciativas com ICE > 7.

### Exemplo de Aplicação

| Iniciativa | Impact | Confidence | Ease | ICE | Prioridade |
|------------|--------|-----------|------|-----|------------|
| Documentar processo de onboarding | 8 | 9 | 7 | 8.0 | 🔴 Alta |
| Criar playbook de vendas | 9 | 8 | 6 | 7.7 | 🔴 Alta |
| Ativar tráfego pago (novo canal) | 8 | 6 | 5 | 6.3 | 🟡 Média |
| Implementar NPS | 6 | 9 | 8 | 7.7 | 🔴 Alta |
| Redesenhar site | 4 | 5 | 4 | 4.3 | ⚪ Baixa |

---

## Passo 4 — Construa o Roadmap de 90 Dias

### Template de Roadmap

```
EMPRESA: [Nome]
DATA DE INÍCIO: [DD/MM/AAAA]
SCORE ATUAL: [X/28]
META AO FIM DOS 90 DIAS: [Y/28]

─────────────────────────────────────
MÊS 1 — ORGANIZAÇÃO (Dias 1–30)
─────────────────────────────────────
Foco: Pilar(es) com menor nível que bloqueiam tudo

INICIATIVA 1: [Nome]
  Pilar: [Número e Nome]
  Objetivo: [O que queremos alcançar]
  Ações:
    Semana 1: [Ação específica + responsável]
    Semana 2: [Ação específica + responsável]
    Semana 3: [Ação específica + responsável]
    Semana 4: [Ação específica + responsável]
  Resultado esperado: [Descrição concreta]
  Métrica de sucesso: [KPI mensurável]

INICIATIVA 2: [Nome]
  [Mesmo formato acima]

─────────────────────────────────────
MÊS 2 — ACELERAÇÃO (Dias 31–60)
─────────────────────────────────────
Foco: Pilares externos (captação, venda, produto)

INICIATIVA 3: [Nome]
  [Formato acima]

INICIATIVA 4: [Nome]
  [Formato acima]

─────────────────────────────────────
MÊS 3 — CONSOLIDAÇÃO (Dias 61–90)
─────────────────────────────────────
Foco: Automação, delegação e preparação para próximo ciclo

INICIATIVA 5: [Nome]
  [Formato acima]

REVISÃO DE 90 DIAS:
  - Score revisado: [X/28]
  - O que funcionou: [Lista]
  - O que não funcionou: [Lista + causa raiz]
  - Próximo ciclo de 90 dias: [Próximas prioridades]
```

---

## Passo 5 — Defina as Métricas de Acompanhamento

Para cada pilar trabalhado, defina 1–2 métricas semanais de acompanhamento:

| Pilar | Métrica Primária | Métrica Secundária | Frequência |
|-------|-----------------|-------------------|------------|
| 1. Projeto | % OKRs on track | Número de decisões estratégicas pendentes | Mensal |
| 2. Processos | % processos documentados (dos críticos) | Tempo médio de onboarding de novos colaboradores | Mensal |
| 3. Pessoas | eNPS (satisfação do time) | % metas individuais atingidas | Trimestral |
| 4. Produto | Churn rate (%) | NPS de clientes novos (primeiros 90 dias) | Mensal |
| 5. Captação | Volume de leads/semana | CPL por canal | Semanal |
| 6. Venda | Taxa de conversão do pipeline | Ciclo médio de vendas (dias) | Semanal |
| 7. Entrega | Churn mensal (%) | NPS geral | Mensal |

---

## Armadilhas Comuns a Evitar

### ❌ Trabalhar em tudo ao mesmo tempo
O roadmap eficaz tem no máximo **3 iniciativas simultâneas**. Mais do que isso dilui o foco e nada avança de verdade.

### ❌ Começar pela tecnologia
Automação e ferramentas entram **depois** que o processo humano funciona. Automatizar um processo ruim só gera erros mais rápido.

### ❌ Confundir urgente com importante
O gargalo que mais incomoda hoje nem sempre é o que mais impacta o crescimento. Use o ICE score, não a emoção.

### ❌ Fazer o diagnóstico e não revisitar
O diagnóstico muda conforme a empresa evolui. Revise o score a cada 90 dias — o que era prioridade pode já ter sido resolvido.

### ❌ Roadmap sem dono
Cada iniciativa precisa de **uma pessoa responsável** (não "o time"). Responsabilidade coletiva é a forma educada de dizer que ninguém é responsável.

---

## Exemplo de Roadmap Completo

### Cenário: Empresa de serviços B2B, 8 pessoas, R$ 80k/mês, Score 14/28

**Diagnóstico:**
- Pilar 1 (Projeto): 2 — tem visão informal, sem metas documentadas
- Pilar 2 (Processos): 1 — tudo na cabeça do dono e de 2 colaboradores-chave
- Pilar 3 (Pessoas): 2 — organograma existe, sem job descriptions ou avaliação
- Pilar 4 (Produto): 3 — oferta clara, bom posicionamento
- Pilar 5 (Captação): 2 — 1 canal (indicação) funcionando de forma inconsistente
- Pilar 6 (Venda): 2 — processo informal, sem CRM
- Pilar 7 (Entrega): 2 — entrega boa mas dependente do dono

**Gargalo Primário:** Pilar 2 (Processos) + Pilar 6 (Venda)

**Roadmap 90 dias:**

```
MÊS 1 — Base e Processos
  Iniciativa 1: Documentar os 5 processos críticos
    - Semana 1-2: Identificar e mapear processos com o time
    - Semana 3-4: Escrever SOPs e criar checklists
    - Meta: 5 processos documentados e testados por 1 novo colaborador

  Iniciativa 2: Configurar CRM e pipeline de vendas
    - Semana 1: Escolher e configurar CRM (HubSpot Free ou Pipedrive)
    - Semana 2-3: Migrar deals ativos e treinar time
    - Semana 4: Primeira reunião de pipeline review
    - Meta: 100% dos deals no CRM, pipeline review semanal ativo

MÊS 2 — Captação e Processo de Venda
  Iniciativa 3: Ativar 1 novo canal de captação (conteúdo no LinkedIn)
    - Publicar 3x/semana com casos de sucesso de clientes
    - Meta: 15 leads inbound novos no mês

  Iniciativa 4: Criar playbook básico de vendas
    - Script de qualificação, pitch e tratamento de objeções principais
    - Meta: Taxa de conversão de leads > 30%

MÊS 3 — Delegação e Preparação
  Iniciativa 5: Treinar 1 colaborador para assumir 3 processos do dono
    - Meta: Dono fora por 1 semana sem impacto operacional

MÉTRICAS SEMANAIS:
  - Leads gerados (meta: 10/semana no mês 3)
  - Deals no pipeline (meta: 15 ativos)
  - Taxa de conversão (meta: 30%)
  - Score de maturidade (revisão no dia 90)
```

---

## Próximo Ciclo

Ao final de cada ciclo de 90 dias:

1. Refaça o diagnóstico completo (Questions.md)
2. Recalcule o Score Global
3. Gere um novo roadmap com as prioridades atualizadas
4. Documente os aprendizados do ciclo anterior

O crescimento não é linear. Cada ciclo de 90 dias coloca a empresa em um patamar diferente — e os gargalos mudam conforme a empresa evolui.
