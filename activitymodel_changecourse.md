```mermaid
flowchart TD
  id0([Enter Program]) --> id1
  id1([Present Interface]) --- id2([Student])
  id1 --- id3([Instructor])
  id1 --> id4([Admin])
  id1 --- id5([Other/Exit])
  id4 --- id6([Add Course])
  id4 --- id7([Remove Course])
  id4 --> id8([Add User])
  id4 --> id9([Remove User])
  id4 --> id10([Add Student From Course])
  id4 --> id11([Remove Student From Course])
  id4 --> id12([])
