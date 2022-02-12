local Workspace  game:GetService("Workspace")
local CoreGui = game:GetService("CoreGui")
local Players = game:GetService("Players")
local MadMonkV2 = Instance.new("ScreenGui")
local MMFrame = Instance.new("Frame")
local Close = Instance.new("TextButton")
local DL = Instance.new("TextButton")
local DP = Instance.new("TextButton")
local LG = Instance.new("TextButton")
local MH = Instance.new("TextButton")
local ML = Instance.new("TextButton")
local TeleQ = Instance.new("TextButton")
local MMLabel = Instance.new("TextLabel")
local NC = Instance.new("TextButton")

--Properties:

MadMonkV2.Name = "MadMonkV2"
MadMonkV2.Parent = game.CoreGui
MMFrame.Name = "MMFrame"
MMFrame.Active = true
MMFrame.Parent = MadMonkV2
MMFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MMFrame.BackgroundTransparency = 0.750
MMFrame.Position = UDim2.new(0, 0, 0.315294119, 0)
MMFrame.Size = UDim2.new(0, 177, 0, 228)
MMFrame.Draggable = true

Close.Name = "Close"
Close.Parent = MMFrame
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 0.750
Close.Position = UDim2.new(0, 0, 0.893903077, 0)
Close.Size = UDim2.new(0, 177, 0, 27)
Close.Font = Enum.Font.Arcade
Close.Text = "CLOSE MENU"
Close.TextColor3 = Color3.fromRGB(255,0,0)
Close.TextSize = 14.000
Close.MouseButton1Click:connect(function()
MMFrame:Destroy()
end)

DL.Name = "DL"
DL.Parent = MMFrame
DL.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DL.BackgroundTransparency = 0.750
DL.Position = UDim2.new(-0.0013315359, 0, 0.36134089, 0)
DL.Size = UDim2.new(0, 177, 0, 24)
DL.Font = Enum.Font.Arcade
DL.Text = "TurkOyuncu99"
DL.TextColor3 = Color3.fromRGB(0, 0, 0)
DL.TextSize = 14.000
DL.MouseButton1Click:connect(function()
loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/811e25ec8cfcdaa9ae7026353288783c/raw/4b073a5c1a0a4e2ed7e2304c2e769eb440a371a9/h", true))()
end)

DP.Name = "DP"
DP.Parent = MMFrame
DP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DP.BackgroundTransparency = 0.750
DP.Position = UDim2.new(-0.001299435, 0, 0.450877368, 0)
DP.Size = UDim2.new(0, 177, 0, 27)
DP.Font = Enum.Font.Arcade
DP.Text = "Banana"
DP.TextColor3 = Color3.fromRGB(0, 0, 0)
DP.TextSize = 14.000
DP.MouseButton1Click:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptRUs/Banana/main/BananaChicken.lua",true))()
end)

LG.Name = "LG"
LG.Parent = MMFrame
LG.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LG.BackgroundTransparency = 0.750
LG.Position = UDim2.new(-0.00168181835, 0, 0.750669777, 0)
LG.Size = UDim2.new(0, 177, 0, 28)
LG.Font = Enum.Font.Arcade
LG.Text = "Pulco ESP"
LG.TextColor3 = Color3.fromRGB(0, 0, 0)
LG.TextSize = 14.000

LG.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DevPuclo/ESPpuclo/main/README.md",true))()
end)

MH.Name = "MH"
MH.Parent = MMFrame
MH.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MH.BackgroundTransparency = 0.750
MH.Position = UDim2.new(-3.21008265e-05, 0, 0.251804382, 0)
MH.Size = UDim2.new(0, 177, 0, 28)
MH.Font = Enum.Font.Arcade
MH.Text = "BLACKGAMER1221"
MH.TextColor3 = Color3.fromRGB(0, 0, 0)
MH.TextSize = 14.000
MH.MouseButton1Click:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/bandlans/main/README.md"))()
end)

ML.Name = "ML"
ML.Parent = MMFrame
ML.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ML.BackgroundTransparency = 0.750
ML.Position = UDim2.new(0, 0, 0.152069867, 0)
ML.Size = UDim2.new(0, 177, 0, 21)
ML.Font = Enum.Font.Arcade
ML.Text = "Mad-Lads (TP patch)"
ML.TextColor3 = Color3.fromRGB(0, 0, 0)
ML.TextSize = 14.000
ML.MouseButton1Click:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DevPuclo/Mad-ladsvv7/main/README.md",true))()
end)

TeleQ.Parent = MMFrame
TeleQ.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleQ.BackgroundTransparency = 0.750
TeleQ.Position = UDim2.new(-0.00168182021, 0, 0.550413847, 0)
TeleQ.Size = UDim2.new(0, 177, 0, 27)
TeleQ.Font = Enum.Font.Arcade
TeleQ.Text = "God Mode [sélection]"
TeleQ.TextColor3 = Color3.fromRGB(0, 0, 0)
TeleQ.TextSize = 14.000
TeleQ.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DevPuclo/Choupremev4.1/main/README.md",true))()
end)


MMLabel.Name = "MMLabel"
MMLabel.Parent = MMFrame
MMLabel.BackgroundColor3 = Color3.fromRGB(0, 161, 0)
MMLabel.BackgroundTransparency = 0.850
MMLabel.Position = UDim2.new(-0.000162415585, 0, -0.00081789738, 0)
MMLabel.Size = UDim2.new(0, 177, 0, 27)
MMLabel.Font = Enum.Font.Arcade
MMLabel.Text = "Mode Manager v4.2"
MMLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
MMLabel.TextSize = 14.000

NC.Parent = MMFrame
NC.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NC.BackgroundTransparency = 0.750
NC.Position = UDim2.new(-0.00137052345, 0, 0.651128411, 0)
NC.Size = UDim2.new(0, 177, 0, 27)
NC.Font = Enum.Font.Arcade
NC.Text = "Auto-Rob"
NC.TextColor3 = Color3.fromRGB(0, 0, 0)
NC.TextSize = 12.000
NC.MouseButton1Down:connect(function()
_G.MaxPlayers = 7 -- select the number of players on the server for teleportation
loadstring(game:HttpGet('https://system-exodus.com/scripts/madcity/MadLadsAR.lua',true))()
end)


