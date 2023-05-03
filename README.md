# Roblox-Data-System
Quick and easy data system for roblox

All functions are:
DATA.SaveData(player, key, value)
DATA.GetData(player, key, fallback)

Examples of these functions:
DATA.SaveData(player, "Coins", 100)
print(DATA.GetData(player, "Coins", 0))

DATA.SaveData(player, "Name", 100)
print("Players name is "..DATA.GetData(player, "Name").."!")

https://www.roblox.com/library/13333836317/Advanced-Data-Store
