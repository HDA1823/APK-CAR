# Caminho do Carro — Projeto Android

Projeto Android offline da atividade educativa **Caminho do Carro**.

## O que já está incluído
- Malha 6×6.
- Carro sempre inicia na linha inferior.
- Igreja, hospital, casa, parque e shopping em posições aleatórias.
- Nenhum objeto ocupa a linha inferior.
- Destino sorteado e indicado na pergunta.
- Setas na tela e teclado.
- Rastro vermelho do caminho percorrido.
- Obstáculos bloqueiam a passagem.
- Ao chegar ao destino, a atividade é encerrada e os comandos são bloqueados.
- Botão para gerar nova atividade.
- Funciona sem internet e sem Flask.

## Como gerar o APK
1. Abra esta pasta no Android Studio.
2. Aguarde o Gradle sincronizar e instalar os componentes solicitados.
3. Use **Build > Generate App Bundle(s) / APK(s) > Generate APK(s)**.
4. O APK será gerado em `app/build/outputs/apk/debug/`.

O projeto usa `minSdk 23` (Android 6.0) e `targetSdk 35`.
