# Banco de Dados

- [Conceitos](#conceitos)
    - [SGBD](#sgbd)
    - [BD Centralizado](#bd-centralizado)
    - [BD Cliente](#bd-cliente-servidor)
    - [BD Distribuído](#bd-distribuido)
    - [Datawarehouses](#datawarehouses)
  
Aula do dia 15/08/2023

# Conceitos

Um banco de dados é uma coleção organizada de informações/dados estruturadas, normalmente armazenadas em um sistema de computador. Atende uma comunidade de usuários

*para a prova, ele dará um cenário para nós modelarmos (vamos aprender três conceitos de modelagem + a linguagem)

# SGBD

O sistema Gerenciador de Banco de Dados é um software de uso geral que facilita o processo de descrição, construção, manipulação e compartilhamento de banco de dados entre diversos usuários e aplicações.

![image](https://github.com/RafaelaDBonis/BD/assets/98855185/f54ff641-6a5a-4bb7-979f-bef578bb83cc)


# BD Centralizado

Nesse ambiente, os dados e os programas ficam restritos a uma única máquina, sendo acessado por terminais burros
- *Sistemas Gerenciadores de Arquivo* - arquivos são agrupamento de dados armazenados em algum tipo de dispositivo de armazenamento fisíco, e
para acessar esses dados e utilizá-los eram criadas Aplicações (programs de computador).

# BD Cliente (Servidor)

Devido a possibilidade de conexão entre diversas máquinas com alto poder de processamento, o banco de dados pode ser deslocado para uma máquina específica, o servidor de arquivos.

![image](https://github.com/RafaelaDBonis/BD/assets/98855185/5ec430e3-4668-4bd3-a3a4-ce93e513627e)

# BD Distribuídos

Pelo crescimento em volume de dados e redes se tornando quase ilimitadas em tamanho, surge a necessidade de distribuição da própria base de dados (banco de dados distribuídos). Representam a divisão o banco de dados por vários servidores de BD.

![image](https://github.com/RafaelaDBonis/BD/assets/98855185/7844cb2d-9fa1-4346-9e76-5886f887be24)

# Datawarehouses

Os datawarehouses, ou armazéns de dados, contém dados preparados para atender as necessidades de informação dos
níveis estratégicos da organização. Um data warehouse armazena dados atuais e históricos de toda a empresa e alimenta o BI e as funções analíticas.

![image](https://github.com/RafaelaDBonis/BD/assets/98855185/2218a370-fce2-4dc8-b03a-d9c562119704)

# Data mart
