# PyPi Package: MLTranslit

## Description
MLTranslit is a Python package that provides a simple and efficient way to transliterate Malayalam text to English. The package contains a python file *MLTranslit.py* which has a class named *ml_to_en* with a method *transliterate(input)* that takes input Malayalam text as an argument and returns the corresponding English transliteration based on a set of rules. It's useful for tasks such as machine learning, natural language processing, and data analysis that may require transliteration of Malayalam text to English.

## Installation
```python
!pip install MLTranslit
```

## Usage
```python
from MLTranslit import ml_to_en
convert = ml_to_en()
output = convert.transliterate("ഭക്ഷണം")
```
Output: bakshanam

## Example
Input ML text: പരമ്പരാഗതമായി മലയാളം ഇടത്തുനിന്ന് വലത്തോട്ടാണ് എഴുതുന്നത്. മലയാളം ലിപികളെയും അക്ഷരങ്ങളെയെന്നപോലെ സ്വരങ്ങളെന്നും വ്യഞ്ജനങ്ങളെന്നും രണ്ടായി തിരിക്കാം. 

Transliterated EN output: Paramparaagathamaayi malayaalam idatthuninnu valatthottaanu ezhuthunnathu. Malayaalam lipikaleyum aksharangaleyennapole svarangalennum vyanjjanangalennum randaayi thirikkaam.

## License
This package is license under GNU GPL v3.0 license. 
