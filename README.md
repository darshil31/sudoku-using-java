# sudoku-using-java

Project Functionalities with description:


First we create sudoku package, In sudoku package we create main two classes : 1. Main, 2. Sudoku. Then we create three classes easy, medium and hard by extends Sudoku class.

Methods and work of Main Class :

1.	main()
  	main function has 3 choice : 1. newgame(), 2. gamerules() and 3. exit_sudoku().
2.	dashsudoku()
  	dashsudoku function have SUDOKU design.
3.	mainmenu()
  	mainmenu display menu for main function.
4.	exit_sudoku()
  	this function used for quit game and terminate console.
5.	gamerules()
  	this function shows all the rules for solve sudoku.
6.	newgame()
  	this function create the object of child class of sudoku class and generate random sudoku from easy, medium or hard class.
  	It is also initialize the 2D array means Sudoku array.
7.	newgame_menu()
  	this menu display 4 choice : 1. Easy, 2. Medium, 3. Hard, 4. Go back to main menu. 
8.	functions()
  	this function shows choice for solve sudoku and that is add number, save sudoku in file and quit.
9.	play()
  	this function is a main part of over code. This function call isvalid function and check all the rules when user enter any number and this rules are…
  	entered row, column and number must in between 1 to 9.
  	entered number not present in same row, column and corresponding 3×3 matrix.
  	Entered position is must me valid means user can not use fixed position.
10.	isvalid()
  	this function check above conditions.
11.	solve_sudoku()
  	use of this function is solve sudoku and show the right answer to the user. Here we use the concepts of backtracking.
12.	is_safe()
  	this function is check required conditions for the backtracking.

	Methods and work of Sudoku Class :

1.	display()
2.	easy()
3.	medium()
4.	hard()

display class get the current sudoku and then print sudoku on console.
Easy, medium and hard class have 5-5 sudoku and when user select one of this class then that time this class generate randomly 1 sudoku.
