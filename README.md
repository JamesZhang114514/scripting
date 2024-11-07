#!/bin/bash
echo "Welcome to this script!"
echo "Please select an option"
echo "1. Option 1"
echo "2. Option 2"
echo "3. Option 3"
echo "4. Option 4"
echo "5. Option 5"
echo "6. Option 6"
echo
echo "Enter your choice (1-6):"
read -r choice
case $choice in
    1)
        echo "You chose Option 1: [Add your custom response here]"
        ;;
    2)
        echo "You chose Option 2: [Add your custom response here]"
        ;;
    3)
        echo "You chose Option 3: [Add your custom response here]"
        ;;
    4)
        echo "You chose Option 4: [Add your custom response here]"
        ;;
    5)
        echo "You chose Option 5: [Add your custom response here]"
        ;;
    6)
        echo "You chose Option 6: [Add your custom response here]"
        ;;
    *)
        echo "Invalid input. Please try again."
        ;;
esac
