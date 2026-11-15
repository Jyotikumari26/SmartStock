\# SmartStock - Inventory Management System



SmartStock is an ASP.NET Core MVC web application for managing products and categories in an inventory.



\## Features



\### Product Management

\- View product list

\- Add, edit and delete products

\- Search products by name or SKU

\- Filter products by category

\- View SKU, price, quantity and supplier details

\- Prevent duplicate SKUs



\### Category Management

\- View categories and product counts

\- Add, edit and delete categories

\- View products belonging to a category

\- Prevent duplicate category names

\- Prevent deletion of categories containing products



\## Technology Stack

\- ASP.NET Core MVC

\- .NET 10

\- C#

\- Razor Views

\- HTML, CSS and JavaScript

\- Dependency Injection



\## Installation and Setup



```bash

git clone https://github.com/Jyotikumari26/SmartStock.git

cd SmartStock

dotnet restore

dotnet build

dotnet run

```



\## Main Pages

\- Products: `/Products`

\- Categories: `/Categories`



\## Data Storage



The current Product and Category module uses an in-memory data store. Data may not persist after application restart.



SQL Server / LocalDB and Entity Framework Core integration are pending.



\## Repository



https://github.com/Jyotikumari26/SmartStock

