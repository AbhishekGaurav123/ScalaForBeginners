**# ScalaForBeginners
#code to take input from user and check wheater he can vote or not**

object Main {
  def main(args: Array[String]): Unit = {
    println("Enter your age :")

    val age =scala.io.StdIn.readInt()
    if (age > 18){
      println("you can vote")

    }
    else{
      println("You cannot vote")
    }
  }
}
