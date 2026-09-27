# Ardus — visualizador do projeto

Página que o cliente abre pelo **QR do projeto** gerado no Ardus: mostra o projeto em 3D
(e, no celular, em realidade aumentada).

- O modelo 3D fica no servidor da empresa e só é entregue enquanto o link vale (30 dias).
- Esta página não guarda projetos nem dados — só lê o link recebido no endereço (`?v=`).
- A chave presente no código é a **publicável** do Supabase (feita para ser pública).

Gerada por `scripts/gerar-visualizador.mjs` no repositório do Ardus.
