# Boggle-Program
Assignment One f
//MyBoggle

import java.io.*;
import java.util.*;


	public class Board {
	
	private static int size = 4;
	private char [][] board;
	
	public Board()
	{
		this.board = new char[board.size][board.size];
		
		//Traverse both [][] of the board as it will be a 4x4 square when built
		for (int r = 0; i < this.board.length; i++)
		{	for(int c = 0; j < this.board.length; j++)
			{
				
			}
		}	
	}
	
	public boolean foundWord(String word, int row, int col)
	{
		//Again needing two for loops for the two dimensions of the square board.
		for (int row = 0; row < this.board.length; row++)
		{
			for(int col = 0; col < this.board.length; col++)
			{
				if(this.foundWord(word,row,col))
				return true;
			}
		}
		return false; //no word being found
	}	
	
	public class Input //Class for comparing and handling user input
	
	{
		//Different possible print statements that would come from different things happening in the game
		
		System.out.printl("Welcome, please guess a word!");
		
		System.out.printl("Correct guess, that word is on the board.");
		
		System.out.printl("That word is not on the board.");
		
		System.out.printl("That word is not in the dictionary.");
		
		System.out.printl("You found x out of x words.");
		
		System.out.printl("Here are all the words on the board.");
		
		System.out.printl("You found x percent of the words.");
	
	
	
	
	
	}
	
	public static void main(String [] args) throws IOException
		{
		
		}
