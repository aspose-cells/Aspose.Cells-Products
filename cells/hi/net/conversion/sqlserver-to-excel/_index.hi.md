---
title: C# एसक्यूएल सर्वर से एक्सेल - एसक्यूएल सर्वर से एक्सेल कनवर्टर
description: Aspose एक्सेल। Aspose.Cells के साथ SqlServer को EXCEL में जल्दी और आसानी से बदलें। C# SqlServer को EXCEL में बदलें। C# एसक्यूएलसर्वर को एक्सेल में सहेजें। C# का उपयोग करके SqlServer को EXCEL के रूप में सहेजें।
keywords: [Aspose Excel., C# Aspose.Cells., Convert SqlServer to EXCEL in C#., Save SqlServer to EXCEL using C#., C# SqlServer to EXCEL saveformat., SqlServer to EXCEL Converter., C# Save SqlServer as EXCEL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# में SqlServer को EXCEL में बदलें" h2="SqlServer को EXCEL में परिवर्तित करने के लिए हाई-स्पीड C# लाइब्रेरी। यह .NET फ्रेमवर्क, .NET कोर या Mono प्लेटफॉर्म पर EXCEL, SqlServer और कई अन्य प्रारूपों को आयात और निर्यात करने के लिए एक पेशेवर सॉफ्टवेयर समाधान है।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SqlServer" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके SqlServer को EXCEL में बदलें" %}}
 मैं SqlServer को EXCEL में कैसे परिवर्तित करूं? Aspose.Cells for .NET लाइब्रेरी के साथ, आप कोड की कुछ पंक्तियों के साथ आसानी से SqlServer को EXCEL में प्रोग्रामेटिक रूप से परिवर्तित कर सकते हैं।[Aspose.Cells for .NET](https://products.aspose.com/cells/net)सभी एक्सेल फ़ाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन बनाने में सक्षम है। .NET एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित होता है, बल्कि यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प बन जाता है। खुला[NuGet](https://www.nuget.org/packages/aspose.cells) पैकेज मैनेजर, Aspose.Cells खोजें और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="C# के माध्यम से SqlServer को EXCEL में कैसे परिवर्तित करें" %}}

{{% blocks/products/pf/agp/text %}}

SqlServer डेटा को प्रोग्रामेटिक रूप से EXCEL में कनवर्ट करने की आवश्यकता है? .NET डेवलपर्स कोड की कुछ पंक्तियों में आसानी से SqlServer को EXCEL में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1.  'Aspose.Cells for .NET' इंस्टॉल करें।
1.  अपने C# प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।
1.  डेटाटेबल ऑब्जेक्ट प्राप्त करने के लिए SqlServer डेटाबेस से डेटा क्वेरी करें।
1.  एक नई कार्यपुस्तिका बनाएं और डेटाटेबल ऑब्जेक्ट से डेटा आयात करें।
1. Workbook.Save विधि को कॉल करके डेटा को xlsx प्रारूप में सहेजें।

{{% blocks/products/pf/agp/code-block title="SqlServer को EXCEL में बदलने के लिए नमूना कोड - C#" offSpacer="" %}}

```cs
var connectionString = "Server=localhost;Database=SqlServerTestDataBase;User ID=root;Password=admin;Trusted_Connection=False;";
var tableName = "countrylanguage";

string query = $"SELECT * FROM {tableName}";

using (SqlConnection connection = new SqlConnection(connectionString))
{
    connection.Open();
    SqlCommand cmd = new SqlCommand(query, connection);
    SqlDataAdapter adapter = new SqlDataAdapter(cmd);

    DataTable dataTable = new DataTable();
    adapter.Fill(dataTable);

    Workbook workbook = new Workbook();
    Worksheet worksheet = workbook.Worksheets[0];
    worksheet.Cells.ImportData(dataTable, 0, 0, new ImportTableOptions() { InsertRows = true });
    workbook.Save("SQLServerData.xlsx");
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="SqlServer को EXCEL में बदलने के लिए C# लाइब्रेरी" %}}

{{% blocks/products/pf/agp/text %}}

आपके सिस्टम पर "Aspose.Cells for .NET" इंस्टॉल करने के लिए दो वैकल्पिक विकल्प हैं। कृपया वह चुनें जो आपकी आवश्यकताओं से मेल खाता हो और चरण-दर-चरण निर्देशों का पालन करें:

{{% /blocks/products/pf/agp/text %}}

1.  ए स्थापित करें[NuGet पैकेज](https://www.nuget.org/packages/Aspose.Cells/) . देखना[प्रलेखन](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  का उपयोग करके लाइब्रेरी स्थापित करें[पैकेज मैनेजर कंसोल](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) विजुअल स्टूडियो आईडीई के भीतर

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण उदाहरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या .NET, .NET कोर, Windows एज़्योर या Mono प्लेटफ़ॉर्म के साथ संगत ओएस...
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण।
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
