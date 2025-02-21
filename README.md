# Projeto de Redes - Configuração de Sub-redes e Roteamento

 

## Introdução

Este projeto tem como objetivo criar uma rede baseada na faixa 10.100.0.0/20 para atender os departamentos de TI, Helpdesk, Recursos Humanos, Inovação, Vendas e Gerência. A rede foi configurada no GNS3 e conectada a um servidor externo na rede 152.132.30.0/29 para validação de comunicação externa.

 

## Planejamento

 

### Rede Principal

- **Rede Principal**: 10.100.0.0/20 (4096 endereços)

 

### Sub-redes e Justificativas

1. **TI**: 10.100.0.0/21

   - **Hosts Necessários**: 100

   - **Faixa de IPs**: 10.100.0.1 - 10.100.7.254

   - **Gateway**: 10.100.0.1

 

2. **Helpdesk**: 10.100.8.0/22

   - **Hosts Necessários**: 120

   - **Faixa de IPs**: 10.100.8.1 - 10.100.11.254

   - **Gateway**: 10.100.8.1

 

3. **Recursos Humanos (RH)**: 10.100.16.0/24

   - **Hosts Necessários**: 40

   - **Faixa de IPs**: 10.100.16.1 - 10.100.16.254

   - **Gateway**: 10.100.16.1

 

4. **Inovação**: 10.100.12.0/22

   - **Hosts Necessários**: 50 (expansão futura para 129)

   - **Faixa de IPs**: 10.100.12.1 - 10.100.15.254

   - **Gateway**: 10.100.12.1

 

5. **Vendas**: 10.100.20.0/24

   - **Hosts Necessários**: 300

   - **Faixa de IPs**: 10.100.20.1 - 10.100.20.254

   - **Gateway**: 10.100.20.1

 

6. **Gerência**: 10.100.21.0/24

   - **Hosts Necessários**: 50

   - **Faixa de IPs**: 10.100.21.1 - 10.100.21.254

   - **Gateway**: 10.100.21.1
  
Os demais pontos estão no arquivo .docx, descrevendo a solução do projeto.
