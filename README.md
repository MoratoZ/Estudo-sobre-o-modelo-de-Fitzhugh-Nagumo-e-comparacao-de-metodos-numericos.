# Estudo sobre o modelo de Fitzhugh–Nagumo e comparação de métodos numéricos.

Esse documento tem o objetivo de apresentar as animações feitas para para o resumo expandido "ESTUDO SOBRE O MODELO DE FITZHUGH–NAGUMO E COMPARAÇÃO DE MÉTODOS NUMÉRICOS" escrito para o  IX Encontro de Iniciação Científica e Pós-graduação do Instituto Federal de São Paulo - Campus São Paulo (EICPOG).

## Animações para bifurcação de Hopf

Como descrito no texto, aqui estão as animações com base nos parâmetros da Figura 3. A 1ª animação considera apenas a condição inicial $v(0)=1$, $\omega(0)=0$.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/d8664cfd-f382-4dcf-99e2-90423c1dc49d

A 2ª utiliza diversos valores iniciais para $v(0)$ e $\omega(0)$.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/758e9dcf-09e3-4365-ad45-e0b38cdb8ef0

## Animações para o caso onde $\kappa \leq bc$

Também foram feitas animações com os parâmetros $a=0,15$, $b=0,2$ e $c=2,5$, isso é, o caso onde $\kappa \leq bc$, onde espera-se que, para qualquer $I$, o ponto de equilíbrio mantenha-se assintoticamente estável. Como anteriormente, foi feito uma animação considerando a condição inicial $v(0)=1$, $\omega(0)=0$.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/b9fb6901-400c-4fa2-845a-b2f13c505274

E outra com diversos valores iniciais.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/a66cf5ea-6159-4718-940e-8087dd478182

É possível ver que durante todos os valores testados de $I$, a singularidade é um atrator, como esperado.

## Animação para caso onde $b \rightarrow 0$

Conforme $b \rightarrow 0$ a condição $bc < \kappa$ é atendida e com isso ocorre a bifurcação de Hopf, além disso, como $b \rightarrow 0$ então pela segunda equação de (1) $\frac{d\omega}{dt} \rightarrow 0$, logo se espera que com a diminuição de $b$ as trajetórias se tornem praticamente horizontais, com exceção de quando as mesmas estão próximas da função polinomial de 3º grau pois nessa situação $\frac{dv}{dt} \rightarrow 0$. Isso é ilustrado na seguinte animação, feita utilizando os parâmetros $a=0,15$, $I=0,1$ e $c=2,5$ e as condições iniciais $v(0)=1$, $\omega(0)=0$.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/9445085d-87bd-4357-ab78-730005769193

## Animações mostrando a mudança entre o estado excitável e oscilatório

Por último, foram desenvolvidas duas animações mostrando a mudança entre o estado excitável e oscilatório da célula nervosa, bem como sua relação com a bifurcação do modelo. A primeira utiliza os parâmetros $a=0,15$, $b=0,05$ e $c=2,5$ e os valores iniciais $v(0)=1$, $\omega(0)=0$.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/b09e241b-7bf4-471e-bfb9-313fbb228ef1

A segunda usa $a=0,139$, $b=0,008$ e $c=2,54$ e as mesmas condições iniciais.

https://github.com/MoratoZ/ESTUDO-SOBRE-A-DINAMICA-DO-MODELO-DE-FITZHUGH-NAGUMO-E-COMPARA-O-DE-METODOS-NUMERICOS-NO-MESMO/assets/171053133/eac22dc6-a312-42c5-844b-5b21776a2e30

Nota-se em ambas o crecimento de $v$ conforme o aumento de $I$.
