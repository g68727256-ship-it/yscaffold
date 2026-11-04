# YSHARKX7 Scaffold 1.8.9

Projeto-fonte experimental para Minecraft Forge 1.8.9 / Java 8, destinado a mundos proprios e testes autorizados.

## Estado real desta entrega
- Toggle por tecla configuravel em Options > Controls.
- Comandos `/yscaffold on`, `/yscaffold off`, `/yscaffold status` e `/yscaffold delay 1-10`.
- Procura um bloco na hotbar e tenta colocar sob o jogador quando encontra uma face solida adjacente.
- Contador simples de blocos colocados.

## Ainda nao implementado
- GodBridge assistido, rotacao inteligente, Eagle/Sneak automatico e menu grafico.
- A tecla Eagle e o comando Eagle apenas alternam uma variavel; nao executam sneak automatico.
- Nao ha bypass nem ocultacao de anticheat.
- Nao foi compilado ou testado nesta entrega. A compatibilidade real com Zalith 2/GL4ES precisa ser validada.

## Compilar pelo celular
1. Crie um repositorio vazio no GitHub e envie todos os arquivos desta pasta.
2. Abra Actions e execute `Build Forge 1.8.9 mod`.
3. Baixe o artefato `YSHARKX7-Scaffold-jar` se o workflow terminar com sucesso.
4. Extraia o artefato e pegue o JAR em `build/libs`.

## Instalar
Coloque o JAR compilado na pasta `mods` do perfil Forge 1.8.9 do Zalith. Faça backup e teste primeiro em mundo proprio.
