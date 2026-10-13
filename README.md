# Relatório de Obras TM2

Aplicativo da **TM2 Alumínio** para elaboração, aprovação e distribuição dos **Relatórios de Obras** da equipe de Obras e Projetos.

O relatório reúne a identificação da obra, os pontos observados na visita (com descrição e fotos) e, para cada ponto, a ação necessária, o resultado esperado, o responsável e o prazo. Após a aprovação, o aplicativo gera o relatório em **PDF**, liberado para o elaborador distribuir.

## Acesso

| O que | Link |
|---|---|
| Aplicativo | [Abrir o Relatório de Obras](https://tm2aluminio.github.io/relatorio-obras/) |
| Manual de uso | [Abrir o manual](https://tm2aluminio.github.io/relatorio-obras/Manual_RelatorioObras_TM2.html) |

Funciona no Google Chrome, no computador e no celular. Não é necessário instalar nada.

## Arquivos deste repositório

| Arquivo | Descrição |
|---|---|
| `index.html` | O aplicativo (Relatório de Obras TM2) |
| `Manual_RelatorioObras_TM2.html` | Manual de uso em formato de infográfico, otimizado para celular |
| `README.md` | Este arquivo |

## Como funciona (resumo)

1. **Elaborador** preenche a identificação, os participantes e os pontos da visita (texto, fotos e ação de cada ponto).
2. Clica em **Gravar** para salvar o rascunho no próprio aparelho.
3. Clica em **Enviar para aprovação**. O aplicativo gera um arquivo `.json`, que é enviado ao aprovador por WhatsApp ou e-mail.
4. **Aprovador** abre o aplicativo, carrega o arquivo `.json`, revisa o relatório e clica em **Aprovar relatório**, informando seu nome.
5. O aplicativo gera o **PDF** e o arquivo aprovado é devolvido ao elaborador.
6. **Elaborador** distribui o PDF aprovado.

### Código do relatório

O código é gerado automaticamente no formato `REL-<código da obra>-<aammdd>`. Em revisões, é acrescentado o sufixo `(revXX)`.

## Onde guardar os arquivos

O aplicativo não possui servidor: os dados não ficam armazenados na internet. Os arquivos gerados (`.json` e `.pdf`) vão para a pasta de downloads do aparelho. Recomenda-se salvá-los, após cada etapa, na pasta de obras do **OneDrive** da TM2, para manter o histórico e o arquivamento seguro.

## Como atualizar o aplicativo ou o manual

1. Neste repositório, clique em **Add file → Upload files**.
2. Envie o novo arquivo **com exatamente o mesmo nome** (`index.html` ou `Manual_RelatorioObras_TM2.html`).
3. Clique em **Commit changes**. Em cerca de 1 a 2 minutos a versão nova estará no ar.

> Atenção: o GitHub diferencia maiúsculas de minúsculas. Mantenha os nomes dos arquivos exatamente como acima, senão os links deixam de funcionar.

## Contato

Equipe de Obras e Projetos — TM2 Alumínio
