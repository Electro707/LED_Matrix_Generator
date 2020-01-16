# LED Matrix Generator
The purpose of the Python programs is to generate an array based off a visual representation of the matrix, which then can be copied and pasted unto an Arduino program. Currently, there are 2 programs available under their respective folder:

- 4 Matrix Software: This software is to generate an array for a 4-matrix MAX7219 controlled LED Matrix (commonly found on Ebay and similar)
- Single Matrix Software: This software is to generate an array for a 4-matrix MAX7219 controlled LED Matrix (commonly found on Ebay and similar)

Both software generate a column-addressed array. That means that each array element is a column, each bit on an array element represents a row on the selected column.

More documentation about this software can be found on it's site [here!](https://www.electro707.com/documentation/Software/LED_matrix_generator/)

Both software require Python3, as well as the following python libraries/packages in order to work:
- Tkinter
- pyperclip
- PIL (Only for 4-Matrix.py)

Currently, this software has been only tested with my Simple LED Matrix library found [here!](https://github.com/Electro707/Simple-LED-Matrix-Library).

Included in each software inside their folders is a test image(s) that can be used with the "Import Image" button on each software

# To-Do
- Create software which allows for as many column as your heart desires

## Authors

* **Jamal Bouajjaj**

## License

See the [LICENSE](LICENSE) file for details
