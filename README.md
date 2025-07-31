# OnStartup
application which starts on startup 
# code for registering it into startup apps in windows
sc create Mystartupservice binPath= "//path to exe file which we get after publishing"
sc config Mystartupservice start= auto
sc start Mystartupservice
