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
- [Find missing number in sorted array](#MissingNumberInArray)
- [Find duplicate number in array](#DuplicateNumber)
- [Find second largest number in array](#SecondLargestNumber)
- [Find second smallest number in array](#SecondSmallestNumber)
- [Find subarray with given sum](#SubArrayOfGivenSum)
- [Find repeated substring in given paragraph](#RepeatedSubStringInParagraph)
- [Reverse array](#ReverseArray) 
- [Reverse same array](#ReverseSameArray) 
- [Star pyramid program](#StarPattern)
- [Count number of zeros in array(logN)](#CountNumberOfZero)
- [Check Leap year](#CheckLeapYear)
- [Seperate o's, 1's and 2's in array(HCL)](#Seperate012)
- [Intersection of two arrays(Paytm)](#IntersetionTwoArray)
- [Union of two arrays(Paytm)](#UnionTwoArray)
- [Intersection of three arrays(Paytm)](#IntersetionThreeArray)
- [Union of three arrays(Paytm)](#UnionThreeArray)
- [Find element in array (logN)](#FindElementInArray) 
- [Find length of repeated characters like **I/P->(aaabbbcdddaa)O/P->(a3b3cd3a2)**
	if character is available single time then enter character without it's value](#RepeatedCharacters)
- [Add two large string(Paytm)](#AddTwoLargeString)
- [Find the length of the longest sequence of consecutive numbers **(N) like I/P->(1,9,3,10,4,20,2) O/P->4(1,2,3,4)**](#LargeConsecutiveNumbersRange)
- [Convert snake case string into camel case **I/P->(my_test) O/P ->(myTest)(Nagarro)**](#SnakeCaseIntoCamelCase)
- [Convert camel case string into snake case **I/P->(myTest) O/P ->(my_test)(Nagarro)**](#CamelCaseIntoSnakeCase)
- [Merge sorted two array(M+N)](#MergeSortedTwoArray)
- [Create Dynamic Array as like arraylist using array](#CreateDynamicArray)
- [Count frequency of give digits(1) in an array like **I/P-(10,11,12,13) find 1 O/P-(5)**](#CountFrequencyGivenOfDigit)
- [Sort array (N)](#SortArray)
- [Selection Sort](#SelectionSort)
- [Binary search](#BinarySearch)
- [Find all triplets with zero sum (Paytm)](#FindAllTripletWithZeroSum)

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
- [Form the minimum number from the given sequence of characters.(Airtel)<br>
	D: Decreasing<br>
	I: Increasing<br>
	1-9 digits are allowed and you can not repeat the digits<br>
	First letter of the sequence corresponds to two digits<br>
	I/p D , o/p  21<br>
	i/p I , o/p  12<br>
	i/p DD  o/p 321<br>
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
	void swapElement() {
	  int a = 5;
	  int b = 10;
	  print("Before - A: $a,  B: $b");
	  a = a + b;
	  b = a - b;
	  a = a - b;
	  print("After - A: $a,  B: $b");
	}

    
## MissingNumberInArray
	void missingNumber() {
	  var array = [1, 2, 3, 5];
	  int n = array.length;
	  int sum = 0;
	  for (int i = 0; i < n; i++) {
		sum = sum + array[i];
	  }
	  var missingNumber = (((n + 2) * (n + 1)) / 2) - sum;
	  print("MissingNumber :  $missingNumber");
	}

## DuplicateNumber
	void duplicateElement() {
	  var array = [1, 2, 3, 2, 5, 5];
	  int n = array.length;
	  for (int i = 0; i < n; i++) {
		for (int j = i + 1; j < n; j++) {
		  if (array[i] == array[j]) {
			print("Duplicate Element : ${array[j]}");
		  }
		}
	  }
	}

## SecondLargestNumber
	void secLargestNumber() {
	  var array = [1, 2, 3, 2, 5, 5];
	  int largest = -1;
	  int secLargest = -1;

	  for (int i = 0; i < array.length; i++) {
		if (array[i] > largest) {
		  secLargest = largest;
		  largest = array[i];
		} else if (array[i] > secLargest && largest != array[i]) {
		  secLargest = array[i];
		}
	  }
	  print("Largest Number: $largest,\nSecond Largest Number: $secLargest");
	}

## SecondSmallestNumber
	void secSmallestNumber() {
	  var array = [5, 5, 1, 3];
	  int smallest = array[0];
	  int secSmallest = array[0];

	  for (int i = 0; i < array.length; i++) {
		if (array[i] < smallest) {
		  secSmallest = smallest;
		  smallest = array[i];
		} else if (array[i] < secSmallest && smallest != array[i]) {
		  secSmallest = array[i];
		}
	  }
	  print("Smallest Number: $smallest,\nSecond Smallest Number: $secSmallest");
	}

## SubArrayOfGivenSum
	void subArray() {
	  var array = [5, 5, 1, 3];
	  int givenSum = 9;
	  int currentSum = 0;

	  for (int i = 0; i < array.length; i++) {
		currentSum = array[i];
		for (int j = i + 1; j < array.length; j++) {
		  currentSum = currentSum + array[j];
		  if (currentSum == givenSum) {
			print("SubArray At position $i, $j");
		  }
		}
	  }
	}

## RepeatedSubStringInParagraph
	void repeatedString() {
	  var para = "Test My Code My Code";
	  var array = para.split(" ");
	  Map<String, int> map = Map();
	  for (int i = 0; i < array.length; i++) {
		if(map.containsKey(array[i])){
		  map[array[i]] = map[array[i]]!+1;
		}else{
		  map[array[i]] = 1;
		}
	  }
	  for(String keys in map.keys){
	   var value =  map[keys];
		if(value!>1){
		  print("Repeated String: $keys - $value times");
		}
	  }
	}

## ReverseArray
	void reverseList() {
	  var ipAarray = [10, 20, 30, 40];
	  int n = ipAarray.length - 1;
	  var opAarray = {};
	  for (int i = 0; i < ipAarray.length; i++) {
		opAarray[i] = ipAarray[n - i];
	  }
	  print("Reverse Array : $opAarray");
	}

## ReverseSameArray
	void reverseArray() {
	  var ipAarray = [10, 20, 30, 40];
	  int n = ipAarray.length - 1;
	  for (int i = 0; i < ipAarray.length/2; i++) {
	   // Swap
		var temp = ipAarray[n - i];
		ipAarray[n-i] = ipAarray[i];
		ipAarray[i] = temp;
	  }
	  print("Reverse Array : $ipAarray");
	}

## StarPattern
	void starPattern() {
	  int n = 5;
	  for (int i = 0; i < n; i++) {
		for (int j = 0; j < i; j++) {
		  print("*");
		}
		print("\n");
	  }
	}

## CountNumberOfZero
	void noOfZeros() {
	  String n = "111000011100";
	  int count = 0;
	  for (int i = 0; i < n.length; i++) {
		if (n[i] == '0') count++;
	  }
	  print("Number of zero : $count");
	}
**O/P : Number of zero : 6**

## CheckLeapYear
	void isLeapYear() {
	  var year = 2020;
	  if ((year % 4 == 0) && (year % 400 != 0) && (year % 400 == 0)) {
		print("$year is leap year");
	  } else {
		print("$year is not leap year");
	  }
	}
**O/P -> 2020 is not leap year**

## Seperate012
	void addString(String s1, String s2) {
	  int carry = 0;
	  var totalSum = "";
	  for (int i = 0; i < s1.length; i++) {
		var lastPos = s1.length - 1 - i;
		var sum = (int.parse(s1[lastPos]) + int.parse(s2[lastPos])).toString();
		if (sum.length > 1) {
		  totalSum = (int.parse(sum[1]) + carry).toString() + totalSum;
		  carry = int.parse(sum[0]);
		} else {
		  totalSum = (int.parse(sum) + carry).toString() + totalSum;
		  carry = 0;
		}
	  }
	  print("${totalSum}");
	}

## IntersetionTwoArray
	void printIntersection() {
	  var arr1 = [1, 3, 3, 5];
	  var arr2 = [2, 3, 5];
	  int m = arr1.length;
	  int n = arr2.length;
	  int i = 0;
	  int j = 0;

	  while (i < m && j < n) {
		if (arr1[i] < arr2[j]) {
		  i++;
		} else if (arr2[j] < arr1[i]) {
		  j++;
		} else {
		  print("value ${arr2[j]}");
		  i++;
		  j++;
		}
	  }
	}

**I/P -><br>
arr1 = {1, 3, 3, 5}<br>
arr2 = {2, 3, 5}**

**O/P -> {3,5}**

## UnionTwoArray
	void union() {
	  var arr1 = [1, 2, 4, 5, 6];
	  var arr2 = [2, 3, 5, 7];
	  int m = arr1.length;
	  int n = arr2.length;
	  int i = 0, j = 0;
	  while (i < m && j < n) {
		if (arr1[i] < arr2[j]) {
		  print("${arr1[i++]}");
		} else if (arr2[j] < arr1[i]) {
		  print("${arr2[j++]}");
		} else {
		  print("${arr2[j++]}");
		  i++;
		}
	  }
	  while (i < m) print("${arr1[i++]}");

	  while (j < n) print("${arr2[j++]}");
	}

**I/P -><br>
arr1 = {1, 2, 4, 5, 6}<br>
arr2 = {2, 3, 5, 7}**

**O/P -> {1,2,3,4,5,6}**

## IntersetionThreeArray
	void threeArrayIntersection() {
	  var arr1 = [1, 3, 3, 5];
	  var arr2 = [2, 3, 5];
	  var arr3 = [1, 3, 5];
	  int m = arr1.length;
	  int n = arr2.length;
	  int o = arr3.length;
	  int i = 0;
	  int j = 0;
	  int k = 0;
	  while (i < m && j < n && k < o) {
		if (arr1[i] == arr2[j] && arr2[j] == arr3[k]) {
		  print("value ${arr1[i]}");
		  i++;
		  j++;
		  k++;
		} else if (arr1[i] < arr2[j]) {
		  i++;
		} else if (arr2[j] < arr3[k]) {
		  j++;
		} else {
		  k++;
		}
	  }
	}
**I/P -><br>
arr1 = {1, 3, 3, 5}<br>
arr2 = {2, 3, 5}<br>
arr3 = {1, 3, 5}**

**O/P -> {3,5}**

## UnionThreeArray

## FindElementInArray
	void findElement(){
	  var arr = [1,5,56,9,4,5,4,46,4];
	  int key = 9;
	  for(int i=0;i<arr.length;i++){
		if(arr[i]==key){
		  print("Element found at $i position");
		}
	  }
	}
	
## RepeatedCharacters
	void repeatedCharacter() {
	  var arr = "DeepakSharma";
	  Map<String, int> map = Map();
	  for (int i = 0; i < arr.length; i++) {
		if (map.containsKey(arr[i])) {
		  map[arr[i]] = map[arr[i]]! + 1;
		} else {
		  map[arr[i]] = 1;
		}
	  }
	  print("O/P -> $map");
	}

**O/P -> {D: 1, e: 2, p: 1, a: 3, k: 1, S: 1, h: 1, r: 1, m: 1}**

## AddTwoLargeString

	void addString(String s1, String s2) {
	  int carry = 0;
	  var totalSum = "";
	  for (int i = 0; i < s1.length; i++) {
		var lastPos = s1.length - 1 - i;
		var sum = (int.parse(s1[lastPos]) + int.parse(s2[lastPos])).toString();
		if (sum.length > 1) {
		  totalSum = (int.parse(sum[1]) + carry).toString() + totalSum;
		  carry = int.parse(sum[0]);
		} else {
		  totalSum = (int.parse(sum) + carry).toString() + totalSum;
		  carry = 0;
		}
	  }
	  print("${totalSum}");
	}

## LargeConsecutiveNumbersRange
	void largeConsecutiveNumbersRange() {
	 var arr = [5,8,6,7,1,5,62,56,1,61,61,5];
	  Set<int> setValue = {};
	  
	  for(int i=0;i<arr.length;i++){
		setValue.add(arr[i]);
	  }
	  int ans=0;
	   for(int i=0;i<arr.length;i++){
		 if(setValue.contains(arr[i])){
		   int j = arr[i];
		   while(setValue.contains(j)){
			 j++;
			 if((j - arr[i])>ans)ans = j - arr[i];
		   }
		 }
	   }
	  print("Range is : $ans");
	}

## SnakeCaseIntoCamelCase
	void camelCaseString() {
	  var name = "my_new_class";
	  var arr = name.split("_");
	  var camelCaseName = '';
	  for (int i = 0; i < arr.length; i++) {
		var item = arr[i];
		if (i == 0) {
		  camelCaseName = item;
		} else {
		  camelCaseName = camelCaseName +
			  item[0].toUpperCase() +
			  (item.substring(1, item.length));
		}
	  }
	  print("Camel Case Name : $camelCaseName");
	}
**I/P -> 
String str = my_new_class**

**O/P -> Camel Case : myNewClass**

## CamelCaseIntoSnakeCase
	void snakeCaseString() {
	  var name = "myNewClass";
	  var snakeCaseName = '';
	  for (int i = 0; i < name.length; i++) {
		var item = name[i];
		if (item.toUpperCase() == item) {
		  snakeCaseName = snakeCaseName + "_" + item.toLowerCase();
		} else {
		  snakeCaseName = snakeCaseName + item;
		}
	  }
	  print("Camel to snake case : $snakeCaseName");
	}
**I/P -> 
String str = myNewClass**

**O/P -> Snake Case : my_new_class**

## MergeSortedTwoArray
	void mergeSortedArray() {
	  var arr1 = [1, 3,33e 5];
	  var arr2 = [2, 4, 6];
	  var arr3 = {};
	  int m = arr1.length;
	  int n = arr2.length;
	  int i = 0;
	  int j = 0;
	  int k = 0;

	  while (i < m && j < n) {
		if (arr1[i] < arr2[j]) {
		  arr3[k++] = arr1[i++];
		} else {
		  arr3[k++] = arr2[j++];
		}
	  }
	  while (i < m) {
		arr3[k++] = arr1[i++];
	  }

	  while (i < n) {
		arr3[k++] = arr2[j++];
	  }
	  print("Merge Array : $arr3");
	}
	
**I/P -> <br>
arr1 = {1,3,5}<br>
arr1 = {2,4,6}**

**O/P -> {1,2,3,4,5,6}**

## CreateDynamicArray
	public class DynamicArray {
		static int defaultSize = 2;
		static int[] arr = new int[defaultSize];
		static int currentSize = 0;

		public static void add(int value) {
			if (currentSize >= arr.length) {
				int[] temp = new int[arr.length + defaultSize];
				for (int i = 0; i < arr.length; i++) {
					temp[i] = arr[i];
				}
				arr = temp;
			}
			arr[currentSize] = value;
			currentSize++;
			printValue();
		}

		public static int add(int index, int value) {
			if (arr.length > index) {
				arr[index] = value;
				printValue();
				return value;
			}
			return -1;
		}

		public static int remove(int index) {
			if (arr.length > index) {
				int[] temp = new int[arr.length];
				int count = 0;
				for (int i = 0; i < arr.length; i++) {
					if (index != i) {
						temp[count] = arr[i];
						count++;
					}
				}
				arr = temp;
				printValue();
				return arr[index];
			}
			return -1;
		}

		public static int getSize() {
			return arr.length;
		}

		public static void printValue() {
			for (int i = 0; i < arr.length; i++) {
				System.out.println("Values : " + arr[i]);
			}
			System.out.println("\n\n\n\n");
		}
	}
**DynamicArray.add(1);<br>
      DynamicArray.add(2);<br>
      DynamicArray.add(3);<br>
      DynamicArray.add(4);<br>
      DynamicArray.add(8,9);<br>
      DynamicArray.remove(1);**
	
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





