Notes for JoyCon-Driver
=======================

How to build
------------

* Buildable with Visual Studio Community 2022.
    * You need install MSVC v141 and relates.
    * You need install WindowsSDK 10.0.15063.x . It cannot install with Visual Studio Installer and install from https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/ .
* Build on x86 / Releases
* The version mismatch with wx may be claimed when running.
    Rebuild wxWidgets-3.0.3 in that case.
    The solution file for Visual Studio is located at joycon-driver/full/wxWidgets-3.0.3/build/msw
    (e.g. wx_vc12.sln).
    wxWidgets-3.0.3 requires WindowsSDK 10.0.15063.0.
