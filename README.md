
#Ajustes :

1-O projeto não tem arquivo pom.xml aonde ficam as dependencias do projeto

2-O projeto não tem SpringBoot e o main do projeto contem as regras de negocio , o ideal
Seria que as regras de negocio estivessem separadas da main .

3-As classes deveriam estar em modulos como Model(entidades do projeto) , service(regra de negocio) , repositorio(conexão com banco de dados) , controller(controle das requisições)

4-Para melhor experiencia seria bom que o sistema fosse um microserviço documentado pelo swagger e posteriormente consumido pelo front-end para melhor experiencia do usuário.

5-As senhas e usuários estão expostas no código , ideal seria o sistema estar conectado a um banco relacional 
e cadastrar os principais usuários.

