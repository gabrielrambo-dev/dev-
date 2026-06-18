# CodeStudy Pro Mobile

App mobile de estudo de programação em HTML, CSS e JavaScript, preparado para APK com Capacitor pelo GitHub Actions.

## Como gerar APK

1. Envie todos os arquivos deste projeto para um repositório GitHub.
2. Vá em Actions.
3. Rode o workflow Build Android APK.
4. Baixe o APK em Artifacts.

## Correção aplicada

- Workflow aceita branches main e master.
- Node.js configurado em 22.
- Capacitor fixado em latest-7 para evitar quebra do Capacitor 8 em ambiente Android do GitHub.
- Java 17 configurado.
- Build usa --stacktrace para mostrar erro real caso falhe.
