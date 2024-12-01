class Solution:
    def isIsomorphic(self, s: str, t: str) -> bool:
        my_dict = {}
        for i,j in zip(s,t):
            if my_dict.get(i) == None and j not in my_dict.values():
                my_dict[i] = j
            if my_dict.get(i) == None and j in my_dict.values():
                return False
            elif my_dict.get(i) != None and my_dict.get(i) != j:
                return False
        return True
