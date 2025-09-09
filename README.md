# Olá, Mundo!
Primeiro Repositório do curso de Git e Github

Repositório criado a partir do curso do Gustavo Guanabara.

Essa linha adicionei diretamente no site do github.


# Aula de linguagem Markdown
Podemos __*misturar*__ configurações

Lista numerada:
1. Teste
2. Teste2
3. Teste3

Lista demarcada:
* Teste
* Teste
* Teste

Lista de tarefas:

- [x] Criar a página principal
- [x] Criar a pagina da loja
- [ ] Finalizar a reunião como cliente
- [ ] Receber o pagamento

Para criar links:
[Acesse meu Gihub](https://github.com/FelipeRodriguesPinheiro)

Para tabelas:
Número | Nome | Nota
---|---|---
1 | Felipe | 10
2 | Alex | 4
3 | Murilo | 3.9

Terminou a tabela

Para mostrar apenas uma linha de código colocar entre crases:
`printf("Ola mundo");`

Para um código maior usar 3 crases abrindo e fechando:
```
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int A[15]= {7,13,25,42,58,3,19,64,81,9,37,72,5,91,46};
    int n = sizeof(A) / sizeof(int);
    for(int i=0; i<n-2; i++)
    {
        int trocou = 0;
        for(int j=0; j<=n-2; j++)
        {
            if(A[j]>A[j+1])
            {
                int aux=A[j];
                A[j]=A[j+1];
                A[j+1]=aux;
                trocou=1;
            }
        }
                if(trocou == 0)
            {
                break;
            }
    }
    for(int i=0; i<n; i++)
    {
        printf("%d ",A[i]);
    }

    return 0;
}

```

Para emojis usar 2 pontos:
🖖
