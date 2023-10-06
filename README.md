# Control-System  

![image](https://github.com/kangjunhyeong/Control-System/assets/144297425/91330f69-fd4c-45f6-a0ad-4c7e6758de5f)  

$$
\\frac{{V_a - V_1(s)}}{R} + \frac{{V_a - V_2(s)}}{\frac{1}{sC}} = 0\
$$

여기서 

$$
V_a = V_b = 0\
$$

이므로

$$
\-\frac{V_{1}(s)}{R}  -\frac{V_{2}(s)}{\frac{1}{sC}} = 0\
$$

정리하면  

$$
\frac{V_{2}(s)}{V_{1}(s)} = -\frac{1}{RCs}\
$$

![image](https://github.com/kangjunhyeong/Control-System/assets/144297425/3f5d6808-7034-4a8f-a820-fc501004331a)  

$$
\ Y(s) = R(s) \cdot \frac{1}{s + 50} \
$$

이 때 r(t)=unit step이므로  

$$
\ r(t) = 1 \ , \ R(s) = \frac{1}{s} \
$$  

그러므로 식은 다음과 같이 정리된다.  

$$
\ Y(s) = \frac{K}{s(s+50)} \
$$

그리고 y(t) → 1 일 때 \( t \rightarrow \infty \)

$$
\ \lim_{{t \to \infty}} y(t) = \lim_{{s \to 0}} sY(s) \
$$
