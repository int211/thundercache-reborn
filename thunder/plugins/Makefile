CXX = g++

OBJECTS = tube8.com.so \
	grandchase.com.br.so \
	eset.com.so \
        vimeo.com.so \
	kaspersky.com.so \
	xvideos.com.so \
	dailymotion.com.so \
	globo.com.so \
	4shared.com.so \
	pop6.com.so \
	pornotube.com.so \
	avg.com.so \
	symantecliveupdate.com.so \
	video.msn.com.so \
	pornhub.com.so \
	mediafire.com.so \
	metacafe.com.so \
	avast.com.so \
	nai.com.so \
	uol.com.br.so \
	megaupload.com.so \
	megavideo.com.so \
	etrustdownloads.ca.com.so \
	terra.com.so \
	xtube.com.so \
	orkut.com.so \
	ziddu.com.so \
	rapidshare.com.so \
	youtube.com.so \
	viddler.com.so \
	redtube.com.so \
	microsoft.com.so \
	avgate.net.so \
	google.com.so \
	live.com.so \
	edgecastcdn.net.so \
	rad.msn.com.so \
	doubleclick.net.so \
	photobucket.com.so 


all: plugins copiar

plugins: $(OBJECTS)

%.so: %.cpp 
	$(CXX) -I. -fPIC -shared -o $@ $<
	
	
copiar:	
	cp avg.com.so grisoft.com.so
	cp avg.com.so grisoft.cz.so
	cp avgate.net.so  avgate.com.so
	cp avgate.net.so freeav.net.so
	cp avgate.net.so freeav.com.so
	cp kaspersky.com.so  kaspersky-labs.com.so
	cp metacafe.com.so  mccont.com.so
	cp microsoft.com.so  windowsupdate.com.so
	cp nai.com.so  update.nai.com.so
	cp youtube.com.so googlevideo.com.so
	cp vimeo.com.so bitgravity.com.so
	cp orkut.com.so orkut.com.br.so
	cp google.com.so google.com.br.so
	cp live.com.so bing.com.so

clean:
	rm -f *.so
