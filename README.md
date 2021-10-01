# new-repo
This code is writen in c programming
It is used to collect user info of employees, students or any group.

#include <stdio.h>
#include <stdlib.h>
#include <ctype.h>
#include <string.h>
#include <math.h>
#include "shlok_info.h"

 int main()
{
 struct user shlok;
 struct user fernando;

 shlok.userid = 1;

 puts("ENTER THE FIRST NAME OF USER 1");
 gets(user.firstname);
 puts("ENTER THE LAST NAME OF USER 1");
 gets(user.lastname);

 printf("User %d's name is %s and last name is %s", shlok.userid, shlok.firstname, shlok.lastname);

 return 0;
}



Shlok's info file


struct user{
 int userid;
 char firstname[25];
 char lastname[25];
 int age;
 float weight;
 };
 
 
 
 .top_header{
	margin:17px;
	padding:0px;
	background-color:#d1cacc;
    border:2px solid black;
	color:solid green;
	font-size:20px;
}
.navigation_bar{
	font : bold 14px tahoma;
	color:#ffffff;
	
}
.top_section{
	margin:10 px;
	padding: 7px;
	border-bottom:dotted black;
	font-size:20px;
}
.the_footer{
	border-top: solid black;
	text-align: center;
}
.img1{
	padding-bottom:20px;
	width: 299px;
	height: 148px;
	padding-top: -1x;
	padding-left: 200px;
	padding-right: 200px;
	
}
.navigation_bar li{
	display : inline-block;
	list-style : none;
    margin:-10px;	
	padding:8px 60px 8px 60px;
	font:24px bold;
}
.png_file{
	width:550px;
	height:160px;
    padding-left:300px;
	padding-right:300px;
}
.websitename{
	text-align: center;
}
.torres{
	padding: 30px;
}
.headline{
	padding-left: 30px;
	font: 25px bold;
}
