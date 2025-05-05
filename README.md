# gr5243-final-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [GR5243 Final Homework 3 Solved](https://www.ankitcodinghub.com/product/gr5243-final-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94724&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GR5243 Final Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<section class="page-header">
<h1 class="title toc-ignore project-name"></h1>
</section>
<section class="main-content">
<div id="building-a-reporting-engine" class="section level2">
<h2>Building a Reporting Engine</h2>
All of the previous homework assignments have asked you to perform analyses while writing a report. This time, you will build a dynamic reporting system that can display a wider range of information. Each of the questions below will include an analytical component. Then you will build a section of a reporting engine that can answer a whole class of similar questions.

The analytical questions may be written up in the usual style of a report. We will also ask you to turn in your reporting engine as an RMarkdown file.

</div>
<div id="about-the-data" class="section level2">
<h2>About The Data</h2>
We will be working with a simulated data set related to market research surveys for mobile phone products.

<strong>Main File</strong>: Homework 3 Data.csv

<strong>Delimiter</strong>: Each column of each file is separated with a comma&nbsp;<strong>,</strong>&nbsp;delimiter.

<strong>Header</strong>&nbsp;The first row of the data set includes the column names, and each subsequent row includes one observation of values. Here is a selection of 20 randomly sampled lines from the data set:

<div id="htmlwidget-ef43803a81884aa62c16" class="datatables html-widget html-widget-static-bound">
<div id="DataTables_Table_0_wrapper" class="dataTables_wrapper no-footer">
<div id="DataTables_Table_0_length" class="dataTables_length"><label>Show&nbsp;<select class="" name="DataTables_Table_0_length" aria-controls="DataTables_Table_0"><option value="10">10</option><option value="25">25</option><option value="50">50</option><option value="100">100</option></select>&nbsp;entries</label></div>
<div id="DataTables_Table_0_filter" class="dataTables_filter"><label>Search:<input class="" type="search" placeholder="" aria-controls="DataTables_Table_0"></label></div>
<table id="DataTables_Table_0" class="display dataTable no-footer" role="grid" aria-describedby="DataTables_Table_0_info">
<thead>
<tr role="row">
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="id: activate to sort column ascending">id</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Age: activate to sort column ascending">Age</th>
<th class="sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Gender: activate to sort column ascending">Gender</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Income: activate to sort column ascending">Income</th>
<th class="sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Region: activate to sort column ascending">Region</th>
<th class="sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Persona: activate to sort column ascending">Persona</th>
<th class="sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Product: activate to sort column ascending">Product</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Awareness: activate to sort column ascending">Awareness</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_User_Friendly_0_10: activate to sort column ascending">BP_User_Friendly_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Fast_0_10: activate to sort column ascending">BP_Fast_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Battery_Life_0_10: activate to sort column ascending">BP_Battery_Life_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Camera_0_10: activate to sort column ascending">BP_Camera_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Sleek_0_10: activate to sort column ascending">BP_Sleek_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Stylish_0_10: activate to sort column ascending">BP_Stylish_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Status_Symbol_0_10: activate to sort column ascending">BP_Status_Symbol_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Good_Screen_Size_0_10: activate to sort column ascending">BP_Good_Screen_Size_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Boring_0_10: activate to sort column ascending">BP_Boring_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Bulky_0_10: activate to sort column ascending">BP_Bulky_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Fragile_0_10: activate to sort column ascending">BP_Fragile_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="BP_Expensive_0_10: activate to sort column ascending">BP_Expensive_0_10</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Consideration: activate to sort column ascending">Consideration</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Consumption: activate to sort column ascending">Consumption</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Satisfaction: activate to sort column ascending">Satisfaction</th>
<th class="dt-right sorting" tabindex="0" colspan="1" rowspan="1" aria-controls="DataTables_Table_0" aria-label="Advocacy: activate to sort column ascending">Advocacy</th>
</tr>
</thead>
<tbody>
<tr class="odd" role="row">
<td class=" dt-right">6351</td>
<td class=" dt-right">20</td>
<td>Female</td>
<td class=" dt-right">20000</td>
<td>Northeast</td>
<td>Ambivalent Adventurer</td>
<td>MobilitEE</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="even" role="row">
<td class=" dt-right">7937</td>
<td class=" dt-right">71</td>
<td>Female</td>
<td class=" dt-right">62000</td>
<td>South</td>
<td>Consistent Compromiser</td>
<td>Off the Hook</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="odd" role="row">
<td class=" dt-right">412</td>
<td class=" dt-right">63</td>
<td>Male</td>
<td class=" dt-right">40000</td>
<td>Northeast</td>
<td>Ambivalent Adventurer</td>
<td>Ring Ring</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="even" role="row">
<td class=" dt-right">6090</td>
<td class=" dt-right">29</td>
<td>Female</td>
<td class=" dt-right">84000</td>
<td>West</td>
<td>Materialistic Meditator</td>
<td>Smartophonic</td>
<td class=" dt-right">1</td>
<td class=" dt-right">8</td>
<td class=" dt-right">9</td>
<td class=" dt-right">7</td>
<td class=" dt-right">9</td>
<td class=" dt-right">7</td>
<td class=" dt-right">4</td>
<td class=" dt-right">9</td>
<td class=" dt-right">6</td>
<td class=" dt-right">8</td>
<td class=" dt-right">6</td>
<td class=" dt-right">2</td>
<td class=" dt-right">5</td>
<td class=" dt-right">1</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="odd" role="row">
<td class=" dt-right">4323</td>
<td class=" dt-right">32</td>
<td>Male</td>
<td class=" dt-right">43000</td>
<td>South</td>
<td>Ambivalent Adventurer</td>
<td>Phone Zone</td>
<td class=" dt-right">1</td>
<td class=" dt-right">4</td>
<td class=" dt-right">3</td>
<td class=" dt-right">4</td>
<td class=" dt-right">2</td>
<td class=" dt-right">2</td>
<td class=" dt-right">3</td>
<td class=" dt-right">6</td>
<td class=" dt-right">2</td>
<td class=" dt-right">5</td>
<td class=" dt-right">8</td>
<td class=" dt-right">10</td>
<td class=" dt-right">8</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="even" role="row">
<td class=" dt-right">761</td>
<td class=" dt-right">37</td>
<td>Male</td>
<td class=" dt-right">85000</td>
<td>Midwest</td>
<td>Ambivalent Adventurer</td>
<td>MobilitEE</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="odd" role="row">
<td class=" dt-right">5591</td>
<td class=" dt-right">33</td>
<td>Female</td>
<td class=" dt-right">88000</td>
<td>South</td>
<td>Outdoorsy Ombudsman</td>
<td>Speed Dials</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="even" role="row">
<td class=" dt-right">4564</td>
<td class=" dt-right">65</td>
<td>Female</td>
<td class=" dt-right">30000</td>
<td>Midwest</td>
<td>Ambivalent Adventurer</td>
<td>Phone Zone</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="odd" role="row">
<td class=" dt-right">5363</td>
<td class=" dt-right">72</td>
<td>Male</td>
<td class=" dt-right">67000</td>
<td>Midwest</td>
<td>Ambivalent Adventurer</td>
<td>MobilitEE</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
<tr class="even" role="row">
<td class=" dt-right">5577</td>
<td class=" dt-right">58</td>
<td>Female</td>
<td class=" dt-right">52000</td>
<td>Northeast</td>
<td>Technological Triumphalist</td>
<td>Phone Zone</td>
<td class=" dt-right">0</td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
<td class=" dt-right"></td>
</tr>
</tbody>
</table>
<div id="DataTables_Table_0_info" class="dataTables_info" role="status" aria-live="polite">Showing 1 to 10 of 20 entries</div>
<div id="DataTables_Table_0_paginate" class="dataTables_paginate paging_simple_numbers"><a id="DataTables_Table_0_previous" class="paginate_button previous disabled" tabindex="0" aria-controls="DataTables_Table_0" data-dt-idx="0"></a>Previous<a class="paginate_button current" tabindex="0" aria-controls="DataTables_Table_0" data-dt-idx="1">1</a><a class="paginate_button " tabindex="0" aria-controls="DataTables_Table_0" data-dt-idx="2">2</a><a id="DataTables_Table_0_next" class="paginate_button next" tabindex="0" aria-controls="DataTables_Table_0" data-dt-idx="3"></a>Next</div>
</div>
</div>
Your organization’s market research team created a survey to collect information about the customer base. A large, representative sample of customers was surveyed. Each row of the data set records the information for a single respondent’s reactions about a single product. The data are organized in long, melted format. Each person in multiple rows, with one for each product. The Main File includes the following variables:

<ul>
<li><strong>id</strong>: This is a unique identifier for the respondent. The data are structured in a&nbsp;<strong>melted</strong>&nbsp;format. Each person’s responses show up in multiple rows, with 1 row for each product.</li>
<li><strong>Age</strong>: This is the subject’s age in years (rounded down) at the time of survey. For the purpose of this study, all of the respondents should be at least 18 years old. A number of questions will ask you to categorize the respondents into the following groups based on their age:</li>
<li><strong>Age Groups</strong>:
<ul>
<li>At least 18 and under 35. (Don’t include anyone who is 35.)</li>
<li>At least 35 and under 50.</li>
<li>At least 50 and under 65.</li>
<li>At least 65.</li>
</ul>
</li>
<li><strong>Gender</strong>: This identifies the respondent’s gender as Male or Female.</li>
<li><strong>Income</strong>: This is the respondent’s household income – the combined income of all members of the household – rounded to the nearest thousand dollars. A number of questions will ask you to categorize the respondents into the following groups based on their income:</li>
<li><strong>Income Group</strong>:
<ul>
<li>Under $50,000.</li>
<li>At least $50,000 and under $75,000.</li>
<li>At least $75,000 and under $100,000.</li>
<li>At least $100,000 and under $150,000.</li>
<li>At least $150,000.</li>
</ul>
</li>
<li><strong>Region</strong>: This is the geographial region within the U.S.A. in which the respondent lives.</li>
<li><strong>Persona</strong>: This is the respondent’s marketing profile category. These were created previously by the marketing organization as a method of dividing the respondents into a number of illustrative groups.</li>
<li><strong>Product</strong>: This is the name of each brand of mobile phone that was surveyed.</li>
<li><strong>Brand Perceptions</strong>: There are a number of variables about the respondent’s perceptions of the brands. Each of these variables is labeled with the form&nbsp;<strong>BP_quality_min_max</strong>. The word or phrase used in place of the quality is the perception that was surveyed. The respondents were asked to rate that perception on an integer scale from the minimum to the maximum listed values.</li>
<li><strong>Outcomes</strong>: These are the marketing states of engagement that the survey was designed to investigate. The outcomes include Awareness, Consideration, Consumption, Satisfaction, and Advocacy. Satisfaction was assessed on an integer scale from 0 to 10. All of the other outcomes are binary variables. For the purposes of this assignment, it would be reasonable to place all of the outcomes on a percentage scale from 0 to 100.</li>
</ul>
<strong>Note</strong>: A dynamic progression of the questions in the survey was utilized. Those not aware of a product were not asked about any further states of engagement. Those who were aware were asked about their perception of the brand and also their consideration. Those who had considered the product were asked about their consumption. Those who had consumed the product were asked about both their satisfaction and advocaccy. Any questions that were not asked should result in missing (NA) values for the record.

<strong>Note</strong>: The description above tells you&nbsp;<em>the intended structure</em>&nbsp;of the data set. However, it’s possible that there could be problems lurking in the records. In the course of doing this assignment, you may uncover some issues. For instance, you may find an erroneous value. In this circumstance, it will be necessary to resolve the situation. Here are some guidelines for doing so:

<ul>
<li>If the issue has an obvious solution, then you may recode the data. For instance, if you see a value of&nbsp;<strong>“True”</strong>&nbsp;for a binary variable, then you may safely assume that this value should have been coded as a 1.</li>
<li>If the issue does not have an obvious solution, then you can replace the erroneous value with&nbsp;<strong>NA</strong>&nbsp;to denote a missing value.</li>
</ul>
In either circumstance, note the problem in your solution and briefly describe the work you did to clean the data.

Then, use the data to answer the following questions and to build a reporting engine according to the specifications described.

</div>
<div id="question-1-respondent-variables" class="section level2">
<h2>Question 1: Respondent Variables</h2>
<strong>a.</strong>&nbsp;In percentage terms, how were the survey’s respondents divided into categories for the following variables? Answer separately for each variable. Round all percentages to 1 decimal place (e.g.&nbsp;84.2%).

<strong>Hint</strong>: Keep in mind that each respondent may appear multiple times in the data set.

<ul>
<li><strong>Age Group</strong></li>
<li><strong>Gender</strong></li>
<li><strong>Income Group</strong></li>
<li><strong>Region</strong>:</li>
<li><strong>Persona</strong></li>
</ul>
<strong>b.</strong>&nbsp;Now create a visual display of this information. Allow the user to select which variable to explore. Then create a graph that depicts the percentages of respondents in each category for that variable.

</div>
<div id="question-2-segmented-outcomes" class="section level2">
<h2>Question 2: Segmented Outcomes</h2>
<strong>a.</strong>&nbsp;What are the top 5 products by Awareness rates in the Northeast? Round the percentages to 1 decimal place, e.g.&nbsp;84.2%.

<strong>b.</strong>&nbsp;What are the top 5 products by Advocacy rates among females who earn at least $100,000? Round the percentages to 1 decimal place, e.g.&nbsp;84.2%.

<strong>c.</strong>&nbsp;Now create a dynamic, visual display ranking the products by their outcomes. The user will make the following selections:

State of engagement: Only a single state may be selected at once.

Other variables: Age Group, Gender, Income Group, Region, Persona

Then, for all of the other variables, any combination of categories may be selected, so long as at least one category from each variable is chosen. For instance, for Gender, the user may select Male only, Female only, or both Male and Female.

Then, the user should be able to select how many products to display. Once a number is selected, the outcome rates should be graphically displayed in sorted decreasing order for the top products in the selected subgroups. If 5 is selected for Awareness, then the 5 products with the highest rates of Awareness for the specified subgroup will be depicted. Make sure to include the percentages in the graph, each rounded to 1 decimal place (e.g.&nbsp;84.2%).

</div>
<div id="question-3-overall-brand-perceptions" class="section level2">
<h2>Question 3: Overall Brand Perceptions</h2>
<strong>a.</strong>&nbsp;What are the top 5 brands by the overall average perception?

Evaluating this question can be tricky. Some of the perceptions are for positive traits, and others are for negative traits. The brand with the best overall perception would have the highest scores for the positive traits and the lowest scores for the negative traits. To aggregate these scores, we will follow a number of steps:

<ol>
<li>For each brand, compute the average score of each brand perception variable. In computing these averages, remove any missing values from the calculations.</li>
<li>Then, for the negative perceptions, invert the scores to place them on a comparable scale with the positive traits. To do this, use the conversion formula:</li>
</ol>
Inverted Score = min possible score + max possible score – recorded score = 10 – recorded score.

The minimum and maximum possible scores here are 0 and 10. Therefore, the inverted average score is:

Inverted Average Score = 10 – Average Score.

<ol start="3">
<li>With all of the average scores of each perception now recorded on the same scale, we can aggregate them into one measure, the Overall Average Perception. For each brand, compute the mean of these variable averages. (To be clear: within a single product, you can add up the average scores for each perception and then divide by the number of perceptions.)</li>
<li>Now rank the brands in decreasing order of their Overall Average Perception scores.</li>
<li>Show the results for the top 5 brands.</li>
</ol>
<strong>b.</strong>&nbsp;Now create a dynamic, graphical display that allows the user to perform this calculation in selected subgroups. Much like the previous question, the user may make any combination of selections in the following variables, provided that at least one category of each variable is selected: Age Group, Gender, Income Group, Region, Persona.

Also allow the user to select how many brands should be displayed, with the top k brands depicted in decreasing sorted order. All results should display the overall average perception for the brand, rounded to 1 decimal place (e.g.&nbsp;6.1).

</div>
<div id="question-4-outcomes-gaps" class="section level2">
<h2>Question 4: Outcomes Gaps</h2>
The marketing department wants to identify products with engagement that is underperforming in some ways. The best products should have high rates of engagement across all of the outomes, but that is not always the case.

For the purposes of this question, we will work with the average rate of each state of engagement. To ensure a fair comparison, we will place all of the outcomes on a percentage scale from 0 to 100. For binary outcomes (awareness, consideration, consumption, and advocacy), the average will be the percentage of the respondents who answered yes to the question among those who were asked. For outcomes on an integer scale (e.g.&nbsp;Satisfaction), the average will be percentage of the maximum score. So, for instance, if the average satisfaction for a product is 7, then its percentage rating would be 70%.

<strong>a.</strong>&nbsp;Which 5 products have the largest gap between the rate of consumption and the rate of awareness? This would correspond to a formula of Difference = Rate of Consumption – Rate of Awareness. Products with higher rates of awareness than the corresponding rates of consumption will have negative differences. Display a bar graph showing the 5 largest differences in decreasing sorted order. Include the differences as percentages rounded to 1 decimal place (e.g.&nbsp;84.2%).

<strong>b.</strong>&nbsp;Which 5 products have the largest gap between the rate of awareness and the average satisfaction (in percentage terms)? Here the formula would be Difference = Rate of Awareness – Percentage Average Satisfaction. Display a bar graph showing the 5 largest differences in decreasing sorted order. Include the differences as percentages rounded to 1 decimal place (e.g.&nbsp;84.2%).

<strong>c.</strong>&nbsp;Now create a dynamic, graphical display that ranks the products in terms of the difference in averages between any two selected outcomes. The user will be allowed to make the following selections:

<strong>First Outcome</strong>: One of the outcome variables.

<strong>Second Outcome</strong>: Another outcome variable. In practice, it would be nice to exclude the outcome that was selected first. In practice, that requires some additional programming tools. So it’s OK to select the same variable twice. In that case, all of the products should necessarily show a difference of zero.

The difference in rates will be Difference = Average First Outcome – Average Second Outcome per product.

<strong>Number of Top Products</strong>: The user will select how many products to display.

<strong>Display Percentages</strong>: If checked, the bargraph will display the percentages for each product.

<strong>Digits</strong>: How many digits should the percentages be rounded to? 1 digit would be a number like 84.2%.

</div>
<div id="question-5-cross-product-measures" class="section level2">
<h2>Question 5: Cross-Product Measures</h2>
How much does a respondent’s engagement depend on the product, and how much depends on the respondent? One way we might investigate this further is to see whether the respondent’s outcomes in other products has an impact on this one. We will investigate this by the following steps:

<strong>a.</strong>&nbsp;How much impact does respondent’s overall trends in awareness have for that person’s awareness with Buzzdial phones? To answer this question, we want to create a logistic regression model. The outcome will be the respondents’ Awareness of Buzzdial. The variables in the model will include age group, gender, income group, region, persona, and the&nbsp;<strong>aggregated awareness</strong>. The aggregated awareness will be the average of the respondent’s awareness scores for all of the products&nbsp;<em>except for Buzzdial</em>. Each respondent will have a different value of aggregated awareness. Any missing scores should be removed from the calculation of the aggregated awareness. Then, fit the logistic regression model. Display a table including the model’s Odds Ratios, 95% confidence intervals for the Odds Ratios, and the p-values. In particular, show these values for the aggregated awareness variable and comment on the results. Round all of the results to 3 decimal places.

<strong>b.</strong>&nbsp;How much impact does respondent’s overall trends in satisfaction have for that person’s satisfaction with Buzzdial phones? To answer this question, we want to create a linear regression model. The outcome will be the respondents’ Satisfaction with Buzzdial. The variables in the model will include age group, gender, income group, region, persona, and the&nbsp;<strong>aggregated satisfaction</strong>. The aggregated satisfaction will be the average of the respondent’s satisfaction scores for all of the products&nbsp;<em>except for Buzzdial</em>. Each respondent will have a different value of aggregated satisfaction. Any missing scores should be removed from consideration. Then, fit the linear regression model. Display a table including the model’s coefficients, 95% confidence intervals for the coefficients, and the p-values. In particular, show these values for the aggregated satisfaction variable and comment on the results. Round all of the results to 3 decimal places.

<strong>c.</strong>&nbsp;Now we will create a dynamic model that allows the user to build a model including an aggregated outcome for a specific product. The site should include the following features:

<ul>
<li>The user can select the product.</li>
<li>The user can select the state of engagement as the outcome.</li>
<li>The user can select the other variables to include in the model. The list of choices should include the age group, gender, income group, region, persona, brand perceptions, and the Aggregated Engagement. Each person’s aggregated engagement will be calculated as the average score of the selected state of engagement across the measured values of the other products . You can give this variable a name like “Aggregated.Engagement”.</li>
</ul>
The user’s selections will then be incorporated into a model. For Satisfaction outcomes, use a linear regression. For all of the other outcomes, use a logistic regression. Then create a dynamic table showing the model’s results. For logistic regressions, this must include the Odds Ratios, 95% confidence intervals for the Odds ratios, and the p-values. For linear regressions, this must include the coeffiients, 95% confidence intervals for the coefficients, and the p-values. Other factors may be included but are not necessary. Round all of the results to 3 decimal places.

</div>
<div id="completing-the-assignment" class="section level2">
<h2>Completing the Assignment</h2>
Each of the questions include two different components:

<ul>
<li>Building a&nbsp;<strong>reporting engine</strong>&nbsp;that will display a range of information based on the user’s selections.</li>
<li>Answering&nbsp;<strong>specific questions</strong>&nbsp;based on a single set of selections to the reporting engine.</li>
</ul>
To best facilitate this work, we are asking you to generate output in two different files:

<ul>
<li>An Rmarkdown application (using shiny or flexdashboard) that can be run in real time.</li>
<li>A static report built in RMarkdown (e.g.&nbsp;an HTML file) that answers the specific questions.</li>
</ul>
Template files for each of these components will be provided. This is also a good opportunity to design your code to be reusable in both applications. Given the code that can generate the reporting engine, each of the specific questions can subsequently be answered in a single line of code (e.g.&nbsp;by calling a function of your design).

The submission will require the following files:

<ul>
<li>Reporting Engine (in RMarkdown format);</li>
<li>Source Code for the Static Report (in RMarkdown format);</li>
<li>Output of the Static Report (HTML preferred).</li>
</ul>
</div>
</section>
