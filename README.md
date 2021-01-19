2:- for(i=1; i<n; i++){
if(i%2==0){
document.write(i+"is even no.")
}
else if(i%2=1){ 
document.write(i+"is odd no. ")
}
else if(i%2==0 && n%i==0){
count++;
if(count==2){
document.write(i+"is even or prime no.")}
}
}

3:- int i, j,n=5;
 For(i=0;i<5;i++){
for(j=n;j>i;j--){
Document.write("*");
}
documemt.write("\n");
}
