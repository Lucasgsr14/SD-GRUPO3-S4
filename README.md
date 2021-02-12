# SD-GRUPO3-S4

# SD_Grupo3

* MONTAR OS BLOCOS SEGUINDO O PADRÃO DE ACESSO A VARIÁVEIS INTERNAS:
  * 1º NÍVEL: X_{de qual componente vem}:OUT (std_logic) ;
  * 2º NIVEL: X_{nome do bloco}_{nome do sinal/de qual componente vem}:OUT (std_) ;
  
  ![IMAGEM](https://github.com/Lucasgsr14/SD-GRUPO3-S4/blob/main/Untitled%20Diagram.png)
  
  2 Faceis = 1 médio
  2 médios = 1 difícil
  total = 21 pontos (1 de 6 e 3 de 5);

### Quarta(10/02)! 

- [x]  ESCREVER ERROS DE PROJETO PARA A PROXIMA REUNIÃO;

- [x] PESQUISAR SOBRE A FACILIDADE DE TER MONTADOR DE COGIGO DE MÁQUINA; escolher entre:

  * Montar o código de máquina na mão; ou
  * Construir um montador automático.

---

##### Decisões:

 * RETIRAR OS REGISTRADORES (RF_W_addr, RF_Rp_addr, Value_JMP); - 
 * Adicionar flip-flops (Carry, ULA); - NÃO PRECISA DE CLEAR; - 
 * Redefinir os estados adicionar por necessidade dos registradores retirados (Onde tem três da pra fazer em 1 só);
 * Ajeitar o estado de busca;
 * Resumir estados de JMP;
 * Mudar os estados multiplos de incremento para um estado só;
 * Corrigir a saída da ULA;
 
### Quinta(11/02)! 
 
* Ajeitar Datapath <- Lucas
* Corrigir Estados da MDE <- Erika, Wesley, Paulo;

LD_REG, STR, MOV
JMP, JZ, JNZ, JNC, JC
ADD, SUB, AND, OR, NOT, XOR, CMP

### Segunda(15/02)!

VHDL's

---

* Registrador IR; - Fácil - ERIKA
* PC; - Fácil - LUCAS
* Memória de Dados (RAM); - Médio - WESLEY
* Memória de Intruções (ROM1, ROM2); - Fácil - WESLEY
* ULA(Simples e Composta); - Fácil - PAULO
* Banco de Registradores; - Médio - WESLEY
* FlipFlops D; - Fácil - ERIKA
* MDE; - Difícil - ERIKA

ASSEMBLY's

---

* Código de Máquina(1)(ASSEMBLY); - Médio - LUCAS
* Código de Máquina(2)(ASSEMBLY); - Médio - LUCAS

### Quarta(17/02)!

VHDL

---

* CPU (FINAL); - Díficil - PAULO

FUNÇÕES:

 * LÍDER:  LUCAS G.
 * REDATORA: ERIKA
 * VIDEO MAKER: PAULO
 * DEBATEDOR: WESLEY

## ATIVIDADES LUCAS

 *  [DATAPATH](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686481)
 
## ATIVIDADES ERIKA

 * [LD_REG](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686341)
 * [JMP](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686391)
 * [ADD](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686399)
 * [SUB](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686405)
 * [ESTADO DE INCREMENTO (DEFINIR NOME)](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686416)
 
## ATIVIDADES WESLEY

 * [STR](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686419)
 * [JZ](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686427)
 * [JNZ](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686436)
 * [AND](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686436)
 * [OR](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686443)

## ATIVIDADES PAULO

 * [MOV](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686447)
 * [JNC](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686450)
 * [JC](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686451)
 * [XOR](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686460)
 * [CMP](https://github.com/Lucasgsr14/SD-GRUPO3-S4/projects/1#card-54686462)

