# Session-5-Assignment-1
Create a Scala application to find the GCD of two numbers.
package Assign.test

class GCD {
  def gcdval(a: Int,b: Int): Int = {
       if(b ==0) a else gcdval(b, a%b)
    }  
}
object assign05{
def main(args:Array[String]){
    val GCDVal= new GCD();
    println(GCDVal.gcdval(25, 15))
 }
}
