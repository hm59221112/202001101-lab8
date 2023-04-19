# 202001101-lab8
Name:Harsh Anand
ID: 202001101
IT314 - LAB-08

1] Boa.java
Code:

public class Boa {
private String name;
private int length; // the length of the boa, in feet
private String favoriteFood;
public Boa (String name, int length, String favoriteFood){
this.name = name;
this.length = length;
this.favoriteFood = favoriteFood;
}
// returns true if this boa constrictor is healthy
public boolean isHealthy(){
return this.favoriteFood.equals("granola bars");
}
// returns true if the length of this boa constrictor is
// less than the given cage length
public boolean fitsInCage(int cageLength){
return this.length < cageLength;
}
}


2] BoaTest.java file:
Created 10 test cases: 2 for checking isHealthy() function, 6 for fitsInCage() function and 2 for lengthInInches() function







