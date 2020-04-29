# Map-Masters-C-Project

1) C++ console application that calculates and displays the distance between two points on a map.  Prompt the user for four integer coordinates:x1y1x2y2Calculate the distance in kilometers from (x1, y1) to (x2, y2).  See www.mathsisfun.com/algebra/distance-2-points.html for background information.  Use function sqrt(<value>) to calculate the square root of <value>.  Use formatted output manipulators (setw, left/right) to print the following five rows:
  ● x1
  ● y1
  ● x2
  ● y2
  ● DistanceAnd three columns:
  ● A left-justified label.
  ● A right-justified value.
  ● A left-justified units (output manipulators not needed here, just place one space before the units name to separate it from the second column).Define constants for the column widths.  Format all real numbers to one decimal place.
  
2) C++ console application that determines the lowest and highest of three real numbers.  Prompt the user for the numbers.  Use functions:fmin(<value-1>, <value-2>) to get the smallest of <value-1> and <value-2>Andfmax(<value-1>, <value-2>) to get the largest of <value-1> and <value-2>The result of either function may be stored in a variable and then that variable may be used in the next call of either function.  Use formatted output manipulators (setw, left/right) to print the following five rows:
  ● Value 1
  ● Value 2
  ● Value 3
  ● Lowest value
  ● Highest valueAnd two columns
  ● A left-justified label.
  ● A right-justified value.Define constants for the column widths.  Format all real numbers to three decimal places. 
  
3)C++ console application that calculates and displays the Celsius equivalent of a Fahrenheit temperature.  Prompt the user for a temperature in Fahrenheit, convert it to Celsius and show both values.  See https://www.albireo.ch/temperatureconverter/formula.html for background information.  Use formatted output manipulators (setw, left/right) to print the following two rows:
● Fahrenheit temperature
● Celsius temperatureAnd three columns:
● A left-justified label
● A right-justified value.
● A left-justified units (output manipulators not needed here, but don't place one space before the units name to separate it from the second column).Define constants for the column widths.  Format all real numbers to two decimal places.  Include the degree symbol in the output:
● Windows users – declare a constant for the degree symbol:DEGREE_SYMBOL = (char) 167Use the constant in the output.
● Mac OS users – copy the degree symbol above to your code.Run the program five times with the following Fahrenheit values.  What are the results?RunFahrenh
