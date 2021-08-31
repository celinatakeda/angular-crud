# Angular-CRUD
 Projeto CRUD com Angular 9. 
 
 Para melhorar meus conhecimentos em angular, fiz o curso de Angular 9 no Coder.
 
 Alguns conceitos que adquiri.
 
**CRUD** (acrônimo do inglês Create, Read, Update and Delete) são as quatro operações básicas (criação, consulta, atualização e destruição de dados).

**Programação Reativa**: o programa só será chamada quando acontecer um evento para daí o código ser executado.
Vantagem: exige menos do processador.

**Injeção de Dependência**: é um padrão no qual a classe recebe as dependências de uma fonte externa ao invés de criar por conta própria.

**One Way Data Binding** - binding de uma direção(TypeScript para o HTML por exemplo).

**Two Way Data Binding** - binding de duas direções, ou seja, sentido de alteração de duas direções, tanto no TypeScript par o HTML como o contrário.

## Assuntos Importantes

1. **Componentes**: são todos os itens da parte visual da página para o usuário (elementos visual).

2. **Diretivas**: podem ser de dois tipos
    * *Attribute Directives*: Altera a aparência(css) e o comportamento de um elemento, componente ou outra diretiva. Uso @ (@Directive).
    * *Structural Directives*: Altera o layout adicionando e removendo elementos da DOM.(altera a estrutura da página). Uso de asterico na frente(*ngIf).

3. **Rotas**: caminho para chamada das páginas.

4. **Pipes**: processamentos que faz em cima de variáveis. Uso do {{ }}(double mustache). Usado para fazer formatações de data e moedas. 
Pode ter uma cadeia de pipes.

5. **Observables**
    * *Padrão Observer*: padrão orientado a Evento.
    * *Subject*: é quem detecta o evento. O observe fica reativa. Só vai ficar proativa quando o subject notificar que o evento aconteceu.

6. **Services**: são classes que têm como principal objetivo organizar e compartilhar métodos e dados entre os componentes.
 
