-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Title = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Toolbar = Instance.new("Frame")
local Scripts = Instance.new("TextButton")
local Options = Instance.new("TextButton")
local ListLayout = Instance.new("UIListLayout")
local Backdrop = Instance.new("ImageLabel")
local Pages = Instance.new("Frame")
local Scripts_2 = Instance.new("Frame")
local Character = Instance.new("Frame")
local Elements = Instance.new("ImageLabel")
local TextButton = Instance.new("TextButton")
local Icon = Instance.new("ImageLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UIGridLayout = Instance.new("UIGridLayout")
local UIPadding = Instance.new("UIPadding")
local Label = Instance.new("ImageLabel")
local Title_2 = Instance.new("TextLabel")
local Mechanical = Instance.new("Frame")
local Elements_2 = Instance.new("ImageLabel")
local UIGridLayout_2 = Instance.new("UIGridLayout")
local UIPadding_2 = Instance.new("UIPadding")
local Label_2 = Instance.new("ImageLabel")
local Title_3 = Instance.new("TextLabel")
local Aesthetic = Instance.new("Frame")
local Elements_3 = Instance.new("ImageLabel")
local UIGridLayout_3 = Instance.new("UIGridLayout")
local UIPadding_3 = Instance.new("UIPadding")
local Label_3 = Instance.new("ImageLabel")
local Title_4 = Instance.new("TextLabel")
local Weapon = Instance.new("Frame")
local Elements_4 = Instance.new("ImageLabel")
local UIGridLayout_4 = Instance.new("UIGridLayout")
local UIPadding_4 = Instance.new("UIPadding")
local Label_4 = Instance.new("ImageLabel")
local Title_5 = Instance.new("TextLabel")
local Utility = Instance.new("Frame")
local Elements_5 = Instance.new("ImageLabel")
local UIGridLayout_5 = Instance.new("UIGridLayout")
local UIPadding_5 = Instance.new("UIPadding")
local Reset = Instance.new("TextButton")
local Icon_2 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local Replicate = Instance.new("TextButton")
local Icon_3 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local Flip = Instance.new("TextButton")
local Icon_4 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local Tools = Instance.new("TextButton")
local Icon_5 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local Noclip = Instance.new("TextButton")
local Icon_6 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local Block = Instance.new("TextButton")
local Icon_7 = Instance.new("ImageLabel")
local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
local Label_5 = Instance.new("ImageLabel")
local Title_6 = Instance.new("TextLabel")
local Container = Instance.new("Frame")
local Elements_6 = Instance.new("ImageLabel")
local UIGridLayout_6 = Instance.new("UIGridLayout")
local UIPadding_6 = Instance.new("UIPadding")
local Label_6 = Instance.new("ImageLabel")
local Title_7 = Instance.new("TextLabel")
local Container_2 = Instance.new("Frame")
local Elements_7 = Instance.new("ImageLabel")
local UIGridLayout_7 = Instance.new("UIGridLayout")
local UIPadding_7 = Instance.new("UIPadding")
local Label_7 = Instance.new("ImageLabel")
local Title_8 = Instance.new("TextLabel")
local UIPageLayout = Instance.new("UIPageLayout")
local Options_2 = Instance.new("Frame")

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
TextLabel.Text = "Replication UI"
TextLabel.TextColor3 = Color3.fromRGB(79, 79, 79)
TextLabel.TextSize = 14.000

Toolbar.Name = "Toolbar"
Toolbar.Parent = Frame
Toolbar.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Toolbar.BorderSizePixel = 0
Toolbar.Position = UDim2.new(0, 0, 0, 23)
Toolbar.Size = UDim2.new(1, 0, 0, 32)
Toolbar.ZIndex = 2

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

Options.Name = "Options"
Options.Parent = Toolbar
Options.BackgroundColor3 = Color3.fromRGB(236, 109, 17)
Options.BorderSizePixel = 0
Options.LayoutOrder = 1
Options.Size = UDim2.new(0, 70, 1, 0)
Options.AutoButtonColor = false
Options.Font = Enum.Font.SourceSans
Options.Text = "Options"
Options.TextColor3 = Color3.fromRGB(255, 255, 255)
Options.TextSize = 18.000

ListLayout.Name = "ListLayout"
ListLayout.Parent = Toolbar
ListLayout.FillDirection = Enum.FillDirection.Horizontal
ListLayout.SortOrder = Enum.SortOrder.LayoutOrder
ListLayout.VerticalAlignment = Enum.VerticalAlignment.Center

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

Character.Name = "Character"
Character.Parent = Scripts_2
Character.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Character.BackgroundTransparency = 0.999
Character.Size = UDim2.new(0, 162, 0, 130)

Elements.Name = "Elements"
Elements.Parent = Character
Elements.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements.BackgroundTransparency = 1.000
Elements.Position = UDim2.new(0, 0, 0, 10)
Elements.Size = UDim2.new(1, 0, 1, -10)
Elements.Image = "rbxassetid://3069858933"
Elements.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements.ScaleType = Enum.ScaleType.Slice
Elements.SliceCenter = Rect.new(210, 210, 210, 210)
Elements.SliceScale = 0.010

TextButton.Parent = Elements
TextButton.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
TextButton.BorderSizePixel = 0
TextButton.Size = UDim2.new(1, -5, 0, 10)
TextButton.AutoButtonColor = false
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Label Text"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 15.000

Icon.Name = "Icon"
Icon.Parent = TextButton
Icon.AnchorPoint = Vector2.new(0, 0.5)
Icon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon.BackgroundTransparency = 1.000
Icon.Position = UDim2.new(0, 3, 0.5, 0)
Icon.Size = UDim2.new(0, 25, 0, 25)
Icon.Image = "rbxgameasset://Images/octo"

UIAspectRatioConstraint.Parent = Icon

UIGridLayout.Parent = Elements
UIGridLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding.Parent = Elements
UIPadding.PaddingBottom = UDim.new(0, 5)
UIPadding.PaddingLeft = UDim.new(0, 5)
UIPadding.PaddingRight = UDim.new(0, 5)
UIPadding.PaddingTop = UDim.new(0, 10)

Label.Name = "Label"
Label.Parent = Character
Label.AnchorPoint = Vector2.new(0.5, 0)
Label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label.BackgroundTransparency = 1.000
Label.Position = UDim2.new(0.5, 0, 0, 0)
Label.Size = UDim2.new(0, 75, 0, 20)
Label.Image = "rbxassetid://3069858933"
Label.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label.ScaleType = Enum.ScaleType.Slice
Label.SliceCenter = Rect.new(210, 210, 210, 210)
Label.SliceScale = 0.010

Title_2.Name = "Title"
Title_2.Parent = Label
Title_2.AnchorPoint = Vector2.new(0, 0.5)
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Position = UDim2.new(0, 0, 0.5, 0)
Title_2.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_2.Font = Enum.Font.SourceSansSemibold
Title_2.Text = "Character"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

Mechanical.Name = "Mechanical"
Mechanical.Parent = Scripts_2
Mechanical.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Mechanical.BackgroundTransparency = 0.999
Mechanical.Position = UDim2.new(0, 0, 0.44884488, 0)
Mechanical.Size = UDim2.new(0, 162, 0, 165)

Elements_2.Name = "Elements"
Elements_2.Parent = Mechanical
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
UIGridLayout_2.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding_2.Parent = Elements_2
UIPadding_2.PaddingBottom = UDim.new(0, 5)
UIPadding_2.PaddingLeft = UDim.new(0, 5)
UIPadding_2.PaddingRight = UDim.new(0, 5)
UIPadding_2.PaddingTop = UDim.new(0, 10)

Label_2.Name = "Label"
Label_2.Parent = Mechanical
Label_2.AnchorPoint = Vector2.new(0.5, 0)
Label_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_2.BackgroundTransparency = 1.000
Label_2.Position = UDim2.new(0.5, 0, 0, 0)
Label_2.Size = UDim2.new(0, 80, 0, 20)
Label_2.Image = "rbxassetid://3069858933"
Label_2.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_2.ScaleType = Enum.ScaleType.Slice
Label_2.SliceCenter = Rect.new(210, 210, 210, 210)
Label_2.SliceScale = 0.010

Title_3.Name = "Title"
Title_3.Parent = Label_2
Title_3.AnchorPoint = Vector2.new(0, 0.5)
Title_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_3.BackgroundTransparency = 1.000
Title_3.Position = UDim2.new(0, 0, 0.5, 0)
Title_3.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_3.Font = Enum.Font.SourceSansSemibold
Title_3.Text = "Mechanical"
Title_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_3.TextScaled = true
Title_3.TextSize = 14.000
Title_3.TextWrapped = true

Aesthetic.Name = "Aesthetic"
Aesthetic.Parent = Scripts_2
Aesthetic.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Aesthetic.BackgroundTransparency = 0.999
Aesthetic.Position = UDim2.new(0.25490424, 0, 0, 0)
Aesthetic.Size = UDim2.new(0, 162, 0, 162)

Elements_3.Name = "Elements"
Elements_3.Parent = Aesthetic
Elements_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_3.BackgroundTransparency = 1.000
Elements_3.Position = UDim2.new(0, 0, 0, 10)
Elements_3.Size = UDim2.new(1, 0, 1, -10)
Elements_3.Image = "rbxassetid://3069858933"
Elements_3.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_3.ScaleType = Enum.ScaleType.Slice
Elements_3.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_3.SliceScale = 0.010

UIGridLayout_3.Parent = Elements_3
UIGridLayout_3.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_3.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding_3.Parent = Elements_3
UIPadding_3.PaddingBottom = UDim.new(0, 5)
UIPadding_3.PaddingLeft = UDim.new(0, 5)
UIPadding_3.PaddingRight = UDim.new(0, 5)
UIPadding_3.PaddingTop = UDim.new(0, 10)

Label_3.Name = "Label"
Label_3.Parent = Aesthetic
Label_3.AnchorPoint = Vector2.new(0.5, 0)
Label_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_3.BackgroundTransparency = 1.000
Label_3.Position = UDim2.new(0.5, 0, 0, 0)
Label_3.Size = UDim2.new(0, 75, 0, 20)
Label_3.Image = "rbxassetid://3069858933"
Label_3.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_3.ScaleType = Enum.ScaleType.Slice
Label_3.SliceCenter = Rect.new(210, 210, 210, 210)
Label_3.SliceScale = 0.010

Title_4.Name = "Title"
Title_4.Parent = Label_3
Title_4.AnchorPoint = Vector2.new(0, 0.5)
Title_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_4.BackgroundTransparency = 1.000
Title_4.Position = UDim2.new(0, 0, 0.5, 0)
Title_4.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_4.Font = Enum.Font.SourceSansSemibold
Title_4.Text = "Aesthetic"
Title_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_4.TextScaled = true
Title_4.TextSize = 14.000
Title_4.TextWrapped = true

Weapon.Name = "Weapon"
Weapon.Parent = Scripts_2
Weapon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Weapon.BackgroundTransparency = 0.999
Weapon.Position = UDim2.new(0.2549043, 0, 0.554455459, 0)
Weapon.Size = UDim2.new(0, 162, 0, 133)

Elements_4.Name = "Elements"
Elements_4.Parent = Weapon
Elements_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_4.BackgroundTransparency = 1.000
Elements_4.Position = UDim2.new(0, 0, 0, 10)
Elements_4.Size = UDim2.new(1, 0, 1, -10)
Elements_4.Image = "rbxassetid://3069858933"
Elements_4.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_4.ScaleType = Enum.ScaleType.Slice
Elements_4.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_4.SliceScale = 0.010

UIGridLayout_4.Parent = Elements_4
UIGridLayout_4.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_4.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding_4.Parent = Elements_4
UIPadding_4.PaddingBottom = UDim.new(0, 5)
UIPadding_4.PaddingLeft = UDim.new(0, 5)
UIPadding_4.PaddingRight = UDim.new(0, 5)
UIPadding_4.PaddingTop = UDim.new(0, 10)

Label_4.Name = "Label"
Label_4.Parent = Weapon
Label_4.AnchorPoint = Vector2.new(0.5, 0)
Label_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_4.BackgroundTransparency = 1.000
Label_4.Position = UDim2.new(0.5, 0, 0, 0)
Label_4.Size = UDim2.new(0, 67, 0, 20)
Label_4.Image = "rbxassetid://3069858933"
Label_4.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_4.ScaleType = Enum.ScaleType.Slice
Label_4.SliceCenter = Rect.new(210, 210, 210, 210)
Label_4.SliceScale = 0.010

Title_5.Name = "Title"
Title_5.Parent = Label_4
Title_5.AnchorPoint = Vector2.new(0, 0.5)
Title_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_5.BackgroundTransparency = 1.000
Title_5.Position = UDim2.new(0, 0, 0.5, 0)
Title_5.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_5.Font = Enum.Font.SourceSansSemibold
Title_5.Text = "Weapon"
Title_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_5.TextScaled = true
Title_5.TextSize = 14.000
Title_5.TextWrapped = true

Utility.Name = "Utility"
Utility.Parent = Scripts_2
Utility.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Utility.BackgroundTransparency = 0.999
Utility.Position = UDim2.new(0.509808481, 0, 0, 0)
Utility.Size = UDim2.new(0, 324, 0, 124)

Elements_5.Name = "Elements"
Elements_5.Parent = Utility
Elements_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_5.BackgroundTransparency = 1.000
Elements_5.Position = UDim2.new(0, 0, 0, 10)
Elements_5.Size = UDim2.new(1, 0, 1, -10)
Elements_5.Image = "rbxassetid://3069858933"
Elements_5.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_5.ScaleType = Enum.ScaleType.Slice
Elements_5.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_5.SliceScale = 0.010

UIGridLayout_5.Parent = Elements_5
UIGridLayout_5.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_5.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_5.CellSize = UDim2.new(0, 154, 0, 30)

UIPadding_5.Parent = Elements_5
UIPadding_5.PaddingBottom = UDim.new(0, 5)
UIPadding_5.PaddingLeft = UDim.new(0, 5)
UIPadding_5.PaddingRight = UDim.new(0, 5)
UIPadding_5.PaddingTop = UDim.new(0, 10)

Reset.Name = "Reset"
Reset.Parent = Elements_5
Reset.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Reset.BorderSizePixel = 0
Reset.Size = UDim2.new(1, -5, 0, 10)
Reset.AutoButtonColor = false
Reset.Font = Enum.Font.SourceSans
Reset.Text = "Reset Character"
Reset.TextColor3 = Color3.fromRGB(255, 255, 255)
Reset.TextSize = 15.000

Icon_2.Name = "Icon"
Icon_2.Parent = Reset
Icon_2.AnchorPoint = Vector2.new(0, 0.5)
Icon_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_2.BackgroundTransparency = 1.000
Icon_2.Position = UDim2.new(0, 3, 0.5, 0)
Icon_2.Size = UDim2.new(0, 25, 0, 25)
Icon_2.Image = "rbxassetid://3070539754"

UIAspectRatioConstraint_2.Parent = Icon_2

Replicate.Name = "Replicate"
Replicate.Parent = Elements_5
Replicate.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Replicate.BorderSizePixel = 0
Replicate.Size = UDim2.new(1, -5, 0, 10)
Replicate.AutoButtonColor = false
Replicate.Font = Enum.Font.SourceSans
Replicate.Text = "Replicate (0)"
Replicate.TextColor3 = Color3.fromRGB(255, 255, 255)
Replicate.TextSize = 15.000

Icon_3.Name = "Icon"
Icon_3.Parent = Replicate
Icon_3.AnchorPoint = Vector2.new(0, 0.5)
Icon_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_3.BackgroundTransparency = 1.000
Icon_3.Position = UDim2.new(0, 3, 0.5, 0)
Icon_3.Size = UDim2.new(0, 25, 0, 25)
Icon_3.Image = "rbxassetid://3070539679"

UIAspectRatioConstraint_3.Parent = Icon_3

Flip.Name = "Flip"
Flip.Parent = Elements_5
Flip.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Flip.BorderSizePixel = 0
Flip.LayoutOrder = 1
Flip.Size = UDim2.new(1, -5, 0, 10)
Flip.AutoButtonColor = false
Flip.Font = Enum.Font.SourceSans
Flip.Text = "Flip Axes"
Flip.TextColor3 = Color3.fromRGB(255, 255, 255)
Flip.TextSize = 15.000

Icon_4.Name = "Icon"
Icon_4.Parent = Flip
Icon_4.AnchorPoint = Vector2.new(0, 0.5)
Icon_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_4.BackgroundTransparency = 1.000
Icon_4.Position = UDim2.new(0, 3, 0.5, 0)
Icon_4.Size = UDim2.new(0, 25, 0, 25)
Icon_4.Image = "rbxassetid://3070554149"

UIAspectRatioConstraint_4.Parent = Icon_4

Tools.Name = "Tools"
Tools.Parent = Elements_5
Tools.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Tools.BorderSizePixel = 0
Tools.LayoutOrder = 1
Tools.Size = UDim2.new(1, -5, 0, 10)
Tools.AutoButtonColor = false
Tools.Font = Enum.Font.SourceSans
Tools.Text = "Load Tools"
Tools.TextColor3 = Color3.fromRGB(255, 255, 255)
Tools.TextSize = 15.000

Icon_5.Name = "Icon"
Icon_5.Parent = Tools
Icon_5.AnchorPoint = Vector2.new(0, 0.5)
Icon_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_5.BackgroundTransparency = 1.000
Icon_5.Position = UDim2.new(0, 3, 0.5, 0)
Icon_5.Size = UDim2.new(0, 25, 0, 25)
Icon_5.Image = "rbxassetid://3070606748"

UIAspectRatioConstraint_5.Parent = Icon_5

Noclip.Name = "Noclip"
Noclip.Parent = Elements_5
Noclip.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Noclip.BorderSizePixel = 0
Noclip.LayoutOrder = 1
Noclip.Size = UDim2.new(1, -5, 0, 10)
Noclip.AutoButtonColor = false
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "No Collision"
Noclip.TextColor3 = Color3.fromRGB(255, 255, 255)
Noclip.TextSize = 15.000

Icon_6.Name = "Icon"
Icon_6.Parent = Noclip
Icon_6.AnchorPoint = Vector2.new(0, 0.5)
Icon_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_6.BackgroundTransparency = 1.000
Icon_6.Position = UDim2.new(0, 3, 0.5, 0)
Icon_6.Size = UDim2.new(0, 25, 0, 25)
Icon_6.Image = "rbxassetid://3070583479"

UIAspectRatioConstraint_6.Parent = Icon_6

Block.Name = "Block"
Block.Parent = Elements_5
Block.BackgroundColor3 = Color3.fromRGB(255, 112, 17)
Block.BorderSizePixel = 0
Block.LayoutOrder = 1
Block.Size = UDim2.new(1, -5, 0, 10)
Block.AutoButtonColor = false
Block.Font = Enum.Font.SourceSans
Block.Text = "Remove Mesh"
Block.TextColor3 = Color3.fromRGB(255, 255, 255)
Block.TextSize = 15.000

Icon_7.Name = "Icon"
Icon_7.Parent = Block
Icon_7.AnchorPoint = Vector2.new(0, 0.5)
Icon_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon_7.BackgroundTransparency = 1.000
Icon_7.Position = UDim2.new(0, 3, 0.5, 0)
Icon_7.Size = UDim2.new(0, 25, 0, 25)
Icon_7.Image = "rbxassetid://3070572535"

UIAspectRatioConstraint_7.Parent = Icon_7

Label_5.Name = "Label"
Label_5.Parent = Utility
Label_5.AnchorPoint = Vector2.new(0.5, 0)
Label_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_5.BackgroundTransparency = 1.000
Label_5.Position = UDim2.new(0.5, 0, 0, 0)
Label_5.Size = UDim2.new(0, 51, 0, 20)
Label_5.Image = "rbxassetid://3069858933"
Label_5.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_5.ScaleType = Enum.ScaleType.Slice
Label_5.SliceCenter = Rect.new(210, 210, 210, 210)
Label_5.SliceScale = 0.010

Title_6.Name = "Title"
Title_6.Parent = Label_5
Title_6.AnchorPoint = Vector2.new(0, 0.5)
Title_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_6.BackgroundTransparency = 1.000
Title_6.Position = UDim2.new(0, 0, 0.5, 0)
Title_6.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_6.Font = Enum.Font.SourceSansSemibold
Title_6.Text = "Utility"
Title_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_6.TextScaled = true
Title_6.TextSize = 14.000
Title_6.TextWrapped = true

Container.Name = "Container"
Container.Parent = Scripts_2
Container.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Container.BackgroundTransparency = 0.999
Container.Position = UDim2.new(0.50829792, 0, 0.429042906, 0)
Container.Size = UDim2.new(0, 162, 0, 171)

Elements_6.Name = "Elements"
Elements_6.Parent = Container
Elements_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_6.BackgroundTransparency = 1.000
Elements_6.Position = UDim2.new(0, 0, 0, 10)
Elements_6.Size = UDim2.new(1, 0, 1, -10)
Elements_6.Image = "rbxassetid://3069858933"
Elements_6.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_6.ScaleType = Enum.ScaleType.Slice
Elements_6.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_6.SliceScale = 0.010

UIGridLayout_6.Parent = Elements_6
UIGridLayout_6.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_6.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding_6.Parent = Elements_6
UIPadding_6.PaddingBottom = UDim.new(0, 5)
UIPadding_6.PaddingLeft = UDim.new(0, 5)
UIPadding_6.PaddingRight = UDim.new(0, 5)
UIPadding_6.PaddingTop = UDim.new(0, 10)

Label_6.Name = "Label"
Label_6.Parent = Container
Label_6.AnchorPoint = Vector2.new(0.5, 0)
Label_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_6.BackgroundTransparency = 1.000
Label_6.Position = UDim2.new(0.5, 0, 0, 0)
Label_6.Size = UDim2.new(0, 75, 0, 20)
Label_6.Image = "rbxassetid://3069858933"
Label_6.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_6.ScaleType = Enum.ScaleType.Slice
Label_6.SliceCenter = Rect.new(210, 210, 210, 210)
Label_6.SliceScale = 0.010

Title_7.Name = "Title"
Title_7.Parent = Label_6
Title_7.AnchorPoint = Vector2.new(0, 0.5)
Title_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_7.BackgroundTransparency = 1.000
Title_7.Position = UDim2.new(0, 0, 0.5, 0)
Title_7.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_7.Font = Enum.Font.SourceSansSemibold
Title_7.Text = "nothing!!"
Title_7.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_7.TextScaled = true
Title_7.TextSize = 14.000
Title_7.TextWrapped = true

Container_2.Name = "Container"
Container_2.Parent = Scripts_2
Container_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Container_2.BackgroundTransparency = 0.999
Container_2.Position = UDim2.new(0.760563731, 0, 0.429042906, 0)
Container_2.Size = UDim2.new(0, 158, 0, 171)

Elements_7.Name = "Elements"
Elements_7.Parent = Container_2
Elements_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Elements_7.BackgroundTransparency = 1.000
Elements_7.Position = UDim2.new(0, 0, 0, 10)
Elements_7.Size = UDim2.new(1, 0, 1, -10)
Elements_7.Image = "rbxassetid://3069858933"
Elements_7.ImageColor3 = Color3.fromRGB(48, 48, 48)
Elements_7.ScaleType = Enum.ScaleType.Slice
Elements_7.SliceCenter = Rect.new(210, 210, 210, 210)
Elements_7.SliceScale = 0.010

UIGridLayout_7.Parent = Elements_7
UIGridLayout_7.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_7.CellSize = UDim2.new(0, 150, 0, 30)

UIPadding_7.Parent = Elements_7
UIPadding_7.PaddingBottom = UDim.new(0, 5)
UIPadding_7.PaddingLeft = UDim.new(0, 5)
UIPadding_7.PaddingRight = UDim.new(0, 5)
UIPadding_7.PaddingTop = UDim.new(0, 10)

Label_7.Name = "Label"
Label_7.Parent = Container_2
Label_7.AnchorPoint = Vector2.new(0.5, 0)
Label_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_7.BackgroundTransparency = 1.000
Label_7.Position = UDim2.new(0.5, 0, 0, 0)
Label_7.Size = UDim2.new(0, 75, 0, 20)
Label_7.Image = "rbxassetid://3069858933"
Label_7.ImageColor3 = Color3.fromRGB(48, 48, 48)
Label_7.ScaleType = Enum.ScaleType.Slice
Label_7.SliceCenter = Rect.new(210, 210, 210, 210)
Label_7.SliceScale = 0.010

Title_8.Name = "Title"
Title_8.Parent = Label_7
Title_8.AnchorPoint = Vector2.new(0, 0.5)
Title_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_8.BackgroundTransparency = 1.000
Title_8.Position = UDim2.new(0, 0, 0.5, 0)
Title_8.Size = UDim2.new(1, 0, 0.800000012, 0)
Title_8.Font = Enum.Font.SourceSansSemibold
Title_8.Text = "nothing??"
Title_8.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_8.TextScaled = true
Title_8.TextSize = 14.000
Title_8.TextWrapped = true

UIPageLayout.Parent = Pages
UIPageLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIPageLayout.EasingStyle = Enum.EasingStyle.Quint
UIPageLayout.Padding = UDim.new(0, 25)
UIPageLayout.TweenTime = 0.500

Options_2.Name = "Options"
Options_2.Parent = Pages
Options_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Options_2.BackgroundTransparency = 1.000
Options_2.BorderSizePixel = 0
Options_2.LayoutOrder = 1
Options_2.Size = UDim2.new(1, 0, 1, 0)

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


-- Scripts:

local function KWDI_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	
end
coroutine.wrap(KWDI_fake_script)()
