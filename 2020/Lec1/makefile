summary1.pdf: summary1.dvi
	dvipdfmx summary1.dvi
summary1.dvi: summary1.tex fig1_1.eps fig1_2.eps fig1_3.eps fig1_4.eps fig1_5.eps
	platex summary1.tex

fig1_1.eps: fig1_1.svgz
	inkscape -z -f fig1_1.svgz -E fig1_1.eps 
fig1_2.eps: fig1_2.svgz
	inkscape -z -f fig1_2.svgz -E fig1_2.eps 
fig1_3.eps: fig1_3.svgz
	inkscape -z -f fig1_3.svgz -E fig1_3.eps 
fig1_4.eps: fig1_4.svgz
	inkscape -z -f fig1_4.svgz -E fig1_4.eps 
fig1_5.eps: fig1_5.svgz
	inkscape -z -f fig1_5.svgz -E fig1_5.eps 


