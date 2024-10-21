# DSA 21st Oct 2024
Question: Stock Buy And Sell. 

temp=prices[j]-prices[i];
if(temp>maxProfit){
   maxProfit=temp;
   temp=0;
}
One Liner for above code. 
maxPro = Math.max(arr[j] - arr[i], maxPro);
----------------------------------------------------
for(int i=0;i<prices.length;i++){
           if(prices[i]<min){
            min=prices[i];
           }
           if(prices[i]-min>maxProfit){
            maxProfit=prices[i]-min;
           }
        }
One Liner for above code.         
for (int i = 0; i < arr.length; i++) {
      minPrice = Math.min(minPrice, arr[i]);
      maxPro = Math.max(maxPro, arr[i] - minPrice);
  }
----------------------------------------------------  
