local function fetch(url)
    local ok, res = pcall(function()
        return game:HttpGet(url)
    end)

    return ok and res or nil
end

local scripts = {
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar1.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar2.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar3.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar4.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar5.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar6.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar7.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar8.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar9.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar10.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar11.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar12.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar13.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar14.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar15.lua",
    "https://raw.githubusercontent.com/ItsLunarHub/LunarHubLT2/main/Lunar16.lua",
}

for _, url in ipairs(scripts) do
    local content = fetch(url)

    if content then
        local func = loadstring(content)

        if func then
            task.spawn(func)
        end
    end

    task.wait(0.2)
end
