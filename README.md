## SYCL Program
```bash
$ xmake create -P intel_sycl
$ cd intel_sycl
$ cmd /k "`"C:\Program Files (x86)\Intel\oneAPI\setvars.bat`" && powershell"
```
```lua
add_rules("mode.debug", "mode.release")
set_toolchains("dpcpp")

or

```
  cmd /k "`"C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Auxiliary\Build\vcvars64.bat`" && powershell"
```
