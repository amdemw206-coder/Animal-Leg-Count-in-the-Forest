## Project Title: AD 311 Tech Interview Prep: Animal Leg Count in the Forest
#### By: Amde Wubshet

### FAQ: 
- Time Complexity: O(n) (Linear Time). 
- Space Complexity: O(1) (Constant Space). 
- #### How does the function work? 
    - Using iterative for loops and if conditions, the input array of animals gets scanned through to check how many elements in the array have four legged animals. The function checkLegs() accepts the input array "animals," and the function returns an accumlating "count" variable representing the amount of four legged animals in the array 

### Test Cases: 
- animals1 = ['lion', 'monkey', 'deer', 'snake', 'elephant']; // expected: 3
- animals2 = ['frog', 'horse', 'spider', 'ant']; // expected: 1
- animals3 = ['lion', 'lion', 'lion', 'snake']; // expected: 3

### Edge Cases: 
- animals4 = []; // expected: 0
- animals5 = 50; // expected: 0
- animals6 = ['Lion', 'DEER', 'ElePhAnt', 'ANT']; // expected: 3

### Flowchart
![alt text](https://github.com/amdemw206-coder/Animal-Leg-Count-in-the-Forest/blob/main/Flowchart/AD311TIP1drawio.png)

