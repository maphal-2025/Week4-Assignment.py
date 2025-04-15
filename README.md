# Week4-Assignment.py

Question 1
  
        with open(input_file, 'r') as infile:
            content = infile.read()

        modified_content = modify_content(content)

        with open(output_file, 'w') as outfile:
            outfile.write(modified_content)

        print(f"Modified content successfully written to {output_file}")

    except FileNotFoundError:
        print("Error: Input file not found.")
    except Exception as e:
        print(f"An error occurred: {e}")

Question 2

 def modify_content(content):
return content.upper()
def read_and_write_files(input_file, output_file):
    
