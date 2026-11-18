# Alfred-workflow-MDTables
Create basic markdown tables

> [!WARNING]
> Markdown tables use Markdown [extended syntax](https://www.Markdownguide.org/extended-syntax/). Not every flavour of Markdown supports that (or all of the syntax). If the one that you use does not this workflow will not work for you.

> [!IMPORTANT]
> This workflow uses Alfred 6.0 and later. It will not work with earlier Alfred versions. If you are using an earlier version of Alfred use the [2026.3 version](https://github.com/Stephen-Lon/Alfred-workflow-MDTables/releases/tag/2026.3) of this workflow.

# Introduction

This workflow allows for the creation of Markdown tables with a header row (using column headings that you provide) and the number of data rows that you choose (up to 20), as follows:

- a two, three or four column table with all text left justified;
- a two, three or four column table with all text centred.

(Note that Markdown tables do not allow differing text alignments within the same table.)

# Use

1. Run the workflow using the keyword. Choose the parameters for your table and when you have finished click `Continue` (or use the <kbd>⌘C</kbd> shortcut).

	<img width="832" height="635" alt="params" src="https://github.com/user-attachments/assets/c252fc09-aaa8-430b-9ea6-896402bda9c7" />

2. You will be prompted to provide the header for the first table column.

    <img width="860" height="153" alt="FirstColumnPrompt" src="https://github.com/user-attachments/assets/f1206d96-3022-493b-a09a-5d86b0b93e72" />

3. When you have done that press <kbd>↩︎</kbd> and you will be prompted to provide the header for the next table column.

    <img width="860" height="149" alt="SecondColumnPrompt" src="https://github.com/user-attachments/assets/282f334f-ab29-40e8-b2ef-b9c72e8308d5" />

	> [!NOTE]
> In the case of each prompt after the first the subtext of the prompt will list, by way of reminder, the previous column header(s) you have provided.

4. When you have provided all the column headings for the table you will see both the raw Markdown text and the rendered Markdown, side by side, in an Alfred UI window. (The “Your text” placeholders are there merely for convenience so that you can easily see, within the unrendered table formatting, where to type your own text.) You can edit the raw text (e.g., using copy and paste to add additional rows) and see the rendered Markdown update as you do so.
	
	<img width="950" height="689" alt="MDT" src="https://github.com/user-attachments/assets/18410a98-fb76-4294-8831-65f43a8c4750" />

	If you make a mistake with the formatting in the Markdown raw text that will immediately be apparent in the rendered Markdown window so that you can correct the text. When you are satisfied with the table simply click the `Copy to Clipboard` button—or use the <kbd>⌘B</kbd> shortcut—to copy the raw Markdown text to the clipboard so that you can paste it into your Markdown app.

	When you have finished <kbd>⎋</kbd> (Escape) will close the whole window. 

> [!NOTE]
> I have *not* marked the tables as “transient” on the clipboard so that you will not lose access to a table you have created if you do not use it immediately. You can, of course, delete unwanted clipboard items from Alfred's clipboard history in the usual way by using <kbd>fn⌫</kbd>.
