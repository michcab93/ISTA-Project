# ISTA Project Step 3
#####Michelle Caballero
#####January 27, 2019

Database Requirements

customers
    CustomerID text PRIMARY KEY,
    CompanyName text,
    ContactName text,
    ContactTitle text,
    ContactEmail text,
    Address text,
    City text,
    Region text,
    PostalCode text,
    Country text,
    Phone text,

employees (
    EmployeeID integer NOT NULL,
    LastName text  NOT NULL,
    FirstName text  NOT NULL,
    Title text ,
    TitleOfCourtesy text ,
    BirthDate date,
    HireDate date,
    Address text ,
    City text ,
    Region text ,
    PostalCode text ,
    Country text ,
    HomePhone text ,
    Extension text ,
    Notes text,
    ReportsTo integer,
    PhotoPath text

suppliers
    SupplierID integer NOT NULL,
    CompanyName text NOT NULL,
    ContactName text,
    ContactTitle text,
    Address text,
    City text,
    Region text,
    PostalCode text,
    Country text,
    Phone text,

products
    ProductID integer NOT NULL,
    ProductName text NOT NULL,
    CategoryID integer,
    ProductColor text NOT NULL,
    ProductLenght integer NOT NULL,
    ProductWidth interger NOT NULL,
    Product Height interger NOT NULL,
    ProductWeight interger NOT NULL,
    UnitPrice real DEFAULT 0,
    UnitsInStock integer DEFAULT 0,
    UnitsOnOrder integer DEFAULT 0,
    ReorderLevel integer DEFAULT 0,
    Discontinued text NOT NULL DEFAULT '0',


  orders
    OrderID integer NOT NULL PRIMARY KEY AUTOINCREMENT,
    CustomerID text,
    EmployeeID integer,
    OrderDate text,
    RequiredDate text,
    ShippedDate text,
    ShipperID integer,
    ShipAddress text,
    ShipCity text,
    ShipRegion text,
    ShipPostalCode text,

  order_details(

    OrderID integer NOT NULL,
    ProductID integer NOT NULL,
    UnitPrice real NOT NULL DEFAULT 0,
    Quantity integer NOT NULL DEFAULT 1,
    Discount real NOT NULL DEFAULT 0,
