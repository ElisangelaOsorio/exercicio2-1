# Auditoria do Relatório "Mapa de Atores — Atendimento URA Seguro-Desemprego CAIXA"

## TL;DR
- O relatório auditado contém **falhas factuais materiais** (CAIXAPAR citada como ator ativo apesar de extinta em 29/12/2021; CAGED tratado como sistema vivo apesar de substituído pelo eSocial em janeiro/2020) e **atribuições cruzadas inconsistentes** de acórdãos do TCU (o Acórdão 135/2024 é vinculado, no mesmo relatório, a três processos diferentes, sendo apenas um deles — TC-006.464/2022-0 — o verdadeiro), além de **fontes fracas** (YouTube) sustentando dado numérico crítico que o próprio TCU publica em portal oficial.
- A maioria dos elementos legais e os números de telefone (0800 726 0207, 0800 725 7474, 0800 726 0101, 158, Lei 7.998/1990, Lei 13.460/2017, Portaria MTP 671/2021 arts. 311-313) **está correta**, mas o mapa omite stakeholders relevantes (empregador no eSocial, INSS, Receita Federal, SINE, Serpro, ANPD/LGPD, Justiça do Trabalho/MPT, sindicatos, provedora de telecom 0800) e sobre-especifica tecnologias Microsoft genéricas sem nexo evidenciado com a URA do seguro-desemprego.
- O valor "R$ 35 bilhões anuais" está desatualizado: o gasto real foi de **R$ 45,7 bilhões em 2023** (Ipea/MTE); a estimativa para 2024, divulgada no 3º Relatório Bimestral de Avaliação de Receitas e Despesas, é de cerca de **R$ 53 bilhões só com seguro-desemprego** e **R$ 81,3 bilhões combinados com abono salarial**. O ano-base do Relatório CGU nº 925193 (origem do dado "2,641 milhões de requerimentos") é 2021 — não 2022, como o relatório auditado sugere; o relatório CGU de ano-base 2022 é outro documento (nº 1421234).

## Key Findings

### 1. Erros factuais identificados (alta gravidade)

**F1. CAIXAPAR — extinta há mais de 3 anos, citada como ator ativo**
- Trecho do relatório auditado: a CAIXAPAR é apresentada como "braço de participações da Caixa" relevante para o ecossistema de pagamento do seguro-desemprego.
- Realidade: a CAIXA Participações S.A. (CAIXAPAR) foi **incorporada pela CAIXA em 29/12/2021, com extinção da Companhia**, com atos arquivados na JUCIS/DF em 05/01/2022 (fonte oficial: caixa.gov.br/caixa-par). Além disso, seu objeto social era "negócios relativos a participações societárias de longo prazo" — sem relação operacional com pagamento de benefícios sociais.
- Classificação: **erro factual + inferência mal-suportada**. Correção: remover CAIXAPAR do mapa; o agente pagador é a própria CAIXA (caixa.gov.br/beneficios-trabalhador/seguro-desemprego).

**F2. CAGED tratado como sistema operacional ("erro no CAGED")**
- Trecho: refere-se a falhas/erros "no CAGED" como causa atual de bloqueio do benefício.
- Realidade: a Portaria SEPRT 1.127/2019 substituiu o CAGED pelo eSocial a partir da competência **janeiro/2020 para empresas dos Grupos 1, 2 e 3** (gov.br/esocial). O CAGED permanece apenas para entidades do Grupo 4 (órgãos públicos e organizações internacionais ainda não obrigadas ao eSocial). Tratar o CAGED como sistema-fonte corrente é tecnicamente incorreto para a esmagadora maioria dos casos.
- Classificação: **erro factual / desatualização técnica**. Correção: substituir por "eSocial (que substituiu o CAGED a partir de jan/2020 para os Grupos 1-3)".

**F3. Atribuição cruzada e inconsistente de acórdãos/processos do TCU**
- O relatório cita simultaneamente, na referência [12], **"Acórdão 135/2024" ligado ao processo "TC 008.443/2024-6"**, e ainda referencia "036.684/2019-8" e "TC 031.690-2022-0" como se relacionados ao mesmo achado.
- Realidade verificável: o **Acórdão 135/2024-TCU-Plenário** vincula-se **exclusivamente ao processo TC-006.464/2022-0**, sessão de 31/01/2024, relator **Ministro-Substituto Marcos Bemquerer Costa**, unidade técnica **Unidade de Auditoria Especializada em Previdência, Assistência e Trabalho (AudBenefícios)**, auditoria integrada na então Strab/MTP, período **janeiro de 2018 a junho de 2022** (Aviso nº 51-GP/TCU; pesquisa.apps.tcu.gov.br). Os números "TC 008.443/2024-6", "036.684/2019-8" e "TC 031.690-2022-0" **não constam como processos vinculados a esse acórdão** e parecem ter sido cruzados por engano.
- Classificação: **atribuição incorreta**. Correção: o relatório deve referenciar apenas TC-006.464/2022-0 ao falar do Acórdão 135/2024.

**F4. Confusão entre dois relatórios distintos da CGU**
- O relatório atribui o achado "2.3.3" (pagamentos com indício de irregularidade) e o número "2.640.935 requerimentos (4/jan a 8/out/2021)" às "contas de 2022 do Ministério".
- Realidade: o número 2,641 milhões de requerimentos no período 04/01 a 08/10/2021 é tratado no **Relatório de Avaliação CGU nº 925193, cujo ano-base é o exercício de 2021** (avaliação de prestação de contas FAT 2021). O relatório de ano-base 2022 é o nº 1421234, com escopo diferente (avaliação do Programa do Seguro-Desemprego no ano de 2022). Os títulos de achados recuperáveis do PDF 925193 são 2.1.1 ("FRAGILIDADES NA AVALIAÇÃO DOS RESULTADOS DAS POLÍTICAS PÚBLICAS FINANCIADAS COM RECURSOS DO FAT"), 2.2.1 ("FRAGILIDADES NOS CONTROLES INTERNOS RELATIVOS AO RECONHECIMENTO, MENSURAÇÃO E EVIDENCIAÇÃO DAS DESPESAS COM SEGURO DESEMPREGO") e 2.2.4 — a numeração "2.3.3" não foi confirmada verbatim no PDF.
- Classificação: **atribuição incorreta + lacuna de evidência**. Correção: identificar inequivocamente qual relatório CGU (925193, ano-base 2021) sustenta o número 2,641 milhões e qual achado o contém — sem afirmar "2.3.3" sem confirmação direta no PDF.

**F5. Dado de R$ 35 bilhões/ano desatualizado**
- Trecho: "supera a marca de R$ 35 bilhões anuais".
- Realidade: o próprio Acórdão 135/2024 menciona "na casa dos R$ 35 bilhões ao ano" como referência histórica, mas os dados recentes do MTE/IPEA são significativamente maiores. **R$ 45,7 bilhões em 2023** (Ipea/MTE, divulgado em 09/06/2025: "Mudanças no seguro-desemprego e abono salarial geraram economia, mas reduziram proteção aos trabalhadores"). Para 2024, o **3º Relatório Bimestral de Avaliação de Receitas e Despesas Primárias (MTE/2024)** projeta cerca de **R$ 53 bilhões** apenas com seguro-desemprego e o combinado seguro-desemprego + abono em **R$ 81,3 bilhões**, conforme reportado pelo Poder360 ("As despesas de 2024 com seguro-desemprego e abono combinadas são estimadas em R$ 81,3 bilhões, de acordo com o último relatório de avaliação de receitas e despesas primárias").
- Classificação: **lacuna de atualidade + ausência de fonte oficial recente**. Correção: usar valor atualizado com fonte primária (Ipea/MTE/SIOP/Relatório Bimestral).

### 2. Fontes fracas ou ausentes

**F6. YouTube como fonte primária para dado numérico crítico**
- O relatório auditado sustenta a afirmação "cerca de 300.000 solicitações com irregularidades" referenciando um **vídeo do YouTube (referência 2)**.
- Existe fonte oficial direta: notícia institucional do TCU em portal.tcu.gov.br ("Inconsistências no Seguro-Desemprego causaram prejuízo à administração pública", 31/01/2024), cujo texto verbatim afirma: *"O trabalho constatou inconsistências em mais de 300 mil solicitações de seguro-desemprego, com possíveis pagamentos de parcelas indevidas do benefício, em desacordo com o art. 4º da Lei 7.998/1990, no período de 2018 a junho de 2022."* O mesmo número é noticiado pelo Poder360, Exame, Metrópoles e O Antagonista a partir do acórdão.
- Classificação: **fonte fraca**. Correção: substituir referência ao YouTube pela notícia oficial do TCU e/ou pelo acórdão.

**F7. Uso de API/agregador comercial (Infosimples) para sustentar dados de pagamentos do Portal da Transparência**
- A informação sobre lotes (R$ 168.568.459,03; "Lote Nº 1695"; "Lote Nº 989" doméstico) deveria ser consultada diretamente no Portal da Transparência (portaldatransparencia.gov.br), com filtro por UG 380916 (CGFAT) e ação 00H4 (Seguro-Desemprego ao Trabalhador). Sem o link/consulta primária, a plausibilidade dos valores é defensável (alinhados com lote de pagamento típico do FAT, que tem despesa mensal média de cerca de R$ 3-4 bilhões em 2023-24), mas a atribuição numérica permanece sem âncora primária verificável.
- Classificação: **fonte fraca / lacuna de fonte primária**. Correção: trazer link direto a documento de execução de despesa pública no portaldatransparencia.gov.br.

### 3. Inferências mal-suportadas

**F8. "Tecnologias Microsoft" como exigência específica da URA do seguro-desemprego**
- Trecho: "Azure Active Directory, Windows Failover Cluster, PowerShell, System Center Service Manager/Orchestrator/Operations Manager, KMS, NLB, HTTP/SSL".
- Avaliação técnica: esse stack é típico de infraestrutura **corporativa Windows genérica** (gestão de identidade, alta disponibilidade, monitoramento), não específico de plataformas de contact center/URA. Plataformas reais de URA usadas no setor financeiro brasileiro tipicamente envolvem Genesys, Cisco UCCE/CVP, Avaya Aura/Experience Portal ou similares — nenhum desses é citado. A inferência de que esse stack seja "a tecnologia da URA do seguro-desemprego" não é sustentada por edital citado.
- Classificação: **inferência mal-suportada + sobre-especificação**. Correção: ou nomear o edital específico (com número e órgão) e citar trecho verbatim, ou reformular como "exigências gerais de infraestrutura de TI do contratante", sem ligar à URA do seguro-desemprego.

**F9. Métricas "29.000 minutos mensais", "2.000 atendimentos de chat", "PA × 1020"**
- Sem citação do edital específico (número, objeto, órgão, ano), essas métricas não podem ser verificadas. A fórmula "nº de PA × 1020" sugere 1.020 minutos por PA/mês — compatível com 8h/dia × 22 dias × ~77% de ocupação, mas isso é especulativo na ausência da fonte primária.
- Classificação: **lacuna de evidência**. Correção: citar edital com número e link no Comprasnet/transparência.

### 4. Atores omitidos relevantes (lacunas no Mapa de Stakeholders)

**Bastidores institucionais ausentes:**
- **Empregador**: alimenta o eSocial; sua omissão ou erro nos dados gera os bloqueios de habilitação. O Acórdão 135/2024 destaca exatamente este nexo (recontratações em <90 dias presumidamente fraudulentas — Portaria MTP 671/2021 arts. 311 a 313).
- **INSS**: cruzamento de bases para detectar acumulação indevida (pensão por morte, auxílio-doença, BPC). Mencionado expressamente no Acórdão 135/2024.
- **Receita Federal do Brasil**: base CPF/CNIS, validação fiscal.
- **Serpro**: TI governamental crítica (assinatura digital ICP-Brasil, infraestrutura).
- **SINE (Sistema Nacional de Emprego)**: canal presencial estadual/municipal de atendimento ao trabalhador.

**Frontstage/atendimento ausente:**
- **Empresa terceirizada de contact center** vencedora da licitação da Caixa (operadora real dos atendentes humanos da URA) — o relatório auditado não a nomeia.
- **Operadora(s) de telecom** que provê(em) a infraestrutura 0800 e roteamento das chamadas.

**Órgãos de controle/regulação ausentes:**
- **ANPD (Autoridade Nacional de Proteção de Dados)**: regula tratamento de dados pessoais (LGPD) — crítica para um serviço que coleta CPF e dados sensíveis em URA.
- **Ministério Público do Trabalho (MPT)**, **Defensoria Pública da União**, **Justiça do Trabalho/TST**: o próprio Acórdão 135/2024 dedica recomendações ao tratamento de "pagamentos por ordem judicial", evidenciando o papel do Judiciário trabalhista como ator.
- **Sindicatos de trabalhadores** beneficiários e **sindicato da categoria de teleatendimento** (Sintratel-SP e congêneres) — relevantes em uma perspectiva de stakeholder map.
- **Banco Central**: regulador do sistema bancário onde a CAIXA opera contas de crédito.

### 5. Itens verificados como CORRETOS no relatório auditado

- **0800 726 0207** como número do "Atendimento CAIXA ao Cidadão" para PIS, FGTS, Seguro-Desemprego e benefícios sociais: **correto** (caixa.gov.br/atendimento). Observação: o número **111** é distinto e atende prioritariamente Cartão Cidadão/Bolsa Família; não é "o" número exclusivo do Atendimento Caixa Cidadão, embora seja oferecido em paralelo.
- **Ouvidoria CAIXA 0800 725 7474**: **correto** (confirmado verbatim no site oficial caixa.gov.br/atendimento).
- **SAC CAIXA 0800 726 0101**: **correto** (confirmado verbatim no site oficial caixa.gov.br/atendimento).
- **Central Alô Trabalho 158** vinculada ao MTE: **correto e ativo**. A Agência Gov publicou em agenciagov.ebc.com.br/noticias/202508 que *"A Central de Atendimento 'Alô Trabalho'…encerrou o primeiro semestre de 2025 com 1.726.914 atendimentos realizados até 30 de junho"*; horário ampliado para 7h-22h em mar/2024.
- **Portaria MTP 671/2021, arts. 311 a 313**, sobre presunção de fraude em recontratações em menos de 90 dias: **correto**. Citados verbatim no Acórdão 135/2024 ("nos termos dos arts. 311 a 313 da Portaria/MTP 671/2021").
- **Lei 7.998/1990** como lei do Seguro-Desemprego/FAT: **correto** (planalto.gov.br).
- **Lei 13.460/2017** como Código de Defesa do Usuário de Serviços Públicos: **correto** (planalto.gov.br/L13460).
- **Acórdão 135/2024-Plenário; processo TC-006.464/2022-0; relator Ministro-Substituto Marcos Bemquerer Costa; período jan/2018 a jun/2022; unidade técnica AudBenefícios**: **todos corretos** (Aviso nº 51-GP/TCU). Observe que o cargo correto é "Ministro-**Substituto**".
- **Causa-raiz apontada pelo TCU**: o portal do TCU registra verbatim *"Os problemas foram causados principalmente por falhas na governança da relação contratual entre a Secretaria do Trabalho (Strab) e a Dataprev"* — corretamente refletido no relatório auditado.
- **CGFAT (Coordenação-Geral de Recursos do FAT), UG 380916, vinculada ao MTE**: **correto** (Portaria de 15/02/2019, DOU; Portal da Transparência).
- **CAIXA como Agente Pagador do Seguro-Desemprego**: **correto** (caixa.gov.br/beneficios-trabalhador/seguro-desemprego, citando Lei 7.998/1990).
- **Níveis Gov.br Bronze, Prata e Ouro** com exigência de Prata/Ouro para serviços sensíveis: **correto** (Agência Gov/MGI). O seguro-desemprego via Emprega Brasil/Carteira Digital requer conta Prata ou superior na prática para validar identidade.

## Details — Tabela síntese das falhas

| # | Trecho do relatório auditado | Classificação | Justificativa baseada em fonte oficial | Correção sugerida |
|---|---|---|---|---|
| F1 | "CAIXAPAR" como ator no ecossistema de pagamento | Erro factual + inferência mal-suportada | CAIXAPAR foi extinta em 29/12/2021 (caixa.gov.br/caixa-par) e seu objeto era participações societárias, não pagamento de benefícios | Remover do mapa; agente pagador é a própria CAIXA |
| F2 | "erro no CAGED" tratado como sistema corrente | Erro factual (desatualização) | CAGED substituído pelo eSocial em jan/2020 para Grupos 1-3 (Portaria SEPRT 1.127/2019; gov.br/esocial) | Trocar por "eSocial" |
| F3 | Acórdão 135/2024 vinculado a "TC 008.443/2024-6", "036.684/2019-8" e "TC 031.690-2022-0" | Atribuição incorreta | Acórdão 135/2024 vincula-se exclusivamente ao TC-006.464/2022-0 (pesquisa.apps.tcu.gov.br) | Citar apenas TC-006.464/2022-0 |
| F4 | "2.640.935 requerimentos em 4/jan-8/out/2021" vinculados ao "Achado 2.3.3" das contas de 2022 | Atribuição incorreta + lacuna | O dado é do Relatório CGU 925193, ano-base 2021; relatório de ano-base 2022 é o 1421234; achado "2.3.3" não confirmado verbatim no PDF | Identificar relatório CGU correto e citar achado pelo título verbatim |
| F5 | "supera R$ 35 bilhões anuais" | Lacuna de atualidade | R$ 45,7 bi em 2023 (Ipea/MTE); estimativa de ~R$ 53 bi em 2024 conforme 3º Relatório Bimestral de Avaliação de Receitas e Despesas (MTE/2024); combinado seguro-desemprego + abono = R$ 81,3 bi em 2024 | Atualizar com fonte primária recente |
| F6 | "300.000 solicitações com irregularidades" sustentado por vídeo YouTube | Fonte fraca | Notícia institucional do TCU (portal.tcu.gov.br, 31/01/2024) e o próprio Acórdão 135/2024-Plenário sustentam o dado verbatim | Substituir por fonte oficial TCU |
| F7 | Valores de lotes (R$ 168.568.459,03 etc.) via Infosimples | Fonte fraca | Portal da Transparência é a fonte primária (UG 380916, ação 00H4) | Trazer link direto |
| F8 | Stack Microsoft (Azure AD, SCOM/SCSM, KMS, NLB) como exigência da URA | Inferência mal-suportada | Stack genérico de TI corporativa, não específico de URA/contact center; plataformas reais do setor são Genesys/Cisco/Avaya | Citar edital específico ou reformular |
| F9 | "29.000 minutos mensais", "2.000 atendimentos chat", "PA × 1020" | Lacuna de evidência | Nenhum edital nomeado | Citar número e órgão do edital |

## Recommendations

**Etapa 1 — Correções obrigatórias antes de qualquer republicação do mapa:**
1. Remover CAIXAPAR; substituir por CAIXA (Vice-Presidência de Governo / Diretoria Executiva de Transferências de Benefícios e Serviços Sociais) como ator do backstage de pagamento.
2. Substituir "CAGED" por "eSocial (consolidado da RAIS/CAGED desde 2020)" em todas as menções operacionais correntes; manter "CAGED" apenas em referências históricas até 2019 ou para o Grupo 4.
3. Corrigir a vinculação do Acórdão 135/2024-Plenário exclusivamente ao processo **TC-006.464/2022-0**, relator **Ministro-Substituto Marcos Bemquerer Costa**, unidade técnica **AudBenefícios**; remover as referências cruzadas a "TC 008.443/2024-6", "036.684/2019-8" e "TC 031.690-2022-0" se não estiverem documentadas.
4. Substituir a referência ao vídeo do YouTube pela notícia institucional do TCU (portal.tcu.gov.br/imprensa/noticias/inconsistencias-no-seguro-desemprego-causaram-prejuizo-a-administracao-publica) e/ou pelo PDF do Acórdão 135/2024.

**Etapa 2 — Refinamentos de evidência:**
5. Identificar inequivocamente qual relatório da CGU (925193 ano-base 2021 vs 1421234 ano-base 2022) sustenta cada dado citado; abrir cada achado pelo seu título verbatim em vez de só pelo número (e não afirmar "2.3.3" sem confirmação direta no PDF).
6. Trazer os lotes de pagamento por consulta direta ao Portal da Transparência (UG 380916, programa "Promoção do Trabalho Decente e Economia Solidária", ação 00H4), removendo a Infosimples como fonte.
7. Atualizar a despesa anual do seguro-desemprego para o valor mais recente publicado pelo Ipea/MTE/SIOP (R$ 45,7 bi em 2023; ~R$ 53 bi estimado em 2024).

**Etapa 3 — Completar o mapa de stakeholders:**
8. Adicionar como atores: **empregador (eSocial), INSS, Receita Federal, Serpro, SINE, ANPD, MPT, Defensoria Pública da União, Justiça do Trabalho/TST, sindicatos de trabalhadores e o sindicato da categoria de teleatendimento, operadora(s) de telecom 0800, Banco Central** e — se identificável via Comprasnet/Edital — a **empresa terceirizada operadora do contact center** vencedora da licitação Caixa.

**Etapa 4 — Robustez técnica:**
9. Para o stack tecnológico da URA, ou citar o edital específico (número, objeto, órgão, ano) com trecho verbatim, ou substituir pela descrição de uma plataforma de contact center plausível (Genesys/Cisco/Avaya) sob a forma "tecnologias compatíveis com" — evitando inferir um stack Microsoft genérico como sendo "a URA".

**Benchmarks que mudariam essas recomendações:**
- Se a equipe localizar um edital específico da Caixa que de fato exija o stack Microsoft completo para a URA do seguro-desemprego (não apenas para a TI corporativa), F8 deixa de ser falha.
- Se localizar o PDF do CGU 925193 com o achado "2.3.3" e o número "2.640.935" verbatim, F4 reduz-se a desatualização de ano-base.

## Caveats
- Algumas verificações finais (PDF do CGU 925193, edital específico do contact center Caixa, identificação da empresa terceirizada vencedora) foram limitadas por bloqueio anti-bot em fetchers automatizados ou pela ausência de citação primária no relatório original. Onde os dados se sustentam apenas em cobertura de imprensa, isto é sinalizado.
- Esta auditoria não avalia questões cosméticas (formatação, ordem) — apenas substância factual, evidência, atribuição e completude.
- O número "111" da CAIXA atende prioritariamente Bolsa Família/Cartão Cidadão; o "0800 726 0207" atende a uma gama mais ampla (PIS, FGTS, seguro-desemprego, benefícios sociais). Ambos coexistem oficialmente, e a hipótese sugerida na auditoria original ("111 seria 'o' número correto") **não procede** — o 0800 726 0207 é, de fato, oficial e específico para benefícios trabalhistas como o seguro-desemprego.
- A divergência entre "R$ 53,5 bi" e "R$ 53 bi" para 2024 é menor (R$ 0,5 bi) e corresponde a versões diferentes do mesmo Relatório Bimestral de Avaliação de Receitas e Despesas; recomenda-se citar o valor diretamente do bimestre mais recente do MTE/SIOP no momento da republicação.