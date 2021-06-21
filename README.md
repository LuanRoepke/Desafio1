# Desafio1

Passo a passo
- Criei um conjunto de dados no Machine Learning do Azure e fiz um upload dos microdados do Enem 2019

- Selecionei apenas as colunas NU_NOTA_CN, NU_NOTA_CH, NU_NOTA_LC e NU_NOTA_MT,

- Criei uma instância de computação e um cluster de cálculo com a configuração Standard_D11_v2 e o tipo de máquina virtual sendo CPU

- Criei um pipeline de teste:

<img src="1.png"/>

Nele, eu configurei o clean data desse modo:

<img src="4.png"/>

O normalize data desse modo:

<img src="5.png"/>

E o Split data assim:

<img src="6.png"/>

- depois criei um pipeline de inferencia:

<img src="2.png"/>

- pus esses dados para testar:

<img src="3.png"/>

- e esse foi o resultado do teste:

<img src="7.png"/>

