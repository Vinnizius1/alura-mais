## < Aprendizados legais /> 

### 1- "A motivação da imagem"
Acabamos de inserir duas imagens de maneira distinta no nosso código. A imagem do Combo+ foi implementada no arquivo index.html dessa maneira:  
 ***<img src=”img/Combo” alt=”O combo+ é a junção do alura+ e o alura lingua”>***
   
Já a imagem de fundo, que apresenta vários instrutores da Alura, foi implementada no arquivo styles.css desse jeito:   
 ***.principal {
background-image: url(“img/Background.png”);
}***
     
*Pergunta:* Por que a imagem dos instrutores e instrutoras não foi colocada dentro da tag de imagem, a < img >?  
*Resposta:* Pois a imagem “Background.png” é decorativa e seu contexto não muda a leitura da página.   
Quando estamos inserindo uma imagem, é importante pensar: essa imagem faz parte do conteúdo da página? Se não, é possível colocá-la como **background-image()** de algum elemento.
 
<br /> 

#### Link deste curso na Alura:
https://cursos.alura.com.br/course/html-css-praticando-html-css  
