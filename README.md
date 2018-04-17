int main()
{
 printf("Time taken by page fault(Replaced page is not modified\n");
 scanf("%f",&c);
 printf("Time taken by Page fault(Replaced Page is modified\n”) 
 scanf("%f",&b);
 c=c*1000000;
 b=b*1000000;
 printf("Enter memory access time\n”);
 scanf("%f",&mat);
 printf("Enter modification %age in page\n");
 scanf("%f",&p);
 p=p/100;
 a=1-p;
fault_rate();
}
void fault_rate()
{
float p;
p=(200-mat)/(mat-(p*b)-(a*c));
printf("page fault rate is %f",p);
}
