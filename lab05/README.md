# Modelo para Apresentação do Lab05 - Subcomponentes e Páginas Dinâmicas

* [Lab05 - Tarefa 1](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#tarefa-1)
* [Lab05 - Tarefa 2](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#tarefa-2)
	* [Link Para o Projeto no Codepen](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#link-para-o-projeto-no-codepen)
	* [Codepen](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#codepen---c%C3%B3digo-component)
	* [HTML](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#html)
	* [CSS](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#css)
   * [JavaScript](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/tree/master/lab05#javascript)


## Tarefa 1

**Utilizando os componentes ProductViewComponent e ProductSelectionControllerComponent**

[![Lab05 - Tarefa 1 img](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/blob/master/lab05/images/Diagrama%20Lab05%20-%20Tarefa%201.PNG)](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/blob/master/lab05/images/Diagrama%20Lab05%20-%20Tarefa%201.PNG)

## Tarefa 2

### Link Para o Projeto no Codepen

Link para o projeto no Codepen:[ Lab05 - Tarefa 2 - Codepen](https://codepen.io/arupuertas/pen/JjXrGGe)

### Codepen - Código Component

**HTML**

~~~html

<h3> Informações Klebinho </h3>

<ul data-list></ul>

~~~

**JavaScript**

~~~javascript

const data = [
    {
        inf: 'Klebinho o Gato',
        id: 'Nome:'
    },
    {
        inf: 'Laranja',
        id: 'Cor:'
    },
    {
        inf: '4 Anos',
        id: 'Idade: '
    },
    {
        inf: 'João da Silva',
        id: 'Dono:'
    }
]

const listComponent = (data) => {
    return data.map((item) => {
        return (
            `
            <li>
                <span>${ item.id }</span>
                <span>${ item.inf }</span>
            </li>
            `
        )
    }).join('')
}

const el = document.querySelector('[data-list]')

el.innerHTML = listComponent(data)

~~~

## Código Final Codepen

### HTML

~~~html

<div id="root"></div>

<div class="OGatoKlebinho">
        <img src="https://clickerclubsp.com.br/wp-content/uploads/2019/03/gatos-fuga-comportamento-animal.jpg" alt="">
      </div>

<h3> Informações Klebinho </h3>

<ul data-list></ul>

~~~

### CSS

~~~css

h1{
  font-style: italic;
  Color: Orange;
}

h2{
  font-style: italic;
  Color: Blue;
}

h3{
  font-style: italic;
  Color: red;
}
.OGatoKlebinho img {
    max-width:200px;
    max-height:150px;
    width: auto;
    height: auto;
}

~~~

### JavaScript

~~~javascript

class Barra extends React.Component {
  render() {
    let resultado = "";
    for (let b = 1; b <= this.props.tamanho; b++)
     resultado += "=";
    return resultado;
 }
}

const elemento =  <div>
        
                  <h1> Klebinho o Gato Laranja</h1>
                   <Barra tamanho="38"/>
                   <h2> Pulou a Cerca Azul.</h2>
       </div>

      ReactDOM.render(elemento, 
        document.getElementById("root"));

const data = [
    {
        inf: 'Klebinho o Gato',
        id: 'Nome:'
    },
    {
        inf: 'Laranja',
        id: 'Cor:'
    },
    {
        inf: '4 Anos',
        id: 'Idade: '
    },
    {
        inf: 'João da Silva',
        id: 'Dono:'
    }
]

const listComponent = (data) => {
    return data.map((item) => {
        return (
            `
            <li>
                <span>${ item.id }</span>
                <span>${ item.inf }</span>
            </li>
            `
        )
    }).join('')
}

const el = document.querySelector('[data-list]')

el.innerHTML = listComponent(data)

~~~

