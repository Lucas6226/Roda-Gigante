# Roda Gigante Animada 

Projeo feito para exercitar conhecimentos basicos de animações CSS, a roda gigante é feita 100% em HTML&CSS vanila. Sem o uso de imgens, gifs, svgs, e etc.... 

* https://roda-gigante-kappa.vercel.app/


As medidas da roda gigante são definidas atráves de uma simples formula aplicada em CSS, valorBase*x de forma que, x é a certa medida do elemento em questão e valorBase é uma variável comun a todas as aplicações da formula. Dessa forma podemos ter o seguinte cenario: 

* Elemento-A `height: calc(20*var(--medida-base))`
* Elemento-B `height: calc(10*var(--medida-base))`

Em casos como este podemos apenas dobrar a medida base os dois elementos dobram de tamanho e toda a animação segue o padrão e se mantem prorcional. Viso esse sistema como mais eficiênte em realação ao uso de medidas percentuais, pois, desta forma as medidas mantêm o mesmo comportamento a independer do valor atribuido à tag `position: ;`, a qual influência no comportamento de medidas percentuais. 

