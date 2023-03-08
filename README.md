# Apresentação do Commitizen
Commitizen - Uma lib utilizada para facilitação e padronização de commits.
## Instalando esse projeto para teste
```
npm install
```
## Instalando esse projeto para teste
```
//Primeiro é iniciar o git dentro da pasta raiz do projeto 
git init

//Após isso, preparar os arquivos para o commit 
git add . 

//Rodando o Commitizen 
npm run commit 
```

## Guia passo-a-passo da utilização da Lib
### Após utilizar o `npm run commit`, irá aparecer as seguintes telas: 
- Nessa Tela é possivel escolher qual seria o tipo de commit <br>
![Primeira Imagem para colocar o tipo de commit](https://user-images.githubusercontent.com/126891361/223714846-4391e7b6-b251-4c67-9a7a-b54e5a574076.png) <br><br>
- Nessa tela podemos escolher o Scope do commit. (Aqui é colocado o arquivo que sofreu a alteração)
![Scope Commit](https://user-images.githubusercontent.com/126891361/223715526-3d765970-d70e-4ada-9311-bebc6ae8cfa6.png) <br><br>
- Nessa parte colocamos uma breve descrição para o commit. 
![Breve Descrição sobre o projeto](https://user-images.githubusercontent.com/126891361/223715824-fa322202-45c9-4efa-8f9d-cfef637f0c84.png) <br><br>
- Aqui é possivel descrever melhor sobre o commit.<BR>
![Longa Descrição sobre o projeto](https://user-images.githubusercontent.com/126891361/223716076-20d1aada-16d2-425e-85ff-773053c21021.png) <br><br>
- Aqui existe uma tela especialmente somente sobre `BREAKING CHANGE` (Mudanças de funcionalidades que fora desativadas após esse commit) <br>
![Breakinh change](https://user-images.githubusercontent.com/126891361/223716751-92ef6bfb-617e-4e8e-94d2-fc31c3448906.png) <br><br>
- Aqui é possivel referenciar se esse commit irá solucionar alguma `Issue` em aberto. 
![Open Issues](https://user-images.githubusercontent.com/126891361/223717411-c9118c0e-e0d2-4689-8d04-dbe3dd792d8d.png) <br><br>
- Caso haja, esse commit irá referenciar alguma issue, podemos referenciar desta forma. (Para a referencia funcionar, é necessario colocar a `# (Algum numero)` que é referente a *Issue* em questão). Exemplo: <br> 
![Open Issues - com uma Issue Open](https://user-images.githubusercontent.com/126891361/223718204-4fecb2d8-9c26-41b1-bd12-d8999f1ebf06.png) <br><br>
- Como fica no GitHub, após o push do commit para o repositório remoto. 
![Issue - Após o Commit para responder um commit aberta](https://user-images.githubusercontent.com/126891361/223718689-3a0b75e7-d266-47af-a1b0-f4db8b73d737.png)<br><br>
- Uma demonstração de como fica o commit. (Comando `git log`)
![Git Log](https://user-images.githubusercontent.com/126891361/223718997-2f072896-f23d-4d5c-ae7b-25c33c0038e2.png)









