## create a window
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/slf0Dev/Goat-poop/main/Windows%2010%20UI%20Library"))()

-- Creating Gui
local MainWindow = Library.Main("GuiName","KeyBind")
```
## create category
```lua
local Category = MainWindow.Category("Your Text","ImageId","ImageScaleType",Image Transparency)


--[[
ImageScaleTypes : "Crop" , "Fit" , "Slice" , "Stretch"
]]
```

## create a folder
```lua
local Folder = Category.Folder("TemplateFolder")
```

## create label
```lua
local Label = Folder.Label("Your Text")
```
## create button
```lua
local Button = Folder.Button("Your Text",function()
    print("Pressed")
end)
```
## create toggle
```lua
local Toggle = Folder.Toggle("Your Text",function(bool)
print(bool)
end,DefaultBoolValue)
```
## create slider
```lua
local Slider = Folder.Slider("Your Text",min,max,function(value)
print(value)
end,DefaultValue,isFloat) --isFloat is boolean
```
