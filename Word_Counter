def count_text_file(file_path):
    try:
        with open(file_path, 'r', encoding='utf-8') as file:
            text = file.read()
            
        with open(file_path, 'r', encoding='utf-8') as file:
            lines = file.readlines()

        word_count = len(text.split())
        char_count_including_spaces = len(text)
        char_count_excluding_spaces = len(text.replace(" ", ""))
        line_count = len(lines)

        print(f"Lines: {line_count}")
        print(f"Words: {word_count}")
        print(f"Characters (including spaces): {char_count_including_spaces}")
        print(f"Characters (excluding spaces): {char_count_excluding_spaces}")

    except FileNotFoundError:
        print("Error: File not found!")
    except Exception as e:
        print(f"An error occurred: {e}")

# Provide the file path of the text document you want to analyze
file_path = "/content/Task2.txt"  # Update this to the actual file path
count_text_file(file_path)
