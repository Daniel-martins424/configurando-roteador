# Guia Completo de Configuração – TP-Link Archer C64

![imagen](https://sdmntpreastus.oaiusercontent.com/files/00000000-98a8-61f9-967e-d2b86e502fef/raw?se=2025-05-20T19%3A21%3A11Z&sp=r&sv=2024-08-04&sr=b&scid=08f03425-4d34-59e1-9445-f605cb86bb42&skoid=31bc9c1a-c7e0-460a-8671-bf4a3c419305&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-05-20T00%3A33%3A02Z&ske=2025-05-21T00%3A33%3A02Z&sks=b&skv=2024-08-04&sig=JmS%2BMD1LYVHyKavW52UFojLfCVGnmnux%2B1a54%2BmUNn8%3D)

Este guia cobre todo o processo de configuração do roteador TP-Link Archer C64 usando o site oficial de gerenciamento: [http://tplinkwifi.net](http://tplinkwifi.net).

---

## O que você vai precisar

- Um roteador TP-Link Archer C64 conectado à energia elétrica.
- Um cabo Ethernet (opcional, se for usar conexão cabeada).
- Um navegador da web (Chrome, Firefox, Edge, etc.).
- Nome de usuário e senha do seu provedor (caso a conexão seja PPPoE).

---

## 1. Conectando os cabos

1. Conecte o roteador à tomada.
2. Use o cabo Ethernet para conectar o modem à porta **WAN** (geralmente azul) do roteador.
3. Conecte seu computador ao roteador via:
   - Cabo Ethernet (porta LAN), ou
   - Wi-Fi padrão com SSID e senha impressos no adesivo do roteador.

---

## 2. Acessando a Interface Web

1. Abra um navegador e acesse:
   - `http://tplinkwifi.net`  
   - ou `http://192.168.0.1`
2. Ao abrir o painel, crie uma **nova senha de administrador**.
3. Clique em **Começar** para iniciar a configuração.

---

## 3. Assistente de Configuração Inicial

O assistente da TP-Link guiará você pelas seguintes etapas:

### 1. Fuso Horário

- Escolha o fuso horário correto (Exemplo: **GMT -03:00 Brasília**).
- Clique em **Avançar**.
![imagem](https://github.com/Daniel-martins424/configurando-roteador/blob/main/Captura%20de%20tela%202025-05-20%20153340.png?raw=true)
### 2. Tipo de Conexão de Internet

Selecione de acordo com sua operadora:

- **IP Dinâmico (DHCP)** – Mais comum em operadoras de cabo.
- **PPPoE** – Usado por operadoras de fibra/ADSL. Insira o **usuário** e **senha** fornecidos.
- **IP Estático** – Insira IP, Máscara, Gateway e DNS manualmente.

Clique em **Avançar**.
![imagen](https://github.com/Daniel-martins424/configurando-roteador/blob/main/Captura%20de%20tela%202025-05-20%20160641.png?raw=true)
### 3. Configuração Wi-Fi

Você poderá configurar as bandas 2.4GHz e 5GHz:

- **Ativar Wi-Fi:** Certifique-se de que ambas as bandas estão ativas.
- **Nome da rede (SSID):** Escolha nomes para cada banda ou unifique os nomes.
- **Senha Wi-Fi:** Crie uma senha forte (mínimo de 8 caracteres).

Clique em **Avançar**.
![imagen](https://raw.githubusercontent.com/Daniel-martins424/configurando-roteador/refs/heads/main/Captura%20de%20tela%202025-05-20%20160858.png)
### 4. Confirmação das Configurações

- Revise todas as configurações (conexão, Wi-Fi, fuso horário).
- Clique em **Salvar**.
- O roteador irá reiniciar com as novas definições.

---

## 4. Acesso ao Painel Pós-Configuração

Depois da reinicialização:

1. Conecte-se à nova rede Wi-Fi criada.
2. Acesse novamente `http://tplinkwifi.net`.
3. Faça login usando a senha de administrador criada no início.

---

## 5. Configurações Recomendadas (Avançadas)

### Alterar Senha de Administração

Menu: `Sistema > Administrador`

- Altere a senha de acesso ao painel se desejar.

### Ativar Rede de Convidados

Menu: `Rede para Convidados`

- Crie um SSID separado para visitantes.
- Defina senha própria e limite de banda, se necessário.

### Controle dos Pais

Menu: `Controle dos Pais`

- Configure regras para dispositivos específicos:
  - Restrições de tempo de uso.
  - Filtros de conteúdo.

### Qualidade de Serviço (QoS)

Menu: `QoS`

- Priorize largura de banda para atividades como:
  - Streaming.
  - Jogos online.
  - Videoconferência.

### Atualizar Firmware

Menu: `Sistema > Atualização de Firmware`

- Clique em **Verificar Atualizações Online**.
- Se houver nova versão, clique em **Atualizar Agora**.
![imagen](https://raw.githubusercontent.com/Daniel-martins424/configurando-roteador/refs/heads/main/Captura%20de%20tela%202025-05-20%20160923.png)
---
![imagen](https://raw.githubusercontent.com/Daniel-martins424/configurando-roteador/refs/heads/main/Captura%20de%20tela%202025-05-20%20160949.png)
## 6. Testando a Conexão

1. Conecte um dispositivo à rede Wi-Fi configurada.
2. Acesse um site no navegador.
3. Se carregar normalmente, a conexão está funcionando corretamente.

---

## Dicas Finais

- Salve suas senhas: Anote a senha de administração e do Wi-Fi em local seguro.
- Reinicie quando necessário: Reinicializações resolvem falhas temporárias.
- Atualize regularmente: Mantenha o firmware atualizado para segurança e desempenho.

---

## Suporte

Se precisar de ajuda adicional, acesse: [https://www.tp-link.com/br/support](https://www.tp-link.com/br/support)
