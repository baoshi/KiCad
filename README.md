# KiCad Libs
KiCad libraries used in my projects

Eeschema libraries are under [library](library)
Pcbnew modules and optional 3d modules are under [modules](modules)
All libraries and modules are prefixed with z_ or Z_ to avoid confliction with KiCad built-in ones.

About ${KIUSERMOD}
The Pcbnew footprints depend on ${KIUSERMOD} variable to locate 3D modules. This should point to modules directory where you store all the xxx.pretty and xxx.3dshapes

Configure ${KIUSERMOD} in Pcbnew->Preferences->Config Paths

Copyright (c) 2016, Baoshi Zhu. All rights reserved.

Source code in this project is governed by Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0)

