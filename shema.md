## stateDiagram-v2
  ### [*] --> q0
  ### q0 --> q1 : a → X, R
  ### q1 --> q1 : a → a, R
  ### q1 --> q2 : b → Y, R
  ### q2 --> q2 : b → b, R
  ### q2 --> q3 : c → Z, L
  ### q3 --> q3 : b → b, L; Y → Y, L; a → a, L
  ### q3 --> q0 : X → X, R
  ### q0 --> q4 : Y → Y, R
  ### q4 --> q4 : Y → Y, R; Z → Z, R
  ### q4 --> q_accept : ☐ → ☐, —
   ### q_reject --> [*]
