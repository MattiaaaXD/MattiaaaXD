local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua%22))()
local Window = Library.CreateLib("FarmerHUB", "Sentinel")
local main = window:NewTab("Main")
    Main = Window:NewTab("Misc")
    MainSection = Main:NewSection("Misc")



    MainSection:NewButton("Godmode-Earth", "Turn the player invincible, cool as fuck", function()
        local Plr = game.Players.LocalPlayer
local GodModeBool = true

game:GetService("RunService").RenderStepped:connect(function()
if  GodModeBool  then
game.Workspace.Touchy.Part.CFrame = Plr.Character.HumanoidRootPart.CFrame + Vector3.new(0,0,1)
if Plr.PlayerGui:FindFirstChild("Popup") then
Plr.PlayerGui.Popup.Enabled = false
end
if not GodModeBool  then
return
end end end)
    end)


    MainSection:NewButton("", "", function()
        qui script
    end)
