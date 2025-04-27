# Module Four Lab: 16×2 LCD Display Integration

## Reflection

### Summarize the project and what problem it was solving  
I expanded my Module One circuit by adding a 16×2 character LCD display, giving the system the ability to show text feedback instead of relying solely on an LED. This solved the need for a richer user interface on my embedded device by allowing real-time status and data to be displayed directly on the hardware .
![led](https://github.com/user-attachments/assets/599a5af1-c83f-4af5-af52-c8f04bb1b8ba)

### What did I do particularly well?  
I carefully followed the wiring diagram to install the display and potentiometer, methodically verifying each jumper connection to ensure correct pin assignments. I also configured the contrast via the potentiometer and successfully ran the `DisplayTest.py` script to validate text output.

### Where could I improve?  
I could improve my wiring layout for better organization and reduce cable clutter. Additionally, I should implement software debouncing or delay logic around display updates to prevent flicker and avoid overwhelming the LCD with rapid refresh cycles.

### What tools and/or resources are I adding to my support network?  
- **Adafruit Blinka** and **adafruit-circuitpython-charlcd** libraries for easy LCD control  
- **draw.io** for diagramming circuit layouts  
- Official Raspberry Pi GPIO documentation for reference on voltage levels and pin mappings.

### What skills from this project will be particularly transferable?  
- Precise hardware interfacing on a solderless breadboard  
- Configuring and using I²C and GPIO peripherals  
- Writing Python scripts to control text displays in embedded environments  
- Troubleshooting display contrast and update timing issues.

### How did I make this project maintainable, readable, and adaptable?  
I abstracted display logic into a dedicated Python module, used clear variable names for each GPIO pin, and added comment blocks explaining the purpose of each connection. This modular structure allows me to swap in different displays or extend functionality with minimal code changes.
