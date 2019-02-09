# WF-Sorting-App (Team 01)

## Questions and Answers  


**1. Which algorithm is faster?**  

After multiple tests, we found **Bucket Sort** to be faster than Quick Sort.  

**2. Where is the entry point of the application?**

SortComparision.Program.Main() is the entry point of the application.  

**3. What is the name of the code file that displays the main form?**  

frmMain.cs is the name of code file that displays the main form.

**4.	What method does the main form constructor call?**  

The main form constructor calls InitializeComponent() method.  

**5. What is the fully qualified name of the class from which the main form is derived?**  

 The class frmMain is derived from Form class(System.Windows.Forms.Form) and SortComparison.frmMain is the fully qualified name of the class frmMain.

**6. Add code to the Form1_Load method - use intellisense and your IDE to determine: What is this.tbSamples.Value?**  

this.tbSamples.Value represents the number of sample of standard windows trackbar.  

**7.	What is this.cboAlg1?  Set its SelectedIndex to an integer so that the default is Bucket Sort.**  

cboAlg1 is the combo Box on left side. It represents the algorithm 1(Bucket Sort) which we pick from the list box.  

**8.	What is this.cboAlg2? Set its SelectedIndex to an integer so that the default is Quick Sort.**  

cboAlg2 is the combo box in right side of the mainframe.It represents the algorithm 2(Quick Sort) which we pick from the list box.  

**9. Use AppDomain.CurrentDomain.BaseDirectory.ToString() to get the base directory.**  

InitializeOutputFolder() will get string that represents the base directory.  

**10.	Create a new method called InitializeOutputFolder() and call it - see the suggested content below. What does this method do?**

We created a method InitializeOutputFolder(). It will get the base directory and save the images to the folder.

**11. What is this.cmdShuffle?  Call its PerformClick() method before exiting Form1_Load.**

It is a windows form  button. In our project, we used this button to shuffle the samples. PerformClick() generates the click event for the button. 

**12. What is this.cmdSort?  Change its appearance (e.g. ForeColor or BackColor) to highlight it so users will click it.** 

It is a windows form button. We used this button to sort the samples.

**13. Make at least one other obvious improvement or customization as desired.**

We made incremental commits in the repo. Each and every member of our team made some changes in appearances and output responses.
