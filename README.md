-- تشغيل السكربت الأول من مستودع cuddly-goggles
task.spawn(function()
    local success, err = pcall(function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shhd-code/cuddly-goggles/refs/heads/main/README.md"))()
    end)
    if not success then
        warn("فشل تشغيل السكربت الأول: " .. tostring(err))
    end
end)

-- تشغيل السكربت الثاني من مستودع CHat_Sh
task.spawn(function()
    local success, err = pcall(function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shhd-code/CHat_Sh/refs/heads/main/README.md"))()
    end)
    if not success then
        warn("فشل تشغيل السكربت الثاني: " .. tostring(err))
    end
end)
 
