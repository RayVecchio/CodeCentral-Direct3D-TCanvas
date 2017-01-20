# CodeCentral-Direct3D-TCanvas
Using Direct3D to improve VCL TCanvas' performance in Vista and above in C++

Because of the modifications to the Windows Graphics subsystem the GDI calls are now routed along a different route to go to the
Graphics driver, hence the GDI output show a significant drop in performance compare to Windows XP. 
Using the supplied control canvas one use Direct3D to get comparable performance to WinXP while still keeping the old TCanvas code.

This is beerware...

Roy Nelson

#R;
