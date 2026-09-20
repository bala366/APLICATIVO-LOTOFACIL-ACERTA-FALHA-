# Lotofácil Falhas V2 — corrigido

Projeto Android para GitHub Actions.

## IMPORTANTE
Este ZIP foi montado com os arquivos do projeto **na raiz do ZIP**. Ao extrair, envie para a raiz do repositório: `.github`, `app`, `build.gradle`, `settings.gradle`, `gradle.properties` etc. Não deixe tudo dentro de uma subpasta no GitHub.

## Motor
- lê TXT/CSV de resultados da Lotofácil;
- calcula as 10 falhas de cada concurso;
- analisa os 3 últimos;
- usa padrão F/S, Pareto, influência lag 1/2/3, duplas, frequência e tendência;
- aprende quantidade de falhas repetidas;
- executa backtest cego walk-forward;
- entrega 10 falhas projetadas e o complemento de 15 dezenas;
- gera PDF do volante na pasta Download: verde = jogo de 15; vermelho = 10 falhas.

## Compilar
1. Crie um repositório vazio no GitHub.
2. Extraia este ZIP no computador.
3. Envie **o conteúdo da pasta extraída** para a raiz do repositório.
4. Abra **Actions**.
5. Rode `Compilar APK - Lotofacil Falhas V2 CORRIGIDO`.
6. Baixe o artefato `LOTOFACIL-FALHAS-V2-CORRIGIDO-APK`.

ApplicationId mantido: `com.lotofacil.falhas`
VersionCode: 2
