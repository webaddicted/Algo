# Algorithm

This repository contain all frequency ask interview questions in data structure and algo.<br><br>
**Solution provide in two language :<br>
A) Dart<br>
B) Java**

**Online platform for execute these code :<br>
[Dart Online Platform](https://dartpad.dev/?)<br>
[Java Online Platform](https://www.tutorialspoint.com/compile_java_online.php)**

## Pending Task
- [ ] Find unique pair in list whose sum is 5 (Uber)
- [ ] Two linked list meet a point find that point like Y upper two arrow consider as linkedlist, and both list meet on a point find that point (Walmart) 
- [ ] Reverse left linked list from mid and Reverse reverse linked list from mid like 1>2>3>4>5>6 O/p..3>2>1>6>5>4(Delhivery)
- [ ] Merge two linkedlist
<!-- https://www.youtube.com/watch?v=siKFOI8PNKM -->
- [ ] 2D/Matrix print from outer then move to inner (Array in spiral order) (Delhivery) 
- [ ] UnionThreeArray
- [ ] DIDILogic(Airtel)

## ArrayList
- [Check Prime numbers](#PrimeNumber)
- [Palindrome Number](#Palindrome)
- [String Palindrome](#StringPalindrome)
- [Armstrong Number](#ArmstrongNumber)
- [Factorial Number](#FactorialNumber)
- [Fibonacci Series](#FibonacciSeries)
- [Anagram string](#AnagramString)**<br>I/P->(TAB) <br>O/P(BAT) true**
- [Swap two element without third element](#SwapElement)
- [Find missing number in sorted array](#MissingNumberInArray)
- [Find duplicate number in array](#DuplicateNumber)
- [Find second largest number in array](#SecondLargestNumber)
- [Find second smallest number in array](#SecondSmallestNumber)
- [Find subarray with given sum](#SubArrayOfGivenSum)
- [Find SubArray with GivenSum in Sorted Array](#SubArrayOfSortedArray)
- [Find repeated substring in given paragraph](#RepeatedSubStringInParagraph)
- [Reverse array](#ReverseArray) 
- [Reverse same array](#ReverseSameArray) 
- [Star pyramid program](#StarPattern)
- [Count number of zeros in array(logN)](#CountNumberOfZero)
- [Check Leap year](#CheckLeapYear)
<br><br><br>
- [Seperate o's, 1's and 2's in array **(HCL)**](#Seperate012)
- [Intersection of two arrays **(Paytm)**](#IntersetionTwoArray)
- [Union of two arrays **(Paytm)**](#UnionTwoArray)
- [Intersection of three arrays **(Paytm)**](#IntersetionThreeArray)
- [Union of three arrays **(Paytm)**](#UnionThreeArray)
- [Add two large string **(Paytm)**](#AddTwoLargeString)
- [Find the length of the longest sequence of consecutive numbers ](#LargeConsecutiveNumbersRange)**O(N) like :<br>I/P->(1,9,3,10,4,20,2) <br>O/P->4(1,2,3,4)**
- [Find pivot index in array whose left array sum equal to right array sum](#FindPivotIndexInArray)
- [Add Two Hexadecimal Numbers](#AddTwoHexadecimalNumbers)
- [Modulus Of Two Hexadecimal Numbers](#ModulusTwoHexadecimalNumbers)
- [Maximum Consecutive Ones III (If K 0's Flip is Allowed)](#MaximumConsecutiveOnesIfKFlipAllowed)
<br><br><br>
- [Find element in array (logN)](#FindElementInArray) 
- [Find length of repeated characters like :](#RepeatedCharacters)<br>**I/P->(aaabbbcdddaa)<br>O/P->(a3b3cd3a2)<br>
	if character is available single time then enter character without it's value**
- [Convert snake case string into camel case **(Nagarro)**](#SnakeCaseIntoCamelCase)**<br>I/P->(my_test) <br>O/P ->(myTest)**
- [Convert camel case string into snake case **(Nagarro)**](#CamelCaseIntoSnakeCase)**<br>I/P->(myTest) <br>O/P ->(my_test)**
- [Merge sorted two array(M+N)](#MergeSortedTwoArray)
- [Create Dynamic Array as like arraylist using array](#CreateDynamicArray)
- [Count frequency of give digits(1) in number ](#CountFrequencyGivenOfDigit)**like :<br>I/P-10111213 <br>find 1 O/P-(5)**
- [Shuffle deck of cards](#ShuffleDeckOfCards)
- [Sort array (N)](#SortArray)
- [Binary search](#BinarySearch)
- [Binary Rotated Search](#BinaryRotatedSearch)
- [Merge Sort](#MergeSort) **nLog(N)**
- [Find all triplets with zero sum **(Paytm)**](#FindAllTripletWithZeroSum)


## 2D Array / Matrix
- [Diagonals sums of a matrix](#DiagonalsSums)
- [Find transpose of a matrix (Make Row as column)](#FindTransposeMatrix)
- [Print a given matrix in spiral form (First Print outer then print inner)](#PrintSpiralMatrix)

## Linked list
- [Reverse Linked list](#ReverseLinkedList)
- [Reverse Linked list in pair **(Paytm)** ](#ReverseLinkedListInPair) **like : <br>I/P->(1-2-3-4-5) <br>O/P->(2-1-4-3-5)**
- [Find mid element in Linked List](#MidElementInLinkedList)
- [Find last nth element in Linked list](#LastNthItemInLinkedList)
- [Get length of Linked list](#GetLengthOfLinkedList)
- [Sort Linked list](#SortLinkedList)

## Stack
- [Implement stack using array](#ImplementStackUsingArray)
- [Implement a stack using queues **(Airtel)**](#ImplementStackUsingQueues)
- [Reverse a stack](#ReverseStack)
- [Check for Balanced Brackets in an expression (well-formedness) using Stack](#CheckBalancedBrackets)

## Queue
- [Implement a queues using stack](#ImplementQueuesUsingStack)

## Android
- [Bind Service](#BindService)
- [Local Broadcast Receiver](#LocalBrodcastReceiver)
- [Retrofit API Call](#RetrofitAPICall)
- [Room DB Migration](#RoomDBMigration)
- [LRU - Least Recently Used Cache](#LRU)
- [Observer Listener Multiple Place - Multiple Subscriber](#ObserverMultipleListener)

## Other
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
- [Three Bulbs And Three Switches Puzzle](#BlubAndSwitchPuzzle)
- [How will you measure 9 hours from two hourglasses of 7 hours and 4 hours?](#Hourglass9MintMeasure)

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
	
**Method - 2**

    void duplicateElement() {
        var array = [1, 2, 3, 2, 5, 5];
        Map<int, int> map = Map();
        for (int i = 0; i < array.length; i++) {
            if (map.containsKey(array[i])) {
                map[array[i]] = map[array[i]] !+1;
            } else {
                map[array[i]] = 1;
            }
        }
        for (int i = 0; i < array.length; i++) {
            if (map.containsKey(array[i]) && map[array[i]] ! > 1){
                print("Duplicate Element : ${array[i]} - ${map[array[i]]}");
            }
        }
    }
**Duplicate Element : 2 - 2<br>
Duplicate Element : 2 - 2<br>
Duplicate Element : 5 - 2<br>
Duplicate Element : 5 - 2**

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

## SubArrayOfSortedArray

    public static void findPairInSorted(int[] nums, int target) {
        // array is not sorted then First sort then find pair
	//        Arrays.sort(nums);
        int low = 0;
        int high = nums.length - 1;
        while (low < high) {
            // sum found
            if (nums[low] + nums[high] == target) {
                System.out.println("Pair found (" + nums[low] + "," +
                        nums[high] + ")");
                return;
            }
            // increment `low` index if the total is less than the desired sum;
            // decrement `high` index if the total is more than the desired sum
            if (nums[low] + nums[high] < target) {
                low++;
            } else {
                high--;
            }
        }
        // we reach here if the pair is not found
        System.out.println("Pair not found");
    }

**int[] nums = { 8, 7, 2, 5, 3, 1 };<br>
int target = 10;<br>
Pair found (2, 8)**


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
	  if (((year % 4 == 0) && (year % 100 != 0)) || (year % 400 == 0)) {
		print("$year is leap year");
	  } else {
		print("$year is not leap year");
	  }
	}
	
	if year is divisible by 400 then is_leap_year
	else if year is divisible by 100 then not_leap_year
	else if year is divisible by 4 then is_leap_year
	else not_leap_year

**O/P -> 2020 is leap year**

## Seperate012
	void seperate012() {
	  var arr = [0, 0, 2, 2, 1, 0, 1];
	  var li = 0;
	  var mid = 0;
	  var hi = arr.length - 1;
	  var temp = 0;
	  while (mid <= hi) {
		switch (arr[mid]) {
		  case 0:
			{
			  temp = arr[li];
			  arr[li] = arr[mid];
			  arr[mid] = temp;
			  li++;
			  mid++;
			  break;
			}
		  case 1:
			{
			  mid++;
			  break;
			}
		  case 2:
			{
			  temp = arr[hi];
			  arr[hi] = arr[mid];
			  arr[mid] = temp;
			  hi--;
			  break;
			}
		}
	  }
	  print("Print : $arr");
	}

**I/P -><br>
arr1 = [0, 0, 2, 2, 1, 0, 1]<br>**
**O/P -> Print : [0, 0, 0, 1, 1, 2, 2]**

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
			 print("values are : ${j-1}");
			 if((j - arr[i])>ans)ans = j - arr[i];
		   }
		 }
	   }
	  print("Range is : $ans");
	}
**values are : 5,6,7,8<br>	
Range is : 0**

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
**I/P :**<br>DynamicArray.add(1);<br>
      DynamicArray.add(2);<br>
      DynamicArray.add(3);<br>
      DynamicArray.add(8,9);<br>
      DynamicArray.remove(1);<br><br>
**O/P :**<br>
Add 1 : {1}<br>
Add 2 : {1,2}<br>
Add 3 : {1,2,3}<br>
Add 8 with index : {1,2,3}<br>
Remove 1 : {1,3}
	
## CountFrequencyGivenOfDigit
	void frequencyOfGivenDigit() {
	  var number = 10111213;
	  var givenNumber = 1;
	  var temp = number;
	  var count = 0;
	  while (temp > 0) {
		if (temp % 10 == givenNumber) {
		  count++;
		}
		temp = (temp / 10).toInt();
	  }
	  print("Count $count");
	}
	
**I/P -> Number = 10111213,  Given Number = 1 <br>O/P -> Count 5**

**O/P -> {1,2,3,4,5,6}**

## FindPivotIndexInArray
	void findPivotIndex(int pivotIndex) {
	  var arr = [1, 2, 5, 1, 2];
	  var leftSum = 0;
	  var rightSum = 0;

	  for (int i = 0; i < pivotIndex; i++) {
		leftSum = leftSum + arr[i];
	  }
	  for (int i = pivotIndex + 1; i < arr.length; i++) {
		rightSum = rightSum + arr[i];
	  }
	  if (leftSum == rightSum) {
		print("pivot index : $pivotIndex");
	  } else if (pivotIndex == arr.length - 1) {
		print("pivot index not available");
	  } else {
		findPivotIndex(++pivotIndex);
	  }
	}
**I/P -> arr = {1, 2, 5, 1, 2}<br>**
**O/P -> Pivot index : 2**
## ShuffleDeckOfCards
    public static void shuffleDeckOfCards() {
        int cardSize[] = {0, 1, 2, 3, 4, 5, 6, 7, 8,
                9, 10, 11, 12, 13, 14, 15,
                16, 17, 18, 19, 20, 21, 22,
                23, 24, 25, 26, 27, 28, 29,
                30, 31, 32, 33, 34, 35, 36,
                37, 38, 39, 40, 41, 42, 43,
                44, 45, 46, 47, 48, 49, 50,
                51};
        
        Random ran = new Random();
        int numberOfCard = cardSize.length;
        for (int i = 0; i < numberOfCard; i++) {
            int randomPos = i + ran.nextInt(numberOfCard - i);
            int temp = cardSize[i];
            cardSize[i] = cardSize[randomPos];
            cardSize[randomPos] = temp;
        }
        for (int i = 0; i < numberOfCard; i++)
            System.out.print(cardSize[i] + " ");
    }
    
## SortArray
	void sort() {
	  var arr = [5, 4, 2, 1];
	  var isSorted = false;
	  while (!isSorted) {
		isSorted = true;
		for (int i = 0; i < arr.length - 1; i++) {
		  if (arr[i] > arr[i + 1]) {
			var temp = arr[i];
			arr[i] = arr[i + 1];
			arr[i + 1] = temp;
			isSorted = false;
		  }
		}
	  }
	  print("Sorted array :  $arr");
	}
**I/P -> arr = {5, 4, 2, 1}<br>**
**O/P -> Sorted array :  [1, 2, 4, 5]**

## BinarySearch
	void binarySearch() {
	  var arr = [1, 2, 3, 4, 5, 6, 7];
	  var item = 2;
	  var li = 0;
	  var hi = arr.length;
	  var mid = ((hi + li) / 2).toInt();

	  while (li <= hi) {
		if (arr[mid] == item) {
		  print("Item $item find at Index $mid");
		  break;
		} else if (arr[mid] < item) {
		  li = mid + 1;
		} else {
		  hi = mid - 1;
		}
		mid = ((hi + li) / 2).toInt();
	  }
	}
**I/P -> arr = {1, 2, 3, 4, 5, 6, 7}<br>**
**O/P -> Item 2 find at Index 1**

## BinaryRotatedSearch

	void binaryRotatedSearch() {
	  var arr = [4, 5, 6, 7, 1, 2, 3];
	  var item = 2;
	  var li = 0;
	  var hi = arr.length;
	  var mid = ((hi + li) / 2).toInt();
	  while (li <= hi) {
	    if (arr[mid] == item) {
	      print("Item $item find at Index $mid");
	      break;
	    } else if (arr[li] <= arr[mid]) {
	      // left array is sorted
	      if (item >= arr[li] && item < arr[mid]) {
	        // target lies between start and mid index
	        hi = mid - 1;
	      } else {
	        li = mid + 1;
	      }
	    } else {
	      // right array is sorted
	      if (item > arr[mid] && item <= arr[hi]) {
	        // target lies between mid and end index
	        li = mid + 1;
	      } else {
	        hi = mid - 1;
	      }
	    }

	    mid = ((hi + li) / 2).toInt();
	  }
	}

**I/P -> arr = {4, 5, 6, 1, 2, 3}<br>**
**O/P -> Item 2 find at Index 4**


## MergeSort

    static int array[] = {5, 7, 6, 4, 1, 2, 3};

    public static void mergeSortData() {
        divide(0, array.length - 1);
    }

    // Recursive algorithm for merge sort
    public static void divide(int start, int end) {
        int mid = (start + end) / 2;
        if (start < end) {
            // divide left half
            divide(start, mid);
            // divide right half
            divide(mid + 1, end);
            // Merge left and right half
            merge(start, mid, end);
        }
    }

    private static void merge(int start, int mid, int end) {
        // Initializing temp array and index
        int[] tempArray = new int[array.length];
        int tempArrayIndex = start;
        int startIndex = start;
        int midIndex = mid + 1;

        // It will iterate until smaller list reaches to the end
        while (startIndex <= mid && midIndex <= end) {
            if (array[startIndex] < array[midIndex]) {
                tempArray[tempArrayIndex++] = array[startIndex++];
            } else {
                tempArray[tempArrayIndex++] = array[midIndex++];
            }
        }
        // Copy remaining elements
        while (startIndex <= mid) {
            tempArray[tempArrayIndex++] = array[startIndex++];
        }
        while (midIndex <= end) {
            tempArray[tempArrayIndex++] = array[midIndex++];
        }
        // Temp array is sorted array & array is origional array
        // now copy temp array into array
        for (int i = start; i <= end; i++) {
            array[i] = tempArray[i];
        }

        Log.d("TAG", "After merging:   ");
        printArray(tempArray, start, end);
        System.out.println();
    }

    public static void printArray(int arr[], int start, int end) {
        for (int i = 0; i < arr.length; i++) {
            Log.d("TAG", "Sorted : " + arr[i] + " ");
        }
        System.out.println();
    }


## FindAllTripletWithZeroSum
	void findTriplets() {
	  var arr = [1, 2, 5, 8, 9, -1, -2];
	  for (int i = 0; i < arr.length; i++) {
		for (int j = 0; j < arr.length; j++) {
		  for (int k = 0; k < arr.length; k++) {
			if (arr[i] + arr[j] + arr[k] == 0) {
			  print("Triplets whose sum is zero ${arr[i]}+${arr[j]}+${arr[k]}==0");
			}
		  }
		}
	  }
	}
Triplets whose sum is zero 1+1+-2==0<br>
Triplets whose sum is zero 1+-2+1==0<br>
Triplets whose sum is zero 2+-1+-1==0<br>
Triplets whose sum is zero -1+2+-1==0<br>
Triplets whose sum is zero -1+-1+2==0<br>
Triplets whose sum is zero -2+1+1==0<br>

## AddTwoHexadecimalNumbers
	void hexadecimalSum() {
	  var str1 = "AD";
	  var str2 = "1B";
	  Map<String, int> map = Map();
	  map["0"] = 0;
	  map["1"] = 1;
	  map["2"] = 2;
	  map["3"] = 3;
	  map["4"] = 4;
	  map["5"] = 5;
	  map["6"] = 6;
	  map["7"] = 7;
	  map["8"] = 8;
	  map["9"] = 9;
	  map["A"] = 10;
	  map["B"] = 11;
	  map["C"] = 12;
	  map["D"] = 13;
	  map["E"] = 14;
	  map["F"] = 15;
	  Map<int, String> map1 = Map();
	  map1[0] = "0";
	  map1[1] = "1";
	  map1[2] = "2";
	  map1[3] = "3";
	  map1[4] = "4";
	  map1[5] = "5";
	  map1[6] = "6";
	  map1[7] = "7";
	  map1[8] = "8";
	  map1[9] = "9";
	  map1[10] = "A";
	  map1[11] = "B";
	  map1[12] = "C";
	  map1[13] = "D";
	  map1[14] = "E";
	  map1[15] = "F";
	  var carry = 0;
	  var totalSum = '';
	  for (int i = 0; i < str1.length; i++) {
		var lastIndex = str1.length - 1 - i;
		var sum = map[str1[lastIndex]]! + map[str2[lastIndex]]! + carry;
		if (sum > 15) {
		  var restAmount = sum - 16;
		  carry = 1;
		  totalSum = "${map1[restAmount]}$totalSum";
		} else {
		  carry = 0;
		  totalSum = "${map1[sum]}$totalSum";
		}
	  }
	  print("Hexadecimal Sum : $totalSum");
	}

**Hexadecimal Sum : C8**

## AddTwoHexadecimalNumbers

    public static void hexadecimalSum(String N, String k) {
        String str1 = "AD";
        String str2 = "1B";
        long one = Long.parseLong(str1, 16);
        long two = Long.parseLong(str2, 16);
        long longSum = one + two;
        String result = Long.toHexString(longSum);
        System.out.print("Hexadecimal Sum : " + result);
    }
 
**Hexadecimal Sum : AD + 1B = C8**

## ModulusTwoHexadecimalNumbers

    public static void hexadecimalModulus() {
        String str1 = "3E8";
        String str2 = "13";
        long one = Long.parseLong(str1, 16);
        long two = Long.parseLong(str2, 16);
        long longSum = one % two;
        String result = Long.toHexString(longSum);
        Log.d("TAG", "Hexadecimal Sum : " + result);
    }

**Hexadecimal Modulus : 3E8 % 13 = C**

## MaximumConsecutiveOnesIfKFlipAllowed
<!-- https://www.youtube.com/watch?v=TAMLsfGiyOg -->
	int maxConsecutiveCount() {
	  var arr = [1, 1, 0, 0, 0, 1, 0, 0, 1, 1];
	  var k = 2;
	  var zeroCount = 0;
	  var start = 0;
	  var maxConsecutiveCount = 0;
	  for (int i = 0; i < arr.length; i++) {
		if (arr[i] == 0) {
		  zeroCount++;
		}

		while (zeroCount > k) {
		  if (arr[start] == 0) {
			zeroCount--;
		  }
		  start++;
		}
		var countSum = i - start + 1;
		print("$countSum  $maxCoun");
		if (countSum > maxConsecutiveCount) {
		  maxConsecutiveCount = countSum;
		} else {
		  maxConsecutiveCount = maxConsecutiveCount;
		}
	  }
	  return maxConsecutiveCount;
	}

**I/P -> arr = {1, 1, 0, 0, 0, 1, 0, 0, 1, 1}<br>**
**O/P -> Max Consecutive Count : 5**


## DiagonalsSums

    static void printDiagonalSums(int [][]array){
        int n = array.length;
        int principal = 0, secondary = 0;
        for (int i = 0; i < n; i++) {
            principal = array[i][i] + principal;
            secondary = array[i][n - i - 1] + secondary;
        }
        System.out.println("Principal Diagonal:" + principal);
        System.out.println("Secondary Diagonal:" + secondary);
    }
    
**Input : <br>
1 2 3 4<br>
4 3 2 1<br>
7 8 9 6<br>
6 5 4 3<br>
Output :<br>
Principal Diagonal: 16<br>
Secondary Diagonal: 20**<br>    

## FindTransposeMatrix

    static void transpose(int a[][],int b[][]) {
        int i, j;
        int n = a.length;
        for (i = 0; i < n; i++)
            for (j = 0; j < n; j++)
                b[i][j] = a[j][i];
    }

**Input : <br>
1 2 3 <br>
4 5 6 <br>
7 8 9<br>
Output :<br>
1 4 7 <br>
2 5 8 <br>
3 6 9<br>**

## PrintSpiralMatrix

    public static void spiralMatrixPrint(int[][] arr) {

        int rows = arr.length;
        int cols = arr[0].length;
        // Defining the boundaries of the matrix.
        int top = 0, bottom = rows - 1, left = 0, right = cols - 1;

        // Defining the direction in which the array is to be traversed.
        int dir = 1;

        while (top <= bottom && left <= right) {

            if (dir == 1) {    // moving left->right
                for (int i = left; i <= right; ++i) {
                    System.out.print(arr[top][i] + " ");
                }
                // Since we have traversed the whole first
                // row, move down to the next row.
                ++top;
                dir = 2;
            } else if (dir == 2) {     // moving top->bottom
                for (int i = top; i <= bottom; ++i) {
                    System.out.print(arr[i][right] + " ");
                }
                // Since we have traversed the whole last
                // column, move left to the previous column.
                --right;
                dir = 3;
            } else if (dir == 3) {     // moving right->left
                for (int i = right; i >= left; --i) {
                    System.out.print(arr[bottom][i] + " ");
                }
                // Since we have traversed the whole last
                // row, move up to the previous row.
                --bottom;
                dir = 4;
            } else if (dir == 4) {     // moving bottom->up
                for (int i = bottom; i >= top; --i) {
                    System.out.print(arr[i][left] + " ");
                }
                // Since we have traversed the whole first
                // col, move right to the next column.
                ++left;
                dir = 1;
            }
        }
    }
**Input : <br>
1 2 3 <br>
4 5 6 <br>
7 8 9<br>
Output : 1,2,3,6,9,8,7,4,5**

## ReverseLinkedList
    void reverseLinkedList(Node head) {
        //        1>2>3>4
        Node pre = null;
        Node current = head;
        Node next = null;
        while (current != null) {
            next = current.next;//2
            current.next = pre;//null
            pre = current;//1
            current = next;//2
        }
        head = pre;
        Log.d("TAG", "Reverse Linked List : ");
        display();
        //        In this way we reverse pointer
        //        after every iteration current and next move at next position

        //       List - 1>2>3>4
        //       After 1st Iteration- null>1, 2>3>4
        //        After 2st Iteration- null<1<2, 3>4
        //        After 3st Iteration- null<1<2<3, 4
        //        After 4st Iteration- null<1<2<3<4
        //        finally O/P :  4>3>2>1>null
    }

**I/P -> list = 1>2>3>4<br>**
**O/P -> list = 4>3>2>1**
    
## ReverseLinkedListInPair
    void reverseInPair() {
        Node current = head;
        while (current != null && current.next != null) {
        //            Swap Data in pair
            int temp = current.data;
            current.data = current.next.data;
            current.next.data = temp;
            current = current.next.next;
        }
        Log.d("TAG", "Reverse Data in Pair");
        display();
    }

**I/P -> list = 1>2>3>4>5>6<br>**
**O/P -> list = 2>1>4>3>6>5**
        
## MidElementInLinkedList
    void findMidElement(Node node){
        Node slowPtr = node;
        Node fastPtr = node;

        while(fastPtr!=null && fastPtr.next!=null){
            fastPtr = fastPtr.next.next;
            slowPtr = slowPtr.next;
        }
        print("Mid element ${slowPtr.data}");
    }
**I/P -> list = 1>2>3>4>5>6>7<br>**
**O/P -> Mid Element - 4**

## LastNthItemInLinkedList
**Method - 1<br>**
In this method first calculate length of linkedlist and then find element

    void printNthFromLast(Node head, int n) {
        Node current  = head;
        int lengthOfList  = 0;
        while (current!=null){
            lengthOfList++;
            current = current.next;
        }
        current  = head;
        int currentCount = 0;
        while (current!=null){
            if((lengthOfList-currentCount)==n){
                Log.d("TAG", "Last "+n+" item is : " + current.data);
                break;
            }else {
                currentCount++;
            }
            current = current.next;
        }
    }
    
**I/P -> list = 1>2>3>4>5  N- 2<br>**
**O/P -> Last 2 item is : 4**

**Method - 2<br>**
In this method first reverse linkedlist and then find element from starting n item.

    void printNthFromLast(Node head, int n) {
        Node pre = null;
        Node current = head;
        Node next = null;
        while (current != null) {
            next = current.next;
            current.next = pre;
            pre = current;
            current = next;
        }
        current = pre;
        for (int i = 1; i <= n; i++) {
            if (i == n) {
                Log.d("TAG", "Last " + n + " item is : " + current.data);
                break;
            } else {
                current = current.next;
            }
        }
    }
    
**I/P -> list = 1>2>3>4>5  N- 2<br>**
**O/P -> Last 2 item is : 4**
    
## GetLengthOfLinkedList
    void getLength() {
        Node current = head;
        int count = 0;
        while (current != null) {
            current = current.next;
            count++;
        }
        Log.d("TAG", "Size of LinkedList : " + count);
        Log.d("TAG", ".");
    }
**I/P -> list = 1>2>3>4>5>6>7<br>**
**O/P -> Size of LinkedList : 7**
    
## SortLinkedList
	void sortList(Node head) {
	  Node current = head;
	  Node index = null;
	  int temp;
	  if (head == null) {
		return;
	  } else {
		while (current != null) {
		  index = current.next;
		  while (index != null) {
			if (current.data > index.data) {
			  temp = current.data;
			  current.data = index.data;
			  index.data = temp;
			}
			index = index.next;
		  }
		  current = current.next;
		}
	  }
	}
	
## ImplementStackUsingArray
    class MyStack {
        int[] arr;
        int top;

        MyStack(int size) {
            arr = new int[size];
            top = -1;
        }

        void push(int x) {
            if (top >= arr.length) {
                System.out.print("OverFlow");
            } else {
                arr[++top] = x;
            }
        }

        int pop() {
            if (top < 0) {
                System.out.print("UnderFlow");
                return -1;
            } else {
                return arr[top--];
            }
        }

        int top() {
            if (top < 0) {
                System.out.print("UnderFlow");
                return -1;
            } else {
                return arr[top];
            }
        }
    }

## ImplementStackUsingQueues
<!-- https://www.youtube.com/watch?v=jDZQKzEtbYQ -->
**Step 1 : Push()<br>1) x element add into queue<br>2) q1.add(q1.remove()); untill size-1 queue**

	public class Test {
		static Queue<Integer> q1 = new LinkedList();

		public static void push(Integer x) {
			q1.add(x);
			for (int i = 0; i < q1.size() - 1; i++) {
				q1.add(q1.remove());
			}
		}

		public static Integer pop() {
			if (q1.isEmpty()) return -1;
			return q1.remove();
		}

		public static Integer top() {
			return q1.peek();
		}

		public static void print() {
			for (int i = 0; i < q1.size(); i++) {
				System.out.println("" + q1.element());
			}
		}
	}

## ReverseStack
	public class Test {
		public static Stack<Integer> s1 = new Stack<>();
		public static Stack<Integer> s2 = new Stack<>();

		public static void push() {
			s1.push(1);
			s1.push(2);
			s1.push(3);
			s1.push(4);
		}

		public static void reverse() {
			for (int i =0; i<s1.size();i++){
				s2.push(s1.elementAt(s1.size()-1-i));
			}
			s1.addAll(s2);
		}
	}
**I/P -> arr = {1, 2, 3, 4}<br>**
**O/P -> arr = {4, 3, 2, 1}**

## CheckBalancedBrackets
	public class Test {
		public static Stack<Character> s1 = new Stack<>();

		public static boolean isBracketBalance() {
			String str = "([{}])";
			for (int i = 0; i < str.length(); i++) {
				char item = str.charAt(i);
				if (item == '(' || item == '{' || item == '[') {
					s1.push(item);
					continue;
				}
				char check;
				switch (item) {
					case ')': {
						check = s1.pop();
						if (check == '{' || check == '[')
							return false;
						break;
					}
					case '}': {
						check = s1.pop();
						if (check == '(' || check == '[')
							return false;
						break;
					}
					case ']': {
						check = s1.pop();
						if (check == '(' || check == '{')
							return false;
						break;
					}

				}
			}
			return s1.isEmpty();
		}
	}
**Is Bracket Balance : false**

## ImplementQueuesUsingStack
<!-- https://www.youtube.com/watch?v=3Et9MrMc02A&t=156s -->
**Step 1 : Push()<br>1) s1 transfer to s2<br>2) x value add to s1<br>3) s2 transfer to s1 back**

	public class Test {
		static Stack<Integer> s1 = new Stack<>();
		static Stack<Integer> s2 = new Stack<>();

		public static void push(Integer x) {
			while (!s1.empty()) {
				s2.push(s1.pop());
			}
			s1.push(x);
			while (!s2.empty()) {
				s1.push(s2.pop());
			}
		}

		public static Integer pop() {
			if (s1.isEmpty()) return -1;
			return s1.pop();
		}

		public static Integer top() {
			return s1.peek();
		}

		public static void print() {
			for (int i = 0; i < s1.size(); i++) {
				System.out.println("" + s1.elements());
			}
		}
	}
	
## BindService

**This service generate randam number and print in activity**

    class MyBoundService : Service() {
        val iBinder = MyBinder()
        val randomNumberLiveData: MutableLiveData<Int> = MutableLiveData()
        override fun onBind(intent: Intent?): IBinder {
            return iBinder
        }
    
        override fun onCreate() {
            super.onCreate()
            Handler(Looper.getMainLooper()).postDelayed({
                val randomNumber = Random().nextInt(100)
                randomNumberLiveData.postValue(randomNumber)
            }, 1000)
        }
    
        inner class MyBinder : Binder() {
            val service: MyBoundService get() = this@MyBoundService
        }
    }
    
**In Activity Create Connection which pass when service start**

    private val serviceConnection = object : ServiceConnection {
        override fun onServiceConnected(className: ComponentName, iBinder: IBinder) {
            val binder = iBinder as MyBoundService.MyBinder
            val mService = binder.service
            mService.randomNumberLiveData.observe(this@MainActivity, Observer {
                resultTextView?.text = "Random number from service: $it"
            })
        }

        override fun onServiceDisconnected(arg0: ComponentName) {
            Log.d("TAG", "ServiceConnection: disconnected from service.")
            mIsBound = false
        }
    }
    
    private fun bindService() {
        Intent(this, MyBoundService::class.java).also { intent ->
            bindService(intent, serviceConnection, Context.BIND_AUTO_CREATE)
        }
    }
    
    private fun unbindService() {
        Intent(this, MyBoundService::class.java).also { intent ->
            unbindService(serviceConnection)
        }
    }

## LocalBrodcastReceiver
**In Activity register, unregister receiver and event fire from service**

    override fun onPause() {
        LocalBroadcastManager.getInstance(this).unregisterReceiver(mMessageReceiver)
        super.onPause()
    }

    override fun onResume() {
        LocalBroadcastManager.getInstance(this).registerReceiver(
            mMessageReceiver, IntentFilter("custom-event-name")
        )
        super.onResume()
    }

    private val mMessageReceiver: BroadcastReceiver = object : BroadcastReceiver() {
        override fun onReceive(context: Context, intent: Intent) {
            val message = intent.getStringExtra("message")
            Log.d("receiver", "Got message: $message")
        }
    }
    
    private fun sendMessage() {
        Log.d("sender", "Broadcast Receiver : can call from service message")
        val intent = Intent("custom-event-name")
        intent.putExtra("message", "This is my message!")
        LocalBroadcastManager.getInstance(this).sendBroadcast(intent)
    }
## RetrofitAPICall
        fun getRetrofit(@ApplicationContext context: Context): Retrofit {
            return Retrofit.Builder()
            .baseUrl(BuildConfig.BASE_URL)
            .addCallAdapterFactory(CoroutineCallAdapterFactory())
            .addConverterFactory(GsonConverterFactory.create())
            .client(provideOkHttpClient(context))
            .build()
         }

        private fun provideOkHttpClient(context: Context): OkHttpClient {

	  val okHttpClientBuilder = OkHttpClient.Builder()
          okHttpClientBuilder.connectTimeout(ApiConstant.API_TIME_OUT, TimeUnit.SECONDS)
          okHttpClientBuilder.readTimeout(ApiConstant.API_TIME_OUT, TimeUnit.SECONDS)
          okHttpClientBuilder.writeTimeout(ApiConstant.API_TIME_OUT, TimeUnit.SECONDS)

          val interceptor = HttpLoggingInterceptor()
	  //    TODO print response
          interceptor.level = HttpLoggingInterceptor.Level.BODY
	  //        okHttpClientBuilder.addNetworkInterceptor(StethoInterceptor())
	  //        if (BuildConfig.DEBUG)interceptor.level = HttpLoggingInterceptor.Level.BODY
	  //        if (BuildConfig.DEBUG)okHttpClientBuilder.addNetworkInterceptor(StethoInterceptor())
          okHttpClientBuilder.addInterceptor(interceptor)
          okHttpClientBuilder.addInterceptor(TokenInterceptor())
          val authenticator = TokenAuthenticator(context)
          okHttpClientBuilder.authenticator(authenticator)
          return okHttpClientBuilder.build()
        }
	
**Call Api from Activity/Fragment**

        RetrofitInstance.ApiServiceInterface().registration(
                email.getText().toString().trim(),
                password.getText().toString().trim(),
                new Callback<SignUpResponse>() {
                    @Override
                    public void success(SignUpResponse signUpResponse, Response response) {
                        // in this method we will get the response from API
                        Toast.makeText(MainActivity.this, signUpResponse.getMessage(), Toast.LENGTH_SHORT).show();
                    }

                    @Override
                    public void failure(RetrofitError error) {
                        // if error occurs in network transaction then we can get the error in this method.
                        Toast.makeText(MainActivity.this, error.toString(), Toast.LENGTH_LONG).show();
                    }
                });


## RoomDBMigration
**In case of fallbackToDestructiveMigration() it delete all table and create new one again.**

     Room.databaseBuilder(
          context,
          AppDatabase::class.java,//abstract class all DAO mention in this file
          ApiConstant.DB_NAME
      ).addMigrations(MIGRATION_1_2).build()
	
     private val MIGRATION_1_2: Migration = object : Migration(1, 2) {
         override fun migrate(database: SupportSQLiteDatabase) {
             database.execSQL(
                """
                CREATE TABLE commitmentSheet (
                    id TEXT PRIMARY KEY NOT NULL,
                    commitmentType TEXT NOT NULL,
                    commitmentDetails TEXT NOT NULL,
                    targetDate TEXT NOT NULL,
                    signImg TEXT NOT NULL,
                    isImgSynced INTEGER NOT NULL
                 )
                 """.trimIndent()
             )
         }
     }

	
## LRU
<!-- https://www.youtube.com/watch?v=N-GGrDK_Ev8 -->
    class CacheData {
    String imgUrlAsKey;
    String bitmap;

    CacheData(String imgUrlAsKey, String bitmap) {
        this.imgUrlAsKey = imgUrlAsKey;
        this.bitmap = bitmap;
       }
    }

    public class ImageCache {
        Deque<CacheData> q = new LinkedList<>();
        Map<String, CacheData> map = new HashMap<>();
        int CACHE_SIZE = 3;
    
        public String getCacheImg(String imgUrlKey) {
            if (map.containsKey(imgUrlKey)) {
                CacheData data = map.get(imgUrlKey);
                q.remove(data);
                q.addFirst(data);
                return data.bitmap;
            }
            return null;
        }
    
        public void putImgInCache(String imgUrlKey, String bitmap) {
            if (map.containsKey(imgUrlKey)) {
                q.remove();
            } else {
                if (CACHE_SIZE == q.size()) {
                    CacheData removeLast = q.removeLast();
                    map.remove(removeLast.imgUrlAsKey);
                }
            }
            CacheData data = new CacheData(imgUrlKey, bitmap);
            q.addFirst(data);
            map.put(imgUrlKey, data);
        }
    }
    
**ImageCache cache = new ImageCache();<br>
cache.putImgInCache("Img1", "Bitmap 1");<br>
cache.putImgInCache("Img2", "Bitmap 2");<br>
cache.putImgInCache("Img3", "Bitmap 3");<br>
cache.putImgInCache("Img4", "Bitmap 4");<br>
System.out.println(cache.getCacheImg("Img2"));<br>
System.out.println(cache.getCacheImg("Img3"));**

## ObserverMultipleListener
Implement observer design pattern where user can subscribe catagory at multiple place.

    public class EventManager {
        Map<String, List<EventListener>> listeners = new HashMap<>();
    // String key is type of subscriber, it could be category, details
    // EventListener is list of interfaces, when screen is open then subscribe with listener
        public EventManager(String... operations) {
            for (String operation : operations) {
                this.listeners.put(operation, new ArrayList<>());
            }
        }

        public void subscribe(String eventType, EventListener listener) {
            List<EventListener> users = listeners.get(eventType);
            users.add(listener);
        }

        public void unsubscribe(String eventType, EventListener listener) {
            List<EventListener> users = listeners.get(eventType);
            users.remove(listener);
        }

        public void notify(String eventType, File file) {
            List<EventListener> users = listeners.get(eventType);
            for (EventListener listener : users) {
                listener.update(eventType, file);
            }
        }
    }
    
## DIDILogic

## 3_5LiterWaterPuzzle
**Suppose you have a 3 liter jug and a 5 liter jug (this could also be in gallons). The jugs have no measurement lines on them either. How could you measure exactly 4 liter using only those jugs and as much extra water as you need?**

    - Fill the 3 litre can from the tap.
    - Empty the contents of the 3 litre can into the 5 litre can.
    - Fill the 3 litre can from the tap.
    - Empty the contents of the 3 litre can into the 5 litre can. - Leaving the 5 litre can full and 1 litre in the 3 litre can.
    - Pour away the contents of the 5 litre can
    - Pour the 1 litre from the 3 litre can into the 5 litre can.
    - Fill the 3 litre can from the tap.
    - Empty the contents of the 3 litre can into the 5 litre can.
    - Leaving 4 litres in the 5 litre can.
    
## SpiderWebPuzzle
**A spider is trying to build a web for itself. It doubles the work done everyday.
If the spider completely built the web in 15 days, how many days did it take for the spider to build 25% of the web ?**

    - 13 days will take for 25% of the web.
    - 15 Days for 100%
    - 14 days for 50%
    - 13 days for 25%
    - 12 days for 12.5%

## BlubAndSwitchPuzzle
**There is a room with a door (closed) and three light bulbs. Outside the room, there are three switches, connected to the bulbs. You may manipulate the switches as you wish, but once you open the door you can’t change them. Identify each switch with its bulb. All bulbs are in working condition.**

    Let the bulbs be X, Y, and Z
    Turn on switch X for 5 to 10 minutes. Turn it off and turn on switch Y. Open the door and touch the light bulb.
    1. the light is on from the bulb, it is Y Now we will check other two off bulbs
    2. the bulb which is hot, it is X
    3. the bulb which is cold, it is Z

## Hourglass9MintMeasure

		When the 4-min timer is empty for the second time, the 7-min timer has 1 minute worth of sand in the bottom half.
		Flip it over so there is now 1 minute in the top. When the 7-min timer empties, 9 minutes have elapsed.


