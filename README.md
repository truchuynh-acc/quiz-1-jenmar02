[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Jennifer Martinez
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

//will hold information on cars (inc. model, year, and color)
class Car
{
private:
    std::string model;
    int year;
    string color;
public:
    //default constructor
    Car()
    {
        //if not entry inputted -- this will auto display
        model = "";
        year = 0;
        color = "";

    }//end of the default constructor

    //setters
    //will set the model of the car
    void setModel(string theModel)
    {
        model = theModel;

    } //end of void setModel(string theModel)

    //will set the year of the car 
    void setYear( int theYear)
    {
        year = theYear;
    }//end of void setYear( int theYear)

    //will set the color of the car
    void setColor( string theColor)
    {
        color = theColor;
    }//end of void setColor( string theColor)

    //getter
    //will return the model of the car
    string getModel()
    {
        return model;
    } //end of string getModel()

    //will return the year of the car 
    int getYear()
    {
        return year;
    }//end of int getYear()

    //will set the color of the car
    string getColor()
    {
        return color;
    }//end of string getColor()

    //will display the information held in the class
    void displayDetails()
    {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;

    }//end of void displayDetails()

}; //end of class Car

int main()
{
    //create an instance of the class
    Car myCar;

    myCar.displayDetails();

    return 0;

} //end of int main()

```
