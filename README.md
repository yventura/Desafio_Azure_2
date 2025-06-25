# Monitoramento de Máquinas Virtuais no Microsoft Azure

## Descrição do Projeto
Este repositório documenta a configuração e o gerenciamento do monitoramento de máquinas virtuais (VMs) no Microsoft Azure. O objetivo é demonstrar como garantir visibilidade, controle e resposta rápida a eventos críticos, como a exclusão acidental de uma VM.

## Objetivos de Aprendizagem
- Aplicar conceitos práticos de monitoramento no Azure.
- Documentar passo a passo os processos técnicos envolvidos.
- Compartilhar conhecimento através do GitHub, facilitando estudos futuros e a implementação em ambientes reais.

## Conteúdo
1. Configuração do Azure Monitor para VMs
2. Criação e uso de alertas no Azure Monitor
3. Uso do Log Analytics para consultas e análise
4. Monitoramento e troubleshooting com Network Watcher
5. Exemplo prático de detecção e resposta a exclusão de VM
6. Dicas e melhores práticas

## Passo a Passo Resumido

### 1. Configurar Azure Monitor
- Ativar diagnósticos para máquinas virtuais
- Vincular VMs a um Log Analytics Workspace

### 2. Criar alertas
- Criar alertas baseados em métricas e logs (ex: exclusão de VM)
- Configurar grupos de ação para notificações via e-mail

### 3. Utilizar Log Analytics
- Executar queries KQL para análise de logs coletados
- Exemplo de query para detectar eventos de exclusão

### 4. Usar Network Watcher para diagnóstico de rede
- Habilitar Network Watcher na região
- Utilizar recurso IP Flow Verify para analisar tráfego

## Recursos Úteis
- [Documentação oficial - Monitoramento de VMs no Azure](https://learn.microsoft.com/azure/azure-monitor/insights/vminsights-overview)
- [Guia GitHub Markdown](https://guides.github.com/features/mastering-markdown/)

