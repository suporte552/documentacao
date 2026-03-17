# Campanhas
## Visão Geral

A **Gestão de Campanhas** é onde você cria e acompanha todas as suas ações promocionais, desde o planejamento até a execução nas lojas.

## Benefícios

- **Controle Centralizado**: Todas as informações da campanha em um único lugar
- **Fluxo Estruturado**: Processo organizado em etapas com responsáveis definidos
- **Flexibilidade**: Adaptação às necessidades específicas de cada cliente
- **Visibilidade**: Acompanhamento em tempo real do status e prazos
- **Rastreabilidade**: Histórico completo de ações e aprovações

## Funcionalidades Principais

### 1. Criação de Campanhas
![Identificação](images/Pasted%20image%2020260317123555.png)
O processo de criação de campanhas é dividido em três etapas principais através de um assistente intuitivo:
#### **Etapa 1: Identificação**

Definição das informações básicas da campanha:
- **Nome da Campanha**: Identificação única
- **Lojas Participantes**: Seleção de unidades (múltipla escolha)
- **Calendário**: Vinculação com calendário promocional
- **Motivo da Campanha**:
    - Calendário promocional
    - Produto avariado
    - Produto próximo ao vencimento
    - Excesso de estoque
    - Proteção de território
- **Margem**: Margem de lucro esperada (%)
- **Datas de Vigência**:
    - Data de início da oferta
    - Data final da vigência
- **Canal de Venda**: Loja física, e-Commerce ou ambos
- **Status**: Rascunho, Em andamento, Concluído, Arquivado

#### **Etapa 2: Prazos e Etapas**

Configuração do fluxo de trabalho com 7 etapas possíveis (configuráveis por cliente):

1. **Preenchimento Comercial**: Cadastro inicial de produtos
2. **Aprovação Comercial**: Validação pelo gestor comercial
3. **Aprovação de Pricing**: Validação de preços e margens
4. **Diagramação Marketing**: Criação de mídias visuais
5. **Aprovação Marketing**: Validação das mídias criadas
6. **Integrações**: Envio de dados para sistemas externos
7. **Execução Loja**: Período de vigência da campanha

Para cada etapa ativa, define-se:

- **Data de Início** (opcional, configurável)
- **Data de Fim** (opcional, configurável)
- **Responsável**: Usuário com o perfil apropriado

> **Nota**: O controle de datas pode ser ativado ou desativado conforme configuração da sua empresa.

#### **Etapa 3: Layout e Páginas**

Estruturação das páginas de materiais da campanha:

- **Páginas de Materiais**: Criação de múltiplas páginas
    
    - Nome ou título da página
    - Número de produtos esperados
    - Tipo: Capa ou Interna
- **Distribuição de Produtos**: Atribuição de responsáveis
    
    - Seleção de compradores
    - Quantidade de produtos por comprador

### 2. Acompanhamento de Campanhas

#### **Listagem de Campanhas**

A tela de listagem apresenta:

- **Ordenação Inteligente**: Campanhas com início mais próximo aparecem primeiro
- **Dias Restantes**: Contador automático para a etapa atual
- **Filtros por Loja**: Usuários veem apenas campanhas de suas lojas
- **Campanhas de Rede**: Campanhas marcadas como "rede" são visíveis para todos

#### **Indicadores Visuais**

- Status da campanha (etiquetas coloridas)
- Progresso da etapa atual
- Alertas de prazos próximos ou vencidos
- Quantidade de produtos cadastrados vs. esperados

### 3. Gestão de Produtos na Campanha

Através da aba "Gerenciar Produtos":

- Adição de produtos ao mix promocional
- Definição de preços especiais
- Configuração de posicionamento nas páginas
- Aprovação individual de produtos
- Geração de materiais específicos

### 4. Navegação por Etapas

Acesso direto às telas específicas de cada etapa:

- **Gerenciar Produtos**: Gestão do mix de produtos
- **Aprovação Comercial**: Validação de produtos e preços
- **Aprovação Pricing**: Análise de margens e rentabilidade
- **Diagramação**: Acesso aos editores visuais
- **Aprovação Marketing**: Validação de materiais visuais
- **Baixar Materiais**: Download de materiais finalizados
- **Integrações**: Análise e envio para sistemas externos (ex: Sysmo)

## Conceitos-Chave

### **Campanha**

Evento promocional com período definido, mix de produtos e materiais de divulgação associados.

### **Etapa Atual**

Fase do processo de aprovação em que a campanha se encontra. Define quem pode atuar e quais ações estão disponíveis.

### **Calendário Promocional**

Planejamento anual de campanhas com datas pré-definidas (Natal, Dia das Mães, Black Friday, etc.).

### **Página de Campanha**

Agrupamento lógico de produtos que serão organizados juntos em um material promocional.

### **Canal de Venda**

Meio onde a campanha será executada (loja física, e-commerce ou ambos).

## Casos de Uso

### Caso 1: Campanha de Black Friday

1. Marketing cria campanha "Black Friday 2025"
2. Vincula ao calendário promocional
3. Define 10 lojas participantes
4. Configura 7 etapas com datas e responsáveis
5. Cria 5 páginas de materiais (1 capa + 4 internas)
6. Distribui: 20 produtos por comprador (3 compradores)
7. Compradores cadastram produtos até a data limite
8. Gestor comercial aprova os produtos
9. Pricing valida margens
10. Marketing cria materiais visuais
11. Gestor de marketing aprova materiais
12. Sistema envia dados para outros sistemas
13. Campanha entra em execução nas lojas

### Caso 2: Campanha Emergencial - Excesso de Estoque

1. Comprador identifica excesso de estoque
2. Cria campanha com motivo "Excesso de estoque"
3. Define vigência curta (1 semana)
4. Desativa controle de datas (aprovação rápida)
5. Adiciona apenas produtos específicos
6. Fluxo simplificado com menos etapas
7. Execução imediata após aprovação comercial

### Caso 3: Campanha Multi-Canal

1. Campanha planejada para lojas físicas e e-commerce
2. Produtos específicos por canal
3. Materiais diferentes: cartazes para loja, banners para site
4. Integração automática com plataforma de e-commerce
5. Acompanhamento de performance por canal

## Permissões Necessárias

### Criar Campanhas

- Perfil necessário: Gestor Comercial de Campanhas ou superior
- Permite: Criar novas campanhas

### Editar Campanhas

- Perfil necessário: Gestor Comercial de Campanhas ou superior
- Permite: Editar campanhas ativas (campanhas arquivadas não podem ser editadas)

### Visualizar Campanhas

- Perfil necessário: Qualquer usuário com acesso ao sistema
- Você verá apenas campanhas das suas lojas

### Avançar Etapas

- Apenas o responsável pela etapa pode avançar
- Cada etapa tem suas próprias permissões

## Integrações

### Com Outros Módulos

- **Produtos**: Busca de produtos do catálogo para adicionar na campanha
- **Lojas**: Filtro e segmentação por unidade
- **Usuários**: Atribuição de responsáveis por etapa
- **Calendário**: Planejamento e modelos de campanha
- **Materiais**: Geração automática de peças promocionais
- **Integrações**: Envio para sistemas externos (Sysmo, etc.)

### Com Sistemas Externos

- **Sistema de Gestão (ERP)**: Busca de produtos e custos
- **Sistema de Caixa (PDV)**: Envio de preços promocionais
- **E-commerce**: Sincronização de ofertas
- **Relatórios**: Exportação de dados para análise

## Dicas e Melhores Práticas

### Planejamento

✅ **Recomendado:**

- Crie campanhas com pelo menos 30 dias de antecedência
- Use calendários promocionais para campanhas recorrentes
- Defina responsáveis antes de iniciar o processo
- Configure alertas de prazo para etapas críticas

❌ **Evite:**

- Campanhas sem datas definidas em períodos de alta demanda
- Mudar responsáveis após início da etapa
- Criar muitas páginas sem necessidade

### Organização

✅ **Recomendado:**

- Use nomes padronizados (ex: "BF2025_Loja01")
- Agrupe produtos similares na mesma página
- Documente o motivo da campanha
- Mantenha histórico de campanhas passadas (não exclua)

❌ **Evite:**

- Nomes genéricos ("Campanha 1", "Teste")
- Misturar categorias muito diferentes na mesma página
- Arquivar campanhas que ainda servem de referência

### Aprovações

✅ **Recomendado:**

- Revisar todos os produtos antes de aprovar
- Verificar margens e preços
- Testar materiais visuais em diferentes dispositivos
- Documentar motivos de reprovação

❌ **Evite:**

- Aprovar em lote sem revisar
- Pular etapas do processo
- Avançar etapa com pendências

### Performance

✅ **Recomendado:**

- Limite campanhas grandes a 200-300 produtos
- Divida campanhas muito grandes em múltiplas menores
- Use filtros na listagem de produtos
- Arquive campanhas antigas periodicamente

❌ **Evite:**

- Campanhas com milhares de produtos
- Manter todas as campanhas sempre ativas
- Duplicar campanhas sem necessidade

## Fluxo de Trabalho Recomendado

```
1. PLANEJAMENTO (Marketing/Comercial)
   ↓
2. CRIAÇÃO DA CAMPANHA (Gestor Comercial)
   ↓
3. CADASTRO DE PRODUTOS (Compradores)
   ↓
4. APROVAÇÃO COMERCIAL (Gestor Comercial)
   ↓
5. APROVAÇÃO PRICING (Gestor de Pricing)
   ↓
6. CRIAÇÃO DE MATERIAIS (Designer/Marketing)
   ↓
7. APROVAÇÃO MARKETING (Gestor de Marketing)
   ↓
8. INTEGRAÇÕES (Sistema/TI)
   ↓
9. EXECUÇÃO EM LOJA (Operacional)
   ↓
10. ANÁLISE DE RESULTADOS (BI/Comercial)
```

## Perguntas Frequentes

**P: Posso editar uma campanha após iniciada?**  
R: Sim, mas apenas campos não críticos. Mudanças em produtos, preços e datas podem requerer nova aprovação.

**P: Como funciona o controle de datas?**  
R: Cada empresa pode ativar ou desativar. Quando ativo, cada etapa tem início e fim definidos. Quando inativo, o processo é baseado apenas em aprovações.

**P: Posso pular etapas?**  
R: Não diretamente. O sistema respeita o processo configurado. Se uma etapa não é necessária, ela deve ser desabilitada na configuração da sua empresa.

**P: Quantas lojas posso incluir em uma campanha?**  
R: Não há limite técnico, mas recomendamos avaliar se campanhas para muitas lojas não deveriam ser divididas por região ou grupo.

**P: O que acontece se perder um prazo?**  
R: O sistema exibe alertas visuais, mas não bloqueia ações. O responsável pode prosseguir, mas a informação fica registrada no histórico.

## Veja Também