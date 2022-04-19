# DARIA HARLIAK
## *Student*
###### ![alt text](https://github.com/dadasha1917/CV/blob/markdowm-cv/photo5393362262800054174.jpg)
# Contact information:
* Location: Vitebsk, Belarus
* Phone: +375291016877
* E-mail: dasha09340@gmail.com
* Telegram: @dadasha1917
* GitHub: dadasha1917@github.com
# About me
I am 18 years old. I graduated school with honors in 2021. Now I am a first-year student of Vitebsk State University named after P. M. Masherov.

I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.
# Skills
* HTML
* C++
* Photoshop
* Inkscape
* Excel
* GitHub
# Code examples
```C++
struct tnode* addnode(double x, tnode* tree) {
    if (tree == NULL) { // Если дерева нет, то формируем корень
        tree = new tnode; // память под узел
        tree->field = x;   // поле данных
        tree->left = NULL;
        tree->right = NULL; // ветви инициализируем пустотой
    }
    else  if (x < tree->field)   // условие добавление левого потомка
        tree->left = addnode(x, tree->left);
    else    // условие добавление правого потомка
        tree->right = addnode(x, tree->right);
    return(tree); 
 ```    
    
    C++
    {
    Complex a;
    Complex b;
    cout << "vvedite a:";
    cin >> a;
    cout << "vvedite b:";
    cin >> b;
    cout << "a = " << a << "; b =" << b << endl;


    Complex c ;
  

    cout << a+b  << endl;
    cout << a*b  << endl;

    return 0;}
#  Work experience:
Nothing yet...
# Education and courses:
* High school 4 of Gorki (successfully graduated with a gold medal)
* Now  I study at Vitebsk State University named after P.M. Masherov
* C++ video courses on YouTube channel Simple Code
* Git video courses on YouTube channel Glo Academy
# Languages:
* Russian
* English level-A2
