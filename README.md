-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabel.Parent = ScreenGui
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(-0.081249997, 0, -0.070866093, 0)
ImageLabel.Size = UDim2.new(0, 1798, 0, 865)
ImageLabel.Image = "http://www.roblox.com/asset/?id=6995787089"

TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Position = UDim2.new(0.372883856, 0, 0.757480323, 0)
TextLabel.SelectionImageObject = ImageLabel
TextLabel.Size = UDim2.new(0, 323, 0, 110)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Nice balls"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true
