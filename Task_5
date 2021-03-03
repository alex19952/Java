package com.company;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner cin = new Scanner(System.in);
        String str = cin.nextLine();

        for (int i = 0; i < str.length(); ) {
            String str2 = "";
            if (str.charAt(i) >= 65 & str.charAt(i) <= 90) {
                str2 += str.charAt(i);
                i++;
            }
            while (i < str.length() && str.charAt(i) < 65 | str.charAt(i) > 90) {
                str2 += str.charAt(i);
                i++;
            }
            System.out.println(str2);
        }
    }
}
