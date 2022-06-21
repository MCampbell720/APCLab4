```mermaid
flowchart TD
  id0[/Enter Program\] --> id1
  id1([Present Interface]) --- id5([Other/Exit])
  id1 --- id2([Student])
  id1 --- id3([Instructor])
  id1 --> id4([Admin])
  id4 --> id6([Add/Remove Course])
  id4 --- id8([Add/Remove Instructor])
  id4 --- id10([Add/Remove Student])
  id4 --- id12([Assign User to Course])
  id6 --> ida([Add])
  id6 --> idb([Remove])
  ida --> idc([Enter Course Number])
  idb --> idc
