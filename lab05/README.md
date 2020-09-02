# Modelo para Apresentação do Lab05 - Subcomponentes e Páginas Dinâmicas

* [Lab05 - Tarefa 1](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/blob/master/lab05/images/Diagrama%20Lab05%20-%20Tarefa%201.PNG)
* [Lab05 - Tarefa 2]()
	* [Codepen]()
	* [HTML]()
  * [JavaScript]()


## Tarefa 1

[![Lab05 - Tarefa 1 img](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/blob/master/lab05/images/Diagrama%20Lab05%20-%20Tarefa%201.PNG)](https://github.com/arupuertas/inf331-componentizacao-e-reuso-de-software/blob/master/lab05/images/Diagrama%20Lab05%20-%20Tarefa%201.PNG)

## Tarefa 2

### Codepen - Código Component

~~~javascript


~~~

### HTML

~~~html
<div id="root"></div>
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

const elemento = <div>
                   <h2>O dinossauro</h2>
                   <Barra tamanho="10"/>
                   <h2>pulou na lama.</h2>
                 </div>
ReactDOM.render(elemento, 
        document.getElementById("root"));
~~~

