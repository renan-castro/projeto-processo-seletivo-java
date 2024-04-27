# Processo Seletivo - Candidatura

Este é um programa simples em Java que simula um processo seletivo de candidatos para uma vaga de emprego. O programa realiza algumas operações básicas, como tentar entrar em contato com os candidatos, selecionar candidatos com base em seus salários pretendidos e analisar suas candidaturas.

## Funcionalidades

1. **Entrar em Contato com os Candidatos**: O programa tenta entrar em contato com cada candidato da lista, realizando até três tentativas.

2. **Selecionar Candidatos**: Com base nos salários pretendidos pelos candidatos, o programa seleciona até cinco candidatos para a vaga de emprego.

3. **Analisar Candidatos**: Analisa o salário pretendido de cada candidato e decide se deve entrar em contato com eles, fazer uma contraproposta ou aguardar o resultado dos demais candidatos.

## Estrutura do Código

O código está organizado em classes e métodos para facilitar a compreensão e manutenção do programa:

- `ProcessoSeletivo`: Classe principal que contém o método `main` para iniciar o processo seletivo.
- `entrandoEmContato`: Método para tentar entrar em contato com um candidato.
- `atender`: Método auxiliar para simular se o candidato atendeu ou não à ligação.
- `imprimirSelecionados`: Método para imprimir a lista de candidatos selecionados.
- `selecaoCandidatos`: Método para selecionar candidatos com base nos salários pretendidos.
- `valorPretendido`: Método para gerar um valor aleatório para o salário pretendido de um candidato.
- `analisarCandidadato`: Método para analisar o salário pretendido de um candidato e decidir a ação apropriada.

## Como Utilizar

1. Clone o repositório para o seu ambiente de desenvolvimento.
2. Compile e execute o programa Java.
3. Siga as instruções no console para acompanhar o processo seletivo.

## Contribuição

Contribuições são bem-vindas! Se você tiver alguma ideia para melhorar este programa ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.
