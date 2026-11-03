# Knowledge Extractor — Releases

Este repositório guarda apenas as **versões publicadas** do Knowledge Extractor (aplicativo desktop
para macOS). O código-fonte fica em um repositório privado; aqui ficam os instaladores, os pacotes
de atualização e as notas de cada versão.

## Instalar pela primeira vez

1. Abra a [última release](https://github.com/ai-driven-projects/knowledge-extractor-releases/releases/latest).
2. Baixe o instalador do seu Mac (menu Apple > Sobre Este Mac > Chip ou Processador):
   - **Apple Silicon** (M1, M2, M3, M4…): `KnowledgeExtractor-osx-arm64-Setup.pkg`
   - **Intel**: `KnowledgeExtractor-osx-x64-Setup.pkg`
3. Abra o `.pkg` e siga o instalador. O app vai para Aplicativos.

O app não é notarizado pela Apple. Se o macOS disser que não pode abrir o pacote ou o app, clique
nele com o **botão direito** e escolha **Abrir** (ou vá em Ajustes do Sistema > Privacidade e
Segurança > **Abrir Mesmo Assim**). Isso só é preciso na primeira vez.

Sem instalador, também dá para usar o `KnowledgeExtractor-<arquitetura>-Portable.zip`: descompacte e
arraste o app para Aplicativos.

## Atualizações

Não é preciso voltar aqui a cada versão. O app procura uma versão nova ao abrir e a cada 6 horas
(e em Configurações > Atualizações, a qualquer momento), baixa em segundo plano e avisa com uma
faixa no topo. "Reiniciar e atualizar" troca o app no lugar e reabre nas mesmas abas; quem não
clicar recebe a versão nova ao fechar o app. Com execuções rodando, a troca espera elas terminarem.

Os demais arquivos de cada release (`*.nupkg`, `releases.*.json`, `assets.*.json`, `RELEASES-*`) são
os que o próprio app usa para se atualizar.
