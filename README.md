package project;

import java.util.ArrayList;
import java.util.LinkedList;  

public class tb3 {

	public static void main(String[] args) {

		Student a = new Student ("ali","ryadh");
		System.out.println(a.getname()+"  "+a.getaddress());
		
		LinkedList<String> courses = new LinkedList<String>();
		courses.add("math");
		courses.add("english");
		
		LinkedList<Integer> grades = new LinkedList<Integer>();
		grades.add(4);
		grades.add(3);
		Student b = new Student("ali","ryadh");
		b.printGrades(grades);
		b.printcourses(courses);
		
		
		Teacher f = new Teacher ("hmzh","sodan");
		ArrayList<String> courses1 = new ArrayList<String>();
		courses1.add("math");
		System.out.println(f.toString());
		
		
		
		
	}

}
