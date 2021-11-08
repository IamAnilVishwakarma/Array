# Array
Array related to solved program.

package com.company;
public class Main{
    public static void main(String[] args) {

        int arr[] = {100, 20, 30, 40, 50, 15, 9, 2};
        int min = arr[0];
        int max = arr[0];

        for (int i = 1; i < arr.length; i++) {
            if (arr[i] < min) {
                min = arr[i];
            }
            else if (arr[i] > max){
                max = arr[i];
            }
        }

        System.out.print(" mininmum " + min + " maximum " + max);
    }
