# Algorithm

This repository contain all frequency ask interview questions in data structure and algo.

## ArrayList
- [Check Prime numbers](#PrimeNumber)
- [Palindrome Number](#Palindrome)
- [String Palindrome](#StringPalindrome)
- [Armstrong Number](#ArmstrongNumber)
- [Factorial Number](#FactorialNumber)
- [Fibonacci Series](#FibonacciSeries)
- [Anagram string **I/P->(TAB) O/P(BAT) true**](#AnagramString)
- [Swap two element without third element](#SwapElement)
- [Find missing number in array](#MissingNumberInArray)
- [Find duplicate number in array](#DuplicateNumber)
- [Find second largest and smallest number in array](#SecondLargest&SmallestNumber)
- [Find subarray with given sum](#SubArrayOfGivenSum)
- [Find substring in given paragraph](#SubStringInParagraph)
- [Reverse array](#ReverseArray) 
- [Star pyramid program](#StarPattern)
- [Count number of zeros in array(logN)](#CountNumberOfZero)
- [Check Leap year](#CheckLeapYear)
- [Seperate o's, 1's and 2's in array(HCL)](#Seperate012)
- [Intersection and Union of two arrays(Paytm)](#IntersetionUnionTwoArray)
- [Intersection and Union of three arrays(Paytm)](#IntersetionUnionThreeArray)
- [Find element in array (logN)](#FindElementInArray) 
- [Find length of repeated characters like **I/P->(aaabbbcdddaa)O/P->(a3b3cd3a2)**
	if character is available single time then enter character without it's value](#RepeatedCharacters)
- [Add two large string(Paytm)](#AddTwoLargeString)
- [Find the length of the longest sequence of consecutive numbers **(N) like I/P->(1,9,3,10,4,20,2) O/P->4(1,2,3,4)**](#LargeConsecutiveNumbers)
- [Convert string into camel case and reverse **I/P->(my_test) O/P ->(myTest)(Nagarro)**](#StringIntoCamelCase)
- [Merge and sort two array(M+N)](#MergeAndSortTwoArray)
- [Create Dynamic Array as like arraylist using array](#CreateDynamicArray)
- [Count frequency of give digits(1) in an array like **I/P-(10,11,12,13) find 1 O/P-(5)**](#CountFrequencyGivenOfDigit)
- [Sort array (N)](#SortArray)
- [Selection Sort](#SelectionSort)
- [Binary search](#BinarySearch)

## Linked list
- [Reverse Linked list](#ReverseLinkedList)
- [Reverse Linked list in pair(Paytm) **like I/P->(1-2-3-4-5) O/P->(2-1-4-3-5)**](#ReverseLinkedListInPair)
- [Find mid element in Linked List](#MidElementInLinkedList)
- [Find last nth element in Linked list](#LastNthItemInLinkedList)
- [Get length of Linked list](GetLengthOfLinkedList)

## Stack
- [Implement a stack using queues(Airtel)](#ImplementStackUsingQueues)
- [Reverse a stack](#ReverseStack)

## Queue
- [Implement a queues using stack](#ImplementQueuesUsingStack)

## Android
- [Bind Service](#BindService) 

## Other
- [Shuffle deck of cards](#ShuffleDeckOfCards)
- [Form the minimum number from the given sequence of characters.(Airtel)   

	D: Decreasing
	
	I: Increasing
	
	1-9 digits are allowed and you can not repeat the digits
	
	First letter of the sequence corresponds to two digits

	I/p D , o/p  21
	
	i/p I , o/p  12
	
	i/p DD  o/p 321
	
	i/p DIDI  o/p 21435](#DIDILogic)
	
## Puzzle
- [The 3 & 5 Litre Die Hard Water Puzzle](#3_5LiterWaterPuzzle)
- [Spider web puzzle](#SpiderWebPuzzle)

## PrimeNumber

      void checkPrimeNumber() {
        int number = 13;
        if (number == 0 || number == 1) {
          print("$number is not prime number");
          return;
        }
        var isPrime = true;
        for (int i = 2; i < number / 2; i++) {
          if (number % i == 0) {
            isPrime = false;
            break;
          }
        }
        if (isPrime) {
          print("$number is prime number");
        } else {
          print("$number is not prime number");
        }
      }	
	
## Palindrome

       void checkPalindrome() {
          // O(N)
          int number = 131;
          int temp = number;
          int sum = 0;
          while (temp > 0) {
            sum = (sum * 10) + temp % 10;
            temp = (temp / 10).toInt();
          }
          if (sum == number) {
            print("$number is palindrome number");
          } else {
            print("$number is not palindrome number");
          }
        }
	
	
## StringPalindrome

        void checkPalindrome() {
          // O(N)
          String ipString = "TAT";
          String opString = "";
          for (int i = 0; i < ipString.length; i++) {
            opString = ipString[i] + opString;
          }
          if (opString == ipString) {
            print("$ipString is palindrome number");
          } else {
            print("$ipString is not palindrome number");
          }
        }
	
	
## ArmstrongNumber

      void checkArmstrongNumber() {
        int number = 153;
        int temp = number;
        int sum = 0;
        while (temp > 0) {
          int cube = temp % 10;
          cube = cube * cube * cube;
          sum = sum + cube;
          temp = (temp / 10).toInt();
        }
        if (number == sum) {
          print("$number is armstrong number");
        } else {
          print("$number is not armstrong number");
        }
      }
      
## FactorialNumber

      void factorialNumber() {
        int number = 5;
        int sum = 1;
        for (int i = 1; i <= number; i++) {
          sum = i * sum;
        }
        print("$number Factorial Number Is - $sum");
      }
      
## FibonacciSeries

      void fibonacciSeries() {
        int number = 50;
        int n3 = 0;
        int n2 = 1;
        int n1 = 0;
        print("$n1, $n2");
        for (int i = 1; i <= number; i++) {
          n3 = n1 + n2;
          print("$n3");
          n1 = n2;
          n2 = n3;
        }
      }

## AnagramString
    public static void main(String[] args) {
        String s1 = "Tab".toLowerCase();
        String s2 = "Bat".toLowerCase();

        if (areAnagram(s1.toCharArray(), s2.toCharArray()))
            System.out.print("Is Anagram");
        else System.out.print("Not Anagram");
    }
    
    static boolean areAnagram(char[] str1, char[] str2) {
        if (str1.length != str2.length)
            return false;
        int NO_OF_CHARS = 256;
        int[] count = new int[NO_OF_CHARS];
        int i;

        for (i = 0; i < str1.length; i++) {
            count[str1[i] - 'a']++;
            count[str2[i] - 'a']--;
        }

        for (i = 0; i < NO_OF_CHARS; i++) {
            if (count[i] != 0) return false;
        }
        return true;
    }

## SwapElement
	void main() {
	  int a = 5;
	  int b = 10;
	  print("Before - A: $a,  B: $b");
	  a = a + b;
	  b = a - b;
	  a = a - b;
	  print("After - A: $a,  B: $b");
	}

    
## MissingNumberInArray
## DuplicateNumber
## SecondLargest&SmallestNumber
## SubArrayOfGivenSum
## SubStringInParagraph
## ReverseArray
## StarPattern
## CountNumberOfZero
## CheckLeapYear
## Seperate012
## IntersetionUnionTwoArray
## IntersetionUnionThreeArray
## FindElementInArray
## RepeatedCharacters
## AddTwoLargeString
## LargeConsecutiveNumbers
## StringIntoCamelCase
## MergeAndSortTwoArray
## CreateDynamicArray
## CountFrequencyGivenOfDigit
## SortArray
## SelectionSort
## BinarySearch
## ReverseLinkedList
## ReverseLinkedListInPair
## MidElementInLinkedList
## LastNthItemInLinkedList
## GetLengthOfLinkedList
## ImplementStackUsingQueues
## ReverseStack
## ImplementQueuesUsingStack
## BindService
## ShuffleDeckOfCards
## DIDILogic
## 3_5LiterWaterPuzzle
## SpiderWebPuzzle





