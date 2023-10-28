class Solution {
    public int titleToNumber(String columnTitle) {
        int res = 0;
        for(int i = columnTitle.length()-1; i>=0;i--){
            char c = columnTitle.charAt(i);
            int pow = Math.abs(i-columnTitle.length()+1);
            res+=(c-64)*Math.pow(26, pow);
        }
        return res;
    }
}
