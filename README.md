###### ***Readme last reviewed at ThinBasic v1.11.4.0***

# thinSample
user tool to help finding all relevant  [thinBasic](https://www.thinbasic.com) samples scripts given a keyword

⮞ [thinSample tread](https://www.thinbasic.com/community/showthread.php?13033-thinSample-at-your-service) with screenshots on thinBasic's community forum.

## thinAir integration

1. Copy folder _thinSample_ to _%thinBasic_Installation_Folder%\thinAir\Tools\_
2. Edit  _%thinBasic_Installation_Folder%\thinAir\Tools\thinAir_Tools_Usr.ini_ and append the following section :
<pre>
[thinSample]
Menu=thinSample
CommandLine=%thinbasicinstallpath%\thinbasic.exe "%thinAirinstallpath%\Tools\thinSample\thinSample.tbasic "
SaveScriptBefore=false
</pre>
3. Restart thinAir

## Usage

run from _Tools\User tools\thinSample_ menu

type or paste a keyword in the inputbox

double click a sample name (if any) in the listbox or select it and click the _Modify_ button
