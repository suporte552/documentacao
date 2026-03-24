
## Introdução

O **Calendário** é uma ferramenta de planejamento que permite organizar e visualizar campanhas promocionais ao longo do ano. Ele serve como base para a criação de campanhas recorrentes e padronização de períodos promocionais, funcionando como um agrupador simples para organizar campanhas e modelos de mídia.

> [!NOTE] Acesso ao Formulário
> 
> Caminho: Menu lateral esquerdo -> Campanhas -> Calendários

## Entrega de Valor

- **Planejamento Estratégico:** Visão antecipada das campanhas do ano.
- **Padronização:** Eventos recorrentes com configurações predefinidas.
- **Organização:** Evita sobreposição e conflitos de datas.
- **Eficiência:** Criação mais rápida com modelos vinculados.
- **Histórico:** Comparação facilitada com anos anteriores.
## Fluxo de Trabalho

```
graph TD
    A[Acessar Calendários] --> B[Criar Novo Calendário]
    B --> C[Definir Nome e Especificações]
    C --> D{Vincular Elementos}
    D --> E[Campanhas]
    D --> F[Modelos de Mídia]
```
## Estrutura da Configuração

### Componentes Principais

1. **Nome:** Identificação obrigatória do calendário.
2. **Especificações:** Campo de texto livre para observações.
3. **Status:** Publicado ou Rascunho (gerenciado automaticamente).
4. **Vínculo de Campanha:** Agrupador temático para cada campanha criada.
5. **Vínculo de Modelo de Mídia:** Filtro que determina quais artes aparecem em cada campanha.
    
## Processo de Configuração

### Passo 1: Criação de Calendários
1. Acesse **Campanhas -> Calendários**.
2. Clique em **Novo Calendário**.
3. Preencha as informações conforme a tabela abaixo:

| **Campo**          | **Descrição**                                                       |
| ------------------ | ------------------------------------------------------------------- |
| **Nome**           | Identificação do calendário (ex: "Páscoa 2025", "Ofertas Semanais") |
| **Especificações** | Campo de texto livre para descrição ou observações                  |

### Passo 2: Uso em Campanhas
1. Ao criar uma campanha, selecione o calendário no campo **"Calendário"**.
2. O sistema aplicará automaticamente a **Filtragem**: facilitando encontrar campanhas relacionadas e modelos de mídia compatíveis.

### Passo 3: Uso em Modelos de Mídia
Os modelos de mídia devem ser vinculados para garantir a consistência visual:
- **Lâminas, Cards e Stories:** Permitem apenas **um** calendário por modelo.
- **Cartazes:** Permitem vincular **múltiplos** calendários.

> [!TIP] Filtragem Automática
> 
> Durante a diagramação, o sistema filtra e exibe apenas os modelos que estão vinculados ao mesmo calendário da campanha ativa. Isso garante que você não use acidentalmente uma moldura de "Natal" em uma campanha de "Páscoa".

## Casos de Uso

### Organização por Eventos Sazonais
Uma rede de supermercados cria calendários como **"Black Friday 2025"** ou **"Dia das Mães 2025"**.
- **Resultado:** Modelos de mídia específicos aparecem automaticamente ao criar campanhas desses eventos, mantendo o histórico organizado por tema.

### Ofertas Semanais Recorrentes
Criação do calendário **"Ofertas Semanais 2025"** para campanhas de quinta a domingo.
- **Resultado:** Padronização visual e agilidade na busca de campanhas recorrentes.

### Organização Regional
Criação de calendários como **"Regional Sul"** ou **"Nacional"**.
- **Resultado:** Campanhas e modelos regionais ficam restritos aos seus respectivos calendários, facilitando a gestão por praça de atuação.
    
## Funcionalidades Adicionais

### Ações em Massa
Na grid de calendários, é possível utilizar o botão **Ações** para excluir registros selecionados, otimizando a limpeza de calendários antigos.

### Gestão de Modelos
- Garante que apenas modelos apropriados sejam usados.
- Mantém a consistência visual entre campanhas do mesmo tema.
    

> [!INFO] Considerações Importantes
> 
> - **O calendário não armazena datas:** Ele é apenas um agrupador. As datas de vigência são definidas dentro da Campanha.
>     
> - **Edição Segura:** Você pode editar o nome de um calendário mesmo que ele já possua campanhas vinculadas; isso não afetará os dados das campanhas.
>     
> - **Exclusão:** Se excluir um calendário, as campanhas vinculadas não são apagadas, elas apenas perdem a referência do agrupador.
>     

## Considerações Finais

A configuração correta dos calendários é o primeiro passo para uma operação de marketing eficiente e organizada, garantindo que a equipe de diagramação tenha sempre as ferramentas certas para cada tema promocional.

## Leia Também
