# Engenharia de Software I (20242)
# Nome dos integrantes do grupo:
1) Ruan Wickert
2) Rafael Rockenbach
3) Bernardo Bernardi
4) João Decarli

## Casos de uso do sistema de reserva de passagens aéreas
Tabelas com a descrição dos casos de uso
| **Caso de Uso 1**                 | **Descrição**                                                                                                                                       |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso**           | Realizar reserva de voo                                                                                                                            |
| **Escopo**                        | Sistema de gerenciamento de reservas de voos                                                                                                       |
| **Nível**                         | Meta do usuário                                                                                                                                     |
| **Ator principal**                | Cliente autenticado (individual ou empresa)                                                                                                       |
| **Interessados e interesses**     | Clientes: realizar reservas de maneira prática e confiável.<br>Empresa: organizar reservas e gerar vendas de passagens de forma eficiente.         |
| **Pré-condições**                 | Cliente deve possuir cadastro ativo e estar autenticado no sistema.                                                                               |
| **Garantias de sucesso**          | A reserva é salva com um código único e está disponível para ser confirmada, modificada ou cancelada dentro do prazo estabelecido.                 |
| **Cenário de sucesso**            | 1. Cliente acessa o sistema.<br>2. Seleciona origem, destino, data e horário do voo.<br>3. Escolhe um assento disponível.<br>4. Reserva é registrada. |
| **Extensões**                     | - Cliente cancela a reserva antes do prazo.<br>- Reserva expira automaticamente após 30 dias.<br>- Sistema informa falta de disponibilidade.        |
| **Requisitos especiais**          | - O sistema deve validar a identidade do cliente antes de permitir reservas.<br>- Cada reserva deve ter um código único.<br>- Segurança nos pagamentos. |


## Diagrama de casos de uso
Inserir nesta posição o diagrama de casos de uso em formato JPG.
![image](https://github.com/user-attachments/assets/c5d06f7e-5ebf-4514-92a8-298d01401226)

## Modelo de Domínio
Inserir nesta posição o modelo de domínio em formato JPG.
![image](https://github.com/user-attachments/assets/52fb0710-b1e1-4c2d-bd71-c4e09b8535fd)

## Diagrama de Atividades
Inserir nesta posição o diagrama de atividades em formato JPG.
![image](https://github.com/user-attachments/assets/e18391d4-530b-4012-9952-1f0357782732)

## Diagrama de Classes de Implementação
 Inserir nesta posição o diagrama de classes de Implementação em formato JPG.
![image](https://github.com/user-attachments/assets/501e4f67-2f1e-402b-b54e-44956731630a)

![image](https://github.com/user-attachments/assets/9041d4c8-7ec5-47c7-a285-ebd9906ca79e)
