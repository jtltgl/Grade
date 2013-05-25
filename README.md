Horse Grade
=====
This app will compare winning time against track record and will grade performance. App was made using Sencha Architect and can be found on GitHub or http://smallprogramdesign.com. I am still learning GitHub so bear with me as I am still making mistakes.


You can test app out by typing http://smallprogramdesign.com/myapp. 

example 1.) 

First you need Track Records. You can find most track records on Web.

Track record time of 2:01.4 at PIMLICO for 1 1/4 miles was by Horse name Manzotti;



So ORB race 12 PIMLICO very first entry which will be results from Kentuckey Derby: 

Win = 202.89;
Loss = 0;
Record = 201.4;

Your Grade is 99.27;

now OXBOW race 12 PIMLICO very first entry;

Win - 202.89;
Loss = 9.5;
Record = 201.4;

Your Grade is 98.35;


Formula is Record/(Win -(Loss * 1/5))*100;

Record = Track Record race distance;
Win = Winning Time;
Loss = Length Loss By in decimals (ex. 3 1/2 equals 3.5);

