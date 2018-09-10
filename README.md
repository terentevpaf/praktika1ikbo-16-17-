# praktika1ikbo-16-17-
# Терентьев Павел Вадимович ИКБО-16-17

public class Main
{
	public static void main(String[] args) {
		Book bk = new Book();
		bk.infoBook();
		Ball bl = new Ball();
		bl.infoBall();
	}
}

public class Book {
    public String nameBook;
    public int size;
    public Book()
    {
        this.nameBook = "None";
        this.size = 1;
    }
    public Book(String name, int size)
    {
        this.nameBook = name;
        this.size = size;
    }
    public Book(String name)
    {
        this.nameBook = name;
        this.size = 20;
    }
    public Book(int size)
    {
        this.nameBook = "";
        this.size = size;
    }
    public void setName(String name)
    {
        this.nameBook = name;
    }
    public String getName()
    {
        return nameBook;
    }
    public void setSize(int size)
    {
        this.size = size;
    }
    public int getSize()
    {
        return size;
    }
    public void infoBook()
    {
        System.out.println("Name: " + nameBook + ", size: "+size);
    }
}

public class Ball {
    public String nameBall;
    public String color;
    public Ball()
    {
        this.nameBall = "None";
        this.color = "Red";
    }
    public Ball(String name, String color)
    {
        this.nameBall = name;
        this.color = color;
    }
    public void setName(String name)
    {
        this.nameBall = name;
    }
    public String getName()
    {
        return nameBall;
    }
    public void setColor(String color)
    {
        this.color = color;
    }
    public String getColor()
    {
        return color;
    }
    public void infoBall()
    {
        System.out.println("Name: " + nameBall + ", color: " + color);
    }
}
