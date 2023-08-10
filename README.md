# San Andreas Audio Toolkit (SAAT) - Version 1.10

SAAT is a collection of command-line tools designed for modding the PC version of the video game Grand Theft Auto: San Andreas. It enables the import of music files into SA audio streams and the import of wave files into SA SFX archives. Additionally, it facilitates exporting from these archives into individual files. SAAT, written by Dave Schmitt (aka "p.D. Escobar") in C++, is an open-source program released under the [GNU General Public License](http://www.gnu.org/licenses/licenses.html#GPL). It builds upon the foundation of the open-source program [Radio Free San Andreas](http://www.lysator.liu.se/~creideiki/radio-free-san-andreas/) and incorporates various open-source libraries such as [libogg](http://www.xiph.org/downloads/) and [libvorbis](http://www.xiph.org/downloads/) for Ogg Vorbis processing, as well as [libsndfile](http://www.mega-nerd.com/libsndfile/) for other sound processing.

## Resources

**Download Locations for Version 1.10:**
- Official Website: [Download from pdescobar.Home.Comcast.Net](http://pdescobar.Home.Comcast.Net/gta/saat/saat_release_1_10.zip)
- GTA Garage: [Download from GTAGarage](http://www.gtagarage.com/mods/show.php?Id=1186)

**Official Website:** Visit the [Official SAAT Website](http://pdescobar.Home.Comcast.Net/gta/saat/) for the most recent version of this README, additional documentation, and distribution downloads.

## Feedback

For discussions and feedback related to SAAT, visit its dedicated thread on the GTA Forums: [GTA Forums Thread](http://www.gtaforums.com/index.php?showtopic=225049). You can also contact the author directly via email.

## Documentation

Here's a concise overview of SAAT. For more comprehensive documentation and usage examples, refer to [manual.txt](./manual.txt). To explore the changes in this version, see [changes.txt](./changes.txt).

## Installation (Windows Binaries)

1. Unzip the two executables and all INI files into a convenient location, such as the GTASA main directory.
2. Open a command prompt and navigate to the installation directory.

## Usage (Stream Tool)

- `saat_stream.exe -e`: Simple export mode; exports all tracks from <input_file>, storing the Ogg Vorbis files in appropriately named subdirectories of <output_directory>.
- `saat_stream.exe -r`: Rfsa export mode; similar to -e, but uses additional descriptive information from <reference_file> to tag and name exported files.
- `saat_stream.exe -i`: Import mode; creates <output_file> based on information and filename references in <input_file>. Also updates references to reflect changes.

## Usage (SFX Tool)

- `saat_sfx.exe -e`: Export mode; exports all sounds from <input_file>, storing the wave files in appropriately named subdirectories of <output_directory>. Uses <reference_file> to locate sounds.
- `saat_sfx.exe -i`: Import mode; creates <output_file> based on information and filename references in <input_file>. Updates references accordingly.

## Acknowledgements

The following individuals and projects have contributed significantly to SAAT:

- SAAT is built upon [Radio Free San Andreas (RFSA)](http://www.lysator.liu.se/~creideiki/radio-free-san-andreas/), released under the GNU GPL. RFSA's primary author is Karl-Johan Karlsson. Adaptations by Marcus Eriksson made RFSA code compatible with SAAT.
- [Ondra Hosek](http://ondrasplayground.on.funpic.de/) contributed changes to RFSA that were integrated into the 32-bit Windows release of SAAT.
- SAAT employs Ogg Vorbis commenting routines derived from the [vorbis-tools distribution](http://www.xiph.org/downloads/), authored by Michael Smith and Ralph Giles.
- SAAT leverages example code from the [libsndfile distribution](http://www.mega-nerd.com/libsndfile/), developed by Eric de Castro Lopo.
- Stream decoding and encoding are built upon the work of Simon Elén, who initially cracked Rockstar's stream encoding.
- SAAT incorporates and enhances stream metadata from [San Andreas Radio](http://www.tinyted.net/eddie/sanandreasradio/) by Eddie Edwards.
- SFX processing in SAAT benefited from the SFX bank header format posted on [GTA Forums](http://www.gtaforums.com/) by [Steve M](http://www.steve-m.com/).

## Licensing

SAAT is distributed under the GNU General Public License. You can redistribute and modify it under the terms of this license. See [COPYING.txt](./copying.txt) for full details. SAAT is provided without warranty; consult the license for specifics.

For more information, contact the [Free Software Foundation](http://www.gnu.org/philosophy/free-sw.html).

## References

1. [GNU General Public License](http://www.gnu.org/licenses/licenses.html#GPL)
2. [Radio Free San Andreas](http://www.lysator.liu.se/~creideiki/radio-free-san-andreas/)
3. [Xiph.Org Downloads](http://www.xiph.org/downloads/)
4. [libsndfile](http://www.mega-nerd.com/libsndfile/)
5. [Download SAAT v1.10](http://pdescobar.Home.Comcast.Net/gta/saat/saat_release_1_10.zip)
6. [Download from GTAGarage](http://www.gtagarage.com/mods/show.php?Id=1186)
7. [Official SAAT Website](http://pdescobar.Home.Comcast.Net/gta/saat/)
8. [GTA Forums Thread](http://www.gtaforums.com/index.php?showtopic=225049)
9. [manual.txt](./manual.txt)
10. [changes.txt](./changes.txt)
11. [Radio Free San Andreas (RFSA)](http://www.lysator.liu.se/~creideiki/radio-free-san-andreas/)
12. [Ondra Hosek's Contributions](http://ondrasplayground.on.funpic.de/)
13. [vorbis-tools Distribution](http://www.xiph.org/downloads/)
14. [libsndfile Distribution](http://www.mega-nerd.com/libsndfile/)
15. [San Andreas Radio](http://www.tinyted.net/eddie/sanandreasradio/)
16. [GTA Forums](http://www.gtaforums.com/)
17. [Steve M's Profile](http://www.steve-m.com/)
18. [COPYING.txt](./copying.txt)
