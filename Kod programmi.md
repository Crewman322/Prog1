# Kod grogrammi 1
#include <stdio.h>
#include <iostream>

using namespace std;

class troad
	{
	public:
	float Length;
	int Width;
	troad(float length0, int width0);
	};
	
troad::troad(float length0, int width0)
{
	if(length0>0)
Length=length0;
else Length=1;
	if(width0>0)
Width=width0;
else Width=1;
}

int main()
{
	troad road(50.1,4);
road.Length=0;
road.Width=0;
std::cout<<"road.Width="
<<road.Width<<std::endl;
std::cout<<"road.Length="
<<road.Length<<std::endl;
road.Length=3;
road.Width=5;
std::cout<<"road.Width="
<<road.Width<<std::endl;
std::cout<<"road.Length="
<<road.Length<<std::endl;

return 0;
}
