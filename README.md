public String HoleTwoScore (int holenumber, int NOSP, int NOSC)
	{
//Instantiating the method HoleTwoScore with the parameters holenumber, NOSP //(number of strokes for par) and NOSC (number of strokes to complete this hole)
String Score = "an out of range score";
//initializes the String Score to “an out of range score”
	if (NOSC == NOSP - 2)
		Score = "an eagle";
//If the score is two less than par, it is an eagle.
	if (NOSC == NOSP - 1)
		Score = "a birdie";
//If the score is one less than par, it is a birdie
	if (NOSC == NOSP)
		Score = "a par";
//if the score is equal to par, it is called par
	if (NOSC == NOSP + 1)
		Score = "a bogey";
//if the score is one over par, the golfer scored a bogey
	if (NOSC == NOSP + 2)
		Score = "a double bogey";
//if the score is two over par, the golfer scored a double bogey
	totalScore = NOSCwhole + NOSC;
//add NOSCwhole to the value from NOSC equal to totalScore
		System.out.println ("You earned " + Score + " on this hole.");
		return ("You earned " + Score + " on this hole.");
//prints out the golfers score on their hole
//prints out “an out of range score” if the none of the if statements are meant   
	}
public String HoleThreeScore (int holenumber, int NOSP, int NOSC)
	{
//Instantiating the method HoleThreeScore with the parameters holenumber, NOSP //(number of strokes for par) and NOSC (number of strokes to complete this hole)
String Score = "an out of range score";
//initializes the String Score to “an out of range score”
	if (NOSC == NOSP - 2)
		Score = "an eagle";
//If the score is two less than par, it is an eagle.
	if (NOSC == NOSP - 1)
		Score = "a birdie";
//If the score is one less than par, it is a birdie
	if (NOSC == NOSP)
		Score = "a par";
//if the score is equal to par, it is called par
	if (NOSC == NOSP + 1)
		Score = "a bogey";
//if the score is one over par, the golfer scored a bogey
	if (NOSC == NOSP + 2)
		Score = "a double bogey";
//if the score is two over par, the golfer scored a double bogey
	totalScore = NOSCwhole + NOSC;
//add NOSCwhole to the value from NOSC equal to totalScore
		System.out.println ("You earned " + Score + " on this hole.");
		return ("You earned " + Score + " on this hole.");
//prints out the golfers score on their hole
//prints out “an out of range score” if the none of the if statements are meant   
	}
