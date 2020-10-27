.. _Latfood ltd:

Latfood
--------------------

Latfood prjects include several BI projects to date.
Latfood is both a Financial Cosultant customer and BI customer.

Approving documentations : XXXXXXXXX
Latfood contact : XXXXXXXXX


BI Projects
^^^^^^^^^^^^^^^^^^^^^^^^^^

Management System
##############

No documentation yet

Gross Profit Calculator
##############

The Gross Profit Calculator is a calculator which outputs the gross profit in
different scenarios, inputed by the user.


.. note::
 The goal of the calculator is to understand profitability better and it
 will be mainly used by the sales manager.


Documentation
****

.. important::
 **The Gross Profit Calculator will contain 3 sections :**

 1. **Output** the 'Gross Profit' based on an **input** of 'Items' and 'Sale Price', given a parameterized 'Cost'.
     This section requires **PowerBI**.

 2. **Output** the required 'Sale Price' for 'Items' based on an **input** of required 'Gross Profit' 
     This section requires **PowerBI and PowerApps**.

 3. **Output** a sensitivity table for each choice of segments (Items, Item Group etc..)
     This section requires **PowerBI**.

.. note::
 The Gross Profit Calculator is constructed from user inputs and outputs.

.. csv-table:: Section 1 Inputs
   :header: "Input Field", "Description"
   :widths: 20, 60

   "Items", "Item selection will be available both in 'Name' and in 'Code'"
   "Sale Price", "The intended 'Sale Price'"

.. csv-table:: Section 1 Outputs
   :header: "Output", "Description"
   :widths: 20, 60

   "Gross Profit", "The 'Gross Profit' for a given 'Item' and 'Sale Price' with a parameterized 'Cost'"

.. csv-table:: Section 2 Inputs
   :header: "Input Field", "Description"
   :widths: 20, 60

   "Item", "Item selection will be available both in 'Name' and in 'Code'"
   "Gross Profit Margin", "The wanted Gross 'Profit Margin'"

.. csv-table:: Section 2 Outputs
   :header: "Output", "Description"
   :widths: 20, 60

   "Sale Price", "The necessary 'Sale Price' in order to recieve a certain inputed 'Gross Profit'"

.. csv-table:: Section 3 Outputs
   :header: "Output", "Description"
   :widths: 20, 60

   "Sensitivity Table", "Gross Profit sensitivity table with +/- 10% in margin'"

The following section will describe the ''Tables'' and the ''Fields'' from the customer's server
which will be pulled to develop the calculator.

.. csv-table:: Required Tables/Fields
   :header: "Table", "Field", "Description"
   :widths: 20, 20, 60

   "OITM", "ItemCode", "The item's code (used in ERP)"
   "OITM", "ItemName", "The item's name"
   "OITM", "ItmsGrpCod", "The item's code for the 'Items Group'"
   "OTIM", "LastPurPrc", "The last documented purchase price"
   "OITB", "All Fields", "Items group table"

****
Summary and Scope of Work
****

The following table will contain the estimated work (Textual) and the time (Time)
needed in each phase of the project.

.. csv-table:: Scope of Work
   :header: "Action", "Description", "Estimated Time"
   :widths: 30, 60, 20

   "Creating Documentation", "Creating documentation of the project", "2 Hours"
   "Creating databases", "Creating databases for the PowerApps application that will be the base of section 2", "1 Hour"
   "Creating Application", "Creating the PowerApps application", "5 Hours"
   "Connecting PowerBI to Servers", "Connecting BI system to local and remote servers", "30 minutes'"
   "Creating BI Measures", "Creating the measures and calculations", "3 Hours"
   "Creating BI Objects", "Creating the user interface, graphsm objects etc..", "5 Hours"

.. important::
 **The final developement time estimated is : 16 Hours and 30 Minutes.**
 **Approved by : Not Approved Yet, Date : Not Approved Yet**


Changes History
****

.. tip::
 It is generally a good practice to document the changes by date and description
 to help fellow employees

.. csv-table:: Changes History
   :header: "Change Made", "Description", "Date and Time", "Employee", "Authorizing Manager"
   :widths: 20, 40, 20, 20, 20

   "Content Created", "Creating description for the project", "27/10/2020, 11:53:00", "Daniel Millionshik", "Lior Meidan"

.. doxygenclass:: Nutshell
  :members:


AI Projects
^^^^^^^^^^^^^^^^^^^^^^^^^^
Customer Purchase Date
##############

No documentation yet

Sales Prediction
##############

No documentation yet

Product Recommendations
##############

No documentation yet

.. doxygenclass:: Nutshell
  :members:
