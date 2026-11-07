# Dobra — APKs de teste

Distribuição pública de APKs de teste. Apenas README, `latest.json` e APKs nas Releases; sem código-fonte separado, ZIP ou chaves de assinatura.

[Descarregar Dobra 0.3.0-test](https://github.com/Snoozept/dobra-releases/releases/download/v0.3.0-test/dobra-amostra.apk) · [Notas](https://github.com/Snoozept/dobra-releases/releases/tag/v0.3.0-test)

## Nova curva e novas terras
200 níveis. Dobras realmente necessárias, não apenas limites maiores:
- 1–15: 1; 16–20: 2; 21–30: 3; 31–50: 4.
- 51–79: 5, com consolidação e mais combinações; 80–200: 6, sem regressão brusca após 100.

No início exato do nível 50 chega o Bosque das Sementes: cartão com folhas, árvores dobradas e Pip com casaco turquesa e emblema de folha. No início do 100 chegam as Ilhas do Céu: cartão de nuvem, nuvens/lanternas físicas e casaco ameixa com estrela. Mapa com previsões de dobras/terras e transições narrativas em dez idiomas. A identidade do Pip mantém-se.

## Instalar / atualizar
Android API 23+ com WebView atualizado e WebGL2; retrato e ecrã cheio. APK universal de teste, assinada com a mesma chave de debug de 0.1/0.2. Instalar por cima, sem desinstalar. O Android pede confirmação; não existe instalação silenciosa.

O atualizador consulta [latest.json](https://raw.githubusercontent.com/Snoozept/dobra-releases/main/latest.json), oferece uma versão superior e verifica hash/app/versão/certificado antes do instalador. O jogo, as fontes e os 200 níveis funcionam offline; apenas a consulta/download de atualização usa rede.

Os 200 layouts foram revistos. A migração guarda a versão de conteúdo e conserva níveis concluídos/desbloqueados, posição e preferências. Um nível ainda incompleto recomeça no tabuleiro novo; não se apagam conquistas antigas nem se exige repetir níveis concluídos.

Menu, mapa/progresso, pausa, definições, som/vibração opcionais e movimento reduzido. Inglês em cada abertura; idioma apenas de sessão: English, 中文(简体), Español, हिन्दी, العربية, Português, বাংলা, Русский, 日本語, Français.

## Limites de teste
Os 200 mínimos exatos foram confirmados por provas de separadores verificadas e por BFS exaustivo independente, sem heurística. Sem duplicados estruturais sob oito simetrias. Traduções não revistas por nativos. Construção procedural e aumento de dobras não provam diversão, equilíbrio ou dificuldade sentida: a estratégia-base continua a aproximar faixas de canal. As regras aguardam validação da Solene.

Testes Chromium com toque CDP, não aparelho físico. Sem medição de FPS num Android médio e sem teste completo do instalador 2→3. O emulador anteriormente recusou instalar por timeout da verificação de integridade; não se contornou essa recusa.
