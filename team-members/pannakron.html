import tkinter as tk
from tkinter import messagebox
import pygame
import os
from PIL import Image, ImageTk

# -----------------------------
# ฟังก์ชันจัดการเพลง
# -----------------------------
def play_music():
    music_path = "neymar.mp3"
    if os.path.exists(music_path):
        pygame.mixer.init()
        pygame.mixer.music.load(music_path)
        pygame.mixer.music.play(-1)
    else:
        messagebox.showerror("Error", "ไม่พบไฟล์เพลง neymar.mp3")

def stop_music():
    if pygame.mixer.get_init():
        pygame.mixer.music.stop()

# -----------------------------
# สร้างหน้าต่างหลัก
# -----------------------------
root = tk.Tk()
root.title("เกี่ยวกับฉัน")
root.geometry("400x600")
root.configure(bg="#a8dadc")  # โทนสีฟ้าอ่อน

# -----------------------------
# ข้อความทักทาย
# -----------------------------
label = tk.Label(root, text="Hello I Am Morphine ✨", font=("Comic Sans MS", 22, "bold"),
                 fg="#1d3557", bg="#a8dadc")
label.pack(pady=15)

# -----------------------------
# กรอบสำหรับรูป
# -----------------------------
frame_img = tk.Frame(root, bg="#457b9d", bd=5, relief=tk.RIDGE)
frame_img.pack(pady=10)

# โหลดรูป morphine.png
image_path = "morphine.png"
if os.path.exists(image_path):
    try:
        img_open = Image.open(image_path)
        img_open = img_open.resize((300, 300))
        img = ImageTk.PhotoImage(img_open)
        panel = tk.Label(frame_img, image=img, bg="#457b9d")
        panel.image = img
        panel.pack(padx=5, pady=5)
    except Exception as e:
        tk.Label(frame_img, text=f"โหลดรูปไม่ได้: {e}", fg="red", bg="#457b9d").pack(pady=10)
else:
    tk.Label(frame_img, text="ไม่พบไฟล์ morphine.png", fg="red", bg="#457b9d").pack(pady=10)

# -----------------------------
# ฟังก์ชันตกแต่งปุ่ม
# -----------------------------
def on_enter(e):
    e.widget['bg'] = '#1d3557'
    e.widget['fg'] = '#f1faee'

def on_leave(e):
    e.widget['bg'] = '#457b9d'
    e.widget['fg'] = '#f1faee'

btn_play = tk.Button(root, text="▶️ เล่นเพลง 🎵", command=play_music,
                     width=20, height=2, bg="#457b9d", fg="#f1faee",
                     font=("Arial", 12, "bold"), bd=0)
btn_play.pack(pady=10)
btn_play.bind("<Enter>", on_enter)
btn_play.bind("<Leave>", on_leave)

btn_stop = tk.Button(root, text="⏹️ หยุดเพลง ❌", command=stop_music,
                     width=20, height=2, bg="#457b9d", fg="#f1faee",
                     font=("Arial", 12, "bold"), bd=0)
btn_stop.pack(pady=5)
btn_stop.bind("<Enter>", on_enter)
btn_stop.bind("<Leave>", on_leave)

# -----------------------------
# รันโปรแกรม
# -----------------------------
root.mainloop()
