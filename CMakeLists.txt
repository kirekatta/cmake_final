cmake_minimum_required(VERSION 3.15) 
									 
									 

set(PROJECT_NAME StayAlive)				 		 
project("${PROJECT_NAME}")


set(CMAKE_CXX_STANDARD 17)			
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

include_directories("inc/")

add_executable("${PROJECT_NAME}" main.cpp
				 game.cpp
				 game.h
				 font.ttf
			 	 duck_1.png
				 enemy_1.png
  				 dead_duck.png
				 background.png			 				 
)