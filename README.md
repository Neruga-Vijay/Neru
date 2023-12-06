from tkinter import*
import tkinter.messagebox

def main():
    root = tkinter.Tk()
    root.geometry("1000x600")
    root.configure(background="white")
    topFrame = tkinter.Frame(root)
    bottomFrame = tkinter.Frame(root)
    
    canvas = tkinter.Canvas(root, width= 900, height=500,
                            highlight thickness = "lavender"
                    
                            

    
    Frame1=tkinter.Frame(text = "Paradise of Vowels",
                         size = 55,
                         colour="lavender")
    playButton=tkinter.Button(bottomFrame,
                              text="Play",
                              command= showinfo)
    Frame2=tkinter.Frame(text="Enter your name",
                         size = 50,
                         color = "black")
    Entry1 = tkinter.Entry(root)
    startButton=tkinter.Button(bottomFrame,
                               text="Start",)
                            
    
    
    
    
    

    tkinter.mainloop()

main()
      




