# EurorackOTAVCF
## General
An OTA Voltage Controlled Filter Module in Eurorack format.

The design is based on the AI Synthesis AI004 OTA filter and the MS20 filter.

I extended the module with one more input, so that two audio signals can be filtered together to the same output.

There is a [YouTube video](https://www.youtube.com/watch?v=-D7pCkikvYc) available, showing a demonstration of the sound with several DIY filters, oncluding my first version with only one audio input. But it will give you an idea of how it sounds.

## Module Built and PCBs
If you want to build the module yourself, I uploaded the schematics, the BOM and the Gerber files for the PCB.
For creating a front panel, I added a picture with the dimensions and positions of the control components, fitting to the control PBC layout.

The module is built up by just one PCB. I used several SMD components to keep the module that compact.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.
Choose the one you need.

If you want to know about my DIY building process, take a look at those two YouTube videos:
- [How I design PCBs for my Eurorack Synth Modules](https://youtu.be/pXtuV9Pv-m4)
- [Eurorack Module Synth - Building an Electric Druid Wavetable Oscillator Module](https://youtu.be/ECpdo4HfqLg)

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- The design makes use of the SMD version of the LM13700 IC, called V13700M.
- Also the quad op amp TL074 is an SMD version. If available for you, you can also use UPC824 instead.
- There is a number of SMD 0.1uF capacitors with the package size 1608.
- For the tranistors 2N3906, the SMD version MMBT3906 is used on the PCBs.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.
- The switch used is a standard DPDT toggle switch.

<img width="282" alt="OTAVCF_PCB1" src="https://user-images.githubusercontent.com/97026614/177075769-852c615e-270a-4616-aefa-c97f214e308f.png">
<img width="282" alt="OTAVCF_PCB2" src="https://user-images.githubusercontent.com/97026614/177075802-ea320aa6-6ea8-4929-b313-cb34a2f4e64f.png">
