## 1) Intro to Power BI

Microsoft Power BI is a data analytics and visualization tool powerful enough for the most demanding data scientists but accessible enough for everyday use by anyone needing to get more from their data. This chapter introduces Microsoft Power BI, discusses the entire Power BI family of products, provides an overview of how Power BI works, and looks at what distinguishes it from other similar tools.

---

### What is Power BI?

Power BI is both a piece of software and a larger ecosystem of products. Usually when people use the term "Power BI", it is in reference to the desktop software. However, when discussing how most people will visually share their work with others, it is done in the context of the Power BI service. Hereafter, we focus on Power BI Desktop and the Power BI service. *Power BI Desktop* is a tool for data investigation and visualization. Analysts can take data and create interactive reports that enable end users to garner insights.

The following is an overview of the components of the Power BI family of products:

- *Power BI Desktop*

An application you install on a local computer that you can use to connect to, transform and visualize data.

- *Power BI service*

An online software-as-a-service solution that lets end users share reports created in Power BI Desktop or Power BI Report Builder with users across an organization.

- *Power BI Mobile*

A set of applications for Windows, iOS and Android that allows end users to view reports in the Power BI service from their mobile devices.

- *Power BI Report Builder*

An application you install on a local computer that you use to generate paginated reports in the same form as SQL Server Reporting Services.

- *Power BI Report Server on premises*

If, for security reasons, you cannot publish reports to the Power BI service, your IT team may put a version of that software on an internal server behind the company firewall using on-premises computing resources.

- *Power BI Embedded*

Allows you to integrate Power BI reports and visuals into applications or websites.

---

### Power BI Desktop

There are two main components to Power BI Desktop, the Power BI canvas and Power Query. The canvas is the place where you build visualizations. Here you can use drag-and-drop functionality to pull information into different visualizations to explore your data and garner insights. Power Query is used to import and manipulate data. Unlike Excel, for example, you do not edit cells of data; you manipulate columns of data by using its functions, wizards and formulas. 

---

### Power BI service

The correct way to share reports with other users is to create a new workspace and invite others to that workspace. To be eligible to be invited to a workspace, a user must have a Power BI Pro license, or your organization must be using Power BI Premium. The Power BI service lets other end users explore reports you have created. This exploration can take the form of dashboards of curated visuals you put together, or it can be access to a report you have created with all its pages. Developers can manage deployment pipelines for workspace in the Power BI service, which lets you create and manage the development, test and production of workspaces. 

---

### Power BI Under the Hood

Power BI desktop works because under the hood it has two powerful engines, the VertiPaq engine and the DAX formula language. The formula engine takes data requests, processes them and generates a query plan for execution. The storage engine stores the data of the data model and pulls the data requested by the formula engine to satisfy a query's demand.

DAX is a formula language used in Analysis Services Tabular, Power BI and Power Pivot. This is done in the same way that you wold write SQL to get data from a database. Power BI users will most commonly use DAX to create measures and calculated columns. Even drag-and-drop functionality, or when visuals get created, Power BI generates the DAX for you and passes it to the internal engine.
