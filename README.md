game.Players.PlayerAdded:Connect(function(player)
    -- Cria a pasta leaderstats
    local leaderstats = Instance.new("Folder")
    leaderstats.Name = "leaderstats"
    leaderstats.Parent = player

    -- Cria a moeda
    local money = Instance.new("IntValue")
    money.Name = "Coins"
    money.Value = 0
    money.Parent = leaderstats
end)# Levelk
