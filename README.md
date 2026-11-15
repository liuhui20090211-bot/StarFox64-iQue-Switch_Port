# Star Fox 64 (iQue Chinese) - Nintendo Switch Native Port

**Status: ABANDONED / UP FOR ADOPTION**

## 📢 A Message to the Future
I am leaving this here for my future self, and for anyone in the open-source community who wants to take over. This project is the result of pure passion (and frustration with the Switch N64 emulator). 

**I am NOT a CS major. I wrote ZERO code.** The entire workflow—scripting, compiling, debugging—was **100% driven by AI**. I just tested the build on my hardware and pasted the crash logs back to the AI. I acted as the Director, and the AI wrote the code.

## 📦 Where is the code?
The complete workspace (approx. 600MB), including source code, audit reports, and builds, is available in the **[Releases](../../releases)** section on the right side of this page. 

*   **Based on**: Existing N64 decompilation projects (like Starship).
*   **Language**: The detailed handoff document (`HANDOFF_V18_2026-11-11.md`) is in **Chinese** (I apologize, I am a Chinese developer). Please use an AI translator to read it!

## 📉 Detailed Hardware Test Results (V18)
**Please note: This is NOT a black screen! The game actually boots and runs.**
Here is the exact behavior of the V18 build on a real Nintendo Switch:

**✅ What WORKS:**
*   **Intro Cutscene**: Plays smoothly. Almost perfect (minor stutters, very acceptable).
*   **Main Menus**: Textures display correctly. Menus are fully functional.

**❌ What CRASHES / Breaks:**
*   **Main Game**: Stutters when entering the planet map. **Level 1 (Corneria) crashes instantly and cannot be entered.**
*   **Training Mode**: UI textures are broken. **Crashes immediately when the Arwing flies upwards.** Laser shots, bombs, and crosshair are invisible. It barely reaches the "Wing Repair" item, then becomes unplayable.

The project is stuck at these runtime crashes. It needs someone with better reverse-engineering skills to fix it.

## ⚠️ LEGAL
**NO copyrighted ROM (.z64) is included.** You must provide your own original ROM to extract assets.

Let's hope someone can fix the final crash. Good luck, and have fun!
