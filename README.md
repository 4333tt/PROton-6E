# PROton-6E
This is PC on P8032AH from 1980, I work on it
; ==========================================================
; PROTON-6E v2.8
; FULL BASIC COMPUTER FOR P8032 / 8051
; ==========================================================
; FEATURES:
; - UART 9600 baud (8MHz quartz)
; - I2C EEPROM 24C16 (32KB) with SAVE/LOAD
; - AV video out (PAL, monochrome) via 74HC164
; - PS/2 keyboard (optional)
; - LED blink 5Hz
; - BASIC: PRINT, LIST, RUN, GOTO, SAVE, LOAD
; - BASIC: LET A=10, A=A+1, INPUT A, RND
; - BASIC: FOR A=1 TO 10 / NEXT A
; - BASIC: DELETE n, STOP, END
; ==========================================================
; HARDWARE MAP:
;   P1.0 - LED
;   P1.1 - DATA_AV (74HC164)
;   P1.2 - CLK_AV
;   P1.3 - SYNC_AV
;   P1.4 - PS2_CLK
;   P1.5 - PS2_DAT
;   P1.6 - I2C_SDA (24C16)
;   P1.7 - I2C_SCL
;   P3.0 - UART_RX
;   P3.1 - UART_TX