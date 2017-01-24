Projeto Coding WikiHouse

https://github.com/codingwikihouse

_________________________________________________________________

Este algorítmo é um projeto acadêmico de programação visual
que tem como objetivo estudar a parametrização do 
sistema construtivo da WikiHouse v3.0.

Está disponível para toda(s) a(s) comunidade(s) sob os termos da licença
Creative Commons Attribution-ShareAlike 4.0 International.

A versão disponibilizada aqui (v22) é uma cópia que foi 
apresentada pelo Arquiteto David Mendonça como Trabalho 
Final de Graduação da FAU UFRJ, sob a orientação dos 
Professores Andrés Passaro e Gonçalo Henriques. Trabalho
este desenvolvido dentro do LAMO (Laboratório de Modelos) 
da Faculdade de Arquitetura e Urbanismo.
Maiores informações em:

http://www.lamo.fau.ufrj.br/projetos/academicos/048tfgwikicurva/ 

https://issuu.com/davidmendonca/docs/tfg

_________________________________________________________________


Como o algorítmo funciona?



A modelagem paramétrica nesse algorítmo conta com parâmetros informados
pelo usuário, assim, algumas variáveis precisam ser inseridas no código.

É na coluna inputs que alguns parâmetros deverão ser informados, são eles:
(de cima para baixo)

1) Componente "Curve" (FRAME): é a curva 2D informada ao algorítmo que vai
gerar toda a volumetria e peças, com a forma de acordo com seu perfil.

2) Componente "Points" (SJOINTS): São pontos contidos (ou próximos) 
a curva informada onde serão aplicados os encaixes S-Joints.

3) Componente "Points" (CONECTORES HORIZONTAIS): São pontos contidos (ou próximos) 
a curva informada no item 1), onde serão aplicados os conectores horizontais.

4) Componente "Points" (PEGS): São pontos contidos (ou próximos) 
a curva informada no item 1), onde serão aplicados os pegs.

Todos esses dados estão internalizados em seus respectivos componentes.
A unidade de medida usada é milimetros.

_________________________________________________________________


Vocabulário:

Frame: Forma que definirá o perfil 2D da WikiHouse

S-Joints: Encaixes em formato de S que conectam as diferentes partes do frame.

Conectores horizontais: conexões horizontais que conectam os diferentes frames.

Pegs: Encaixes onde os painéis de vedação serão encaixados.

PS: É devida muita atenção para evitar conflito entre os dados informados acima,
eg.: os pontos informados no PEGS não podem coincidir com os SJOINTS, o mesmo vale
para os CONECTORES HORIZONTAIS, de preferência, cada um dos três parâmetros deverá
ser informado em uma coordenada única ao longo da curva.

________________________________________________________________________

Versão do leia me: 1.0. 
Em 24/01/2017
