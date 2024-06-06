2024-05-16 0143 EDT
JAMODU BUSAYO DANIEL
WEB APP CREATED W/ VS2022 .NET 7



Recreated the ASP .NET MVC Core application
Using .Net 7,no authentication


0144- Ran the program, Confirmed the default works: https://localhost:7168
      MvcMovie Folder created.

0147- Changed Welcome in the index.cshtml to MVC MOVIES
       Part 1 of lab completed


0213-  Add a controller
       HelloWordController.cs opened successfully.
       Using https://localhost:7168/HelloWorld the default screen displayed ie This is my default action...

0217- Using https://localhost:7168/HelloWorld/Welcome the default screen displayed ie This is the welcome action method...
      chnaged the welcome method to include two parameters


0226- https://localhost:7168/HelloWorld/Welcome?name=Rick&numtimes=4 worked sucessfully, edited and tried different names from the browser.
      changed the welcome method to use ID and confirm it worked, https://localhost:7168/HelloWorld/Welcome/3?name=Rick
      


0245- issue with opening the index.cshtml.Took a while to troubleshoot the issue, had to take a step back before i could decipher the issue in index.cshtml


0302- resolved issues, ommitted codes didnt allow Index statement return View()
      Found a block of code i ommitted, added them to Index at HelloWordController.cs


2024-05-23 0150 EDT
Continuation- WEB APP CREATED W/ VS2022 .NET 7


0153- went through work dot netdot was previously completed, ran codes to make sure all was intact.

0156- created a view, sucessfully. Ran it annd it worked


0200-added the nuGet packages, didnt work at first but figured i nneeded to change to the version of virtual studio
selected v.7.0 and it installed successfully.

0210-sucessfully installed Microsoft.VisualStudio.Web.CodeGeneration.Design Microsoft.EntityFrameworkCore.SqlServer and Microsoft.EntityFrameworkCore.Designdotnet

0240- error. pkg not working

0300-error.


2024-05-23 0150 EDT
Continuation- WEB APP CREATED W/ VS2022 .NET 7

0900- after making some research oline i was able to navigate the issue. I noticed when i tried to manage the nuggets it dispalyed 8.0 as the best option but i chnaged to 7.0 and download the module.

0930-After installing i realised it doawnload the 8.0 module. I was able to navigate through this issue and rectify the version to a 7.0 mpdule,
i used the command dotnet tool install --global dotnet-ef --version 7.* this innstalls dotnet-ef that is compatible with  7.0 module.

1010-After this i was able to createa a scafold and used the SQL Server,Initial migration
and tested the app and workd sucessfullywas



timestamp
20240524003850_InitialCreate.cs
tested the app




2024-05-28 0120 EDT
Continuation- WEB APP CREATED W/ VS2022 .NET 7

0125- Part 5 completeed ad tested.; Seed data was ceeated. Updated the program.cs.
      Tested and ran the SeedData.Initialize method rans and seeds the database.

0132- Moved to part 6
      Updated the Index method in the MoviesController.cs.I encountered a bit of an obstacle on locating where this new codes would but after testing i figured it out and ran the application
       Searchstring attached.

0150- Added the <form>
      Created the new class in the molders folder named MovieGenreViewModel, this adds about 3 models. The search by genre index view was also asked to be updated which i did
       Tested the app and now i can see the search box and genre search on the /Movies on the web

0220- Now i am working on adding a rating property  to the Movie model
     Added the ratiing command ie public string? Rating {  get; set; } to the models/Movie.cs
     ran the app.

0255- i have now updated the Bind command in both the create and edit method in /Views/Movies/Index.cshtml
      Also included the Rating label in the SeedData.cs
      Rating = "R" was includded to all the new movies in the SeedData

0320- Error after adding rating, app not working
       Tryingn to figure the error issue with the index. 


2024-06-06
1328
testing agai.. woring now ?