while wait() do
    for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
        if v.Name == "Stun" or v.Name == "CombatStun" then
             v:Destroy()
        end
    end
end
