static int Array[20]; 
for(int i = 0; i < sizeof(Array); i++) Array[i] = rand() % 100;
for(int i = 0; i < sizeof(Array); i++) printf("%d\n", Array[i]);