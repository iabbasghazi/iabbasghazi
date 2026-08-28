import os
import time

# Terminal clear
os.system("cls" if os.name == "nt" else "clear")

red = "\033[91m"
dark_red = "\033[31m"
white = "\033[97m"
reset = "\033[0m"

logo = f"""
{dark_red}████████╗ ██████╗ ██╗  ██╗██╗ ██████╗
╚══██╔══╝██╔═══██╗╚██╗██╔╝██║██╔════╝
   ██║   ██║   ██║ ╚███╔╝ ██║██║
   ██║   ██║   ██║ ██╔██╗ ██║██║
   ██║   ╚██████╔╝██╔╝ ██╗██║╚██████╗
   ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝ ╚═════╝
{reset}
"""

subtitle = f"""
{red}        A FAIRYTALE FOR GROWN-UPS{reset}
"""

# Cinematic fade-in effect
for line in logo.splitlines():
    print(line)
    time.sleep(0.08)

time.sleep(0.5)

for char in subtitle:
    print(char, end="", flush=True)
    time.sleep(0.03)

print("\n")
time.sleep(1)

print(f"{white}              ⚠ TOXIC ⚠{reset}")
print()
