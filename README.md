-- Gui to Lua
-- Version: 3.2

Sound = Instance.new("Sound", game:GetService("Workspace")) -- ตรงนี้ไม่ต้องไปสน นาจา ;0;
Sound.Name = "Mrbeast" -- ชื่อเสียง \;
Sound.SoundId = "rbxassetid://658625769" -- เลขขขขขเสียง ;/
Sound.Looped = false -- วนลูป :>
Sound.Playing = true -- เล่นเสียง :<
Sound.Volume = 1 -- ระดับเสียงงงงงงง ;-;

-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")

--Properties:
ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabel.Parent = ScreenGui
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.0540265031, 0, 0.0507936515, 0)
ImageLabel.Size = UDim2.new(0, 892, 0, 543)
ImageLabel.Image = "http://www.roblox.com/asset/?id=10111107769"
wait(3)
game.CoreGui:FindFirstChild("ScreenGui"):Destroy()
