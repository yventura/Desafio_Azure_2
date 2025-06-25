# Monitoramento de Máquinas Virtuais no Azure

## Sobre este projeto
Este repositório reúne todo o processo de configuração e gerenciamento do monitoramento de máquinas virtuais no Microsoft Azure. A ideia é mostrar como garantir que possamos acompanhar o funcionamento das VMs, detectar problemas rapidamente e reagir, como no caso de uma exclusão inesperada.

## O que você vai aprender aqui
- Como colocar em prática o monitoramento no Azure para VMs.
- Documentar cada etapa técnica de forma clara e objetiva.
- Usar o GitHub para organizar e compartilhar esse conhecimento.

## Conteúdos abordados
1. Configuração básica do Azure Monitor para VMs
2. Criação de alertas para eventos importantes
3. Consultas usando Log Analytics para analisar dados coletados
4. Diagnóstico de rede com Network Watcher
5. Cenário prático: identificar e agir sobre exclusão de VM
6. Recomendações e boas práticas

## Guia rápido

### 1. Ativando o Azure Monitor
- Configurar diagnósticos nas máquinas virtuais
- Associar as VMs a um workspace do Log Analytics

### 2. Configurando alertas
- Criar alertas com base em métricas e logs (por exemplo, para exclusão de VM)
- Definir grupos de ação para notificação automática

### 3. Explorando o Log Analytics
- Criar e executar queries Kusto (KQL) para monitoramento
- Exemplo de consulta para capturar eventos de exclusão

### 4. Usando Network Watcher para análise
- Habilitar o recurso na região correspondente
- Utilizar ferramentas como IP Flow Verify para diagnosticar tráfego

## Materiais de referência
- [Documentação oficial do Azure Monitor para VMs](https://learn.microsoft.com/azure/azure-monitor/insights/vminsights-overview)
- [Guia de Markdown para GitHub](https://guides.github.com/features/mastering-markdown/)
