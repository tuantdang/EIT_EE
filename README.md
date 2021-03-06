# Spectra PDF

The schematic for the 32 electrode EIT system is called Spectra.pdf and is contained in the top level directory. Please let me know if you think it should have any modifications. 

# Eagle_EIT

Note: the following design is an older design for an 8 electrode system. I have a newer better system which was designed in Altium which I'll put up here as soon as crowd supply campaign finalized. In the meantime I'd love it if you wanted to join the mailing list! 

https://www.crowdsupply.com/mindseye-biomedical/spectra

## EIT PCB design in Eagle CAD

Electrical Impedance Tomography is a new way to image conductivity changes inside any mostly liquid medium - such as the human body. It's attractive as it doesn't use ionizing radiation like the X-rays used in a CATSCAN, and could be relatively cheap to mass produce. 

This project is an example of a working system from PCB to firmware to reconstruction algorithm. Further work could certainly improve the resolution, but for now we have functionality in all sub sections. 

This is everything required for the basic 8 electrode design to work. Photo of the assembled PCB included. 

![alt text](images/PCB.png "EIT PCB")

The design is based on the ADuCM350 which has a dedicated high precision front end with 16 bit resolution 160 kSPS data speed.The front end also performs a DFT at the rate of 13.8ms per calculation. This leads to a high performance minimal noise set up, excellent for both R&D or educational purposes. 

In the not too distant future kits may be available with a smaller version of the PCB mounted in a box, an electrode harness for mounting to the body, and all cables required to run. 

This combination would be an excellent educational tool for those researching this area, as it allows you to try most of the reconstruction algorithms or come up with your own and quantify any improvements in results. 

It's the same technique as is used in CATSCAN's, except the current running through the body instead of dangerous ionizing radiation of X-Rays. 

![alt text](images/eit_anti-clockwise_motion.png "EIT example")

Improvements are welcome to this design. To increase resolution you could make a rotational version which is time resolution limited, or simply add more electrodes and re-compute the reconstruction that way. Another intended improvement is to move to tetrapolar differential electrodes set up. If you'd like to collaborate just pull the repository or email contact@mindseyebiomedical.com

We'd love to hear how you are using this! 

## New Board Design 

We have a newer better board design which is uploaded and called Spectra.pdf. Check it out. 


## Future Plans 

Are hatching! Join the technical discussion list to discuss further at openeit.github.io 


## License 

The Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License seems to fit best with this project. Check out the human readable summary here: 

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

If you'd like to make a derivative of this project in a commercial setting, we'd love a payment so that we can afford to spend time both maintaining this project and making more projects like this one. If this hybrid open source model works, it would enable open source projects to receive some funding, making the global commons stronger to benefit everyone. 



