# RAINMETER-Disable-skin-if-maximized
A skin that will automatically disable the "VisBubble -> BarExtrude.ini" skin when it detects that Firefox is maximized.
This was heavily inspired by jsmorley's post (https://forum.rainmeter.net/viewtopic.php?t=21785)

This detects that firefox is running, by searching for a REGULAR EXPRESSION on the title of programs. For some reason, firefox always has "firefox" in it's title, even when it's not visible.
If you want to modify this, this is an obligatory read: https://www.autoitscript.com/autoit3/docs/tutorials/regexp/regexp.htm

The [MeasureWindow] and [MeasureWindow] sections are pretty much necessary for the whole thing to work. Good luck if you wish to improve this.
