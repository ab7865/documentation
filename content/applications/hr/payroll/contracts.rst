=========
Contracts
=========

<<<<<<< HEAD
Every employee in Odoo is required to have a contract to be paid. A contract outlines the terms of
an employee's job position, compensation, working hours, and any other details specific to their
role.
||||||| parent of b19ed6a22 (temp)
Every employee in Odoo is required to have a contract in order to be paid. A contract outlines the
terms of an employee's position, their compensation, their working hours, and any other details
about their position.
=======
Every employee in Odoo is required to have a contract in order to be paid. A contract outlines the
terms of an employee's position, their compensation, working hours, and any other details about
their position.
>>>>>>> b19ed6a22 (temp)

.. important::
   Contract documents (PDFs) are uploaded and organized using the *Documents* application, and are
   signed using the *Sign* application. Ensure these applications are installed to send and sign
   contracts. Please refer to the :doc:`../../productivity/documents` and
   :doc:`../../productivity/sign` documentation.

<<<<<<< HEAD
To view the employee contracts, go to :menuselection:`Payroll app --> Contracts --> Contracts` from
the top menu. All employee contracts are displayed in a default list view, grouped into four
categories: :guilabel:`New`, :guilabel:`Running`, :guilabel:`Expired`, and :guilabel:`Cancelled`.

The default view has all categories collapsed. The number of contracts in each category is displayed
next to the category name (example: `Running (20)`). To view the list of contracts under any
category, click on the category, and the list expands downward, showing all contracts beneath it.
||||||| parent of b19ed6a22 (temp)
To view the employee contracts, go to the :menuselection:`Payroll app --> Employees --> Contracts`
from the top menu. All employee contracts, and their current contract status, are displayed in a
default kanban view. The default view displays both running contracts and contracts that need
action. Expired and canceled contracts are hidden in the default view.
=======
To view the employee contracts, go to the :menuselection:`Payroll app --> Contracts --> Contracts`
from the top menu. All employee contracts, and their current contract status, are displayed in a
Kanban view, by default. The Kanban view displays running contracts, contracts that require action,
expired contracts, and cancelled contracts.
>>>>>>> b19ed6a22 (temp)

.. image:: contracts/contracts-overview.png
   :align: center
   :alt: Contracts dashboard view showing running contracts and contracts with issues.

.. note::
   The list of contracts in the *Payroll* application matches the list of contracts in the
   *Employees* application.

.. _payroll/new-contract:

<<<<<<< HEAD
Create new contracts
====================
||||||| parent of b19ed6a22 (temp)
In order for an employee to be paid, an active contract is required. If a new contract is needed,
click the :guilabel:`Create` button on the contracts dashboard. A contract form appears where the
information can be entered. Required fields are underlined in bold.
=======
In order for an employee to be paid, an active contract is required. If a new contract is needed,
click the :guilabel:`Create` button on the :guilabel:`Contracts` dashboard. A contract form appears
where the information can be entered. Required fields are underlined in bold.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
For an employee to be paid, an active contract is required. When a new contract is needed, click the
:guilabel:`New` button on the :guilabel:`Contracts` dashboard. A contract form appears where the
information can be entered.
||||||| parent of b19ed6a22 (temp)
Required fields
---------------
=======
New contract form
-----------------
>>>>>>> b19ed6a22 (temp)

.. _payroll/gen-info:

General information section
---------------------------

- :guilabel:`Contact Reference`: type in the name or title for the contract, such as `John Smith
  Contract`. This field is **required**.
- :guilabel:`Employee`: using the drop-down menu, select the employee that the contract applies to.
- :guilabel:`Contract Start Date`: the date the contract starts. To choose a date, click the
  drop-down menu, navigate to the correct month and year with the :guilabel:`< > (arrow)` icons,
  then click on the desired date. This field is **required**.
- :guilabel:`Contract End Date`: if the contract has a specific end date, click the drop-down menu,
  navigate to the correct month and year with the :guilabel:`< > (arrow)` icons, then click on the
  desired date.
- :guilabel:`Working Schedule`: select one of the working schedules from the drop-down menu. This
  field is **required**.

  .. tip::
     The :guilabel:`Working Schedule` drop-down menu displays all the working schedules for the
     selected company. To modify or add to this list, go to :menuselection:`Payroll app -->
     Configuration --> Working Schedules`. Click :guilabel:`New`, and create a new working schedule,
     or click on an existing working schedule and make edits.

- :guilabel:`Work Entry Source`: select how the :doc:`work entries <work_entries>` are generated.
  This field is **required**. Click the radio button next to the desired selection. The options are:

  - :guilabel:`Working Schedule`: work entries are generated based on the selected
    :guilabel:`Working Schedule`.
  - :guilabel:`Attendances`: work entries are generated based on the employee's check-in records in
    the *Attendances* application. (This requires the *Attendances* application).
  - :guilabel:`Planning`: work entries are generated based on the planned schedule for the employee
    from the *Planning* application. (This requires the *Planning* application).

- :guilabel:`Salary Structure Type`: select one of the salary structure types from the drop-down
  menu. The default salary structure types are :guilabel:`Employee` or :guilabel:`Worker`. A
  :ref:`new salary structure type <payroll/new-structure-type>` can be created, if needed.
- :guilabel:`Department`: select the department the contract applies to from the drop-down menu.
- :guilabel:`Job Position`: select the specific job position the contract applies to from the
  drop-down menu.

  .. note::
     If the selected :guilabel:`Job Position` has a contract template linked to it with a specific
     :guilabel:`Salary Structure Type`, the :guilabel:`Salary Structure Type` changes to the one
     associated with that :guilabel:`Job Position`.

- :guilabel:`Wage on Payroll`: enter the employee's monthly wage.
- :guilabel:`Contract Type`: choose either :guilabel:`Permanent`, :guilabel:`Temporary`,
  :guilabel:`Seasonal`, :guilabel:`Full-Time`, or :guilabel:`Part-Time` from the drop-down menu.

.. figure:: contracts/required-fields.png
   :align: center
   :alt: New contract form to be filled in when creating a new contract, with required fields
         outlined in red.

<<<<<<< HEAD
   The general information section filled out, with the required fields highlighted in red.

Salary Information tab
----------------------

This section is where the specific salary details are defined. This section is country-specific, so
depending on where the company is located, these fields may vary.

The following fields are universal and apply to all localizations:
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Contact Reference`: Type in the name or title for the contract, such as `John Smith
  Contract`.
- :guilabel:`Company`: Select the company the contract applies to by clicking on the drop-down menu.
  A new company can be created by typing the name in the field, then clicking either
  :guilabel:`Create` to create the new company, or :guilabel:`Create and Edit` to create the new
  company and edit the company details.
- :guilabel:`Salary Structure Type`: Select one of the salary structure types from the drop-down
  menu. The default salary structure types are :guilabel:`Employee` or :guilabel:`Worker`. A new
  salary structure type can be created by typing the name in the field.
- :guilabel:`Start Date`: The date the contract starts. Choose a date by clicking on the drop-down
  menu, navigating to the correct month and year by using the :guilabel:`< > (arrow)` icons, then
  clicking on the :guilabel:`date`.
- :guilabel:`Working Schedule`: Select one of the working schedules from the drop-down menu.

.. tip::
   The :guilabel:`Working Schedule` drop-down menu displays all the working times for the selected
   :guilabel:`Company`. To modify or add to this list, go to :menuselection:`Payroll -->
   Configuration --> Working Times` and either :guilabel:`Create` a new working time or click on an
   existing working time and edit it by clicking :guilabel:`Edit`.

Optional fields
---------------

- :guilabel:`Employee`: Name of the employee that the contract applies to.
- :guilabel:`Department`: The department the contract applies to.
- :guilabel:`Job Position`: The specific job position the contract applies to.
- :guilabel:`Contract Type`: Choose from :guilabel:`CDI`, :guilabel:`CDD`, or :guilabel:`PFI` from
  the drop-down menu.
=======
- :guilabel:`Contact Reference`: type in the name or title for the contract, such as `John Smith
  Contract`. This field is **required**.
- :guilabel:`Employee`: name of the employee the contract applies to.
- :guilabel:`Contract Start Date`: the date the contract starts. Choose a date by clicking on the
  drop-down menu, navigating to the correct month and year by using the :icon:`fa-chevron-left`
  :icon:`fa-chevron-right` :guilabel:`(arrow)` icons, then clicking on the desired date. This field
  is **required**.
- :guilabel:`Contract End Date`: the date the contract ends. Choose a date by clicking on the
  drop-down menu, navigating to the correct month and year by using the :icon:`fa-chevron-left`
  :icon:`fa-chevron-right` :guilabel:`(arrow)` icons, then clicking on the desired date. This field
  is **required**.
- :guilabel:`Salary Structure Type`: select one of the salary structure types from the drop-down
  menu. The default salary structure types are :guilabel:`Employee` or :guilabel:`Worker`. A new
  salary structure type can be created by typing the name in the field. This field is **required**.
- :guilabel:`Working Schedule`: select one of the working schedules from the drop-down menu. This
  field is **required**.
- :guilabel:`Department`: the department the contract applies to.
- :guilabel:`Job Position`: the specific job position the contract applies to.
- :guilabel:`Wage on Payroll`: the amount to be paid to the employee each month.
- :guilabel:`Contract Type`: choose from :guilabel:`CDI`, :guilabel:`CDD`, or :guilabel:`PFI` from
  the drop-down menu.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
- :guilabel:`Wage Type`: select either :guilabel:`Fixed Wage` or :guilabel:`Hourly Wage` from the
  drop-down menu.
- :guilabel:`Schedule Pay`: select how often the employee is paid using the drop-down menu. Options
  are :guilabel:`Annually`, :guilabel:`Semi-annually`, :guilabel:`Quarterly`,
  :guilabel:`Bi-monthly`, :guilabel:`Monthly`, :guilabel:`Semi-monthly`, :guilabel:`Bi-weekly`,
  :guilabel:`Weekly`, or :guilabel:`Daily`.
- :guilabel:`Wage`: enter the employee's gross wage. The metric for the :guilabel:`Wage` is based on
  what is selected for the :guilabel:`Schedule Pay`.
||||||| parent of b19ed6a22 (temp)
  - :guilabel:`CDI` is an open-ended contract with only a start date but no end date.
  - :guilabel:`CDD` is a contract with both a start date and an end date.
  - :guilabel:`PFI` is a Belgian-specific contract used when hiring employees that need training,
    and covers the training period specifically.
=======
  - :guilabel:`CDI` is an open-ended contract with only a start date, but no end date.
  - :guilabel:`CDD` is a contract with both a start date and an end date.
  - :guilabel:`PFI` is a Belgian-specific contract used when hiring employees that need training,
    and covers the training period specifically.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
  .. example::
     If :guilabel:`Annually` is selected for the :guilabel:`Schedule Pay`, then the :guilabel:`Wage`
     field appears in a `$0.00/year` format. If the :guilabel:`Schedule Pay` is set to
     :guilabel:`Bi-weekly`, then the :guilabel:`Wage` field appears in a `$0.00/two weeks` format.
||||||| parent of b19ed6a22 (temp)
- :guilabel:`End Date`: If the contract has a specific end date, click the drop-down menu, navigate
  to the correct month and year using the arrow icons, then click on the date.
- :guilabel:`HR Responsible`: If there is a specific person in HR that is responsible for the
  contract, select the person from the drop-down menu.
- :guilabel:`Analytic Account`: This field allows a link between the contract and a specific
  analytic account for accounting purposes.
=======
- :guilabel:`HR Responsible`: if there is a specific person in HR that is responsible for the
  contract, select the person from the drop-down menu. This field is required.

.. tip::
   The :guilabel:`Working Schedule` drop-down menu displays all the working times for the selected
   :guilabel:`Company`. To modify or add to this list, go to :menuselection:`Payroll app -->
   Configuration --> Working Times`, and either :guilabel:`Create` a new working time, or click on
   an existing working time, then edit it by clicking :guilabel:`Edit`.
>>>>>>> b19ed6a22 (temp)

- :guilabel:`Yearly Cost (Real)`: this field automatically updates after the :guilabel:`Schedule
  Pay` and :guilabel:`Wage` fields are entered. This amount is the total yearly cost for the
  employer. This field can be modified. However, if this is modified, the :guilabel:`Wage` field
  updates, accordingly. Ensure both the :guilabel:`Wage` and :guilabel:`Yearly Cost (Real)` are
  correct if this field is modified.
- :guilabel:`Monthly Cost (Real)`: this field automatically updates after the :guilabel:`Schedule
  Pay` and :guilabel:`Wage` fields are entered. This amount is the total monthly cost for the
  employer. This field **cannot** be modified, and is calculated based on the :guilabel:`Yearly
  Cost (Real)`.

  .. image:: contracts/salary-info.png
     :align: center
     :alt: Optional tabs for a new contract.

Contract Details tab
--------------------

The :guilabel:`Contract Details` tab allows for the addition and editing of a contract, along with
specifying which template to use when a new contract is created. These fields **must** be populated
in order to create a new contract.

.. important::
   To access the various contract template fields in the :guilabel:`Contract Details` tab, the
   *Salary Configurator* (`hr_contract_salary`) module **must** be :ref:`installed
   <general/install>`.

   When the *Salary Configurator* module is installed, the *Salary Configurator - Holidays* and
   *Salary Configurator - Payroll* modules install, as well.

   Once the modules are installed, the database reverts to the main dashboard.

- :guilabel:`Contract Template`: select a pre-existing contract template from the drop-down menu.
  Contract templates are typically created through the configuration menu, and stored in the
  *Documents* application.

Sign section
~~~~~~~~~~~~

- :guilabel:`HR Responsible`: select the person who is responsible for validating the contract from
  the drop-down menu. This field is required.
- :guilabel:`New Contract Document Template`: select a contract from the drop-down menu to be
  modified for this new employee contract. These documents are stored in the *Sign* application.
- :guilabel:`Contract Update Document Template`: select a contract from the drop-down menu, if the
  employee has an existing contract that requires updating. These documents are stored in the *Sign*
  application.

.. important::
   The :guilabel:`HR Responsible`, :guilabel:`New Contract Document Template`, and
   :guilabel:`Contract Update Document Template` fields are only visible if the *Sign* application
   is installed, along with the `hr_contract_salary` and `hr_contract_salary_payroll` :doc:`modules
   <../../general/apps_modules>`. The *Sign* application is where the contract templates are stored.
   This application is required for an employee to sign any contract.

Accounting section
~~~~~~~~~~~~~~~~~~

- :guilabel:`Analytic Account`: select the account the contract affects from the drop-down menu. It
  is recommended to check with the accounting department to ensure the correct account is selected.

Part Time section
~~~~~~~~~~~~~~~~~

- :guilabel:`Part Time`: tick this box if the employee is working part-time. When active, additional
  fields appear:

  - :guilabel:`% (Percentage)`: enter the percent of time the employee works as compared to a
    full-time employee.
  - :guilabel:`Standard Calendar`: select the working hours that a typical full-time worker uses
    from the drop-down menu.
  - :guilabel:`Part Time Work Entry Type`: select the work entry type that generates the balance of
    a full-time working schedule.

    .. example::
       If a full-time employee works 40 hours a week, and the employee works 20, enter `50` in the
       :guilabel:`% (Percentage)` field (50% of 40 hours = 20 hours). The employee generates twenty
       (20) hours of work entries under the work entry type `part-time`, and another twenty (20)
       hours of work entries under the work entry type `generic time off`, for a total of forty (40)
       hours worth of work entries.

Notes section
~~~~~~~~~~~~~

- :guilabel:`Notes`: a text field where any notes for the employee contract are entered for future
  reference.

.. image:: contracts/contract-details.png
   :align: center
   :alt: Contract details in optional tabs for a new contract.

<<<<<<< HEAD
Personal Documents tab
----------------------
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Contract Template`: Select a pre-existing contract template from the drop-down menu.
  Contract templates are typically created through the *Recruitment* application.
- :guilabel:`New Contract Document Template`: Select a contract from the drop-down menu to be
  modified for this new employee contract.
- :guilabel:`Contract Update Document Template`: Select a contract from the drop-down menu if the
  employee has an existing contract that requires updating.
- :guilabel:`Notes`: The notes field is a text field where any notes for the employee contract can
  be entered for future reference.
=======
- :guilabel:`Analytic Account`: this field allows a link between the contract and a specific
  analytic account for accounting purposes.
- :guilabel:`Contract Template`: select a pre-existing contract template from the drop-down menu.
  Contract templates are typically created through the *Recruitment* application.
- :guilabel:`New Contract Document Template`: select a contract from the drop-down menu to be
  modified for this new employee contract.
- :guilabel:`Contract Update Document Template`: select a contract from the drop-down menu, if the
  employee has an existing contract that requires updating.
- :guilabel:`Notes`: the notes field is a text field where any notes for the employee contract can
  be entered for future reference.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
Once an :guilabel:`Employee` is selected in the :ref:`General Information section
<payroll/gen-info>`, the :guilabel:`Personal Documents` tab appears.
||||||| parent of b19ed6a22 (temp)
Modifying a contract
~~~~~~~~~~~~~~~~~~~~
=======
Modify a contract template
~~~~~~~~~~~~~~~~~~~~~~~~~~
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
If any documents are needed to keep on file, add them in the :guilabel:`Personal Documents` tab.
Depending on what other applications are installed, and what kind of benefits are enabled (and
offered) to the employee, the various options to add a file varies. The :guilabel:`Image` option
always appears, and is available by default.
||||||| parent of b19ed6a22 (temp)
Click the :guilabel:`External Link` button at the end of each line to open the corresponding
contract template and make any changes.
=======
Click the :icon:`fa-external-link` :guilabel:`(external Link)` icon at the end of either the
:guilabel:`New Contract Document Template` or :guilabel:`Contract Update Document Template` to open
the corresponding contract template, and proceed to make any desired changes.
>>>>>>> b19ed6a22 (temp)

Click the :guilabel:`Upload your file` button next to the corresponding document, navigate to the
file, then click :guilabel:`Open` to select the document and add it to the tab.

Modifying contract templates
============================

Contracts templates can be modified at any point when changes are needed.

<<<<<<< HEAD
To modify a contract template, refer to the :ref:`contract templates <payroll/contract-templates>`
section of the main payroll documentation.
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Tags`: Select any tags associated with the contract.
- :guilabel:`Signed Document Workspace`: This is where the signatures are stored. Choose a
  pre-configured workspace or create a new one.
- :guilabel:`Signed Document Tags`: Select or create any tags associated only with the signed
  contract as opposed to the original unsigned contract.
- :guilabel:`Redirect Link`: Enter a redirect link for the employee to access the contract. A
  redirect link takes the user from one URL to another, in this case, to the newly updated contract
  specifically written for them.
- :guilabel:`Who can Sign`: Select either :guilabel:`All Users` or :guilabel:`On Invitation`.
=======
- :guilabel:`Tags`: select any tags associated with the contract.
- :guilabel:`Signed Document Workspace`: this is where the signatures are stored. Choose a
  pre-configured workspace, or create a new one. To create a new :guilabel:`Signed Document
  Workspace`, type in the name of the workspace, then click either :guilabel:`Create` to add the new
  workspace, or :guilabel:`Create and Edit` to add the workspace and modify the workspace details.
- :guilabel:`Signed Document Tags`: select or create any tags that are only associated with the
  signed contract, as opposed to the original unsigned contract.
- :guilabel:`Redirect Link`: enter a redirect link for the employee to access the contract. A
  redirect link takes the user from one URL to another. In this case, it takes them to the
  newly-updated contract specifically written for them.
- :guilabel:`Who can Sign`: select either :guilabel:`All Users` or :guilabel:`On Invitation`.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
Salary attachments
==================
||||||| parent of b19ed6a22 (temp)
  - :guilabel:`All Users`: Any user in the organization can sign the contract.
  - :guilabel:`On Invitation`: Only users selected in this field can sign the contract.

- :guilabel:`Invited Users`: Select the person(s) that can sign the document.
- :guilabel:`Document`: The attached document can be replaced by clicking the :guilabel:`✏️
  (pencil)` icon. A pop-up window appears so another document can be selected for upload. The file
  must be a PDF. To remove the document, click the :guilabel:`🗑️ (trash can)` icon.

Once the edits are complete, click the :guilabel:`Save` button. All the information for the selected
contract template populates the fields in the :guilabel:`Salary Information` tab. Any additional
tabs, such as :guilabel:`Personal Documents`, appears if applicable.

Salary information
------------------

.. image:: contracts/salary-info.png
   :align: center
   :alt: Optional tabs for a new contract.

This section is where the specific salary details are defined. This section is country-specific, so
depending on where the company is located, these fields may vary.

Enter the amount in the various fields, or check a box to apply a benefit. Some options that can be
entered here include :guilabel:`Meal Vouchers`, :guilabel:`Fuel Card`, :guilabel:`Internet`,
:guilabel:`Paid Time Off`, etc.

Some fields may be automatically filled in based off of the contracts selected in the
:guilabel:`Contract Details` tab.

Attachment of salary
--------------------
=======
  - :guilabel:`All Users`: any user in the organization can sign the contract.
  - :guilabel:`On Invitation`: only users selected in this field can sign the contract.

- :guilabel:`Invited Users`: select the person (or people) that can sign the document.
- :guilabel:`Document`: the attached document can be replaced by clicking the :icon:`fa-pencil`
  :guilabel:`(pencil)` icon. A pop-up window appears, so another document can be selected for
  upload. The file **must** be a PDF. To remove the document, click the :icon:`fa-trash-o`
  :guilabel:`(trash can)` icon.

Once the edits are complete, click the :guilabel:`Save` button. All the information for the selected
contract template populates the fields in the :guilabel:`Salary Information` tab. Any additional
tabs, such as :guilabel:`Personal Documents`, appears if applicable.

Salary information
------------------

.. image:: contracts/salary-info.png
   :align: center
   :alt: Optional tabs for a new contract.

This section is where the specific salary details are defined. This section is country-specific, so
these fields vary, depending on where the company is located.

Enter the amount in the various fields, or tick a checkbox to apply a benefit. Some options that can
be entered here include :guilabel:`Group Insurance Sacrifice Rate` and :guilabel:`Canteen Cost`, for
example.

Some fields may be automatically filled in as other fields are entered. For example, the
:guilabel:`Yearly Cost (Real)` and :guilabel:`Monthly Cost (Real)` updates once the :guilabel:`Wage`
is populated.

Personal documents
------------------
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
Any automatic deductions or allocations for an employee, such as child support payments and wage
garnishments, are referred to as a *salary attachment*. Navigate to :menuselection:`Payroll app -->
Contracts --> Salary Attachments` to view a list of all the currently configured salary attachments.
||||||| parent of b19ed6a22 (temp)
Any automatic deductions or allocations for an employee, such as child support payments and wage
garnishments, are referred to as a *salary attachment*. This section is where all of these
deductions or allocations are set.
=======
This tab **only** appears after an :guilabel:`Employee` is selected, and houses any documents that
are linked to the employee on their employee record. Documents cannot be added to this tab, this tab
**only** shows documents that are already uploaded and associated with the employee.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
Each salary attachment appears with all its relevant details displayed. The :guilabel:`Status` for
each attachment is color-coded in the far right column.

Currently running salary attachments have a :guilabel:`Status` of :guilabel:`Running`, and appear in
green. Salary attachments that have been paid in-full, and are no longer active, have a
:guilabel:`Status` of :guilabel:`Completed`, and appear in blue. Cancelled salary attachments have a
:guilabel:`Status` of :guilabel:`Cancelled`, and appear in red.

.. image:: contracts/attachments.png
   :align: center
   :alt: A list view of all the salary attachments with their status displayed.

New salary attachment
---------------------

To create a new salary attachment from the :guilabel:`Salary Attachment` page, click
:guilabel:`New`, and a blank salary attachment form loads. Enter the following information on the
form:

- :guilabel:`Employees`: add any employees the salary attachment applies to using the drop-down
  menu.

  .. tip::
     Multiple employees can be added, if the salary attachment details are identical. After all
     employees are added, a :guilabel:`Create Individual Attachments` button appears at the top of
     the form.

     After the form is completed, click the :guilabel:`Create Individual Attachments` button to
     create separate salary attachments for each of the employees listed in this field.

     .. image:: contracts/individual-attachments.png
        :align: center
        :alt: The Create Individual Attachments button that appears after multiple employees are
              added to the Employees field.

     This is a time-saving tip, so that separate salary attachments do not need to be created
     individually. They can be created in a batch using this method.

- :guilabel:`Description`: enter a description for the specific type of salary attachment.
- :guilabel:`Type`: select the :ref:`type of salary attachment <payroll/salary-attachment-types>`
  from the drop-down menu. The options listed come from the salary attachment types configured in
  the configuration menu.
- :guilabel:`Start Date`: enter the date the salary attachment begins. The first of the current
  month populates this field, by default. Click on the date, and a calendar appears. Navigate to the
  desired month and year, using the :guilabel:`< > (arrow)` icons, and click on the date to select
  it.
- :guilabel:`Document`: if any documents are needed for the salary attachment, click the
  :guilabel:`Upload your file` button, and a file explorer appears. Navigate to the file, and click
  :guilabel:`Open` to select them, and attach them to the form.
- :guilabel:`Monthly Amount`: enter the amount to be taken out of the paycheck each month for this
  salary attachment.
- :guilabel:`Estimated End Date`: this field only appears after the :guilabel:`Monthly Amount` field
  is populated, and if the :guilabel:`Type` is **not** set to :guilabel:`Child Support`. This date
  is when the salary attachment is predicted to end, and is automatically calculated once both, the
  :guilabel:`Monthly Amount` and :guilabel:`Total Amount`, fields are populated. This is calculated
  based on how much is required to be paid, and how much is paid towards that amount each month. If
  either the :guilabel:`Monthly Amount` or :guilabel:`Total Amount` changes, this field
  automatically updates. It is **not** possible to modify this field.
- :guilabel:`Total Amount`: enter the total amount to be paid in this field. If :guilabel:`Child
  Support` is selected for the :guilabel:`Type`, this field does **not** appear.

.. image:: contracts/garnishment.png
   :align: center
   :alt: Enter a new line for each type of garnishment.

.. important::
   When the total amount has been paid for the salary attachment, navigate to the individual salary
   attachment, and click the :guilabel:`Mark as Completed` button at the top of the form. This
   changes the status to :guilabel:`Completed`, and the garnishments are no longer taken out of the
   employee's paychecks.

Offers
======

Once a contract has been created or modified, the contract **must** be sent to the employee to be
accepted and signed.

Send an offer
-------------

Open an individual contract by navigating to :menuselection:`Payroll app --> Contracts ->
Contracts`, and click on a contract to open the contract form. Click on the :guilabel:`Generate
Offer` button at the top of the page, and a :guilabel:`Generate Simulation Link` pop-up form
appears.
||||||| parent of b19ed6a22 (temp)
To add a new deduction, click :guilabel:`Add a line`. Type in a description for the allocation under
:guilabel:`Description`.

.. image:: contracts/garnishment.png
   :align: center
   :alt: Enter a new line for each type of garnishment.

Select the :guilabel:`Garnished Type` from the drop-down menu. Choose from:

- :guilabel:`Attachment of Salary`: Any payments taken out towards something that is *not* child
  support. Typically any garnishments such as lawsuit payments, payments toward taxes owed, etc.
- :guilabel:`Assignment of Salary`: Any deduction that is not required but voluntary, such as a
  pre-tax allocation to a college savings account.
- :guilabel:`Child Support`: Any payments taken out specifically for child support.

Enter the start and end dates the entry applies to. Click on the drop-down menu under
:guilabel:`From` and :guilabel:`To`, navigate to the correct month and year by using the
:guilabel:`< > (arrow)` icons, then click on the :guilabel:`date`.

Last, enter the :guilabel:`Amount` that each payslip pays towards the entry.

To delete a line, click the :guilabel:`🗑️ (trash can)` icon at the end of the line.

Save and send the contract
--------------------------

Once a contract has been created and/or modified, save the contract by clicking the :guilabel:`Save`
button. Next, the contract must be sent to the employee to be signed.

Click on one of the following buttons to send the contract to the employee:
=======
The available documents in this tab can be downloaded. Click the :icon:`fa-download`
:guilabel:`(download)` icon next to the document to download it.

Save and send the contract
--------------------------

Once a contract has been created and/or modified, save the contract by clicking the :guilabel:`Save`
button. Next, the contract must be sent to the employee to be signed.

Click on one of the following buttons to send the contract to the employee:
>>>>>>> b19ed6a22 (temp)

.. image:: contracts/send-contract.png
   :align: center
   :alt: Send the contract to the employee via one of the buttons.

<<<<<<< HEAD
The :guilabel:`Generate Simulation Link` pop-up form contains all the information pulled from the
contract, including the :guilabel:`Contract Template`, :guilabel:`Job Position`, :guilabel:`Job
Title`, :guilabel:`Department`, :guilabel:`Contract Start Date`, :guilabel:`Default Vehicle`,
:guilabel:`Contract Type`, and :guilabel:`Yearly Cost`.
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Generate Simulation Link`: This option is for Belgian companies only. Clicking this
  opens a pop-up window that contains the basic information from the contract as well as a link for
  the contract when using the salary configurator. Click :guilabel:`Send Offer` to send an email to
  the employee so they can sign the contract.
=======
- :guilabel:`Generate Simulation Link`: this option is **only** for Belgian companies. Clicking this
  opens a pop-up window that contains the basic information from the contract, as well as a link for
  the contract when using the salary configurator. Click :guilabel:`Send` to send an email to the
  employee, so they can sign the contract.
>>>>>>> b19ed6a22 (temp)

At the bottom of the pop-up form is a :guilabel:`Link Expiration Date`. This is the timeframe that
the contract offer is valid for. By default, this field is pre-populated with `30 days`, but it can
be modified.

<<<<<<< HEAD
Click the :guilabel:`Send By Email` button, and a :guilabel:`Send Offer Email` template pop-up
window appears. Make any modifications to the email, and attach any additional documents needed,
then click :guilabel:`Send` to send the offer.
||||||| parent of b19ed6a22 (temp)
  .. note::
     In order to send a contract using the :guilabel:`Generate Simulation Link`, there must be a
     signature field in the contract PDF being sent to the employee so they can sign it.
=======
  .. note::
     In order to send a contract using the :guilabel:`Generate Simulation Link`, there **must** be a
     signature field in the contract PDF being sent to the employee, so they can sign it.
>>>>>>> b19ed6a22 (temp)

<<<<<<< HEAD
.. image:: contracts/send-offer.png
   :align: center
   :alt: The email template pop-up to send an offer.
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Signature Request`: Click this and a pop-up window appears where an email can be typed
  to the employee. Select the document, such as a contract, NDA, or Homeworking Policy, from the
  drop-down menu, and fill out the email section. Click :guilabel:`Send` when the email is ready to
  be sent.
=======
- :guilabel:`Signature Request`: clicking this reveals a pop-up window, where an email can be typed
  to the employee. Select the document (such as a contract, NDA, or Homeworking Policy) from the
  drop-down menu, and fill out the email section. Click :guilabel:`Send` when the email is ready to
  be sent.
>>>>>>> b19ed6a22 (temp)

.. note::
   To send a contract using the :guilabel:`Generate Simulation Link`, there **must** be a signature
   field in the contract PDF being sent to the employee, so they can sign it.

<<<<<<< HEAD
Accept an offer
---------------

Once the offer email is received, the offer can be accepted, and the contract can be signed.

In the offer email, click the :guilabel:`Configure your package` button, and the offer loads in a
new tab. Enter the requested information on the form. Next, click the :guilabel:`Review Contract &
Sign` button to begin the signing process.

Click the :guilabel:`CLICK TO START` button at the top-left of the contract. Follow the prompts to
complete the signature request. The contract auto-populates with the information entered on the
:guilabel:`Configure your package` page. When done, click the :guilabel:`Validate & Send Completed
Document` button at the bottom of the contract.

After the document is signed by the (potential) employee, management signs the contract next. The
manager's signature is completed directly in the *Sign* application.

.. image:: contracts/sign-contract.png
   :align: center
   :alt: The contract offer, ready to sign with the Click to Start button highlighted.

.. note::
   Depending on the localization settings, there may be the option to customize the offer in the
   :guilabel:`Configure your package` tab.

View offers
-----------

To view the current offers, navigate to :menuselection:`Payroll app --> Contracts --> Offers`. This
presents all offers in a list view, grouped by status, and displays the number of offers in each
status category. The statuses are: :guilabel:`Fully Signed`, :guilabel:`Partially Signed`,
:guilabel:`In Progress`, and :guilabel:`Expired`.

To view the offers with a specific status, click on the status to expand the list. If a specific
status has no offers, the status is not visible in the list.

.. image:: contracts/offers.png
   :align: center
   :alt: The offers in a list view, grouped by status.
||||||| parent of b19ed6a22 (temp)
- :guilabel:`Credit Time`: This option is for Belgian companies only. When clicked, a pop-up window
  appears that allows for the changing of working times, and can compute time off.
=======
Salary attachments
------------------

Any automatic deductions or allocations for an employee, such as child support payments and wage
garnishments, are referred to as a *salary attachment*. This section is where all of these
deductions or allocations are set.

To add a new deduction, first navigate to :menuselection:`Payroll app --> Contracts --> Salary
Attachments`. Next, click :guilabel:`Create`, and a new salary attachment form loads.

.. image:: contracts/garnishment.png
   :align: center
   :alt: The salary attachment form with everything filled in for Ronnie Hart's child support.

Fill out the following fields on the form:

- :guilabel:`Employee`: using the drop-down menu, select the employee the salary attachment applies
  to.
- :guilabel:`Description`: enter a short description for the salary attachment, such as `Child
  Support` or `529 Contribution`.
- :guilabel:`Type`: using the drop-down menu, select the type of salary attachment being created.
  Choose from:

  - :guilabel:`Attachment of Salary`: any payments taken out towards something that is *not* child
    support. Typically any garnishments, such as lawsuit payments, payments toward taxes owed, etc.
  - :guilabel:`Assignment of Salary`: any deduction that is not required, but voluntary, such as a
    pre-tax allocation to a college savings account.
  - :guilabel:`Child Support`: any payments taken out specifically for child support.

- :guilabel:`Start Date`: the date the salary attachment starts. Choose a date by clicking on the
  drop-down menu, navigating to the correct month and year by using the :icon:`fa-chevron-left`
  :icon:`fa-chevron-right` :guilabel:`(arrow)` icons, then clicking on the desired date. This field
  is **required**.
- :guilabel:`Estimated End Date`: this field automatically populates after both the
  :guilabel:`Monthly Amount` and :guilabel:`Total Amount` fields are populated. This field is
  **not** modifiable.
- :guilabel:`Document`: attach any documents relevant to the salary attachment. Click the
  :guilabel:`Upload Your File` button, navigate to the desired document in the file explorer, then
  click :guilabel:`Open` to select the document, and attach it to the form. To change the attached
  document, click the :icon:`fa-pencil` :guilabel:`(pencil)` icon, and select a different document.
  To remove a document, click the :icon:`fa-trash-o` :guilabel:`(trash can)` icon.
- :guilabel:`Monthly Amount`: enter the amount to be taken out of the employee's paycheck every
  month for this specific salary attachment.
- :guilabel:`Total Amount`: enter the total amount that the employee pays for the salary attachment
  to be completed.
>>>>>>> b19ed6a22 (temp)
