# Branch de dados

Guarda só `defesa-civil.json`, atualizado pelo workflow "Alertas da Defesa Civil (JF)".
Fica fora de `main` para que cada atualização não gere deploy na Vercel.
O `vercel.json` daqui manda a Vercel ignorar qualquer commit desta branch.
O histórico é reescrito (1 commit só) a cada atualização, então não cresce.
