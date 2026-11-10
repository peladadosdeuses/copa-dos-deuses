# Copa dos Deuses · PDD

Site da Copa dos Deuses (02/12, 21h às 00h): sorteio dos times por estrela e posição, tabela com simulação e chance de semi, jogos com notas dos jogadores, semis, final e craque da copa.

- Hospedagem: GitHub Pages (branch `main`, pasta raiz).
- Dados: Firebase Firestore. Login com Google só pra ditadura.

## Configurar
1. Em `config.js`, cole o `firebaseConfig` e os e-mails da ditadura.
2. No Firebase, em Firestore > Regras, cole o conteúdo de `firestore.rules` (com os mesmos e-mails) e publique.
3. Em Authentication > Configurações > Domínios autorizados, adicione `davialcoforado.github.io`.
