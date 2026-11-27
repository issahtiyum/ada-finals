# Group 4: Counting Important Cross Period Pairs

Haris Issah: 41942028

Gabriel Akurang: 35882028

Ewurakoa Amoah: 74492028

Ebow Esselfie: 88872028


```
Flow

Merge/ Brute Force ->Testing -> Experiment-> Counts-> Graph
```

## Setup

```bash
pip install -r requirements.txt

```

## What you need in place

| File | Purpose |
|---|---|
| `final_project_group4` | Jupyter notebook containing brute-force implementation, modified merge sort implementation,tests and experiment |




To do: install libraries in requirements.txt

## Description
The code seeks to export two algorithmic approaches to counting important cross pairs. The condition was to count pairs satisfying the condition:

**Given integers** a<sub>1</sub>, …, a<sub>n</sub>, count pairs satisfying i &lt; j and a<sub>i</sub> &gt; 2a<sub>j</sub>.

**Brute Force**- The brute force approach is a straightfoward approach whereby an index i>0 is picked  and we check from index i+1 to n matches the condition statement, resulting in a time complexity of O$(n^2)$ since every element is checked with all remaining elements.

**Modified Mergesort**- The mergesort combines the functionality of the basic mergesort algorithm whilst adding a counter to the merge algorithm. This results in a time complexity of O$(nlogn)$

**Testing**- The tests contained a series of varying arrays whihc tested various use cases of both algorithms. The results are presented in a tabular format displaying each array, the manually verified result and the result of both algorithm. 

**Experimentation**- The experiment compares the differences in the number of comparisms and running times between the brute force and merge sort algorithms of arrays of different sizes and criteria such as duplicates and negative values. The results are visually represented as graphs. 




## Project structure

```
final_project_group4.ipynb #Implementation and testing of the counting imoorant cross period pairs

README #instructions

requirements.txt #libraries to be downloaded before running the jupyter notebook

```
