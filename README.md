# Alunos.DAT
Exercicios (ou Rascunhos) de exercicios feitos na faculdade.

#include<iostream>
#include<stdlib>
#include<stdlib.h>
#include<fstream>
#include<ioman.p>
#include<STDIO.H>

#define NOTA1;
#define NOTA2;
#define NUMERO;

using namespace: std;




struct dados_do_aluno
typedef struct{
 char nome_do_aluno;
 float numero;
 int curso;
 float nota1;
 float nota2;
 int i;

}
void.ler(string_Meuarquivo);



int main(){
 // Abrindo o arquivo para escrita
    ofstream arquivo("alunos.dat");
 
 // Verificando se o arquivo foi aberto corretamente
     if (!arquivo.is_open()) {
     cout << "Erro ao abrir o arquivo" << endl;
     return 1;
     }

char nome_do_aluno 
double nota1 [NOTA1]
double nota2 [NOTA2]
double numero [NUMERO];
int curso

int nome_do_aluno;
int nota1[9];
int nots2[8];
int numero[]
int curso;

while (leitura.eof())

cout <<"nome do aluno/ numero/ curso / nota1 / nota 2" << endl;

ofstream outClientFile("alunos.dat", ios::out);

cout << "Insira o nome completo" << "Enter end-of-file to end input. \n?";


// leitura >> nome_do_aluno >> matricula >> email;

arquivo << numero << "," << nome << "," << curso << "," << nota1 << "," << nota2 << endl;
cout <<"?";


return 0;

//
float nota1, nota2;

do{
printf("Digite a primeira nota: ");
scanf("%f", &nota1);

while(nota1 < 0 \\ nota > 10);
}

do{
printf("Digite a segunda nota: ");
scanf("%f", &nota2);

while(nota2 < 0 \\ nota > 10);

}

  
  // Fechando o arquivo
    arquivo.close();
    
    return 0;

}


