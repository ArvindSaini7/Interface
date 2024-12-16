package Interfaces;

public class interface_a {
	public static void main(String args[])
	{
		B b=new B();
		b.a();
	}
	

}

 interface A {
	void a();

}

 class B implements A{
	public void a(){
		System.out.println("hello");
	}
	
}
# Interface
declaration of interface
