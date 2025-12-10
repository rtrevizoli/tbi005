# EX 06 - Criptografia e Socket
Rafael Trevizoli - 1460282423016
Professor Diogo Branquinho Ramos

**Topic:** Criptografia e Socket
**Lab:** [EX6 - Criptografia e Socket.pdf](lab/EX6-2.pdf)

## EX6 - Criptografia e Socket

> ***Importante 1:*** Exemplos encontram-se no GitHub: [@diogobranquinho](http://github.com/diogobranquinho)

### Criptografia
#### 1. Elabore um programa ilustrando a geração de chaves, criptografando e descriptografando os dados.  
> GitHub: [@rtrevizoli/Encryption](https://github.com/rtrevizoli/Encryption/).

##### a. Explique o código fonte utilizado;  
Utilizado python como linguagem principal pela simplicidade e as biblotecas **rsa**, **pathlib** e **argparse**.

* `rsa` foi utilizada para a principal funcionalidade do programa, a geração de pares de chave assimétricas.
* `pathlib` foi utilizado para a sanitização dos arquivos e caminhos, assim como para confirmar a exsistência do arquivo e a opção em sobrescrever o mesmo.
* `argparse` foi utilizado para trazer um comportamento de programa de linha de comando, onde os principais inputs do usuário são informados.

##### b. Descreva os resultados obtidos.
Com a execução deste programa é possível a geração de pares de chaves assimétricas, podendo ser utilizadas para criptografar e descriptografar mensagens e arquivos pelos detentores das mesmas.

<p align="center">
<img src="lab/assets/01_Mermaid-encryption-flow-chart.png" alt="Img 01 - Encription flowchart"/><br>
<em>Img 01 - Encription flowchart</em>
</p>

### Socket
1. Elabore um programa ilustrando a conexão socket UDP entre dois processos.  
    a. Explique o código fonte utilizado;  
    b. Descreva os resultados obtidos.

2. Elabore um programa ilustrando a conexão socket TCP entre dois processos.  
    a. Explique o código fonte utilizado;  
    b. Descreva os resultados obtidos.

1. Elabore um programa ilustrando a conexão socket TCP de servidor com thread.  
    a. Explique o código fonte utilizado;  
    b. Descreva os resultados obtidos.
