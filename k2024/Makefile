kiban_c_nakaji2024.pdf: kiban_c_nakaji2024.tex fig1.png fig2.png fig3.png
	uplatex kiban_c_nakaji2024.tex
	ptex2pdf -u -l kiban_c_nakaji2024.tex

all: kiban_c_nakaji2024.pdf

view: all
	xpdf kiban_c_nakaji2024.pdf

clean:
	rm -f kiban_c_nakaji2024.pdf *.aux *.log *~
