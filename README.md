# palindrome
function palindrome(num)
{
    var temp = num;
    var num2=0;
    while(num > 0)
    {
    var rev = num % 10;
    num2 = num2*10 + rev;
    num = parseInt(num/10);
    }
   if( temp == num2)
   {
   return "palindrome";
   }
   else
   {
   return "Not palindrome";
   }
}

console.log(palindrome(17871));
