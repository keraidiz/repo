# **Описание работы класса SalesManager**

#### Вызов объекта класса *SalesManager* в классе *Main* с параметром в виде целочислительного массива:

>SalesManager salesManager = new SalesManager(new int[] {45, 725, 90}); 


#### Метод *int max()* позволяет определить максимальное значение задаваемых чисел.
````
public int max() {
  int max = -1;
      for (int sale : sales) {
      if (sale > max) {
      max = sale;
   }
}
  return max;
}
````
#### Вызываем данный метод в классе *Main*:
````
salesManager.max();
````
#### Выводим результат на консоль: 
````
 System.out.println(salesManager.max());
````


