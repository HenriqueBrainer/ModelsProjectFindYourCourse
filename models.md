# CASO DE USO

![Caso de Uso](imgs/diagrama-caso-uso.pn)

<!--@startuml
title Caso de Uso - Find Your Course

left to right direction

actor Estudante 

rectangle "Aplicação Web" {

  usecase "Selecionar Interesses" as UC1
  usecase "Cadastrar Informações" as UC2
  usecase "Buscar Curso" as UC3
  usecase "Selecionar Afinidades" as UC4
  usecase "Visualizar Opções de Cursos" as UC5
  usecase "Buscar Instituições" as UC6

}

Estudante -- UC1
Estudante -- UC2
Estudante -- UC4


UC1 ..> UC3 : <<include>>
UC4 ..> UC3 : <<include>>
UC3 <.. UC6 : <<extends>>
UC3 <.. UC5 : <<extends>>
@enduml-->
