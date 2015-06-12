# elementTranslator
Translates words/strings using symbols for chemical elements

## Example
"Python is nice" becomes (_PYThON IS NICe_) _Phosphorus Yttrium Thorium Oxygen Nitrogen Iodine Sulfur Nitrogen Iodine Cerium_.

## Usage
One argument is the string to translate, the next is which mode to use (default is *letter*-mode, other option is *names*-mode)
```
./eTranslate.py "python is nice" -names
```
where `-names` can be omitted (and the order of arguments is not important).
