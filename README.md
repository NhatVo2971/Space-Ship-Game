###Bare Metal OS – Screen Display & Game Development
##📌 Overview
This project extends a Bare Metal OS with screen display features and a CLI-driven game on Raspberry Pi 3 / QEMU. It demonstrates image rendering, video playback, custom fonts, and basic game mechanics.

##👥 Team 8
Mai Xuan Huy (s3878672)
Hoang Nghia Tri Hung (s3930336)
Truong Phuoc Huy (s3891442)
Vo Phuc Duy Nhat (s3868763)

##✨ Features
Image display with scroll (W/S, exit with X)
Video playback (24 FPS, delay interrupts)
Custom font rendering (bitmap conversion, color support)

##Game development:
#Stage 1: Shoot monsters
<img width="510" height="377" alt="Screenshot 2025-09-28 175922" src="https://github.com/user-attachments/assets/9aa77517-03bf-42e7-9229-1dbc05fd80db" />

#Stage 2: Boss fight with bombs
<img width="570" height="426" alt="Screenshot 2025-09-28 175929" src="https://github.com/user-attachments/assets/425168d3-81a5-4657-a26c-ea9f70a8d096" />

#Pause / Restart / Quit menu
<img width="627" height="474" alt="Screenshot 2025-09-28 175942" src="https://github.com/user-attachments/assets/378553b1-a657-492c-8c6e-8233886b4b49" />

#Score & health system
<img width="191" height="237" alt="Screenshot 2025-09-28 175935" src="https://github.com/user-attachments/assets/041a40d2-749f-42ad-bc98-ca48f8af5aa6" />

##🛠️ Tools & Tech
Languages: C / C++
Platform: Raspberry Pi 3, QEMU Emulator
Tools: image2cpp, ezgif (video-to-frames)
Concepts: Frame Buffer, CLI interaction, Bitmap rendering

##🚀 Run on QEMU
make
qemu-system-aarch64 -M raspi3 -kernel kernel8.img

##🎮 Controls
Image Scroll: W (up), S (down), X (exit)
Game: CLI commands / space to shoot, menu for pause/restart/quit

##📚 References
image2cpp
Intel Multicore Optimization
Video to JPG Converter

