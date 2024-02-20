Algoritmo "melhor aluno"
Var
 al, cont:inteiro
 nota,maior:real
 nome,melhor:caractere
Inicio
      ESCREVAL ("--------------------")
      ESCREVAL ("    Escola Pública")
      ESCREVAL ("--------------------")
      ESCREVA("Quantos alunos a turma tem? ")
      leia(al)
      cont<-1
      maior<-0
      melhor<- " "
      enquanto (cont<=al) faca
        ESCREVAL ("--------------------")
        ESCREVAL ("   ALUNO ",cont)
        ESCREVA ("Nome do aluno: ")
      leia(nome)
      ESCREVA ("Nota de ",nome, ":")
      leia(nota)
      cont<- cont+1
      se (nota>maior) entao
         maior<- nota
         melhor<- nome
      fimse
      fimenquanto
      escreval("-----------------------")
      escreval("O melhor aproveitamento foi de ",melhor, " com a nota ",maior)
Fimalgoritmo