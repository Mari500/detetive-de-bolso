# 🕵️ Detetive de Bolso

Jogo de detetive para celular, direto no navegador. Sem instalar nada.

**Jogar:** https://mari500.github.io/detetive-de-bolso/

## Como funciona
- Você recebe mensagens de quem pediu ajuda e investiga pelo chat.
- **Examine a cena:** toque nos objetos da foto pra encontrar pistas.
- **Interrogue os suspeitos:** faça perguntas e mostre pistas pra pegar contradições.
- **Acuse:** diga quem foi, como fez, por quê e qual é a prova. Nota de 0 a 4.

## Casos
| | Caso | Dificuldade |
|---|---|---|
| ☕ | Caso Grão Fino | médio |
| 🦜 | A Arara Sumiu | fácil |
| 🏐 | O Troféu da Final | médio |
| 🌽 | Sal no Arraiá | médio |
| 💻 | Queda em Produção | difícil |
| 💍 | O Anel da Cachoeira | fácil |

## Ranking
Mais estrelas primeiro, depois o menor tempo. Cada acusação errada soma 1 minuto.

- **Neste aparelho:** sempre funciona. Cada pessoa no mesmo celular tem o seu perfil.
- **Online:** junta todo mundo que abrir o link. Usa o Firebase (Firestore):
  cole a configuração do projeto em `FIREBASE_CONFIG` no `index.html`
  e publique as regras de `firestore.rules` no console do Firebase.

## Estrutura
Tudo em um único arquivo, `index.html` (HTML, CSS e JavaScript puros, sem dependências).
Os casos ficam no array `CASES`: para criar um caso novo, copie um existente e edite os textos, as pistas e a cena (SVG, viewBox 360×300).
