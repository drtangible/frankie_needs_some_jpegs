**Step 1**

Back up your files, in case this goes horribly wrong.

**Step 2**

Move the top level directory to your Desktop. Once finished, your folder structure should look like this:

	++ Desktop

		++++ Top_Level_Folder

			++++++ Sub_Folder_1
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			++++++ Sub_Folder_2
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			++++++ Sub_Folder_3
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			.
			.
			.

			++++++ Sub_Folder_100
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3



**Step 3**

Move the file named _rename_frankies_filez.sh_ into the top level directory.

	++ Desktop

		++++ Top_Level_Folder             <-- Move 'rename_frankies_filez.sh' into this directory.

			++++++ Sub_Folder_1
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			++++++ Sub_Folder_2
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			++++++ Sub_Folder_3
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3

			.
			.
			.

			++++++ Sub_Folder_100
				++++++++ Loan_Pic_1
				++++++++ Loan_Pic_2
				++++++++ Loan_Pic_3



**Step 3**

Open a Terminal window (Finder -> Go -> Utilities -> Terminal).



**Step 4**


Navigate to the top level directory in the Terminal window (Note: replace 'Top_Level_Folder' with whatever your top-level directory is called).

`cd Desktop/Top_Level_Folder`

Make sure that you've correctly navigated to the directory. When you execute the `pwd` command, your output should be similar to `/Users/drtangible/Desktop/frankie_needs_some_jpegz`.


**Step 5**

Run the command in the Terminal window.

`./rename_frankies_filez.sh`


**Step 6**

That's it! Your folder structure should now look like this:

	++ Desktop

		++++ Top_Level_Folder

			++++++ Sub_Folder_1
				++++++++ Loan_Pic_1.jpg
				++++++++ Loan_Pic_2.jpg
				++++++++ Loan_Pic_3.jpg

			++++++ Sub_Folder_2
				++++++++ Loan_Pic_1.jpg
				++++++++ Loan_Pic_2.jpg
				++++++++ Loan_Pic_3.jpg

			++++++ Sub_Folder_3
				++++++++ Loan_Pic_1.jpg
				++++++++ Loan_Pic_2.jpg
				++++++++ Loan_Pic_3.jpg

			.
			.
			.

			++++++ Sub_Folder_100
				++++++++ Loan_Pic_1.jpg
				++++++++ Loan_Pic_2.jpg
				++++++++ Loan_Pic_3.jpg
