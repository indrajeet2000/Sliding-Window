# Sliding-Window

IDENTIFICATION

given:  arr | string  /  subarray | substring  /  window size | Condt 

Window Size : j-1+1

Pseudo code:

int i=0, j=0;

while(j<size)
{

condt;

if(j-i+1 < k) j++;

else if(j-i+1 == k)

 { ans;
calculation;
i++, j++;  // slide the window
 }

}

return ans;

