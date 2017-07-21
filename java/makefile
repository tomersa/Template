a: run

build: clean
	javac src/main.java -o out/main

run: build
	pushd .
	cd out
	java main; popd

clean:
	rm -rf out/*
