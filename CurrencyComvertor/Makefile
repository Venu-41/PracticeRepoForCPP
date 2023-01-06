CXXFLAGS:=-lstdc++
.PHONY: all
all : test 

.PHONY: test
test: Testingcode
	./Testingcode

Testingcode:  Testingcode.o CurrencyConvertor.o

.PHONY: clean
clean::
	$(RM) *.[adios] Testingcode 
		