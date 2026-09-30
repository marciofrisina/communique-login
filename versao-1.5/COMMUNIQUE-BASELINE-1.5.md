# Communique Login — versão 1.5

Base: versão 1.4 local, preservada sem alterações. Credenciais do protótipo: c / c.

Lua removida, sem download de sua imagem. Fundo limitado a 30 FPS, DPR máximo 1 e orçamento de 1,6 milhão de pixels por canvas. Detalhes e brilhos reduzidos; geometria do cartão reutilizada. Pausa enquanto os campos estão focados ou a aba está oculta. Modo econômico manual persistido localmente e automático após desempenho lento sustentado (mais de 30 amostras lentas em 90 quadros); preferência de movimento reduzido e economia de dados respeitadas. Modo estático redesenha apenas ao redimensionar. Flip e resumo da conta preservados.

A redução de CPU/GPU precisa ser medida nos dispositivos afetados; não há percentual garantido.

## Validação

Chromium headless, viewport 1440 × 1000, DPR 2: canvas de 1440 × 1000; 29 renderizações em 1,1 s na última execução (limite de 30 FPS). Nenhum redesenho durante foco nos campos, modo econômico e movimento reduzido. Verificados login inválido/válido, mostrar senha, flip, persistência do modo econômico e alteração da preferência de movimento reduzido em tempo real. Layout conferido em 1440 × 1000 e 390 × 844. Pausa/retomada verificada com evento de visibilidade simulado; fallback automático verificado com custo de renderização artificial de 28 ms. Sem erros JavaScript. Não representa medição de CPU/GPU em dispositivos reais.
