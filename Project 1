#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    srand(time(0)); // Seed the random number generator 
    int player, computer = rand() % 3; // Random number between 0 and 2    
    /*
        0 --> Snake
        1 --> Water
        2 --> Gun
        
        Rules:
        - Snake (0) beats Water (1)
        - Water (1) beats Gun (2)
        - Gun (2) beats Snake (0)
    */
    printf("Enter 0 for Snake, 1 for Water, or 2 for Gun: \n");
    scanf("%d", &player);
    
    printf("Computer chose: %d\n", computer);

    if (player == 0 && computer == 0) {
        printf("It's a tie!\n");
    } else if (player == 0 && computer == 1) {
        printf("You win! Snake drinks Water.\n");
    } else if (player == 0 && computer == 2) {
        printf("Computer wins! Gun kills Snake.\n");
    } else if (player == 1 && computer == 0) {
        printf("Computer wins! Snake drinks Water.\n");
    } else if (player == 1 && computer == 1) {
        printf("It's a tie!\n");
    } else if (player == 1 && computer == 2) {
        printf("You win! Water damages Gun.\n");
    } else if (player == 2 && computer == 0) {
        printf("You win! Gun kills Snake.\n");
    } else if (player == 2 && computer == 1) {
        printf("Computer wins! Water damages Gun.\n");
    } else if (player == 2 && computer == 2) {
        printf("It's a tie!\n");
    } else {
        printf("Invalid input!\n");
    }
    
    return 0;
}
