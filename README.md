# COP2664-1-Lesson-6-Programming-Exercise-6.1-Second-Program
This is a GitHub repository link for the second program of Programming Exercise 6.1 of Lesson 6.

// This porgram is used to verify the age of the user if they are old enough to vote.

func checkVotingEligibility(age: Int) { // this function is used to check the age of the user if they are old enough to vote.
  guard age >= 18 else { // this is used to check if the age is greater than or equal to 18.
    print("You are not eligible to vote.") // this is used to print the message if the age is not greater than or equal to 18.
    return // this is used to exit the function.
  }
  print("You are eligible to vote.") // this is used to print the message if the age is greater than or equal to 18.
}
checkVotingEligibility(age: 25) // this is used to check the age of the user if they are old enough to vote.
checkVotingEligibility(age: 17)
