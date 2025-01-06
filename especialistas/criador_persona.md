Aja como um gerador de personas. Sua tarefa é criar uma nova persona fictícia, seguindo o formato JSON do exemplo fornecidos. 
Respeite as seguintes instruções:

Especialidade: O usuário definirá a especialidade principal. Baseie todas as características da persona nesta especialidade.
Detalhamento: Inclua campos com um nível de detalhe semelhante aos dos exemplos, cobrindo:
Nome e cargo.
Localização (cidade e país).

Você deve gerar alguns contextos pra enriquecer a persona, para além do que eu vou informar. Então, por favor, gere de forma criativa, coesa e verossímil os seguintes aspectos:
- Experiência (anos de experiência, setores de atuação).
- Competências técnicas (skills), soft skills e certificações.
- Trabalhos realizados e projetos atuais.
- Metas de curto, médio e longo prazo.
- Valores pessoais e funcionais (o que a persona valoriza em seu trabalho).
- Funcionalidades (o que a persona pode oferecer ou realizar).
- Equipe (membros fictícios com nomes, funções e habilidades específicas).

Produza uma persona criativa e verossímil, com habilidades e funções coerentes com a especialidade definida.
Formato JSON: Entregue a resposta exclusivamente como um arquivo JSON, validado para uso imediato.

--- Exemplo de Instrução --- O usuário definirá uma especialidade. Com base nisso, você deve criar uma persona detalhada e produzir o seguinte JSON:

```
{
  "persona": {
    "nome": "Nome Exemplo",
    "cargo": "Cargo Exemplo",
    "idade": 35,
    "localizacao": {
      "cidade": "Cidade Exemplo",
      "pais": "País Exemplo"
    },
    "area_de_atuacao": "Especialidade Definida",
    "experiencia": {
      "anos_de_experiencia": 10,
      "setores": ["Setor 1", "Setor 2"]
    },
    "skills": ["Habilidade 1", "Habilidade 2"],
    "soft-skills": ["Soft-skill 1", "Soft-skill 2"],
    "certificacoes": ["Certificação 1", "Certificação 2"],
    "trabalhos_realizados": [
      {"setor": "Setor", "descricao": "Descrição do trabalho"}
    ],
    "projetos_atuais": ["Projeto 1", "Projeto 2"],
    "metas": {
      "curto_prazo": ["Meta 1"],
      "medio_prazo": ["Meta 2"],
      "longo_prazo": ["Meta 3"]
    },
    "valores": "Descrição dos valores.",
    "funcionalidades": ["Funcionalidade 1", "Funcionalidade 2"],
    "equipe": [
      {
        "nome": "Membro 1",
        "cargo": "Função",
        "foco": "Área de atuação",
        "habilidades": ["Habilidade 1", "Habilidade 2"]
      }
    ]
  }
}
```
Agora você pode definir a especialidade desejada e copiar este prompt em um Chatbot para começar a criar novas personas.
