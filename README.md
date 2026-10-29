# BR DSC Network Watcher — Canal de Distribuição e Atualização OTA

> **Repositório Público de Distribuição de Artefatos Compilados (OTA)**  
> **Infrastructure and Service Management (ISM) · DHL Supply Chain Brasil**

---

## 1. Finalidade deste Repositório

Este repositório atua exclusivamente como **Content Delivery Network (CDN) e canal de entrega Over-The-Air (OTA)** para os pacotes de execução e metadados de versão do **BR DSC Network Watcher**, ferramenta interna de monitoramento operacional de redes utilizada pela equipe de ISM da DHL Supply Chain no Brasil.

### Conteúdo Disponibilizado neste Canal
- `version.json`: Manifesto com número da versão homologada, data de liberação e notas de atualização.
- `payload.json`: Pacote estático compilado da aplicação para sincronização transparente em segundo plano.
- `BR_DSC_Network_Watcher.html`: Artefato consolidado único para execução direta no navegador corporativo.

---

## 2. Governança, Privacidade e Segurança da Informação

O canal de distribuição opera sob estrita conformidade com as políticas corporativas de Segurança da Informação:

1. **Repositório de Fontes Privado:**  
   O código-fonte modular, arquitetura de desenvolvimento, pipeline de automação, laboratório de testes (*mock*) e documentação técnica detalhada residem em repositório interno **estritamente privado**, sem visibilidade pública.
2. **Zero Dados Sensíveis ou Corporativos:**  
   Este repositório **NÃO contém e NUNCA armazena** chaves de API, tokens de acesso, credenciais, endereços IP corporativos, topologias confidenciais de clientes, contratos de operadoras ou dados de incidentes reais.
3. **Comunicação do Lado do Cliente (Client-Side Only):**  
   O Watcher é uma aplicação que executa localmente na estação de trabalho do analista. Todas as requisições de leitura de telemetria ocorrem diretamente entre o navegador do usuário e o cluster corporativo de monitoramento (PRTG), trafegando exclusivamente pela VPN/SD-WAN protegida da DHL. **Nenhuma informação da rede interna trafega pela internet.**
4. **Integridade de Execução:**  
   Os artefatos distribuídos neste canal são gerados automaticamente através de pipeline auditado de compilação, garantindo integridade de código e proteção contra adulterações acidentais.

---

## 3. Direitos de Propriedade e Uso

- **Titularidade:** Software de propriedade corporativa exclusiva da **DHL Supply Chain Brasil** (Deutsche Post DHL Group).
- **Uso Restrito:** Ferramenta destinada exclusivamente para uso funcional e operacional de analistas e engenheiros devidamente autorizados de Infrastructure and Service Management (ISM).
- **Vedação Externa:** É vedada a redistribuição, engenharia reversa, comercialização ou uso não autorizado fora do perímetro corporativo da DHL.

---
*Canal mantido pela equipe de **Infrastructure Service Management (ISM)** · DHL Supply Chain Brasil.*
