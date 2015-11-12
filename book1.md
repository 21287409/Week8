from book import Book

def main():
    book1 = Book("The Study Skills Handbook", "Stella Cottrell", "April 2013")
    book1.showDetails()

    print(book1.getTitle())
    print(book1.setTitle("Harry Potter"))

    print()

    book2 = Book("Learn Python the Hard Way", "Zed Shaw and Addison Wesley", "August 2013")
    book2.showDetails()

    print(book2.getTitle())
    print(book2.setTitle("Study Computing"))
    

    print()

    book3 = Book("Discrete Mathematics for Computing", "Grossman, P", "2002")
    book3.showDetails()

    print(book1.getTitle())
    print(book1.setTitle("Doctor Who"))


main()
