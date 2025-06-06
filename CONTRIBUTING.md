# Guia de Contribuição

Este documento descreve as diretrizes para contribuir com o projeto.

## Fluxo de Trabalho com Git

### Branches

- `main`: Branch principal, contém o protótipo ou documentação validada  
- `develop`: Branch de desenvolvimento e evolução contínua  
- `feature/nome-da-feature`: Para novas funcionalidades (ex: botão "Voltar", mensagens de erro)  
- `bugfix/nome-do-bug`: Para correções de problemas de usabilidade ou acessibilidade  
- `docs/nome-da-documentacao`: Para atualizações em relatórios, heurísticas, testes ou documentação de design  

### Processo de Contribuição

1. Crie uma branch a partir de `develop`
2. Faça suas alterações (ex: revisão de telas, inclusão de rótulos, melhorias visuais)
3. Submeta um Pull Request para `develop`
4. Aguarde a revisão da equipe (design, usabilidade e/ou documentação)
5. Após aprovação, seu conteúdo será integrado ao projeto principal

## Padrões de Codificação

- Utilizar estrutura de layout vertical e espaçamentos adequados  
- Priorizar clareza visual com o uso de labels, placeholders e feedback visual  
- Garantir navegação por teclado e leitura de campos por leitores de tela  
- Seguir consistência tipográfica e paleta de cores definidas para cada tela  
- Adotar componentes padrão (botões, campos de entrada, links de ajuda)  

## Processo de Review

- Toda contribuição deve ser revisada por pelo menos um outro membro da equipe  
- Usar os comentários no Pull Request para discutir decisões e sugestões  

**Critérios de revisão:**
- Consistência visual entre as telas  
- Inclusão de mensagens de erro, rótulos e instruções  
- Suporte básico de acessibilidade (navegação, leitura, foco)  
- Alinhamento com os testes de usabilidade realizados  

## Commits

Utilize mensagens de commit claras e descritivas seguindo o padrão:

```markdown
[tipo]: descrição curta

Descrição mais detalhada se necessário
