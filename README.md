# HALF_ADDER
# Aim
To Study and Verify Half Adder using vivado.
# Apparatus Required
Personal Computer with Vivado Software.
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# Program
```
module Half_adder(a,b,sum,carry);
input a,b;
output sum,carry;
xor g1(sum,a,b);
and g2(carry,a,b);
endmodule
```
# Output
![image](https://github.com/karanpro06/HALF_ADDER/assets/119782103/337cd8db-1547-4543-8b55-064bcc8986d9)
# Result
Hence Half adder program is verified.
