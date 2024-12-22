# Using the SMelter

The basic principle of the SMelter is that it can slowly heat up and melt a solid sample. The temperature at which the sample melts gives you clues as to the content and purity of the sample. For help assembling the SMelter, see [how to build a SMelter](./assembly.md)

<IMG ALT="Animated gif of a sample melting on the heating block" SRC="./media/melting2.gif" width="1000" />

An animation showing what it looks like when a sample melts.

## Set Up

First, look up the melting point of the substance you are testing. This information is available online in chemical literature and on Wikipedia. Note this temperature somewhere handy.

Next, connect the SMelter's various modules together, turn on the thermometer, and confirm that when the PWM's knob is turned the temperature of the SMelter's heat block increases. If it does not, double check all components and connections. A multimeter may be helpful for this to confirm voltages across the various electrical components.

## Testing a Sample

Now that we have confirmed the SMelter is working, we will test a sample by placing it on the heating block, gradually increasing the temperature, and seeing when the sample melts.

- Place a small amount of sample material on the heat block close to the thermometer's probe. Keeping the sample near the probe will give the most accurate readings.
- Turn the knob on the PWM module all the way clockwise to fully activate the heater cartridge.
- Watch the temperature rise and turn the knob back down when you approach within ~35°C of the expected temperature.
  - Note: There will be a delay of a few seconds between adjusting the PWM and the temperature responding to that change. Be patient and adjust in small increments. We recommend playing with the device before performing an actual sample test to get a sense for how it handles.
  - Note: If your themometer turns off automatically, you may want to turn it off and back on here so it does not time out at a critical moment.
- Adjust the knob on the PWM so that the temperature slowly rises. Ideally, you want less than one degree per second.
- Watch the sample for signs of melting. It may change shape slightly or darken in color as it begins to change from solid to liquid. This is the beginning of the melting point range. Note the temperature on the thermometer when you first notice signs of melting.
- Watch for when the sample becomes completely liquid. This is the end of the melting point range. Note the temperature on the thermometer when this occurs as well.

## Interpreting Results

Hopefully, your sample melted within a few degrees of the expected temperature. If so, it is likely that you have what you think you have. If not, it is likely that your sample contained adulterants (the chemical kind, not the non-monogamy kind) or that it is something else entirely. Remember that this test does not confirm the content of the sample. It only rules out certain possibilities.

## Cleaning Up

Once you are done testing, turn the knob on the PWM module all the way down (typically counterclockwise) and unplug the power supply. Wait for the block to cool before handling it.

After the test, your sample will likely resolidify. Once it has cooled to a safe temperature, clean the heating block with an appropriate solvent to prepare for the next test. Remember that you can always replace the aluminium foil if you have trouble removing residue.

## Additional Notes

### Applicability

Not every substance melts. Not every substance melts at a reasonable temperature (for example, table salt is solid until 800°C). Look up the properties of your target chemical to make sure this is an appropriate test for it.

### Testing a Large Batch of Material

Remember that a powder in a container may not be homogenous - this is sometimes known as "the chocolate chip cookie effect". An adulterated container may have a layer of pure material placed along the top so that a cursory testing shows that it is pure when the rest of the package is not. There are even [specialized tools](https://www.mcmaster.com/products/thief-samplers/) to help sample larger containers to account for this. These tools may be excessive for your purposes, but it is good practice to make sure your samples are well mixed and/or taken from a variety of places in your material.

### Fancier Methods

Most scientists in a laboratory setting will use a more complex aparatus that resembles a tiny oven which accept small glass capillary tubes filled with sample material. These operate on the same principles but have accuracy and usability advantages over this more rudimentary heat block method. Stay tuned for news on the open-source DIY Fancy Melting Point Tester in 2025.

🏴🏴‍☠️💊💉🧪🧬⚗️🔬🏳️‍⚧️