Marc McCully 101190878

Walkthrough Link: https://www.youtube.com/watch?v=mWGfHxhRxJA


Compile and run with Maven

Compile:
  mvn compile
Run: 
  mvn compile exec:java "-Dexec.mainClass=Main"

Project Structure
  Comp3005FinalProject: The Application
    /src/main/java:
      /App: Logic and Views
      /Models: Models mapping entities to database

  docs: Supporting documentation (ER Diagram + Mapping + Normalization + etc)
  

Notes: 
  If it is your first time running the project uncomment the try block in the main class that runs the firstValuesFunction inorder to populate the database. On subsequent runs it should remain commented to not overwrite data by trying to reinsert.

Index: See User class
View: See GroupSessionSummary
Trigger: See SessionJoinTableListener and InvoiceCreator