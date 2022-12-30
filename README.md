# Digital-Forensics-GIF-Finder-Recoverer-
This repo contains the C project files for finding GIF file block and recovering that file



build: mainNameAttr.c cl_getMftAdd.c getFname.c getNameAttrAdd.c prtFileName.c prtFileData.c gif.c
	gcc $^
clean:
	rm a.out
