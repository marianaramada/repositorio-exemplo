# Caso de Uso: Formações


| <div style="width:290px">Versão</div> | Atividade | Autor | Data |
|:------------|:----------------|:--------------|:----------------|
| 1.0 | Versão Inicial do Arquivo | Mariana Soller Ramada  | 08/04/2025 |

## **Descrição**
Representa um benefício que as empresas associadas (Memberships) possuem para realizar a formação do seus recursos humanos. 

Permite que o representante da empresa associada indique funcionários ou outras pessoas para cursarem formações como: cursos de especialização, curta duração ou bootcamps ofertados pelo AKCIT. Permite, também, o acompanhamento do status das indicações e do andamento dos colaboradores que foram matriculados.   

## **Ator(es)**
Representante da empresa associada.

## **Pré-condições**

O usuário necessita estar logado.

## **Protótipo da(s) Tela(s)**

Disponível aqui\<link\>.

## **Funcionalidades**

- F01 - Indicar colaborador para realizar uma formação
- F02 - Editar indicação
- F03 - Remover indicação
- F04 - Visualizar informações da formação


## Regras de Negócio

| ID | Descrição da Regra |
|:-----|:-----|
| **RN01** | As turmas das formações possuem um período de início e fim na qual podem ser realizadas as indicações. O usuário somente poderá indicar colaboradores durante esse período. |
| **RN02** | As indicações possuem uma ordem de prioridade. Indicações que possuem maior nível de prioridade terão maior chance de serem aprovadas considerando a disponibilidade das vagas da formação.|
| **RN03** | O usuário poderá visualizar todas as formações disponíveis e filtrá-las de acordo com seus status: Indicações abertas, Matrículas abertas, Em andamento e Concluído. |
| **RN04** | O usuário poderá filtrar quais formações possuem colaboradores matriculados. |



