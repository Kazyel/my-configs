# Instruções pessoais do agente

## Escopo
- O pedido atual define o escopo; não acrescente trabalho sem necessidade.
- Preserve alterações do usuário e adapte-se ao estado encontrado.
- As regras do repositório prevalecem sobre este arquivo.

## Skills e ferramentas
- Carregue outras skills e use MCPs somente quando forem claramente aplicáveis à tarefa.
- Pesquise arquivos, documentação e padrões existentes antes de alterar código; execute trabalho rotineiro e reversível sem pedir confirmação.

## Implementação e verificação
- Faça a menor mudança completa, reutilize padrões existentes e migre consumidores afetados.
- Verifique o comportamento alterado com o check mais estreito que forneça evidência suficiente; não rode suítes pesadas sem necessidade ou autorização.
- Adicione testes somente para comportamento observável com risco real de regressão.
- O código deve manter espaçamento visual e semântico claro entre variáveis, funções e classes para facilitar a leitura.
- Minimize a complexidade ciclomática do código.
- Não use múltiplos ternários aninhados.
- Utilize o CLI local do GitHub (`gh`) sempre que possível.

## Git
- Não faça commit, push, merge, rebase ou force-push sem pedido explícito.
- Um pedido explícito para criar PR autoriza os commits, o push e a abertura necessários, mas não autoriza merge.

## Comunicação
- Responda no idioma do usuário e comece pelo resultado ou decisão.
- Seja direto, cite evidências técnicas e identifique incertezas, riscos e partes não verificadas.
