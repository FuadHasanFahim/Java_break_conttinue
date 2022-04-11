# Java_break_conttinue

# Java Break

**Syntax**

for (int i = 0; i < 10; i++) {

  if (i == 4) {
  
     break;
     
  }
  
  System.out.println(i);
  
}

# Java Continue

**Syntax**

for (int i = 0; i < 10; i++) {

  if (i == 4) {
  
    continue;
    
  }
  
  System.out.println(i);
  
}

# Break and Continue in While Loop

**Break Example**

int i = 0;

while (i < 10) {

  System.out.println(i);
  
  i++;
  
  if (i == 4) {
  
    break;
    
  }
  
}

**Continue Example**

int i = 0;

while (i < 10) {

  if (i == 4) {
  
    i++;
    
    continue;
    
  }
  
  System.out.println(i);
  
  i++;
  
}
