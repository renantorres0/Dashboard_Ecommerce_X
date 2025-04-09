# Dashboard de Performance eCommerce X - Power BI

Dashboard interativo desenvolvido no Power BI para monitoramento estratégico de campanhas de marketing, proporcionando insights acionáveis para o alcance das metas trimestrais.

## 📌 Visão Geral

Este projeto consiste em um painel analítico completo que:
- Monitora KPIs-chave de desempenho de campanhas
- Identifica tendências e padrões de compra
- Segmenta audiência por múltiplos critérios demográficos
- Fornece visualizações intuitivas para tomada de decisão ágil

## 🛠️ Ferramentas Utilizadas
- **Power BI** (Desktop e Service) - Desenvolvimento do dashboard e publicações
- **Excel** - ETL inicial e preparação dos dados
- **DAX** - Criação de métricas avançadas e cálculos personalizados

## 📊 Estrutura dos Dados

### Fontes de Dados
Arquivos Excel contendo dados históricos de campanhas com a seguinte estrutura:

| Nome da Coluna | Tipo de Dado | Descrição | Exemplo |
|----------------|--------------|-----------|---------|
| Data do período analisado | Date | Data de referência dos indicadores | 2023-01-15 |
| Receita total | Decimal | Valor bruto gerado no período | 15200.50 |
| Soma da Receita média por compra | Decimal | Ticket médio agregado | 320.75 |
| Total de compradores | Integer | Número único de clientes | 215 |
| Visualizações | Integer | Pageviews/impressões | 10500 |
| Compradores por dia | Integer | Conversões diárias | 48 |
| Compradores por origem | String | Canal de aquisição (Google, Facebook, etc) | "Organic Search" |
| Usuários totais por plataforma | String | Dispositivo de acesso (Mobile/Desktop) | "Mobile" |
| Usuários totais por cidade | String | Localização geográfica | "São Paulo" |
| Usuários ativos por gênero | String | Segmentação demográfica | "Feminino" |

## 🖥️ Visualizações do Dashboard

### Seções Principais
1. **Visão Geral de Performance**
   - Gráfico de tendência de receita vs visualizações
   - Indicadores-chave em cards (CVR, ROAS, CAC)
   - Mapa de calor geográfico

2. **Análise de Audiência**
   - Pirâmide etária e distribuição por gênero
   - Dispositivos preferenciais
   - Top 10 cidades com maior engajamento

3. **Eficiência de Canais**
   - Comparativo de conversão por origem
   - ROI por campanha
   - Funil de conversão multicanal

![Preview do Dashboard](https://github.com/user-attachments/assets/194486a1-dc08-47ab-8136-dda356261fc8)
*Visão consolidada dos principais KPIs*

![Análise de Compradores](https://github.com/user-attachments/assets/478b7f9f-8528-446c-82e1-7e590da6140a)
*Segmentação de compradores por características demográficas*

## 🔍 Métricas Calculadas
- **Taxa de Conversão**: `(Total de Compradores / Visualizações) * 100`
- **ROAS (Return on Ad Spend)**: `(Receita Total / Investimento em Campanha)`
- **LTV (Lifetime Value)**: `(Receita Média por Compra × Frequência de Compra) × Tempo de Retenção`
- **CAC (Custo de Aquisição por Cliente)**: `(Investimento Total / Número de Novos Clientes)`

## 🚀 Como Utilizar
1. **Atualização de Dados**:
   - Substituir o arquivo fonte na pasta designada
   - Atualizar conexão no Power BI Desktop
   - Publicar nova versão no Power BI Service

2. **Filtros Interativos**:
   - Seletor de período temporal
   - Filtros por região/cidade
   - Segmentação por canal de aquisição

3. **Exportação de Relatórios**:
   - Clique em "Exportar" para gerar PDFs segmentados
   - Agende entregas automáticas para stakeholders

## 📅 Roadmap de Melhorias
- [ ] Integração direta com Google Analytics/Ads
- [ ] Modelo preditivo de conversão
- [ ] Alertas automáticos para anomalias
- [ ] Painel de benchmark setorial

## 🤝 Contribuição
Contribuições são bem-vindas! Siga o processo:
1. Faça um fork do projeto
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova métrica XYZ'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## ✉️ Contato
Renan Torres - nantorres0@gmail.com
