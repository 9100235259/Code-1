
  class solution{
  public:
    
    string armstrongNumber(int n){
        int sum=0; 
        int temp=n; 

       
        while(temp)
        {
            int last_dig=temp%10;
            temp/=10; 
            sum+=(last_dig*last_dig*last_dig); 
        } 
        if(sum==n)
            return "Yes";
        else 
            return "No";
    }
 
};

