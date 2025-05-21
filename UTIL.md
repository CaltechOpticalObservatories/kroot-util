## Overview

This document provides a comprehensive reference for the low-level utilities and software components maintained within KROOT. It includes usage instructions, architecture insights, and support notes.

---

## Supported Utilities

| Name         | Language | Description                       | Location            |
|--------------|----------|-----------------------------------|---------------------|
| `AstroResCam`      | C++           | Contains versions of the code from Astronomical Research Cameras, Inc. (ARC)      | `kroot/util/AstroResCam/`|
| `apcpdu`           | C++           | Low level util for APC power strips      | `kroot/util/apcpdu/`|
| `argv0`            | C             | Command-line util with a custom argv[0]     | `kroot/util/argv0/`|
| `axisFault`        | Python        | TODO: Ask Jeff Mader what this is for     | `kroot/util/axisFault/`|
| `bittytool`        | ???           | TODO: Need more info about it's use     | `kroot/util/bittytool/`|
| `bk_precision`     | Python        | Low level util for BK Precision power supplies     | `kroot/util/bk_precision/`|
| `blackflys`        | ???           | TODO: Need more info about it's use     | `kroot/util/blackflys/`|
| `cfitsio`          | C             | Utilities for reading/writing FITS files (Astronomical data format).     | `kroot/util/cfitsio/`|
| `cfitsio-4.2.0`    | C             | Utilities for reading/writing FITS files version 4.2.0.  | `kroot/util/cfitsio-4.2.0/`  |
| `cfitsio142`       | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio142/`    |
| `cfitsio2027`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio2027/`   |
| `cfitsio2037`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio2037/`   |
| `cfitsio2202`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio2202/`   |
| `cfitsio2410`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio2410/`   |
| `cfitsio2430`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio2430/`   |
| `cfitsio3020`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3020/`   |
| `cfitsio3040`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3040/`   |
| `cfitsio3060`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3060/`   |
| `cfitsio314`       | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio314/`    |
| `cfitsio3270`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3270/`   |
| `cfitsio3280`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3280/`   |
| `cfitsio3370`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3370/`   |
| `cfitsio3490`      | C             | Utilities for reading/writing FITS files.    | `kroot/util/cfitsio3490/`    |
| `conk` | C      | Utility to change permissions for conk accounts                 | `kroot/util/conk/`|
| `createTclMenu` | ???      | TODO: Need more info about it's use                  | `kroot/util/createTclMenu/`|
| `cred2` | Python      | Low level util for CRED-2 detectors                       | `kroot/util/cred2/`|
| `d275_aat` | ???      | Utility for Davidson Optronics AAT D-275 Autocollimating Alignment Telescope     | `kroot/util/d275_aat/`|
| `dcslog` | tcsh      | TODO: Need more info about it's use                        | `kroot/util/dcslog/`|
| `doc` | ???      | Utility for UCO/Lick Keck Tcl documenting code                 | `kroot/util/doc/`|
| `domelamps` | ???      | TODO: Need more info about it's use                      | `kroot/util/domelamps/`|
| `ds9` | ???      | TODO: Need more info about it's use                            | `kroot/util/ds9/`|
| `eaton` | Python      | Low level util for Eaton PDUs                             | `kroot/util/eaton/`|
| `echsim` | Fortran      | Program for Keck HIRES Echelle Simulator                | `kroot/util/echsim/`|
| `electrolog` | ???      | TODO: Need more info about it's use                     | `kroot/util/electrolog/`|
| `emir` | Tcl      | Program for emir (Event Monitoring and Incident Response)     | `kroot/util/emir/`|
| `esp302` | Tcl      | TODO: Need more info about it's use                         | `kroot/util/esp302/`|
| `eventmusic` | ???      | TODO: Need more info about it's use                     | `kroot/util/eventmusic/`|
| `file` | C      |  Utilities for searching for and opening files                  | `kroot/util/file/`|
| `firewalld` | XML      | TODO: Need more info about it's use                      | `kroot/util/firewalld/`|
| `fitsTcl-2.5` | C      | Houses the fiteTcl code in its own directory along with KROOT Makefile structures     | `kroot/util/fitsTcl-2.5/`|
| `fitsio` | Fortran      | FITSIO libraries                                        | `kroot/util/fitsio/`|
| `fitsverify-4.22` | C      | Source code for the fitsverify FITS file conformance verification program     | `kroot/util/fitsverify-4.22/`|
| `focusLog` | Python      | TODO: Ask Jeff Mader what this is for                  | `kroot/util/focusLog/`|
| `gateway` | ???      | TODO: Need more info about it's use                        | `kroot/util/gateway/`|
| `gettimeofday` | C      | Util to get time of day                                 | `kroot/util/gettimeofday/`|
| `graphix` | ???      | Low level util for Leybold Graphix Vacuum Gauge Controller | `kroot/util/graphix/`|
| `grf` | C      |  Houses code for GRFd and GRF tools software                     | `kroot/util/grf/`|
| `idl` | ???      | TODO: Need more info about it's use                            | `kroot/util/idl/`|
| `init.d.tools` | Python      | TODO: Ask Will D what this is for                  | `kroot/util/init.d.tools/`|
| `instec` | ???      | Low level util for Instec device                            | `kroot/util/instec/`|
| `instr` | ???      | Util to get time of day                                      | `kroot/util/instr/`|
| `intrcon` | ???      | Low level util for Leybold Graphix Vacuum Gauge Controller | `kroot/util/intrcon/`|
| `java-jna` | Java  | Houses Java Native Access (JNA)                              | `kroot/util/java-jna/`|
| `java-util` | Java      | Collection of Java classes used to support KTL          | `kroot/util/java-util/`|
| `kPySequencer` | Python      | Python sequencer for EPICS/KTL control             | `kroot/util/kPySequencer/`|
| `kdeploy` | ???      | Utility for updating production KROOT                      | `kroot/util/kdeploy/`|
| `kelf` | ???      | Utility for kelf command (Solaris)                            | `kroot/util/kelf/`|
| `keygrabber` | Python      | Utility for keyword broadcasts                       | `kroot/util/keygrabber/`|
| `kfigdisp` | C      | Houses Figdisp program modified for Keck                    | `kroot/util/kfigdisp/`|
| `klemola` | Fortran  | Houses Fortran programs for Lick Observatory               | `kroot/util/klemola/`|
| `kparload` | Python      | Program for a PAR (parameter file loader)              | `kroot/util/kparload/`|
| `kpdu` | Java      | Collection of Java classes used to support KTL               | `kroot/util/kpdu/`|
| `kplot`           | Unknown  | Unknown                                            | `kroot/util/kplot/`     |
| `kpython`         | Unknown  | Unknown                                            | `kroot/util/kpython/`   |
| `kscriptserv`     | Unknown  | Unknown                                            | `kroot/util/kscriptserv/`|
| `ksim`            | Unknown  | Unknown                                            | `kroot/util/ksim/`      |
| `ktcl`            | Unknown  | Unknown                                            | `kroot/util/ktcl/`      |
| `ktest`           | Unknown  | Unknown                                            | `kroot/util/ktest/`     |
| `ktlcamerad`      | TCL/C    | KTL interface to COO camerad                       | `kroot/util/ktlcamerad/`|
| `ktlwatch`        | Unknown  | Unknown                                            | `kroot/util/ktlwatch/`  |
| `ktlxml`          | Unknown  | Unknown                                            | `kroot/util/ktlxml/`    |
| `ktui`            | Unknown  | Unknown                                            | `kroot/util/ktui/`      |
| `kvncpkg`         | Unknown  | Unknown                                            | `kroot/util/kvncpkg/`   |
| `kwextractor`     | Unknown  | Unknown                                            | `kroot/util/kwextractor/`|
| `kxtract`         | Unknown  | Unknown                                            | `kroot/util/kxtract/`   |
| `lakeshore`       | Unknown  | Unknown                                            | `kroot/util/lakeshore/` |
| `lakeshore_KPF`   | Unknown  | Unknown                                            | `kroot/util/lakeshore_KPF/`|
| `loggerclient`    | Unknown  | Unknown                                            | `kroot/util/loggerclient/`|
| `logtools`        | Unknown  | Unknown                                            | `kroot/util/logtools/`  |
| `lzo`             | Unknown  | Unknown                                            | `kroot/util/lzo/`       |
| `makeDcsRealSim`  | Unknown  | Unknown                                            | `kroot/util/makeDcsRealSim/`|
| `micronix`        | Unknown  | Unknown                                            | `kroot/util/micronix/`  |
| `modhead`         | Unknown  | Unknown                                            | `kroot/util/modhead/`   |
| `ncmill`          | Unknown  | Unknown                                            | `kroot/util/ncmill/`    |
| `newlog`          | Unknown  | Unknown                                            | `kroot/util/newlog/`    |
| `nightpath`       | Unknown  | Unknown                                            | `kroot/util/nightpath/` |
| `npoint`          | Unknown  | Unknown                                            | `kroot/util/npoint/`    |
| `pdv`             | Unknown  | Unknown                                            | `kroot/util/pdv/`       |
| `pig`             | Unknown  | Unknown                                            | `kroot/util/pig/`       |
| `prochelper`      | Unknown  | Unknown                                            | `kroot/util/prochelper/`|
| `py-util`         | Python   | Unknown                                            | `kroot/util/py-util/`   |
| `pyMACIE`         | Python   | Unknown                                            | `kroot/util/pyMACIE/`   |
| `python`          | Python   | Unknown                                            | `kroot/util/python/`    |
| `rdisp`           | Unknown  | Unknown                                            | `kroot/util/rdisp/`     |
| `sat`             | Unknown  | Unknown                                            | `kroot/util/sat/`       |
| `scripts`         | Unknown  | Scripts for various tasks                          | `kroot/util/scripts/`   |
| `service.io`      | Unknown  | Unknown                                            | `kroot/util/service.io/`|
| `slalib`          | Unknown  | Unknown                                            | `kroot/util/slalib/`    |
| `slalib.sla`      | Unknown  | Unknown                                            | `kroot/util/slalib.sla/`|
| `slalib_v9.1229`  | Unknown  | Unknown                                            | `kroot/util/slalib_v9.1229/`|
| `slitmask`        | Unknown  | Unknown                                            | `kroot/util/slitmask/`  |
| `soundboard`      | Unknown  | Unknown                                            | `kroot/util/soundboard/`|
| `spinnaker`       | Unknown  | Unknown                                            | `kroot/util/spinnaker/` |
| `svc.duplicate`   | Unknown  | Unknown                                            | `kroot/util/svc.duplicate/`|
| `tclstuff`        | TCL      | Unknown                                            | `kroot/util/tclstuff/`  |
| `tcspk`           | Unknown  | Unknown                                            | `kroot/util/tcspk/`     |
| `testall`         | Unknown  | Unknown                                            | `kroot/util/testall/`   |
| `thorwheel`       | Python   | Low level utility code for ThorLab Filter wheels   | `kroot/util/thorwheel/` |
| `timetail`        | Unknown  | Unknown                                            | `kroot/util/timetail/`  |
| `tklogger`        | Unknown  | Unknown                                            | `kroot/util/tklogger/`  |
| `ufw`             | README  | Ruminations about how to configure ufw              | `kroot/util/ufw/`       |
| `unixIoc`         | ???  | TODO: Need more info about it's use                    | `kroot/util/unixIoc/`   |
| `usleep`          | C  | TODO: Need more info about it's use                      | `kroot/util/usleep/`    |
| `viz`             | ???  | TODO: Need more info about it's use                    | `kroot/util/viz/`       |
| `vncmonitor`      | Tcl  | TODO: Ask Will D what this is for                      | `kroot/util/vncmonitor/`|
| `wapp`            | Tcl  | Preprocessor utility                                   | `kroot/util/wapp/`      |
| `xdatecookie`     | C  | Program sets and fetches a property on the root window of the X server      | `kroot/util/xdatecookie/`|
| `xmled`           | C  | CLI for XML Files                                        | `kroot/util/xmled/`     |
