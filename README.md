# Netflix-Tips 


## change download dir

```cmdline
robocopy C:\Users\{username}\AppData\Local\Packages\4DF9E0F8.Netflix_mcm4njqhnhss8\LocalState D:\NF\downloads /E /COPYALL /XJ

rd /Q/S C:\Users\{username}\AppData\Local\Packages\4DF9E0F8.Netflix_mcm4njqhnhss8\LocalState

mklink /D C:\Users\{username}\AppData\Local\Packages\4DF9E0F8.Netflix_mcm4njqhnhss8\LocalState D:\NF\downloads\

```
