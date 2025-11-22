# sql-data-warehouse-project

Welcome to the **Data Warehouse and Analytics Project** repository!
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

[Medallion_Architecture.drawio](https://github.com/user-attachments/files/23690345/Medallion_Architecture.drawio)
<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/142.0.0.0 Safari/537.36" version="29.1.0">
  <diagram name="Page-1" id="wTElO5UkD06yLwhrPjn9">
    <mxGraphModel dx="1500" dy="561" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-1" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=20;fontStyle=1" value="&lt;font&gt;High Level Architecture&lt;/font&gt;" vertex="1">
          <mxGeometry height="30" width="270" y="10" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-4" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="450" width="160" x="40" y="90" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-5" parent="1" style="rounded=0;whiteSpace=wrap;html=1;strokeColor=light-dark(#767574, #e96b12);" value="" vertex="1">
          <mxGeometry height="450" width="630" x="260" y="90" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-6" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="450" width="160" x="950" y="90" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-7" parent="1" style="rounded=0;whiteSpace=wrap;html=1;strokeColor=none;fillColor=default;fontSize=14;" value="&lt;b&gt;Sources&lt;/b&gt;" vertex="1">
          <mxGeometry height="60" width="120" x="60" y="60" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-8" parent="1" style="rounded=0;whiteSpace=wrap;html=1;strokeColor=none;fillColor=default;fontSize=14;" value="&lt;b&gt;&lt;font&gt;Data Warehouse&lt;/font&gt;&lt;/b&gt;" vertex="1">
          <mxGeometry height="60" width="250" x="450" y="60" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-9" parent="1" style="rounded=0;whiteSpace=wrap;html=1;strokeColor=none;fillColor=default;fontSize=14;" value="&lt;b&gt;Consume&lt;/b&gt;" vertex="1">
          <mxGeometry height="60" width="120" x="970" y="60" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-10" parent="1" style="image;aspect=fixed;html=1;points=[];align=center;fontSize=12;image=img/lib/azure2/general/Folder_Blank.svg;" value="" vertex="1">
          <mxGeometry height="30" width="36.96" x="101.52" y="160" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-11" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="CRM" vertex="1">
          <mxGeometry height="30" width="60" x="90" y="190" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-12" parent="1" style="image;aspect=fixed;html=1;points=[];align=center;fontSize=12;image=img/lib/azure2/general/Folder_Blank.svg;" value="" vertex="1">
          <mxGeometry height="30" width="36.96" x="101.51999999999998" y="240" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-13" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="ERP" vertex="1">
          <mxGeometry height="30" width="60" x="90" y="270" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-15" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=light-dark(#FA6800,#F16F13);fontColor=#000000;strokeColor=#FA6800;opacity=40;" value="Bronze Layer" vertex="1">
          <mxGeometry height="30" width="140" x="310" y="150" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-18" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;fontColor=#000000;strokeColor=#FA6800;opacity=40;" value="" vertex="1">
          <mxGeometry height="340" width="140" x="310" y="190" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-19" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#eeeeee;strokeColor=#36393d;opacity=40;" value="Silver Layer" vertex="1">
          <mxGeometry height="30" width="140" x="505" y="150" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-20" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;fontColor=#000000;strokeColor=light-dark(#767574, #e96b12);opacity=40;" value="" vertex="1">
          <mxGeometry height="340" width="140" x="505" y="190" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-21" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=none;opacity=40;" value="Gold Layer" vertex="1">
          <mxGeometry height="30" width="140" x="700" y="150" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-22" parent="1" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;strokeColor=#d6b656;opacity=40;" value="" vertex="1">
          <mxGeometry height="340" width="140" x="700" y="190" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-24" parent="1" style="html=1;verticalLabelPosition=bottom;align=center;labelBackgroundColor=#ffffff;verticalAlign=top;strokeWidth=2;strokeColor=#d79b00;shadow=0;dashed=0;shape=mxgraph.ios7.icons.data;fillColor=#ffe6cc;" value="" vertex="1">
          <mxGeometry height="40" width="38" x="362" y="210" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-25" parent="1" style="html=1;verticalLabelPosition=bottom;align=center;labelBackgroundColor=#ffffff;verticalAlign=top;strokeWidth=2;strokeColor=#666666;shadow=0;dashed=0;shape=mxgraph.ios7.icons.data;fillColor=#f5f5f5;fontColor=#333333;" value="" vertex="1">
          <mxGeometry height="40" width="38" x="556" y="210" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-26" parent="1" style="html=1;verticalLabelPosition=bottom;align=center;labelBackgroundColor=#ffffff;verticalAlign=top;strokeWidth=2;strokeColor=#666666;shadow=0;dashed=0;shape=mxgraph.ios7.icons.data;fillColor=light-dark(#fffaeb, #1a1a1a);fontColor=#333333;" value="" vertex="1">
          <mxGeometry height="40" width="38" x="751" y="210" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-27" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Raw Data" vertex="1">
          <mxGeometry height="30" width="60" x="351" y="260" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-28" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Cleaned, Standardized Data" vertex="1">
          <mxGeometry height="30" width="110" x="520" y="260" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-29" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Business Ready Data" vertex="1">
          <mxGeometry height="30" width="110" x="715" y="260" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-31" parent="1" style="line;strokeWidth=1;html=1;" value="" vertex="1">
          <mxGeometry height="10" width="130" x="60" y="300" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-33" parent="1" style="line;strokeWidth=1;html=1;" value="" vertex="1">
          <mxGeometry height="10" width="130" x="316" y="300" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-34" parent="1" style="line;strokeWidth=1;html=1;" value="" vertex="1">
          <mxGeometry height="10" width="130" x="510" y="300" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-35" parent="1" style="line;strokeWidth=1;html=1;" value="" vertex="1">
          <mxGeometry height="10" width="130" x="705" y="300" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-36" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="&lt;b&gt;Object Type:&amp;nbsp;&lt;/b&gt;&amp;nbsp;CSV Files&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;Interface:&lt;/b&gt; Files in Folders&lt;/div&gt;" vertex="1">
          <mxGeometry height="100" width="120" x="60" y="320" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-37" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="&lt;b&gt;Object Type:&amp;nbsp;&lt;/b&gt;&amp;nbsp;Tables&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;Load:&amp;nbsp;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;- Batch Processing&lt;/div&gt;&lt;div&gt;- Full Load&lt;/div&gt;&lt;div&gt;- Truncate &amp;amp; Insert&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;No&lt;b&gt; Transformations&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;&lt;br&gt;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;Data Model:&amp;nbsp;&lt;/b&gt;&amp;nbsp;None (as-is)&lt;/div&gt;" vertex="1">
          <mxGeometry height="160" width="120" x="321" y="310" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-38" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="&lt;b&gt;Object Type:&amp;nbsp;&lt;/b&gt;&amp;nbsp;Tables&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;Load:&amp;nbsp;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;- Batch Processing&lt;/div&gt;&lt;div&gt;- Full Load&lt;/div&gt;&lt;div&gt;- Truncate &amp;amp; Insert&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;No&lt;b&gt; Transformations:&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;&lt;br&gt;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;- Data Cleansing&lt;/div&gt;&lt;div&gt;- Data Standardization&lt;/div&gt;&lt;div&gt;- Data Normalization&lt;/div&gt;&lt;div&gt;- Derived Columns&lt;/div&gt;&lt;div&gt;- Data Enrichment&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;Data Model: None (as-is)&lt;/div&gt;" vertex="1">
          <mxGeometry height="170" width="125" x="515" y="330" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-39" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;fontSize=10;" value="&lt;b&gt;Object Type:&amp;nbsp;&lt;/b&gt;&amp;nbsp;Views&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;No&lt;b&gt; Load&amp;nbsp;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;No&lt;b&gt; Transformations:&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;&lt;br&gt;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;- Data Integrations&lt;/div&gt;&lt;div&gt;- Aggregations&lt;/div&gt;&lt;div&gt;- Business Logics&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;Data Model:&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;&lt;br&gt;&lt;/b&gt;&lt;/div&gt;&lt;div&gt;&lt;b&gt;- &lt;/b&gt;Star Schema&lt;/div&gt;&lt;div&gt;- Flat Table&lt;/div&gt;&lt;div&gt;- Aggregated Table&lt;/div&gt;" vertex="1">
          <mxGeometry height="170" width="125" x="707.5" y="320" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-40" parent="1" style="image;aspect=fixed;html=1;points=[];align=center;fontSize=12;image=img/lib/azure2/analytics/Power_BI_Embedded.svg;" value="" vertex="1">
          <mxGeometry height="60.67" width="45.5" x="1004.5" y="131" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-41" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="BI &amp;amp; Reporting" vertex="1">
          <mxGeometry height="30" width="90" x="990" y="200" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-42" parent="1" style="html=1;whiteSpace=wrap;strokeColor=none;fillColor=#0079D6;labelPosition=center;verticalLabelPosition=middle;verticalAlign=top;align=center;fontSize=12;outlineConnect=0;spacingTop=-6;fontColor=#FFFFFF;sketch=0;shape=mxgraph.sitemap.search;" value="Search" vertex="1">
          <mxGeometry height="50" width="90" x="990" y="270" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-43" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Ad-Hoc&lt;div&gt;SQL Queries&lt;/div&gt;" vertex="1">
          <mxGeometry height="30" width="90" x="990" y="330" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-44" parent="1" style="sketch=0;points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;fontColor=#232F3E;fillColor=#01A88D;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=12;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.machine_learning;" value="" vertex="1">
          <mxGeometry height="68" width="68" x="1001" y="392" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-45" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Machine Learning" vertex="1">
          <mxGeometry height="30" width="100" x="990" y="470" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-46" parent="1" style="shape=singleArrow;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" value="" vertex="1">
          <mxGeometry height="50" width="70" x="190" y="240" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-47" parent="1" style="shape=singleArrow;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" value="" vertex="1">
          <mxGeometry height="50" width="70" x="445" y="240" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-48" parent="1" style="shape=singleArrow;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" value="" vertex="1">
          <mxGeometry height="50" width="70" x="637.5" y="240" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-49" parent="1" style="shape=singleArrow;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" value="" vertex="1">
          <mxGeometry height="50" width="80" x="880" y="240" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-50" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;b&gt;&lt;font style=&quot;font-size: 17px;&quot;&gt;SQL SERVER&lt;/font&gt;&lt;/b&gt;" vertex="1">
          <mxGeometry height="39.33" width="120" x="290" y="55" as="geometry" />
        </mxCell>
        <mxCell id="bcnY3LW9IMrmuUcHhQ1t-51" parent="1" style="image;aspect=fixed;html=1;points=[];align=center;fontSize=12;image=img/lib/azure2/databases/SQL_Database.svg;" value="" vertex="1">
          <mxGeometry height="30.67" width="23" x="270" y="59.33" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
