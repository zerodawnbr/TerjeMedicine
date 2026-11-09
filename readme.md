# 🏥 Terje Medicine — Guia Médico em Português

<p align="center">
  <img src="https://raw.githubusercontent.com/TerjeBruoygard/TerjeMods/master/WIKI/logos/TerjeMedicine.jpg" width="500">
</p>

<p align="center">
  **[BR] ZERO DAWN — MANUAL DE SOBREVIVÊNCIA**
  <br>
  Guia de doenças, ferimentos, medicamentos e tratamentos do Terje Medicine.
</p>

---

## 📑 Índice

- [1. Como funciona o sistema médico](#1-como-funciona-o-sistema-médico)
- [2. Doenças e intoxicações](#2-doenças-e-intoxicações)
  - [Gripe, resfriado e pneumonia](#gripe-resfriado-e-pneumonia)
  - [Intoxicação alimentar](#intoxicação-alimentar)
  - [Intoxicação química](#intoxicação-química)
  - [Vírus zumbi](#vírus-zumbi)
  - [Sepse](#sepse)
  - [Raiva](#raiva)
- [3. Ferimentos e lesões](#3-ferimentos-e-lesões)
  - [Hematomas](#hematomas)
  - [Ferimentos por bala e objetos penetrantes](#ferimentos-por-bala-e-objetos-penetrantes)
  - [Lesões em órgãos internos](#lesões-em-órgãos-internos)
  - [Suturas cirúrgicas](#suturas-cirúrgicas)
  - [Concussão](#concussão)
- [4. Sangramento e recuperação sanguínea](#4-sangramento-e-recuperação-sanguínea)
  - [Hemostasia](#hemostasia--controle-do-sangramento)
  - [Regeneração sanguínea](#regeneração-sanguínea)
- [5. Sintomas e estados do personagem](#5-sintomas-e-estados-do-personagem)
  - [Dor](#dor)
  - [Overdose](#overdose)
  - [Saúde mental](#saúde-mental)
  - [Sono](#sono)
- [6. Vacinas](#6-vacinas)
- [7. Desinfecção](#7-desinfecção)
- [8. Equipamentos médicos](#8-equipamentos-médicos)

---

# 1. Como funciona o sistema médico

O Terje Medicine adiciona um sistema médico mais complexo ao DayZ.

As doenças e os ferimentos possuem diferentes estágios de evolução, sintomas e métodos de tratamento.

### 💊 Tipos de medicamentos

| Apresentação | Descrição |
|---|---|
| Comprimidos | Geralmente utilizados nos estágios iniciais das doenças e na prevenção. |
| Ampolas | Medicamentos mais potentes. Necessitam de seringa para administração. |
| Injetores | Medicamentos injetáveis descartáveis que não necessitam de seringa. |
| Pomadas | Utilizadas principalmente no tratamento de hematomas. |
| Vacinas | Criam imunidade contra doenças específicas. |

**⚠️ Importante:**

- Os medicamentos são divididos em níveis de potência.
- Medicamentos de níveis superiores podem tratar doenças de níveis inferiores.
- O uso excessivo de medicamentos pode provocar overdose.
- Após utilizar uma seringa, ela fica contaminada e precisa ser desinfetada com álcool ou fervida em uma panela com água sobre o fogo.

### Níveis dos medicamentos

| Nível | Classificação |
|---|---|
| 🟢 Nível 1 | Tratamento básico |
| 🟡 Nível 2 | Tratamento intermediário |
| 🔴 Nível 3 | Tratamento avançado |

---

# 2. Doenças e intoxicações

## 🤧 Gripe, resfriado e pneumonia

**Causa:** exposição prolongada a temperaturas baixas.

Um resfriado leve pode evoluir para gripe e posteriormente pneumonia quando não tratado.

**Sintomas e consequências:**

- Resfriado e sintomas gripais.
- Evolução progressiva da doença.
- Na pneumonia, o personagem começa a perder vida lentamente.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Tetracycline | `TetracyclineAntibiotics` | 1 | Comprimido | 300 | 0.45 |
| Paracetamol | `TerjePillsParacetamol` | 1 | Comprimido | 200 | 0.45 |
| Amibaktam | `TerjePillsAmibaktam` | 1 | Comprimido | 60 | 0.05 |
| Ibuprofen | `TerjePillsIbuprofen` | 2 | Comprimido | 300 | 0.35 |
| Nurofen | `TerjePillsNurofen` | 2 | Comprimido | 300 | 0.52 |
| Amoxiclav | `TerjePillsAmoxiclav` | 2 | Comprimido | 1200 | 0.75 |
| Piperacillin | `TerjePillsPiperacylin` | 2 | Comprimido | 1100 | 0.45 |
| Ketarol | `TerjeAmpouleKetarol` | 2 | Ampola | 1200 | 0.50 |
| Amoxivan | `TerjeAmpouleAmoxivan` | 2 | Ampola | 900 | 0.30 |
| Topoisomerase | `TerjeInjectorTopoizomeraza` | 3 | Injetor | 900 | 0.65 |
| Imipenem | `TerjeAmpouleImipenem` | 3 | Ampola | 900 | 0.70 |
| Flemoclave | `TerjeAmpouleFlemoclav` | 3 | Ampola | 1200 | 0.80 |
| Amoxiclav | `TerjeInjectorAmoxiclav` | 3 | Injetor | 1800 | 0.60 |

### 🛡️ Vacina

| Vacina | Classe do item | Duração (s) |
|---|---|---:|
| Vaxicam | `TerjeAmpouleVaxicam` | 14400 |

### 🩹 Solução

1. Em casos leves, procure um local aquecido e descanse.
2. Utilize antibióticos compatíveis com o estágio da doença.
3. Medicamentos de nível superior também podem ser utilizados.
4. Em casos de pneumonia, podem ser necessárias várias doses para a recuperação completa.
5. Utilize Vaxicam para prevenção.

**⚠️ Atenção:** a pneumonia pode provocar perda gradual de vida.

---

## 🤢 Intoxicação alimentar

**Causa:** consumo de alimentos estragados ou malcozidos, frutas podres, cogumelos venenosos, água contaminada ou ingestão acidental de gasolina.

**Sintomas e consequências:**

- Náuseas.
- Vômitos.
- Desidratação.
- Perda gradual de vida quando não tratada.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Carvão ativado | `CharcoalTablets` | 1 | Comprimido | 300 | 0.01 |
| Polysorb | `TerjePillsPolisorb` | 1 | Comprimido | 300 | 0.05 |
| Phthalazole | `TerjePillsFtalazol` | 1 | Comprimido | 1200 | 0.25 |
| Mesalazine | `TerjePillsMesalazin` | 2 | Comprimido | 600 | 0.35 |
| Chelating Tablets | `ChelatingTablets` | 2 | Comprimido | 600 | 0.60 |
| Metoclopramid | `TerjeAmpouleMetoclopramid` | 2 | Ampola | 1200 | 0.40 |
| Heptral | `TerjeAmpouleHeptral` | 3 | Ampola | 600 | 0.60 |
| Stomaproxidal | `TerjeInjectorStomaproxidal` | 3 | Injetor | 900 | 0.68 |

### 🩹 Solução

1. Utilize medicamentos específicos para intoxicação alimentar.
2. Beba bastante água para combater a desidratação.
3. Evite alimentos estragados, cogumelos desconhecidos e água contaminada.

---

## ☣️ Intoxicação química

**Causa:** inalação de gases tóxicos.

**Sintomas e consequências:**

- Tosse nos estágios iniciais.
- Náuseas e vômitos.
- Perda severa de vida nos estágios avançados.
- Pode ser fatal sem tratamento.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Rombiopental | `TerjePillsRombiopental` | 1 | Comprimido | 30 | 0.15 |
| Neirocetal | `TerjeAmpouleNeirocetal` | 2 | Ampola | 500 | 1.25 |
| AntiChem Injector | `AntiChemInjector` | 3 | Injetor | 180 | 1.10 |

### 🩹 Solução

1. Afaste-se imediatamente da fonte de contaminação.
2. Utilize o medicamento correspondente ao nível da intoxicação.
3. Não permaneça em áreas contaminadas sem proteção adequada.

---

## 🧟 Vírus zumbi

**Causa:** transmissão por gotículas no ar e fluidos corporais. Existe uma pequena possibilidade de infecção durante combates próximos com zumbis, aumentando significativamente quando o personagem sofre ferimentos.

**Sintomas e consequências:**

- Longo período de incubação.
- Mais de uma hora de tempo real para procurar um antídoto.
- No estágio terminal, a vida começa a diminuir rapidamente.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Apresentação | Duração (s) | Overdose |
|---|---|---|---:|---:|
| Zivirol | `TerjeAmpouleZivirol` | Ampola | 1000 | 2.35 |
| Zivirol | `TerjeInjectorZivirol` | Injetor | 1200 | 2.50 |

### 🛡️ Vacina

| Vacina | Classe do item | Duração (s) |
|---|---|---:|
| Zerivax | `TerjeAmpouleZerivax` | 7200 |

### 🩹 Solução

1. Procure o Zivirol assim que identificar a infecção.
2. Não espere chegar ao estágio terminal.
3. Utilize Zerivax preventivamente.
4. Máscaras e proteção balística podem reduzir o risco de infecção.

**⚠️ Atenção:** Zivirol é o medicamento de tratamento. Zerivax é a vacina preventiva.

---

## 🩸 Sepse

**Causa:** entrada de bactérias em ferimentos abertos.

Pode ocorrer após:

- Arranhões de zumbis.
- Ferimentos por facas.
- Ferimentos por armas de fogo.
- Manipulação de feridas com mãos sujas.

**Sintomas e consequências:**

- Infecção progressiva.
- Deterioração gradual da vida.
- Pode ser fatal sem tratamento.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Flemoclav | `TerjeAmpouleFlemoclav` | 3 | Ampola | 1200 | 0.80 |
| Imipenem | `TerjeAmpouleImipenem` | 3 | Ampola | 900 | 0.70 |
| Amoxiclav | `TerjeInjectorAmoxiclav` | 3 | Injetor | 300 | 0.60 |
| Topoisomerase | `TerjeInjectorTopoizomeraza` | 3 | Injetor | 600 | 0.65 |

### 🩹 Solução

1. Utilize antibióticos específicos para tratar a infecção.
2. Mantenha os ferimentos limpos.
3. Desinfete as mãos antes de realizar procedimentos médicos.
4. Utilize instrumentos médicos desinfetados.

---

## 🐺 Raiva

**Causa:** mordidas de animais infectados, como lobos.

**Estágios e sintomas:**

| Estágio | Sintomas |
|---|---|
| 🟢 Estágio 1 | Alterações leves de temperatura e fraqueza. |
| 🟡 Estágio 2 | Náuseas intensas e vômitos, impedindo alimentação e hidratação. |
| 🔴 Estágio 3 | Febre elevada, perda rápida de vida e exaustão. |

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Rabinoline | `TerjeAmpouleRabinoline` | 2 | Ampola | 600 | 0.80 |
| Rifampicin | `TerjeAmpouleRifampicyne` | 3 | Ampola | 300 | 1.35 |
| Rabinucoline | `TerjeInjectorRabinucoline` | 3 | Injetor | 900 | 1.46 |

### 🛡️ Vacina

| Vacina | Classe do item | Duração (s) |
|---|---|---:|
| Rabivax | `TerjeAmpouleRabivax` | 14400 |

### 🩹 Solução

1. Procure tratamento o mais cedo possível.
2. Utilize medicamentos específicos para raiva.
3. Utilize Rabivax preventivamente.
4. Não espere chegar ao estágio crítico.

**⚠️ Atenção:** a raiva pode ser fatal sem tratamento adequado.

---

# 3. Ferimentos e lesões

## 🟣 Hematomas

**Causa:** golpes de zumbis ou impactos de armas contundentes.

**Consequências:**

- Acúmulo de hematomas.
- Quando existem muitos hematomas, a vida começa a diminuir.

Os hematomas desaparecem naturalmente com o tempo, mas pomadas aceleram a recuperação.

### 💊 Pomadas para tratamento

| Medicamento | Classe do item | Apresentação | Duração (s) | Overdose |
|---|---|---|---:|---:|
| Viprosal | `TerjeSalveViprosal` | Pomada | 300 | 0.00 |
| Capsicum | `TerjeSalveCapsicum` | Pomada | 400 | 0.00 |
| Finalgon | `TerjeSalveFinalgon` | Pomada | 600 | 0.00 |

### 🩹 Solução

1. Utilize uma das pomadas disponíveis.
2. Aguarde o efeito do medicamento.
3. Evite acumular muitos hematomas.

---

## 🔪 Ferimentos por bala e objetos penetrantes

**Causa:** ataques com armas brancas ou disparos de armas de fogo.

**Consequências:**

- Sangramento intenso.
- Objetos estranhos alojados no ferimento.
- Possibilidade de lesões em órgãos internos.

**🩹 Primeiros socorros:**

- Estanque o sangramento imediatamente.
- Bandagens hemostáticas são mais eficientes que bandagens comuns ou panos.
- Após o curativo, o ferimento pode continuar sangrando levemente até que o objeto estranho seja removido cirurgicamente.

### 🛠️ Equipamentos cirúrgicos

| Equipamento | Classe do item | Volume | Órgãos internos (força/tempo) | Bala (força/tempo) | Fragmentos (força/tempo) |
|---|---|---:|---:|---:|---:|
| Medical Bowl (Ceramic) | `TerjeSurgicalTool_Ceramic` | 1 | 0.05 / 90 | 0.2 / 40 | 0.4 / 30 |
| Medical Bowl (White) | `TerjeSurgicalTool_White` | 1 | 0.05 / 90 | 0.2 / 40 | 0.4 / 30 |
| Field Surgical Kit | `TerjeSurgicalKit` | 5 | 0.2 / 40 | 0.5 / 25 | 0.7 / 20 |
| IFAK | `TerjeFirstAidKitIndividual_Black` | 10 | 0.3 / 40 | 0.6 / 30 | 0.8 / 20 |
| AFAK | `TerjeFirstAidKitAdvance_Black` | 20 | 0.3 / 40 | 0.6 / 30 | 0.8 / 20 |

**Legenda:**
- Força: eficiência do equipamento no procedimento.
- Tempo: duração do procedimento em segundos.

### 🦺 Proteção balística

Coletes balísticos podem proteger contra ferimentos de bala.

| Tipo de munição | Proteção |
|---|---|
| Pequeno calibre | Alguns coletes leves podem bloquear. |
| Médio calibre | Coletes leves podem não ser suficientes. |
| Grande calibre | Coletes leves são ineficazes. |

**⚠️ Atenção:** mesmo quando o colete bloqueia um projétil, o personagem ainda pode sofrer um hematoma.

---

## 🫀 Lesões em órgãos internos

**Causa:** ferimentos penetrantes graves que atingem órgãos internos.

**Consequências:**

- Lesões profundas.
- Maior dificuldade de tratamento.
- Necessidade de procedimento cirúrgico.

### 🛠️ Tratamento

Utilize os equipamentos cirúrgicos da tabela anterior.

A eficiência varia de acordo com o equipamento utilizado.

**Recomendação:** equipamentos IFAK e AFAK possuem maior eficiência cirúrgica entre os itens listados.

---

## 🪡 Suturas cirúrgicas

As suturas são aplicadas durante procedimentos cirúrgicos.

**⚠️ Importante:** os materiais utilizados devem ser desinfetados regularmente para evitar infecções e sepse.

### 🧼 Cuidados

1. Desinfete as mãos antes da cirurgia.
2. Utilize equipamentos médicos limpos.
3. Desinfete os instrumentos utilizados.
4. Evite realizar procedimentos com materiais contaminados.

Os equipamentos utilizados para suturas são os mesmos equipamentos cirúrgicos apresentados na seção de ferimentos.

---

## 🧠 Concussão

**Causa:**

- Pancadas fortes na cabeça com objetos contundentes.
- Explosões próximas ao personagem.
- Impactos de projéteis de baixo calibre contra capacetes balísticos.

**Sintomas e consequências:**

- Dor de cabeça.
- Tontura.
- Coordenação instável.
- Visão embaçada.
- Dificuldade de movimentação e combate.

A concussão pode desaparecer naturalmente, mas medicamentos aceleram a recuperação.

### 💊 Medicamentos para tratamento

| Medicamento | Classe do item | Apresentação | Duração (s) | Overdose |
|---|---|---|---:|---:|
| Noopept | `TerjePillsNoopept` | Comprimido | 380 | 0.35 |
| Neirox | `TerjeAmpouleNeirox` | Ampola | 600 | 0.60 |
| Neirox | `TerjeInjectorNeirox` | Injetor | 500 | 0.30 |

### 🩹 Solução

1. Utilize Noopept ou Neirox.
2. Aguarde o efeito do medicamento.
3. A recuperação também pode ocorrer naturalmente com o tempo.

---

# 4. Sangramento e recuperação sanguínea

## 🩸 Hemostasia — Controle do sangramento

**Função:** processo natural do organismo para interromper sangramentos.

Medicamentos específicos podem diminuir a velocidade da perda de sangue, oferecendo mais tempo para tratar o ferimento.

### 💊 Medicamentos

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Vikasol | `TerjePillsVikasol` | 1 | Comprimido | 300 | 0.15 |
| Erytromixelin | `TerjeInjectorErytromixelin` | 3 | Injetor | 300 | 0.32 |

### 🩹 Solução

1. Utilize medicamentos hemostáticos.
2. Faça o curativo do ferimento.
3. Procure tratamento cirúrgico quando houver objetos alojados.

**⚠️ Atenção:** medicamentos hemostáticos não substituem os curativos.

---

## 🩸 Regeneração sanguínea

**Função:** estimula a regeneração dos glóbulos vermelhos e acelera a recuperação do sangue perdido.

É especialmente útil após arranhões, cortes e ferimentos por bala.

### 💊 Medicamentos

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Irovit | `TerjePillsIrovit` | 1 | Comprimido | 120 | 0.30 |
| Magnesium Sulfate | `TerjePillsMagnesiumSulfate` | 1 | Comprimido | 120 | 0.30 |
| Erythropoetin | `TerjeAmpouleErythropoetin` | 1 | Ampola | 600 | 0.40 |
| Erythropoetin | `TerjeInjectorErythropoietin` | 1 | Injetor | 900 | 0.40 |
| Erytromixelin | `TerjeInjectorErytromixelin` | 2 | Injetor | 300 | 0.32 |

### 🩹 Solução

1. Utilize medicamentos específicos para regeneração sanguínea.
2. Aguarde o efeito do medicamento.
3. Controle também os sangramentos ativos para evitar novas perdas.

---

# 5. Sintomas e estados do personagem

## 😣 Dor

**Causa:** diferentes tipos de ferimentos e traumas.

A intensidade da dor depende da gravidade da lesão.

A dor diminui naturalmente com o tempo, mas pode ser aliviada com analgésicos.

### 💊 Medicamentos

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Codeine | `PainkillerTablets` | 1 | Comprimido | 300 | 0.20 |
| Analgin | `TerjePillsAnalgin` | 1 | Comprimido | 500 | 0.15 |
| Nimesulide | `TerjePillsNimesulid` | 1 | Comprimido | 600 | 0.25 |
| Paracetamol | `TerjePillsParacetamol` | 1 | Comprimido | 200 | 0.45 |
| Ibuprofen | `TerjePillsIbuprofen` | 1 | Comprimido | 600 | 0.35 |
| Nurofen | `TerjePillsNurofen` | 1 | Comprimido | 350 | 0.52 |
| Noopept | `TerjePillsNoopept` | 1 | Comprimido | 380 | 0.35 |
| Ketarol | `TerjeAmpouleKetarol` | 1 | Ampola | 1200 | 0.50 |
| Novacaine | `TerjeAmpouleNovacaine` | 2 | Ampola | 1200 | 0.40 |
| Morphinocin | `TerjeAmpouleMorphine` | 3 | Ampola | 850 | 0.52 |
| Hexobarbital | `TerjeAmpouleGexobarbital` | 3 | Ampola | 900 | 0.65 |
| Reanimatal | `TerjeInjectorReanimatal` | 3 | Injetor | 240 | 1.85 |
| Propital | `TerjeInjectorPropital` | 2 | Injetor | 180 | 0.75 |
| Morphine | `Morphine` | 3 | Injetor | 300 | 0.75 |
| Promidol | `TerjeInjectorPromidol` | 3 | Injetor | 600 | 0.45 |

### 🩹 Solução

1. Identifique a intensidade da dor.
2. Utilize analgésicos do nível correspondente ou superior.
3. Aguarde a duração do medicamento.
4. A dor também pode desaparecer naturalmente.

---

## 💊 Overdose

**Causa:** ingestão excessiva de medicamentos ou substâncias tóxicas.

A overdose evolui em três estágios.

| Estágio | Sintomas |
|---|---|
| 🟢 Estágio 1 | Náuseas e alucinações. Perda da percepção normal. |
| 🟡 Estágio 2 | Agravamento dos sintomas e possibilidade de perda de consciência. |
| 🔴 Estágio 3 | Deterioração crítica da saúde e risco de morte. |

### 💊 Tratamento

| Item | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Água | `WaterBottle` | 1 | Garrafa | 300 | 0.00 |

### 🩹 Solução

1. Interrompa imediatamente o uso de medicamentos.
2. Beba água.
3. Aguarde a eliminação gradual das toxinas.
4. Evite administrar novos medicamentos sem necessidade.

**⚠️ Atenção:** a overdose é um efeito acumulativo do uso excessivo de medicamentos. Verifique sempre a coluna de overdose antes de administrar uma substância.

---

## 🧠 Saúde mental

**Causa:** deterioração da saúde mental devido a situações extremas, como:

- Ataques de zumbis.
- Exposição prolongada a zonas psiônicas.
- Consumo de carne humana.

**Sintomas e consequências:**

- Pânico.
- Alucinações.
- Desorientação.
- Crises nervosas.
- Dificuldade de controlar o personagem.

### 💊 Medicamentos

| Medicamento | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| Adepress | `TerjePillsAdepress` | 1 | Comprimido | 150 | 0.20 |
| Agteminol | `TerjePillsAgteminol` | 1 | Comprimido | 120 | 0.20 |
| Venlafaxine | `TerjePillsVenlafaxine` | 1 | Comprimido | 250 | 0.30 |
| Actaparoxetine | `TerjeAmpouleActaparoxetine` | 2 | Ampola | 400 | 0.40 |
| Metralindole | `TerjeAmpouleMetralindole` | 2 | Ampola | 300 | 0.10 |
| Amitriptyline | `TerjeAmpouleAmitriptyline` | 3 | Ampola | 600 | 0.40 |
| Amfitalicyne | `TerjeInjectorAmfitalicyne` | 3 | Injetor | 520 | 0.60 |

### 🩹 Solução

1. Utilize antidepressivos específicos.
2. Evite exposição prolongada a zonas psiônicas.
3. Evite consumir carne humana.
4. Mantenha o estado mental estabilizado.

---

## 🌙 Sono

**Função:** o personagem precisa dormir, assim como precisa de alimentação e hidratação.

A falta de sono prejudica a sobrevivência e pode provocar perda de consciência.

### Indicadores de sono

| Indicador | Efeito |
|---|---|
| 🟡 Amarelo | O personagem começa a bocejar e a visão piora gradualmente. |
| 🔴 Vermelho | Pode ocorrer perda de consciência por exaustão. |

### 🛌 Onde dormir?

- Próximo a uma lareira.
- Dentro de uma barraca.
- Dentro de uma casa.
- Em um saco de dormir.

### Condições que impedem dormir

- Personagem congelando.
- Personagem passando fome.
- Doenças graves no estágio 2 ou superior.

### Benefícios do sono

- Recuperação de vida.
- Recuperação de sangue.
- Possibilidade de recuperação de doenças leves, como gripe no estágio 1.
- Maior conforto e proteção contra o frio quando se utiliza saco de dormir.

### 🥤 Bebidas de recuperação do sono

| Bebida | Classe do item | Nível | Apresentação | Duração (s) | Overdose |
|---|---|---:|---|---:|---:|
| MadBull Energy Drink | `TerjeDrinkMadBull` | 8 | Garrafa | 1.0 | 0.00 |
| Gang Energy Drink | `TerjeDrinkGang` | 6 | Garrafa | 1.0 | 0.00 |
| Yaguar Energy Drink | `TerjeDrinkYaguar` | 10 | Garrafa | 1.0 | 0.00 |
| PrayBoy Energy Drink | `TerjeDrinkPrayboy` | 4 | Garrafa | 1.0 | 0.00 |
| 6Energy Energy Drink | `TerjeDrink6Energy` | 8 | Garrafa | 0.8 | 0.00 |

---

# 6. Vacinas

As vacinas proporcionam imunidade contra doenças específicas.

Devem ser administradas preventivamente para reduzir o risco de infecção.

| Vacina | Classe do item | Proteção | Duração |
|---|---|---|---:|
| 💉 Vaxicam | `TerjeAmpouleVaxicam` | Gripe / resfriado | 14400 s (4 horas) |
| 💉 Zerivax | `TerjeAmpouleZerivax` | Vírus zumbi | 7200 s (2 horas) |
| 💉 Rabivax | `TerjeAmpouleRabivax` | Raiva | 14400 s (4 horas) |

**⚠️ Importante:** as vacinas são preventivas. Não confunda vacinação com tratamento de uma infecção já estabelecida.

---

# 7. Desinfecção

A desinfecção é obrigatória para manter a esterilidade e evitar infecções nos ferimentos.

Mãos e instrumentos médicos devem ser desinfetados antes de procedimentos e operações.

### 🧴 Produtos desinfetantes

| Produto | Classe do item | Finalidade |
|---|---|---|
| Tintura alcoólica | `DisinfectantAlcohol` | Desinfecção |
| Spray desinfetante | `DisinfectantSpray` | Desinfecção |

### 🧼 Procedimentos

1. Desinfete as mãos antes de realizar qualquer procedimento médico.
2. Desinfete instrumentos médicos sujos antes de utilizá-los.
3. Utilize materiais esterilizados em cirurgias.
4. Após administrar uma ampola, desinfete a seringa com álcool ou ferva-a em uma panela com água sobre o fogo.

**⚠️ Atenção:** manipular ferimentos com mãos sujas aumenta significativamente o risco de sepse.

---

# 8. Equipamentos médicos

### 🛠️ Equipamentos cirúrgicos

| Equipamento | Classe do item | Volume |
|---|---|---:|
| Tigela médica com instrumentos (Cerâmica) | `TerjeSurgicalTool_Ceramic` | 1 |
| Tigela médica com instrumentos (Branca) | `TerjeSurgicalTool_White` | 1 |
| Kit cirúrgico de campo | `TerjeSurgicalKit` | 5 |
| IFAK | `TerjeFirstAidKitIndividual_Black` | 10 |
| AFAK | `TerjeFirstAidKitAdvance_Black` | 20 |

### 📋 Resumo rápido de tratamentos

| Problema | Tratamento recomendado |
|---|---|
| 🤧 Gripe / Pneumonia | Antibióticos e repouso em local aquecido nos casos leves |
| 🤢 Intoxicação alimentar | Carvão ativado e medicamentos específicos |
| ☣️ Intoxicação química | Rombiopental, Neirocetal ou AntiChem |
| 🧟 Vírus zumbi | Zivirol |
| 🩸 Sepse | Antibióticos de nível 3 |
| 🐺 Raiva | Rabinoline, Rifampicin ou Rabinucoline |
| 🟣 Hematomas | Viprosal, Capsicum ou Finalgon |
| 🔫 Ferimentos por bala | Bandagem e cirurgia |
| 🫀 Lesões internas | Equipamentos cirúrgicos |
| 🧠 Concussão | Noopept ou Neirox |
| 🩸 Sangramento | Bandagens e medicamentos hemostáticos |
| 🩸 Perda de sangue | Medicamentos para regeneração sanguínea |
| 😣 Dor | Analgésicos |
| 💊 Overdose | Água e interrupção do uso de medicamentos |
| 🧠 Saúde mental | Antidepressivos |
| 🌙 Falta de sono | Descanso e bebidas de recuperação |

---

## ⚠️ Avisos importantes

- Os valores de duração representam o tempo de efeito indicado na documentação do mod.
- O valor de overdose é o parâmetro de overdose indicado para cada medicamento.
- A duração do medicamento não representa necessariamente o tempo total para curar uma doença.
- A documentação não especifica uma quantidade universal de doses para todas as doenças.
- Os procedimentos cirúrgicos dependem da eficiência dos equipamentos utilizados.
- A disponibilidade dos itens depende da configuração e da versão instalada no servidor.

---

<p align="center">

**🏥 [BR] ZERO DAWN**

*Sobreviver não é apenas lutar. É saber cuidar da própria saúde.*

**Boa sorte, sobrevivente!**

</p>

---

### 📚 Referências oficiais

- [Terje Medicine — Documentação oficial](https://github.com/TerjeBruoygard/TerjeMods/tree/master/WIKI/en/Medicine)
- [Terje Medicine — Repositório do mod](https://github.com/TerjeBruoygard/TerjeMods/tree/master/TerjeMedicine)
- [Terje Radiation — Repositório do mod](https://github.com/TerjeBruoygard/TerjeMods/tree/master/TerjeRadiation)
