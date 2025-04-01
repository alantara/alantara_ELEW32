# Respostas Lab1

## 7.
Para visualizar os simbolos predefinidos, criamos variáveis no escopo da main para conseguirmos visualizar pela aba Call Stack + Locals e configuramos a otimização para -O0 para conseguirmos debugar linha por linha.

### Valores atribuidos e Interpretação
- \_cplusplus -> não definido

- \_\_DATE\_\_ -> "Apr 1 2025"

- \_\_TIME\_\_ -> "12:13:22"

- \_\_FILE\_\_ -> "src_other/main.c"

- \_\_LINE\_\_ -> 0x61 = 97

- \_\_STDC\_\_ -> 0x1

- \_\_ARMCC\_VERSION -> 0x5F0FF1

- \_\_TARGET\_ARCH\_THUMB -> não definido

- \_\_STDC_VERSION\_\_ -> 0x30CDD

## 8.
- Run, Stop, Step, Step Over, Step Out, Run to Cursor Line, insert/Remove Breakpoint, Disable Brakpoint, Reset
- No modo de Debug, a tela nomeada Registers possui os registradores da CPU conectada.
- Utilizando a aba de Peripherals, podemos selecionar qual periférico queremos ver os registradores e o Keil abrirá uma nova aba com as informações.
- Na aba nomeada Memory 1 podemos selecionar o bloco de memória que queremos ver e editar cada bit.
- Utilizando a aba Call Stack + Locals, podemos selecionar variáveis para olhar.
- Porque algumas variáveis ainda podem estar não inicializadas ou fora de escopo