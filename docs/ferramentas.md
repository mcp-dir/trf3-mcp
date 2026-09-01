# Ferramentas

Jurisprudência TRF3 expõe 3 ferramentas (todas somente leitura).

### 1. `jurisprudencia_buscar`
**Input**: `termo`, `tipo` (opcional), `tribunais` (opcional), `data_de` (opcional), `data_ate` (opcional), `ordenar` (opcional), `max` (opcional)

Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese.

### 2. `jurisprudencia_sumulas`
**Input**: `termo`, `max` (opcional)

Busca SÚMULAS (incluindo vinculantes) por termo.

### 3. `jurisprudencia_documento`
**Input**: `id` (opcional), `numeracao` (opcional), `tribunal` (opcional), `ids` (opcional)

Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo).

## Prompts de exemplo

```
Pesquise jurisprudência do TRF3, que responde pela Justiça Federal em São Paulo e Mato Grosso do Sul, direto do Claude, ChatGPT ou do seu agente. Previdenciário, tributário federal e execução fiscal, com órgão julgador, relator, data, o trecho que casou a busca e o link oficial. A mesma conexão alcança outros 16 tribunais quando a tese passa pelas cortes superiores. Grátis, sem login.
Jurisprudência do TRF3 sobre aposentadoria especial por insalubridade
Como o TRF3 vem decidindo prescrição em execução fiscal?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```
