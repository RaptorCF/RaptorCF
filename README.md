import tkinter as tk

root = tk.Tk()
root.attributes('-fullscreen', True)

label = tk.Label(root, text="И зачем?", font=("Arial", 48))
label.pack(expand=True)

root.mainloop()
