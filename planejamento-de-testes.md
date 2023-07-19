# Planejamento de testes
## Técnicas / testes exploratórios
- Planejamento testes exploratórios
  - **Explorar** uma funcionalidade/componente/módulo
  - **Com** alguma estratégia/recurso/condição
  - **Para** descobrir alguma determinada função

  ### Exemplo:
  - **Explorar** a regra de datas no cadastro de empregos
  - **Com** classes de equivalência e valores limites
  - **Para** descobrir como o sistema se comportará em caso de concomitâncias de emprego.

## Freestyle - Técnica 
Usa-se para determinarmos uma rota, e termos um card inicial, levantarmos cenários a serem cobertos, e assim os próximos cards, mais focados.

Exemplo:
- **Explorar** a aplicação
- **Com** navegação livre
- **Para descobrir** as principais funcionalidade do sistema.
# BDD
- **Dado** - Pré-requisitos do desejo;
- **E**   - Pré-requisitos, necessidades da ação;
- **Quando** - Contexto da ação, realização;
- **Então**  - resultado esperado.

# Gherkin 
- **Como** -Persona, Alguém, Usuário;
- **Quero**, Preciso, Desejo - A ser  realizado, o que deve acontecer;
- **Porque** - Resultado esperado.

# Pirâmide de Testes 
- **Topo** - Flx complt, Funcionais, E2E, Front End, Manual / Autom;
- **Meio** - Integração / Aceitação
- **Base** - Unitário [ Lógica Utilizada, Classes, Funções ] - BackEnd

# Etapas do processo de criação de um software 
- Concepção → Planejamento → Projeto →  Modelagem → Construção → Entrega

## Regras de negócio
- Como deve acontecer a funcionalidade (Macro)
- Critérios de aceite  
- O que preciso que exista para testar (Micro)

Erro > Falha > Defeito (Bug)