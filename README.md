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

![Diagrama PlantUML](https://www.planttext.com/api/plantuml/png/PP2x2iCm34LtW__1PC_Gf7D9C1sw5le1mbP1u3WWAVd-lgaJZpeShguqY0BhCYLh8EZCpYV2hFWRnpXH9b66EBCrrYo20GHTSyaK2DXTKP1NQ1o8k_b3OPplgBHMIbSeOrBaokWBmqCEc2hb-EhoxUhQzlHPlGNT7lHxy4pP7FZ70-Ru_ie3)

## Modelo de Domínio

![Diagrama PlantUML](https://www.planttext.com/api/plantuml/png/VLNDQXmn3BuFp3kOlGJQxDBIsn12DjiMIg6K9FIkZhKJ5ziojcS9BNsOqaEVe4-mBrPv_dPsPjAzhD4dMv-aJvgR4C77skWykn0x3I5W4CuhMoe7AWX98gWGqK2UbGbc9uKselYHPu9_BqNfzeMuZtodwas-cbei6PpQ94Ju1A5KXX-aGho5Y3t60PMUNYXHrnhypAmaIBp3e2GoRvZYzNu9-vbdVKhlZFCOO9IITT-MCkWSfr14ZNkok2CR8MLo3ZUvF8ErtEUC5tbo6kWFOvuaLKMTUQcyvqLz9C-M1wvtR-7knphqDyNL5UY87YHS2jnZL8VcM8BbqlFn-hg_U03TCV_0OgZGyrsf82IF4UClH5EsR9eo9QygD3F-6AAoC-UKX5Tq3np_F9aEsJrY1LDCieWX2U2Z6IYVCTsY9mk7aQwZShFW7Yj-oDFTzdRMIN3GTdFBGyI23ik1FYjDaVuxFal3Ocl336yz7cRGCsCn6Q4n1QYWcRaJ2uEH90t0I15EFLsAhwJP8Id1n-DlEkd0WK_I26CTcEElfuruSoOMyWyKWUcyrmJnL4uq_7IWpiwNqN2GGDpzNdODeK5N5uBBIzp8uv_ZNzvL37eK44JPBgyywnVKwlLAhDVyjzcyM0spKt1GrkvttcVzs2yvvbbo1McKJGrdx_w1mNlLg3kzjqUFwy1QIuOHFcYg47LKRT29IwU6GhXq05wtZlnYi5FJ2i5rXhOOTroWKd6K5iBWa6kZvrLujTdmgK-Pun5NsA6Fl1QJGc_GokOpy0y0)

## Diagrama de Atividades

![Diagrama PlantUML](https://www.planttext.com/api/plantuml/png/RP11RW8n34NtaN87BuShmAAWeQgweLMHs4U91onbx2eENAYB7g17c8lLKuOH4iqcYVtz_Uorrb3gkS_U_RsyMxuoHGe5Fb2nNCBAE-gWQJCXLuHmhdPJ34cU5b1FoD3igLzu1tQMUymOITZgtmeTiGU4BMebbjKaUTOe-OG53ZB7fbu5DgfcFyOnAqAp6xvazfPiP7LKtI26RykFOaxKNK4dAsY5EofzIE4_pXSivjCEFucE0Wdlfhr2ycNSmSraxlC0rGQEc4twNYIYwXsDLldqRcq_s-yl)


## Diagrama de Classes de Implementação

![Diagrama PlantUML](https://www.planttext.com/api/plantuml/png/PP113e8m44NtJNg7BZM62x0m6EBIXE09HXX9az8cqu45nhiBs5RKhjhNzityAJm3yT0RAHe3tglIQBICwY65cjVXDF1yrWtGRf-hctC6mOQx6i7e2QX6ZpJ2yY1ifNXA4PM19UNvZgp7jt1qkesL32FzqH9iWsQBD-OAEkZdzbnoNv1Twt9rPTAs2x02MXm-LzhoJ-z9yHLlhH57aMN7JwuOPe7fhnG5sdQTuWi0)


![image](https://github.com/user-attachments/assets/9041d4c8-7ec5-47c7-a285-ebd9906ca79e)
