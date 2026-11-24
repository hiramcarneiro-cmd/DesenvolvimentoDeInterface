# Relatório de Testes — Calculadora
## Atividade

A calculadora precisa mostrar as respostas esperadas nos testes realizados. Cálculos das médias, classificando os resultados certos como Reprovado, Recuperação ou Aprovado.

Também montar testes com notas inválidas, usando números abaixo de 0 e acima de 10, que são fora do permitido.
## Casos de teste

| Caso | Dados de entrada | Resultado esperado | Resultado obtido | Status |
| ---- | ---------------- | ----------------- | ---------------- | ------ |
| 1 | Nome: Hiram; Notas: 6, 2, 3 | Média 3,7; Reprovado | Média 3,7; Reprovado | Correto |
| 2 | Nome: Hiram; Notas: 6, 6, 6 | Média 6,0; Recuperação | Média 6,0; Recuperação | Correto |
| 3 | Nome: Hiram; Notas: 7, 7, 8 | Média 7,3; Aprovado | Média 7,3; Aprovado | Correto |
| 4 | Nome: Hiram; Notas: 6, 7, -10 | Use notas entre 0 e 10. | Use notas entre 0 e 10. | Correto |
| 5 | Nome: Hiram; Notas: 6, 7, 20 | Use notas entre 0 e 10. | Use notas entre 0 e 10. | Correto |

