Shell 数组
=====
* 获取数组中的所有元素

  使用@ 或 * 可以获取数组中的所有元素，例如：

  \#!/bin/bash

  \# author:菜鸟教程

  \# url:www.runoob.com

  my_array[0]=A

  my_array[1]=B

  my_array[2]=C

  my_array[3]=D

  echo "数组的元素为: ${my_array[*]}"

  echo "数组的元素为: ${my_array[@]}"
* 获取数组长度

  echo "数组元素个数为: ${#my_array[*]}"
  
  echo "数组元素个数为: ${#my_array[@]}"
