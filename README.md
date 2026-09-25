# Dashboard Tributário, Performance & Governança Patrimonial

Simulador financeiro, tributário e sucessório interativo para planejamento patrimonial familiar, estruturação de holdings, apuração de IRPF, ganho de capital (GCAP), ITCMD, ITBI, previdência (PGBL/VGBL) e governança imobiliária.

---

## 🚀 Acesso Online (GitHub Pages)

Este projeto foi construído em arquitetura **Single Page Application (SPA) 100% autônoma e serverless**, sem dependências externas de backend.

Para publicar e acessar diretamente por link público ou privado via **GitHub Pages**:

1. Acesse as **Settings** deste repositório no GitHub.
2. No menu lateral esquerdo, clique em **Pages**.
3. Em **Build and deployment > Branch**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
4. Clique em **Save**.
5. Em poucos segundos, seu link público estará ativo no formato:
   ```
   https://<seu-usuario>.github.io/<nome-do-repositorio>/
   ```

---

## 📊 Módulos Integrados

1. **Simulador Master de Deduções da Receita Federal (10 Cards Reativos)**:
   - Estrutura Familiar (`Individual` vs `Casal`).
   - Regime de Casamento (`Comunhão Parcial`, `Separação Total`, `Comunhão Universal`, `Separação Obrigatória 70+`, `União Estável`).
   - Renda Bruta Anual Tributável com recálculo em tempo real de tetos e deduções.
   - Seguro de Vida (Homem-Chave / D+30 Isento).
   - Seguro Saúde e Despesas Médicas (100% sem teto).
   - Previdência Complementar (PGBL com teto de 12% da renda vs VGBL sucessório).
   - Administração de Aluguel e IPTU (Art. 31 da Lei nº 7.713/88).
   - Educação / Instrução (Teto legal R$ 3.561,50/pessoa).
   - Dependentes Legais e Saúde/Terapias TEA.
   - Pensão Alimentícia Judicial (100% integral).
   - Previdência Oficial (INSS / RPPS).
   - Livro-Caixa do Profissional Autônomo.
   - Incentivos Fiscais e Doações Diretas (Teto de até 6% do IR devido).

2. **Acervo Imobiliário & Gestão Centralizada**:
   - Tabela de imóveis com 23 colunas condensadas e centralizadas.
   - Cálculo de valor de aquisição, valor de mercado, aluguel mensal, taxa de administração (0% a 10%), IPTU e condomínio segregados.
   - Modais de Governança:
     - 📜 **Cláusulas Restritivas** (Inalienabilidade, Impenhorabilidade, Incomunicabilidade, Reversão e Dispensa de Colação).
     - 👥 **Distribuição de Titularidade** por Cotista/Herdeiro.
     - ⚙️ **Usufruto Vitalício** com reserva de direitos políticos e econômicos.

3. **Comparativos Tributários**:
   - **Locação**: Pessoa Física (Carnê-Leão até 27,5%) vs Holding Familiar (Lucro Presumido 11,33% / Lucro Real).
   - **Venda de Imóveis**: GCAP Pessoa Física (15% a 22,5%) vs Holding (6,73% / 5,93% atividade imobiliária).
   - **Sucessão & Transmissão**: Inventário Judicial / Extrajudicial (Custas + Honorários + ITCMD) vs Doação de Quotas com Reserva de Usufruto.

4. **Performance Histórica & Custo de Oportunidade**:
   - Comparativo de Retorno Total do Imóvel (Ganho de Capital + Yield Líquido de Locação) vs **IPCA** vs **CDI (100% e 85% Líquido)**.

---

## 🎨 Identidade Visual & Acessibilidade

- **Padrão Estrito Preto & Branco (Monocromático)**: Alto contraste, elegância corporativa e legibilidade impecável tanto em **Modo Claro** quanto em **Modo Escuro**.
- **Bordas Delimitadas**: Traços finos e nítidos (`1px solid #000000`) contornando abas, cartões, caixas de preenchimento e botões de ação.
- **Responsivo**: Compatível com navegadores desktop, tablets e smartphones.

---

## ⚖️ Fundamentação Legal Aplicada

- **Código Civil (Lei nº 10.406/2002)**: Arts. 1.658 (Comunhão Parcial), 1.687 (Separação Total), 1.667 (Comunhão Universal), 1.641 (Separação Legal), 1.829 (Ordem de Vocação Hereditária), 1.390 a 1.411 (Usufruto), 1.911 (Cláusulas Restritivas).
- **Legislação Tributária Federal**: Lei nº 7.713/1988 (IRPF e Deduções de Locação Art. 31), Lei nº 9.250/1995 (Deduções IRPF), Lei nº 9.718/1998 e Lei nº 12.973/2014 (Tributação da Atividade Imobiliária).
- **Jurisprudência Vinculante**: STF Temas 498 e 809 (União Estável), STF Súmula 377, STJ REsp 1.382.170 (Sucessão na Separação Total).
