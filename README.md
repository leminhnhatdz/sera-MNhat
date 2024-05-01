getgenv().config = {
    ["Team"] = "Marines",
    ["Use Race"] = {
        ["V3"] = true,
        ["V4"] = true
    },
    ["Info Screen"] = true,
    ["White Screen"] = false,
    ["BypassTp"] = true,
    ["SkipFruit"] = {
        "Portal-Portal"
    },
    ["Skip Race V4 User"] = false,
    ["MainSkillToggle"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1.5,
                },
                [ "X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Blox Fruit"] = {
            ["Enable"] =true,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["V"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
                ["F"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Gun"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        }
    },
    ["Webhooks"] = {
        ["Link Webhook"] = "https://discord.com/api/webhooks/1205388446055800922/RaXmDGB-oIdikwQYnwnuUm849ByqL0HqNZK8PxJobSfV_ILWUvZleyDU8KdpYgu25oOE",
        ["Toggle Webhook"] = true
    },
    ["ChatSpam"] = {"Sera Hub On Top", "No Skill? Using SeraHub"},
    ["MinBountyHunt"] = 0,
    ["MaxBountyHunt"] = 30000000,
    ["SafeHealth"] = 5500
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/LumosSera/SeraHub/main/AutoBounty.lua"))()
