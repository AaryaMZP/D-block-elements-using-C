#include<stdio.h>
int main(){
    int atomic_no,m,n;
    printf("******Welcome to the D block of Modern Periodic Table.******\n");
    printf("> Enter 1 to know about element.\n");
    printf("> Enter 2 if you  to display the D block elements the periodic table.\n");
    printf("> Enter 3 if you want to close the periodic table.\n");
    printf("ENTER:");
    scanf("%d",&m);
    if(m==3){
        int d;
        printf(">>Do you want to exit:");
        printf("\n>>>Enter 4 for Yes.");
        printf("\n>>>Enter 5 for No.");
        printf("\nEnter:");
        scanf("%d",&d);
        if(d==4){
            printf("The periodic table has been closed.");//Periodic table close message
            printf("\nThankyou.");
        }
        if(d==5){
            printf("Periodic Table has not closed and you can continue to learn more about elements.\n");
            printf(">>>Going To The Program\n");
            printf(">>>Loading....\n");
            printf("> Enter 1 to know about element.\n");
            printf("> Enter 2 if you  to display the D block elements the periodic table.\n");
            printf("ENTER:");
            scanf("%d",&m);
        }
    }
    if(m==1){
    
    printf("Press 3 to search element by atomic number.\n");
    printf("ENTER:");
    scanf("%d",&n);
    if(n==3){//Prints element and its value corresponding to the "atomic number" in case
        printf("Note:\nThe d block consist of elements with atomic number 21-30 , 39-48, 57, 72-80, 89, 104-112.\n");
        printf("Enter atomic number within the given Range.\n");
        printf("Enter the element atomic number you want to search:");
        scanf("%d",&atomic_no);
        printf("\n");
    switch(atomic_no){
        case 21:
            printf("The element is Scandium.\n");
            printf("The element's symbol is Sc.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d1.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 22:
            printf("The element is Titanium.\n");
            printf("The element's symbol is Ti.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d2.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 23:
            printf("The element is Vanadium.\n");
            printf("The element's symbol is V.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d3.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 24:
            printf("The element is Chromium.\n");
            printf("The element's symbol is Cr.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s1,3d5.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 25:
            printf("The element is Manganese.\n");
            printf("The element's symbol is Mg.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d5.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 26:
            printf("The element is Iron.\n");
            printf("The element's symbol is Fe.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d6.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 27:
            printf("The element is Cobalt.\n");
            printf("The element's symbol is Co.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d7.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 28:
            printf("The element is Nickel.\n");
            printf("The element's symbol is Ni.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d8.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 29:
            printf("The element is Copper.\n");
            printf("The element's symbol is Cu.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s1,3d10.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 30:
            printf("The element is Zinc.\n");
            printf("The element's symbol is Zn.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,4s2,3d10.\n");
            printf("The element belong to 4th period.\n");
            printf("The element belong to 3d series.\n");
            printf("The element belong to 1st transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 39:
            printf("The element is Yttrium.\n");
            printf("The element's symbol is Y.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d1,5s2.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 40:
            printf("The element is Zirconium.\n");
            printf("The element's symbol is Zr.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d2,5s2.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 41:
            printf("The element is Niobium.\n");
            printf("The element's symbol is Nb.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d4,5s1.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 42:
            printf("The element is Molybdenum.\n");
            printf("The element's symbol is Mo.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d5,5s1.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 43:
            printf("The element is Technetium.\n");
            printf("The element's symbol is Tc.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d5,5s2.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 44:
            printf("The element is Ruthenium.\n");
            printf("The element's symbol is Ru.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d7,5s1.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 45:
            printf("The element is Rhodium.\n");
            printf("The element's symbol is Rh.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d8,5s1.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 46:
            printf("The element is Palladium.\n");
            printf("The element's symbol is Pd.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s0.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 47:
            printf("The element is Silver.\n");
            printf("The element's symbol is Ag.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s1.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 48:
            printf("The element is Cadmium.\n");
            printf("The element's symbol is Cd.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2.\n");
            printf("The element belong to 5th period.\n");
            printf("The element belong to 4d series.\n");
            printf("The element belong to 2nd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 57:
            printf("The element is Lanthanum.\n");
            printf("The element's symbol is La.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,5d1,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 72:
            printf("The element is Hafnium.\n");
            printf("The element's symbol is Hf.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d3,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 73:
            printf("The element is Tantalum.\n");
            printf("The element's symbol is Ta.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d4,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 74:
            printf("The element is Tungsten.\n");
            printf("The element's symbol is W.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d4,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 75:
            printf("The element is Rhenium.\n");
            printf("The element's symbol is Re.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d5,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 76:
            printf("The element is Osmium.\n");
            printf("The element's symbol is Os.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d6,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 77:
            printf("The element is Iridium.\n");
            printf("The element's symbol is Ir.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d7,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 78:
            printf("The element is Platinum.\n");
            printf("The element's symbol is Pd.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d9,6s1.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 79:
            printf("The element is Gold.\n");
            printf("The element's symbol is Au.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,,4f14,5d10,6s1.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 80:
            printf("The element is Mercury.\n");
            printf("The element's symbol is Hg.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2.\n");
            printf("The element belong to 6th period.\n");
            printf("The element belong to 5d series.\n");
            printf("The element belong to 3rd transition series.\n");
            printf("This is not a radioactive element.\n");
            break;
        case 89:
            printf("The element is Actinium.\n");
            printf("The element's symbol is Ac.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,6d1,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 104:
            printf("The element is Rutherford.\n");
            printf("The element's symbol is Rf.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d2,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 105:
            printf("The element is Dubnium.\n");
            printf("The element's symbol is Db.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d2,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 106:
            printf("The element is Seaborgium.\n");
            printf("The element's symbol is Sg.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d4,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 107:
            printf("The element is Bohrium.\n");
            printf("The element's symbol is Bh.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,6d1,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 108:
            printf("The element is Hassium.\n");
            printf("The element's symbol is Hs.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d6,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 109:
            printf("The element is Meitnerium.\n");
            printf("The element's symbol is Mt.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d7,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 110:
            printf("The element is Darmstadtium.\n");
            printf("The element's symbol is Ds.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d9,7s1.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 111:
            printf("The element is Roentgenium.\n");
            printf("The element's symbol is Rg.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d10,7s1.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        case 112:
            printf("The element is Copernicium.\n");
            printf("The element's symbol is Cn.\n");
            printf("The element electronic configuration is 1s2,2s2,2p6,3s2,3p6,3d10,4s2,4p6,4d10,5s2,5p6,4f14,5d10,6s2,6p6,5f14,6d10,7s2.\n");
            printf("The element belong to 7th period.\n");
            printf("The element belong to 6d series.\n");
            printf("The element belong to 4rd transition series.\n");
            printf("This is radioactive element.\n");
            break;
        
        default://if the atomic number not matches any case.
            printf(">>> Wrong atomic number entered.Please check the note first.\n");
    }
    
    }
    
    }
    if(m==2){                              // Displays D block elements
        printf("******D BLOCK ELEMENTS******\n");
        printf(" Sc Ti V  Cr Mn Fe Co Ni Cu Zn   >>1st Transition Series \n");     //1st Transition Series
        printf(" Y  Zr Nb Mo Tc Ru Rh Pd Ag Cd   >>2nd Transition Series\n");     //2nd Transition Series
        printf(" La Hf Ta W  Re Os Ir Pt Au Hg   >>3rd Transition Series\n");     //3rd Transition Series
        printf(" Ac Rf Db Sg Bh Hs Mt Ds Rg Cn   >>4th Transition Series\n");     //4th Transition Series
    }
    
    printf("\nProgram done by Aarya Dubey ");//Author Name
    printf("\nRoll number:- Y22170801");//Author Roll Number
    printf("\n");
    
    return 0;
}
