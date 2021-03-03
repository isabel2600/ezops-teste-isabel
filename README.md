# ezops-teste-isabel

![AWS-EC2-852x459-1](https://user-images.githubusercontent.com/68034656/104957262-93920780-59ac-11eb-9df8-598726e16a1f.jpg)


EC2 via cloudformation

Este é o passo a passo para que você possa criar um template.yaml. Está receita será usada para que você possa coloca-la dentro do framework serverless

EC2 via Cloudformation

Antes de tudo, para realizar para implementar EC2 via cloudformation, você precisa criar uma conta na aws console https://aws.amazon.com/pt/console/

Depois você precisa clicar também baixar no seu computador qualquer editor de sua preferência na sua máquina e criar um template em formato.yaml Observação: Gosto muito de usar o visual code estudio. Link está abaixo

https://code.visualstudio.com/docs/editor/versioncontrol

Toda documentação sobre a criação da receita(template) em formato yam do EC2 se encontra no Manual da Aws Cloudformation.
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ec2-instance.html


Framework Serverless

Nosso objetivo é automatizar tudo. E podemos criar a stack, colocar a receita.yaml, etc..... Tudo em um lugar só

Primeiro passo: Você precisa ir na aws e criar um usuário com permissão

Segundo passo: Você precisa instalar via terminal(shell) o framework servervelss. Segue abaixo

npm install -g serverless

Terceiro passo: configure seu profile via terminal

serverless create --template aws-nodejs --myservelessproject

Quarto Passo: Deploy através de linha de comando no terminal

sls deploy -s dev
