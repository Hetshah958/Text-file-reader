# Text File Reader

This is a small Python project that reads a text file, counts the total number of lines, and copies the first two lines into a new file.

## Requirements

- Python 3
- No additional packages required

## How to Run

1. Download or clone this repository.
2. Keep `main.py` and `input.txt` in the same folder.
3. Open a terminal in that folder.
4. Run the following command:

```bash
python main.py
```

## Example

The input file contains:

```text
This is the first line.
This is the second line.
This is the third line.
This is the fourth line.
```

### Output

```text
Total number of lines: 4
First two lines written to output.txt
```

The program creates `output.txt` containing:

```text
This is the first line.
This is the second line.
```

## Concepts Used

- Reading and writing text files
- Counting lines using `len()`
- Extracting lines using list slicing
- Using `with` to handle files safely
- Checking whether a file exists

## Conclusion

This project demonstrates basic file handling in Python by reading text, counting lines, and saving selected content to another file.
