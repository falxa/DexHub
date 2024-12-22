local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

local function getRandomColor()
    return Color3.new(math.random(), math.random(), math.random())
end

local function createText()
    local textLabel = Instance.new("TextLabel")
    textLabel.Parent = screenGui
    textLabel.Size = UDim2.new(0, 200, 0, 50)
    textLabel.Position = UDim2.new(math.random(), 0, math.random(), 0)
    textLabel.Text = "เดกซ์น่ารัก"
    textLabel.TextColor3 = getRandomColor()
    textLabel.BackgroundTransparency = 1
    textLabel.Font = Enum.Font.SourceSansBold
    textLabel.TextSize = 24
end

while true do
    createText()
    wait(0.1) 
end
