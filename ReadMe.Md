def cal_kc(t , T=120):
    temp = t/T
    kc= 8.5*pow(temp , 5) -15.2*pow(temp,4)+9.1*pow(temp,3)-4.6*pow(temp ,2)+2.8*temp +0.7
    return kc
