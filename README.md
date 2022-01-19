"# ASM-Lab02" 
"# ASM-Lab02" 
main PROC

	mov	eax,val1			; start with 10000h
	add	eax,val2			; add 40000h
	sub	eax,val3			; subtract 20000h
	mov	finalVal,eax		; store the result (30000h)
	call	DumpRegs			; display the registers

	exit
main ENDP
END main
