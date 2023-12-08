clean:
	rm -rf .aws-sam
	rm -rf ./**/node_modules

b: clean
	time sam build
	
bb: clean
	time sam build --build-in-source