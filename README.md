--[[
	 Gui to Lua Converter
-- Revamped by:Choupreme
--]]



-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local TextButton_8 = Instance.new("TextButton")
local TextButton_9 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Frame2 = Instance.new("Frame")
local TextButton_10 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")


--[[
	Properties:
--]]

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0383211672, 0, 0.0656063631, 0)
Frame.Size = UDim2.new(0.0994525552, 0, 0.0337972157, 0)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton.BackgroundTransparency = 1
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.854838729, 0, 0, 0)
TextButton.Size = UDim2.new(0.145161286, 0, 1, 0)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.Text = "-"
TextButton.TextColor3 = Color3.new(1, 1, 1)
TextButton.TextScaled = true
TextButton.TextSize = 14
TextButton.TextWrapped = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.Font = Enum.Font.SourceSansLight
TextLabel.Text = "Script séléction v6"
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextScaled = False 
TextLabel.TextSize = 22
TextLabel.TextWrapped = true

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame_2.BorderColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 1.00900004, 0)
Frame_2.Size = UDim2.new(1, 0, 6.1800001, 0)

TextButton_2.Parent = Frame_2
TextButton_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_2.BackgroundTransparency = 1
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0, 0, 0.0272358228, 0)
TextButton_2.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_2.Font = Enum.Font.SourceSansLight
TextButton_2.Text = "TurkOyuncu99"
TextButton_2.TextColor3 = Color3.new(1, 1, 1)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 16
TextButton_2.TextWrapped = true
TextButton_2.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/811e25ec8cfcdaa9ae7026353288783c/raw/4b073a5c1a0a4e2ed7e2304c2e769eb440a371a9/h", true))()
end)


TextButton_3.Parent = Frame_2
TextButton_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_3.BackgroundTransparency = 1
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0, 0, 0.148021415, 0)
TextButton_3.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_3.Font = Enum.Font.SourceSansLight
TextButton_3.Text = "TR1V5"
TextButton_3.TextColor3 = Color3.new(1, 1, 1)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 16
TextButton_3.TextWrapped = true
TextButton_3.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/tr1vvvv/main/README.md",true))()
end)

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_4.BackgroundTransparency = 1
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0, 0, 0.268807083, 0)
TextButton_4.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_4.Font = Enum.Font.SourceSansLight
TextButton_4.Text = "BLACKGAMER1221"
TextButton_4.TextColor3 = Color3.new(1, 1, 1)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 16
TextButton_4.TextWrapped = true
TextButton_4.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/bandlans/main/README.md"))()
end)

TextButton_5.Parent = Frame_2
TextButton_5.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_5.BackgroundTransparency = 1
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0, 0, 0.389592737, 0)
TextButton_5.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_5.Font = Enum.Font.SourceSansLight
TextButton_5.Text = "Ruby Hub V1.3"
TextButton_5.TextColor3 = Color3.new(1, 1, 1)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 16
TextButton_5.TextWrapped = true
TextButton_5.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/Ruby/main/README.md",true))()
end)

TextButton_6.Parent = Frame_2
TextButton_6.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_6.BackgroundTransparency = 1
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0, 0, 0.51037842, 0)
TextButton_6.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_6.Font = Enum.Font.SourceSansLight
TextButton_6.Text = "Marco8642"
TextButton_6.TextColor3 = Color3.new(1, 1, 1)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 16
TextButton_6.TextWrapped = true
TextButton_6.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/Carsall/main/README.md"))()
end)

TextButton_7.Parent = Frame_2
TextButton_7.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_7.BackgroundTransparency = 1
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0, 0, 0.631163955, 0)
TextButton_7.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_7.Font = Enum.Font.SourceSansLight
TextButton_7.Text = "Hoho | Hub"
TextButton_7.TextColor3 = Color3.new(1, 1, 1)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 16
TextButton_7.TextWrapped = true
TextButton_7.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/trico/main/README.md",true))() 
end)


TextButton_8.Parent = Frame_2
TextButton_8.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_8.BackgroundTransparency = 1
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0, 0, 0.751949549, 0)
TextButton_8.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_8.Font = Enum.Font.SourceSansLight
TextButton_8.Text = "ESP synapse"
TextButton_8.TextColor3 = Color3.new(1, 1, 1)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 16
TextButton_8.TextWrapped = true
TextButton_8.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/ESPpuclo/main/README.md",true))()
end)


TextButton_9.Parent = Frame_2
TextButton_9.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_9.BackgroundTransparency = 1
TextButton_9.BorderSizePixel = 0
TextButton_9.Position = UDim2.new(0, 0, 0.879840255, 0)
TextButton_9.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_9.Font = Enum.Font.SourceSansLight
TextButton_9.Text = "Auto-Rob"
TextButton_9.TextColor3 = Color3.new(1, 1, 1)
TextButton_9.TextScaled = true
TextButton_9.TextSize = 16
TextButton_9.TextWrapped = true
TextButton_9.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://system-exodus.com/scripts/madcity/MadLadsAR.lua",true))()
end)


TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.new(1, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 1, 0)
TextLabel_2.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel_2.ZIndex = 5
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = ""
TextLabel_2.TextColor3 = Color3.new(0, 0, 0)
TextLabel_2.TextSize = 14

--[[
	 Scripts:
--]]

local function DAUB_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Text == "-" then
			script.Parent.Text = "+"
			script.Parent.Parent.Frame:TweenSize(UDim2.new(1, 0,0, 0),"In","Quint",0.5)
		elseif
			script.Parent.Text == "+" then
				script.Parent.Text = "-"
				script.Parent.Parent.Frame:TweenSize(UDim2.new(1, 0,6.15, 0),"Out","Quint",0.5)
		end
	end)
end
coroutine.wrap(DAUB_fake_script)()
local function MOBT_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
	
	end)
end
