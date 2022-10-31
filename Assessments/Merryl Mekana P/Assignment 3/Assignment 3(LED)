import RPi.GPIO as GP
from time import sleep


GP.setwarnings(False)
GP.setmode(GP.BOARD)
GP.setup(8,GP.OUT,initial=GP.LOW)


while True:                      #infinite loop
    GP.output(8, GPIO.HIGH)               # Turn on
    print("The LED is ON")
    sleep(2)                     # Sleep for 2 second
    
    GP.output(8, GPIO.LOW)                # Turn off
    print("The LED is OFF")
    sleep(2)                     # Sleep for 2 second
