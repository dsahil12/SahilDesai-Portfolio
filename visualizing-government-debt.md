| [home page](https://dsahil12.github.io/SahilDesai-Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# General Government Debt Overview

It is the gross debt of the general government expressed as a percentage of GDP. Debt is calculated as the sum of the following liability categories where applicable: currency and deposits, debt securities, loans, insurance, pensions and standardized guarantee schemes, and other accounts payable. This indicator serves as a key measure of the sustainability of government finance, with changes in government debt over time primarily reflecting the impact of past government deficits.

## Part One: Working with Web-Based Visualization Tools and Data

I downloaded this image from the oecd.org site, which enabled me to manipulate and display the data in a user-friendly format. The main objective was identifying trends, patterns, and outliers within the dataset.


![General Government Debt](General government debt.png)

For this part of the assignment, we used a bar chart, a popular visualization method that uses bars to depict values across different categories, making it ideal for straightforward comparisons. Providing a clear representation of the debt levels, expressed as a percentage of GDP, for different nations. The data highlights the comparative debt burdens and allows for insights into how economic policies and fiscal management vary globally.

## Part Two: Working with Tableau

<div class='tableauPlaceholder' id='viz1726003418336' style='position: relative'>
  <noscript>
    <a href='#'>
    <img alt='Government Debt RepresentationSource: https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRepresentationHeatmap&#47;GovernmentDebtRepresentation&#47;1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='GovernmentDebtRepresentationHeatmap&#47;GovernmentDebtRepresentation' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRepresentationHeatmap&#47;GovernmentDebtRepresentation&#47;1.png' /> 
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object></div>                
  <script type='text/javascript'>                    
    var divElement = document.getElementById('viz1726003418336');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
  </script>

The heatmap displays government debt as a percentage of GDP for various countries from 1995 to 2019, using blue for lower debt and orange for higher debt. It quickly highlights trends, with Japan, Greece, and Italy showing consistently high debt (orange), while Estonia, Turkey, and the Czech Republic have lower levels (blue). This visualization effectively captures comparative debt trends across countries and over time.


## Part Three: My Own Visualization

<div class='tableauPlaceholder' id='viz1726004878609' style='position: relative'>
  <noscript>
  <a href='#'>
    <img alt='Total Government Debt RepresentationSource: https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRepresentation&#47;TotalGovernmentDebtRepresentation&#47;1_rss.png' style='border: none' />
  </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='GovernmentDebtRepresentation&#47;TotalGovernmentDebtRepresentation' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtRepresentation&#47;TotalGovernmentDebtRepresentation&#47;1.png' /> 
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726004878609');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


I chose a bubble chart to represent countries' debt as a percentage of GDP, which is a type of scatter plot that uses the size of each circle to depict debt levels, with larger circles indicating higher debt. This approach combines visual quantity (size) with qualitative insights (color gradient), offering a multi-dimensional view that helps quickly identify which countries have the highest and lowest debt levels relative to their GDP. The bubble chart also highlights clusters of countries with similar debt levels, making it well-suited for comparative financial analysis across nations.

Compared to heatmaps and bar charts, the bubble chart provides a more dynamic and engaging way to present multidimensional data, emphasizing both proportional sizes and relative values. Unlike heatmaps, which display data in a grid-like format without size dimensions, or bar charts that may not clearly depict clusters of values, the bubble chart effectively merges these elements, making it an excellent choice for visualizing complex financial data in a visually compelling and easily interpretable manner.

# Summary
The data source for this bubble chart is the OECD's general government debt indicators, which measure gross government debt as a percentage of GDP. This debt includes liabilities such as currency, deposits, securities, loans, and other accounts payable. It's a key metric for assessing the sustainability of government finances, reflecting the impact of past deficits. The indicator provides a clear comparison of debt levels across countries, highlighting financial disparities effectively.

### Reflection
Overall, the bubble chart was chosen over heatmaps and bar charts because of its ability to represent multidimensional data effectively, allowing viewers to quickly grasp the overall landscape of global debt levels.
