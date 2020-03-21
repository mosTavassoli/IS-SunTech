Model of Organization - To Be

# Summary of changes

The big issue of AS-IS system is that each section such as financial units, sales units, and other sections which are described before, just contact each other in a very inefficient way, like a telephone in order to do their tasks. Another problem which can cause the handling the warehousing process makes more complex is not having an integrated system to collect information from various sections. Be doing so, accessing info could be extremely straightforward for each part and definitely in the long term, it would increase customer satisfaction.

# Organizational variables
No changes
<!-- Keep this section and subsections, if there is no change just write "no change". In case there is a change detail it. -->

## Size

## Products services

## Goal, goal type, vision, mission, strategy

## Culture

## Structure

### IT office

## Formalization specialization centralization

## Organizational type

# Business model canvas

No Changes

# IS Views

## Functional view, data
<img src="https://www.mediafire.com/convkey/fe16/xgwve72lc75h7836g.jpg" alt="TO-BE"></img>

## Functional view, processes

Write no change if the model remains as in As Is

### Process selection

<!-- Report the PICK chart (see process redesign chapter) used to select the process to be changed and argument about it -->

### Process (PROCESSING THE REQUEST)

<img src="https://www.mediafire.com/convkey/df31/uoqqsu6cxivtogb6g.jpg" alt=""> <br>

<!-- For each changed process report the new BPMN (highlight where are the changes and why) and  the software functions needed by the IS, as follows -->

| Activity in BPMN | Supporting Software functions |
| --- | --- |
|  Checking the Availability   |  with integration system sales unit can access to the all list of available items in the warehouse and able to decide which departments should be take action.   |

### Process (RETURNING)
<img src="https://www.mediafire.com/convkey/1263/5rb983gpg7midjg6g.jpg" alt=""> <br>

<!-- For each changed process report the new BPMN (highlight where are the changes and why) and  the software functions needed by the IS, as follows -->

| Activity in BPMN | Supporting Software functions |
| --- | --- |
|making decision about request  |  all negotiations about request are transmitting over the system without any paper working |


## IT view

### Application portfolio

<!-- Write no change if the portfolio remains as in As Is

Otherwise list here the new portfolio, highlighting new applications, and abandoned applications. -->
There is a developed internally integrated central app with multiple functions which is providing the web interface access to all departments and providing the services that they need instead of separately using different vendor's app for each department.

#### Selection

Describe the applications considered for the selection

| Application name | Vendor | Description | Price model and fees |
| --- | --- | --- | --- |
|  Broonz-CentralApp |  Internally |  Main application with lot functionalities like automation and finance. |  hiring the developers and paying the monthly salaries |
|  Arian APP |  Arian System |  Business integrated system offered different applications and services such as ERP ,CRM ,billing, warehousing, etc. |  Suitable for all sizes company,Fees is medium |
|  Segal APP |  Segalpardaz |  Segal app is a business management software including marketing, financial, warehousing, reporting, etc. | Suitable for all sizes company,Fees is medium |
|  Odoo APP |   Odoo |  business management software including inventory,manufacturing, project management, billing, CRM, etc. |  Suitable for all sizes company,Fees is high |


Describe here how the selection of the new application was made

| Criterion | Broonz-CentralApp | Arian APP | Segal APP | Odoo |
| --- | --- | --- | --- | ---|
|  Integrity |  9 |  8 |  8 | 9|
|  Price | 10  | 8  |  7 |5|
|  Easily operated | 7  |  6 | 7  |9|
|  Support |  10 |  8 |  7 | 6|
|  Services | 10  |  7 |  7 |10|
|  Customization | 10 |  6 | 5  | 8|

BEST = 10, WORST = 0
<!-- Alternatively argue that the new application should be developed custom for the company. -->
According to the above comparison table, despite Odoo's functionalities and services, the price was too high and the support was not provided. so the decision has been made to develop the app internally inside the company.

#### Coverage

Show how the selected application provides the software functions needed (as identified in Functional view, processes section), discuss gaps, if any

| Software function needed (from process view) | Software function provided by application selected | Gap analysis |
| --- | --- | --- |
| Easy to Communicate through all departments  |  web-base application |  No |
|  Accounting | Invoice System  |  No |
| Inventory management and warehousing  |  web-base applicaiton | No  |
| Reporting and statistics |  web-base applicaiton | No  |


### Technological view

<img src="https://www.mediafire.com/convkey/7f95/ol04wdtrt1d0yfb6g.jpg" alt=""> <br>
<!-- Write no change in case. Otherwise report the new deployment diagram and highlight the changes -->

#### Integration

In case a new application is introduced discuss how integration happens in terms of:

<!-- * Data exchange (which data is exchanged)


* Control mechanism (mechanism used by applications to interact, ex message passing, rpc, etc) -->
All data and information are stored in a central database that easily transferred from local databases into central ones because the application has a web interface all departments can access it easily and communicate and exchange the information via the network.

# IT strategy

Discuss if there should be changes to it.

Now, compnay is offered a new integrated system for all it's departments by IT.

# Effect of change(s)

1-Increased customer satisfaction.
2-Great Useability and functionality
3-Reduced ERRORS and lost
4-Reduced Overhead-cost
5-Reduced the production's time and improved the quality


## Effect on KPIs and CSFs

(remark, KPIs and CSFs should not depend on the change, but should remain the ones defined in the As Is section - the goal being to compare the effect of the change on the same indicators)

Report only indicators that are supposed to change, argument on why the change has an effect on them, report how much the indicator could change. Do not forget the unit cost of the product / service.

| Indicator (Csf, Kpi) name | Effect | Quantitative estimate of variation (absolute, %) |
| --- | --- | --- |
| S-LT0	  | Could be reduced  |  30% |
|  UC-0 |  Number of employees are reduced and there is no any paper/ink cost  | 25%  |
|   S-LTR0| Could be reduced   | 45%  |
|  UCR-0 | Number of employees are reduced and there is no any paper/ink cost   |  30% |

## TCO, ROI and Break even

Define the TCO for the change (use a 3 -5 years horizon)

Estimate costs (from TCO) and savings, and discuss the number of years needed to recover the investment
| Phase  | Cost | 
| --- | --- | 
| Construction  | Define requirements for new IT application,develop or acquire it|   
|  Deployment| Deployment of new IT application, training of employees|   
| Operation |  Electricity, conditioning |   
| Maintenace  | Fix of defects, development of new or enhanced functions  |   
| Dismissal  |  Transfer data into new systems |   

TCO = C+D + 5OM ,
TCOper year = TCO/5 

| Year/Cost or saving  | YEAR1 | YEAR2 | YEAR3 | YEAR4 | YEAR5 | 
| --- | --- | --- | --- | --- | ---|
|  Cost |  C,D |   |  |  |  |
|  Cost |  O,M |  O,M | O,M | O,M | O,M |
|  Saving | S  |   |  |  |  |

## Risks

Discuss the main risks (technological, organizational, human factors) related to the change, and what can be done to reduce them

Concerning human factors, it is essential to train all of employees to use the system precisely, beside of that compatibility could be reduced with other vendor's applications. 

# Conclusion

In summary, why the organization should buy (and pay for) your proposal of change?
In conclusion, according to the lack of integrity and communication, because of using separated and different vendor's app leads to have poor performance of co-operation, services and having a lot of Errors and failures and bunch of paper works. 