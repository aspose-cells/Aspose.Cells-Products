---
title: Anotações de arquivo do Excel NET C#
description: Adicione ou remova anotações de dados de planilhas do Excel e OpenOffice com apenas algumas linhas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Remover Microsoft<sup>&reg;</sup> Anotações de arquivo do Excel via .NET" h2="Adicione ou exclua anotações de arquivos do Excel usando o código C# em aplicativos baseados em .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca Excel](/cells/pt/net/) fornece suporte para gerenciar anotações no nível da célula adicionando, acessando e removendo comentários. Usando comentários no nível da célula, as informações relevantes podem ser armazenadas para os usuários finais. Os formatos de arquivo suportados incluem ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotações de dados de arquivos do Excel" %}}
 Gerenciando comentários em planilhas - Não há limite de quantos comentários uma planilha possui no MS Excel. Pode-se adicionar tanto quanto do requisito do aplicativo. Nós usaremos o[Classe de comentário](https://reference.aspose.com/cells/net/aspose.cells/comment)para todas essas funcionalidades.

+ Carregue o arquivo do Excel usando o objeto de classe Workbook
+ Acesse a respectiva planilha e seu respectivo índice Cell
+ Chame RemoveAt com o ID Cell para removê-lo
 + Usar[Propriedade da nota](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) para adicionar conteúdo de comentários
+ Salve a pasta de trabalho antes e depois de chamar o método RemoveAt para comparar

{{% blocks/products/pf/feature-page-code h3="C# Código para Acessar, Inserir e Deletar Arquivos Excel Cell Comentários" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
