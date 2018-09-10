# HTML-CSS-PAGE


## Compilação dos arquivos PUG

### Linux

Para converter o projeto em HTML é necessário ter instalado o **pug**:

`sudo apt install nodejs`

`sudo npm install pug -g`

`sudo npm install pug-cli -g`

Após instalar use o *script* que se encontra na raíz do projeto para compilar:

`bash compilar.sh`

### Windows

Caso utilize windows o procedimento é bem parecido. Instale o [nodejs](https://nodejs.org/en/download/), e depois instale o pug com os comandos:

`npm install pug -g`

`npm install pug-cli -g`

Após isso dê dois cliques no arquivo *compilar.bat* que se encontra na raíz do projeto

### Alternativa portátil para Windows

Caso você não tenha permissão para instalar o *nodejs* baixe o [nodejs portátil](https://sourceforge.net/projects/nodejsportable/) e extraia o arquivo com um extrator (por exemplo o *7zip*).

Após isso basta executar o arquivo "NodeJSPortable.exe" e instalar o *pug* por lá:

`npm install pug -g`

`npm install pug-cli -g`

E para compilar o projeto execute `compilar.bat`, dentro do próprio terminal do NodeJSPortable.exe

