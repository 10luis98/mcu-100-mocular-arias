# MCU-100 Modular (Arias)

Proyecto base en KiCad para diseño y práctica modular con la suite completa de módulos de **Hellen-One** y **Arias**.

## Módulos de Hellen-One Configurados
El proyecto ya tiene vinculadas todas las librerías de símbolos y huellas de Hellen-One:
- **Microcontroladores:** mega-mcu100 (LQFP-100), mega-mcu144 (LQFP-144), mega-mcu64, mcu.
- **Alimentación (Power):** power12, power5, power_12and5V.
- **Comunicaciones:** can, lin, stlink.
- **Sensores y Entradas:** r, r-discrete, r-max9924, knock, dinput4.
- **Salidas y Drivers:** ign8 (encendido), output (inyección/salidas bajas), mcz33810, motor-driver, uaefi.
- **Almacenamiento y Banda Ancha:** sd, wbo (Wideband Oxygen Controller).
- **Librerías RusEFI y Arias:** kicad6-libraries, symbol-arias, oot-arias (conectores MRE48 y componentes EasyEDA/LCSC).

## Archivos del Proyecto
- mcu-100-modular.kicad_pro: Archivo de proyecto KiCad.
- mcu-100-modular.kicad_sch: Esquemático principal.
- mcu-100-modular.kicad_pcb: PCB base de trabajo.
- p-lib-table & sym-lib-table: Tablas de librerías portátiles con ${KIPRJMOD}.
