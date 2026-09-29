# Mnemo

Uma base de conhecimento que roda no seu computador e dá memória pra sua IA.

Você coloca seus arquivos nele (PDF, Word, planilha, anotações) e o Mnemo lê e indexa tudo localmente. Aí você busca pelo sentido do que procura, não pela palavra exata. Cada resultado mostra o trecho e o arquivo de onde ele veio. Se a resposta não está nos seus documentos, ele diz que não encontrou em vez de inventar. Também dá pra conectar numa IA (Claude, Cursor e outras que aceitam MCP) pra ela consultar seus arquivos sozinha.

**Site:** [appmnemo.com](https://appmnemo.com)

## Quem faz isso, e por que cobra

Sou entusiasta de IA, não programador. O Mnemo foi construído conversando com o Claude: eu decidi o que ele precisava fazer, testei, apontei o que estava errado, e o código foi escrito por ele. Uso no meu dia a dia e funciona, mas é um projeto de entusiasta. Pode ter bug, e eu vou corrigindo conforme aparece.

O Mnemo é vendido só pra ajudar a custear uma parte do projeto. Não é uma empresa e não tenho a pretensão de virar uma.

## Baixar

O instalador é público, mas o app só abre com uma chave de ativação, que você recebe por e-mail ao apoiar o projeto em [appmnemo.com](https://appmnemo.com).

Baixe a versão mais recente em **[Releases](../../releases/latest)**:

| Sistema | Arquivo |
|---|---|
| Windows (64 bits) | `Mnemo-Setup-X.Y.Z.exe` |
| macOS (chip Apple, M1 ou mais novo) | `Mnemo-macOS-X.Y.Z.zip` |

Como o app não tem assinatura digital paga, o Windows e o macOS podem mostrar um aviso de segurança na primeira abertura. Isso é esperado.

## Instalar

- **Windows:** execute o instalador e siga os passos.
- **macOS:** descompacte o zip e arraste o `Mnemo.app` pra pasta Aplicativos.

Na primeira tela, cole a chave de ativação. No primeiro uso o Mnemo baixa os modelos de indexação, então precisa de internet só nessa hora. Depois disso, indexar e buscar funciona offline.

## O que ele faz

- Busca por significado, somada a busca por palavra-chave, com reranking dos resultados
- Lê Markdown, TXT, HTML, CSV, PDF, Word, Excel e PowerPoint
- Vários acervos independentes (vaults), um por cliente, projeto ou assunto
- Mapa que agrupa seus documentos por assunto, sem você organizar nada
- Conexão com IAs via MCP
- Sincronização automática: editou um arquivo, ele reindexa sozinho

## Privacidade

Seus arquivos e suas buscas ficam no seu computador. O que o app conversa com a internet é só a ativação da licença (a chave e um identificador anônimo da máquina) e a checagem de versão nova.

## Planos

| | Preço | O que inclui |
|---|---|---|
| Licença | R$ 50 | Versão atual completa, uso vitalício |
| Fundador | R$ 100 | Tudo da Licença + 12 meses de atualizações |

Pagamento único, sem assinatura. Depois dos 12 meses, quem é Fundador continua usando tudo que já recebeu.

## Achou um problema?

Abra uma [issue](../../issues) descrevendo o que aconteceu e em qual sistema. Vou olhando conforme der.

## Software de terceiros

O Mnemo é feito em cima de software aberto, cada um sob a licença original dos seus autores: ChromaDB, sentence-transformers, PyTorch, pywebview e modelos de linguagem abertos (como o multilingual-e5-small). O código-fonte do Mnemo em si não é público.
