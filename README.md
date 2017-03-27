# 10520CS423300-Network-Programming-Practic3-27Mar2017

`In-class practice #3: Before 20:00		
		
Use select and shutdown functions to implement TCP Echo Server/Client to achieve		
		
the following check points:		
		
Check point 1: (70%)		
		
Complete client/server program by select function		
		
Check point 2: (30%)		
		
Complete program by adding shutdown functions		
		
Time before 22:00, 下禮拜補交(8折)		
	
include file list:	
#include <stdlib.h>	
#include <stdio.h>	
#include <unistd.h>	
#include <sys/types.h>	
#include <sys/socket.h>	
#include <arpa/inet.h>	
#include <strings.h>	
#include <sys/ioctl.h>	
#include <signal.h>	
#include <errno.h>	
Hint:	
waitpid(-1, &stat, WNOHANG)	
//-1: wait for any child process to terminate	
//WNOHANG: tell kernel not to block if there are no terminated children		
