# Engineering
# print("Hello Freddy!")
# print("Hello World")

import board
import digitalio
import time

led = digitalio.DigitalInOut(board.LED)
led.direction = digitalio.Direction.OUTPUT

def main():
    print("Hello Sanjeevan")
    while True:
        led.value = True
        
        time.sleep(0.2)
        led.value = False
        
        time.sleep(0.2)
        
main()
    
