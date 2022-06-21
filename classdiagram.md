```mermaid
classDiagram
  User <|-- Student
  User <|-- Instructor
  User <|-- Admin
  User : +String FName
  User : +String Lname
  User : +Int ID
  User: +login()
  User: +logout()
  User: +searchforcourse()
  class Student{
     +String FName
     +String LName
     +int ID
     +addcourse()
     +removecourse()
     +checkconflicts()
     +printschedule()
  }
  class Instructor{
     +String FName
     +String LName
     +int ID
    +printschedule()
    +print/searchroster()
  }
  class Admin{
     +String FName
     +String LName
     +int ID
     +addcourse()
     +removecourse()
     +addinstructor()
     +removeinstructor()
     +linkinstructor()
     +unlinkinstructor()
  }
