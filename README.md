# Painel de Estudos

Site estático para acompanhar simulados e redações do vestibular. Funciona direto no navegador, sem servidor e sem login.

## O que faz
- Lançamento de simulados por modelo de prova (ENEM, ENEM Dia 1 / Dia 2, FAMERP etc.), com meta por modelo e por área.
- "Simulados completos": junta Dia 1 + Dia 2 do mesmo simulado e mostra a evolução de cada dia e do total, avisando quando falta um dia.
- Evolução em porcentagem ou em número de acertos, por área.
- Redações com as 5 competências, filtro Todas / Escritas / Reescritas e efeito da reescrita.
- Conclusões calculadas no próprio site: área que mais melhorou, que mais caiu e em que mais erra (todos os simulados, últimos 3 ou último).

## Seus dados
Ficam só no navegador (localStorage). Nada é enviado para servidor. Para não perder:
**Configurações (engrenagem) → Exportar dados** baixa um arquivo `.json`; **Importar dados** restaura em outro navegador ou aparelho.

## Publicar no GitHub Pages
Settings → Pages → Deploy from a branch → `main` / `(root)`.
