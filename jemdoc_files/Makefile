
.PHONY : all
all : www/index.html

www/%.html : %.jemdoc MENU mysite.conf
	python ../jemdoc -c mysite.conf -o ../www/  $< 

.PHONY : clean
clean :
	-rm -f html/*.html
