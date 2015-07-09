INCOMPLETE WORK

p-build-root (packaging:pom)
	|
	|---p-build-data 
	|		(packaging:pom, builds data.tar)
	|
	|---p-build-scripts 
	|		(packaging:pom, builds a scripts.tar)
	|
	|---p-build-final 
	|		(packaging:pom, builds p.tar)
	|		(In p.tar, need to include data.tar and scripts.tar)
	
TODO
p-build-final
	(packaging:pom, builds p.tar)
	(In p.tar, need to include data.tar and scripts.tar)
	|
	|---p-build-data 
	|		(packaging:pom, builds data.tar)
	|	
	|---p-build-scripts 
	|		(packaging:pom, builds a scripts.tar)
	|
