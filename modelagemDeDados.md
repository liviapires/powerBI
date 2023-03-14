# O que é Modelagem de Dados?

- Processo de criar uma representação visual
    - Define os sistemas de coleta e gerenciamento de informações

> Gera uma "blueprint", modelo de dados

- Ajuda diferentes partes interessadas:
    - Analistas de Dados
    - Cientistas de Dados
    - Arquitetos de Dados
    - Engenheiros de Dados

> Visão unificada dos dados da organização

<span style="background-color:#134F78">⠀O modelo descreve quais dados a empresa coleta, a relação entre eles e os métodos para armazenar e analisá-lo.⠀</span>

<span style="border: 1px solid #134F78">⠀Modelo de dados: criação de um modelo <i>conceitual</i>, <i>lógico</i> e <i>físico</i> de dados.⠀</span>


### Conceitual

Define entre os dados:
- Conceitos
- Relações

_(não é possível fazer no Microsoft Power BI)_


### Lógico

Especifica:
- Como os dados serão armazenados
- Como as relações serão representadas no banco de dados

### Físico

Descreve como os dados serão armazenados em um sistema de armazenamento específico.

> O Power BI cria um _modelo simplificado_ que tem uma característica de modelo <span style="background-color:#134F78">lógico</span> e parece um modelo <span style="background-color:#134F78">físico</span>
> - Na verdade acaba sendo apenas uma <span style="background-color:#134F78">visão geral</span>
>
> Ele também evita erros de relacionamentos se os dados não estiverem organizados corretamente
> - Porém não criará relacionamentos sem as conexões corretas entre os dados
>   - Mesmo que permita criar gráficos e dashboards assim mesmo
>
> <span style="background-color:#134F78">⠀É obrigação do desenvolvedor organizar os dados corretamente.⠀</span>

<span style="background-color:#134F78">⠀O Power BI não é uma ferramenta de modelagem de dados!⠀
