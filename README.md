# Alogoritimo-convers-o-d-lar-2

Declaração
	numero1: decimal;
	numero2: decimal;
	Resultado: decimal;

Inicio

	ESCREVA("Digite a cotação do dólar");
	LEIA(numero1);
	ESCREVA("Digite o valor desejado para a conversão");
	LEIA(numero2);
	
	SE(numero2<10) ENTAO
		ESCREVA("Não é possível fazer conversão. O valor à ser convertido deve ser maior que 10");
	SENAO
	  	SE(numero2 = 10) ENTAO
			  Resultado<-numero1*numero2;
			  ESCREVA("O resultado é:");
		  		ESCREVA(resultado);
	SENAO
			    Resultado<-numero1*numero2;
			    ESCREVA("O resultado é:");
		    		 ESCREVA(resultado);
		FIM-SE
	
	FIM-SE
	
FIM
