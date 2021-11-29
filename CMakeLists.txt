cmake_minimum_required(VERSION 2.8)	 
										
										

project(lab2Branchuk)			

add_library(
	lab2 
	STATIC 
	lab2.cpp
)	

add_executable(
	main 
	main.cpp
)	

target_link_libraries(main lab2)		
