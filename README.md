# Calculator-using-Tkinter-in-Pythonfrom tkinter import*
cwindow=Tk()
cwindow.title("Calculator")
cwindow.geometry("300x200")
cwindow.configure(bg='black')
#----labels----

l1=Label(cwindow,text="Firstnumber")
l1.configure(bg='white')
l1.place(x=10,y=10)

l2=Label(cwindow,text="Secondnumber")
l2.configure(bg='white')
l2.place(x=10,y=40)

l3=Label(cwindow,text="Result")
l3.configure(bg='white')
l3.place(x=10,y=70)

#----entries-----
e1=Entry(cwindow)
e1.place(x=140,y=10)

e2=Entry(cwindow)
e2.place(x=140,y=40)

e3=Entry(cwindow)
e3.place(x=140,y=70)

#----Button----
b1=Button(cwindow,text="ADD",height=3,width=13).place(x=10,y=100)
cwindow.mainloop()

