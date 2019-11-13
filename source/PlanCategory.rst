Plan Category
=============

The Plan Category has an Input Editor screen through which the user can create multiple series. 
By clicking the Plan Tab, you will be able to view the Input Editor screen as shown below. 

.. figure:: _static/pll1.png  
    :align: center
    :alt: alternate text

    Input Editor

The series which are created using the Input Editor are the Planning Series. 
The created planning series will get listed as drop down values in the top most panel (see Figure below).

.. figure:: _static/pll2.png  
    :align: center
    :alt: alternate text

    Data Series Display

After selecting the required series for both the Primary and Comparison Series, the Tree will get displayed 
based on the selection (see Figure below). For our example, the Primary Series has been selected as “Budget” 
and the Comparison Series has been selected as “Forecast”. 

.. figure:: _static/pll3.png  
    :align: center
    :alt: alternate text

    Tree Structure for the selected Primary and Comparison Series

Input Editor Functionality
--------------------------

For our example, the below Figure represents the sample Data Source being assigned for the Planning Series.

.. figure:: _static/pl4.png
    :align: center
    :alt: alternate text  

    Sample Data Source

With the help of the above shown Data Source, you will be able to create a New series using the Input Editor.  
The below steps explains us on how to create a Series in the Input Editor.

1.	By clicking the Plan Category, you will be able to view the Input Editor screen. Now you will be able to view the New Series screen as shown below.

.. figure:: _static/pl5.png
    :align: center
    :width: 400
    :alt: alternate text  

    New Series window 

2.	For our example, lock the Tree Structure as shown in the above Figure. This would lock the node structure and to add the new nodes you need to unlock the structure. You need to lock the structure in order to enable the top down adjustments to the rules applied at parent nodes. 
3.	Now enter the name for the New series. In our example, it is being named as “Aug Fcst” (as it represents the August Forecast) and it is user defined. Select the Base Series and Budget will be the Primary in our case (see Figure below).

.. figure:: _static/pl6.png
    :align: center
    :width: 400
    :alt: alternate text 

    Series Name with Base Series Selection

The Primary Series is the Main Data that will get displayed on the node. The Comparison Series will be the Variance data that will get displayed on the node  and it is be compared to this series.

New Series can be also created from Empty Series : Zero based budgeting and also based on Primary or Comparison series.

4.	At the top of the panel, you will be able to view the Tabs which would highlight the names of the series (see Figure below).

.. figure:: _static/pl7.png
    :align: center
    :alt: alternate text 
 
    Series Name at the Top Panel

You can also click on the New Series as shown in the above Figure and create a new series. This can be created on existing series, empty series or the newly created series. 

It is to be noted that the Series created using the Input Editor screen will be also listed in the Variance Analysis screen as drop down fields for Base Series and Compared Series. 

In the settings section, you can set the newly created series as primary or the comparative series. We can also rename or delete the series as shown in the below Figure.  

.. figure:: _static/pl8.png
    :align: center 
    :width: 200
    :alt: alternate text 

    Series Settings 

5.	There are three different methods of Planning and they are listed below (see Figure below).

•	Weight
•	Equals
•	Trend

.. figure:: _static/pl9.png
    :align: center
    :alt: alternate text 

    Planning Methods

Once when the values are allocated for the periods we have the option to allocate the values across the period to different nodes. Here the planning can happen based on Weight or Equal. 

6.	The Planning Methods that are available at Year Level are “Weight” and “Equals” (see Figure below). Based on the user selection of the cell, the Planning Methods will get activated.

.. figure:: _static/pl10.png 
    :align: center
    :width: 400
    :alt: alternate text 
    
    User defined cell and planning methods

**Note:**
The Number format and scaling will be taken from the tree. The Number bar will have the absolute value irrespective of the format and scaling.

7.	For our example, there are different scenarios for illustrating the Planning Methods and they are explained below:
 
Scenario 1
~~~~~~~~~~

Increase the total revenue by 10%, other revenue remains same and move the Impact to sales revenue.

a.	For our example, expand the Total Revenue. Now select the node “Other Revenue” and lock the node (see Figure below).

.. figure:: _static/pl11.png
    :align: center
    :alt: alternate text  

    Scenario 1

b.	Now select the Total Cell for node “Total Revenue” as shown in the below Figure.

.. figure:: _static/pl12.png
    :align: center
    :width: 400
    :alt: alternate text  

    Cell Selection

You can also update the number by double clicking the cell, enter the number directly in the number bar or enter the number in the Pop up.

c.	Now double click the total cell and type “+10%” at the end of the number and Click on “Weight” as shown in the below Figure.

.. figure:: _static/pl13.png
    :align: center
    :width: 400
    :alt: alternate text  

    Total cell value increased to 10 %

d.	Click on Weight option as shown in the above Figure and you will be able to view the Spread by Weights 

.. figure:: _static/pl14.png
    :align: center
    :width: 400
    :alt: alternate text 
 
    Spread by Weights

Now select the current node and the current series and select the “Overwrite Values” option. You can also select different weights to allocate. You can further decide to allocate the full amount or the delta amount (see Figure above).

The Overwrite Values option will delete the existing number and re writes the new allocated value and the Append option will add the delta value to the existing value and only the delta value gets allocated in the selected weights (see Figure above). 
For our example, the Overwrite option has been selected.

e.	As an end result of the Scenario 1, you will be able to view the Input Editor screen loaded with the configured values (see Figure below). The cells where the planning was impacted turns pink color. 

.. figure:: _static/pl15.png
    :align: center
    :alt: alternate text 
 
    Scenario 1 with configured values

Scenario 2
~~~~~~~~~~

Increase cost of sale by 10% from April Onwards

a.	For our example, select the Node “Cost of Sales” for April month (see Figure below).

.. figure:: _static/pl16.png
    :align: center
    :alt: alternate text  

    Cell Selection

b.	Increase the cell value by 10% and click Enter (see Figure below).

.. figure:: _static/pl17.png
    :align: center
    :alt: alternate text  

    Cost of Sales for April increased by 10%

c.	Now click the “Copy To” icon to copy the value from April across the periods till December (see Figure below) 

.. figure:: _static/pl18.png
    :align: center
    :width: 75
    :alt: alternate text  

    Copy-to icon

d.	After clicking the Copy to icon, the Input Editor screen looks similar to the Figure shown below.

.. figure:: _static/pl19.png 
    :align: center
    :alt: alternate text  

    Constant cell values from Apr to Dec

**Note:**
There is another copy-to function icon as shown in the below Figure.

.. figure:: _static/pl20.png
    :align: center
    :alt: alternate text 

    Copy-to Icon

This icon when clicked copies the value vertically downwards for the parent node to parent node and from child node to child node as shown in the below Figure. The value is “100” for the parent node and “50” for the  child node (see Figure below).

.. figure:: _static/pl21.png
    :align: center
    :alt: alternate text 

    Constant Cell values for parent to parent and child to child nodes 

Scenario 3
~~~~~~~~~~

Increase other costs a trend of 2% month on month

a.	For our example, select the Node “Other Costs” for Jan month (see Figure below).

.. figure:: _static/pl22.png 
    :align: center
    :width: 400
    :alt: alternate text  

    Cell Selection

b.	Now click the “Trend” icon (see Figure below) 

.. figure:: _static/pl23.png 
    :align: center
    :width: 60
    :alt: alternate text  
 
    Trend icon

c.	Now the Trend pop up opens. For our example, select the “By Percentage” option and enter value 2 in the Increase Trend section. Now select the Overwrite Values option and click “Apply” (see Figure below). 

.. figure:: _static/pl24.png 
    :align: center
    :width: 400
    :alt: alternate text  

    Increased Trend by 2 %

d.	Based on the above configuration, you will be able to view the Input Editor screen as shown below.

.. figure:: _static/pl25.png 
    :align: center
    :alt: alternate text  
 
    Scenario 3 with configured values from Jan to Dec
    
Scenario 4
~~~~~~~~~~

There is no increase in Support Costs at Total level but costs should be allocated in line with the Cost of Sales spread.

a.	For our example, select the Node “Support Costs” for Total column (see Figure below).

.. figure:: _static/pl26.png 
    :align: center
    :alt: alternate text   

    Cell Selection

b.	Now click the “Weight” icon (see Figure below) 

.. figure:: _static/pl27.png 
    :align: center
    :alt: alternate text  
 
    Weight icon

c.	Now the Spread by Weight pop up opens. For our example, select the Node as “Cost of Sales”. Select the Overwrite Values option and click “Apply” (see Figure below). The Total Value which is the Support Costs value can be also changed based on your requirement. 

.. figure:: _static/pl28.png 
    :align: center
    :width: 400
    :alt: alternate text   

    Spreads by Weights

d.	As an end result of the Scenario 4, you will be able to view the Input Editor screen loaded with the configured values (see Figure below). 

.. figure:: _static/pl29.png 
    :align: center
    :alt: alternate text  
 
    Scenario 4 with configured values


Scenario 5
~~~~~~~~~~

Increase Rent by 5% for Q1 and 10% from Q2 Onwards.

a.	Select the Node Rent and lock the entire Row for the Node Rent. 
b.	Release the lock for the Cells from Jan to Mar. 
c.	Now select the cell “Jan” for the Node Rent. Increase the value by 5% (see Figure below).

.. figure:: _static/pl30.png 
    :align: center
    :width: 400
    :alt: alternate text   

    Rent increased by 5% for Jan Month

d.	Now copy it across the cells. The Input Editor looks similar to the Figure as shown below.

.. figure:: _static/pl31.png 
    :align: center
    :alt: alternate text   

    Rent increased by 5% across the cells in the Row

e.	Now release the lock for the complete Row of the Node Rent. 
f.	Select the cell “Apr” for the Node Rent. Increase the value by 10% (see Figure below).

.. figure:: _static/pl32.png 
    :align: center
    :alt: alternate text   

    Rent increased by 10% for Apr Month

g.	Now copy it across the cells. The Input Editor looks similar to the Figure as shown below.

.. figure:: _static/pl33.png 
    :align: center
    :alt: alternate text  
 
    Rent increased by 10% across the cells in the Row from Apr till Dec Month

 
Other common features of the Input Editor
-----------------------------------------

Allocate Children
~~~~~~~~~~~~~~~~~

There are 2 different options namely "Weight" and "Equal" for the Children Node allocation (see Figure below).

.. figure:: _static/plch.png 
    :align: center
    :alt: alternate text  

    Allocate Children Nodes 

As part of the Business Scenario, the allocation for the children nodes will be based on the weight option and also the cell values will be only applied for the delta values.

Adding a Note
~~~~~~~~~~~~~

a.	In the Input Editor, select the Node “Rent” for Total column (see Figure below).

.. figure:: _static/pl34.png 
    :align: center
    :width: 500
    :alt: alternate text  

    Cell Selection

b.	Now click on the Note Icon as shown below.

.. figure:: _static/pl35.png 
    :align: center
    :alt: alternate text  
 
    Note Icon

c.	Enter the details in the note pop up as shown below.

.. figure:: _static/pl36.png 
    :align: center
    :alt: alternate text   

    Comments for the cell

d.	Once a note is entered, the cell would look similar to the Figure as shown below. On the right top corner, you can view a Note Indicator.

.. figure:: _static/pl37.png 
    :align: center
    :alt: alternate text   

    Note Indicator

View History
~~~~~~~~~~~~

Using the View History option, you will be able to view the Change Histories that have been done in the cells for different planning. You can select the specific history and restore them. You can also reset all the Histories by using the Reset All option (see Figure below).

.. figure:: _static/pl38.png 
    :align: center
    :width: 400
    :alt: alternate text 

    View History

Nodes Filtering 
~~~~~~~~~~~~~~~

Using the Search option in the Input Editor screen, you can filter the Nodes by providing the Node Name in the Search option as shown below.

.. figure:: _static/pl39.png 
    :align: center
    :width: 500
    :alt: alternate text   

    Search option for Nodes Filtering 

**Note:**
For the huge models, you can use this filter mode to only see the main node and children node. 


Input Editor Functionality

For our example, the below Figure represents the sample Data Source being assigned for the Planning Series.
 
Sample Data Source
With the help of the above shown Data Source, you will be able to create a New series using the Input Editor. The below steps explains us on how to create a Series in the Input Editor.


