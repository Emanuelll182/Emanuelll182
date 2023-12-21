import tkinter as tk

from tkinter import

Laport randon

from tkinter import messagebox

root tk.Tk()

root.title('Aceitas?')

root.geometry(600x600)

root.configure(background="#ffcBdd')

def move button 1(e):

if abs(e.x-button_1.winfo_x()) < 50 and abs(e.y button_1.winfo_y()) < 40: x random.randint(e, root.winfo_width()-button_1.winfo_width())

y random.randint(e, root.winfo_height()-button_1.winfo_height())

button 1.place(x, y)

def accepted():

messagebox.showinfo(

"Meu ator', 'Eu te amo meu amor, lanchinho mais tarde?")

def denied():

button 1.destroy()

margin Canvas (root, width-500, bg-'#ffcBdd', height=100, bd-e, highlightthickness-0, relief-'ridge')

margin.pack()

text id Label(root, bg-"#ffc8dd', text-Tá com raiva de mim?", fo-#590022', font-('Montserrat, 24, 'bold'))

text_id.pack()

button 1 tk.Button(root, text="Não", bg="#ffb3c1", command-denied, relief-RIDGE, bd-3, font("Montserrat, 8, 'bold'))

button 1.pack()

root.bind('Motion), move button 1)

button 2 tk.Button(root, text-'Sim', bg-"#ffb3c1", cellef-RIDGE, bd-3, command-accepted, font=('Montserrat, 14, 'bold'))

button 2.pack()

root.mainloop()
