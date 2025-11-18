# Certificacao-AZ-900-Arquitetura-e-Serviços-do-Microsoft-Azure-
---

# 🧭 Guia Interativo: Arquitetura e Serviços do Microsoft Azure (AZ-900)

Este guia lista os principais componentes físicos e organizacionais da infraestrutura do Azure, essenciais para quem está se preparando para a certificação AZ-900.

---

## 🌍 1. Regiões do Azure

### ✅ O que são
- Áreas geográficas com um ou mais datacenters próximos.
- Mais de **60 regiões** cobrindo **140+ países**.
- Oferecem **baixa latência**, **residência de dados** e **conformidade local**.

### 💡 Pergunta para refletir
> Por que é importante escolher uma região próxima ao seu público-alvo?

### 🛠️ Prática sugerida
- Acesse o portal do Azure e explore as regiões disponíveis.
- Crie um recurso em uma região diferente da sua para observar a latência.

---

## 🛡️ 2. Zonas de Disponibilidade

### ✅ O que são
- Conjunto de datacenters independentes dentro de uma mesma região.
- Cada zona possui **energia, resfriamento e rede próprios**.
- Conectadas por redes privadas de fibra óptica.

### 💡 Pergunta para refletir
> Como as zonas de disponibilidade ajudam a garantir alta disponibilidade?

### 🛠️ Prática sugerida
- Crie uma máquina virtual com replicação entre zonas de disponibilidade.

---

## 🧭 3. Pares de Regiões

### ✅ O que são
- Regiões emparelhadas com separação mínima de **300 milhas**.
- Suporte à **recuperação de desastres** e **atualizações sequenciais**.

### 💡 Pergunta para refletir
> Qual vantagem os pares de regiões oferecem em termos de continuidade de negócios?

### 🛠️ Prática sugerida
- Explore o mapa de pares de regiões: [aka.ms/PairedRegions-ptb](https://aka.ms/PairedRegions-ptb)

---

## 🏛️ 4. Regiões Soberanas

### ✅ O que são
- Regiões dedicadas a governos e agências federais.
- Exemplo: **Azure Government** (EUA), com acesso restrito e infraestrutura isolada.

### 💡 Pergunta para refletir
> Por que algumas organizações precisam de regiões soberanas?

---

## 🔧 5. Recursos do Azure

### ✅ O que são
- Componentes como **VMs, redes, bancos de dados e armazenamento**.
- São os blocos de construção das soluções em nuvem.

### 💡 Pergunta para refletir
> Quais recursos você usaria para criar um site simples no Azure?

---

## 📦 6. Grupos de Recursos

### ✅ O que são
- Contêineres lógicos para **organizar e gerenciar recursos**.
- Um recurso pertence a apenas um grupo, mas pode ser movido.
- Aplicações podem usar múltiplos grupos.

### 💡 Pergunta para refletir
> Como os grupos de recursos ajudam na organização de projetos?

### 🛠️ Prática sugerida
- Crie dois grupos de recursos e mova um recurso entre eles.

---

## 📜 7. Assinaturas do Azure

### ✅ O que são
- Fornecem acesso autenticado aos serviços.
- Permitem **controle de cobrança** e **gerenciamento de acesso**.

### 💡 Pergunta para refletir
> Como você organizaria diferentes departamentos de uma empresa usando assinaturas?

---

## 🗂️ 8. Grupos de Gerenciamento

### ✅ O que são
- Permitem **organizar múltiplas assinaturas** sob uma hierarquia.
- Aplicam políticas e controles de forma centralizada.

### 💡 Pergunta para refletir
> Qual vantagem os grupos de gerenciamento oferecem para grandes organizações?

---

## 🧪 9. Contas do Azure

### 🆓 Conta Gratuita
- 12 meses de produtos populares + crédito inicial de 30 dias.

### 🎓 Conta de Estudante
- $100 em créditos por 12 meses.
- Acesso gratuito a ferramentas de desenvolvimento.

### 💡 Pergunta para refletir
> Qual tipo de conta é ideal para você começar a praticar?

---

## 📚 Recursos Complementares

- [Introdução à Arquitetura do Azure](https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/1-introduction)
- [Contas do Azure](https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/3-get-started-azure-accounts)
- [Infraestrutura Física do Azure](https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/5-describe-azure-physical-infrastructure)

---

