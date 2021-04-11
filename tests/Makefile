# Κάνοντας compile το <foo>_test.c με μια υλοποίηση <foo>.c του
# συγκεκριμένου τύπου, παράγουμε ένα tets για την υλοποίηση αυτή.

# Υλοποιήσεις μέσω dynamic array: ADTVector
#
UsingDynamicArray_ADTVector_test_OBJS = ADTVector_test.o $(MODULES)/UsingDynamicArray/ADTVector.o

# Υλοποιήσεις μέσω ADTMap: ADTVector
#
UsingADTMap_ADTVector_test_OBJS = ADTVector_test.o $(MODULES)/UsingADTMap/ADTVector.o $(MODULES)/UsingADTSet/ADTMap.o $(MODULES)/UsingAVL/ADTSet.o

# Υλοποιήσεις μέσω BinarySearchTree: ADTSet
#
UsingBinarySearchTree_ADTSet_test_OBJS = ADTSet_test.o $(MODULES)/UsingBinarySearchTree/ADTSet.o

# Ο βασικός κορμός του Makefile
include ../common.mk