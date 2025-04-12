```markdown
# Trabalho Final de Redes de Computadores 1

Este repositório contém o trabalho final da disciplina de Redes de Computadores 1, que envolve a configuração de uma rede utilizando o Cisco Packet Tracer. O objetivo principal é configurar e interligar os equipamentos da rede de forma adequada, garantindo a comunicação entre todos os hosts e a funcionalidade dos serviços implementados.

## Objetivo do Projeto

O projeto consiste em realizar a configuração de uma rede conforme as especificações fornecidas, abordando os seguintes serviços e configurações:

### Configurações e Serviços Implementados

1. **E-mail**:
   - Configurar os serviços de E-mail no "Server 2".
   - Configurar duas contas no serviço de E-mail para que os equipamentos PC0 e PC2 possam se comunicar utilizando as contas configuradas.

2. **DNS**:
   - Configurar o serviço de DNS no "Server 1".
   - Atualizar o serviço de DHCP para direcionar ao serviço de DNS configurado.

3. **FTP**:
   - Configurar o serviço de FTP no "Server 0".
   - Garantir que todos os equipamentos da rede possam acessar o serviço de FTP.

4. **DHCP**:
   - Configurar o serviço de DHCP no "Server 0", conectado ao switch IFB1.
   - Configurar os hosts (PC0 e Laptop0) para receberem a configuração IP do servidor DHCP.

5. **HTTP**:
   - Configurar o serviço de HTTP no "Server 1" para que todos os hosts da rede possam acessá-lo via navegador.

6. **IPv4 e Roteamento**:
   - Configurar adequadamente as redes IPv4 de todas as topologias apresentadas na figura `EA2.png`, complementando a Etapa Avaliativa I.
   - Configurar o roteamento estático, quando necessário.

7. **Comunicação e Testes**:
   - Garantir que todos os hosts possam se comunicar entre si.
   - Realizar testes de comunicação para validar as configurações.

### Configuração de Equipamentos e Segurança

- Interligar os equipamentos adequadamente, conforme a imagem `EA2.png`.
- Configurar os endereços IP de todos os equipamentos, incluindo os switches (VLAN1), observando as reservas de IP identificadas na imagem.
- Configurar os hostnames dos switches de acordo com a imagem.
- Configurar senha para o console dos switches (senha: `ifb2023`).
- Configurar a senha para o modo privilegiado (senha: `ifb2023`) e criptografar as senhas no ambiente.
- Salvar as configurações no `startup-config`.

## Itens Avaliados

- Configuração adequada das sub-redes IPv4 (de forma estática).
- Configuração de roteamento estático, quando necessário.
- Testes de comunicação entre os hosts.
- Configuração e funcionamento adequado dos serviços (E-mail, DNS, FTP, HTTP e DHCP).
- Segurança e criptografia de senhas no ambiente.
- Persistência das configurações após reinicialização (`startup-config`).

## Ferramenta Utilizada

- **Cisco Packet Tracer**: Ferramenta de simulação utilizada para a configuração e teste da rede.

## Como Utilizar

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/L0rdWerther/Trabalho-final-de-redes.git
   ```

2. Abra o arquivo `.pkt` no Cisco Packet Tracer para visualizar e testar a configuração da rede.

3. Consulte a imagem `EA2.png` para entender a topologia da rede e as reservas de IP.

4. Realize os testes de comunicação entre os hosts para validar as configurações.

---

Este projeto reflete o aprendizado prático em redes de computadores, abrangendo desde a configuração básica de equipamentos até a implementação e testes de serviços essenciais.
```
