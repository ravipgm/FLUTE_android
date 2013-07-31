------------------------------------------------------------------------------------

                               FLUTE-android archive

------------------------------------------------------------------------------------
    FLUTE_android: Building FLUTE application to add support for all android devices.
    Copyright (c) 2013 Ravichandran, Nomor Research GmbH
    contact: chandran@nomor.de

    This program is free software; you can redistribute it and/or modify  
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

-----------------------------------------------------------------------------------

    FLUTE_android archive consist of:

    - alclib:				Source files for ALCLIB library.
    - flute:				Source files for FLUTE application.
    - flutelib:				Source files for FLUTELIB library.
    - sdplib:				Source files for SDPLIB library.
    - cURL:					cross compiled CURL library.
    - openssl:				cross compiled OPENSSL library.
    - zlib:					cross compiled ZLIB library.
    - expat:				cross compiled EXPAT library.
    - Makefile:				Makefile for Linux OS to cross-compile for android OS.
    - README.TXT:			This readme file.
    - LICENCE.TXT:			Archive's licence file.
    - LICENCE-UPDATE.TXT:		Additional licence file.
	
------------------------------------------------------------------------------------

    Supported Operation Systems are:

    - android 2.3+
    - Tested on android 4.0+	

------------------------------------------------------------------------------------

    How to cross-compile FLUTE for android:

    The FLUTE_android archive contains a Makefile to compile the ALCLIB, the
    FLUTELIB and the SDPLIB libraries and all other depenent libraries included here
    like cURL, openssl are already pre-compiled from android. Please note that the
    application is compiled using arm-linux-gnueabi compiler. 

    Only write make in the top directory, and all directories are scanned
    through and the ALCLIB, the FLUTELIB and the SDPLIB libraries, with included
    pre-compiled other dependent libraries and the FLUTE applications are compiled.

    The ALCLIB, the FLUTELIB and the SDPLIB libraries are created to the lib 
    directory, and the FLUTE applications are created to the bin directory.
	
------------------------------------------------------------------------------------
