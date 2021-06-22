# Swap_Case
def swap_case(s):
    s1=""
    for i in range(len(s)):
        if s[i].isupper():
            s1+=s[i].lower()
        elif s[i].lower():
            s1+=s[i].upper()
        else:
            s1+=s[i]        
    return s1

if __name__ == '__main__':
    s = input()
    result = swap_case(s)
    print(result)
