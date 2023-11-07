# adc-mspm0g3507

Title: **Using the ADC System**

Objective:



## Pseudocode for adc-mspm0g3507

### Steps:

**Step 1**: Set ADC input pin to potentiometer, here we assigned PA25 pin.\
**Step 2**: Set ADC parameters:
         - Clock divide ratio  
         - Input channel
         - Power down mode
         - Repeat mode
         - Sample time\
**Step 3**: Enable ADC interrupt on the high/low threshold window and compare.\
**Step 4**: Set GPIO output pin for LED, here we assigned pin PA0.\
**Step 5**: Start ADC conversion.\
**Step 6**: In the interrupt handler, set/clear LED based on the threshold comparison.

## Output:

[Video link](https://usfedu-my.sharepoint.com/:v:/g/personal/dobariya_usf_edu/EbpjT_Ei7VJGjbUa1ghthw8B3ikhdUtDLq8nkLpt2Fw9Dw?e=AwIhf3)

