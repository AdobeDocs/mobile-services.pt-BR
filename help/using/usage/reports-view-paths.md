---
description: O relatório Caminhos de exibição, que se baseia na análise de caminhos, mostra um gráfico que representa os caminhos que foram tomados entre estados no aplicativo.
keywords: dispositivos móveis
solution: Experience Cloud Services,Analytics
title: Exibir relatório Caminhos
topic-fix: Reports,Metrics
uuid: bc73edce-0cc0-4349-9a48-e0a40cbe1b67
exl-id: 475dbe01-fa4d-433c-ac77-68f2a6972c0c
source-git-commit: 7cfaa5f6d1318151e87698a45eb6006f7850aad4
workflow-type: tm+mt
source-wordcount: '494'
ht-degree: 100%

---

# Exibir relatório Caminhos {#view-paths}

{#eol}

O relatório **[!UICONTROL Caminhos de exibição]**, que se baseia na análise de caminhos, mostra um gráfico que representa os caminhos que foram tomados entre estados no aplicativo.

>[!TIP]
>
>Os relatórios **[!UICONTROL Caminhos de exibição]** e **[!UICONTROL Ação de exibição]** são semelhantes porque ambos são relatórios de definição de caminho. O relatório **[!UICONTROL Caminhos de exibição]** permite ver como os usuários navegam no seu aplicativo de uma tela para outra. O relatório **[!UICONTROL Ações de exibição]** exibe a sequência de ações (eventos, como cliques, seleções, redimensionamento, etc.) que os usuários executam no aplicativo. Você pode usar um relatório de funil para combinar navegação e ações em um relatório. Para obter mais informações, consulte [Funil](/help/using/usage/reports-funnel.md).

![caminhos de visualização](assets/view_paths.png)

Cada nó, formado como uma caixa, representa um estado nos caminhos dos usuários em um aplicativo. Por exemplo, na ilustração acima, o nó superior representa o número de usuários que inicializaram o aplicativo e navegaram até a visualização principal.

Quando você clica em um nó para fornecer as opções adicionais para modificar o gráfico, opções adicionais como **[!UICONTROL Focar]** ou **[!UICONTROL Expandir]** são exibidas. Por exemplo, se você clicar no estado **[!UICONTROL MainView]** no nó superior, os ícones **[!UICONTROL Focar]** e **[!UICONTROL Expandir]** serão exibidos.

Para expandir a exibição, clique no ícone **[!UICONTROL +]** para exibir os caminhos adicionais que entram ou saem do nó. Na ilustração abaixo, o estado 1 é a inicialização do aplicativo, o estado 2 é a exibição da página principal do aplicativo e o estado 3 inclui os seguintes caminhos que os usuários tomaram:

* Navegar até o rolo da câmera
* navegar até o seletor de itens
* navegar até a câmera
* navegar até a página de informações do item

![](assets/view_paths_expand.png)

Clique em ![focus icon](assets/icon_focus.png) para isolar o nó e mostrar os caminhos que entram e saem do nó selecionado. Na ilustração abaixo, os seguintes caminhos precederam os usuários que estavam vendo a visualização principal do aplicativo:

* informações do item
* seletor de itens
* Rolo da câmera
* Câmera

![visualizar foco do caminho](assets/view_paths_focus.png)

Você pode focar ou expandir vários nós para obter uma visualização detalhada dos caminhos que os usuários tomam em seu aplicativo. Por exemplo:

![caminho de visualização múltiplo](assets/view_paths_mult.png)

Você pode configurar as seguintes opções no relatório:

* **[!UICONTROL Período]**
Clique no ícone **[!UICONTROL Calendário]** para selecionar um período personalizado ou um período atual na lista suspensa.
* **[!UICONTROL Personalizar]**
Para personalizar seus relatórios, altere as opções **[!UICONTROL Mostrar por]**, adicionando métricas e filtros, séries (métricas) extras e muito mais. Para obter mais informações, consulte [Personalizar relatórios](/help/using/usage/reports-customize/reports-customize.md).
* **[!UICONTROL Filtro]**
Clique em **[!UICONTROL Filtro]** para criar um filtro que abrange vários relatórios e observar o desempenho de um segmento específico em todos os relatórios móveis. Um filtro fixo permite definir um filtro aplicado a todos os relatórios não relacionados à definição de caminho. Para obter mais informações, consulte [Adicionar filtro fixo](/help/using/usage/reports-customize/t-sticky-filter.md).
* **[!UICONTROL Download]**
Clique em **[!UICONTROL PDF]** ou **[!UICONTROL CSV]** para baixar ou abrir documentos e compartilhá-los com usuários que não têm acesso ao Mobile Services ou para usá-los em apresentações.
