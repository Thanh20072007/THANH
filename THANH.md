getgenv().Setting = {
    ["Team"] = "Pirates",
    ["Chat"] = {},
    ["Skip Race V4"] = true,
    ["Misc"] = {
        ["Click Delay"] = 1,
        ["Enable Lock Bounty"] = true,
        ["autoboty"] = true,
        ["Lock Bounty"] = {0, 300000000},
        ["Hide Health"] = {4500,5500},
        ["Lock Camera"] = false,
        ["Enable Cam Farm"] = false,
        ["White Screen"] = true,
        ["FPS Boost"] = false,
        ["Bypass TP"] = true,
        ["Random & Store Fruit"] = false,
    },
    ["Item"] = {
        ["Melee"] = {["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 1.5},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0.1}
        },
        ["Blox Fruit"] = {["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 1.2},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["V"] = {["Enable"] = false, ["Hold Time"] = 0},
            ["F"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Sword"] = {["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.1},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1}
        },
        ["Gun"] = {["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0.1},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0.1}
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/NGUYENVUDUY1/Bounty/main/HiruHub.lua"))()
