#Assignment 1#
##PID: 4060056##
###CEN4072###

b. Cyclomatic Complexity = E - N + 2
Answer = 26 - 20 + 2 = 8

c.

Path 1: 1-2-3-5-6-7-8-16-17-18-19-5-20
Path 2: 1-2-3-5-6-7-8-16-17-19-5-20
Path 3: 1-2-3-5-6-7-9-12-13-15-16-17-18-19-5-20
Path 4: 1-2-3-5-6-7-9-12-14-15-16-17-18-19-5-20
Path 5: 1-2-3-5-6-7-9-12-13-15-16-17-19-5-20
Path 6: 1-2-3-5-6-7-10-16-17-18-19-5-20
Path 7: 1-2-3-5-6-7-10-16-17-19-5-20
Path 8: 1-2-3-5-6-7-11-16-17-18-19-5-20
Path 9: 1-2-3-5-6-7-11-16-17-19-5-20
Path 10: 1-2-4-5-6-7-8-16-17-18-19-5-20
Path 11: 1-2-4-5-6-7-8-16-17-19-5-20
Path 12: 1-2-4-5-6-7-9-12-13-15-16-17-18-19-5-20
Path 13: 1-2-4-5-6-7-9-12-13-15-16-17-19-5-20
Path 14: 1-2-4-5-6-7-9-12-14-15-16-17-18-19-5-20
Path 15: 1-2-4-5-6-7-9-12-14-15-16-17-19-5-20
Path 16: 1-2-4-5-6-7-10-16-17-18-19-5-20
Path 17: 1-2-4-5-6-7-10-16-17-19-5-20
Path 18: 1-2-4-5-6-7-11-16-17-18-19-5-20
Path 19: 1-2-4-5-6-7-11-16-17-19-5-20
Path 20: 1-2-3-5-20
Path 21: 1-2-4-5-20

A | B | C | D | E | F
--- | --- | --- | --- | --- | ---
  Test Case | C1 | C2 | C3 | C4 | C5
  1 | **TRUE** |  **FALSE** | **NA** | **NA** | **NA**
  2 | **FALSE** | **FALSE** | **NA** | **NA** | **NA**
  3 | **TRUE** | **TRUE** | **A** | **NA** | **TRUE**
  4 | **TRUE** | **TRUE** | **A** | **NA** | **FALSE**
  5 | **FALSE** | **TRUE** | **A** | **NA** | **TRUE**
  6 | **FALSE** | **TRUE** | **A** | **NA** | **FALSE**
  7 | **TRUE** | **TRUE** | **B** | **TRUE** | **TRUE**
  8 | **TRUE** | **TRUE** | **B** | **TRUE** | **FALSE**
  9 | **TRUE** | **TRUE** | **B** | **FALSE** | **TRUE**
  10 | **TRUE** | **TRUE** | **B** | **FALSE** | **FALSE**
  11 | **FALSE** | **TRUE** | **B** | **TRUE** | **TRUE**
  12 | **FALSE** | **TRUE** | **B** | **TRUE** | **FALSE**
  13 | **FALSE** | **TRUE** | **B** | **FALSE** | **TRUE**
  14 | **FALSE** | **TRUE** | **B** | **FALSE** | **FALSE**
  15 | **TRUE** | **TRUE** | **C** | **NA** | **TRUE**
  16 | **TRUE** | **TRUE** | **C** | **NA** | **FALSE**
  17 | **FALSE** | **TRUE** | **C** | **NA** | **TRUE**
  18 | **FALSE** | **TRUE** | **C** | **NA** | **FALSE**
  19 | **TRUE** | **TRUE** | **D** | **NA** | **TRUE**
  20 | **TRUE** | **TRUE** | **D** | **NA** | **FALSE**
  21 | **FALSE** | **TRUE** | **D** | **NA** | **TRUE**
  22 | **FALSE** | **TRUE** | **D** | **NA** | **FALSE**
