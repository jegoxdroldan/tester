workspace.__THINGS.__REMOTES.MAIN:FireServer("b", "bank withdraw")
local function Bank(id)
   local self = {}
   function self:withdraw(pets, gems)
local A_1 = 
{
    [1] = id, 
    [2] = 
{
}, 
    [3] = gems
}
        local Event = game:GetService("Workspace")["__THINGS"]["__REMOTES"]["bank withdraw"]
        Event:InvokeServer(A_1)
   end
   return self
end
--//
local bankid = "469299ad-dafd-48b3-8e9f-92658f9bb21d"--bank
local bankid = "469299ad-dafd-48b3-8e9f-92658f9bb21d"--bank
local bankid = "469299ad-dafd-48b3-8e9f-92658f9bb21d"--bank
local bankid = "469299ad-dafd-48b3-8e9f-92658f9bb21d"--bank
local bankid = "469299ad-dafd-48b3-8e9f-92658f9bb21d"--bank

for i=5, 999, 0.1 do
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   Bank(bankid):withdraw({}, 1)
   task.wait(0)
end

--// Variables

local Players = game:GetService("Players")
local OldNameCall = nil

--// Global Variables

getgenv().SendNotifications = true -- Set to true if you want to get notified regularly.

--// Anti Kick Hook

OldNameCall = hookmetamethod(game, "__namecall", function(Self, ...)
    local NameCallMethod = getnamecallmethod()

    if tostring(string.lower(NameCallMethod)) == "kick" then
        if getgenv().SendNotifications == true then
            game:GetService("StarterGui"):SetCore("SendNotification", {
                Title = "Exunys Developer",
                Text = "You almost got kicked! Successfully prevented.",
                Icon = "rbxassetid://6238540373",
                Duration = 3,
            })
        end
        
        return nil
    end
    
    return OldNameCall(Self, ...)
end)

if getgenv().SendNotifications == true then
    game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Exunys Developer",
        Text = "Anti-Kick script loaded",
        Icon = "rbxassetid://6238537240",
        Duration = 5,
    })
end
