##  Oops_Assignment1
## README

### ForInstalling Scala use code
```bash
sudo apt-get install scala
```
## Clone the Github Repository

Using the clone command to clone the repository.
```bash
git clone https://github.com/Shashikant-15/Oops_Assignment1.git
```
### To Execute the code

* Change the working directory to the cloned directory
 
cd ../Oops_Assignment1/src/main/scala/samplepackage

### Further Run the following commands 
```bash
scalac MainObject.scala
scala MainObject
```
## In oops Assignment-1 we have to do :``
* Make a trait Queue which performs two functions of enqueue and dequque.
* Two classes: DoubleQueue and SquareQueue mix in this trait.
* You may use List for the implementation and keep both the classes in the same file with proper packaging.
### After that 

* DoubleQueue enqueues the element after doubling them
* SquareQueue enqueues the element after squaring them
* dequeue method will remove the first element from the queue(having concrete definition in trait Queue).
