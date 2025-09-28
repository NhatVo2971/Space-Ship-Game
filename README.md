Bare Metal OS – Screen Display & Game Development
📌 Overview

This project extends a Bare Metal OS with screen display features and a CLI-driven game on Raspberry Pi 3 / QEMU. It demonstrates image rendering, video playback, custom fonts, and basic game mechanics.

👥 Team 8

Mai Xuan Huy (s3878672)

Hoang Nghia Tri Hung (s3930336)

Truong Phuoc Huy (s3891442)

Vo Phuc Duy Nhat (s3868763)

✨ Features

Image display with scroll (W/S, exit with X)

Video playback (24 FPS, delay interrupts)

Custom font rendering (bitmap conversion, color support)

Game development:

Stage 1: Shoot monsters

Stage 2: Boss fight with bombs

Pause / Restart / Quit menu

Score & health system

🛠️ Tools & Tech

Languages: C / C++

Platform: Raspberry Pi 3, QEMU Emulator

Tools: image2cpp, ezgif (video-to-frames)

Concepts: Frame Buffer, CLI interaction, Bitmap rendering

🚀 Run on QEMU
make
qemu-system-aarch64 -M raspi3 -kernel kernel8.img

🎮 Controls

Image Scroll: W (up), S (down), X (exit)

Game: CLI commands / space to shoot, menu for pause/restart/quit

📚 References

image2cpp

Intel Multicore Optimization

Video to JPG Converter
