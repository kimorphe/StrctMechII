note3.pdf: note3.dvi
	dvipdfmx note3.dvi
note3.dvi: note3.tex fig5.eps fig6.eps fig7.eps fig8.eps
	platex note3.tex
fig5.eps: fig5.svgz
	inkscape -z -f fig5.svgz -E fig5.eps 
fig6.eps: fig6.svgz
	inkscape -z -f fig6.svgz -E fig6.eps 
fig7.eps: fig7.svgz
	inkscape -z -f fig7.svgz -E fig7.eps 
fig8.eps: fig8.svgz
	inkscape -z -f fig8.svgz -E fig8.eps 


