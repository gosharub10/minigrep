This is a simple cli application that searches for a substring in a file and outputs it to another file or console
First of all you need to write in conosle 
****cargo run -- text sapmle.txt****

text is a word containts in file 
sample.txt is a file where contains your text

If you would ignore register you need write a key in terminal command
****IGNORE_CASE=1 cargo run -- text sample.txt****

If you would get result in other text file you need to write
****cargo run -- text sample.txt > output.txt****
