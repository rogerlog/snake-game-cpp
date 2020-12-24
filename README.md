# Snake Game - cpp

Classic game developed in cpp and with Linux libraries.

Some classes need to be changed to work on Windows.

```cpp
int main()
{
    printf("\n\n\n");
    printf("Let's start a new simple Snake Game");
    printf("\n\n\n");

    Setup();
    while (!gameOver)
    {
        Draw();
        Input();
        Logic();
        usleep(70000); //convert to Windows like this... Sleep();
    }
    return 0;
}
```

#### Images
![dev1](/.img/dev1.png)

![dev2](/.img/dev2.png)

#### to-do
- :ballot_box_with_check: ​Place infinite walls 
- :no_entry: ​Increase speed with each score 
- :no_entry: ​Record maximum score in external file