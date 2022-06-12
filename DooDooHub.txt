--Made By RXX
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local InfiniteSpin = Instance.new("TextButton")
local VGHub = Instance.new("TextButton")
local ServerHop = Instance.new("TextButton")
local FatesAdmin = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(255, 164, 32)
main.Position = UDim2.new(0.0183654726, 0, 0.641717792, 0)
main.Size = UDim2.new(0, 462, 0, 268)
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(214, 145, 34)
TextLabel.Size = UDim2.new(0, 462, 0, 70)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = "Doo Doo Hub | RXX#5949"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 29.000

UICorner.Parent = TextLabel

UICorner_2.Parent = main

InfiniteSpin.Name = "Infinite Spin"
InfiniteSpin.Parent = main
InfiniteSpin.BackgroundColor3 = Color3.fromRGB(255, 164, 32)
InfiniteSpin.Position = UDim2.new(0.0411255397, 0, 0.335820884, 0)
InfiniteSpin.Size = UDim2.new(0, 200, 0, 50)
InfiniteSpin.Font = Enum.Font.Roboto
InfiniteSpin.Text = "Inf Spin"
InfiniteSpin.TextColor3 = Color3.fromRGB(0, 0, 0)
InfiniteSpin.TextSize = 20.000
InfiniteSpin.MouseButton1Down:connect(function()
	--v038
	--Update: Updated script 5/22/2022
	--Put the script in autoexec if your exploit have it, free exploits don't usually.

	Credits = [[
    THIS IS CREDITS DON'T TOUCH OR EDIT BECAUSE WITHOUT THIS EXACT CREDITS SCRIPT WON'T WORK
    
    This script actually is actually FREE and it can be found by a faker who releases this script under their name
    without giving credits to me, and making people go through many ads to get it
    or even making it paid, but whole time its free, make sure you get it from the source!
    Where to buy: https://www.tech-brain.net/product-page/shindo-life-infinite-spinning

    List of bloodlines and stuff is in the channel named #bloodline-names, and many
    other steps on how to use the script correctly Discord Server: https://discord.gg/8KqTZVcfCP
    
    The real owner and the creator of this script is Tech Brain#0001
    If you get this script from a fake person, send their info to me at Tech Brain#0001 in the discord
    Discord Server: https://discord.gg/8KqTZVcfCP or discord.io/techbrain
]]

	function GetHttp(URL)
		local returning = nil
		repeat
			pcall(function()
				returning = game:HttpGet(URL,true)
			end)
			if returning == nil then
				warn("Failed to get "..URL)
				wait(0.5)
			end
		until returning ~= nil
		return returning
	end

	got = GetHttp("https://gist.githubusercontent.com/TechyBrain/0cae69c69880daa4355e3c3a46191ae4/raw")
	loadstring(got)()
end)

VGHub.Name = "VG Hub"
VGHub.Parent = main
VGHub.BackgroundColor3 = Color3.fromRGB(255, 164, 32)
VGHub.Position = UDim2.new(0.525974035, 0, 0.335820884, 0)
VGHub.Size = UDim2.new(0, 200, 0, 50)
VGHub.Font = Enum.Font.Roboto
VGHub.Text = "VG Hub"
VGHub.TextColor3 = Color3.fromRGB(0, 0, 0)
VGHub.TextSize = 20.000
VGHub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

ServerHop.Name = "Server Hop"
ServerHop.Parent = main
ServerHop.BackgroundColor3 = Color3.fromRGB(255, 164, 32)
ServerHop.Position = UDim2.new(0.0411255397, 0, 0.671641767, 0)
ServerHop.Size = UDim2.new(0, 200, 0, 50)
ServerHop.Font = Enum.Font.Roboto
ServerHop.Text = "Server Hop"
ServerHop.TextColor3 = Color3.fromRGB(0, 0, 0)
ServerHop.TextSize = 20.000
ServerHop.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://www.scriptblox.com/raw/Server-Browser_80", true))()
end)

FatesAdmin.Name = "Fates Admin"
FatesAdmin.Parent = main
FatesAdmin.BackgroundColor3 = Color3.fromRGB(255, 164, 32)
FatesAdmin.Position = UDim2.new(0.525974035, 0, 0.671641767, 0)
FatesAdmin.Size = UDim2.new(0, 200, 0, 50)
FatesAdmin.Font = Enum.Font.Roboto
FatesAdmin.Text = "Fates Admin"
FatesAdmin.TextColor3 = Color3.fromRGB(0, 0, 0)
FatesAdmin.TextSize = 20.000
FatesAdmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)