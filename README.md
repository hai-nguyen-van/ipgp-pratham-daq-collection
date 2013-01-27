Data acquisition software collection for Pratham satellite ground station at IPGP
==============

A set of tools developed at the [Institut de Physique du Globe de Paris](http://www.ipgp.fr) that helps [Pratham satellite](http://www.aero.iitb.ac.in/pratham/) ground station developers automate control, data acquisition (SCADA) and demodulation tasks under [LabVIEW](http://www.ni.com/labview/).

Further documentation on technical and scientific issues can be found in [ipgp-pratham-doc](https://github.com/EmptyStackExn/ipgp-pratham-doc) repository. _*NIX_ users can find ports of LabVIEW for [FreeBSD](http://people.freebsd.org/~murray/daq.html#labview) and [Linux](http://www.ni.com/white-paper/11786/en) operating systems.

Usage of `ipgp-pratham-daq-collection` is allowed under the terms listed in LICENSE section at the bottom of this file.


Downloading and building
=============

To download you can click upon (`ZIP` button) or type the following line in the Terminal:

	git clone git://github.com/EmptyStackExn/ipgp-pratham-daq-collection.git

The directory `./ipgp-pratham-daq-collection/` is created within you can find:

- `Main.vi` : main data acquisition automation tool
- `Digitization_of_signal.vi` : signal digitizer
- `FSK_demodulation_of_signal.vi` : FSK demodulator
- `Pratham_type_signal_generator.vi` : Pratham-type signal generator
- `Pratham_type_rawfile_generator.vi` : Pratham-type raw signal generator
- `Wave_file_of_LVM_file.vi` : returns a [WAVE audio](http://www-mmsp.ece.mcgill.ca/Documents/AudioFormats/WAVE/WAVE.html) file of a signal
- `LVM_file_of_wave_file.vi` : inversed map of the previous program

Open and execute them with LabVIEW.

Troubleshooting
---------------

You can report bugs at <nguyenva@informatique.univ-paris-diderot.fr>.


Minimum system requirements
---------------------------

- [NI LabVIEW 8.6](http://digital.ni.com/src.nsf/websearch/968B3DF8AD48394D86257880005141A8?OpenDocument&node=node=203014_us)
- [NI DAQ-mx 9.2.3](http://joule.ni.com/nidu/cds/view/p/id/2260/lang/fr) (ADC drivers)
- [Nova for Windows 2.2c](http://www.nlsa.com/uploads/nfw21v/nova_21v_download.html) (satellite tracking and antenna rotor control)

LICENSE
=======

The Pratham software system is not free software. This release can be used for evaluation, research and education purposes, but not for commercial purposes. The copyright to this code is held by Institut de Physique du Globe de Paris and distributed under the INRIA Non-Commercial License Agreement. All rights reserved.

THE PROVIDER MAKES NO REPRESENTATIONS ABOUT THE SUITABILITY, USE, OR PERFORMANCE OF THIS SOFTWARE OR ABOUT ANY CONTENT OR INFORMATION MADE ACCESSIBLE BY THE SOFTWARE, FOR ANY PURPOSE. THE SOFTWARE IS PROVIDED "AS IS," WITHOUT EXPRESS OR IMPLIED WARRANTIES INCLUDING, BUT NOT LIMITED TO, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NONINFRINGEMENT WITH RESPECT TO THE SOFTWARE. THE PROVIDER IS NOT OBLIGATED TO SUPPORT OR ISSUE UPDATES TO THE SOFTWARE.

Hai Nguyen Van <nguyenva@informatique.univ-paris-diderot.fr>
