# Laura Muslioska 213197
CFG

![image](https://github.com/LauraMuslioska/SI_2023_lab2_213197/assets/129580380/751fa98e-f91e-4c66-8337-06997304d818)


 Цикломатската комплексност
Цикломатската комплексност на дадениот код е 11, ја добив на тој начин што ги броев сите предикатни јазли и на тој број додавам плус еден(+1), исто така за да ја потврдам таа бројка од кога го нацртав CFG за дадениот код имаше 10 региони вкупно +1, знаци исто се добива 11;

Multiple Condition
if (user==null || user.getPassword()==null || user.getEmail()==null)
 тест случаи
 FXX (null,’’,’’) значи моментот кога само user е null значи  дека  барем еден услов е исполнет бидејќи го имаме ‘или’ операторот, а другите не се битни како се исполнети поради тоа што ние ниту продолжуваме нив да ги провериме ; 
TFX (user,null,””), тука првиот тест пример поминува, но pass е null  и тука како погоре што напоменав не продолжува со проверка доколку се појави еден со null т.е првото е точно Т, второто е null F, и другото може да биде што било;
TTF  (user,pass,null) првите две имаат точни вредности, а за последното имаме грешка вреднот или во некој случај не ни е и битно;
TTT последниот случај ни е кога ги имам сите точни вредноости ;
