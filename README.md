# HTML ✔
  
  - Hyper-Text-Markup-Language ou Linguagem de Marcação de HiperTexto
  - Marca o corpo de uma página.

## Tags HTML ✔
  - Como se trata de uma linguagem de marcação, nós apenas delimitamos espaços.
  - Para isso usamos tags, que ficam entre os sinais de maior e menor que, conforme padrão:

    - ```<tag></tag>```


  ### Exemplo de tags:
  
    Títulos -> <h6>-<h1>
    Parágrafos -> <p>
    Links -> <a>
    Caixas de Texto -> <textarea>
    
  - Algumas tags não precisam de fechamento quando escritas em HTML puro, exemplo: ```<img>``` ou ```<input>```
  - Além disso podemos definir estilos para as páginas de duas maneiras:
    - Usando a tag ```<style></style>```
    - Criando um arquivo novo para o CSS

# CSS ✔
  - Cascading Style Sheets ou Folhas de Estilo em Cascata
  - Serve não só para definir o estilo das páginas mas também para criar efeitos, animações, etc.
  
  ## Primeiros passos no CSS ✔
  - Assim como em outras linguagens no CSS terminamos uma linha de código com ```;```
  - Além disso, nós também podemos usar variáveis.
  - Como declarar uma váriável no CSS: para isso vamos na raiz do arquivo (```*```) e definimos o nome após dois traços (```--```), conforme o exemplo abaixo declarando duas variáveis de cores.
  ```
  :root{
    --white-pattern: #ffffff;
    --black-pattern: #121212;
  }
  ```

  - Para pegarmos elementos do CSS usamos os seguintes atributos que a maioria das tags possume  ```id``` e ```class```, qual a diferença?<br/>
    
    - Com ```id``` definimos elementos únicos na página
    
    - Com ```class``` definimos elementos que podem aparecer mais de uma vez na página

  - Mas o que podemos estilizar? Tudo! Além de ids e classes o CSS é esperto o suficiente pra entender o que são as tags.
  
  ## Propriedades que podemos alterar no CSS
  - Cor da letra (```color```);
  - Cor de fundo (```background```);
  - Bordas (```border```);
  - Margens (```margin```)
  - Preenchimentos (```padding```)
  - Modo de exibição (```display```)
  - Posicionamento de textos (```justify-content, justify-self, justify-items, justify-tracks, text-justify ```)
  - Alinhamento (```align-self, align-items, align-content, align-tracks```)

# Fim! Abaixo deixo algumas dicas e links.
## Dicas
- Crie landing pages
- Tente clonar sites chamativos
- Domine uma propriedade antes de ir para outra
- Inspecione páginas, como? Vai em uma página qualquer e aperta ```F12``` ou ```Ctrl + Shift + I``` ou vai nos três pontos na parte superior direita, Mais Ferramentas, Ferramentas do Desenvolvedor.
## Links
- [HTML Tutorial](https://www.w3schools.com/html/default.asp)
- [CSS Tutorial](https://www.w3schools.com/css/default.asp)
