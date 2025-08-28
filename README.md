int main(){
  float unit;
  printf("enter unit : ");
  scanf("%f",&unit);
  if(unit>=0 && unit<100){
      printf("price : %f",5*unit);
  }
  else if (unit>=100 && unit<200){
      printf("price : %f",6*unit);
  }
  else if (unit>=200 && unit<300){
      printf("price :%f",7*unit);
  }
  else {
      printf("price :%f",8*unit);
  }
}
