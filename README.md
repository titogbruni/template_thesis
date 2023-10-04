<a href='https://github.com/titogbruni/template_thesis'><img src='https://github.com/titogbruni/template_thesis/blob/main/images_README/logo_README.png' align="right" height="139" /></a>

#### **TeX template**

Template que usei na minha monografia de final de curso. Esse template está dentro das regras ABNT. 

Ao escrever um texto em TeX, sugiro usar o site Overleaf. Para isso, crie seu cadastro [aqui](https://www.overleaf.com/login).

---------------------------------------------------

**1. Criar Novo Projeto**

No canto superior esquerdo, *New Project* $\rightarrow$ *Blank Project*.  

Após criar o arquivo, você verá sua tela dividida em duas partes. O lado esquerdo tem o editor do código que gera o arquivo. Para que as mudanças do lado esquerdo apareçam no output do lado direito, clique no botão verde "Recompile" no topo da tela da direita. As mudanças ficam automaticamente salvas. 

----------------------------------------------------

**2. Colando o template**

Apague tudo que está no editor de código e cole o código do arquivo [template](https://github.com/titogbruni/template_thesis/blob/main/template.tex).

Para quem for escrever a monografia em português, alterar o primeiro comando do código para que o programa entenda que o texto está em português:

`\documentclass[12pt,openright,twoside,a4paper,portuguese,brazil]{abntex2}`

Ao clicar em "Recompile" você ainda terá problemas, pois falta dar upload em alguns arquivos que o código chama. 

---------------------------------------------------

**3. Upload dos arquivos que faltam**

 - **3.1** - O primeiro arquivo que falta é a imagem da logo da PUC que eu uso no capa. Você pode baixar a imagem que [usei](https://github.com/titogbruni/template_thesis/blob/main/logo_puc.png), ou usar outra logo da puc do seu gosto. Para adicionar arquivos (pdf, jpg,...) no seu documento, clique no botão da imagem abaixo:

   <a href='https://github.com/titogbruni/template_thesis'><img src='https://github.com/titogbruni/template_thesis/blob/main/images_README/upload_logo.png' align="top" height="139" /></a>


- **3.2** - O segundo arquivo que falta é a bibliografia. Copie o texto do arquivo    [references](https://github.com/titogbruni/template_thesis/blob/main/references.tex), depois clique no botão indicado abaixo e crie um arquivo com nome "references.bib":

   <a href='https://github.com/titogbruni/template_thesis'><img src='https://github.com/titogbruni/template_thesis/blob/main/images_README/reference_img.png' align="top" height="139" /></a>

----------------------------------------

**4. Citações**

Se dá através do arquivo "references.bib" .

 - **4.1** - abrir citação

   Ex: Clique no botão abaixo para abrir a citação no formato BibTeX:

   <a href='https://github.com/titogbruni/template_thesis'><img      src='https://github.com/titogbruni/template_thesis/blob/main/images_README/citation.png' align="top" height="139" /></a>


 - **4.2** - copie a citação

   <pre>
`@article{garcia2003taxa,
  title={Taxa de juros, risco cambial e risco Brasil},
  author={Garcia, M{\'a}rcio Gomes Pinto and Didier, Tatiana},
  year={2003},
  publisher={Instituto de Pesquisa Econ{\^o}mica Aplicada (Ipea)}
}`
   </pre>

 - **4.3** - cole no references.bib

 - **4.4** - cite no main.tex

   Para citar um artigo ao longo do texto principal, sugiro dois comandos: `\cite{}` e `\citeyear{}` que citam nome e data, e (apenas) data, respectivamente. 

   No exemplo acima, o nome da citação, que sempre se encontra na primeira string da citação BibTeX, é **garcia2003taxa**, logo poderia citar usando `\cite{garcia2003taxa}`.

   Note que você pode redefinir o nome da citação, caso você queira. Basta alterar a  primeira string do BibTeX no "references.bib".


----------------------------------------

**5. Escrevendo sua monografia**

Agora, basta que você apague o que eu escrevi (usei o comando *\lipsum[1]* que gera parágrafos aleatórios) e escreva seu texto! 

Lembre-se de que há muitos [tutoriais](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) de como usar LaTeX. Boa sorte!





