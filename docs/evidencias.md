# Evidências e limites — DiárioPro

Revisão documental e estática em **28/10/2026**. Aplicação, provedores e testes não foram iniciados nesta revisão.

| Afirmação | Base de verificação | Limite |
|---|---|---|
| Fluxo contexto → IA → DOCX → histórico | Rotas, serviço de planos, validadores e gerador de documentos presentes no código privado | Existência da implementação; não é uma nova execução ponta a ponta |
| Groq e OpenRouter | Adaptadores de provedores e serviço de fallback | Exige configuração e disponibilidade; fallback não garante sucesso |
| Habilidades curriculares restritas à seleção | Serviço de IA e camada curricular | Não valida automaticamente toda a correção pedagógica |
| 1.958 registros curriculares | Contagem dos arrays de registros nas três fontes versionadas | 1.351 BNCC, 460 Currículo Paulista EF/EI e 147 Currículo Paulista EM; fontes podem compartilhar códigos |
| 146 verificações Python aprovadas e 2 ignoradas | Relatório interno V3.2, 10/10/2026 | Seleção de testes em ambiente isolado, com IA simulada; não é o total atual de toda a suíte |
| 48 verificações Node.js aprovadas | Mesmo relatório V3.2 | Cobertura dos fluxos indicados no relatório |
| Contas e dados privados por usuário | Dependências de autenticação, consultas com escopo de proprietário e relatório de regressão | Não equivale a certificação de segurança |
| Modos local e web com armazenamento separado | Implementações e documentação de armazenamento | Não houve acesso à infraestrutura cloud nesta revisão |

O projeto registra uma publicação web anterior. A disponibilidade atual desse ambiente não foi verificada para este portfólio. Não são divulgados URLs de operação, nomes de recursos ou detalhes de acesso.

## Recursos experimentais

Voz, imagem/OCR e entradas assistidas têm documentação e implementações de piloto. A documentação registra validação com mocks e pendências de uso real. A extensão de consulta a portal escolar tem limites próprios; não se afirma lançamento automático em portal nem integração completa de frequência.

## Imagens

- Planejamento: captura de demonstração com identidade fictícia e aviso de IA simulada.
- Acesso: captura histórica de validação local sem campos preenchidos.

Os arquivos foram regravados em PNG sem metadados opcionais, mantendo os pixels decodificados. Não representam métricas de adoção, alunos reais ou atividade atual.

## Métricas ainda não estabelecidas

Não foram comprovados número de usuários ativos, adoção institucional, receita, redução de tempo de preparação ou qualidade pedagógica comparativa. Uma próxima avaliação pode cronometrar a mesma tarefa com e sem o produto, usando critérios definidos previamente e dados autorizados.

As fontes privadas foram preservadas para rastreabilidade local. Não são anexadas porque contêm informações operacionais além do recorte público.
