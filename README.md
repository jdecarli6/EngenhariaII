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
![Diagrama PlantUML](https://www.planttext.com/api/plantuml/png/VLNDQXmn3BuFp3kOlGJQxDBIsn12DjiMIg6K9FIkZhKJ5ziojcS9BNsOqaEVe4-mBrPv_dPsPjAzhD4dMv-aJvgR4C77skWykn0x3I5W4CuhMoe7AWX98gWGqK2UbGbc9uKselYHPu9_BqNfzeMuZtodwas-cbei6PpQ94Ju1A5KXX-aGho5Y3t60PMUNYXHrnhypAmaIBp3e2GoRvZYzNu9-vbdVKhlZFCOO9IITT-MCkWSfr14ZNkok2CR8MLo3ZUvF8ErtEUC5tbo6kWFOvuaLKMTUQcyvqLz9C-M1wvtR-7knphqDyNL5UY87YHS2jnZL8VcM8BbqlFn-hg_U03TCV_0OgZGyrsf82IF4UClH5EsR9eo9QygD3F-6AAoC-UKX5Tq3np_F9aEsJrY1LDCieWX2U2Z6IYVCTsY9mk7aQwZShFW7Yj-oDFTzdRMIN3GTdFBGyI23ik1FYjDaVuxFal3Ocl336yz7cRGCsCn6Q4n1QYWcRaJ2uEH90t0I15EFLsAhwJP8Id1n-DlEkd0WK_I26CTcEElfuruSoOMyWyKWUcyrmJnL4uq_7IWpiwNqN2GGDpzNdODeK5N5uBBIzp8uv_ZNzvL37eK44JPBgyywnVKwlLAhDVyjzcyM0spKt1GrkvttcVzs2yvvbbo1McKJGrdx_w1mNlLg3kzjqUFwy1QIuOHFcYg47LKRT29IwU6GhXq05wtZlnYi5FJ2i5rXhOOTroWKd6K5iBWa6kZvrLujTdmgK-Pun5NsA6Fl1QJGc_GokOpy0y0)

## Diagrama de Atividades
Inserir nesta posição o diagrama de atividades em formato JPG.
![image](https://github.com/user-attachments/assets/e18391d4-530b-4012-9952-1f0357782732)

## Diagrama de Classes de Implementação
 Inserir nesta posição o diagrama de classes de Implementação em formato JPG.
![image](https://github.com/user-attachments/assets/501e4f67-2f1e-402b-b54e-44956731630a)

![image](https://github.com/user-attachments/assets/9041d4c8-7ec5-47c7-a285-ebd9906ca79e)
