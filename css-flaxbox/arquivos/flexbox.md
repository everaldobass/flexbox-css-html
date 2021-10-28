# Introdução - dicasparadevs
- Iniciante em flexbox
### Oque é Flexbox
- Flexible Box Model
- Aplicamos com display:flex
- Organização dos nossos layouts se torna mais flexível e dinânmica
- Por padrão, todos os istens do container ficam lado a lado
- Grande capacidade de responsividade

### CSS-Tricks
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/

```
  display: flex; - Fica Lado a Lado 
  flex-direction: row; - Fica Lado a Lado
  flex-direction: column; -(Empilha) Fica um abaixo do outro

  Main Axis-> flex-direction:row - Horizontal
  Cross Axis-> flex-direction:column - Vertical
  
  justify-content: flex-start; - Alinha lado Esquerdo
  justify-content: flex-end; - Alinha ao Lado Direito
  justify-content: center; - Centraliza no meio do container
  justify-content: space-between; - Distribui os items (Geralmente usa-se no menu do site)
  justify-content: space-around; - Espaço com margim

  align-items: flex-start; - Alinha os items no inicio do container
  align-items: flex-end; - Alinha os items no final do container
  align-items: center; - Alinha os items no centro do container
  align-items: stretch; - Todos os itens cresce com o mesmo tamanho


   align-content: flex-start; - Alinha os items no inicio container
   align-content: flex-end; - Alinha os items no final do container
   align-content: center; - Alinha os items no centro do container

   flex-flow
   flex-flow: wrap; - Quebra a linha dos itens
   flex-flow: nowrap;  - Não permite a quebra de linha
   flex-flow: wrap-reverse; - Quebra a linha acima

   order: 1 - Altera a ordem dos items
   flex: 1 - Altera o tamanho do item.
   flex-basis: 33%;

```