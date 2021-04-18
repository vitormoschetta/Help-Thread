# Help-Thread

Thread é um processo/tarefa executada pela Unidade Central de Processamento (CPU). 

Uma CPU pode ser single-thread ou multi-thread:

1. Single-thread   
O processador executa uma única tarefa de cada vez, ou seja, as tarefas são concorrentes.

2. Multi-thread  
O processador cria processos distintos na mesma thread, e os executa paralelamente, ou seja, ao mesmo tempo.   

Prós: Execução de diversos processos e/ou programas de forma mais eficiente.

Contras: Maior complexidade de processamento; Aquecimento excessivo do processador. 

Foi olhando para os contra-argumentos apontados acima, que foram desenvolvidos processadores multi-core, ou seja, uma única CPU com dois ou mais núcleos. Isso é
basicamente ter duas ou mais CPUs no mesmo espaço físico. 

Obs: Processadores multi-core podem também ter os seus núcleos funcionando em multi-thread. 

<br>

## Aplicaçes multi-threads
Não adianta um processador ser multi-thread se a aplicação não der suporte a isso. 

Veja no link abaixo exemplos de multi-thread em C# com Thread e Task:

<https://github.com/vitormoschetta/Help-CSharp/tree/master/src/Threads>

<https://github.com/vitormoschetta/Help-CSharp/tree/master/src/Tasks>
