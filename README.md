-- Gui to Lua
-- Version: 3.2

-- Instances:

local SandhurstExploits = Instance.new("ScreenGui")
local Title = Instance.new("Frame")
local elements = Instance.new("Frame")
local nameTXT = Instance.new("TextLabel")
local JJAmount = Instance.new("TextBox")
local UICorner = Instance.new("UICorner")
local JJStart = Instance.new("ImageButton")
local UICorner_2 = Instance.new("UICorner")
local nameTXT_2 = Instance.new("TextLabel")
local nameTXT_3 = Instance.new("TextLabel")
local ST = Instance.new("ImageButton")
local UICorner_3 = Instance.new("UICorner")
local nameTXT_4 = Instance.new("TextLabel")
local PT = Instance.new("ImageButton")
local UICorner_4 = Instance.new("UICorner")
local nameTXT_5 = Instance.new("TextLabel")
local FORMALS = Instance.new("ImageButton")
local UICorner_5 = Instance.new("UICorner")
local nameTXT_6 = Instance.new("TextLabel")
local underline = Instance.new("Frame")
local title = Instance.new("TextButton")

--Properties:

SandhurstExploits.Name = "SandhurstExploits"
SandhurstExploits.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
SandhurstExploits.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Title.Name = "Title"
Title.Parent = SandhurstExploits
Title.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.00584593136, 0, 0.00941909291, 0)
Title.Size = UDim2.new(0.24248302, 0, 0.0368188508, 0)

elements.Name = "elements"
elements.Parent = Title
elements.BackgroundColor3 = Color3.fromRGB(34, 32, 34)
elements.BorderSizePixel = 0
elements.Position = UDim2.new(0, 0, 1.08000016, 0)
elements.Size = UDim2.new(1, 0, 12.8641777, 0)

nameTXT.Name = "nameTXT"
nameTXT.Parent = elements
nameTXT.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT.BackgroundTransparency = 1.000
nameTXT.Position = UDim2.new(0, 0, 0.0217658877, 0)
nameTXT.Selectable = true
nameTXT.Size = UDim2.new(1, 0, 0.116927594, 0)
nameTXT.Font = Enum.Font.GothamSemibold
nameTXT.Text = "AUTO JUMPING JACKS"
nameTXT.TextColor3 = Color3.fromRGB(255, 255, 255)
nameTXT.TextSize = 20.000

JJAmount.Name = "JJAmount"
JJAmount.Parent = elements
JJAmount.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
JJAmount.BorderSizePixel = 0
JJAmount.Position = UDim2.new(0.0439999998, 0, 0.159147322, 0)
JJAmount.Size = UDim2.new(0.899999976, 0, 0.134839475, 0)
JJAmount.Font = Enum.Font.SourceSans
JJAmount.PlaceholderColor3 = Color3.fromRGB(34, 32, 34)
JJAmount.PlaceholderText = "Amount of JJs"
JJAmount.Text = ""
JJAmount.TextColor3 = Color3.fromRGB(255, 255, 255)
JJAmount.TextScaled = true
JJAmount.TextSize = 14.000
JJAmount.TextWrapped = true

UICorner.Parent = JJAmount

JJStart.Name = "JJStart"
JJStart.Parent = elements
JJStart.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
JJStart.Position = UDim2.new(0.243999943, 0, 0.34514451, 0)
JJStart.Size = UDim2.new(0.499140143, 0, 0.0709365383, 0)
JJStart.ZIndex = 2
JJStart.ImageColor3 = Color3.fromRGB(0, 255, 140)
JJStart.ImageTransparency = 1.000

UICorner_2.CornerRadius = UDim.new(0, 4)
UICorner_2.Parent = JJStart

nameTXT_2.Name = "nameTXT"
nameTXT_2.Parent = JJStart
nameTXT_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_2.BackgroundTransparency = 1.000
nameTXT_2.Position = UDim2.new(-0.00400000066, 0, 0, 0)
nameTXT_2.Selectable = true
nameTXT_2.Size = UDim2.new(1, 0, 1, 0)
nameTXT_2.Font = Enum.Font.GothamSemibold
nameTXT_2.Text = "START"
nameTXT_2.TextColor3 = Color3.fromRGB(53, 49, 49)
nameTXT_2.TextSize = 20.000
nameTXT_2.TextWrapped = true

nameTXT_3.Name = "nameTXT"
nameTXT_3.Parent = elements
nameTXT_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_3.BackgroundTransparency = 1.000
nameTXT_3.Position = UDim2.new(0, 0, 0.491286784, 0)
nameTXT_3.Selectable = true
nameTXT_3.Size = UDim2.new(1, 0, 0.116927594, 0)
nameTXT_3.Font = Enum.Font.GothamSemibold
nameTXT_3.Text = "UNIFORM"
nameTXT_3.TextColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_3.TextSize = 20.000

ST.Name = "ST"
ST.Parent = elements
ST.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
ST.Position = UDim2.new(0.0736621842, 0, 0.621881962, 0)
ST.Size = UDim2.new(0.389477879, 0, 0.0709365383, 0)
ST.ZIndex = 2
ST.ImageColor3 = Color3.fromRGB(0, 255, 140)
ST.ImageTransparency = 1.000

UICorner_3.CornerRadius = UDim.new(0, 4)
UICorner_3.Parent = ST

nameTXT_4.Name = "nameTXT"
nameTXT_4.Parent = ST
nameTXT_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_4.BackgroundTransparency = 1.000
nameTXT_4.Position = UDim2.new(-0.00400000066, 0, 0, 0)
nameTXT_4.Selectable = true
nameTXT_4.Size = UDim2.new(1, 0, 1, 0)
nameTXT_4.Font = Enum.Font.GothamSemibold
nameTXT_4.Text = "ST"
nameTXT_4.TextColor3 = Color3.fromRGB(53, 49, 49)
nameTXT_4.TextSize = 20.000
nameTXT_4.TextWrapped = true

PT.Name = "PT"
PT.Parent = elements
PT.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
PT.Position = UDim2.new(0.515999913, 0, 0.618772626, 0)
PT.Size = UDim2.new(0.389477879, 0, 0.0709365383, 0)
PT.ZIndex = 2
PT.ImageColor3 = Color3.fromRGB(0, 255, 140)
PT.ImageTransparency = 1.000

UICorner_4.CornerRadius = UDim.new(0, 4)
UICorner_4.Parent = PT

nameTXT_5.Name = "nameTXT"
nameTXT_5.Parent = PT
nameTXT_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_5.BackgroundTransparency = 1.000
nameTXT_5.Position = UDim2.new(-0.00400000066, 0, 0, 0)
nameTXT_5.Selectable = true
nameTXT_5.Size = UDim2.new(1, 0, 1, 0)
nameTXT_5.Font = Enum.Font.GothamSemibold
nameTXT_5.Text = "PT"
nameTXT_5.TextColor3 = Color3.fromRGB(53, 49, 49)
nameTXT_5.TextSize = 20.000
nameTXT_5.TextWrapped = true

FORMALS.Name = "FORMALS"
FORMALS.Parent = elements
FORMALS.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
FORMALS.Position = UDim2.new(0.217662185, 0, 0.743148983, 0)
FORMALS.Size = UDim2.new(0.5614779, 0, 0.0709365383, 0)
FORMALS.ZIndex = 2
FORMALS.ImageColor3 = Color3.fromRGB(0, 255, 140)
FORMALS.ImageTransparency = 1.000

UICorner_5.CornerRadius = UDim.new(0, 4)
UICorner_5.Parent = FORMALS

nameTXT_6.Name = "nameTXT"
nameTXT_6.Parent = FORMALS
nameTXT_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_6.BackgroundTransparency = 1.000
nameTXT_6.Position = UDim2.new(-0.00400000066, 0, 0, 0)
nameTXT_6.Selectable = true
nameTXT_6.Size = UDim2.new(1, 0, 1, 0)
nameTXT_6.Font = Enum.Font.GothamSemibold
nameTXT_6.Text = "FORMALS"
nameTXT_6.TextColor3 = Color3.fromRGB(53, 49, 49)
nameTXT_6.TextSize = 20.000
nameTXT_6.TextWrapped = true

underline.Name = "underline"
underline.Parent = Title
underline.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
underline.BorderSizePixel = 0
underline.Position = UDim2.new(0, 0, 1, 0)
underline.Size = UDim2.new(1, 0, 0.0799999982, 0)

title.Name = "title"
title.Parent = Title
title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
title.BackgroundTransparency = 1.000
title.Size = UDim2.new(1, 0, 1, 0)
title.Font = Enum.Font.GothamBold
title.Text = "SANDHURST EXPLOITS"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextSize = 20.000

-- Scripts:

local function VQWYBSG_fake_script() -- Title.close 
	local script = Instance.new('LocalScript', Title)

	local close = script.Parent.title
	
	close.MouseButton1Click:Connect(function()
		script.Parent.elements.Visible = not script.Parent.elements.Visible
	end)
end
coroutine.wrap(VQWYBSG_fake_script)()
local function KTDY_fake_script() -- SandhurstExploits.JJ 
	local script = Instance.new('LocalScript', SandhurstExploits)

	game.Players.LocalPlayer.PlayerGui.SandhurstExploits.Title.elements.JJStart.MouseButton1Click:Connect(function()
		local AmountOfJJs = game.Players.LocalPlayer.PlayerGui.SandhurstExploits.Title.elements.JJAmount.Text
		local TimeBetweenMessages = 1 -- must be at least 2.5 to avoid chat limiter
	
		local JJtype = "JJ" -- This can be "JJ" Jumping Jacks, "HJ" Hell Jacks, or "PJ" Phonetic Jacks
	
		inverse_units = {
			"VIGINTILLION ",     -- 10^63
			"NOVEMDECILLION ",   -- 10^60
			"OCTODECILLION ",    -- 10^57
			"SEPTENDECILLION ",  -- 10^54
			"SECDECILLION ",     -- 10^51
			"QUINDECILLION ",    -- 10^48
			"QUATTUORDECILLION ",-- 10^45
			"TREDECILLION ",     -- 10^42
			"DUODECILLION ",    -- 10^39
			"UNDECILLION ",     -- 10^36
			"DECILLION ",       -- 10^33
			"NONILLION ",       -- 10^30
			"OCTILLION ",       -- 10^27
			"SEPTILLION ",      -- 10^24
			"SEXTILLION ",      -- 10^21
			"QUINTILLION ",     -- 10^18
			"QUADRILLION ",     -- 10^15
			"TRILLION ",        -- 10^12
			"BILLION ",         -- 10^9
			"MILLION ",         -- 10^6
			"THOUSAND ",        -- 10^3
		}
		inverse_numbers = {
			"ONE ",
			"TWO ",
			"THREE ",
			"FOUR ",
			"FIVE ",
			"SIX ",
			"SEVEN ",
			"EIGHT ",
			"NINE ",
			"TEN ",
			"ELEVEN ",
			"TWELVE ",
			"THIRTEEN ",
			"FOURTEEN ",
			"FIFTEEN ",
			"SIXTEEN ",
			"SEVENTEEN ",
			"EIGHTEEN ",
			"NINETEEN ",
			"TWENTY ",
			[30] = "THIRTY ",
			[40] = "FORTY ",
			[50] = "FIFTY ",
			[60] = "SIXTY ",
			[70] = "SEVENTY ",
			[80] = "EIGHTY ",
			[90] = "NINETY ",
		}
		phonetics = {
			["A"] = "ALFA",
			["B"] = "BRAVO",
			["C"] = "CHARLIE",
			["D"] = "DELTA",
			["E"] = "ECHO",
			["F"] = "FOXTROT",
			["G"] = "GOLF",
			["H"] = "HOTEL",
			["I"] = "INDIA",
			["J"] = "JULIETT",
			["K"] = "KILO",
			["L"] = "LIMA",
			["M"] = "MIKE",
			["N"] = "NOVEMBER",
			["O"] = "OSCAR",
			["P"] = "PAPA",
			["Q"] = "QUEBEC",
			["R"] = "ROMEO",
			["S"] = "SIERRA",
			["T"] = "TANGO",
			["U"] = "UNIFORM",
			["V"] = "VICTOR",
			["W"] = "WHISKEY",
			["X"] = "X-RAY",
			["Y"] = "YANKEE",
			["Z"] = "ZULU",
		}
	
		function ConvertNumToWords(n)
			local s = tostring(n)
			local c = string.match (s, "%D")
			if c then
				return nil, "Non-numeric digit '" .. c .. "' in number"
			end
			if #s == 0 then
				return nil, "No number supplied"
			elseif #s > 66 then
				return nil, "Number too big to convert to words"
			end 
			while #s % 3 > 0 do
				s = "0" .. s
			end 
			local result = ""
			local start = #inverse_units - (#s / 3) + 2
	
			for i = start, #inverse_units do
				local group = tonumber(string.sub (s, 1, 3))
				if group > 0 then
					result = result .. ConvertTo999 (group) .. inverse_units [i]
				end
				s = string.sub(s, 4)    
			end
			result = result .. ConvertTo999(tonumber (s))
			if result == "" then
				result = "ZERO"
			end
			return (string.gsub(result, " +$", ""))
		end
	
		function ConvertTo999(n)
			if n <= 0 then
				return ""
			end
	
			local hundreds = math.floor(n / 100)
			local tens = math.floor(n % 100)
			local result = ""  
	
			if hundreds > 0 then
				result = inverse_numbers[hundreds] .. "HUNDRED "
				if tens == 0 then
					return result
				end 
	
				result = result .. "AND "
	
			end 
	
			if tens <= 20 then
				return result .. inverse_numbers[tens] 
			end
	
			result = result .. inverse_numbers[math.floor(tens / 10) * 10] 
	
			local digits = math.floor(n % 10)
	
			if digits > 0 then
				result = result ..  inverse_numbers [digits]
			end
	
			return result
		end
	
		function sendChatMessage(msg)
			game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(msg,"All")
		end
	
		local Humanoid = game.Players.LocalPlayer.Character.Humanoid
		if JJtype == "JJ" then
			for i=1,AmountOfJJs do
				sendChatMessage(ConvertNumToWords(i))
				Humanoid.Jump = true
				wait(TimeBetweenMessages)
				if not Humanoid then return end
			end
		elseif JJtype == "HJ" then
			for i=1,AmountOfJJs do
				local thisWord = ConvertNumToWords(i)
				for i=1,string.len(thisWord) do
					sendChatMessage(string.sub(thisWord,i,i))
					Humanoid.Jump = true
					wait(TimeBetweenMessages)
					if not Humanoid then return end
				end
				sendChatMessage(thisWord)
				Humanoid.Jump = true
				wait(TimeBetweenMessages)
				if not Humanoid then return end
			end
		elseif JJtype == "PJ" then
			for i=1,AmountOfJJs do
				local thisWord = ConvertNumToWords(i)
				local ActualMessage = ""
				for i=1,string.len(thisWord) do
					if i > 1 then
						ActualMessage = ActualMessage.. " "
					end
					local thisLetter = string.sub(thisWord,i,i)
					local thisPhonetic = phonetics[thisLetter]
					ActualMessage = ActualMessage.. thisPhonetic
				end
				sendChatMessage(ActualMessage)
				Humanoid.Jump = true
				wait(TimeBetweenMessages)
				if not Humanoid then return end
			end
		end
	end)
end
coroutine.wrap(KTDY_fake_script)()
