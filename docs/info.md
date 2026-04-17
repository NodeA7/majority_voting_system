<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
This is a **majority-rules** circuit. It takes three inputs and only turns the light on if at least two of them are active. It works by checking every possible pair of inputs—if any pair is **ON**, the whole system says **Yes**. It's like a three-person jury where you need at least two votes to reach a verdict.

## How to test
* **Run the simulation:** Click the play button.
* **Test one input:** Flip only one switch. The LED should stay **off** because there is no majority.
* **Test a majority:** Flip any two switches. The LED should turn **on**.
* **Test all inputs:** Flip all three switches. The LED should stay **on**.

## External hardware
* **DIP Switch:** The red component used to toggle the three votes.
* **Logic Gates:** A mix of AND gates (to check for pairs) and OR gates (to combine the results).
* **Input/Output Blocks:** The green modules that organize the signal flow.
* **Red LED:** The visual indicator that shows when a majority is reached.
* **Power & Ground:** The VCC and Ground connections that provide the "electricity" for the simulation.
