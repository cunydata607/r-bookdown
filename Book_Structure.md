Let's start planning the structure of the book here...  My idea is to organize chapters by Packages and then have subchapters for each function within the package.  Although we may want to structure based more on a workflow, but I think that's harder to plan.  We can always start with this plan and then reorgnize later.

Here's some info from the Tidyverse website to get us started...  I suggest we add functions under each and put our name next to the ones we want to work on.  For example, I started with the stringr package below...

## Core tidyverse
The core tidyverse includes the packages that you're likely to use in everyday data analyses. As of tidyverse 1.2.0, the following packages are included in the core tidyverse:


### ggplot2
ggplot2 is a system for declaratively creating graphics, based on The Grammar of Graphics. You provide the data, tell ggplot2 how to map variables to aesthetics, what graphical primitives to use, and it takes care of the details. Learn more ...


### dplyr
dplyr provides a grammar of data manipulation, providing a consistent set of verbs that solve the most common data manipulation challenges. Learn more ...


### tidyr
tidyr provides a set of functions that help you get to tidy data. Tidy data is data with a consistent form: in brief, every variable goes in a column, and every column is a variable. Learn more ...


### readr
readr provides a fast and friendly way to read rectangular data (like csv, tsv, and fwf). It is designed to flexibly parse many types of data found in the wild, while still cleanly failing when data unexpectedly changes. Learn more ...


### purrr
purrr enhances R’s functional programming (FP) toolkit by providing a complete and consistent set of tools for working with functions and vectors. Once you master the basic concepts, purrr allows you to replace many for loops with code that is easier to write and more expressive. Learn more ...


### tibble
tibble is a modern re-imagining of the data frame, keeping what time has proven to be effective, and throwing out what it has not. Tibbles are data.frames that are lazy and surly: they do less and complain more forcing you to confront problems earlier, typically leading to cleaner, more expressive code. Learn more ...


### stringr
stringr provides a cohesive set of functions designed to make working with strings as easy as possible. It is built on top of stringi, which uses the ICU C library to provide fast, correct implementations of common string manipulations. Learn more ...

(I just copied this list out of the stringr documentation)  They could be reordered to something that makes more logical sense rather than alphabetical...
#### 	case 
#### 	invert_match 
#### 	modifiers 
#### 	stringr-data 
#### 	str_c 
#### 	str_conv 
#### 	str_count 
#### 	str_detect 
#### 	str_dup 
#### 	str_extract 
#### 	str_flatten 
#### 	str_glue 
#### 	str_length 
#### 	str_locate 
#### 	str_match 
#### 	str_order 
#### 	str_pad 
#### 	str_remove 
#### 	str_replace 
#### 	str_replace_na 
#### 	str_split 
#### 	str_sub 
#### 	str_subset 
#### 	str_trim 
#### 	str_trunc 
#### 	str_view 
#### 	str_wrap 

### forcats
forcats provides a suite of useful tools that solve common problems with factors. R uses factors to handle categorical variables, variables that have a fixed and known set of possible values. Learn more ...
