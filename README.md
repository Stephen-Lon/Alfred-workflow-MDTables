# Alfred-workflow-MDTables
Create basic markdown tables

# Warning

Markdown tables use markdown [extended syntax](https://www.markdownguide.org/extended-syntax/). Not every flavour of markdown supports that (or all of the syntax). If the one that you use does not this workflow will not work for you.

# Introduction

This workflow allows for the creation of markdown tables with a header row (using column headings that you provide) and the number of data rows that you choose (up to 100), as follows:

- a two, three or four column table with all text left justified;
- a two, three or four column table with all text centred.

(Note that markdown tables do not allow differing text alignments within the same table.)

# Use

1. In the workflow configuration dropdown choose whether you want all table text to be left justified or centred.
2. Type the full keyword (which you can change in the workflow configuration) to see the list of the number of columns you can choose (two, three or four):

    <img width="860" height="263" alt="ColumnChoice" src="https://github.com/user-attachments/assets/6034cf52-78b3-47f1-8ea8-5d88f94e240a" />


Select your choice and press <kbd>↩︎</kbd>.

3. Choose the number of data rows (i.e., excluding the header row) you want in your table:

   <img width="860" height="152" alt="Rows" src="https://github.com/user-attachments/assets/fd4b16cc-91d1-4a8e-9256-1bf6871067aa" />

You can choose any number between 1 and 100 (let's be sensible 😀). Type a number and press <kbd>↩︎</kbd>.


4. You will be prompted to provide the header for the first table column:

    <img width="860" height="153" alt="FirstColumnPrompt" src="https://github.com/user-attachments/assets/7deea6fc-7f80-4d70-8a14-c7d0141df3b8" />



5. When you have done that press <kbd>↩︎</kbd> and you will be prompted to provide the header for the next table column:

    <img width="860" height="149" alt="SecondColumnPrompt" src="https://github.com/user-attachments/assets/c14c52ee-b02e-4a2d-9a02-32eaf626b171" />



Note that in the case of each prompt after the first the subtext of the prompt will list, by way of reminder, the previous column header(s) you have provided.

5. When you have provided all the column headings for the table you have chosen you will be notified that the table has been copied to the clipboard—so that you can paste it into the markdown app of your choice. (The “Your text” placeholders are there merely for convenience so that you can easily see, within the unrendered table formatting, where to type your own text.) You can obviously copy and paste to create further table rows if you need to do so.

    <img width="672" height="322" alt="Result" src="https://github.com/user-attachments/assets/2fe1948c-d01b-4689-8238-1da7f9cbd56c" />


# Note

I have *not* marked the tables as “transient” on the clipboard so that you will not lose access to a table you have created if you do not use it immediately. You can, of course, delete unwanted clipboard items from Alfred's clipboard history in the usual way by using <kbd>fn⌫</kbd> (fn + Backspace).
