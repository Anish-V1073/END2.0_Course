## Getting Started

Please follow the instructions to Build the DataTracePro installer application.

### Prerequisites

To build DataTracePro installer application following things are needed.
* [Inno setup Compiler](https://jrsoftware.org/download.php/is.exe)
* [Inno Script Studio](https://www.kymoto.org/downloads/ISStudio_Latest.exe)
* [Microsoft® SQL Server® 2014 Express ](https://www.microsoft.com/en-in/download/details.aspx?id=42299)
* [.NET Framework 3.5](https://www.microsoft.com/en-us/Download/confirmation.aspx?id=25150)

### Installing

First Install Inno setup and then Inno-script-studio. Open the Inno-script-studio. Click on Tools->Options->Compiler Settings. 
Browse the location of Inno Setup compiler directory(C:\Program Files (x86)\Inno Setup 6).

### Building DataTracePro
Clone the [dt-installer-v1311](https://github.com/MesaLabs/DataTrace-Pro/tree/dt-installer-v1311) branch.
Place the following files to the respective directory.
* SQLEXPR_x64_ENU.exe -> DataTrace-Pro/Src/3rd Party/SQL_Express/
* dotnetfx35.exe -> DataTrace-Pro/Src/3rd Party/NET_Framework/

Open DataTracePro.iss file with Inno-script studio and compile the script.

