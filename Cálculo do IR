#include <stdio.h>
#include <locale.h>
//Cálculo do INSS

int main(void)
{

setlocale(LC_ALL, "Portuguese");
float sal, ir;

printf("Digite seu salário: R$");
scanf("%f", &sal);

if (sal <= 1903.99)
{
  ir = 0;
}
else
{
  if(sal <= 2826.65)
  {
    ir = (sal * 0.075) - 142.80;
  }
  else
  {
    if(sal <= 3751.05)
    {
      ir = (sal * 0.15) - 354.80;
    }
    else
    {
      if (sal <= 4664.68)
      {
        ir = (sal * 0.225) - 636.13;
      }
      else
      {
        ir = (sal * 0.275) - 869.36;
      }
    }
  }
}

if (ir == 0)
{
  printf("Você é isento do imposto");
}
else
{
  printf("Imposto calculado: R$%.2f", ir);
}
}