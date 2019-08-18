# New-Beginnings
Getting my start as a game developer

f = open("New_Beginnings.txt", "w")
line1 = "There was once a land called Crysilis."
line2 = "In Crysilis, there existed one too many races."
line3 = "Resources were so scarce that wars seemed neverending..."
line4 = "As you go through the story, your choices will impact the fate of your country & people."
f.write("{}\n{}\n{}\n{}\n".format(line1,line2,line3,line4))
f.close()
  
f = open("New_Beginnings.txt", "r")
print(f.readlines())
f.close()
