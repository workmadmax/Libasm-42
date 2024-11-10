# README

## Useful Links

- [Link 1](https://blog.freedev.com.br/entenda-o-que-%C3%A9-assembly-ed64526cab49)
- [Link 2](https://chromium.googlesource.com/chromiumos/docs/+/master/constants/syscalls.md#x86_64-64_bit)
- [Link 3](#)

### Registradores || Registrar

* - Os registradores em Assembly para arquitetura x86-64 (bits) são componentes essencias do processadorque armazenam dados temporários e auxiliam na execução de instruções de baixo nível.

* - Os registradores gereais no modo 64 bits são usados para uma variedade de propósitos, como operações matemáticas, armazenamentos temporários de valores e passagem de parâmetros para funções.

* São 16 os principais registradores:
    
    - 1 - RAX : registrador acumulador. Muitas vezes utilizado para operações aritméticas e para retornar valores de funções.
    - 2 - RBX : registrador de base, usado como ponteiro de base em algumas operações de acesso á memória.
    - 3 - RCX : registrador contador, geralmente usado em loops e instruções de repetição.
    - 4 - RDX : utilizado em operações aritméticas e para armazenar o segundo parâmetro em chamadas de funções.
    - 5 - RSI e RDI : registradores de índice de origem e destino, frequentemente utilizados em operações de movimentação de dados, como 'mov' ou em operações de cadeia.
    - 6 - RBP : ponteiro de base, usado para acessar variáveis locais e parâmetros dentro da pilha.
    - 7 - RSP : ponteiro de pilha, aponta para o topo da pilha e é usado em operações de chamada e retorno de função.
    - 8 - R8 a R15 : registradores adicionais no modo 64 bits. expansões dos registradores tradicionais, podendo armazenar dados temporários ou parâmetros adicionais para funções.

* - REGISTRADORES DE SEGMENTO
    - esses registradores são menos utilizados no modo 64 bits, pois a segmentação foi simplificada, mas ainda existem:
        - CS : segmento de código, define onde as instruções de código estão localizadas.
        - DS, ES, SS, FS, GS : segmentos de dados e pilha, usados para referenciar diferente segmentos de memória. Em x86-64, são utilizados principalmente para compatibilidade com versões anteriores.

    - ainda existe registradores de flags, controle e depuração mais vou para por aqui e tentar usar os registradores.