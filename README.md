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

local gameId = game.PlaceId

if gameId == 2753915549 or gameId == 4442272183 or gameId == 7449423635 then
    -- Blox Fruits
    print("Detectado Blox Fruits, executando script...")
    safeLoad("https://gist.githubusercontent.com/celestialhub551/a541d8dd5cb7382f34c6aacd2d67a162/raw/44671bd0b5a57640a2ec2a772a9461695c1fb7ab/dz%20scripts.lua"))()")
elseif gameId == 10260193230 then
    -- Meme Sea
    print("Detectado arm wrestle, executando script...")
    safeLoad("https://gist.githubusercontent.com/celestialhub551/46c936ae513dbfe54f5d758fc173fcb5/raw/1732b6477eca8a771d00a7542c776ceb72a94940/dz%20scripts.lua"))()")
elseif gameId == 13918861725 then
     print("vc adm?")
     safeLoad("https://raw.githubusercontent.com/Flontium2/SkyLand-Hub/refs/heads/main/Fisch.lua")
else
    print("Jogo não reconhecido. Nenhum script foi executado.")
end
