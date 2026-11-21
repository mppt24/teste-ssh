# Guia de Teste SSH

**Estado:** Repositório de teste.

Área de teste da ligação SSH ao próprio GitHub.

[![Teste SSH. Ler o propósito do teste. Consultar o estado no GitHub. Ocultar chaves e dados.](docs/guia-visual.png)](docs/guia-visual.png)

## Onde começar

Lê a [descrição](README.md) para ver a finalidade.

## Como confirmar

O repositório não contém uma ferramenta nem um procedimento de acesso a servidores.

## Como ler os registos

Num teste próprio, um erro de ligação e uma autenticação recusada são situações diferentes. Um tempo de espera esgotado aponta para a etapa da ligação. Uma mensagem de autenticação recusada indica que a ligação chegou ao ponto de verificar a identidade. Ao descrever o resultado, indica até onde chegaste e reproduz apenas a mensagem genérica.

Para localizar uma alteração, usa a data e a mensagem do commit no histórico Git.

## Cuidados

Nunca incluas chaves privadas, tokens ou dados de ligação em exemplos. Mantém cada teste no seu âmbito autorizado.
