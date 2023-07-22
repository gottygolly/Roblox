local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Parent = game.Players.LocalPlayer.PlayerGui

local MainFrame = Instance.new("Frame")
MainFrame.Size = UDim2.new(0.4, 0, 0.4, 0)
MainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
MainFrame.Parent = ScreenGui

local Corner = Instance.new("UICorner")
local Stroke = Instance.new("UIStroke")

Corner:Clone().Parent = MainFrame
local MainFrame_Stroke = Stroke:Clone()
MainFrame_Stroke.Parent = MainFrame
MainFrame_Stroke.Thickness = 5
MainFrame_Stroke.Color = Color3.fromRGB(217, 168, 35)

local MainFrame_Title_Frame = Instance.new("Frame")
MainFrame_Title_Frame.Size = UDim2.new(1, 0, 0.1, 0)
MainFrame_Title_Frame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame_Title_Frame.Position = UDim2.new(0.5, 0, 0.1, 0)
MainFrame_Title_Frame.BackgroundColor3 = Color3.fromRGB(230, 179, 39)
MainFrame_Title_Frame.BorderSizePixel = 0
MainFrame_Title_Frame.Parent = MainFrame

local MainFrame_Title = Instance.new("TextLabel")
MainFrame_Title.Size = UDim2.new(1, 0, 1, 0)
MainFrame_Title.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame_Title.Position = UDim2.new(0.5, 0, 0.5, 0)
MainFrame_Title.BackgroundTransparency = 1
MainFrame_Title.Text = "Title"
MainFrame_Title.TextScaled = true
MainFrame_Title.BorderSizePixel = 0
MainFrame_Title.Parent = MainFrame_Title_Frame

wait(2)
ScreenGui:Destroy()
