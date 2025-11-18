package ass1;

public class List {
	
	static class Node
	{
		private int data;
		private Node next;
		
		public Node(int value)
		{
			data = value;
			next = null;
		}
		
	}
	
	private Node head;
	
	public List()
	{
		head = null;
	}
	
	
	public void addFirst(int value) {
		
		Node newnode = new Node(value);

		if(head == null)
		{
			head = newnode;
		}
		
		else
		{
			newnode.next = head;
			head = newnode;
		
		}
	}
	
	public void display() {
		
		Node trav = head;
		
		while(trav != null)
		{
			System.out.print(" "+trav.data);
			trav = trav.next;
		}
		
		System.out.println();
	}
	
	public void insertAfter(int data, int value)
	{
		
		Node trav = head;
		Node newnode = new Node(value);
		
		while(trav != null && trav.data != data)
		{
			trav = trav.next;	
		}
		
		if(trav == null)
		{
			System.out.println("give value is not present in th list");
		}
		
		newnode.next = trav.next;
		
		trav.next = newnode;
	
	}
	
	
	public void insertBefor(int data, int value) {
		
		Node newnode = new Node(value);
		
		Node trav = head;
		
		while(trav.next.data != data)
		{
			trav = trav.next;
		}
		
		newnode.next = trav.next;
		trav.next = newnode;
		
	}
	}

