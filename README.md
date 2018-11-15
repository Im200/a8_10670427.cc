#include <iostream>
#include <vector>

using namespace std;

int binarySearch(vector<int>&vec,int start ,int end ,int val)

{
    int mid;
    mid=start+(end+start)/2;
}
int main()
{
  vector(int)vec;
  int vecsize;
  int elem;
  int val;
  int loc; 
  
  cout<<"\n.....Binary Search....\n\n";
  
  cout<<"Enter size of array;";
  cin>> vecsize;
  cout<<endl;
  
  for(int i=0;i<vecsize;i++)
  {
      cout<<"Element n"<<i+1<<";";
      cin>> elem;
      vec.push_back(elem)
  }
  cout<<endl<<"Enter the value you are searching for;";
  cin>>val;
  cout<<endl;
  
  loc=binarySearch(vec,0,vec.size()-1,val);
  
  if(loc>=0)
  {                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             
     cout<<"Value found!"<<char(2)<<endl;
     cout<<"The number you are searching for is Element n"<<loc+1<<"."<<endl;
     
  }
  else
{
    cout<<"Not found."endl;
    
}
cout<<endl; 
system("pause");
  
  return 0;
  
}
