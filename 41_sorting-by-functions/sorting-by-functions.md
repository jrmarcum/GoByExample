___
#### To run the program, make sure you are in the program's folder, then use the Run Command below.
___
#### Running our program shows a list sorted by string length, as desired.
___
##### Run Command:

`$ go run sorting-by-functions.go`

##### Result:

`[kiwi peach banana]`

___
#### By following this same pattern of creating a custom type, implementing the three `Interface` methods on that type, and then calling sort.Sort on a collection of that custom type, we can sort Go slices by arbitrary functions.
___
###### This work and the accompanying code was originally from Mark McGranaghan at [https://github.com/mmcgrana/gobyexample](https://github.com/mmcgrana/gobyexample) and licensed under a Creative Commons Attribution 3.0 Unported License [http://creativecommons.org/licenses/by/3.0/](http://creativecommons.org/licenses/by/3.0/). It has been used to provide an example base for multiple languages to provide a basis of comparitive programming language study for syntax, language simplicity, number of lines of code and operations required to perform the same task, as well as compile and run speed combined.