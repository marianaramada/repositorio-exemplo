# Caso de Uso: Formações


| <div style="width:290px">Versão</div> | Atividade | Autor | Data |
|:------------|:----------------|:--------------|:----------------|
| 1.0 | Versão Inicial do Arquivo | Mariana Soller Ramada  | 08/04/2025 |

## **Descrição**
Representa um benefício que as empresas associadas (Memberships) possuem para realizar a formação do seus recursos humanos. 

Permite que o representante da empresa associada indique funcionários ou outras pessoas para cursarem formações como: cursos de especialização, curta duração ou bootcamps ofertados pelo AKCIT. Permite, também, o acompanhamento do status das indicações e do andamento dos colaboradores que foram matriculados.   

## **Ator(es)**
Representante da empresa associada

## **Pré-condições**

O usuário necessita estar logado.

## **Protótipo da(s) Tela(s)**

Disponível aqui\<link\>.

## **Fluxo Principal**
### FP - Indicar colaborador para realizar uma formação

1. O usuário seleciona uma formação com período de indicação aberto
2. O usuário indica um ou mais colaboradores considerando a ordem de prioridade

## **Fluxo Alternativo**

### FA02 - Editar indicação

1. O usuário seleciona uma formação
2. O usuário seleciona a lista de indicações
3. O usuário seleciona um colaborador
4. O usuário altera os dados do colaborador

### FA03 - Remover indicação

1. O usuário seleciona uma formação
2. O usuário seleciona a lista de indicações
3. O usuário remove um colaborador

### FA04 - Visualizar informações da formação

1. O usuário seleciona uma formação
2. O usuário visualiza a descrição do formação, os módulos, professores e colaboradores inscritos e matriculados

## **Fluxo Extensão**
Não se aplica.

## **Fluxo Exceção**

### FEX01 - E-mail inválido

1. O usuário indica um colaborador com e-mail inválido
2. O sistema exibe mensagem informando que o formato de e-mail é inválido

## Regras de Negócio

| ID | Descrição da Regra |
|:-----|:-----|
| **RN01** | As turmas das formações possuem um período de início e fim na qual podem ser realizadas as indicações. O usuário somente poderá indicar colaboradores durante esse período. |
| **RN02** | As indicações possuem uma ordem de prioridade. Indicações que possuem maior nível de prioridade terão maior chance de serem aprovadas considerando a disponibilidade das vagas da formação.|
| **RN03** | O usuário poderá visualizar todas as formações disponíveis e filtrá-las de acordo com seus status: Indicações abertas, Matrículas abertas, Em andamento e Concluído. |
| **RN04** | O usuário poderá filtrar quais formações possuem colaboradores matriculados. |



