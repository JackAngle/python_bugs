

# 1/ Python 3 Microsoft Visual C++ 14.0 is required

Fix Python on Windows:

error Microsoft Visual C++ 14.0 is required

by installing Microsoft Build Tools for Visual Studio.

Select: Workloads → Desktop development with C++, then for Individual Components, select only:

    Windows SDK
    C++ x64/x86 build tools

The build tools allow using MSVC “cl.exe” C / C++ compiler from the command line.

### References: https://www.scivision.dev/python-windows-visual-c-14-required/