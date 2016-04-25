COMPILESTR = jifc -classpath ./ Main.jif

compile:
	$(COMPILESTR)

principals:
	jifc jif/principals/*.jif


explain:
	$(COMPILESTR) -explain

run:
	jif -classpath ./ Main

clean:
	rm *.java *.class

# you shouldn't need this
xxx_principalsclean:
	rm jif/principals/*.java
	rm jif/principals/*.class
