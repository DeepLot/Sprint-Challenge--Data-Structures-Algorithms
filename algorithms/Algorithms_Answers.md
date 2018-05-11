Add your answers to the Algorithms exercises here.

Excercise 1 - 

a) O(n)
b) O(logn)
c) O(sqrt (n))
d) O(nlogn)
e) O(n^3)
f) O(n)
g) O(n)

Excercise 2 - 

a)

function maxDifference(arr) {
    let minVal = arr[0];
    let maxDiff = 0;

    for (let i = 0; i < arr.length; i++) {
        minVal = Math.min(minVal, arr[i]);
        maxDiff = Math.max(maxDiff, arr[i] - minVal);
    }

    return maxDiff;
}


b) 

Binary Search

Excercise 3 -

a) O(n^2) - the pivot is at one end of the sort

b) the complexity would always be O(n log n) if the pivot were in the middle and successfully divided by 2