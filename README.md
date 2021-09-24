public class aboutMe {

    private String name, interests, school;

    aboutMe() {
        name = "Thomas";
        interests = "Software Engineering, Embedded Systems, Networking";
        school = "The University of Texas at Austin";
    }

    public void printName() {
        //prints out the this.name
        System.out.print("My name is: ");
        System.out.println(name);
    }

    public void printInterests() {
        //prints out this.interests
        System.out.print("My interests are: ");
        System.out.println(interests);
    }

    public void printSchool() {
        //prints out this.school
        System.out.print("I currently attend: ");
        System.out.println(school);
    }

}

