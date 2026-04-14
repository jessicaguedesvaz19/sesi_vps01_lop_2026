# Título: VPS01
## Subtítulo descrição: Verificação Prática Somativa 01 
Arquivos gerados durante a avaliação de Lógica de Programação, algoritmos e fluxogramas 

## Tecnologias

|Tecnologia|Ultilidade|
|:-:|-|
|Linguagem *C*|Desenvolvimento|
|IDE| Embarcadero *Dev C++*|
|[Draw.io](https://app.diagrams.net/)  |Braw.io |para desenhar os fluxogramas|
| Bloco de notas|* portugol* lógica|

  ## Como testar
  - 1 Clone este repositório
  - 2 Abra os arquivos .c com o DevC++
  - 3 Pressione F11 para compilar execultar

## Exemplo de código 
```c
#include<stdio.h>
#include<windows.h>
void main(){
	SetConsoleOutputCP(CP_UTF8);
	char nome[20], sexo;
	int idade;
	printf("Digite seu nome, sexo m/f e idade\n");
	scanf(" %s %c %d", &nome, &sexo, &idade);
	if(sexo == 'm'){
		if(idade > 65){
			printf("O atendimento do paciente %s é prioritário", nome);
  		}else{
		  	printf("O atendimento do paciente %s é normal", nome);
  		}
   }else{
      if(idade > 60){
	  	printf("O atendimento do paciente %s é prioritário", nome);
      }else{
      	printf("O atendimento do paciente %s é normal", nome);
	  }
    }
    getch();
}
```
![Fluxograma](./atendimento.png).
