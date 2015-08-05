# recursive
递归

int jiecheng(int n)     //递归阶乘
{
    if (n == 0 || n == 1) {
        return 1;
    }
    int s = 1;
    s = n*jiecheng(n-1);
    
    
    return  s;
}
int main(int argc, const char * argv[]) {
   
    
    
    printf("%d\n",jiecheng(5));
    
    
    return 0;
}
