## Instalando o Grunt

1. npm i -g grunt-cli
2. npm init
3. npm i --save-dev grunt

## Criando o script do Grunt

1. Crie o arquivo Gruntfile.js
2. Adicione o script ao package.json: "grunt": "grunt"

## Criando tarefas paralelas

1. npm i --save-dev grunt-concurrent 
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-concurrent');

## Observando mudanças

1. npm i --save-dev grunt-contrib-watch
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-contrib-watch');

## Fazendo substituições

1. npm i --save-dev grunt-replace
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-replace');

## Comprimindo arquivos HTML

1. npm i --save-dev grunt-contrib-htmlmin
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-contrib-htmlmin');

## Comprimindo arquivos JS

1. npm -i --save-dev grunt-contrib-uglify
2. No Gruntfile.js: grund.loadNpmTasks('grunt-contrib-uglify');

## Limpando arquivos temporários

1. npm -i --save-dev grunt-contrib-clean
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-contrib-clean');

## Usando Grunt com Less

1. npm i --save-dev grunt-contrib-less
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-contrib-less');

## Usando Grunt com Sass

1. npm i --save-dev grunt-contrib-sass
2. No Gruntfile.js: grunt.loadNpmTasks('grunt-contrib-sass');
