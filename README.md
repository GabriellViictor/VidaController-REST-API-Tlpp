# VidaController-REST-API-Tlpp
A classe VidaController atua como uma interface de comunicação para a tabela de "Vidas" (BTS) no  sitema Protheus, permitindo operações completas de um CRUD - Create, Read, Update e Delete. 

Tipo   URL                               Body   Funcao

POST   http://localhost:8080/vida/       Sim    Store                                                                                       
GET    http://localhost:8080/vida/"CPF"  Nao    Show                                                                                        
PUT    http://localhost:8080/vida/"CPF"  Sim    Update                                                                                      
DELETE http://localhost:8080/vida/"CPF"  Nao    Destroy                                                                                                                                                                             
