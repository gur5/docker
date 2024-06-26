<h1>Java_img</h1>

<h2>Dockerfile</h2>
from openjdk:latest
copy . .
run javac hello.java
cmd ["java", "abc"]

<h2>hello.java</h2>
class abc {
	public static void main(String[] args){
		system.out.println("hello, World!");
	}
}
