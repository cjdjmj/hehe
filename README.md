-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Title = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Toolbar = Instance.new("Frame")
local ListLayout = Instance.new("UIListLayout")
local Scripts = Instance.new("TextButton")
local Backdrop = Instance.new("ImageLabel")
local Pages = Instance.new("Frame")
local Scripts_2 = Instance.new("Frame")
local Mechanical = Instance.new("Frame")
local Elements = Instance.new("ImageLabel")
local UIGridLayout = Instance.new("UIGridLayout")
local UIPadding = Instance.new("UIPadding")
local Utility = Instance.new("Frame")
local Elements_2 = Instance.new("ImageLabel")
local UIGridLayout_2 = Instance.new("UIGridLayout")
local UIPadding_2 = Instance.new("UIPadding")
local Reset = Instance.new("TextButton")
local Icon = Instance.new("ImageLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Replicate = Instance.new("TextButton")
local Icon_2 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UIPageLayout = Instance.new("UIPageLayout")
local Options = Instance.new("Frame")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Frame.BorderColor3 = Color3.fromRGB(239, 99, 6)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(0, 671, 0, 366)

Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Title.BorderSizePixel = 0
Title.Size = UDim2.new(1, 0, 0, 23)
Title.ZIndex = 2

TextLabel.Parent = Title
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "gamesx this is a ui lib so stfu please"
TextLabel.TextColor3 = Color3.fromRGB(79, 79, 79)
TextLabel.TextSize = 14.000

Toolbar.Name = "Toolbar"
Toolbar.Parent = Frame
Toolbar.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Toolbar.BorderSizePixel = 0
Toolbar.Position = UDim2.new(0, 0, 0, 23)
Toolbar.Size = UDim2.new(1, 0, 0, 32)
Toolbar.ZIndex = 2

ListLayout.Name = "ListLayout"
ListLayout.Parent = Toolbar
ListLayout.FillDirection = Enum.FillDirection.Horizontal
ListLayout.SortOrder = Enum.SortOrder.LayoutOrder
ListLayout.VerticalAlignment = Enum.VerticalAlignment.Center

Scripts.Name = "Scripts"
Scripts.Parent = Toolbar
Scripts.BackgroundColor3 = Color3.fromRGB(255, 118, 26)
Scripts.BorderSizePixel = 0
Scripts.Size = UDim2.new(0, 70, 1, 0)
Scripts.AutoButtonColor = false
Scripts.Font = Enum.Font.SourceSansBold
Scripts.Text = "Scripts"
Scripts.TextColor3 = Color3.fromRGB(255, 255, 255)
Scripts.TextSize = 18.000

Backdrop.Name = "Backdrop"
Backdrop.Parent = Frame
Backdrop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Backdrop.BackgroundTransparency = 1.000
Backdrop.Size = UDim2.new(1, 0, 1, 0)
Backdrop.Image = "rbxassetid://3069759312"
Backdrop.ImageTransparency = 0.980
Backdrop.ScaleType = Enum.ScaleType.Tile
Backdrop.TileSize = UDim2.new(0, 325, 0, 325)

Pages.Name = "Pages"
Pages.Parent = Frame
Pages.AnchorPoint = Vector2.new(0.5, 0.5)
Pages.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Pages.BackgroundTransparency = 0.999
Pages.ClipsDescendants = true
Pages.Position = UDim2.new(0.500745177, 0, 0.573770463, 0)
Pages.Size = UDim2.new(1, -9, 1, -63)

Scripts_2.Name = "Scripts"
Scripts_2.Parent = Pages
Scripts_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Scripts_2.BackgroundTransparency = 1.000
Scripts_2.BorderSizePixel = 0
Scripts_2.Size = UDim2.new(1, 0, 1, 0)

Mechanical.Name = "Mechanical"
Mechanical.Parent = Scripts_2
Mechanical.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Mechanical.BackgroundTransparency = 0.999
Mechanical.Position = UDim2.new(0.253776431, 0, 0.0330033004, 0)
Mechanical.Size = UDim2.new(0, 162, 0, 165)

Elements.Name = "Elements"
Elements.Parent = Mechanical
Elements.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements.BackgroundTransparency = 1.000
Elements.Position = UDim2.new(-0.0370370448, 0, -0.0181818008, 0)
Elements.Size = UDim2.new(1, 0, 1.0363636, -10)
Elements.Image = "rbxassetid://3069858933"
Elements.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements.ScaleType = Enum.ScaleType.Slice
Elements.SliceCenter = Rect.new(210, 210, 210, 210)
Elements.SliceScale = 0.010

UIGridLayout.Parent = Elements
UIGridLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding.Parent = Elements
UIPadding.PaddingBottom = UDim.new(0, 5)
UIPadding.PaddingLeft = UDim.new(0, 5)
UIPadding.PaddingRight = UDim.new(0, 5)
UIPadding.PaddingTop = UDim.new(0, 10)

Utility.Name = "Utility"
Utility.Parent = Scripts_2
Utility.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Utility.BackgroundTransparency = 0.999
Utility.Position = UDim2.new(0.509808481, 0, 0, 0)
Utility.Size = UDim2.new(0, 324, 0, 124)

Elements_2.Name = "Elements"
Elements_2.Parent = Utility
Elements_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_2.BackgroundTransparency = 1.000
Elements_2.Position = UDim2.new(0, 0, 0, 10)
Elements_2.Size = UDim2.new(1, 0, 1, -10)
Elements_2.Image = "rbxassetid://3069858933"
Elements_2.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_2.ScaleType = Enum.ScaleType.Slice
Elements_2.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_2.SliceScale = 0.010

UIGridLayout_2.Parent = Elements_2
UIGridLayout_2.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_2.CellSize = UDim2.new(0, 154, 0, 30)

UIPadding_2.Parent = Elements_2
UIPadding_2.PaddingBottom = UDim.new(0, 5)
UIPadding_2.PaddingLeft = UDim.new(0, 5)
UIPadding_2.PaddingRight = UDim.new(0, 5)
UIPadding_2.PaddingTop = UDim.new(0, 10)

Reset.Name = "Reset"
Reset.Parent = Elements_2
Reset.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Reset.BorderSizePixel = 0
Reset.Size = UDim2.new(1, -5, 0, 10)
Reset.AutoButtonColor = false
Reset.Font = Enum.Font.SourceSans
Reset.Text = "Buy Bugers"
Reset.TextColor3 = Color3.fromRGB(255, 255, 255)
Reset.TextSize = 15.000

Icon.Name = "Icon"
Icon.Parent = Reset
Icon.AnchorPoint = Vector2.new(0, 0.5)
Icon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon.BackgroundTransparency = 1.000
Icon.Position = UDim2.new(0, 3, 0.5, 0)
Icon.Size = UDim2.new(0, 25, 0, 25)
Icon.Image = "rbxassetid://3070539754"

UIAspectRatioConstraint.Parent = Icon

Replicate.Name = "Replicate"
Replicate.Parent = Elements_2
Replicate.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Replicate.BorderSizePixel = 0
Replicate.Size = UDim2.new(1, -5, 0, 10)
Replicate.AutoButtonColor = false
Replicate.Font = Enum.Font.SourceSans
Replicate.Text = "Replicate (0)"
Replicate.TextColor3 = Color3.fromRGB(255, 255, 255)
Replicate.TextSize = 15.000

Icon_2.Name = "Icon"
Icon_2.Parent = Replicate
Icon_2.AnchorPoint = Vector2.new(0, 0.5)
Icon_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_2.BackgroundTransparency = 1.000
Icon_2.Position = UDim2.new(0, 3, 0.5, 0)
Icon_2.Size = UDim2.new(0, 25, 0, 25)
Icon_2.Image = "rbxassetid://3070539679"

UIAspectRatioConstraint_2.Parent = Icon_2

UIPageLayout.Parent = Pages
UIPageLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIPageLayout.EasingStyle = Enum.EasingStyle.Quint
UIPageLayout.Padding = UDim.new(0, 25)
UIPageLayout.TweenTime = 0.500

Options.Name = "Options"
Options.Parent = Pages
Options.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Options.BackgroundTransparency = 1.000
Options.BorderSizePixel = 0
Options.LayoutOrder = 1
Options.Size = UDim2.new(1, 0, 1, 0)

-- Module Scripts:

local fake_module_scripts = {}

do -- ScreenGui.GuiLib
	local script = Instance.new('ModuleScript', ScreenGui)
	script.Name = "GuiLib"
	local function module_script()
		local methods = {}
		local player = game:GetService("Players").LocalPlayer
		local mouse = player:GetMouse()
		
		methods.relativePosition = function(guiObject, x, y)
			local z = guiObject.AbsolutePosition
			return UDim2.new(0, x - z.X, 0, y - z.Y)
		end
		
		methods.multColor3 = function(color3, delta)
			return Color3.new(
				math.clamp(color3.r*delta, 0, 1), 
				math.clamp(color3.g*delta, 0, 1), 
				math.clamp(color3.b*delta, 0, 1)
			)
		end
		
		methods.tween = function(object,style,direction,t,goal)
		    local tweenservice = game:GetService("TweenService")
		    local tweenInfo = TweenInfo.new(t,Enum.EasingStyle[style],Enum.EasingDirection[direction])
		    local tween = tweenservice:Create(object,tweenInfo,goal)
		    tween:Play()
		    return tween
		end
		
		methods.bindButton = function(button, func)
			button.MouseButton1Click:Connect(func)
		end
		
		methods.colorInteractive = function(guiObject)
			local origin = guiObject.BackgroundColor3
			local hover = methods.multColor3(origin, 1.2)
			local press = methods.multColor3(origin, 0.8)
			guiObject.MouseEnter:Connect(function()
				methods.tween(guiObject, "Sine", "Out", .5, {
					BackgroundColor3 = hover
				})
			end)
			guiObject.MouseLeave:Connect(function()
				methods.tween(guiObject, "Sine", "Out", .5, {
					BackgroundColor3 = origin
				})
			end)
			guiObject.MouseButton1Down:Connect(function()
				methods.tween(guiObject, "Sine", "Out", .3, {
					BackgroundColor3 = press
				})
			end)
			guiObject.MouseButton1Up:Connect(function()
				methods.tween(guiObject, "Sine", "Out", .4, {
					BackgroundColor3 = hover
				})
			end)
		end
		
		methods.circleInteractive = function(guiObject, delta, duration)
			guiObject.ClipsDescendants = true
			guiObject.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 then
					local circle = Instance.new("ImageLabel", guiObject)
					circle.BackgroundTransparency = 1
					circle.ImageTransparency = 0.7
					circle.AnchorPoint = Vector2.new(.5,.5)
					circle.Position = methods.relativePosition(circle, mouse.X, mouse.Y)
					circle.Image = "rbxassetid://232918622"
					circle.Size = UDim2.new(0, 0, 0, 0)
					
					local aspectRatio = Instance.new("UIAspectRatioConstraint", circle)
					
					local size = guiObject.AbsoluteSize.X
					if guiObject.AbsoluteSize.Y > size then size = guiObject.AbsoluteSize.Y end
					
					methods.tween(circle, "Sine", "Out", duration or 1.5, {
						Size = UDim2.new(0, size * (delta or 1), 0, size * (delta or 1)),
						ImageTransparency = 1
					})
					
					wait(duration or 1.5)
					circle:Destroy()
				end
			end)
		end
		
		methods.draggable = function(ui, dragui)
			if not dragui then dragui = ui end
			local UserInputService = game:GetService("UserInputService")
			
			local dragging
			local dragInput
			local dragStart
			local startPos
			
			local function update(input)
				local delta = input.Position - dragStart
				ui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
			end
			
			dragui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = ui.Position
					
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
			
			dragui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
			
			UserInputService.InputChanged:Connect(function(input)
				if input == dragInput and dragging then
					update(input)
				end
			end)
		end
		
		return methods
	end
	fake_module_scripts[script] = module_script
end
