# 2D-binary-string



int t;
cin>>t;
while(t--){int n,m,co=0,ro=0,go=0;
cin>>n>>m;
int a[n][m]={0};
for(int i=0;i<n;i++){
    for(int j=0;j<m;j++){
        a[i][j]=1;
        
    }
}
 
for(int i=0;i<n;i++){
    string s;
  cin>>s;
  for(int j=0;j<m;j++){
    if(s[j]=='0'){
        a[i][j]=0;
        
    }
    
  }
}
