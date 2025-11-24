# doctor2
c


#include <stdio.h>


struct Doctor {
    char name[50];
    char specialist[50];
    char qualification[50];
    long long contact;
};


int main() {


    printf("Searching doctor in pune\n");
    
    struct Doctor d1 = {
        "Dr_Sharma",
        "Surgeon",
        "MBBS_MD",
        9876543210LL
    };
    
    struct Doctor d2 = {
        "Dr_kulkarni",
        "Surgeon",
        "MBBS",
        9123456780LL
    };


      printf("Doctor found\n");
      
   printf("-----1.Doctor  Information -----\n");
    printf("Name: %s\n", d1.name);
    printf("Specialist: %s\n", d1.specialist);
    printf("Qualification: %s\n", d1.qualification);
    printf("Contact Number: %lld\n", d1.contact);
   printf("Location: Karvenagar ,pune");
    printf("----- 2.Doctor  Information -----\n");
    printf("Name: %s\n", d2.name);
    printf("Specialist: %s\n", d2.specialist);
    printf("Qualification: %s\n", d2.qualification);
    printf("Contact Number: %lld\n", d2.contact);
printf("Location:warje, pune");
    return 0;
}
