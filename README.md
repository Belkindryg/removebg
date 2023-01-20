# Локальный код, для удаления фона с фотографии
Картинки только JPG.

Нужно дабавить путь к файлам:

for ext in list_of_extensions:
        all_files.extend(Path('..folder path/input_imgs').glob(ext))
        
        output_path = f'...folder path/output_imgs/{file_name}_output.png'
        
        
    
