# STM32_CPP
Port of https://github.com/damogranlabs/VS-Code-STM32-IDE for C++ projects

## Setup
After setting up toolchain and folder structure as described here: https://github.com/damogranlabs/VS-Code-STM32-IDE,
1) Run update to generate the buildData.json, c_cpp_properties.json, tasks.json and launch.json.
2) Add "specs=nosys.specs" to user_ldFlags in the c_cpp_properties.json file.
3) Make sure the relevant code files are in the user_cSources and user_cppSources.
4) While generating the first time make sure Makefile.backup matches the one in this repository (this would be used to generate the new Makefile)
5) Run updateWorkspace task
6) Build