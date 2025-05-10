# AIM:
To develop a UiPath automation workflow that reads the content of a PDF file and writes the extracted text into a .txt file.

# SOFTWARE REQUIRED:
```
1.UiPath Studio (Any recent version)
2.UiPath.PDF.Activities Package
3.Windows OS
4.Text Editor (e.g., Notepad) for viewing output
```

# PROCEDURE:
```
1.Open UiPath Studio and create a new project.
2.Install the UiPath.PDF.Activities package via Manage Packages.
3.Drag a Read PDF Text activity into the sequence.
4.Set the file path to your PDF.
5.Store the output in a string variable (e.g., pdfText).
6.Drag a Write Text File activity below it.
7.Set the path for the .txt file to save the extracted content.
8.Use pdfText as input.
9.Save and run the workflow.
```

# WORKFLOW:
![Screenshot 2025-05-10 113229](https://github.com/user-attachments/assets/839d5e4f-6c1b-48d7-8e21-10441b74ae89)

# OUTPUT:
![Screenshot 2025-05-10 113239](https://github.com/user-attachments/assets/ea201905-aa25-432a-b42a-d42eb7257eee)
![Screenshot 2025-05-10 113315](https://github.com/user-attachments/assets/841256e8-066e-4b15-9943-69618631eaf1)

# RESULT:
The workflow successfully extracts the text from the given PDF and writes it into a .txt file at the specified location.
