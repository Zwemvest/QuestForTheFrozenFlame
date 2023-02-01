[[Xiat]] Basic Rotation:


```mermaid
graph
  1["Turn 1:</br>Move✰</br>Spellstrike✰✰"];
  2["Turn 2:</br>Cast a Focus spell/Refresh spellstrike✰</br>Arcane Cascade✰</br>Move/Raise a shield/Attack✰"];
  3a["Turn 3a:</br>Move/Raise a Shield✰</br>Spellstrike✰✰"]
  3b["Turn 3c:</br>Move/Raise a Shield/Attack✰</br>Cast a Focus spell/Refresh Spellstrike✰"]
  3c["Turn 3b:</br>Cast a Focus spell/Refresh your spellstrike✰</br>Spellstrike✰✰"]
  1 --> 2;
  2 --> 3a;
  3a --> 3b;
  3b --> 3a;
  3c --> 3c;
  3a --> 3c;
  3c --> 3b;

linkStyle default stroke-width:2px,fill:none,stroke:gray;
```

Explained:   
Turn 1: Move+Spellstrike.  
Turn 2: Refresh Spellstrike, enter Arcane Cascade, move/attack  
Alternate between 3A and 3C.  
You can fit in 3B in between when you do not need to move/raise a shield.  
Remember: do you not need to raise a shield when you cast your focus spell.  