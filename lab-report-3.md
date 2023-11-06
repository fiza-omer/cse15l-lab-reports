# LAB REPORT 3: CSE15L
---
## P1

**A failure-inducing input for the buggy program, as a JUnit test and any associated code (write it as a code block in Markdown)**

```
	@Test 
	public void testReverseInPlaceBetterTest() {
    int[] inputT2 = { 2,4,6,8,10,12 };
    ArrayExamples.reverseInPlace(inputT2);
    assertArrayEquals(new int[]{12,10,8,6,4,2}, inputT2);
	}

```


**An input that doesn’t induce a failure, as a JUnit test and any associated code (write it as a code block in Markdown)**

```
	@Test 
	public void testReverseInPlaceAlwaysRightButWrong() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}
```
