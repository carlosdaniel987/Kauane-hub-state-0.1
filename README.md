-- carregar biblioteca
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

-- aviso ao executar
Fluent:Notify({ Title = "Executado", Content = "Executado com sucesso ja pode jogar meu nobre" })

local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Exemplo Básico",
    Size = UDim2.fromOffset(400, 300),
    Theme = "Light"
})
SaveManager:SetLibrary(Fluent)
InterfaceManager:SetLibrary(Fluent)

local MainTab = Window:AddTab({ Title = "Principal" })

MainTab:AddButton({
    Title = "Clique-me",
    Callback = function()
        print("Botão clicado")
    end
})

local Slider = MainTab:AddSlider("Volume", {
    Title = "Ajuste o Volume",
    Min = 0, Max = 100, Default = 50
})

Slider:OnChanged(function(Value)
    print("Volume ajustado para:", Value)
end)

Fluent:Notify({
    Title = "Bem-vindo",
    Content = "Interface carregada com sucesso!"
})

Window:SelectTab(1)
Fluent:Notify({ Title = "kauane hub", Content = "Bom estar tudo certo seu script foi executado." })

SaveManager:SetLibrary(Fluent)
InterfaceManager:SetLibrary(Fluent)

local Window = Fluent:CreateWindow({
    Title = "KAUANE♥️" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "BLUE"
})

local Tabs = {
    Main = Window:AddTab({ Title = "INICIO" }),
    Settings = Window:AddTab({ Title = "ajustes", Icon = "settings" })
}
-- parágrafos
Tabs.Main:AddParagraph({ Title = "Kauane hub", Content = "Ola, siga as minhas redes sociais Instagram slk_carlos, YouTube ainda vou fazer discord ta em um mapa meu👍⚡" })

-- botões
Tabs.Main:AddButton({ Title = "DISCORD", Callback = function() https://discord.com/channels/1264665405662695516/1264665405662695520 end })
Tabs.Main:AddButton({ Title = "YOUTUBE", Callback = function() https://www.youtube.com/@Carlhub end })
Tabs.Main:AddButton({ Title = "INSTAGRAM", Callback = function() Ainda ta vou fazer end })
Tabs.Main:AddButton({ Title = "Rael hub op", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")() end})
Tabs.Main:AddButton({ Title = "speed wave", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/speedwavevip/scriptspeed/refs/heads/main/Brookhaven_lraq"))() end })
Tabs.Main:AddButton({ Title = "BROOKHAVEN", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))() end })
Tabs.Main:AddButton({ Title = "EQ CARL", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/eQA4nfcw"))() end })
Tabs.Main:AddButton({ Title = "CENTRAL BR", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md",true))() end })
Tabs.Main:AddButton({ Title = "SANDER X CARL", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))() end })
Tabs.Main:AddButton({ Title = "G HUB CARL", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() end })
Tabs.Main:AddButton({ Title = "CARL HUB OLD", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md")() end })
