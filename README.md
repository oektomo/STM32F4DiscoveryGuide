# STM32F4 Configuration

![Create C Project](docs/1_Create_C_Project.png)
on picture above, fill the Project name, we fill it with "coba1". As we use STM32F4 Discovery board, so we are selecting STM32F4xx C/C++ Project  

![Target processor settings](docs/2_Target_processor_settings.png)
Select the correct Chip Family, it's STM32F407xx for Discovery Board!  

![Folder Settings](docs/3_folder_settings.png)
directory settings for source code and header file, library source code.  

![Toolchain Configuration](docs/4_Toolchain_Configuration.png)
Remember to download the right Toolchain, extract it and paste the path here.  
Wi need to write something about the toolchain.  

![Check HSE VALUE](docs/5_Check_HSE_VALUE.png)
The HSE_Value are asked in header file in startup source code file. here HSE_VALUE are written as an define in compiler option (-D)

![Schematic STM32F4Discovery](docs/SchematicSTM32F4Discovery.png)
the board overlay design are taken from Board datasheet. 

