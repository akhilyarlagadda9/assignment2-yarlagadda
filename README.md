# assignment2-yarlagadda

# Akhil Babu Yarlagadda

###### MALDIVES

It is not cheap or easy to reach, but this isolated paradise between the **Arabian and Laccadive seas** is the personification of a dreamy tropical vacation. In this **South Asian** destination, which is made up of more than **1,000 islands**, thatched-roof bungalows sit above crystal-clear aquamarine waters, providing easy water access and a romantic atmosphere. 

## ORDERED LIST OF TRAVEL INFORMATION
1. Get a cab in Maryville to Kansas Airport
    1. You could book cab using uber app from Maryville
    2. Cab charge to the airport will be $40
2. Take a flight from Kansas(MCI) to FRANCE(FNS)
    1. Air France Airlines are flexible with the timings
        1. Charge of the ticket will be around $500
    2. You can get cheap charges when you book before
3. From France take flight to India Capital Chennai
    * In Chennai Buy some Food/Drinks for Enjoyment
        * Food Needed
            * Sambar Rice (Very Special in chennai)
            * Rotis
            * Curd Rice
            * Dosa
        * Drinks Mandatory
            * Coke
            * Jucies
            * Lassy
4. From Chennai go to the Maldives by car
 

**[Document](AboutMe.md)**


---
# RECOMMENDED FOODS - BARBECUE AND BEYOND


Food/Drink  | Location   | Price
----------- | ---------- | -----

Burger      | Joseph     | $ 9.50
KFC         | Maryville  | $ 6.00
Dominos     | Maryville  | $ 7.50

# Pithy Quotes
> "A dream is not that which you see while sleeping, it is something that does not let you sleep."
> *- APJ ABDUL KALAM*

> "Excellence happens not by accident. It is a process."
> *- Sir C.V. RAMAN*


# String Processing
> In mathematics, the Z function is a function used for studying the Riemann zeta function along the critical line where the argument is one-half. It is also called the Riemann–Siegel Z function, the Riemann–Siegel zeta function, the Hardy function, the Hardy Z function and the Hardy zeta function. It can be defined in terms of the Riemann–Siegel theta function and the Riemann zeta
(https://en.wikipedia.org/wiki/Z_function)

```
vector<int> z_function_trivial(string s) {
    int n = (int) s.length();
    vector<int> z(n);
    for (int i = 1; i < n; ++i)
        while (i + z[i] < n && s[z[i]] == s[i + z[i]])
            ++z[i];
    return z;
}
```

[Link](https://cp-algorithms.com/string/z-function.html)