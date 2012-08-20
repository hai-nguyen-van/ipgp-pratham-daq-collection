LAASP — Data acquisition software for PRATHAM satellite ground station at IPGP
==============

__LAASP__ - acronym for L(ogiciel) (d')A(cquisition)A(utomatisé)(pour le)S(atellite)P(RATHAM) - is a set of tools developed at the [Institut de Physique du Globe de Paris](http://www.ipgp.fr) that helps [Pratham satellite](http://www.aero.iitb.ac.in/pratham/) ground station developers automate control, data acquisition (SCADA) and demodulation tasks under [LabVIEW](http://www.ni.com/labview/). Further documentation on technical and scientific issues can be found in [ipgp-pratham-doc](https://github.com/EmptyStackExn/ipgp-pratham-doc) repository.

This unstable version is still incomplete. Usage of `ipgp-pratham-laasp-client` is allowed under the terms listed in LICENSE section at the bottom of this file. _*NIX_ users can find ports of LabVIEW for [FreeBSD](http://people.freebsd.org/~murray/daq.html#labview) and [Linux](http://www.ni.com/white-paper/11786/en) operating systems.


Downloading and building
=============

To download you can click upon or type the following in the Terminal:

	git clone git://github.com/EmptyStackExn/ipgp-pratham-laasp-client.git

The directory `./ipgp-pratham-laasp-client/` is created within you can find:

- `laasp.vi` : data acquisition automation tool
- `DemodulationFSK_Fourier_5-20Hz.vi` : example of FSK demodulation
- `GBF.vi` : signal generator
- `Numerisation_FSK_OOK_from_Amplitude_DPS.vi` : signal digitizer
- `Wav_Sound_of_Lvm_Recording.vi` : returns a [WAVE audio](http://www-mmsp.ece.mcgill.ca/Documents/AudioFormats/WAVE/WAVE.html) file of a signal

Open and execute them with LabVIEW.

Troubleshooting
---------------

You can report bugs at <nguyenva@informatique.univ-paris-diderot.fr>.


Minimum system requirements
---------------------------

- [NI LabVIEW 8.6](http://digital.ni.com/src.nsf/websearch/968B3DF8AD48394D86257880005141A8?OpenDocument&node=node=203014_us)
- [NI DAQ-mx 9.2.3](http://joule.ni.com/nidu/cds/view/p/id/2260/lang/fr)
- [Nova for Windows 2.2c](http://www.nlsa.com/uploads/nfw21v/nova_21v_download.html)

LICENSE
=======

The copyright to this code is held by Institut de Physique du Globe de Paris. All rights reserved. This file is distributed under the license CeCILL Free Software License Agreement.

THIS FILE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Hai Nguyen Van <nguyenva@informatique.univ-paris-diderot.fr>
