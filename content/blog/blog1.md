---
title: "Hello World: My first Blog"

date: "2021-10-31"

tags: ["hello world"]


#links:
    #website: 'https://github.com/hadisinaee/avicenna'
    #alias: link_name_here
---

{{< table_of_contents >}}

# Header `I`

+ Hello World: Code Block.

  ```c++
  #include<iostream>
  using namespace std;
  int main()
  {
      cout << "Hello World!" << endl;
  	return 0;
  }
  ```

+ Hello World: equation
  $$
  A = B*C \tag{1}
  $$

+ Hello World: pictures

  ![](blog1.assets/image-20211031095456052.png)

  + Note for pictures:
  	+  I need to move the picture folder to the same directory of html. Example:
  
  	```
  	# In the root path of our page_generator project:
  	$ mv public/blog/blog1.assets public/blog/blog1/ 
  	```
  	
  	+ Or maybe I could set up a specific repositories to save all my pictures online. 

# Header `II`

+ ​	Null.

