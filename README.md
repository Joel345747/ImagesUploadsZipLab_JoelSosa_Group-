# ImagesUploadsZipLab_JoelSosa_Group.zip
import tkinter as tk

cat = tk.Tk()
cat.geometry("400x400")
cat.configure(bg="purple")
cat.title(" images_and_uploads_lab.py ")

myCatImg = tk.PhotoImage(file="/Users/mac/Downloads/_ 2.png")
myCatImg1 = tk.PhotoImage(file="/Users/mac/Downloads/download (1).png")
myCatImg2 = tk.PhotoImage(file="/Users/mac/Downloads/images.png")
myCatImg3 = tk.PhotoImage(file="/Users/mac/Downloads/images (1).png")

label1 = tk.Label(cat, image=myCatImg)
label1.grid(row=0, column=0)

label2 = tk.Label(cat, image=myCatImg1)
label2.grid(row=0, column=1)

label3 = tk.Label(cat, image=myCatImg2)
label3.grid(row=2, column=0)

label4 = tk.Label(cat, image=myCatImg3)
label4.grid(row=2, column=1)


cat.mainloop()
