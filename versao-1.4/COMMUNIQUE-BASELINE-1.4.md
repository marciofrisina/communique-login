# Communique Login — Baseline 1.4

Status: primeiro experimento da versão 1.4, iniciado em 3 de agosto de 2026.

Arquivo de entrada: `index.html`

Esta versão parte da 1.3 e substitui o melting por um cartão de duas faces. Depois da autenticação simulada, a janela gira 180 graus no eixo vertical e apresenta um resumo da conta.

- Notificações sorteadas entre 10 e 200.
- Acesso sorteado a uma seleção sem repetição de 1 a 7 países.
- Lista restrita a Brasil, MOG, Chile, Colombia, Peru, Bolivia, Paraguai, Costa Rica, El Salvador, Guatemala, Honduras e Panama; quatro ou mais acessos são distribuídos em duas colunas.
- Painel fixo de notificações com 112 × 112 px e número centralizado.
- `Last Access` e sua data em uma única linha, sem metadados do navegador.
- `System Update 7.0.2` e sua data em uma única linha.
- Botão `Go to Communique`, que recarrega o protótipo.

O campo de acesso usa o rótulo `User or Email` e apresenta uma pequena bandeira circular. O país é estimado pelo IP público e combinado com o timezone IANA do navegador; se a consulta externa falhar, um mapa local de timezones fornece o fallback.

Credenciais do protótipo:

- User: `c`
- Password: `c`

O objeto âmbar seleciona uma estrela em um catálogo de 55 possibilidades, mostra sua constelação e distância aproximada, e mantém um histórico local das últimas 12 escolhas para reduzir repetições.

Pontos de restauração preservados:

- Versões anteriores: `../versao-1.0/`, `../versao-1.1/`, `../versao-1.2/` e `../versao-1.3/`.
- Código experimental original que originou esta entrega: `../ultima-opcao-plasma/`
