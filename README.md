# Orçamento — Instaladores

Aplicação desktop de **orçamento de obras de rede elétrica de distribuição**, de uso
interno da Sirtec.

Este repositório guarda apenas os **instaladores** e o `version.json` que o app
consulta para se atualizar sozinho. O código-fonte não fica aqui.

## Instalação

Baixe o instalador mais recente em **[Releases](../../releases/latest)** e execute.

- Instala em `%LOCALAPPDATA%\Sirtec\Orcamento` e **não pede senha de administrador**.
- Na primeira execução o Windows pode exibir o aviso *"O Windows protegeu o seu
  computador"* (SmartScreen). Isso acontece com qualquer executável novo sem
  assinatura digital: clique em **Mais informações → Executar assim mesmo**.

## Atualizações

O app verifica sozinho ao abrir e avisa quando há versão nova — é só aceitar. Seus
orçamentos ficam em `%APPDATA%\Sirtec\Orcamento` e **não são afetados** por
atualização nem por desinstalação.
