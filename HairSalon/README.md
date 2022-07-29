# hair salon stylist tracker

#### By _**Jacob Palaoro**_  

#### _An MVC application to organize a hair salons stylist and clients._  

---

## Table of Contents

**[Technologies Used](#technologies-used)  
[Description](#description)  
[Setup/Installation Requirements](#setup-and-installation-requirements)  
[Known Bugs](#known-bugs)  
[License](#license)**

---

## Technologies Used

* _C#_
* _.NET_
* _HTML_
* _CSS_
* _SQL Workbench_
* _Entity Framework_
* _MVC_

---
## Description

_This is an MVC application that was built using C#. The purpose of this application is to allow the user to view stylist and their corresponding clients. When the application runs, the user can add a stylist. After the type is inputted using the "add" button, users can then add specific clients to that specific stylist._

---
## Setup and Installation Requirements

<details>
<summary><strong>Initial Setup</strong></summary>
<ol>
<li>Copy the git repository url
<li>Open a shell program and navigate to your desktop.
<li>Clone the repository for this project using the "git clone" command and including the copied URL.
<li>While still in the shell program, navigate to the root directory of the newly created file named "Salon.Solution".
<li>From the root directory, navigate to the "HairSalon" directory.
<li>Move onto "SQL Workbench" instructions below to re-create database necessary to run this project.
<br>
</details>

<details>
<summary><strong>SQL Workbench Configuration</strong></summary>
<ol>
<li>Create an appsetting.json file in the "HairSalon" directory of the project*  
   <pre>HairSalon.Solution
   └── HairSalon
    └── appsetting.json</pre>
<li> Insert the following code** : <br>

<pre>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=jacob_palaoro;uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
}</pre>
<small>*note: you must include your password in the code block section labeled "YOUR-PASSWORD-HERE".</small><br>
<small>**note: if you plan to push this cloned project to a public-facing repository, remember to add the appsettings.json file to your .gitignore before doing so.</small>

<li>Once "appsettings.json" file has been created, navigate back to SQL Workbench.
<li>Import the database named "jacob_palaoro.sql" from the root directory of the project.<br><br>
How to Import a Database:
<ol> 
  <li>Open SQL Workbench.
  <li>Navigate to "Administration" tab in SQL Workbench.
  <li>Click "Data Import/Restore".
  <li>Select the radio button "Import from Self-Contained File" and include file path to the sql file of this project you cloned to your machine.
  <li>In "Default Schema to be Imported to" click "New".
  <li>Name the schema "jacob_palaoro" then click "OK".
  <li>Once named, switch to "Import Progress" tab and click "Start Import".
  
</details>

<details>
<summary><strong>To Run</strong></summary>
Navigate to:  
   <pre>HairSalon.Solution
   └── <strong>HairSalon</strong></pre>

Run ```$ dotnet restore``` in the console.<br>
Run ```$ dotnet run``` in the console
</details>
<br>

This program was built using *`Microsoft .NET SDK 5.0.401`*, and may not be compatible with other versions. Your milage may vary.

---
## Known Bugs

* _No known issues_

## License

_[MIT License](license)_

Copyright (c) July 28th, 2022 Jacob Palaoro