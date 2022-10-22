# School
This is my first semester at Mizzou. I transfered from MACC which is also here in Columbia. I am a townie and have been in school at Columbia most of my life. I trandsfered with 60 credits but plan to graduate in may 2025. I am majoring in Inormation Technology.
  Before starting at mizzou I actually wanted to pursue Orthodontics. I shadowed a few times and talked to some profesionals and decided I did not want to continue. I was slightly lost in wanted I wanted to do but came across IT and really enjoyed it.
  
## Classes

I am currently in a few different IT coding classes including INFOTC 1000 and INFOTC 1040.
**Here is an example of a code I did for class**

def perform_calculation():
   
    try:
        filename = input("Input the filename: ")
       
        with open(filename) as file:
            column = file.readlines()
            numbers = [int(num) for num in column]
            print("File Name: ", filename)
            print("Sum: ", sum(numbers))
            print("Count: ", len(numbers))
            print("Average: ", sum(numbers)/len(numbers))
            print("Maximum: ", max(numbers))
            print("Minimum: ", min(numbers))
            print("Range: ", max(numbers) - min(numbers))
           
    except Exception as error:
        print(error)
   
def main():
    while True:
            perform_calculation()
            response = input("Would you like to evaluate another file? (y/n)")
            if (response == "y"):
                print("")
                continue
            else:
                break
 
 ## Examples of other projects 
 
 An image I created in Illustrator
 
 [robot](TrishaSamala4c.png)

main()
   
