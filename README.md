programa
{
	
	funcao inicio()
	{
		inteiro soma = 0 
		inteiro alunos[3][3] = {
			{1,3,5},
			{7,9,11},
			{13,15,17}
			
		}
		   
			para(inteiro linh=0; linh < 3; linh++)
			{
				para(inteiro colu=0; colu < 3; colu++)
				{

					escreva(alunos[linh][colu]," ")
					
					soma += alunos[linh][colu]
							
				}
				
		     	escreva("\n")
						
			}

				escreva("==============================\n")
				escreva("A soma das matrizes é de = ", soma)
				escreva("\n==============================\n")
				
	} 
}
