# Portal Rito OSS — Anexo V

Mesmo modelo do [Fala Saúde 10](https://falasaude10.grok.me/): site que o Grok Build publica em `*.grok.me`.

O endereço `algo.grok.me` **não é criado por commit no GitHub**. Ele nasce do botão **Publicar** no Grok (modo Build), igual foi feito com o Fala Saúde 10.

## Como publicar em grok.me (igual ao Fala Saúde 10)

1. No Grok (grok.com), abra o modo **Build** (o mesmo da seção do Fala Saúde 10).
2. Peça para o Grok usar os arquivos da pasta `public/` deste projeto (index.html, styles.css, data.js, shim.js, app.js).
3. Quando o preview abrir e o login funcionar (`relator` / `Relator#2026`), clique em **Publicar**.
4. Confirme o endereço (`ritooss.grok.me` ou o que o Grok mintar).
5. Acesso: **qualquer um com o link** (banca) — não deixe aberto na internet inteira se houver dados das propostas.
6. Publique. O link é o portal.

## Logins iniciais

| Usuário | Senha | Papel |
|---|---|---|
| relator | Relator#2026 | administrador |
| avaliador | Avalia#2026 | tríade |
| apoio | Apoio#2026 | cadernos |
| comissao | Comissao#2026 | ranking |

Troque as senhas na primeira sessão. O relator cadastra um usuário por pessoa.

## Limite do grok.me

Como o Fala Saúde 10, o grok.me serve **página estática**. O estado fica no navegador (localStorage). Os três avaliadores no **mesmo computador/perfil** compartilham o certame. Em computadores diferentes, cada um tem uma cópia — use Backup JSON para unificar, ou o servidor Node (`portal_rito_oss/server.js`) se precisar de simultaneidade real.

## Nota do eixo

A nota do eixo é a **pontuação que o Anexo V atribui ao conceito** (A/B/C ou A/C), somada nos subcritérios. Não há ponto fora do conceito.
