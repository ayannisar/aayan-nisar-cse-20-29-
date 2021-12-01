int num,flag=0;
	
	printf("ENTER A NUMBER \n");
	scanf("%d",&num);
	flag=prime(num);
	if(flag==0)
		printf("%d IS A PRIME NUMBER\n",num);
	else
		printf("%d IS NOT A PRIME NUMBER\n",num);

}
int prime(int n)
{
	int i;
	for(i=2;i<=n/2;i++)
	{
		if(n%i!=0)
			continue;
		else
			return 1;
	}
	return 0;
}
