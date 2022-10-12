# TIPOS-DE-OBJETOS-NO-R

# Criação de um dataframe

vetor nome <- c('Maria', 'José', 'Tereza', Joaquim', 'Eduardo') # vetor nome de alunos

vetor TEM <- c(8.7, 9.4, 10, 8.5, 9.5) # vetor notas Tópicos Especiais de Metodologia

Vetor OPP <- c(8.1, 9.2, 8.3, 9.7, 8.8) # vetor notas Orçamento em Políticas Públicas

vetor RPP <- c(9.1, 8.2, 8.6, 9.9, 9.5) # vetor notas Regulação em Políticas Públicas

presença <- c(95, 70, 80, 100, 90) # vetor presença 

df <- data.frame (nome, TEM, OPP, RPP, presença)

view (df)



