# B.MOOVE · Remarcação de treinos (protótipo)

Protótipo **descartável** para validar, com o Centro de Treinamento B.MOOVE, as regras de
remarcação e cancelamento de treinos pelo aluno, antes de construir o MVP.

- Arquivo único, sem instalação: `prototipo/remarcacao-prototipo.html`
- Dados 100% fictícios; nada é salvo (recarregar a página recomeça tudo).
- À esquerda: o app do aluno. À direita: relógio simulado, regras ajustáveis e cenários guiados.

## Alunos de teste

| Aluno | Matrícula | Código | Modalidade(s) |
|---|---|---|---|
| Ana | 1024 | BM7K3P | Treinamento Funcional |
| Bruno | 1031 | BM9Q2D | Treinamento Funcional + Fortalecimento e Reabilitação Funcional |
| Carla | 1045 | BM4X8L | Treinamento Funcional |
| Diego | 1052 | BM2W6R | Cross Trainer |
| Elisa | 1060 | BM5H3T | Fortalecimento e Reabilitação Funcional (2x/semana) |

## Regras em validação

- Agenda dos próximos 15 dias, só dias úteis e só dias com modalidade do aluno.
- Todos os horários aparecem (inclusive lotados/encerrados), para transparência.
- **Remarcar**: para qualquer modalidade do plano do aluno, só onde há vaga, com antecedência
  mínima (2h) e limite de remarcações (3 a cada 15 dias). Se o novo dia já tiver outro treino,
  o aluno escolhe manter (padrão) ou cancelar esse outro.
- **Cancelar**: libera a vaga; não conta no limite de remarcações.
- Feriados: aulas desativadas (não remarca, não cancela, não é destino).
- Acesso: matrícula + código de acesso fornecido pelo CT, com bloqueio após 5 tentativas.

Valores de capacidade das turmas e a grade de Fortalecimento são provisórios.
