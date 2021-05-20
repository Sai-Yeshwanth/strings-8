class Jala {
	
	public static void main(String[] args) {
		String name="Yeshwanth Reddy";
		String name2="yeshwanth reddy";
		System.out.println(name.equalsIgnoreCase(name2));
		System.out.println(name.startsWith("Yesh"));
		System.out.println(name2.endsWith("ddy"));
		System.out.println(name.compareTo(name2));
	}
}
