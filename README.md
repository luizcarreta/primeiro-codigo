# média vendas - portugol
programa
{
	
	funcao inicio()
	{
		real jan,fev,mar,abr,media,soma
		cadeia vendedor

		escreva("Digite o nome do vendedor:")
		leia(vendedor)
		escreva("Digite as vendas de janeiro:")
		leia(jan)
		escreva("Digite as vendas de fevereiro:")
		leia(fev)
		escreva("Digite as vendas de março:")
		leia(mar)
		escreva("Digite as vendas de abril:")
		leia(abr)

		media=(jan+fev+mar+abr)/4
		soma=(jan+fev+mar+abr)
		
		escreva(" A média de vendas do vendedor " + vendedor + " é: " + media + " e o total das vendas é: " + soma)
		
	}
}

