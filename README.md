THIS ONLY CAN USE ON PC
U CAN CHANGE THE SEC TO MIN e.g.
function sleep (a) 
    local sec = tonumber(os.clock() + a); 
    while (os.clock() < sec) do 
    end 
end
TO
function sleep (a) 
    local min = tonumber(os.clock() + a); 
    while (os.clock() < sec) do 
    end 
end
