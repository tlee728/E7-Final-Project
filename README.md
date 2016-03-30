# E7-Final-Project

project
for q = 1:nr
    for w = 1:nc
%       marchers already in their target position stay in same place  
        if target_formation(q,w) == 1 && initial_formation(q,w) ~= 0
            instructions(initial_formation(q,w)).i_target = q;
            instructions(initial_formation(q,w)).j_target = w;
            instructions(initial_formation(q,w)).wait = max_beats;
            instructions(initial_formation(q,w)).direction = '.';
            
            
            
            
            
            
            
            
            
            
