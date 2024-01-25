## 2) The Report and Data Views

In the following we shall go over the basics of the Power BI Desktop interface, specifically looking at the Report and Data views.

### Report View

The *Enter Data* button on the *Home* tab of the Report View gives you an interface that should feel familiar if you use Excel, as it opens a table-like structure where you can add columns, name them and put data into cells. It is important to note that this interface has no formula function, it is only for simple data entry. This window can be useful for testing, but it is not recommended that you put large amounts of information into this type of table structure.

Under *Calculations*, you have *New Measure* and *Quick Measure* options. *Measures* are calculations across your data using DAX. If you click *New Measure* you will see a formula bar appear where you can put in DAX for your measure. This is like the formula bar you might use in Excel. The *Quick Measure* button opens a pop-up box that helps you create a measure by using a wizard with several predefined calculations.

The *Elements* subsection of the *Insert* tab, deals with report elements. These are items that are not necessarily interactive like Power BI visuals, but they can help enhance your report ot give it extra clarity. These include text boxes, buttons, shapes and images. The buttons element can help with report navigation or provide additional information. Note that for all these buttons, except Q&A, Bookmark and the Navigator options, placing the button on the canvas does not do anything until you give Power BI the context for how that button should be used. After placing the button, you will see a *Format* button and it will contain visual formatting options, noting what action that button should do.

Under the *Modeling* tab, the *Manage relationships* button opens a window where you can see all the relationships in your model, and you can add or make edits to existing relationships. By default, Power BI will try to autodetect relationships based on column names. This can be useful for getting an initial set of relationships together for your data model, but it might not always be the way you want the model set up.

The *New column* and *New table* buttons in the *Calculations* subsection will bring up the inline DAX editor so that you can create either DAX calculated columns or DAX calculated tables.

The *Page refresh* subsection has a *Change detection* button that is relevant only in DirectQuery scenarios. You can determine whether you want your pages to refresh when there is a detected change in the data or on a fixed refresh interval.

The *Visualizations* pane is where you choose visualizations to add to a report, add columns and measures to display in those visuals in the *Values* subsection, and more. The *Drill through* section on the *Visualizations* pane allows you to drill down from one subsection of your report to another, while keeping all the data elements filtered as you had them previously - enabling you to develop a story with data that allows users to find specific examples that are relevant to their analysis.

### Data View

The Data view allows you to see the table-level data inside your report. It will display the columns in your report in their ordinal order instead of their alphabetical order. Two new subsections of the ribbon appear in Data view, *Table tools* and *Column tools*. The *Table tools* subsection allows you to change the table name or mark it as a date table, or we can look at our relationships here. The *Column tools* allows us to see the name of the selected column and its data type. From this tab we can select how we want the data to be formatted, its default summarizations and how Power BI should categorize that data. The *Sort by column* button allows you to sort one column by the contents of another. This allows you to set a rule for a column in terms of how it automatically sorts itself when put into a visual. *Data groups* allow you to put combinations or bins of data together for quick analysis. Some obvious examples of this are age brackets or ethnographic groupings. 
