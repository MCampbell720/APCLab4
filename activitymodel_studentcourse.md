```mermaid
flowchart TD
  id0[/Enter Program\] --> id1
  id1([Present Interface]) --- id5([Other/Exit])
  id1 --- id2([Student])
  id1 --- id3([Instructor])
  id1 --> id4([Admin])
  id2 --> id6([Add/Remove Course])
  id2 --- id8([Check Conflicts in Schedule])
  id2 --- id10([Print Schedule])
  id6 --> id7([Enter Course ID])
  id7 --> id11([Add])
  id7 --> id9([Remove])
