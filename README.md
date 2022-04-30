# Data-manipulation-with-python. 

## objective statment
 <ul>

  <li>Object Series</li>

  <li>Creating a series from array</li>

  <li>Accessing element of Series</li>
 <li>Accessing Element from Series with Position</li>
 li>Accessing Element Using Label (index)</li>
</ul>

## Challenge
<ul>
  <li>Change the Data into Series</li>
  <li>Convert Series into Array</li>
  <li>How to call data </li>
</ul>

## Analytic technictechnicquie Loc dan iLoc
<ul>

  <li>Example of data that has the same implicit index and explicit index</li>

  <li>when we access one index then what appears is the explicit index</li>
  <li>when we call the explicit index from index 2 to index 3. the value that appears is precisely the implicit index </li>

</ul>

## Benefits Data Frame
<ul>

  <li>Data Frame is a collection of series, with at least one series</li>

  <li>when calling data with the regional.pop syntax it will appear as below because pop is the same as the name of the function in the Data Frame</li>

  <li>In the population area, take data that has been done by the previous data frame </li>

</ul>

## Expected outcame 
<ul>
  <li>Next it does with an explicit index on its population syntax</li>
  <li>add new Colom</li>
  <li>add new line </li>
  <li>combine regional data and additional_area data with concat</li>
</ul>

# DATA-MANIPULATION-WITH-PYTHON

Data manipulation means to organize or arrange the kind of structured data that is read by computer programs so that it’s easier to interpret. Performing this process effectively can improve the quality of your data and analysis.

Pandas has two objects, namely series and data frames.

# Object Series

Series is a one-dimensional labeled array capable of holding any data type (integers, strings, floating point numbers, Python objects, etc.). The axis labels are collectively referred to as the index. Pandas Series is nothing but a column in an a sheet. Labels need not be unique but must be a hashable type.

<ul>

  <li>Creating a series from array</li>

  <li>Creating a series from Lists</li>

In order to create a series from list, we have to first create a list after that we can create a series from list.

  

  <li>Accessing Element from Series with Position</li>

<li>Accessing element of Series</li>

There are two ways through which we can access element of series, they are :

 

  <li>Accessing Element from Series with Position</li>

  <li>Accessing Element Using Label (index)</Li>

  Change the Data into Series

  display index. The index is a range, where the starting point is inclusive of the range and the stop point is exclusive to the range.

  implicit index is the default index we can define the index, this is called the explicit index that is defined. when defining an index, the number of indexes must be equal to the number of data.

  but we can slice with the implicit index, then only the starting point will appear. because the implicit index is a range

</ul>

# loc and iloc

Pandas provides at least three ways of displaying (selecting) data, namely .loc, .iloc and [] .

<ul>

  <li>.loc Selects rows and columns based on their labels.</li>

  <li>.iloc Selects rows and columns by position, indicated by an integer number.</li>

  <li>[] Selecting rows and columns based on column names, similar to .loc but this feature is the most used because generally what we need is to retrieve all rows from a given column.</li>

  

</ul>

when the implicit index and the explicit index are the same. when we call the data, it will only call the explicit index

Example of data that has the same implicit index and explicit index

when we call the explicit index from index 2 to index 3.. the value that appears is precisely from the implicit index..

when the explicit index and the implicit index are the same, there will be inconsistencies as in the case above

To overcome this inconsistency, we will use the Loc and iLoc kaidah rules

<ul>

  <li>Loc is to call its explicit index</li>

  <li>iLoc is to call its implicit index</li>

 

</ul>

# Data Frame

Data Frame is a collection of series, with at least one series

when calling data with the regional.pop syntax it will appear as below because pop is the same as the name of the function in the Data Frame

In the population area, take data that has been done by the previous data frame

# Next it does with an explicit index on its population syntax

 <ul>

 

  <li>index explicit</li>

  <li>index implicit</li>

  <li>add new line </li>

<Li> combine regional data and additional_area 

</ul>



