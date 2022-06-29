# Inheritance
Blood Type Inheritance Simulator in C which outputs the inheritance of a family from a DNA.txt file.

How to Test Your Code
Upon running ./inheritance, your program should adhere to the rules described in the background. The child should have two alleles, one from each parent. The parents should each have two alleles, one from each of their parents.

For example, in the example below, the child in Generation 0 received an O allele from both Generation 1 parents. The first parent received an A from the first grandparent and a O from the second grandparent. Similarly, the second parent received an O and a B from their grandparents.

$ ./inheritance<br>
Child (Generation 0): blood type OO<br>
    Parent (Generation 1): blood type AO<br>
        Grandparent (Generation 2): blood type OA<br>
        Grandparent (Generation 2): blood type BO<br>
    Parent (Generation 1): blood type OB<br>
        Grandparent (Generation 2): blood type AO<br>
        Grandparent (Generation 2): blood type BO<br>
